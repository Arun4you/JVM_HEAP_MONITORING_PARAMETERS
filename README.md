# JVM_HEAP_MONITORING_PARAMETERS
JVM Pamaters for GC logs and Heap dumps

Enabling GC logs:

-XX:+PrintGCApplicationStoppedTime 
-XX:+PrintHeapAtGC  
-Xloggc:${GC_LOG_PATH} 
-XX:+PrintGCDateStamps 
-XX:+PrintGCDetails

HEAP HUMP:

-XX:HeapDumpPath=${DUMP_PATH}
-XX:+HeapDumpOnOutOfMemoryError
