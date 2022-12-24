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
# Warmup Iteration   1: 4.786 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.182 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.094 ±(99.9%) 1.481 ops/ms [Average]
  (min, avg, max) = (10.022, 10.094, 10.182), stdev = 0.081
  CI (99.9%): [8.613, 11.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 10.741 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.988 ops/ms
Iteration   2: 10.676 ops/ms
Iteration   3: 10.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.883 ±(99.9%) 3.268 ops/ms [Average]
  (min, avg, max) = (10.676, 10.883, 10.988), stdev = 0.179
  CI (99.9%): [7.614, 14.151] (assumes normal distribution)


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
# Warmup Iteration   1: 7.089 ops/ms
# Warmup Iteration   2: 10.143 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.354 ops/ms
Iteration   3: 10.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.360 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (10.197, 10.360, 10.529), stdev = 0.166
  CI (99.9%): [7.329, 13.391] (assumes normal distribution)


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
# Warmup Iteration   1: 5.848 ops/ms
# Warmup Iteration   2: 7.641 ops/ms
# Warmup Iteration   3: 7.971 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 7.793 ops/ms
Iteration   3: 7.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.886 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (7.793, 7.886, 7.988), stdev = 0.098
  CI (99.9%): [6.096, 9.675] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.003 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.045, 3.088, 3.113), stdev = 0.038
  CI (99.9%): [2.395, 3.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.001 ms/op
Iteration   1: 2.910 ±(99.9%) 0.004 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.975 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (2.910, 2.975, 3.012), stdev = 0.057
  CI (99.9%): [1.937, 4.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.096 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.057, 3.096, 3.139), stdev = 0.041
  CI (99.9%): [2.350, 3.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.011 ms/op
Iteration   1: 4.183 ±(99.9%) 0.010 ms/op
Iteration   2: 3.980 ±(99.9%) 0.008 ms/op
Iteration   3: 3.934 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 2.419 ms/op [Average]
  (min, avg, max) = (3.934, 4.032, 4.183), stdev = 0.133
  CI (99.9%): [1.613, 6.451] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.519 ms/op
                 createUser·p0.9999: 11.288 ms/op
                 createUser·p1.00:   12.059 ms/op

Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.715 ms/op
                 createUser·p0.9999: 16.027 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.280 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  12.127 ms/op
                 createUser·p0.9999: 24.419 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315131
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25725 
    [ 2.500,  5.000) = 288155 
    [ 5.000,  7.500) = 858 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.280 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.419 ms/op
     p(99.9900) =     21.658 ms/op
     p(99.9990) =     24.735 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.175 ms/op
                 existUser·p0.9999: 17.354 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.208 ms/op
                 existUser·p0.9999: 13.556 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.275 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 18.829 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324572
  mean =      2.958 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46034 
    [ 2.500,  5.000) = 277819 
    [ 5.000,  7.500) = 500 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.406 ms/op
     p(99.9900) =     18.122 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.412 ms/op
                 getUser·p0.9999: 15.014 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  5.835 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.389 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.982 ms/op
                 getUser·p0.9999: 29.367 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317410
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29386 
    [ 2.500,  5.000) = 287190 
    [ 5.000,  7.500) = 629 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.283 ms/op
     p(99.9900) =     28.844 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.306 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  17.681 ms/op
                 listUser·p0.9999: 26.453 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 3.972 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  16.461 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.223 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245384
  mean =      3.909 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5058 
    [ 2.500,  5.000) = 213578 
    [ 5.000,  7.500) = 25735 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     26.906 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.094 ± 1.481  ops/ms
ClientGrpc.existUser                       thrpt       3  10.883 ± 3.268  ops/ms
ClientGrpc.getUser                         thrpt       3  10.360 ± 3.031  ops/ms
ClientGrpc.listUser                        thrpt       3   7.886 ± 1.790  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.693   ms/op
ClientGrpc.existUser                        avgt       3   2.975 ± 1.039   ms/op
ClientGrpc.getUser                          avgt       3   3.096 ± 0.747   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 2.419   ms/op
ClientGrpc.createUser                     sample  315131   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.280           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.419           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.838           ms/op
ClientGrpc.existUser                      sample  324572   2.958 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.275           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.122           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  317410   3.024 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.389           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.283           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.844           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.655           ms/op
ClientGrpc.listUser                       sample  245384   3.909 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.306           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.723           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
