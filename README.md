# Introduction

I am a data architect and full stack engineer with an interest (and a [Master's degree](https://www.si.umich.edu/programs/master-applied-data-science)) in data science.  

My personal GitHub repositories are pushed to the [FAR Analytics & Research](https://github.com/faranalytics) GitHub organization. Examples of my work can also be found in the respositories of the [Educational Technology Collective](https://github.com/educational-technology-collective).

## Select public respositories that I have contributed to.
* [Socketnaut](https://github.com/faranalytics/socketnaut) Scalable multithreaded Node.js servers made easy.
* [Port Agent](https://github.com/faranalytics/port_agent) A RPC-like facility for making inter-thread function calls.
* [Network⬄Services](https://github.com/faranalytics/network-services) A type safe asynchronous RPC Service facility for connecting your apps to the network.
* [memoir](https://github.com/faranalytics/memoir) A type-checked asynchronous logging facility with a simple and familiar interface.
* [Python memoiz](https://github.com/faranalytics/python_memoiz) A thread-safe memoization decorator for Python.
* [elemental-0](https://github.com/faranalytics/elemental-0) A synchronous dynamic HTML generator that will run on the client or the server.
* [JupyterLab Telemetry](https://github.com/educational-technology-collective/etc_jupyterlab_telemetry_library) A JupyterLab extension for capturing [JupyterLab](https://jupyter.org/) events deployed to the [Coursera](https://www.coursera.org/) learning environment.

## Featured Projects

### [Socketnaut](https://github.com/faranalytics/socketnaut)
<img src="transport.svg" style="width:50%" align="right">Socketnaut makes scaling native Node.js servers easy.  A Socketnaut **Service** consists of a TCP proxy and a pool of HTTP servers.  Socketnaut will uniformly distribute incoming TCP sockets across the pool of allocated servers.  This strategy allows for both distribution and parallel processing of incoming requests.  Socketnaut consumes native Node.js servers (e.g., `http.Server`, `https.Server`, `net.Server`, `tls.Server`); hence, if you know the [Node API](https://nodejs.org/docs/latest-v18.x/api/http.html), you already know how to build applications on Socketnaut.

Socketnaut can be combined with performant Node.js web application frameworks (e.g.,[ Fastify](https://fastify.dev/), [Koa](https://koajs.com/), [Express](https://expressjs.com/)) in order to easily scale the main module of the web application.

A single Socketnaut instance can handle thousands of *concurrent* connections when running on capable hardware.  When under load, Socketnaut will spawn HTTP servers in order to meet demand and release resources as demand declines; hence, Socketnaut mitigates its memory footprint by effectively managing its thread pool.

### [Network⬄Services](https://github.com/faranalytics/network-services)
Network-Services provides a simple and intuitive toolkit that makes connecting your app to the network easy. You can use Network-Services to transform your application into a network connected [Service Application](https://github.com/faranalytics/network-services#service-app). You can connect to your Service App, from the same process or another process, and call methods on it using a type-safe [Service API](https://github.com/faranalytics/network-services#service-api).

### [Port Agent](https://github.com/faranalytics/port_agent)
Port Agent provides a simple and intuitive interface that makes inter-thread function calls *easy*.  Port Agent will marshal the return value or `Error` from the other thread back to the caller.  The other thread may be the main thread or a worker thread.

## Links
- [Educational Technology Collective](https://edtech.labs.si.umich.edu/)
- [FAR Analytics & Research](https://github.com/faranalytics)
- [LinkedIn](https://www.linkedin.com/in/adpatter/)

## Notes
```bash
git reset --mixed $(git log --pretty=format:"%h" | tail -n -1) && git status && git add . && git commit -m 'more' && git push --force
```