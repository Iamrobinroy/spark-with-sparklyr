# spark-with-sparklyr

Apache SparkR is a data processing framework that can quickly perform processing tasks on very large data sets, and can also distribute data processing tasks across multiple computers, either on its own or in tandem with other distributed computing tools. These two qualities are key to the worlds of big data and machine learning, which require the marshaling of massive computing power to crunch through large data stores.


When we think of the computation power that Spark provides and the ease of use of the R language, it is natural to want them to work together, seamlessly. This is also what the R community expected: an R package that would provide an interface to Spark that was easy to use, compatible with other R packages, and available in CRAN. With this goal, we started developing sparklyr.
Officially, sparklyr is an R interface for Apache Spark. It’s available in CRAN and works like any other CRAN package, meaning that it’s agnostic to Spark versions, it’s easy to install, it serves the R community, it embraces other packages and practices from the R community, and so on. It’s hosted in GitHub and licensed under Apache 2.0, which allows we to clone, modify, and contribute back to this project.
Sparklyr is an R package that lets we analyze data in Spark while using familiar tools in R.
 
Sparklyr is an open-source package that provides an interface between R and Apache Spark. We can now leverage Spark’s capabilities in a modern R environment, due to Spark’s ability to interact with distributed data with little latency. 

Sparklyr is an effective tool for interfacing with large datasets in an interactive environment. This way we can benefit from the familiar tools in R in order to analyze data in Spark., giving we the best of both worlds.

# Features

Through Sparklyr we can use Spark as the backend for dplyr, a popular data manipulation package.

Sparklyr provides a range of functions that allow us to access the Spark tools for transforming/pre-processing data, On top of that, it also provides interfaces to Spark’s distributed machine learning algorithms and much more.

Sparklyr is also extensible. R packages that depend on Sparklyr to call the full Spark API can be created. One such extension is H2O’s Sparkling, an R package compatible with H2O’s machine learning algorithm.

