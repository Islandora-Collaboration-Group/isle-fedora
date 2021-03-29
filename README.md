# ISLE Fedora

## Part of the ISLE Islandora 7.x Docker Images
Designed as the Fedora Repository for ISLE.

Based on:  
* [ISLE-Tomcat](https://github.com/Islandora-Collaboration-Group/isle-tomcat)

Contains and Includes:
* [Fedora Repository 3.8.1](https://duraspace.org/fedora/)
* [Gsearch 2.9](https://github.com/discoverygarden/gsearch.git) (_DGI fork_)
* [Maven 3.x.x](https://maven.apache.org/)
* [Ant 1.x.x](https://ant.apache.org/)
* [DGI basic-solr-config 4.10.x branch](https://github.com/discoverygarden/basic-solr-config/tree/4.10.x)
* [DGI gsearch Extensions 0.1.x](https://github.com/discoverygarden/dgi_gsearch_extensions.git)
* [DGI Trippi-Sail 1.x](https://github.com/discoverygarden/trippi-sail)

## Important Paths
* `$FEDORA_HOME` is `/usr/local/fedora`

### Usage
- This version of the Fedora Image works in conjunction with the optional component [isle-blazegraph](https://github.com/Islandora-Collaboration-Group/isle-blazegraph) image.
* For general usage of this image and [ISLE](https://github.com/Islandora-Collaboration-Group/ISLE), please refer to [ISLE documentation](https://islandora-collaboration-group.github.io/ISLE/)
