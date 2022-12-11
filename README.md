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
- [Tuning innodb_buffer_pool_chunk_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_chunk_size)
### innodb_buffer_pool_instances
- [Tuning innodb_buffer_pool_instances](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_instances)
- [How Many innodb_buffer_pool_instances Do You Need in MySQL 8?](https://www.percona.com/blog/2020/08/13/how-many-innodb_buffer_pool_instances-do-you-need-in-mysql-8/)
### innodb_buffer_pool_size
- [Tuning innodb_buffer_pool_size](https://releem.com/docs/mysql-performance-tuning/innodb_buffer_pool_size)
- [Innodb_buffer_pool_size – Is 80% of RAM the right amount?](https://www.percona.com/blog/2015/06/02/80-ram-tune-innodb_buffer_pool_size/)
- [Is InnoDB Buffer Pool big enough?](https://vettabase.com/blog/is-innodb-buffer-pool-big-enough/) and [Can we shrink InnoDB Buffer Pool?](https://vettabase.com/blog/can-we-shrink-innodb-buffer-pool/)
### innodb_flush_log_at_trx_commit
- [Tuning innodb_flush_log_at_trx_commit](https://releem.com/docs/mysql-performance-tuning/innodb_flush_log_at_trx_commit)
- [Is it safe to use innodb_flush_log_at_trx_commit = 2?](https://dba.stackexchange.com/questions/12611/is-it-safe-to-use-innodb-flush-log-at-trx-commit-2)
### innodb_flush_method
- [Tuning innodb_flush_method](https://releem.com/docs/mysql-performance-tuning/innodb_flush_method)
- [MySQL (innodb) performance tuning](https://www.ilsistemista.net/index.php/linux-a-unix/26-mysql-performance-tuning.html?start=4)
### innodb_log_file_size
- [What is a big innodb_log_file_size?](https://www.percona.com/blog/2016/05/31/what-is-a-big-innodb_log_file_size/)
- [Tuning innodb_log_file_size](https://releem.com/docs/mysql-performance-tuning/innodb_log_file_size)
### innodb_read_io_threads
- [Tuning innodb_read_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_read_io_threads)
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)
### innodb_write_io_threads
- [Tuning innodb_write_io_threads](https://releem.com/docs/mysql-performance-tuning/innodb_write_io_threads)
- [How do you tune innodb_read_io_threads?](https://dba.stackexchange.com/questions/299461/how-do-you-tune-innodb-read-io-threads)
### join_buffer_size
- [Tuning join_buffer_size](https://releem.com/docs/mysql-performance-tuning/join_buffer_size)
- [Tuning MySQL my.cnf? Avoid this common pitfall!](https://haydenjames.io/my-cnf-tuning-avoid-this-common-pitfall/)
### key_buffer_size
- [Tuning key_buffer_size](https://releem.com/docs/mysql-performance-tuning/key_buffer_size)
- [Optimizing key_buffer_size](https://mariadb.com/kb/en/optimizing-key_buffer_size/)
### max_allowed_packet
- [Tuning max_allowed_packet](https://releem.com/docs/mysql-performance-tuning/max_allowed_packet)
- [How to change max_allowed_packet size](https://stackoverflow.com/questions/8062496/how-to-change-max-allowed-packet-size)
### max_connections
- [Tuning max_connections](https://releem.com/docs/mysql-performance-tuning/max_connections)
- [Max Connection Tuning with MariaDB Enterprise Server](https://mariadb.com/docs/skysql/connect/connections/max-connections/es/)
### max_heap_table_size
- [Tuning max_heap_table_size](https://releem.com/docs/mysql-performance-tuning/max_heap_table_size)
- [Rule of thumb for tmp_table_size and max_heap_table_size MySQL properties](https://dba.stackexchange.com/questions/209411/rule-of-thumb-for-tmp-table-size-and-max-heap-table-size-mysql-properties)
### read_rnd_buffer_size
- [Tuning read_rnd_buffer_size](https://releem.com/docs/mysql-performance-tuning/read_rnd_buffer_size)
- [MySQL: What read_buffer_size Value is Optimal?](https://www.percona.com/blog/2007/09/17/mysql-what-read_buffer_size-value-is-optimal/)
### sort_buffer_size
- [Tuning sort_buffer_size](https://releem.com/docs/mysql-performance-tuning/sort_buffer_size)
- [MySQL sort_buffer_size](https://www.educba.com/mysql-sort_buffer_size/)
### thread_cache_size
- [Tuning thread_cache_size](https://releem.com/docs/mysql-performance-tuning/thread_cache_size)
- [MySQL Optimization Tip – Thread Cache Size](https://www.navisite.com/blog/mysql-optimization-tip-thread-cache-size/)
### thread_pool_size
- [Tuning thread_pool_size](https://releem.com/docs/mysql-performance-tuning/thread_pool_size)
- [Thread Pool Tuning](https://dev.mysql.com/doc/refman/8.0/en/thread-pool-tuning.html)
### tmp_table_size
- [Tuning tmp_table_size](https://releem.com/docs/mysql-performance-tuning/tmp_table_size)
- [MySQL tmp_table_size optimization settings for how much appropriate _mysql](https://topic.alibabacloud.com/a/mysql-tmp_table_size-optimization-settings-for-how-much-appropriate-_mysql_1_41_20122890.html)
### table_open_cache
- [Tuning table_open_cache](https://releem.com/docs/mysql-performance-tuning/table_open_cache)
- [Optimize table_open_cache](https://mariadb.com/kb/en/optimizing-table_open_cache)
### bulk_insert_buffer_size
- [Tuning bulk_insert_buffer_size](https://releem.com/docs/mysql-performance-tuning/bulk_insert_buffer_size)
- [How to set bulk_insert_buffer_size in mysql?](https://dba.stackexchange.com/questions/54197/how-to-set-bulk-insert-buffer-size-in-mysql)

## Talks

- [MySQL Performance Tuning: Part 1. Configuration (Covers MySQL 5.7)](https://www.youtube.com/watch?v=0CqMv0ucqFA)

## Configuration

- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - A script that allows you to review a MySQL installation quickly and make recommendations to increase performance and stability.
- [Releem](https://releem.com) - MySQL Performance Tuning as a Service. Releem helps you to automatically monitor MySQL metrics, and tune MySQL configuration to improve performance and reduce costs of server resources.
