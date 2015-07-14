# Spring-djn is part of DirectJNgine #
The Spring connector is now part of DirectJNgine, as a separate JAR file. Please, visit the [DirectJNgine](https://code.google.com/p/directjngine/) page for further info.

Go to the [downloads](http://www.softwarementors.com/directjngine/downloads/) page to get the compiled library and the source code.

# Introduction #
Spring-DJN is a connector for [DirectJNgine](https://code.google.com/p/directjngine/) that allows using [Spring](http://projects.spring.io/spring-framework/) beans as [ExtJs'](http://www.sencha.com/products/extjs/) Direct actions. Just that -**but that!**

Once you do this, all your action classes will be _Spring capable_: you will be able to manage their lifecycle with Spring, or reference other Spring beans from them, just by configuring them appropriately as Spring beans.

## Configuring the Spring DirectJNgine connector ##

Using the Spring connector is as easy as including the corresponding _directjngine-spring-connector-XXX.jar_ in your classpath and then configuring your _web.xml_ as follows:

```
  <init-param>
    <param-name>dispatcherClass</param-name>
    <!-- Spring connector -->
    <param-value>com.softwarementors.djn.spring.dispatcher.SpringDispatcher</param-value>
  </init-param>
```

Now, just configure your action classes as a Spring beans, and voilá!

## Download ##

In order to make things easier, we are making the different DirectJNgine connector JARs available in the DirectJNgine [downloads](http://www.softwarementors.com/directjngine/downloads/) section, so that you can find all connectors in just one place.

For more information about DirectJNgine, go to its [main site](https://code.google.com/p/directjngine/).