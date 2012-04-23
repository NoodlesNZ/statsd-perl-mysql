A simple tool to parse the Innodb Stats from MySQL and fire them to Statsd/Graphite

The example in innodb.pl logs "log i/o's/second" and "Buffer pool size"

Note: If you're using MySQL <5.5 then you will need to omit the "ENGINE" keyword in the "SHOW ENGINE INNODB STATUS" query.