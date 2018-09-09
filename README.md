# My favorite Software Engineering resources
***
## System Design

[Concurrent Programming for Scalable Web Architectures](http://berb.github.io/diploma-thesis/community/index.html) (document)
  * Master's thesis on web scalability principles
  * Good for review
  
[Designing Data-Intensive Applications](https://dataintensive.net/) (book) [Amazon](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321/)
  * Must-read, distributed systems bible
  * Extremely comprehensive
  
#### System Design - Case studies
* [How We Scaled Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc) YouTube, 1h 8 min, Feb 22, 2012
   > Kevin Modzelewski talks about Dropbox and its History. He describes the technological issues faced by Dropbox and the actions they have to take in order to continuously improve it.
* [Four Distributed Systems Architectural Patterns by Tim Berglund](https://www.youtube.com/watch?v=tpspO9K28PM) YouTube, 50 min, Aug 2, 2017
   * Focused on Kafka and Nosql
   > Developers and architects are increasingly called upon to solve big problems, and we are able to draw on a world-class set of open source tools with which to solve them. Problems of scale are no longer consigned to the web’s largest companies, but are increasingly a part of ordinary enterprise development. At the risk of only a little hyperbole, we are all distributed systems engineers now.

   > In this talk, we’ll look at four distributed systems architectural patterns based on real-world systems that you can apply to solve the problems you will face in the next few years. We’ll look at the strengths and weaknesses of each architecture and develop a set of criteria for knowing when to apply each one. You will leave knowing how to work with the leading data storage, messaging, and computation tools of the day to solve the daunting problems of scale in your near future.
* [Building at Uber Scale by Ryan Sonnenberg](https://www.youtube.com/watch?v=bSojCYTTz-A) YouTube, 28 min, Apr 11, 2017
   > Working on large scale android projects opens up issues, traditionally not seen at smaller scales. These issues stem from rapidly growing code size, expanding build times, and dissemination of configuration and coding practices. At Uber, we are able to overcome many of these problems and ship with high confidence, through moving off of traditional build systems and detecting common anti patterns, as they arise. In this talk, Ryan will showcase the improvements we have made to traditional tools like lint and checkstyle, as well as how we translated common anti patterns into codified rules that are enforced at compile time.
* [The Verification of a Distributed System by Caitie McCaffrey](https://www.youtube.com/watch?v=ZMbqbXxRthE) YouTube, 48 min, Apr 13, 2017
   > Distributed Systems are difficult to build and test for two main reasons: partial failure & asynchrony. These two realities of distributed systems must be addressed to create a correct system, and often times the resulting systems have a high degree of complexity. Because of this complexity, testing and verifying these systems is critically important. In this talk we will discuss strategies for proving a system is correct, like formal methods. We will also discuss less strenuous methods of testing which will help increase our confidence that our systems are doing the right thing.
   
   > Caitie McCaffrey is a Backend Brat and Distributed Systems Diva at Twitter

## Databases

#### Databases - Case Studies

* [Using Redis at Scale at Twitter - Rashmi Ramesh](https://www.youtube.com/watch?v=QznaOSk20nU) YouTube, 40 min, Jul 5, 2017
   * Nighthawk / distributed caching with Redis
   > Timelines, DMs, Twitter Analytics are just some of the major services at Twitter that use Redis. A majority of our analytics services use lambda architecture and they require a highly available cache to store and read stream compute data, while their corresponding batch processing jobs catch up. Our caching solution, built on top of Redis, offers replication for such services requiring a highly available, scalable cache, serving millions of requests per second. In this session, we’ll cover the architecture, constraints and some problems of distributed caching we are trying to tackle today. We’ll also touch upon data partitioning, data movement, failure domain considerations and how we leverage Redis features to achieve the same.
   
   > Slide deck https://www.slideshare.net/RedisLabs/redisconf17-using-redis-at-scale-twitter
