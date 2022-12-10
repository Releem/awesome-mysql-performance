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
### innodb_buffer_pool_instances

### innodb_buffer_pool_size
- [Is InnoDB Buffer Pool big enough?](https://vettabase.com/blog/is-innodb-buffer-pool-big-enough/) and [Can we shrink InnoDB Buffer Pool?](https://vettabase.com/blog/can-we-shrink-innodb-buffer-pool/)
### innodb_flush_log_at_trx_commit

### innodb_flush_method

### innodb_log_file_size
- [What is a big innodb_log_file_size?](https://www.percona.com/blog/2016/05/31/what-is-a-big-innodb_log_file_size/)
### innodb_read_io_threads

### innodb_write_io_threads

### join_buffer_size

### key_buffer_size

### max_allowed_packet

### max_connections

### max_heap_table_size

### read_rnd_buffer_size

### sort_buffer_size

### thread_cache_size

### thread_pool_size

### tmp_table_size

### table_open_cache
- [Tuning table_open_cache](https://mariadb.com/kb/en/optimizing-table_open_cache/#:~:text=This%20improves%20performance%2C%20although%20it,any%20one%20table%20cache%20instance.&text=If%20the%20number%20of%20opened,at%20increasing%20the%20table_open_cache%20value.)

## Talks

- [MySQL Performance Tuning: Part 1. Configuration (Covers MySQL 5.7)](https://www.youtube.com/watch?v=0CqMv0ucqFA)

## Configuration

- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - A script that allows you to review a MySQL installation quickly and make recommendations to increase performance and stability.
- [Releem](https://releem.com) - MySQL Performance Tuning as a Service. Releem helps you to automatically monitor MySQL metrics, and tune MySQL configuration to improve performance and reduce costs of server resources.
