# Web-Server-using-C
Multi Threaded Proxy Server with and without Cache


How did we implement Multi-threading?
# Used Semaphore instead of Condition Variables and pthread_join() and pthread_exit() function.
# pthread_join() requires us to pass the thread id of the the thread to wait for.
# Semaphore’s sem_wait() and sem_post() doesn’t need any parameter. So it is a better option.
