# everything-and-more
## Threads
- [ ] Lazy Threads
- [ ] How do you know communications between threads are acknowledged by each other
- [ ] CSP - Communicating Sequential Processes (*Golang channels*)
- [ ] Busy wait and weight lock
- [ ] Run level (0,2,3,4,5)
    - [ ] Switch between run levels and init config
- [ ] How does a crashed app get restarted by *init process*
- [ ] How do *daemons* stay up? How are they revived if killed?
- [ ] Login threads and processes - what happens from startup to login screen?
    - [ ] *Login Manager* (runs at root) -> privileges because it has access to credentials
    - [ ] Privilege change (occurs at root)
    - [ ] Login (*fork call* for spawning processes and exec call)
- [ ] Kernel space vs User space during login and boot up
- [ ] Exec replaces a running process with image of process to change it
- [ ] How are child processes and child daemons linked to each other
- [ ] Dynamically linked libraries and statically linked libraries
- [ ] [[Intel vs M-Series]]
  ## Networking
- [ ] ICMP
- [ ] Public vs Private IPs
- [ ] Routing table - path length calculation
    - [ ] Multiple links in routing
    - [ ] How 'lookup' works - the bits required for *lookup* [*routing algorithms*]
- [ ] TCP priority -> how time sensitive/important data has priority defined to drop a TCP packet that is not high priority
    - [ ] Cannot fool a router
    - [ ] How do routers know priority
- [ ] ICMP block
- [ ] OSI in theory has clear separation, but in reality has overlap. Why?
- [ ] TCP algorithms - TAHOE, RENO, FastStart etc.
- [ ] HTTP/3 - UDP algorithm - *Quic*
- [ ] TLS (SSL)
- [ ] Public key cryptography
- [ ] Keep-alive - overhead of creating new connection avoided (HTTP/1.1)
- [ ] *2616 HTTP/1.1 RFCs -> IETF publishes*
- [ ] Bandwidth and latency not related (slow-start algorithm example)
- [ ] sll, dll, AOT and JIT, .NET in JIT
- [ ] C being commonality between most HLL
## Garbage Collector
- [ ] Working
- [ ] Types
    - [ ] *Pause the world*
    - [ ] *Pauseless (AZUL)*
- [ ] Stack vs Heap memory
    - [ ] *Stacktrace*
- [ ] *Class bytecode* modification (Java)
- [ ] Maximum arguments passed to a method in Java
- [ ] No compaction in C/C++ and can be manually changed
- [ ] graalvm - no garbage collection
- [ ] *Reference object* - pointer in Java -> moves locations without programmers knowing (because C/CPP has pointers but java doesn't)
- [ ] Mark, sweep and compaction (GC)
## Databases
- [ ] Secret Store
- [ ] Facebook 2018 pen-testing environment
- [ ] Authentication and authorization
- [ ] Database isolation
- [ ] Pushing Boundaries or a program - reading some other program's boundaries (can access passwords etc.)
- [ ] Showsql in config (debugging-tasks, ex5)
- [ ] Why are regexes slow (with regard to databases)
- [ ] More clauses slowing down because stash memory
- [ ] Issue with using LIKE statements - SQL databases
- [ ] Postgis vs Postgres (postgres + geospatial queries)
- [ ] Log4sj vs SL4J
- [ ] OWASP top 10 issues (CORS)
- [ ] CSRF if CORS not implemented correctly
- [ ] SQL Sanitation
- [ ] Encode and Sanitation of strings to avoid SQL injection
- [ ] Clickhouse DB and other analytical databases
- [ ] [Following a database read to the metal](https://medium.com/@hnasr/following-a-database-read-to-the-metal-a187541333c2)
## JVM + Kotlin
- [ ] Beans
- [ ] Configurations + Annotations in JVM
- [ ] Comparators
- [ ] [Coroutines](https://blog.rockthejvm.com/kotlin-coroutines-101/)
- [ ] Specific data types for money - BigDecimal
    - Don't use constructor - always use string method
- [ ] Composition, Aggregation and Assocation
- [ ] Declarative Programming
    - [ ] With reference to infix functions, inline functions
    - [ ] Higher order functions
    - [ ] Functional Programming
- [ ] Generic types
- [ ] Reified types
- [ ] [Building REST-ful APIs using Micronaut](https://itnext.io/building-restful-apis-with-micronaut-98f4eb39211c)
## Docker
- [ ] How does docker check health of its containers
