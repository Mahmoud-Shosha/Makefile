T = touch

otherfiles = myfile myotherfile
buildfiles = myfile2

all: $(buildfiles)

myfile:
	$(T) $@

myotherfile:
	$(T) $@

myfile2: $(otherfiles)
	cat $^ > $@

clean:
	$(RM) myfile
	$(RM) myotherfile
	$(RM) myfile2