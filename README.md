# Cache Actuator not visible

This is a simple spring boot 2.1 example with caching and ehcache enabled. Unfortunatelly the cache actuator is not working. `CachesEndpointAutoConfiguration` bean is present.

Steps to reproduce:
- Start DemoApplication
- Execute http://localhost:8080/actuator/

=> Cache is not listed
