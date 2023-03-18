# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ops/ms
# Warmup Iteration   2: 8.855 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.169 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (10.113, 10.169, 10.264), stdev = 0.082
  CI (99.9%): [8.668, 11.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.445 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 10.998 ops/ms
Iteration   2: 11.316 ops/ms
Iteration   3: 11.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.198 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (10.998, 11.198, 11.316), stdev = 0.174
  CI (99.9%): [8.015, 14.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.113 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.448 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.594 ±(99.9%) 0.826 ops/ms [Average]
  (min, avg, max) = (10.542, 10.594, 10.621), stdev = 0.045
  CI (99.9%): [9.768, 11.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.641 ops/ms
# Warmup Iteration   2: 7.861 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.138 ±(99.9%) 2.399 ops/ms [Average]
  (min, avg, max) = (7.988, 8.138, 8.231), stdev = 0.131
  CI (99.9%): [5.740, 10.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.001 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (2.950, 3.013, 3.075), stdev = 0.063
  CI (99.9%): [1.872, 4.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.002 ms/op
Iteration   1: 2.817 ±(99.9%) 0.002 ms/op
Iteration   2: 2.885 ±(99.9%) 0.002 ms/op
Iteration   3: 2.898 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (2.817, 2.867, 2.898), stdev = 0.044
  CI (99.9%): [2.071, 3.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.537 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 2.972 ±(99.9%) 0.001 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (2.972, 3.034, 3.112), stdev = 0.071
  CI (99.9%): [1.739, 4.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.025 ms/op
Iteration   1: 3.903 ±(99.9%) 0.009 ms/op
Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
Iteration   3: 4.025 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.951 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (3.903, 3.951, 4.025), stdev = 0.065
  CI (99.9%): [2.760, 5.142] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.121 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.488 ms/op
                 createUser·p0.9999: 12.882 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.905 ms/op
                 createUser·p0.9999: 14.718 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.945 ms/op
                 createUser·p0.9999: 20.710 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309963
  mean =      3.097 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14937 
    [ 2.500,  5.000) = 293713 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 15.989 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   2: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  5.895 ms/op
                 existUser·p0.9999: 14.432 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.187 ms/op
                 existUser·p0.999:  7.948 ms/op
                 existUser·p0.9999: 15.499 ms/op
                 existUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329304
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 992 
    [ 1.250,  2.500) = 30107 
    [ 2.500,  3.750) = 288502 
    [ 3.750,  5.000) = 8818 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.065 ms/op
     p(99.9900) =     14.699 ms/op
     p(99.9990) =     16.215 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.924 ms/op
                 getUser·p0.9999: 13.535 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.519 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.699 ms/op
                 getUser·p0.9999: 23.346 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.579 ms/op
                 getUser·p0.9999: 17.577 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315040
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20875 
    [ 2.500,  5.000) = 292898 
    [ 5.000,  7.500) = 1005 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     22.462 ms/op
     p(99.9990) =     23.649 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.578 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.018 ms/op
                 listUser·p0.999:  17.969 ms/op
                 listUser·p0.9999: 25.996 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.346 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.336 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241560
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3423 
    [ 2.500,  5.000) = 212625 
    [ 5.000,  7.500) = 24100 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.431 ms/op
     p(99.9900) =     25.118 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.169 ± 1.501  ops/ms
ClientGrpc.existUser                       thrpt       3  11.198 ± 3.183  ops/ms
ClientGrpc.getUser                         thrpt       3  10.594 ± 0.826  ops/ms
ClientGrpc.listUser                        thrpt       3   8.138 ± 2.399  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 1.141   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.795   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 1.295   ms/op
ClientGrpc.listUser                         avgt       3   3.951 ± 1.191   ms/op
ClientGrpc.createUser                     sample  309963   3.097 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.874           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  329304   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.065           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.699           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.253           ms/op
ClientGrpc.getUser                        sample  315040   3.045 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.519           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.824           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.462           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  241560   3.972 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.431           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.118           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
