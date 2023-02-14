###### Full-text search

#### Full-text search

Full text search is a search query that returns some or all of the words from the query. It has search features like fuzzy text as well as synonyms.Traditional databases are easy to store and retrieve data while comparing with full text search but, Full-text indexes offer more flexibility in terms of matching words than standard database search. Full-text search is the most common technique used in Web search engines.



#### Lucene 

Lucene is an inverted full-text index. It takes all the documents, splits them into words, and then builds an index for each word. Since the index is an exact string-match, unordered, it can be extremely fast. Doug Cutting wrote Lucene in 1999. Apache Lucene is a high performance, full-text search engine library written entirely in Java. It can be used with any application that requires full-text search. It looks through the entire index to find what you want. The index is mapped with a hash ID. As soon as it finds the desired text, it simply fetch it. Elasticsearch as well as Solr are built on Apache Lucene. 

## Lucene features

Scalable, High-performance indexing.
Small RAM requirements (1MB heap).
Powerful, accurate and efficient search algorithms.
Ranked searching - best results returned first.
Sorting by any field.
configurable storage engine (codecs).
Cross-platform solution.



#### Elasticsearch

Elasticsearch is build on Apache Lucene and was released in 2010. It is distributed, free, open search, RESTful and analytics engine. It can be used with many types of data like text, numbers, structured and unstructured. Elasticsearch stores data as JSON documents. Each document has set of keys that is mapped with their corresponding types. Elasticsearch creates an inverted index, which is used to allow very fast full-text searches. Same like Lucene it arrange every unique word that appears in any document and identifies all of the documents each word occurs in. 

## Elasticsearch features

It is fast. latency is typically one second.
It is distributed by nature.
It comes with a wide set of features such as data rollups and index lifecycle management.



#### Solr

Solr is a search server built on Apache Lucene. It is an open source, Java-based, information retrieval library. It is designed for scalability and fault tolerance. Solr was created in 2004 by Yonik Seeley to add search capability for the company website. Not only for search, but also it can be used for storage purpose. Like other NoSQL databases, Solr is a non-relational data storage and processing technology.

## Solr features

It can be used in high volume traffic.
Solr has a built in responsive administrative user interface to make it easy to control.
It is easy to monitor your instances.
To communicate with Solr, it is not mandatory to have programming skills. We can use restful services like XML,JSON, and.CSV and get results in the same format.
It has features such as tokens, phrases, spell check, wildcard and auto-complete.
We can customize the components of Solr easily.



#### Reference Links:

Full text-search - https://www.mongodb.com/basics/full-text-search

Lucene - https://lucene.apache.org/
Lucene - https://en.wikipedia.org/wiki/Apache_Lucene
Lucene - https://www.baeldung.com/lucene
Lucene features - https://lucene.apache.org/core/

Elasticsearch - https://www.elastic.co/elasticsearch/
Elasticsearch - https://www.elastic.co/what-is/elasticsearch
Elasticsearch - https://www.youtube.com/watch?v=upvaxy7zj60
Elasticsearch features - https://aws.amazon.com/what-is/elasticsearch/

Solr - https://en.wikipedia.org/wiki/Apache_Solr#External_links
Solr - https://solr.apache.org/guide/7_2/a-quick-overview.html
Solr - https://www.tutorialspoint.com/apache_solr/apache_solr_overview.htm
Solr features - https://solr.apache.org/
