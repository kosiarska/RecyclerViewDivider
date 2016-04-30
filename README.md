RecyclerViewDivider
===============

A simple divider for a RecyclerView used as an item decoration.

<img src="https://raw.githubusercontent.com/Fondesa/RecyclerViewDivider/master/screenshot_1.png" height="500">
<img src="https://raw.githubusercontent.com/Fondesa/RecyclerViewDivider/master/screenshot_2.png" height="500">
<img src="https://raw.githubusercontent.com/Fondesa/RecyclerViewDivider/master/screenshot_3.png" height="500">

Usage
------

###Basic divider###

```java
RecyclerViewDivider.with(context).addTo(recyclerView).build().show();
```
###Colored divider with all properties###
```java
RecyclerViewDivider.with(context)
                   .addTo(recyclerView)
                   .color(color)
                   .size(size)
                   .marginSize(marginSize)
                   .build()
                   .show();
```
###Custom drawable divider with all properties###
```java
RecyclerViewDivider.with(context)
                   .addTo(recyclerView)
                   .drawable(drawable)
                   .tint(color)
                   .size(size)
                   .marginSize(marginSize)
                   .build()
                   .show();
```
###Simple space###
```java
RecyclerViewDivider.with(context).addTo(recyclerView).asSpace().build().show();
```

Gradle
------
Available both on ```jcenter()``` and ```mavenCentral```
```gradle
dependencies {
    compile 'com.github.fondesa:recycler-view-divider:1.1.1'
}
```

Maven
------
```xml
<dependency>
  <groupId>com.github.fondesa</groupId>
  <artifactId>recycler-view-divider</artifactId>
  <version>1.1.1</version>
  <type>pom</type>
</dependency>
```