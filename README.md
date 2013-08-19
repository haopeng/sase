sase
====

SASE 1.0 Release
We are delighted to release the first version of SASE - SASE 1.0.

SASE is a stream processing system developed at the University of Massachusetts Amherst. SASE provides fast pattern matching over streams. It supports complex pattern queries and achieves high throughput. The release of SASE 1.0 contains the stream processing engine of the SASE system. Some advanced features such as processing streams with imprecise timestamps are not included in this release.

In the package of SASE 1.0, we include the following components:

  * Query Evaluation Engine: evaluates pattern queries over streams
  * Query Parser: we provide two query parser. One can read queries in the SASE language, and the other can read an automaton-based representation of a query in a pre-defined format
  * Stream Generator: generates synthetic data for experiments
  * Command Line User Interface
SASE 1.0 is implemented in the Java language, using J2SE 5.0. We have tested SASE 1.0 on Unix, Mac and Windows (Cygwin).