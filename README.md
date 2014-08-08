SASE Open Source System
====

We are delighted to release the first version of SASE Open Source System Release.
##Introduction
SASE is a stream processing system developed at the University of Massachusetts Amherst. SASE provides fast pattern matching over streams. It supports complex pattern queries and achieves high throughput. The release of SASE 1.0 contains the stream processing engine of the SASE system. Some advanced features such as processing streams with imprecise timestamps are not included in this release.

In the package of SASE 1.0, we include the following components:

  * Query Evaluation Engine: evaluates pattern queries over streams
  * Query Parser: we provide two query parser. One can read queries in the SASE language, and the other can read an automaton-based representation of a query in a pre-defined format
  * Stream Generator: generates synthetic data for experiments
  * Command Line User Interface
SASE 1.0 is implemented in the Java language, using J2SE 5.0. We have tested SASE 1.0 on Unix, Mac and Windows (Cygwin).

##Citing SASE Open Source System
This is the publication you should cite if you want to make reference to the SASE Open Source System, which is developed as part of the prototype system in this paper.

_Zhang, Haopeng, Yanlei Diao, and Neil Immerman. *"Recognizing patterns in streams with imprecise timestamps."* Proceedings of the VLDB Endowment 3.1-2 (2010): 244-255._ **[PDF](http://www.vldb2010.org/proceedings/files/papers/R21.pdf)  [BibTex](http://avid.cs.umass.edu/sase/uploads/img/sase2010.bib)**.

Or you can cite another paper below, in which the mentioned prototype system is also developed based on SASE Open Source System.

_Zhang, Haopeng, Yanlei Diao, and Neil Immerman. "On Complexity and Optimization of Expensive Queries in Complex Event Processing."In Proceedings of the 2014 ACM SIGMOD international conference on Management of data (pp. 217-228). ACM_ **[PDF](http://delivery.acm.org/10.1145/2600000/2593671/p217-zhang.pdf )  [BibTex](http://avid.cs.umass.edu/sase/uploads/img/sase2014.bib )**.
