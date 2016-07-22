ecosystem
=========

data management
---------------

#.  apache hadoop

#.  apache hadoop hdfs

#.  apache hadoop yarn

data access
-----------

#.  apache accumulo

    ..  note::

        sorted, distributed key-value store with cell-based access control

#.  apache hadoop

#.  apache hadoop mapreduce

#.  apache hawq

    ..  note::

        native sql on hadoop based on advanced mpp elastic query engine

#.  apache hbase

#.  apache hive

#.  apache pig

#.  apache slider

    ..  note::

        a framework for yarn-based long-running application

        like hbase, accumulo, storm

#.  apache solr

#.  apache spark

#.  apache storm

#.  apache tez

    ..  note::

        a framework for yarn-based data processing application

data governance & integration
----------------------

#.  data lifecycle & governance

    #.  apache atlas

        ..  note::

            metadata

    #.  apache falcon

        ..  note::

            framework for managing data lifecycle in hadoop clusters

#.  data workflow

    #.  apache flume

        ..  note::

            streaming logs into hadoop

    #.  apache hadoop

    #.  apache hadoop hdfs

    #.  apache kafka

        ..  note::

            fast, scalable, fault-tolerant messaging system

    #.  apache sqoop

        ..  note::

            transfers bulk data between hadoop and structured datastores

security
--------

#.  apache hadoop

#.  apache hadoop hdfs

#.  apache knox gateway

    ..  note::

        secure entry point for hadoop clusters

#.  apache ranger

    ..  note::

        authoriztion, authentication, audit, and data protection

        supports for hdfs, hive, hbase, storm, knox, solr, kafka, yarn

operation
---------

#.  apache ambari

    ..  note::

        platform for provisioning, managing, monitoring and securing hadoop clusters

#.  apache hadoop

#.  apache oozie

    ..  note::

        job scheduling

#.  apache zookeeper

    #.  distributed configuration service

    #.  synchronization service

    #.  naming registry

tools
-----

#.  zeppelin

    ..  note::

        web-based notebook interactive data analytics

    #.  data ingestion

    #.  data exploration

    #.  visualization

    #.  sharing

    #.  collaboration

#.  ambari user view

    #.  **tez view** understand and optimize cluster resource usage

    #.  **hive view** write and execute hql

    #.  **pi view** write and running pig script

    #.  **capacity scheduler** creating and managing yarn queues

    #.  **files view** manage, browse and upload files and foler in hdfs
