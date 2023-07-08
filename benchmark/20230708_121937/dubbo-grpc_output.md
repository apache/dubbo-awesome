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
# Warmup Iteration   1: 4.565 ops/ms
# Warmup Iteration   2: 9.666 ops/ms
# Warmup Iteration   3: 10.214 ops/ms
Iteration   1: 10.787 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.779 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (10.738, 10.779, 10.810), stdev = 0.037
  CI (99.9%): [10.110, 11.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 10.909 ops/ms
# Warmup Iteration   3: 11.311 ops/ms
Iteration   1: 11.229 ops/ms
Iteration   2: 11.299 ops/ms
Iteration   3: 11.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.297 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (11.229, 11.297, 11.362), stdev = 0.066
  CI (99.9%): [10.089, 12.504] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.194 ops/ms
# Warmup Iteration   2: 10.478 ops/ms
# Warmup Iteration   3: 10.972 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 11.052 ops/ms
Iteration   3: 10.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.830 ±(99.9%) 3.780 ops/ms [Average]
  (min, avg, max) = (10.642, 10.830, 11.052), stdev = 0.207
  CI (99.9%): [7.049, 14.610] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ops/ms
# Warmup Iteration   2: 7.841 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 8.128 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (8.128, 8.144, 8.168), stdev = 0.021
  CI (99.9%): [7.753, 8.535] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.969 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.962, 2.977, 2.999), stdev = 0.020
  CI (99.9%): [2.612, 3.341] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.003 ms/op
Iteration   1: 2.844 ±(99.9%) 0.003 ms/op
Iteration   2: 2.836 ±(99.9%) 0.003 ms/op
Iteration   3: 2.819 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.833 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.819, 2.833, 2.844), stdev = 0.013
  CI (99.9%): [2.598, 3.068] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.004 ms/op
Iteration   1: 2.955 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.960 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.955, 2.960, 2.967), stdev = 0.006
  CI (99.9%): [2.847, 3.072] (assumes normal distribution)


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.024 ms/op
Iteration   1: 3.854 ±(99.9%) 0.019 ms/op
Iteration   2: 3.883 ±(99.9%) 0.024 ms/op
Iteration   3: 3.844 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.860 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.844, 3.860, 3.883), stdev = 0.020
  CI (99.9%): [3.492, 4.229] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 12.216 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 12.964 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.943 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  16.368 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323372
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34118 
    [ 2.500,  5.000) = 287857 
    [ 5.000,  7.500) = 993 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.579 ms/op
     p(99.9900) =     25.404 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.788 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.889 ms/op
                 existUser·p0.9999: 11.515 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 21.784 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   3: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.166 ms/op
                 existUser·p0.9999: 13.474 ms/op
                 existUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335651
  mean =      2.858 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50128 
    [ 2.500,  5.000) = 284074 
    [ 5.000,  7.500) = 1028 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.310 ms/op
     p(99.9900) =     15.408 ms/op
     p(99.9990) =     22.074 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 12.328 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.430 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  5.849 ms/op
                 getUser·p0.9999: 16.865 ms/op
                 getUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319493
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20226 
    [ 2.500,  5.000) = 298360 
    [ 5.000,  7.500) = 584 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     19.236 ms/op
     p(99.9990) =     20.146 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 20.763 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.921 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 25.019 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.692 ms/op
                 listUser·p0.999:  14.206 ms/op
                 listUser·p0.9999: 21.421 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246348
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3696 
    [ 2.500,  5.000) = 221149 
    [ 5.000,  7.500) = 20440 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     26.807 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.779 ± 0.668  ops/ms
ClientGrpc.existUser                       thrpt       3  11.297 ± 1.207  ops/ms
ClientGrpc.getUser                         thrpt       3  10.830 ± 3.780  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 0.391  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.364   ms/op
ClientGrpc.existUser                        avgt       3   2.833 ± 0.235   ms/op
ClientGrpc.getUser                          avgt       3   2.960 ± 0.113   ms/op
ClientGrpc.listUser                         avgt       3   3.860 ± 0.369   ms/op
ClientGrpc.createUser                     sample  323372   2.967 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.579           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.404           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  335651   2.858 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.583           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.310           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.408           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  319493   3.004 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.589           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.236           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  246348   3.895 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.733           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.680           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
