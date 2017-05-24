Easily Secure your Spring Boot Apps with Keycloak
=================================================

This is the support repository for :
- This [Blog Post](https://developers.redhat.com/blog/?p=432287)
- These screencasts : [Part 1](https://youtu.be/UUWyu1kG6YI) and [Part 2](https://youtu.be/Yc5Qe5C3Xn4)

The full instructions to setup the [Keycloak Server](http://www.keycloak.org/downloads.html) can be found in the Blog Post.


To start the app from the command line :
```

mvn clean spring-boot:run

```

## Importing the realm

If you don't want to create and configure the initial Keycloak Realm manually, you can just import it through the Keycloak Web Console. Import the [springdemo.json](springdemo.json) which is located at the root of this repo.


# Part 1 - Create a Spring Boot app and add Keycloak support

This is on the [Master branch](https://github.com/sebastienblanc/spring-boot-keycloak-tutorial/tree/master)

# Part 2 - Add Spring Security support

This is on the [Spring Security branch](https://github.com/sebastienblanc/spring-boot-keycloak-tutorial/tree/spring-security)

# Part 3 - Splitting the monolith and secure microservices

TODO

## Resources

* [Keycloak website](http://www.keycloak.org/)
* [Spring Boot Keycloak Adapter Doc](https://keycloak.gitbooks.io/documentation/securing_apps/topics/oidc/java/spring-boot-adapter.html)
* [Spring Security Keycloak Adapter](https://keycloak.gitbooks.io/documentation/securing_apps/topics/oidc/java/spring-security-adapter.html)
* [Keycloak quickstarts](https://github.com/keycloak/keycloak-quickstarts)
