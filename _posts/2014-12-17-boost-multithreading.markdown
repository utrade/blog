---
layout: post
title:  "Boost Multi-threading with C++"
date:   2014-12-17 13:41:49
categories:
---

Boost libraries (Boost.Thread) provide an easy implementation for multi-threading applications in C++.
Code is portable on different OS platforms. Three basic code examples are discussed below for a kick start on use of these libraries.
Last example also shows the use of mutex.
On Linux, it uses pthreads underlying. So it can be thought of pthreads wrapped in C++ style objects. BOOST library provides different ways to use locks also.

[Here][boost] is the official link.

Example-1 : Basic Multi-threading

This simple example spawns two threads. Callback function for each thread is invoked.

    #include <boost/thread.hpp>
    void readerApi()
    {
      for (int i=0; i < 10; i++) {
        usleep(400);
        std::cout << "readerApi: " << i
		  << std::endl;
      }
    }
    void writerApi()
    {
      for (int i=0; i < 10; i++) {
        std::cout << "writerApi: " << i
                  << std::endl;
        usleep(400);
      }
    }

    int main()
    {
      boost::thread readerThread(readerApi);
      boost::thread writerThread(writerApi);

      readerThread.join();
      writerThread.join();
    }


[boost]: http://www.boost.org/doc/libs/1_49_0/doc/html/thread.html

