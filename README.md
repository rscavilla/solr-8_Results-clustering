# solr-8_Results-clustering

Results clustering was removes in solr 8.x. The reason sited on the solr website was “The search results clustering contrib (Carrot2) has been removed from 8.x Solr due to lack of Java 1.8 compatibility in the dependency that provides online clustering of search results.”

I needed to have results clustering before it’s reintroduced in solr 9.0. Here is what I did:
1.	Follow the instructions for installing the clustering contrib: https://solr.apache.org/guide/8_1/result-clustering.html
2.	Add solr-clustering-8.7.0.jar to /solr-8.x.x/dist (I tested this jar up to Solr version 8.11.1)
3.	Add the clustering directory to the solr-8.x.x/contrib  directory
4.	restart solr


