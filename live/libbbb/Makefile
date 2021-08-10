CC=g++
INC+= -I ../UsageEnvironment/include 
INC+= -I ../groupsock/include 
INC+= -I ../liveMedia/include 
INC+= -I../BasicUsageEnvironment/include

LIB+= ./lib/libBasicUsageEnvironment.a
LIB+= ./lib/libgroupsock.a
LIB+= ./lib/libliveMedia.a
LIB+= ./lib/libUsageEnvironment.a





main : main.cpp
	$(CC) -L.  $(INC) -o $@ $< $(LIB)

clean: main
	rm $^
