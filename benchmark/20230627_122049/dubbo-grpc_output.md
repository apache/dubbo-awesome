# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ops/ms
# Warmup Iteration   2: 9.590 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.965 ops/ms
Iteration   3: 10.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.799 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (10.678, 10.799, 10.965), stdev = 0.149
  CI (99.9%): [8.080, 13.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.093 ops/ms
# Warmup Iteration   2: 11.245 ops/ms
# Warmup Iteration   3: 11.275 ops/ms
Iteration   1: 11.142 ops/ms
Iteration   2: 11.294 ops/ms
Iteration   3: 11.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.257 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (11.142, 11.257, 11.335), stdev = 0.101
  CI (99.9%): [9.407, 13.107] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.166 ops/ms
# Warmup Iteration   2: 10.330 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.968 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.940 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (10.882, 10.940, 10.969), stdev = 0.050
  CI (99.9%): [10.024, 11.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.002 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.205 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.182 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (8.162, 8.182, 8.205), stdev = 0.022
  CI (99.9%): [7.789, 8.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.956 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.948, 2.961, 2.978), stdev = 0.016
  CI (99.9%): [2.677, 3.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.003 ms/op
Iteration   1: 2.949 ±(99.9%) 0.002 ms/op
Iteration   2: 2.840 ±(99.9%) 0.003 ms/op
Iteration   3: 2.866 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (2.840, 2.885, 2.949), stdev = 0.057
  CI (99.9%): [1.845, 3.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.968 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.960, 2.968, 2.985), stdev = 0.014
  CI (99.9%): [2.706, 3.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.131 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.019 ms/op
Iteration   1: 3.927 ±(99.9%) 0.013 ms/op
Iteration   2: 3.868 ±(99.9%) 0.012 ms/op
Iteration   3: 3.909 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.901 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (3.868, 3.901, 3.927), stdev = 0.030
  CI (99.9%): [3.354, 4.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.021 ms/op
                 createUser·p0.9999: 13.355 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.754 ms/op
                 createUser·p0.9999: 12.728 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 17.717 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318183
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1247 
    [ 1.250,  2.500) = 26298 
    [ 2.500,  3.750) = 274484 
    [ 3.750,  5.000) = 14643 
    [ 5.000,  6.250) = 664 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     16.932 ms/op
     p(99.9990) =     17.972 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
Iteration   1: 2.882 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 12.041 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.581 ms/op
                 existUser·p0.9999: 12.584 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.538 ms/op
                 existUser·p0.9999: 13.218 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332489
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2492 
    [ 1.250,  2.500) = 41391 
    [ 2.500,  3.750) = 279492 
    [ 3.750,  5.000) = 7852 
    [ 5.000,  6.250) = 768 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     12.821 ms/op
     p(99.9990) =     15.058 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.259 ms/op
                 getUser·p0.9999: 19.669 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.297 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.213 ms/op
                 getUser·p0.999:  8.081 ms/op
                 getUser·p0.9999: 12.440 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   3: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  5.792 ms/op
                 getUser·p0.9999: 15.237 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322138
  mean =      2.977 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16449 
    [ 2.500,  5.000) = 304482 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     18.489 ms/op
     p(99.9990) =     19.948 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.349 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.643 ms/op
                 listUser·p0.9999: 15.895 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  15.156 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 26.570 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247617
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2905 
    [ 2.500,  5.000) = 226085 
    [ 5.000,  7.500) = 17534 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     25.197 ms/op
     p(99.9990) =     26.740 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.799 ± 2.719  ops/ms
ClientGrpc.existUser                       thrpt       3  11.257 ± 1.850  ops/ms
ClientGrpc.getUser                         thrpt       3  10.940 ± 0.916  ops/ms
ClientGrpc.listUser                        thrpt       3   8.182 ± 0.393  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 1.040   ms/op
ClientGrpc.getUser                          avgt       3   2.968 ± 0.263   ms/op
ClientGrpc.listUser                         avgt       3   3.901 ± 0.547   ms/op
ClientGrpc.createUser                     sample  318183   3.019 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.372           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.932           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  332489   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.821           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.483           ms/op
ClientGrpc.getUser                        sample  322138   2.977 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.363           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.489           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  247617   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.682           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.041           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.197           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
