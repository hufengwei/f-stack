SUBDIRS=compat libutil libmemstat libxo sysctl ifconfig route top netstat

all:
	for d in $(SUBDIRS); do ( cd $$d; $(MAKE) all ) ; done

clean:
	for d in $(SUBDIRS); do ( cd $$d; $(MAKE) clean ) ; done
