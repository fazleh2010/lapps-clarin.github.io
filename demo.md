
# LAPPS-CLARIN Integration Demo

This page provides a link to and explanation of a small-scale demonstration of the LAPPS-CLARIN integration. The focus is on how users of CLARIN's WebLicht can access services on LAPPS and vice versa.


## WebLicht and LAPPS

WebLicht and LAPPS are both environments for building, executing, and visualizing the results of NLP pipelines. The NLP tools integrated are basic NLP tools like tokenizers, sentences splitters, part-of-speech taggers, named entity recognizers and parsers. See the [NLP tools](nlptools.html) page for an introduction to what these tools do.

WebLicht NLP tools consume and produce the Text Corpus Format (TCF) data, an XML format designed for use as an internal data exchange format for WebLicht processing tools. LAPPS tools use the LAPPS Interchange Format (LIF), which is based on JSON-LD.

While integrating LAPPS tools into WebLicht and WebLicht tools into LAPPS the major guiding principle was that a WebLicht user would get a WebLicht experience and a LAPPS user a LAPPS experience. Therefore, this demo has two parts: a WebLicht demo that shows how WebLicht users can access LAPPS services and a LAPPS demo that shows how LAPPS users can access WebLicht services.


## WebLicht demo

This demo is available at https://weblicht.sfs.uni-tuebingen.de/weblicht-lapps/.

For this demo you need credentials that allow you to log in as a WebLicht user. There is a video at [WebLicht user guide](http://sfs.uni-tuebingen.de/~meh/weblicht-lapps/) to show you how to use LAPPS and access WebLicht tools.


## LAPPS demo

This demo is available at http://mellon.lappsgrid.org/.

LAPPS uses Galaxy as a front end for all user interactions. Users first need to create an account on the Galaxy server to get full functionality (without this, visualizations will fail). Creating an account is a pain-free process of creating an account name and password.

There is a video at XXXX to show you how to use LAPPS and access WebLicht tools. To learn more about Galaxy go to [Learn Galaxy](https://galaxyproject.org/learn/) or to [Galaxy 101](https://galaxyproject.org/tutorials/g101/), the basic introduction to Galaxy's interface, its functionality, and workflows.

<!--
- Screencast to create and execute a simple tool chain including services from both LAPPS and CLARIN.
   - Webcasts should be short and snappy.
- LAPPS video and user guide
- WebLicht video and user guide

- [demo requirements](https://docs.google.com/document/d/1xeXld3V8T8kpny2vuz2aCAWtxA7MZAZMYBzcQ3pCJhI/edit#heading=h.4er8ywhwqusi) (this will not be
-->
