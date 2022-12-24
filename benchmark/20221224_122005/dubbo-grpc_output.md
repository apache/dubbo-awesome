# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ops/ms
# Warmup Iteration   2: 9.669 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.113 ops/ms
Iteration   3: 10.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.245 ±(99.9%) 5.726 ops/ms [Average]
  (min, avg, max) = (10.019, 10.245, 10.604), stdev = 0.314
  CI (99.9%): [4.520, 15.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.603 ops/ms
# Warmup Iteration   2: 10.865 ops/ms
# Warmup Iteration   3: 10.665 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 11.061 ops/ms
Iteration   3: 11.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.036 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (10.951, 11.036, 11.095), stdev = 0.076
  CI (99.9%): [9.657, 12.415] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.456 ops/ms
# Warmup Iteration   2: 10.368 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.471 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (10.404, 10.471, 10.583), stdev = 0.098
  CI (99.9%): [8.691, 12.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.102 ops/ms
# Warmup Iteration   2: 7.763 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.865 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.855 ±(99.9%) 0.337 ops/ms [Average]
  (min, avg, max) = (7.834, 7.855, 7.866), stdev = 0.018
  CI (99.9%): [7.518, 8.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.134 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.053, 3.134, 3.181), stdev = 0.070
  CI (99.9%): [1.856, 4.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.938 ±(99.9%) 0.002 ms/op
Iteration   2: 2.914 ±(99.9%) 0.002 ms/op
Iteration   3: 2.905 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.919 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.905, 2.919, 2.938), stdev = 0.017
  CI (99.9%): [2.606, 3.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.004 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (2.989, 3.024, 3.052), stdev = 0.032
  CI (99.9%): [2.436, 3.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.013 ms/op
Iteration   1: 4.027 ±(99.9%) 0.028 ms/op
Iteration   2: 3.985 ±(99.9%) 0.027 ms/op
Iteration   3: 3.910 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.910, 3.974, 4.027), stdev = 0.059
  CI (99.9%): [2.893, 5.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.285 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.581 ms/op
                 createUser·p0.9999: 16.396 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.461 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.619 ms/op
                 createUser·p0.9999: 16.351 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.788 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315941
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1639 
    [ 1.250,  2.500) = 26743 
    [ 2.500,  3.750) = 264575 
    [ 3.750,  5.000) = 21800 
    [ 5.000,  6.250) = 636 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     18.305 ms/op
     p(99.9990) =     19.416 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.756 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  5.786 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.466 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  5.480 ms/op
                 existUser·p0.9999: 18.175 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.085 ms/op
                 existUser·p0.999:  7.064 ms/op
                 existUser·p0.9999: 18.187 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328536
  mean =      2.920 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1830 
    [ 1.250,  2.500) = 49831 
    [ 2.500,  3.750) = 261815 
    [ 3.750,  5.000) = 14325 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      5.955 ms/op
     p(99.9900) =     17.962 ms/op
     p(99.9990) =     18.823 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.325 ms/op
                 getUser·p0.9999: 11.824 ms/op
                 getUser·p1.00:   12.321 ms/op

Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.926 ms/op
                 getUser·p0.9999: 15.119 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.100 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.020 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308659
  mean =      3.109 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 771 
    [ 1.250,  2.500) = 26211 
    [ 2.500,  3.750) = 248898 
    [ 3.750,  5.000) = 31967 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.428 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     15.443 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.041 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.010 ms/op
Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  12.516 ms/op
                 listUser·p0.9999: 20.932 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  14.505 ms/op
                 listUser·p0.9999: 22.114 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.139 ms/op
                 listUser·p0.9999: 15.854 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243517
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3523 
    [ 2.500,  5.000) = 219171 
    [ 5.000,  7.500) = 19840 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     12.837 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.121 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.245 ± 5.726  ops/ms
ClientGrpc.existUser                       thrpt       3  11.036 ± 1.379  ops/ms
ClientGrpc.getUser                         thrpt       3  10.471 ± 1.779  ops/ms
ClientGrpc.listUser                        thrpt       3   7.855 ± 0.337  ops/ms
ClientGrpc.createUser                       avgt       3   3.134 ± 1.278   ms/op
ClientGrpc.existUser                        avgt       3   2.919 ± 0.313   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.589   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 1.080   ms/op
ClientGrpc.createUser                     sample  315941   3.041 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.285           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.848           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.305           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.497           ms/op
ClientGrpc.existUser                      sample  328536   2.920 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.962           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.038           ms/op
ClientGrpc.getUser                        sample  308659   3.109 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.428           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.860           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.072           ms/op
ClientGrpc.listUser                       sample  243517   3.940 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.824           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.837           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
