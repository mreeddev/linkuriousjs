[![Build Status](https://travis-ci.org/dilbertside/linkuriousjs.svg?branch=master)](https://travis-ci.org/dilbertside/linkuriousjs)

# linkuriousjs
WebJars Linkurious.js

#Original library
https://github.com/Linkurious/linkurious.js

fork from sigma.js (in sync but faster release pace and more plugins)

#Made on the model of
http://www.webjars.org/contributing


#to install and run locally stable version
```
mvn install
```

example of use in a Spring managed Thymeleaf page
```
    <script th:src="@{/webjars/linkuriousjs/1.0.6/sigma.min.js}"></script>
    <script th:src="@{/webjars/linkuriousjs/1.0.6/plugins/sigma.parsers.gexf.min.js}"></script>
    <script th:src="@{/webjars/linkuriousjs/1.0.6/plugins/sigma.plugins.dragNodes.min.js}"></script>
    <script th:src="@{/webjars/linkuriousjs/1.0.6/plugins/sigma.layout.forceAtlas2.min.js}"></script>
```
