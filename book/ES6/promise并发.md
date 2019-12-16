# promise并发

* promise.all -->并发请求且都resolve后执行回调，缺点：短路特性,一个请求reject导致整个状态reject
* primise.race -->并发请求有一个resolve后执行回调，缺点：短路特性,一个请求reject导致整个状态reject
* promise.allSettled -->并发请求且都状态完成（或resolve或reject）后执行回调


