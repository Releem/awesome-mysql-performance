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
- [Configuring InnoDB Buffer Pool Size](https://dev.mysql.com/doc/refman/5.7/en/innodb-buffer-pool-resize.html)																									
- [Setting Innodb Buffer Pool Size Dynamically](https://mariadb.com/kb/en/setting-innodb-buffer-pool-size-dynamically/)																									
- [MySQL InnoDB buffer pool configuration | Role of InnoDB buffer pool chunk size and Instances](https://www.youtube.com/watch?v=c-xyooZyPW0)																									
- [Tuning innodb_buffer_pool_chunk_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_chunk_size)																									
### innodb_buffer_pool_instances																									
- [How Many innodb_buffer_pool_instances Do You Need in MySQL 8?](https://www.percona.com/blog/2020/08/13/how-many-innodb_buffer_pool_instances-do-you-need-in-mysql-8/)																									
- [Configuring Multiple Buffer Pool Instances](https://dev.mysql.com/doc/refman/5.6/en/innodb-multiple-buffer-pools.html)																									
- [InnoDB Buffer Pool](https://mariadb.com/kb/en/innodb-buffer-pool/#innodb_buffer_pool_instances)																									
- [MySQL InnoDB buffer pool configuration | Role of InnoDB buffer pool chunk size and Instances](https://www.youtube.com/watch?v=c-xyooZyPW0)																									
- [Tuning innodb_buffer_pool_instances](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_instances)																									
### innodb_buffer_pool_size																									
- [How large should be mysql innodb_buffer_pool_size?](https://dba.stackexchange.com/questions/27328/how-large-should-be-mysql-innodb-buffer-pool-size)																									
- [Is InnoDB Buffer Pool big enough?](https://vettabase.com/blog/is-innodb-buffer-pool-big-enough/) and [Can we shrink InnoDB Buffer Pool?](https://vettabase.com/blog/can-we-shrink-innodb-buffer-pool/)																									
- [InnoDB Buffer Pool](https://mariadb.com/kb/en/innodb-buffer-pool/#innodb_buffer_pool_size)																									
- [Databases: Setting innodb_buffer_pool_size in for Mysql](https://www.youtube.com/watch?v=rIxCsQYOjew)																									
- [Tuning innodb_buffer_pool_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_size)																									
### innodb_flush_log_at_trx_commit																									
- [Is it safe to use innodb_flush_log_at_trx_commit = 2?](https://dba.stackexchange.com/questions/12611/is-it-safe-to-use-innodb-flush-log-at-trx-commit-2)																									
- [MariaDB innodb_flush_log_at_trx_commit](https://mariadb.com/docs/server/ref/mdb/system-variables/innodb_flush_log_at_trx_commit/)																									
- [Description of innodb_flush_log_at_trx_commit and sync_binlog](https://support.huaweicloud.com/intl/en-us/bestpractice-rds/rds_02_0010.html)																									
- [Tuning innodb_flush_log_at_trx_commit](https://releem.com/docs/mysql-performance-tuning/innodb_flush_log_at_trx_commit)																									
- [Databases: MySQL innodb_flush_log_at_trx_commit clarification](https://www.youtube.com/watch?v=05zW-wFXNj8)																									
### innodb_flush_method																									
- [MySQL (innodb) performance tuning](https://www.ilsistemista.net/index.php/linux-a-unix/26-mysql-performance-tuning.html?start=4)																									
- [MariaDB innodb_flush_method](https://mariadb.com/kb/en/innodb-system-variables/#innodb_flush_method)																									
- [MySQL innodb_flush_method](https://dev.mysql.com/doc/refman/8.0/en/innodb-parameters.html#sysvar_innodb_flush_method)																									
- [Clarification on MySQL innodb_flush_method variable](https://www.youtube.com/watch?v=Ak-Miuio4ks)																									
- [Tuning innodb_flush_method](https://releem.com/docs/mysql-performance-tuning/innodb_flush_method)																									
### innodb_log_file_size																									
- [What is a big innodb_log_file_size?](https://www.percona.com/blog/2016/05/31/what-is-a-big-innodb_log_file_size/)																									
- [MySQL innodb_log_file_size](https://dev.mysql.com/doc/refman/5.6/en/innodb-parameters.html#sysvar_innodb_log_file_size)																									
- [MariaDB innodb_log_file_size](https://mariadb.com/kb/en/innodb-system-variables/#innodb_log_file_size)																									
- [How to safely change MySQL innodb variable 'innodb_log_file_size'?](https://www.youtube.com/watch?v=zvVIfwZRQTQ)																									
- [Tuning innodb_log_file_size](https://releem.com/docs/mysql-performance-tuning/innodb_log_file_size)																									
### innodb_read_io_threads																									
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)																									
- [MySQL innodb_read_io_threads](https://dev.mysql.com/doc/refman/8.0/en/innodb-parameters.html#sysvar_innodb_read_io_threads)																									
- [MariaDB innodb_read_io_threads](https://mariadb.com/kb/en/innodb-system-variables/#innodb_read_io_threads)																									
- [MySQL Performance Tuning](https://www.youtube.com/watch?v=0CqMv0ucqFA)																									
- [Tuning innodb_read_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_read_io_threads)																									
### innodb_write_io_threads																									
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)																									
- [MySQL innodb_write_io_threads](https://dev.mysql.com/doc/refman/8.0/en/innodb-parameters.html#sysvar_innodb_write_io_threads)																									
- [MariaDB innodb_write_io_thread](https://mariadb.com/docs/skysql/ref/mdb/system-variables/innodb_write_io_threads/)																									
- [MySQL Server Configuration for High Performance](https://www.youtube.com/watch?v=d37_2tFPstU)																									
- [Tuning innodb_write_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_write_io_threads)																									
### join_buffer_size																									
- [MySQL join_buffer_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_join_buffer_size)																									
- [MySQL Database Performance: Avoid this common mistake](https://haydenjames.io/mysql-database-performance-avoid-this-common-mistake/)																									
- [MariaDB join_buffer_size](https://mariadb.com/docs/skysql/ref/mdb/system-variables/join_buffer_size/)																									
- [join_buffer_size ＞= 4 M is not advised?](https://www.youtube.com/watch?v=1MPN-smayhU)																									
- [Tuning join_buffer_size](https://releem.com/docs/mysql-performance-tuning/join_buffer_size)																									
### key_buffer_size																									
- [Optimizing key_buffer_size](https://mariadb.com/kb/en/optimizing-key_buffer_size/)																									
- [MySQL key_buffer_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_key_buffer_size)																									
- [MySQL: Is it safe to set key_buffer_size to 0 if the db doesn't have any MyISAM table?](https://dba.stackexchange.com/questions/240210/mysql-is-it-safe-to-set-key-buffer-size-to-0-if-the-db-doesnt-have-any-myisa)																									
- [Should I increase my key_buffer_size?](https://www.youtube.com/watch?v=5yEULP9d3l0)																									
- [Tuning key_buffer_size](https://releem.com/docs/mysql-performance-tuning/key_buffer_size)																									
### max_allowed_packet																									
- [How to change max_allowed_packet size](https://stackoverflow.com/questions/8062496/how-to-change-max-allowed-packet-size)																									
- [MariaDB max_allowed_packet](https://mariadb.com/docs/server/ref/mdb/system-variables/max_allowed_packet/)																									
- [MySQL max_allowed_packet](https://dev.mysql.com/doc/refman/8.0/en/packet-too-large.html)																									
- [How to change max allowed packet size for mysql](https://www.youtube.com/watch?v=zDaaG8hFYlk)																									
- [Tuning max_allowed_packet](https://releem.com/docs/mysql-performance-tuning/max_allowed_packet)																									
### max_connections																									
- [Max Connection Tuning with MariaDB Enterprise Server](https://mariadb.com/docs/skysql/connect/connections/max-connections/es/)																									
- [MySQL max_connections](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_max_connections)																									
- [MySQL : How to increase the MySQL max connections value](https://www.youtube.com/watch?v=tEHzwkgOzAQ)																									
- [MariaDB max_connections](https://mariadb.com/docs/skysql/ref/mdb/system-variables/max_connections/)																									
- [Tuning max_connections](https://releem.com/docs/mysql-performance-tuning/max_connections)																									
### max_heap_table_size																									
- [MySQL max_heap_table_size](https://dev.mysql.com/doc/refman/5.7/en/server-system-variables.html#sysvar_max_heap_table_size)																									
- [MariaDB max_heap_table_size](https://mariadb.com/docs/skysql/ref/mdb/system-variables/max_heap_table_size/)																									
- [Change max_heap_table_size value in MySQL?](https://www.tutorialspoint.com/change-max-heap-table-size-value-in-mysql)																									
- [MySQL : Mysql tmp_table_size max_heap_table_size](https://www.youtube.com/watch?v=4cVS3rgCSR0)																									
- [Tuning max_heap_table_size](https://releem.com/docs/mysql-performance-tuning/max_heap_table_size)																									
### read_rnd_buffer_size																									
- [MySQL: What read_buffer_size Value is Optimal?](https://www.percona.com/blog/2007/09/17/mysql-what-read_buffer_size-value-is-optimal/)																									
- [MySQL read_rnd_buffer_size](https://dev.mysql.com/doc/refman/5.7/en/server-system-variables.html#sysvar_read_rnd_buffer_size)																									
- [How to optimize MySQL performance](https://www.woktron.com/secure/knowledgebase/272/How-to-optimize-MySQL-performance.html)																									
- [MySQL performance tuning](https://www.youtube.com/watch?v=RMwCrtqvkM0)																									
- [Tuning read_rnd_buffer_size](https://releem.com/docs/mysql-performance-tuning/read_rnd_buffer_size)																									
### sort_buffer_size																									
- [MySQL sort_buffer_size](https://www.educba.com/mysql-sort_buffer_size/)																									
- [MySQL sort_buffer_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_sort_buffer_size)																									
- [MariaDB sort_buffer_size](https://mariadb.com/docs/skysql/ref/mdb/system-variables/sort_buffer_size/)																									
- [How to determine the optimal sort_buffer_size?](https://www.youtube.com/watch?v=s-FGH4YQ_Ms)																									
- [Tuning sort_buffer_size](https://releem.com/docs/mysql-performance-tuning/sort_buffer_size)																									
### thread_cache_size																									
- [MySQL thread_cache_size](https://dev.mysql.com/doc/refman/5.7/en/server-system-variables.html#sysvar_thread_cache_size)																									
- [Changing thread_cache_size in MySQL](https://ixnfo.com/en/changing-thread_cache_size-in-mysql.html)																									
- [MariaDB thread_cache_size](https://mariadb.com/docs/server/ref/mdb/system-variables/thread_cache_size/)																									
- [What exactly is a "thread" in thread_cache_size?](https://www.youtube.com/watch?v=pr_mS4C-0Dc)																									
- [Tuning thread_cache_size](https://releem.com/docs/mysql-performance-tuning/thread_cache_size)																									
### thread_pool_size																									
- [Thread Pool Tuning](https://dev.mysql.com/doc/refman/8.0/en/thread-pool-tuning.html)																									
- [Optimum thread_pool_size](https://forums.percona.com/t/optimum-thread-pool-size/11417)																									
- [MariaDB thread_pool_size tuning](https://dba.stackexchange.com/questions/196751/mariadb-thread-pool-size-tuning)																									
- [Databases: MariaDB thread_pool_size tuning](https://www.youtube.com/watch?v=KFexyFb1qLo)																									
- [Tuning thread_pool_size](https://releem.com/docs/mysql-performance-tuning/thread_pool_size)																									
### tmp_table_size																									
- [MySQL tmp_table_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_tmp_table_size)																									
- [MariaDB tmp_table_size](https://mariadb.com/docs/server/ref/mdb/system-variables/tmp_table_size/)																									
- [tmp_table_size and max_heap_table_size](https://www.percona.com/blog/2007/01/19/tmp_table_size-and-max_heap_table_size/)																									
- [Rule of thumb for tmp_table_size and max_heap_table_size MySQL properties](https://www.youtube.com/watch?v=nPplCK7Cs94)																									
- [Tuning tmp_table_size](https://releem.com/docs/mysql-performance-tuning/tmp_table_size)																									
### table_open_cache																									
- [Optimize table_open_cache](https://mariadb.com/kb/en/optimizing-table_open_cache)																									
- [MySQL table_open_cache](https://dev.mysql.com/doc/refman/5.6/en/server-system-variables.html#sysvar_table_open_cache)																									
- [Increase the table open cache size](https://cloud.google.com/sql/docs/mysql/recommender-high-number-of-open-tables)																									
- [Databases: mariadb / mysql wont change table_cache / table_open_cache](https://www.youtube.com/watch?v=LhDoqnFf710)																									
- [Tuning table_open_cache](https://releem.com/docs/mysql-performance-tuning/table_open_cache)																									
### bulk_insert_buffer_size																									
- [How to set bulk_insert_buffer_size in mysql?](https://dba.stackexchange.com/questions/54197/how-to-set-bulk-insert-buffer-size-in-mysql)																									
- [MySQL bulk_insert_buffer_size](https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_bulk_insert_buffer_size)																									
- [MariaDB bulk_insert_buffer_size](https://mariadb.com/docs/skysql/ref/mdb/system-variables/bulk_insert_buffer_size/)																									
- [Databases: How to set bulk_insert_buffer_size in mysql?](https://www.youtube.com/watch?v=Iz4R2oAI5Dc)																									
- [Tuning bulk_insert_buffer_size](https://releem.com/docs/mysql-performance-tuning/bulk_insert_buffer_size)																									
																									
## Talks																									
																									
- [MySQL Performance Tuning: Part 1. Configuration (Covers MySQL 5.7)](https://www.youtube.com/watch?v=0CqMv0ucqFA)																									
																									
## Configuration																									
																									
- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - A script that allows you to review a MySQL installation quickly and make recommendations to increase performance and stability.																									
- [Releem](https://releem.com) - MySQL Performance Tuning as a Service. Releem helps you to automatically monitor MySQL metrics, and tune MySQL configuration to improve performance and reduce costs of server resources.																									
- [Releem](https://releem.com) - MySQL Performance Tuning as a Service. Releem helps you to automatically monitor MySQL metrics, and tune MySQL configuration to improve performance and reduce costs of server resources.													
