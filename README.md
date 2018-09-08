# docker-compose file whit: 

- mongo:3.2.18
- targetprocess/mongodb_exporter:latest
- image: prom/prometheus:latest


# Metrics on localhost:9001

# HELP go_gc_duration_seconds A summary of the GC invocation durations.
# TYPE go_gc_duration_seconds summary
go_gc_duration_seconds{quantile="0"} 8.7291e-05
go_gc_duration_seconds{quantile="0.25"} 0.000274314
go_gc_duration_seconds{quantile="0.5"} 0.00031858900000000004
go_gc_duration_seconds{quantile="0.75"} 0.000418816
go_gc_duration_seconds{quantile="1"} 0.006044172
go_gc_duration_seconds_sum 0.033925797
go_gc_duration_seconds_count 79
# HELP go_goroutines Number of goroutines that currently exist.
# TYPE go_goroutines gauge
go_goroutines 20
# HELP go_memstats_alloc_bytes Number of bytes allocated and still in use.
# TYPE go_memstats_alloc_bytes gauge
go_memstats_alloc_bytes 3.240632e+06
# HELP go_memstats_alloc_bytes_total Total number of bytes allocated, even if freed.
# TYPE go_memstats_alloc_bytes_total counter
go_memstats_alloc_bytes_total 2.05154392e+08
# HELP go_memstats_buck_hash_sys_bytes Number of bytes used by the profiling bucket hash table.
# TYPE go_memstats_buck_hash_sys_bytes gauge
go_memstats_buck_hash_sys_bytes 1.454414e+06
# HELP go_memstats_frees_total Total number of frees.
# TYPE go_memstats_frees_total counter
go_memstats_frees_total 748474
# HELP go_memstats_gc_sys_bytes Number of bytes used for garbage collection system metadata.
# TYPE go_memstats_gc_sys_bytes gauge
go_memstats_gc_sys_bytes 292864
# HELP go_memstats_heap_alloc_bytes Number of heap bytes allocated and still in use.
# TYPE go_memstats_heap_alloc_bytes gauge
go_memstats_heap_alloc_bytes 3.240632e+06
# HELP go_memstats_heap_idle_bytes Number of heap bytes waiting to be used.
# TYPE go_memstats_heap_idle_bytes gauge
go_memstats_heap_idle_bytes 3.93216e+06
# HELP go_memstats_heap_inuse_bytes Number of heap bytes that are in use.
# TYPE go_memstats_heap_inuse_bytes gauge
go_memstats_heap_inuse_bytes 3.964928e+06
# HELP go_memstats_heap_objects Number of allocated objects.
# TYPE go_memstats_heap_objects gauge
go_memstats_heap_objects 8970
# HELP go_memstats_heap_released_bytes_total Total number of heap bytes released to OS.
# TYPE go_memstats_heap_released_bytes_total counter
go_memstats_heap_released_bytes_total 0
# HELP go_memstats_heap_sys_bytes Number of heap bytes obtained from system.
# TYPE go_memstats_heap_sys_bytes gauge
go_memstats_heap_sys_bytes 7.897088e+06
# HELP go_memstats_last_gc_time_seconds Number of seconds since 1970 of last garbage collection.
# TYPE go_memstats_last_gc_time_seconds gauge
go_memstats_last_gc_time_seconds 1.5364391799164667e+09
# HELP go_memstats_lookups_total Total number of pointer lookups.
# TYPE go_memstats_lookups_total counter
go_memstats_lookups_total 2005
# HELP go_memstats_mallocs_total Total number of mallocs.
# TYPE go_memstats_mallocs_total counter
go_memstats_mallocs_total 757444
# HELP go_memstats_mcache_inuse_bytes Number of bytes in use by mcache structures.
# TYPE go_memstats_mcache_inuse_bytes gauge
go_memstats_mcache_inuse_bytes 4800
# HELP go_memstats_mcache_sys_bytes Number of bytes used for mcache structures obtained from system.
# TYPE go_memstats_mcache_sys_bytes gauge
go_memstats_mcache_sys_bytes 16384
# HELP go_memstats_mspan_inuse_bytes Number of bytes in use by mspan structures.
# TYPE go_memstats_mspan_inuse_bytes gauge
go_memstats_mspan_inuse_bytes 24720
# HELP go_memstats_mspan_sys_bytes Number of bytes used for mspan structures obtained from system.
# TYPE go_memstats_mspan_sys_bytes gauge
go_memstats_mspan_sys_bytes 32768
# HELP go_memstats_next_gc_bytes Number of heap bytes when next garbage collection will take place.
# TYPE go_memstats_next_gc_bytes gauge
go_memstats_next_gc_bytes 5.180174e+06
# HELP go_memstats_other_sys_bytes Number of bytes used for other system allocations.
# TYPE go_memstats_other_sys_bytes gauge
go_memstats_other_sys_bytes 1.290154e+06
# HELP go_memstats_stack_inuse_bytes Number of bytes in use by the stack allocator.
# TYPE go_memstats_stack_inuse_bytes gauge
go_memstats_stack_inuse_bytes 491520
# HELP go_memstats_stack_sys_bytes Number of bytes obtained from system for stack allocator.
# TYPE go_memstats_stack_sys_bytes gauge
go_memstats_stack_sys_bytes 491520
# HELP go_memstats_sys_bytes Number of bytes obtained by system. Sum of all system allocations.
# TYPE go_memstats_sys_bytes gauge
go_memstats_sys_bytes 1.1475192e+07
# HELP http_request_duration_microseconds The HTTP request latencies in microseconds.
# TYPE http_request_duration_microseconds summary
http_request_duration_microseconds{handler="prometheus",quantile="0.5"} 10736.32
http_request_duration_microseconds{handler="prometheus",quantile="0.9"} 12701.819
http_request_duration_microseconds{handler="prometheus",quantile="0.99"} 19023.315
http_request_duration_microseconds_sum{handler="prometheus"} 1.298967334e+06
http_request_duration_microseconds_count{handler="prometheus"} 120
# HELP http_request_size_bytes The HTTP request sizes in bytes.
# TYPE http_request_size_bytes summary
http_request_size_bytes{handler="prometheus",quantile="0.5"} 172
http_request_size_bytes{handler="prometheus",quantile="0.9"} 172
http_request_size_bytes{handler="prometheus",quantile="0.99"} 172
http_request_size_bytes_sum{handler="prometheus"} 20640
http_request_size_bytes_count{handler="prometheus"} 120
# HELP http_requests_total Total number of HTTP requests made.
# TYPE http_requests_total counter
http_requests_total{code="200",handler="prometheus",method="get"} 120
# HELP http_response_size_bytes The HTTP response sizes in bytes.
# TYPE http_response_size_bytes summary
http_response_size_bytes{handler="prometheus",quantile="0.5"} 5126
http_response_size_bytes{handler="prometheus",quantile="0.9"} 5133
http_response_size_bytes{handler="prometheus",quantile="0.99"} 5139
http_response_size_bytes_sum{handler="prometheus"} 614150
http_response_size_bytes_count{handler="prometheus"} 120
# HELP mongodb_asserts_total The asserts document reports the number of asserts on the database. While assert errors are typically uncommon, if there are non-zero values for the asserts, you should check the log file for the mongod process for more information. In many cases these errors are trivial, but are worth investigating.
# TYPE mongodb_asserts_total counter
mongodb_asserts_total{type="msg"} 0
mongodb_asserts_total{type="regular"} 0
mongodb_asserts_total{type="rollovers"} 0
mongodb_asserts_total{type="user"} 0
mongodb_asserts_total{type="warning"} 0
# HELP mongodb_connections The connections sub document data regarding the current status of incoming connections and availability of the database server. Use these values to assess the current load and capacity requirements of the server
# TYPE mongodb_connections gauge
mongodb_connections{state="available"} 838859
mongodb_connections{state="current"} 1
# HELP mongodb_connections_metrics_created_total totalCreated provides a count of all incoming connections created to the server. This number includes connections that have since closed
# TYPE mongodb_connections_metrics_created_total counter
mongodb_connections_metrics_created_total 121
# HELP mongodb_extra_info_heap_usage_bytes The heap_usage_bytes field is only available on Unix/Linux systems, and reports the total size in bytes of heap space used by the database process
# TYPE mongodb_extra_info_heap_usage_bytes gauge
mongodb_extra_info_heap_usage_bytes 6.2117584e+07
# HELP mongodb_extra_info_page_faults_total The page_faults Reports the total number of page faults that require disk operations. Page faults refer to operations that require the database server to access data which isn't available in active memory. The page_faults counter may increase dramatically during moments of poor performance and may correlate with limited memory environments and larger data sets. Limited and sporadic page faults do not necessarily indicate an issue
# TYPE mongodb_extra_info_page_faults_total gauge
mongodb_extra_info_page_faults_total 0
# HELP mongodb_global_lock_client The activeClients data structure provides more granular information about the number of connected clients and the operation types (e.g. read or write) performed by these clients
# TYPE mongodb_global_lock_client gauge
mongodb_global_lock_client{type="reader"} 0
mongodb_global_lock_client{type="writer"} 0
# HELP mongodb_global_lock_current_queue The currentQueue data structure value provides more granular information concerning the number of operations queued because of a lock
# TYPE mongodb_global_lock_current_queue gauge
mongodb_global_lock_current_queue{type="reader"} 0
mongodb_global_lock_current_queue{type="writer"} 0
# HELP mongodb_global_lock_ratio The value of ratio displays the relationship between lockTime and totalTime. Low values indicate that operations have held the globalLock frequently for shorter periods of time. High values indicate that operations have held globalLock infrequently for longer periods of time
# TYPE mongodb_global_lock_ratio gauge
mongodb_global_lock_ratio 0
# HELP mongodb_global_lock_total The value of totalTime represents the time, in microseconds, since the database last started and creation of the globalLock. This is roughly equivalent to total server uptime
# TYPE mongodb_global_lock_total counter
mongodb_global_lock_total 0
# HELP mongodb_instance_local_time The localTime value is the current time, according to the server, in UTC specified in an ISODate format.
# TYPE mongodb_instance_local_time counter
mongodb_instance_local_time 1.536439183e+09
# HELP mongodb_instance_uptime_estimate_seconds uptimeEstimate provides the uptime as calculated from MongoDB's internal course-grained time keeping system.
# TYPE mongodb_instance_uptime_estimate_seconds counter
mongodb_instance_uptime_estimate_seconds 606
# HELP mongodb_instance_uptime_seconds The value of the uptime field corresponds to the number of seconds that the mongos or mongod process has been active.
# TYPE mongodb_instance_uptime_seconds counter
mongodb_instance_uptime_seconds 606
# HELP mongodb_locks_time_acquiring_global_microseconds_total amount of time in microseconds that any database has spent waiting for the global lock
# TYPE mongodb_locks_time_acquiring_global_microseconds_total counter
mongodb_locks_time_acquiring_global_microseconds_total{database="Collection",type="read"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Collection",type="write"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Database",type="read"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Database",type="write"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Global",type="read"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Global",type="write"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Metadata",type="read"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="Metadata",type="write"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="oplog",type="read"} 0
mongodb_locks_time_acquiring_global_microseconds_total{database="oplog",type="write"} 0
# HELP mongodb_locks_time_locked_global_microseconds_total amount of time in microseconds that any database has held the global lock
# TYPE mongodb_locks_time_locked_global_microseconds_total counter
mongodb_locks_time_locked_global_microseconds_total{database="Collection",type="read"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Collection",type="write"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Database",type="read"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Database",type="write"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Global",type="read"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Global",type="write"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Metadata",type="read"} 0
mongodb_locks_time_locked_global_microseconds_total{database="Metadata",type="write"} 0
mongodb_locks_time_locked_global_microseconds_total{database="oplog",type="read"} 0
mongodb_locks_time_locked_global_microseconds_total{database="oplog",type="write"} 0
# HELP mongodb_locks_time_locked_local_microseconds_total amount of time in microseconds that any database has held the local lock
# TYPE mongodb_locks_time_locked_local_microseconds_total counter
mongodb_locks_time_locked_local_microseconds_total{database="Collection",type="read"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Collection",type="write"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Database",type="read"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Database",type="write"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Global",type="read"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Global",type="write"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Metadata",type="read"} 0
mongodb_locks_time_locked_local_microseconds_total{database="Metadata",type="write"} 0
mongodb_locks_time_locked_local_microseconds_total{database="oplog",type="read"} 0
mongodb_locks_time_locked_local_microseconds_total{database="oplog",type="write"} 0
# HELP mongodb_memory The mem data structure holds information regarding the target system architecture of mongod and current memory use
# TYPE mongodb_memory gauge
mongodb_memory{type="mapped"} 0
mongodb_memory{type="mapped_with_journal"} 0
mongodb_memory{type="resident"} 51
mongodb_memory{type="virtual"} 269
# HELP mongodb_metrics_cursor_open The open is an embedded document that contains data regarding open cursors
# TYPE mongodb_metrics_cursor_open gauge
mongodb_metrics_cursor_open{state="pinned"} 0
mongodb_metrics_cursor_open{state="timed_out"} 0
mongodb_metrics_cursor_open{state="total"} 0
# HELP mongodb_metrics_cursor_timed_out_total timedOut provides the total number of cursors that have timed out since the server process started. If this number is large or growing at a regular rate, this may indicate an application error
# TYPE mongodb_metrics_cursor_timed_out_total counter
mongodb_metrics_cursor_timed_out_total 0
# HELP mongodb_metrics_document_total The document holds a document of that reflect document access and modification patterns and data use. Compare these values to the data in the opcounters document, which track total number of operations
# TYPE mongodb_metrics_document_total counter
mongodb_metrics_document_total{state="deleted"} 0
mongodb_metrics_document_total{state="inserted"} 0
mongodb_metrics_document_total{state="returned"} 0
mongodb_metrics_document_total{state="updated"} 0
# HELP mongodb_metrics_get_last_error_wtime_num_total num reports the total number of getLastError operations with a specified write concern (i.e. w) that wait for one or more members of a replica set to acknowledge the write operation (i.e. a w value greater than 1.)
# TYPE mongodb_metrics_get_last_error_wtime_num_total gauge
mongodb_metrics_get_last_error_wtime_num_total 0
# HELP mongodb_metrics_get_last_error_wtime_total_milliseconds total_millis reports the total amount of time in milliseconds that the mongod has spent performing getLastError operations with write concern (i.e. w) that wait for one or more members of a replica set to acknowledge the write operation (i.e. a w value greater than 1.)
# TYPE mongodb_metrics_get_last_error_wtime_total_milliseconds counter
mongodb_metrics_get_last_error_wtime_total_milliseconds 0
# HELP mongodb_metrics_get_last_error_wtimeouts_total wtimeouts reports the number of times that write concern operations have timed out as a result of the wtimeout threshold to getLastError.
# TYPE mongodb_metrics_get_last_error_wtimeouts_total counter
mongodb_metrics_get_last_error_wtimeouts_total 0
# HELP mongodb_metrics_operation_total operation is a sub-document that holds counters for several types of update and query operations that MongoDB handles using special operation types
# TYPE mongodb_metrics_operation_total counter
mongodb_metrics_operation_total{type="fastmod"} 0
mongodb_metrics_operation_total{type="idhack"} 0
mongodb_metrics_operation_total{type="scan_and_order"} 0
# HELP mongodb_metrics_query_executor_total queryExecutor is a document that reports data from the query execution system
# TYPE mongodb_metrics_query_executor_total counter
mongodb_metrics_query_executor_total{state="scanned"} 0
mongodb_metrics_query_executor_total{state="scanned_objects"} 0
# HELP mongodb_metrics_record_moves_total moves reports the total number of times documents move within the on-disk representation of the MongoDB data set. Documents move as a result of operations that increase the size of the document beyond their allocated record size
# TYPE mongodb_metrics_record_moves_total counter
mongodb_metrics_record_moves_total 0
# HELP mongodb_metrics_repl_apply_batches_num_total num reports the total number of batches applied across all databases
# TYPE mongodb_metrics_repl_apply_batches_num_total counter
mongodb_metrics_repl_apply_batches_num_total 0
# HELP mongodb_metrics_repl_apply_batches_total_milliseconds total_millis reports the total amount of time the mongod has spent applying operations from the oplog
# TYPE mongodb_metrics_repl_apply_batches_total_milliseconds counter
mongodb_metrics_repl_apply_batches_total_milliseconds 0
# HELP mongodb_metrics_repl_apply_ops_total ops reports the total number of oplog operations applied
# TYPE mongodb_metrics_repl_apply_ops_total counter
mongodb_metrics_repl_apply_ops_total 0
# HELP mongodb_metrics_repl_buffer_count count reports the current number of operations in the oplog buffer
# TYPE mongodb_metrics_repl_buffer_count gauge
mongodb_metrics_repl_buffer_count 0
# HELP mongodb_metrics_repl_buffer_max_size_bytes maxSizeBytes reports the maximum size of the buffer. This value is a constant setting in the mongod, and is not configurable
# TYPE mongodb_metrics_repl_buffer_max_size_bytes counter
mongodb_metrics_repl_buffer_max_size_bytes 2.68435456e+08
# HELP mongodb_metrics_repl_buffer_size_bytes sizeBytes reports the current size of the contents of the oplog buffer
# TYPE mongodb_metrics_repl_buffer_size_bytes gauge
mongodb_metrics_repl_buffer_size_bytes 0
# HELP mongodb_metrics_repl_network_bytes_total bytes reports the total amount of data read from the replication sync source
# TYPE mongodb_metrics_repl_network_bytes_total counter
mongodb_metrics_repl_network_bytes_total 0
# HELP mongodb_metrics_repl_network_getmores_num_total num reports the total number of getmore operations, which are operations that request an additional set of operations from the replication sync source.
# TYPE mongodb_metrics_repl_network_getmores_num_total counter
mongodb_metrics_repl_network_getmores_num_total 0
# HELP mongodb_metrics_repl_network_getmores_total_milliseconds total_millis reports the total amount of time required to collect data from getmore operations
# TYPE mongodb_metrics_repl_network_getmores_total_milliseconds counter
mongodb_metrics_repl_network_getmores_total_milliseconds 0
# HELP mongodb_metrics_repl_network_ops_total ops reports the total number of operations read from the replication source.
# TYPE mongodb_metrics_repl_network_ops_total counter
mongodb_metrics_repl_network_ops_total 0
# HELP mongodb_metrics_repl_network_readers_created_total readersCreated reports the total number of oplog query processes created. MongoDB will create a new oplog query any time an error occurs in the connection, including a timeout, or a network operation. Furthermore, readersCreated will increment every time MongoDB selects a new source fore replication.
# TYPE mongodb_metrics_repl_network_readers_created_total counter
mongodb_metrics_repl_network_readers_created_total 0
# HELP mongodb_metrics_repl_oplog_insert_bytes_total insertBytes the total size of documents inserted into the oplog.
# TYPE mongodb_metrics_repl_oplog_insert_bytes_total counter
mongodb_metrics_repl_oplog_insert_bytes_total 0
# HELP mongodb_metrics_repl_oplog_insert_num_total num reports the total number of items inserted into the oplog.
# TYPE mongodb_metrics_repl_oplog_insert_num_total counter
mongodb_metrics_repl_oplog_insert_num_total 0
# HELP mongodb_metrics_repl_oplog_insert_total_milliseconds total_millis reports the total amount of time spent for the mongod to insert data into the oplog.
# TYPE mongodb_metrics_repl_oplog_insert_total_milliseconds counter
mongodb_metrics_repl_oplog_insert_total_milliseconds 0
# HELP mongodb_metrics_repl_preload_docs_num_total num reports the total number of documents loaded during the pre-fetch stage of replication
# TYPE mongodb_metrics_repl_preload_docs_num_total counter
mongodb_metrics_repl_preload_docs_num_total 0
# HELP mongodb_metrics_repl_preload_docs_total_milliseconds total_millis reports the total amount of time spent loading documents as part of the pre-fetch stage of replication
# TYPE mongodb_metrics_repl_preload_docs_total_milliseconds counter
mongodb_metrics_repl_preload_docs_total_milliseconds 0
# HELP mongodb_metrics_repl_preload_indexes_num_total num reports the total number of index entries loaded by members before updating documents as part of the pre-fetch stage of replication
# TYPE mongodb_metrics_repl_preload_indexes_num_total counter
mongodb_metrics_repl_preload_indexes_num_total 0
# HELP mongodb_metrics_repl_preload_indexes_total_milliseconds total_millis reports the total amount of time spent loading index entries as part of the pre-fetch stage of replication
# TYPE mongodb_metrics_repl_preload_indexes_total_milliseconds counter
mongodb_metrics_repl_preload_indexes_total_milliseconds 0
# HELP mongodb_metrics_storage_freelist_search_total metrics about searching records in the database.
# TYPE mongodb_metrics_storage_freelist_search_total counter
mongodb_metrics_storage_freelist_search_total{type="bucket_exhausted"} 0
mongodb_metrics_storage_freelist_search_total{type="requests"} 0
mongodb_metrics_storage_freelist_search_total{type="scanned"} 0
# HELP mongodb_metrics_ttl_deleted_documents_total deletedDocuments reports the total number of documents deleted from collections with a ttl index.
# TYPE mongodb_metrics_ttl_deleted_documents_total counter
mongodb_metrics_ttl_deleted_documents_total 0
# HELP mongodb_metrics_ttl_passes_total passes reports the number of times the background process removes documents from collections with a ttl index
# TYPE mongodb_metrics_ttl_passes_total counter
mongodb_metrics_ttl_passes_total 0
# HELP mongodb_network_bytes_total The network data structure contains data regarding MongoDB's network use
# TYPE mongodb_network_bytes_total counter
mongodb_network_bytes_total{state="in_bytes"} 46130
mongodb_network_bytes_total{state="out_bytes"} 2.646396e+06
# HELP mongodb_network_metrics_num_requests_total The numRequests field is a counter of the total number of distinct requests that the server has received. Use this value to provide context for the bytesIn and bytesOut values to ensure that MongoDB's network utilization is consistent with expectations and application use
# TYPE mongodb_network_metrics_num_requests_total counter
mongodb_network_metrics_num_requests_total 723
# HELP mongodb_op_counters_repl_total The opcountersRepl data structure, similar to the opcounters data structure, provides an overview of database replication operations by type and makes it possible to analyze the load on the replica in more granular manner. These values only appear when the current host has replication enabled
# TYPE mongodb_op_counters_repl_total counter
mongodb_op_counters_repl_total{type="command"} 0
mongodb_op_counters_repl_total{type="delete"} 0
mongodb_op_counters_repl_total{type="getmore"} 0
mongodb_op_counters_repl_total{type="insert"} 0
mongodb_op_counters_repl_total{type="query"} 0
mongodb_op_counters_repl_total{type="update"} 0
# HELP mongodb_op_counters_total The opcounters data structure provides an overview of database operations by type and makes it possible to analyze the load on the database in more granular manner. These numbers will grow over time and in response to database use. Analyze these values over time to track database utilization
# TYPE mongodb_op_counters_total counter
mongodb_op_counters_total{type="command"} 724
mongodb_op_counters_total{type="delete"} 0
mongodb_op_counters_total{type="getmore"} 0
mongodb_op_counters_total{type="insert"} 0
mongodb_op_counters_total{type="query"} 1
mongodb_op_counters_total{type="update"} 0
# HELP process_cpu_seconds_total Total user and system CPU time spent in seconds.
# TYPE process_cpu_seconds_total counter
process_cpu_seconds_total 1.71
# HELP process_max_fds Maximum number of open file descriptors.
# TYPE process_max_fds gauge
process_max_fds 1.048576e+06
# HELP process_open_fds Number of open file descriptors.
# TYPE process_open_fds gauge
process_open_fds 11
# HELP process_resident_memory_bytes Resident memory size in bytes.
# TYPE process_resident_memory_bytes gauge
process_resident_memory_bytes 1.5413248e+07
# HELP process_start_time_seconds Start time of the process since unix epoch in seconds.
# TYPE process_start_time_seconds gauge
process_start_time_seconds 1.53643857529e+09
# HELP process_virtual_memory_bytes Virtual memory size in bytes.
# TYPE process_virtual_memory_bytes gauge
process_virtual_memory_bytes 2.1479424e+07
