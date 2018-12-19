Solr image based on [Official](https://hub.docker.com/_/solr) images with the [JTS](https://lucene.apache.org/solr/guide/6_6/spatial-search.html#SpatialSearch-JTSandPolygons) library added.

## Description
These are Solr dockerfiles, based on the [Official](https://hub.docker.com/_/solr) Solr images. Appropriate version of JTS library has been added.

## Versions
- [latest](https://github.com/vishalsngl/solr-jts/blob/master/latest)
- [5.4.1](https://github.com/vishalsngl/solr-jts/blob/master/5.4.1/Dockerfile)

## Usage
Since these are based on Official Images, the environment variables can be used as in [Official Images](https://hub.docker.com/_/solr).
Sample docker run command is as follows

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `docker run vishalsngl/solr-jts:latest`
