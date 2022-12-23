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
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 9.550 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.178 ±(99.9%) 1.639 ops/ms [Average]
  (min, avg, max) = (10.086, 10.178, 10.265), stdev = 0.090
  CI (99.9%): [8.539, 11.818] (assumes normal distribution)


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
# Warmup Iteration   1: 7.838 ops/ms
# Warmup Iteration   2: 10.759 ops/ms
# Warmup Iteration   3: 11.001 ops/ms
Iteration   1: 10.869 ops/ms
Iteration   2: 11.065 ops/ms
Iteration   3: 10.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.944 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (10.869, 10.944, 11.065), stdev = 0.106
  CI (99.9%): [9.013, 12.876] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.463 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.649 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (10.581, 10.649, 10.708), stdev = 0.064
  CI (99.9%): [9.488, 11.810] (assumes normal distribution)


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
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 7.763 ops/ms
# Warmup Iteration   3: 7.953 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.196 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (8.154, 8.196, 8.241), stdev = 0.044
  CI (99.9%): [7.402, 8.990] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.060 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.019, 3.060, 3.115), stdev = 0.050
  CI (99.9%): [2.149, 3.971] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 2.796 ±(99.9%) 0.005 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 2.863 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (2.796, 2.878, 2.974), stdev = 0.090
  CI (99.9%): [1.239, 4.516] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
Iteration   3: 3.064 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.064, 3.093, 3.130), stdev = 0.034
  CI (99.9%): [2.476, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.028 ms/op
Iteration   1: 4.022 ±(99.9%) 0.020 ms/op
Iteration   2: 3.961 ±(99.9%) 0.028 ms/op
Iteration   3: 3.981 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.961, 3.988, 4.022), stdev = 0.031
  CI (99.9%): [3.417, 4.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.703 ms/op
                 createUser·p0.9999: 11.747 ms/op
                 createUser·p1.00:   11.977 ms/op

Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.377 ms/op
                 createUser·p0.999:  11.274 ms/op
                 createUser·p0.9999: 18.380 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.997 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  13.329 ms/op
                 createUser·p0.9999: 16.597 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306272
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1008 
    [ 1.250,  2.500) = 21919 
    [ 2.500,  3.750) = 249171 
    [ 3.750,  5.000) = 32981 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.708 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 16.890 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.219 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 22.983 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325765
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47413 
    [ 2.500,  5.000) = 277178 
    [ 5.000,  7.500) = 650 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.633 ms/op
     p(99.9900) =     19.265 ms/op
     p(99.9990) =     23.585 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.801 ms/op
                 getUser·p0.9999: 18.849 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  8.344 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 3.062 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.627 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.829 ms/op
                 getUser·p0.9999: 35.324 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314392
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23618 
    [ 2.500,  5.000) = 289782 
    [ 5.000,  7.500) = 688 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 18.925 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.007 ms/op
                 listUser·p0.999:  13.234 ms/op
                 listUser·p0.9999: 16.030 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.859 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 15.652 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243403
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3425 
    [ 2.500,  3.750) = 112315 
    [ 3.750,  5.000) = 101729 
    [ 5.000,  6.250) = 21438 
    [ 6.250,  7.500) = 3538 
    [ 7.500,  8.750) = 472 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 153 
    [13.750, 15.000) = 98 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     19.574 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.178 ± 1.639  ops/ms
ClientGrpc.existUser                       thrpt       3  10.944 ± 1.932  ops/ms
ClientGrpc.getUser                         thrpt       3  10.649 ± 1.161  ops/ms
ClientGrpc.listUser                        thrpt       3   8.196 ± 0.794  ops/ms
ClientGrpc.createUser                       avgt       3   3.060 ± 0.911   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 1.638   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 0.571   ms/op
ClientGrpc.createUser                     sample  306272   3.134 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.436           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.842           ms/op
ClientGrpc.existUser                      sample  325765   2.945 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.575           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.265           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  314392   3.053 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.291           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.603           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.652           ms/op
ClientGrpc.listUser                       sample  243403   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.088           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.792           ms/op
