# Google Summer of Code 2021

## Organization: CNCF with Layer5

As a participant of Google Summer of Code 2021, I worked with Layer5 to work on Meshery, introducing many features and rebasing a few things on the server-side. I helped with adding/enhancing a few commands in mesheryctl that helps in managing Filters, Patterns, Performance Results and Profiles, Environment checking, etc. I also set up Unit and Integration Testing for mesheryctl by testing the cobra commands with recording their expected behavior and output in multiple scenarios, stored in golden files. I worked with consolidating multiple handlers on the server side and also changing them in the whole project.

Here I have mentioned my goals and contributions!

### Goals: Meshery CLI
- Adding a new command to meshery's cli tool, i.e. mesheryctl for performance profiles and result management
- Introduction of Unit Testing and Integration testing for Cobra commands of cli tool, mesheryctl.
- Introducing health-checks for environment checking of pre/post-deployment of meshery server
- Adding a new command to meshery's cli tool, i.e. mesheryctl for managing web-assembly filters

### Goals: Meshery Server
- Reworking of API endpoints
- Swagger spec and docs for Rest API
    - Spec definition
    - Docs published
    - Docs auto-published

### Goals: Others
- Documentation on writing Unit and Integration Tests and Contributing to Meshery Server Documentation
- Ci workflow for Swagger Documentation and running Unit and Integration Tests with calculating Code-coverage with CodeCov


### Focus: Meshery CLI
* `mesheryctl perf`
  * https://github.com/meshery/meshery/pull/2928
  * https://github.com/meshery/meshery/pull/3082
  * https://github.com/meshery/meshery/pull/3254
  * https://github.com/meshery/meshery/pull/3762
* `mesheryctl system check`
  * https://github.com/meshery/meshery/pull/3027
  * https://github.com/meshery/meshery/pull/3253
  * https://github.com/meshery/meshery/pull/3490
  * https://github.com/meshery/meshery/pull/3649
  * https://github.com/meshery/meshery/pull/3666
  * https://github.com/meshery/meshery/pull/3707
* `mesheryctl pattern`
  * https://github.com/meshery/meshery/pull/3489
* `mesheryctl exp filter`
  * https://github.com/meshery/meshery/pull/3843
  * https://github.com/meshery/meshery/pull/3857 
* `Unit and Integration Testing`
  * https://github.com/meshery/meshery/pull/3137
  * https://github.com/meshery/meshery/pull/3288
  * https://github.com/meshery/meshery/pull/3430
  * https://github.com/meshery/meshery/pull/3541
  * https://github.com/meshery/meshery/pull/3708
  * https://github.com/meshery/meshery/pull/3714




### Focus: Meshery Server
* `Reworking of server endpoints and Open API Documentation`
  * https://github.com/meshery/meshery/pull/3012
  * https://github.com/meshery/meshery/pull/3075
  * https://github.com/meshery/meshery/pull/3173
  * https://github.com/meshery/meshery/pull/3211
  * https://github.com/meshery/meshery/pull/3342
  * https://github.com/meshery/meshery/pull/3368
  * https://github.com/meshery/meshery/pull/3412
  * https://github.com/meshery/meshery/pull/3518
  * https://github.com/meshery/meshery/pull/3542
  * https://github.com/meshery/meshery/pull/3578
  * https://github.com/meshery/meshery/pull/3641
  * https://github.com/meshery/meshery/pull/3852
  * https://github.com/meshery/meshery/pull/3872 
  * https://github.com/meshery/meshery/pull/3924

### Other contributions
  * https://github.com/meshery/meshery/pull/3170
  * https://github.com/meshery/meshery/pull/3298
  * https://github.com/meshery/meshery/pull/3343
  * https://github.com/meshery/meshery/pull/3392
  * https://github.com/meshery/meshery/pull/3433    
  * https://github.com/meshery/meshery/pull/3461
  * https://github.com/meshery/meshery/pull/3451
  * https://github.com/meshery/meshery/pull/3491
  * https://github.com/meshery/meshery/pull/3786

## Screenshots
![image](https://user-images.githubusercontent.com/50979887/130494555-e1cee00a-c3d6-4a12-a0e2-06bf6d3d344c.png)

Reached 30% code-coverage in mesheryctl commands

![image](https://user-images.githubusercontent.com/50979887/130495186-f5bfcc27-c230-4c73-a598-8a8d5342ab7e.png)
![image](https://user-images.githubusercontent.com/50979887/130495212-076766cb-8d86-48b8-8a72-a7347d54f87a.png)

Screenshots included from Swagger Documentation of APIs

## Summary

Had a fun time working with Layer5, as a student I found the best place to start my Open Source Journey.
Contact Me-  [LinkedIn](https://www.linkedin.com/in/piyushsingariya/) [Twitter](https://twitter.com/piyushsingariya)


