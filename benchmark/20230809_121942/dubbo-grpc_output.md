# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 8.195 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.071 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.041 ±(99.9%) 1.499 ops/ms [Average]
  (min, avg, max) = (9.948, 10.041, 10.104), stdev = 0.082
  CI (99.9%): [8.542, 11.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.210 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 11.018 ops/ms
Iteration   3: 11.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.910 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (10.703, 10.910, 11.018), stdev = 0.179
  CI (99.9%): [7.645, 14.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 9.658 ops/ms
# Warmup Iteration   3: 10.303 ops/ms
Iteration   1: 10.278 ops/ms
Iteration   2: 10.115 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.176 ±(99.9%) 1.627 ops/ms [Average]
  (min, avg, max) = (10.115, 10.176, 10.278), stdev = 0.089
  CI (99.9%): [8.548, 11.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.549 ops/ms
Iteration   2: 7.752 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.701 ±(99.9%) 2.460 ops/ms [Average]
  (min, avg, max) = (7.549, 7.701, 7.804), stdev = 0.135
  CI (99.9%): [5.241, 10.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.093, 3.112, 3.142), stdev = 0.026
  CI (99.9%): [2.638, 3.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.025 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.010, 3.025, 3.038), stdev = 0.014
  CI (99.9%): [2.775, 3.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.688 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.002 ms/op
Iteration   2: 3.276 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.199 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (3.131, 3.199, 3.276), stdev = 0.073
  CI (99.9%): [1.866, 4.532] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.008 ms/op
Iteration   1: 4.233 ±(99.9%) 0.016 ms/op
Iteration   2: 4.163 ±(99.9%) 0.016 ms/op
Iteration   3: 4.189 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.195 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.163, 4.195, 4.233), stdev = 0.035
  CI (99.9%): [3.549, 4.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.180 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.978 ms/op
                 createUser·p0.999:  9.114 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 15.392 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  9.401 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303747
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 692 
    [ 1.250,  2.500) = 13416 
    [ 2.500,  3.750) = 261608 
    [ 3.750,  5.000) = 24984 
    [ 5.000,  6.250) = 1616 
    [ 6.250,  7.500) = 786 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 189 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      9.376 ms/op
     p(99.9900) =     17.420 ms/op
     p(99.9990) =     18.412 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.895 ms/op
                 existUser·p0.9999: 15.177 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  9.686 ms/op
                 existUser·p0.9999: 15.018 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.669 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.173 ms/op
                 existUser·p0.9999: 23.287 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320150
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23470 
    [ 2.500,  5.000) = 294878 
    [ 5.000,  7.500) = 1228 
    [ 7.500, 10.000) = 384 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     23.580 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.983 ms/op
                 getUser·p0.999:  9.162 ms/op
                 getUser·p0.9999: 14.467 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 15.086 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.794 ms/op
                 getUser·p0.999:  9.021 ms/op
                 getUser·p0.9999: 17.592 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304193
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 560 
    [ 1.250,  2.500) = 13464 
    [ 2.500,  3.750) = 263703 
    [ 3.750,  5.000) = 23773 
    [ 5.000,  6.250) = 1573 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 371 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     16.770 ms/op
     p(99.9990) =     18.119 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.648 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.013 ms/op
Iteration   1: 4.240 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.369 ms/op
                 listUser·p0.9999: 21.606 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.574 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.766 ms/op
                 listUser·p0.9999: 18.411 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.264 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 23.707 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226233
  mean =      4.245 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1446 
    [ 2.500,  5.000) = 190377 
    [ 5.000,  7.500) = 31840 
    [ 7.500, 10.000) = 2004 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     16.487 ms/op
     p(99.9900) =     22.725 ms/op
     p(99.9990) =     25.556 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.041 ± 1.499  ops/ms
ClientGrpc.existUser                       thrpt       3  10.910 ± 3.265  ops/ms
ClientGrpc.getUser                         thrpt       3  10.176 ± 1.627  ops/ms
ClientGrpc.listUser                        thrpt       3   7.701 ± 2.460  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   3.025 ± 0.250   ms/op
ClientGrpc.getUser                          avgt       3   3.199 ± 1.333   ms/op
ClientGrpc.listUser                         avgt       3   4.195 ± 0.646   ms/op
ClientGrpc.createUser                     sample  303747   3.160 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.376           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.420           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.514           ms/op
ClientGrpc.existUser                      sample  320150   2.996 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.814           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  304193   3.156 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.770           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  226233   4.245 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.574           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.030           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.487           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
