## MySQL (slow_query_log)  FileBeat +  ElasticSearch + Kibana 


# Start

```
docker-compose up -d
```

# Connect to database 

 - slow query log configuration [Slow log в MySQL](https://ruhighload.com/%D0%9A%D0%B0%D0%BA+%D0%B2%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%8C+slow+log+%D0%B2+mysql%3F)

```
SET GLOBAL slow_query_log = 'ON';
select sleep(4);
```

# MySql logs

```
tail -f /db/logs/mysql-slow.log
```

#Kibana

 - Display slow query log 
 
<a href="http://piccy.info/view3/14236494/31ac337898f23baa813e091007a2859f/" target="_blank"><img src="http://i.piccy.info/i9/88213c79e43d49ec9758c33873fffcd4/1615125793/5622/1418447/Screen_Shot_2021_03_07_at_16_08_28_240.jpg" alt="Piccy.info - Free Image Hosting" border="0" /></a><a href="http://i.piccy.info/a3c/2021-03-07-14-03/i9-14236494/240x128-r" target="_blank"><img src="http://i.piccy.info/a3/2021-03-07-14-03/i9-14236494/240x128-r/i.gif" alt="" border="0" /></a>

