CC=cc
CFLAGS=-dynamic ${PYTHON_INCLUDE_OPTS}
LDFLAGS=-L/work/y07/y07/cse/python/2.7.6/lib -lpython2.7

taskfarm: taskfarm.c 
	$(CC) $(CFLAGS) -o $@ $^ $(LDFLAGS)

