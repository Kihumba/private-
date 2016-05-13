# Outcome - Optimization

Skill Description
----------
An optimized application is very critical and knowing how to optimize an application is a very important skill to have. This outcome treats common optimization issues as well as ways to handle or curb those issues.

Outputs
----------
- Write a blog post on scaling rails applications.
- Implement optimization techniques in checkpoints and simulation project.

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Reasons why a Rails application might be slow. | [ ] | [ ] |
| The 80-20 rule of Rails performance optimization.| [ ] | [ ] |
| Why is memory consumption important?| [ ] | [ ] |
| Ruby Garbage Collector.| [ ] | [ ] |
| Ways of making a Rails application faster:| | |
| <ul><li>**Scaling**| [ ] | [ ] |
| <ul><li>**Caching**:| | |
| <ul><li>Page Caching using actionpack-page_caching gem. | [ ] | [ ] |
| <ul><li>Fragment Caching| [ ] | [ ] |
| <ul><li>Action Caching using actionpack-action_caching gem. | [ ] | [ ] |
| <ul><li>Low-level Caching| [ ] | [ ] |
| <ul><li>SQL Caching| [ ] | [ ] |
| <ul><li>**Code Optimization**| [ ] | [ ] |
| <ul><li>**Avoid memory intensive rails features like:**| | |
| <ul><li>Serializers| [ ] | [ ] |
| <ul><li>Active Record| [ ] | [ ] |
| <ul><li>String Callback| [ ] | [ ] |
| <ul><li>**Write less Ruby:**| | |
| <ul><li>Attribute Preloading| [ ] | [ ] |
| <ul><li>Data Aggregation| [ ] | [ ] |
| <ul><li>**Fine-tune Unicorn:**| | |
| <ul><li>App Preloading| [ ] | [ ] |
| <ul><li>GC Between Requests| [ ] | [ ] |
| <ul><li>**Limit Growth:**| | |
| <ul><li>Internal memory control| [ ] | [ ] |
| <ul><li>External memory control| [ ] | [ ] |
| <ul><li>**Tune Ruby GC**| [ ] | [ ] |
| <ul><li>**Profile**| [ ] | [ ] |
| <ul><li>**Write Performance Tests**| [ ] | [ ] |
| Differences between performance and scalability.| [ ] | [ ] |
| Hosting assets externally:| | |
| <ul><li>Automatic Remote Asset Hosting| [ ] | [ ] |
| <ul><li>Preload Active Record Associations| [ ] | [ ] |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When my rails application is slow... **Action:** I first of all identify the cause.| [ ] | [ ]  |
| **Context:** When the size of my application’s user base can no longer be handled by my rails application... **Action:** I scale the application from my hosting platform.| [ ] | [ ]  |
| **Context:** When building a rails application... **Action:** I use Unicorn as my default rails server.| [ ] | [ ]  |
| **Context:** When working with static resources like images, javascript and css in a rails application... **Action:** I offload those resources to another domain/host like AWS S3.| [ ] | [ ]  |
| **Context:** When working on a rails application that deals heavily with static pages... **Action:** I use actionpack-page_caching gem to cache the static content of the pages.| [ ] | [ ]  |
| **Context:** When working on a rails application that handle authentication on pages... **Action:** I use the actionpack-action_caching gem to cache authentication actions.| [ ] | [ ]  |
| **Context:** When I want to cache a section of my view logic... **Action:** I use fragment caching to serve out the cache store when next a request for that section of view is made.| [ ] | [ ]  |
| **Context:** When I want to cache a value or a query result... **Action:** I use rails low-level caching mechanism by invoking Rails.cache.fetch method.| [ ] | [ ]  |
| **Context:** When I am working with a query that would be evoked at several instances... **Action:** I use SQL caching mechanism to cache the result of the query for subsequent requests.| [ ] | [ ]  |
| **Context:** When I want to represent string from a database as a Hash... **Action:** I implement serialization myself as against using serializers.| [ ] | [ ]  |
| **Context:** When iterating over a large dataset and data is the only thing needed... **Action** I run the query to get the data and avoid using ActiveRecord altogether.| [ ] | [ ] |
| **Context:** When defining rails callbacks... **Action** I define symbol callbacks or callbacks that take a block as against defining string callbacks.| [ ] | [ ] |
| **Context:** When performing a task in rails that can be handled by an outside tool... **Action** I use the external tool.| [ ] | [ ] |
| **Context:** When carrying out optimization in my rails application... **Action** I do not change the GC settings unless I have a good theory on how that can improve performance.| [ ] | [ ] |
| **Context:** When loading large amount of data in a single go... **Action** I reduce the frequency of GC runs by changing the following GC environment variables:RUBY_GC_HEAP_GROWTH_FACTOR, RUBY_GC_MALLOC_LIMIT, RUBY_GC_MALLOC_LIMIT_MAX, RUBY_GC_OLDMALLOC_LIMIT, and RUBY_GC_OLDMALLOC_LIMIT.| [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Rails is a nice framework but when misused performance is hit hard.| [ ] | [ ]  |
| Optimizing a Rails application is easy.| [ ] | [ ]  |
| 80% of speedup comes from memory optimization, remaining 20% from everything else.| [ ] | [ ]  |
| The performance of my application is mostly tied to memory consumption.| [ ] | [ ]  |
| Think scalability before performance everything. I.e. How much? vs How fast?| [ ] | [ ]  |
| An application will not scale if it is not designed to scale.| [ ] | [ ]  |
| Writing better and leaner code aids application performance.| [ ] | [ ]  |
| Everything should be as simple as possible but not simpler.| [ ] | [ ]  |
| The best code is one that does not exist.| [ ] | [ ]  |
