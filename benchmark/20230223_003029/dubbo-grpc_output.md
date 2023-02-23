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
# Warmup Iteration   1: 4.807 ops/ms
# Warmup Iteration   2: 9.470 ops/ms
# Warmup Iteration   3: 10.225 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.253 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.310 ±(99.9%) 6.266 ops/ms [Average]
  (min, avg, max) = (9.999, 10.310, 10.679), stdev = 0.343
  CI (99.9%): [4.044, 16.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.375 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 11.164 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 11.003 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.780 ±(99.9%) 4.111 ops/ms [Average]
  (min, avg, max) = (10.552, 10.780, 11.003), stdev = 0.225
  CI (99.9%): [6.669, 14.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.383 ops/ms
# Warmup Iteration   2: 10.315 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.422 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (10.342, 10.422, 10.491), stdev = 0.075
  CI (99.9%): [9.048, 11.796] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.905 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.012 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.141 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (8.012, 8.141, 8.323), stdev = 0.162
  CI (99.9%): [5.177, 11.105] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.073, 3.108, 3.171), stdev = 0.055
  CI (99.9%): [2.109, 4.107] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.002 ms/op
Iteration   3: 2.899 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (2.899, 2.923, 2.938), stdev = 0.022
  CI (99.9%): [2.530, 3.316] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.161 ±(99.9%) 0.003 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (3.046, 3.109, 3.161), stdev = 0.058
  CI (99.9%): [2.046, 4.173] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.050 ms/op
Iteration   1: 3.998 ±(99.9%) 0.024 ms/op
Iteration   2: 3.912 ±(99.9%) 0.017 ms/op
Iteration   3: 3.855 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.855, 3.922, 3.998), stdev = 0.072
  CI (99.9%): [2.601, 5.242] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  6.024 ms/op
                 createUser·p0.9999: 11.207 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.248 ms/op
                 createUser·p0.999:  7.477 ms/op
                 createUser·p0.9999: 12.972 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.130 ms/op
                 createUser·p0.9999: 15.870 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309727
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1466 
    [ 1.250,  2.500) = 22638 
    [ 2.500,  3.750) = 253041 
    [ 3.750,  5.000) = 31301 
    [ 5.000,  6.250) = 803 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.170 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     16.019 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 11.346 ms/op
                 existUser·p1.00:   11.682 ms/op

Iteration   2: 2.861 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.889 ms/op
                 existUser·p0.9999: 12.678 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 15.039 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329760
  mean =      2.911 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3203 
    [ 1.250,  2.500) = 52330 
    [ 2.500,  3.750) = 257250 
    [ 3.750,  5.000) = 15910 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     14.763 ms/op
     p(99.9990) =     15.403 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.965 ms/op
                 getUser·p0.9999: 20.089 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.405 ms/op
                 getUser·p0.999:  8.525 ms/op
                 getUser·p0.9999: 17.796 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.893 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305337
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19044 
    [ 2.500,  5.000) = 284958 
    [ 5.000,  7.500) = 873 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.869 ms/op
     p(99.9900) =     19.119 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.287 ms/op
                 listUser·p0.999:  12.417 ms/op
                 listUser·p0.9999: 14.419 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.290 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 17.243 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.497 ms/op
                 listUser·p0.9999: 21.164 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239807
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5128 
    [ 2.500,  5.000) = 200631 
    [ 5.000,  7.500) = 32456 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.421 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     22.289 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.310 ± 6.266  ops/ms
ClientGrpc.existUser                       thrpt       3  10.780 ± 4.111  ops/ms
ClientGrpc.getUser                         thrpt       3  10.422 ± 1.374  ops/ms
ClientGrpc.listUser                        thrpt       3   8.141 ± 2.964  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.999   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.393   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 1.064   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 1.321   ms/op
ClientGrpc.createUser                     sample  309727   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.534           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.287           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.056           ms/op
ClientGrpc.existUser                      sample  329760   2.911 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.763           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.532           ms/op
ClientGrpc.getUser                        sample  305337   3.144 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.957           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.869           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.119           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  239807   4.005 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.421           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.644           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
