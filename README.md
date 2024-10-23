# test-toolkit
[![](https://jitpack.io/v/ahunigel/test-toolkit.svg)](https://jitpack.io/#ahunigel/test-toolkit)

Provide an additional test toolkit library for Java unit test.

## Features
- JUnit additional Assertions
    - assertNotEmpty/assertBlank/assertNotBlank for `Collection`
    - assertNotEmpty for `Map`
    - assertNotEmpty/assertBlank/assertNotBlank for `String`
- MockitoBaseTest

## How to use

### Step 1. Add the JitPack repository to your build file
```groovy
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
## Step 2. Add the dependency
```groovy
dependencies {
    implementation 'com.github.ahunigel:test-toolkit:{version}'
}
```
_Refer to https://jitpack.io/#ahunigel/test-toolkit for details._

## See Also
- [springkit-bom](https://github.com/ahunigel/springkit-bom)
- [test-toolkit](https://github.com/ahunigel/test-toolkit)
- [spring-test-toolkit](https://github.com/ahunigel/spring-test-toolkit)
- [spring-security-oauth2-test](https://github.com/ahunigel/spring-security-oauth2-test)
- [spring-toolkit](https://github.com/ahunigel/spring-toolkit)

## TODOs
- hamcrest collection matcher
    - hasItemsInOrder
