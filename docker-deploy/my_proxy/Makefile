TARGETS=proxy
all: $(TARGETS)
clean:
	rm -f $(TARGETS)
proxy: proxyDaemon.cpp
	g++ -pedantic -Wall -pthread -lpthread -std=gnu++11 -o my_proxy proxyDaemon.cpp
