## Clean Code Practices
- [ ] Replacement for for loops, forEach (Higher Order Functions)
    -  Iterator, Filter
- [ ] Enum usage with String
- [ ] [Refactoring Guru](https://refactoring.guru)
- [ ] [Gilded Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/main/GildedRoseRequirements.md)
    - [Gilded Rose GUIDE (Kotlin)](https://www.youtube.com/watch?v=AxxNHKCldzA)
- [ ] Big Ball of Mud Architecture
- [ ] Composition in use for extending classes
- [ ] Mocking tests use (no using *repeat* methods - code smell)
- [ ] Essential Complexity, Accidental Complexity and Incidental Complexity
- [ ] [Object Calisthenics](https://williamdurand.fr/2013/06/03/object-calisthenics/)
- [ ] Tell - Don't Ask Principle
- Design Patterns
    - *Singleton*
    - Factory
    - Abstract Factory
    - **Decorator** 
	- **Facade** - API
    - Adaptor - dependency inversion
    - Iterator 
	- **Strategy**
    - **Composite**
    - **Proxy** - similar to decorator; caching proxy
    - Chain of Responsibility 
	- **Observer** - Hollywood principle; async await; reactive frameworks; promises and futures
    - State
- [ ] Type alias
- [ ] Defensive code - sometimes good, sometimes bad.
- [ ] Uncle Bob refactoring and clean code principles
- [ ] Spy on a method for testing it
- [ ] Use annotations wherever possible for validation
- [ ] Inversion of Control
    - Constructor injection
- [ ] [No objects ending with 'er'](https://objology.blogspot.com/2011/09/one-of-best-bits-of-programming-advice.html)
- [ ] [Clean Code Blog - Uncle Bob](https://blog.cleancoder.com/uncle-bob/2021/03/06/ifElseSwitch.html)
## Functional Programming
- [ ] Monadic Functions
- [ ] Currying - Scala/Haskell
- [ ] Traits - Scala
## Practices
- [ ] MockK > Powermock
- [ ] Custom exceptions - how to use them in test cases
## CI-CD
- [ ] Canary Deployment
- [ ] Are dependencies included in deployable jar file
- [ ] Why can't you ship with build tools - build tool cannot use runtime ; maintenance
- [ ] Run without using gradle (just the jar file)
- [ ] Auto-scaling multiple instances.- RDS, EX2, Load balancer
- [ ] How to deal with failure during release
- [ ] Branched development vs Trunk development
- [ ] Regression tests during CI
- [ ] Artifact generated at the end of pipeline or before deployment
- [ ] CI-level artifact
- [ ] AMI - Artifact
- [ ] Configs inside artifact
- [ ] Config file versioning - is it necessary to version a config file
- [ ] How is it related to the Code version
- [ ] Hotfix
- [ ] Making pipelines for hotfix
- [ ] Self-Service pipeline flow
- [ ] [12 factor](https://12factor.net/)
- [ ] Decoupling deployment from release (feature toggling and feature planning)
- [ ] Feature toggling
    - Facebook canary deployment using employees
    - Region-specific feature
    - How GitHub did CD while also doing feature toggling
- [ ] Plan stories according to being able to toggle features
    - Natural ways to do it - never call the function
- [ ] Branch by abstraction
- [ ] Blue-green deployment
    - Requires monitoring if you're using load balancer
- [ ] Zero-downtime releases
- [ ] How to run without gradle? 
- [ ] Download kafka and experiment
- [ ] pre commit hooks
- [ ] Read Agile manifesto
- [ ] Check gradle lifecycle tasks
- [ ] Check out different artifact registry 
- [ ] How to differentiate between steps and jobs while writing a yml file for github actions?
- [ ] Pipeline parameter
- [ ] different kinds of feature toggling
- [ ] learn about branch by abstraction 
- [ ] Decouple Deployment from Release
- [ ] There are different types of deployment like conary and (green and blue)
## System Design
- [ ] Dependency Inversion
    - Adaptor class or Anti-corruption layer
## Discovery
- [ ] Macro and Micro factors influencing environment
- [ ] Code -> Product -> Business -> Market -> Environment
- [ ] DEPEST
- [ ] Keeping up with trends - [Atari example](https://www.youtube.com/watch?v=F_kEhHAMupU)
- [ ] [The best design is the one that goes live](https://www.zeuxinnovation.com/articles/the-best-design-is-the-one-that-goes-live/)
- [ ] [Root causes of product failure](https://www.youtube.com/watch?v=9dccd8lihpQ)
- [ ] Business model canvas
- [ ] Understand revenue streams - model around consumers and product
- [ ] Digital business models
- [ ] Competition - direct, indirect, replacement competition
- [ ] Solutioning vs Consultancy
- [ ] Product vs solution
    - Solution - long term (ideating one that is aligned with business - can also just be marketing or advertising)
    - Product - here and now
- [ ] Empathy
    - Empathetical user research to identify different personas in the ecosystem
    - Clear distinction between segments and personas
    - Need to understand context so you discover how to enable a user, leverage their treats (fuckall in b2b side, clearer in b2c)
    - Desk research
    - Primary research (physically discovering where problem exists) (have more conversations with users etc to get context)
- [ ] Journey Led Thinking
    - Make a customer journey map - end to end experience of customer can have many experiences that have their own touch points and corresponding customer thoughts.
    - Wherein your solution may play a small or big role. Vistara example.
    - Touchpoint - what the customer comes in contact with; some touchpoints can be owned by the business or partner but some are not but that still plays a role with user's experience
- [ ] Continuous discovery/Continuous Iteration
    - Constantly thinking, innovating, keeping up with market trends etc while creating a product - even with regard to the MVP
    - Ask questions based on your assumptions to get clarity
    - Implement, get feedback, change
    - Keep up with market trends
- [ ] Business alignment
    - Intent
        - Do they want to experiment
        - Do they want a long-term solution
        - Are they traditional
        - Do they want maintainable SW
        - Buy in, Trial, Journey, Blue Sky
    - Cultural dimension
    - Tech maturity
    - Technology journey
    - Stakeholders
    - Understanding Personas
    - Dependencies
# Books to Read
1. [HeadFirst Design Patterns](https://github.com/ajitpal/BookBank/blob/master/%5BO%60Reilly.%20Head%20First%5D%20-%20Head%20First%20Design%20Patterns%20-%20%5BFreeman%5D.pdf)
2. HeadFirst OOAD
3. Grady Booch OOAD
4. [BookBank](https://github.com/ajitpal/BookBank/tree/master)
5. Database Internals
6. Domain Driven Design
7. Clean Code - Robert Martin
8. Kubernetes in action
9. Domain Driven Design (https://github.com/lafengnan/ebooks-1/blob/master/xx735.Eric.Evans.Domaindriven.Design.Tackling.Complexity.in.the.Heart.of.Software.pdf) 
10. https://www.goodreads.com/list/show/119285.Sahaj_Software_Reading_list
11.  
# Sent by Mentors
- [ ] [Idea Keymaps](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
- [ ] [UUID vs ULID](https://medium.com/@sammaingi5/uuid-vs-ulid-how-ulid-improves-write-speeds-d16b23505458#:~:text=For%20example%2C%20ULIDs%20are%20more,work%20with%20in%20certain%20situations.)
- [ ] [How we built Pingora, the proxy that connects Cloudflare to the Internet](https://blog.cloudflare.com/how-we-built-pingora-the-proxy-that-connects-cloudflare-to-the-internet/)
- [ ] [ScyllaDB Internals](https://www.youtube.com/watch?v=AqY13RjWwJg&t=1375s)
- [ ] [SeaStar](https://seastar.io)
- [ ] [Thread per Core Architecture](https://drive.google.com/file/d/1EJHkuxRJMxK_yFQpUftKW8LaFr2SQDSC/view)
- [ ] [In memory columnar data structures](https://entzik.medium.com/a-case-for-in-memory-columnar-data-structures-44ddb20c2c69)
- [ ] [Why single-threaded Redis is fast](https://levelup.gitconnected.com/4-reasons-why-single-threaded-redis-is-so-fast-414e0106f921)
- [ ] [TraceRoute](https://www.fortinet.com/resources/cyberglossary/traceroutes)
- [ ] [Reading TraceRoute results](https://www.varonis.com/blog/what-is-traceroute)
- [ ] [Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP#invention_of_the_world_wide_web)
- [ ] [SO_REUSE in TCP](https://blog.flipkart.tech/linux-tcp-so-reuseport-usage-and-implementation-6bfbf642885a)
- [ ] [Journey of a request to the backend](https://medium.com/@hnasr/the-journey-of-a-request-to-the-backend-c3de704de223)
- [ ] [Refactoring](https://refactoring.guru)
- [ ] [OOPS](https://www.coursera.org/learn/concepts-of-object-oriented-programming/home/week/1)
- [ ] [TTD](https://www.youtube.com/watch?v=qmS4ojQ1Pa8)
- [ ] [Clean Code Blog](https://blog.cleancoder.com/uncle-bob/2014/05/14/TheLittleMocker.html)
- [ ] [Refactoring](https://kata-log.rocks/tdd)
- [ ] [Object Calisthenics](https://williamdurand.fr/2013/06/03/object-calisthenics/)
# Extras (Courtesy of Dheeraj)
- [ ] [Why Stack so fast](https://www.youtube.com/watch?v=N3o5yHYLviQ)
- [ ] [Exploring CoRoutines](https://www.youtube.com/watch?v=jT2gHPQ4Z1Q)
- [ ] [Database Internals](https://github.com/Akshat-Jain/database-internals-notes)
- [ ] [Booknotes (Java, Architecture, System Design, General)](https://github.com/preslavmihaylov/booknotes)
- [ ] [Domain Specific Languages](https://www.jetbrains.com/mps/concepts/domain-specific-languages/)
- [ ] [Configure 2 GitHub Accounts with SSH](https://gist.github.com/rahularity/86da20fe3858e6b311de068201d279e3)
- [ ] [Kotlin Series by JetBrains](https://www.youtube.com/playlist?list=PLlFc5cFwUnmyDrc-mwwAL9cYFkSHoHHz7)
- [ ] [64 bit integers vs 16 bit integers](https://softwareengineering.stackexchange.com/questions/411128/is-using-64-bit-integers-long-long-faster-than-less-bits-ones)
- [ ] [Privelage Rings](https://stackoverflow.com/questions/18717016/what-are-ring-0-and-ring-3-in-the-context-of-operating-systems/44483439#44483439)
- [ ] [Linux Boot and Startup Process](https://opensource.com/article/17/2/linux-boot-and-startup)
- [ ] [Display and Window Manager](https://opensource.com/article/16/12/yearbook-best-couple-2016-display-manager-and-window-manager)
- [ ] [Demystifying memory management in modern programming languages](https://deepu.tech/memory-management-in-programming/)
- [ ] [Concurrency in Modern Programming Languages](https://deepu.tech/concurrency-in-modern-languages/)
- [ ] [Micronaut Guides](https://guides.micronaut.io/latest/index.html)
- [ ] [Hussein Nassar **MEMBERS ONLY**](https://www.youtube.com/playlist?list=UUMO_ML5xP23TOWKUcc-oAE_Eg)
- [ ] [Hussein Nassar **GOOGLE DOCS OF PPT + VIDS**](https://docs.google.com/document/d/1ZjsaF0OjQ4p1e1C4bSfT2ode8Rpg9Pknuil7iIJDr9g/edit?pli=1)
- [ ] [Discord Case Study](https://www.youtube.com/watch?v=xynXjChKkJc)
- [ ] [Shopify Case Study](https://www.youtube.com/watch?v=f53-Iw_5ucA)
- [ ] [Netflix Case Study](https://uxplanet.org/next-episode-the-design-patterns-and-flows-of-netflix-592b63741f89)
- [ ] [DDD](https://www.youtube.com/watch?v=3t0tZTOGk08)
- [ ] [Git Database Internal](https://github.blog/2022-08-29-gits-database-internals-i-packed-object-store/)
