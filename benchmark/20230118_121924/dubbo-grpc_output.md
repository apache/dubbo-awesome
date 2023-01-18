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
# Warmup Iteration   1: 4.489 ops/ms
# Warmup Iteration   2: 9.566 ops/ms
# Warmup Iteration   3: 10.208 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 10.348 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.476 ±(99.9%) 5.944 ops/ms [Average]
  (min, avg, max) = (10.234, 10.476, 10.847), stdev = 0.326
  CI (99.9%): [4.532, 16.421] (assumes normal distribution)


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
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 10.501 ops/ms
# Warmup Iteration   3: 11.092 ops/ms
Iteration   1: 10.982 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.811 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (10.718, 10.811, 10.982), stdev = 0.148
  CI (99.9%): [8.112, 13.510] (assumes normal distribution)


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
# Warmup Iteration   1: 8.060 ops/ms
# Warmup Iteration   2: 10.102 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.482 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (10.312, 10.482, 10.636), stdev = 0.163
  CI (99.9%): [7.514, 13.450] (assumes normal distribution)


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
# Warmup Iteration   1: 6.242 ops/ms
# Warmup Iteration   2: 7.787 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.153 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.092 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (7.955, 8.092, 8.167), stdev = 0.119
  CI (99.9%): [5.926, 10.258] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.002 ms/op
Iteration   1: 3.194 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
Iteration   3: 3.166 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.174 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.163, 3.174, 3.194), stdev = 0.017
  CI (99.9%): [2.858, 3.490] (assumes normal distribution)


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.922 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.922, 2.949, 2.981), stdev = 0.030
  CI (99.9%): [2.397, 3.500] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (3.005, 3.068, 3.140), stdev = 0.068
  CI (99.9%): [1.825, 4.310] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.025 ms/op
Iteration   1: 4.135 ±(99.9%) 0.031 ms/op
Iteration   2: 3.817 ±(99.9%) 0.009 ms/op
Iteration   3: 4.025 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.992 ±(99.9%) 2.938 ms/op [Average]
  (min, avg, max) = (3.817, 3.992, 4.135), stdev = 0.161
  CI (99.9%): [1.054, 6.931] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.851 ms/op
                 createUser·p0.9999: 16.032 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.252 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  13.563 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.530 ms/op
                 createUser·p0.9999: 21.460 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303709
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22116 
    [ 2.500,  5.000) = 280252 
    [ 5.000,  7.500) = 848 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     10.434 ms/op
     p(99.9900) =     21.779 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.913 ms/op
                 existUser·p0.9999: 11.600 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.670 ms/op
                 existUser·p0.9999: 14.295 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 2.913 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.228 ms/op
                 existUser·p0.999:  6.850 ms/op
                 existUser·p0.9999: 18.089 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326252
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3907 
    [ 1.250,  2.500) = 39306 
    [ 2.500,  3.750) = 267234 
    [ 3.750,  5.000) = 14774 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     15.562 ms/op
     p(99.9990) =     18.464 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.437 ms/op
                 getUser·p0.9999: 11.909 ms/op
                 getUser·p1.00:   12.239 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.326 ms/op
                 getUser·p0.9999: 14.337 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.369 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314067
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30207 
    [ 2.500,  5.000) = 282690 
    [ 5.000,  7.500) = 849 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     26.161 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  11.878 ms/op
                 listUser·p0.9999: 14.317 ms/op
                 listUser·p1.00:   14.582 ms/op

Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.290 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  14.559 ms/op
                 listUser·p0.9999: 16.484 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.009 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  19.234 ms/op
                 listUser·p0.9999: 22.775 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239462
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4601 
    [ 2.500,  5.000) = 204866 
    [ 5.000,  7.500) = 28513 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     23.174 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.476 ± 5.944  ops/ms
ClientGrpc.existUser                       thrpt       3  10.811 ± 2.699  ops/ms
ClientGrpc.getUser                         thrpt       3  10.482 ± 2.968  ops/ms
ClientGrpc.listUser                        thrpt       3   8.092 ± 2.166  ops/ms
ClientGrpc.createUser                       avgt       3   3.174 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.551   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 1.242   ms/op
ClientGrpc.listUser                         avgt       3   3.992 ± 2.938   ms/op
ClientGrpc.createUser                     sample  303709   3.159 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.252           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.434           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.779           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.429           ms/op
ClientGrpc.existUser                      sample  326252   2.942 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.988           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  314067   3.057 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.688           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.161           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.263           ms/op
ClientGrpc.listUser                       sample  239462   4.009 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.201           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
