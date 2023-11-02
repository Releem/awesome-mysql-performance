# Awesome-MySQL-performance
🔥 A curated list of awesome links related to MySQL / MariaDB / Percona configuration tuning for improved performance.

## Common MySQL Tuning articles

- [Ten MySQL performance tuning settings after installation](https://www.percona.com/blog/2014/01/28/10-mysql-performance-tuning-settings-after-installation/)
- [MySQL Server and SQL Performance Tuning](https://www.oracle.com/technetwork/community/developer-day/mysql-performance-tuning-403029.pdf)
- [MySQL Performance Cheat Sheet](https://severalnines.com/database-blog/mysql-performance-cheat-sheet)
- [Performance Tuning and Configurations for your MySQL Server](https://www.universalclass.com/articles/computers/performance-tuning-and-configurations-for-your-mysql-server.htm)
- [MAKING IT BETTER: BASIC MYSQL PERFORMANCE TUNING (MYSQLD)](https://mediatemple.net/community/products/dv/204404044/making-it-better%3A-basic-mysql-performance-tuning-(mysqld))
- [InnoDB Performance Optimization Basics](https://www.percona.com/blog/2013/09/20/innodb-performance-optimization-basics-updated/)
- [MySQL 101: Tuning MySQL After Upgrading Memory](https://www.percona.com/blog/2020/09/30/mysql-101-tuning-mysql-after-upgrading-memory/)
- [How MySQL Opens and Closes Tables](https://dev.mysql.com/doc/refman/5.7/en/table-cache.html)

## MySQL Variables tuning

### innodb_buffer_pool_chunk_size
- [InnoDB Buffer Pool Resizing: Chunk Change](https://www.percona.com/blog/2018/06/19/chunk-change-innodb-buffer-pool-resizing/)
- [What should be innodb_buffer_pool_chunk_size for pool_size=2G, pool_instances=2?](https://dba.stackexchange.com/questions/245432/what-should-be-innodb-buffer-pool-chunk-size-for-pool-size-2g-pool-instances-2)
- [MySQL InnoDB buffer pool configuration | Role of InnoDB buffer pool chunk size and Instances](https://www.youtube.com/watch?v=c-xyooZyPW0)
- [Tuning innodb_buffer_pool_chunk_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_chunk_size)
### innodb_buffer_pool_instances
- [How Many innodb_buffer_pool_instances Do You Need in MySQL 8?](https://www.percona.com/blog/2020/08/13/how-many-innodb_buffer_pool_instances-do-you-need-in-mysql-8/)
- [MySQL InnoDB performance improvement: InnoDB buffer pool instances](https://www.saotn.org/mysql-innodb-performance-improvement/#google_vignette)
- [MySQL InnoDB buffer pool configuration | Role of InnoDB buffer pool chunk size and Instances](https://www.youtube.com/watch?v=c-xyooZyPW0)
- [Tuning innodb_buffer_pool_instances](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_instances)
### innodb_buffer_pool_size
- [How large should be mysql innodb_buffer_pool_size?](https://dba.stackexchange.com/questions/27328/how-large-should-be-mysql-innodb-buffer-pool-size)
- [innodb_buffer_pool_size – MySQL Performance](https://haydenjames.io/innodb_buffer_pool_size-mysql-performance/)
- [Databases: Setting innodb_buffer_pool_size in for Mysql](https://www.youtube.com/watch?v=rIxCsQYOjew)
- [How To Adjust the InnoDB Buffer Pool Size](https://support.sciencelogic.com/s/article/1151)
- [Tuning innodb_buffer_pool_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_size)
### innodb_flush_log_at_trx_commit
- [Is it safe to use innodb_flush_log_at_trx_commit = 2?](https://dba.stackexchange.com/questions/12611/is-it-safe-to-use-innodb-flush-log-at-trx-commit-2)
- [innodb_flush_log_at_trx_commit: Optimizing MySQL](https://haydenjames.io/innodb_flush_method-innodb_flush_log_at_trx_commit-optimizing-mysql/)
- [Description of innodb_flush_log_at_trx_commit and sync_binlog](https://support.huaweicloud.com/intl/en-us/bestpractice-rds/rds_02_0010.html)
- [Databases: MySQL innodb_flush_log_at_trx_commit clarification](https://www.youtube.com/watch?v=05zW-wFXNj8)
- [Tuning innodb_flush_log_at_trx_commit](https://releem.com/docs/mysql-performance-tuning/innodb_flush_log_at_trx_commit)
### innodb_flush_method
- [innodb_flush_method: Optimizing MySQL](https://haydenjames.io/innodb_flush_method-innodb_flush_log_at_trx_commit-optimizing-mysql/)
- [MySQL variable innodb_flush_method – summarized](https://kedar.nitty-witty.com/blog/mysql-variable-innodb_flush_method-summarized)
- [Clarification on MySQL innodb_flush_method variable](https://www.youtube.com/watch?v=Ak-Miuio4ks)
- [Tuning innodb_flush_method](https://releem.com/docs/mysql-performance-tuning/innodb_flush_method)
### innodb_log_file_size
- [What is a big innodb_log_file_size?](https://www.percona.com/blog/2016/05/31/what-is-a-big-innodb_log_file_size/)
- [How to safely change MySQL innodb variable 'innodb_log_file_size'?](https://www.youtube.com/watch?v=zvVIfwZRQTQ)
- [How to Choose the MySQL innodb_log_file_size](https://dzone.com/articles/how-to-choose-the-mysql-innodb-log-file-size)
- [Setting correct innodb_log_file_size in mysql](https://stackoverflow.com/questions/18806377/setting-correct-innodb-log-file-size-in-mysql)
- [Tuning innodb_log_file_size](https://releem.com/docs/mysql-performance-tuning/innodb_log_file_size)
### innodb_read_io_threads
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)
- [How to change innodb_read_io_threads in MySQL](https://notes.leetdev.net/database/mariadb/how-to-change-innodb_read_io_threads-in-mysql)
- [MySQL Performance Tuning](https://www.youtube.com/watch?v=0CqMv0ucqFA)
- [Tuning innodb_read_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_read_io_threads)
### innodb_write_io_threads
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)
- [How to change innodb_write_io_threads in MySQL](https://notes.leetdev.net/database/mariadb/how-to-change-innodb_write_io_threads-in-mysql)
- [MySQL Server Configuration for High Performance](https://www.youtube.com/watch?v=d37_2tFPstU)
- [Tuning innodb_write_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_write_io_threads)
### join_buffer_size
- [MySQL join_buffer_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_join_buffer_size)
- [How to change join_buffer_size in MySQL](https://ixnfo.com/en/how-to-change-join_buffer_size-in-mysql.html)
- [join_buffer_size ＞= 4 M is not advised?](https://www.youtube.com/watch?v=1MPN-smayhU)
- [Tuning join_buffer_size](https://releem.com/docs/mysql-performance-tuning/join_buffer_size)
### key_buffer_size
- [MySQL key_buffer_size](https://www.educba.com/mysql-key-buffer-size/)
- [MySQL: Is it safe to set key_buffer_size to 0 if the db doesn't have any MyISAM table?](https://dba.stackexchange.com/questions/240210/mysql-is-it-safe-to-set-key-buffer-size-to-0-if-the-db-doesnt-have-any-myisa)
- [Should I increase my key_buffer_size?](https://www.youtube.com/watch?v=5yEULP9d3l0)
- [Tuning key_buffer_size](https://releem.com/docs/mysql-performance-tuning/key_buffer_size)
### max_allowed_packet
- [max_allowed_packet in mySQL](https://dba.stackexchange.com/questions/45087/max-allowed-packet-in-mysql)
- [How to change max_allowed_packet size](https://stackoverflow.com/questions/8062496/how-to-change-max-allowed-packet-size)
- [Increase max_allowed_packet Size in MySQL](https://wp-staging.com/docs/increase-max_allowed_packet-size-in-mysql)
- [How to change max allowed packet size for mysql](https://www.youtube.com/watch?v=zDaaG8hFYlk)
- [Tuning max_allowed_packet](https://releem.com/docs/mysql-performance-tuning/max_allowed_packet)
### max_connections
- [What does max_connections really mean?)(https://stackoverflow.com/questions/8686291/what-does-max-connections-really-mean)
- [Mysql - when increase 'max_connections', what other paramters to adjust accordingly?(https://dba.stackexchange.com/questions/282622/mysql-when-increase-max-connections-what-other-paramters-to-adjust-accordin)
- [MySQL : How to increase the MySQL max connections value](https://www.youtube.com/watch?v=tEHzwkgOzAQ)
- [Tuning max_connections](https://releem.com/docs/mysql-performance-tuning/max_connections)
### max_heap_table_size
- [Mysql max_heap_table_size](https://stackoverflow.com/questions/13259275/mysql-tmp-table-size-max-heap-table-size)
- [Change max_heap_table_size value in MySQL?](https://www.tutorialspoint.com/change-max-heap-table-size-value-in-mysql)
- [MySQL : Mysql tmp_table_size max_heap_table_size](https://www.youtube.com/watch?v=4cVS3rgCSR0)
- [Tuning max_heap_table_size](https://releem.com/docs/mysql-performance-tuning/max_heap_table_size)
### read_rnd_buffer_size
- [MySQL: What read_buffer_size Value is Optimal?](https://www.percona.com/blog/2007/09/17/mysql-what-read_buffer_size-value-is-optimal/)
- [How to determine the optimal sort_buffer_size?](https://dba.stackexchange.com/questions/60078/how-to-determine-the-optimal-sort-buffer-size)
- [MySQL performance tuning](https://www.youtube.com/watch?v=RMwCrtqvkM0)
- [Tuning read_rnd_buffer_size](https://releem.com/docs/mysql-performance-tuning/read_rnd_buffer_size)
### sort_buffer_size
- [MySQL sort_buffer_size](https://www.educba.com/mysql-sort_buffer_size/)
- [How to determine the optimal sort_buffer_size?](https://dba.stackexchange.com/questions/60078/how-to-determine-the-optimal-sort-buffer-size)
- [Sort Buffer Size on MySQL](https://docs.digitalocean.com/products/databases/mysql/concepts/sort-buffer-size/)
- [How to determine the optimal sort_buffer_size?](https://www.youtube.com/watch?v=s-FGH4YQ_Ms)
- [Tuning sort_buffer_size](https://releem.com/docs/mysql-performance-tuning/sort_buffer_size)
### thread_cache_size
- [What value of thread_cache_size should I use?](https://serverfault.com/questions/408845/what-value-of-thread-cache-size-should-i-use)
- [What is thread_cache_size in MySQL?](https://www.quora.com/What-is-thread_cache_size-in-MySQL)
- [Changing thread_cache_size in MySQL](https://ixnfo.com/en/changing-thread_cache_size-in-mysql.html)
- [What exactly is a "thread" in thread_cache_size?](https://www.youtube.com/watch?v=pr_mS4C-0Dc)
- [Tuning thread_cache_size](https://releem.com/docs/mysql-performance-tuning/thread_cache_size)
### thread_pool_size
- [Optimum thread_pool_size](https://forums.percona.com/t/optimum-thread-pool-size/11417)
- [How to set an ideal thread pool size](https://engineering.zalando.com/posts/2019/04/how-to-set-an-ideal-thread-pool-size.html)
- [MariaDB thread_pool_size tuning](https://dba.stackexchange.com/questions/196751/mariadb-thread-pool-size-tuning)
- [Databases: MariaDB thread_pool_size tuning](https://www.youtube.com/watch?v=KFexyFb1qLo)
- [Tuning thread_pool_size](https://releem.com/docs/mysql-performance-tuning/thread_pool_size)
### tmp_table_size
- [Rule of thumb for tmp_table_size MySQL properties](https://dba.stackexchange.com/questions/209411/rule-of-thumb-for-tmp-table-size-and-max-heap-table-size-mysql-properties)
- [tmp_table_size](https://www.percona.com/blog/2007/01/19/tmp_table_size-and-max_heap_table_size/)
- [Rule of thumb for tmp_table_size and max_heap_table_size MySQL properties](https://www.youtube.com/watch?v=nPplCK7Cs94)
- [Tuning tmp_table_size](https://releem.com/docs/mysql-performance-tuning/tmp_table_size)
### table_open_cache
- [Easy Way to optimize MySQL Table Open_cache variable](https://mysqlwall.com/2018/06/27/easy-way-to-optimize-mysql-table-open_cache/)
- [Increase the table open cache size](https://cloud.google.com/sql/docs/mysql/recommender-high-number-of-open-tables)
- [Databases: mariadb / mysql wont change table_cache / table_open_cache](https://www.youtube.com/watch?v=LhDoqnFf710)
- [Tuning table_open_cache](https://releem.com/docs/mysql-performance-tuning/table_open_cache)
### bulk_insert_buffer_size
- [How to set bulk_insert_buffer_size in mysql?](https://dba.stackexchange.com/questions/54197/how-to-set-bulk-insert-buffer-size-in-mysql)
- [Databases: How to set bulk_insert_buffer_size in mysql?](https://www.youtube.com/watch?v=Iz4R2oAI5Dc)
- [Tuning bulk_insert_buffer_size](https://releem.com/docs/mysql-performance-tuning/bulk_insert_buffer_size)
## Talks

- [MySQL Performance Tuning: Part 1. Configuration (Covers MySQL 5.7)](https://www.youtube.com/watch?v=0CqMv0ucqFA)

## Configuration

- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - A script that allows you to review a MySQL installation quickly and make recommendations to increase performance and stability.
- [Releem](https://releem.com) - MySQL Performance Tuning as a Service. Releem helps you to automatically monitor MySQL metrics, and tune MySQL configuration to improve performance and reduce costs of server resources.
