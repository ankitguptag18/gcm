# gcm
Google Cloud Messaging - client libraries

Forked from [google/fcm](https://github.com/google/gcm), and kept only the rest-client part.

I needed support for FCM, which was added in master branch and a release wan not yet made.

See [original project's](https://github.com/google/gcm) readme for more info.

### Gradle Builds
Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```
allprojects {
  repositories {
    maven { url 'https://jitpack.io' }
  }
}
```
Step 2. Add the dependency

```
dependencies {
  implementation 'com.github.ankitguptag18:gcm:1.0.1'
}
```

### Maven Builds
Step 1. Add the JitPack repository to your build file

Add it in your Pom.xml at the end of repositories:
```
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>
```
Step 2. Add the dependency

```
<dependency>
  <groupId>com.github.ankitguptag18</groupId>
  <artifactId>gcm</artifactId>
  <version>1.0.1</version>
</dependency>
```
### Sbt Builds
Step 1. Add the JitPack repository to your build file

Add it in your build.sbt at the end of resolvers:

```
resolvers += "jitpack" at "https://jitpack.io"
```
Step 2. Add the dependency

```
libraryDependencies += "com.github.ankitguptag18" % "gcm" % "1.0.1"
```
