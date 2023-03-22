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
# Warmup Iteration   1: 4.784 ops/ms
# Warmup Iteration   2: 9.291 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.752 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.721 ±(99.9%) 0.503 ops/ms [Average]
  (min, avg, max) = (10.698, 10.721, 10.752), stdev = 0.028
  CI (99.9%): [10.218, 11.224] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ops/ms
# Warmup Iteration   2: 10.923 ops/ms
# Warmup Iteration   3: 11.324 ops/ms
Iteration   1: 11.323 ops/ms
Iteration   2: 11.214 ops/ms
Iteration   3: 11.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.316 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (11.214, 11.316, 11.411), stdev = 0.099
  CI (99.9%): [9.511, 13.121] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.681 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.740 ops/ms
Iteration   1: 10.910 ops/ms
Iteration   2: 10.894 ops/ms
Iteration   3: 10.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.878 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.830, 10.878, 10.910), stdev = 0.042
  CI (99.9%): [10.104, 11.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.266 ops/ms
Iteration   2: 8.320 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.270 ±(99.9%) 0.868 ops/ms [Average]
  (min, avg, max) = (8.225, 8.270, 8.320), stdev = 0.048
  CI (99.9%): [7.402, 9.139] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 2.990 ±(99.9%) 0.009 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.976 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.965, 2.976, 2.990), stdev = 0.013
  CI (99.9%): [2.742, 3.210] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.003 ms/op
Iteration   1: 2.842 ±(99.9%) 0.003 ms/op
Iteration   2: 2.828 ±(99.9%) 0.004 ms/op
Iteration   3: 2.853 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.828, 2.841, 2.853), stdev = 0.012
  CI (99.9%): [2.613, 3.069] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 2.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.939, 2.956, 2.971), stdev = 0.016
  CI (99.9%): [2.666, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.007 ms/op
Iteration   1: 3.785 ±(99.9%) 0.012 ms/op
Iteration   2: 3.800 ±(99.9%) 0.021 ms/op
Iteration   3: 3.789 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.792 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.785, 3.792, 3.800), stdev = 0.008
  CI (99.9%): [3.647, 3.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.638 ms/op
                 createUser·p0.9999: 22.702 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.588 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.638 ms/op
                 createUser·p0.9999: 16.488 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321418
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30333 
    [ 2.500,  5.000) = 289667 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     21.881 ms/op
     p(99.9990) =     22.963 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.893 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
Iteration   1: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.350 ms/op
                 existUser·p0.9999: 11.189 ms/op
                 existUser·p1.00:   11.387 ms/op

Iteration   2: 2.779 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.764 ms/op
                 existUser·p0.9999: 11.600 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   3: 2.756 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 17.065 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342262
  mean =      2.806 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7678 
    [ 1.250,  2.500) = 58211 
    [ 2.500,  3.750) = 264793 
    [ 3.750,  5.000) = 10384 
    [ 5.000,  6.250) = 804 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.557 ms/op
     p(99.9900) =     16.380 ms/op
     p(99.9990) =     17.764 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.288 ms/op
                 getUser·p0.9999: 12.477 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.250 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.317 ms/op
                 getUser·p0.9999: 14.847 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.385 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320635
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34414 
    [ 2.500,  5.000) = 284953 
    [ 5.000,  7.500) = 945 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.250 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     23.625 ms/op
     p(99.9990) =     25.585 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.495 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 14.168 ms/op
                 listUser·p1.00:   14.336 ms/op

Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 21.437 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253197
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5323 
    [ 2.500,  5.000) = 229858 
    [ 5.000,  7.500) = 16925 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.268 ms/op
     p(99.9900) =     20.437 ms/op
     p(99.9990) =     21.854 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.721 ± 0.503  ops/ms
ClientGrpc.existUser                       thrpt       3  11.316 ± 1.805  ops/ms
ClientGrpc.getUser                         thrpt       3  10.878 ± 0.774  ops/ms
ClientGrpc.listUser                        thrpt       3   8.270 ± 0.868  ops/ms
ClientGrpc.createUser                       avgt       3   2.976 ± 0.234   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 0.228   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.290   ms/op
ClientGrpc.listUser                         avgt       3   3.792 ± 0.144   ms/op
ClientGrpc.createUser                     sample  321418   2.986 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.881           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  342262   2.806 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.557           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.380           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  320635   2.992 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.250           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.553           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.625           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  253197   3.790 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.495           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.437           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.053           ms/op
