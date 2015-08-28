# Introduction #

The closure compiler is available in the Maven Central Repository.

We currently do not have an official plugin for compiling your JS with Maven, but there should be some unofficial plugins on the RelatedProjects page.

# Usage #

To include closure-compiler in your project add the following to your build configuration:

## Maven ##

```
  <dependency>
      <groupId>com.google.javascript</groupId>
     <artifactId>closure-compiler</artifactId>
     <version>v20140730</version>
  </dependency>
```

## Apache Ivy: ##

```
  <dependency org="com.google.javascript" name="closure-compiler" rev="v20140730"/>
```

## Groovy Grape: ##
```
  @Grapes(
      @Grab(group='com.google.javascript', module='closure-compiler', version='v20140730')
  )
```

## Apache Buildr ##

```
  'com.google.javascript:closure-compiler:jar:v20140730'
```


# Release Archive #

Releases before v20130227 were based on the subversion commit number.  The following table identifies the matching date-based releases.

|[r2388](https://code.google.com/p/closure-compiler/source/detail?r=2388)|Corresponds to the 20121212 release |
|:-----------------------------------------------------------------------|:-----------------------------------|
|[r2180](https://code.google.com/p/closure-compiler/source/detail?r=2180)|Corresponds to the 20120917 release |
|[r2079](https://code.google.com/p/closure-compiler/source/detail?r=2079)|Corresponds to the 20120711 release |
|[r1918](https://code.google.com/p/closure-compiler/source/detail?r=1918)|Corresponds to the 20120430 release |
|[r1810](https://code.google.com/p/closure-compiler/source/detail?r=1810)|Corresponds to the 20120305 release |
|[r1741](https://code.google.com/p/closure-compiler/source/detail?r=1741)|Corresponds to the 20112023 release |
|[r1592](https://code.google.com/p/closure-compiler/source/detail?r=1592)|Corresponds to the 20111114 release |
|[r1459](https://code.google.com/p/closure-compiler/source/detail?r=1459)|Corresponds to the 20111003 release |
|[r1352](https://code.google.com/p/closure-compiler/source/detail?r=1352)|Corresponds to the 20110811 release |
|[r946](https://code.google.com/p/closure-compiler/source/detail?r=946)  |Corresponds to the 20110405 release |
|[r916](https://code.google.com/p/closure-compiler/source/detail?r=916)  |Corresponds to the 20110322 release |
|[r706](https://code.google.com/p/closure-compiler/source/detail?r=706)  |Corresponds to the 20110119 release |
|[r606](https://code.google.com/p/closure-compiler/source/detail?r=606)  |Initial Mavenized Release           |