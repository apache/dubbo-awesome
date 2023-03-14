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
# Warmup Iteration   1: 4.718 ops/ms
# Warmup Iteration   2: 9.666 ops/ms
# Warmup Iteration   3: 10.293 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.642 ±(99.9%) 1.921 ops/ms [Average]
  (min, avg, max) = (10.539, 10.642, 10.749), stdev = 0.105
  CI (99.9%): [8.721, 12.563] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ops/ms
# Warmup Iteration   2: 10.893 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 11.084 ops/ms
Iteration   2: 11.326 ops/ms
Iteration   3: 11.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.158 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (11.064, 11.158, 11.326), stdev = 0.146
  CI (99.9%): [8.494, 13.822] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.772 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (10.644, 10.772, 10.862), stdev = 0.114
  CI (99.9%): [8.695, 12.850] (assumes normal distribution)


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
# Warmup Iteration   1: 5.999 ops/ms
# Warmup Iteration   2: 8.406 ops/ms
# Warmup Iteration   3: 8.320 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.451 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (8.356, 8.451, 8.529), stdev = 0.088
  CI (99.9%): [6.847, 10.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.938 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.956 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.938, 2.956, 2.966), stdev = 0.016
  CI (99.9%): [2.668, 3.244] (assumes normal distribution)


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.875 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.004 ms/op
Iteration   1: 2.833 ±(99.9%) 0.003 ms/op
Iteration   2: 2.835 ±(99.9%) 0.003 ms/op
Iteration   3: 2.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.831 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.824, 2.831, 2.835), stdev = 0.006
  CI (99.9%): [2.715, 2.946] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.004 ms/op
Iteration   1: 2.930 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.941 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.909, 2.941, 2.985), stdev = 0.039
  CI (99.9%): [2.233, 3.650] (assumes normal distribution)


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
# Warmup Iteration   1: 5.049 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.011 ms/op
Iteration   1: 3.821 ±(99.9%) 0.026 ms/op
Iteration   2: 3.775 ±(99.9%) 0.037 ms/op
Iteration   3: 3.700 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.765 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.700, 3.765, 3.821), stdev = 0.061
  CI (99.9%): [2.651, 4.879] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  6.982 ms/op
                 createUser·p0.9999: 11.342 ms/op
                 createUser·p1.00:   11.551 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.261 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.095 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.241 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.532 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326202
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34889 
    [ 2.500,  5.000) = 290056 
    [ 5.000,  7.500) = 844 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.241 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.647 ms/op
     p(99.9900) =     16.463 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.813 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.340 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.839 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 22.438 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.847 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338510
  mean =      2.834 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50227 
    [ 2.500,  5.000) = 287416 
    [ 5.000,  7.500) = 588 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.382 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     22.597 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 17.338 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 13.310 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.474 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324028
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29113 
    [ 2.500,  5.000) = 293779 
    [ 5.000,  7.500) = 851 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.151 ms/op
     p(99.9900) =     19.957 ms/op
     p(99.9990) =     23.724 ms/op
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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.010 ms/op
Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.680 ms/op
                 listUser·p0.999:  12.732 ms/op
                 listUser·p0.9999: 15.082 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.757 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 16.924 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.805 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.509 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 21.082 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252120
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5805 
    [ 2.500,  5.000) = 225904 
    [ 5.000,  7.500) = 19078 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.905 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.642 ± 1.921  ops/ms
ClientGrpc.existUser                       thrpt       3  11.158 ± 2.664  ops/ms
ClientGrpc.getUser                         thrpt       3  10.772 ± 2.077  ops/ms
ClientGrpc.listUser                        thrpt       3   8.451 ± 1.604  ops/ms
ClientGrpc.createUser                       avgt       3   2.956 ± 0.288   ms/op
ClientGrpc.existUser                        avgt       3   2.831 ± 0.115   ms/op
ClientGrpc.getUser                          avgt       3   2.941 ± 0.708   ms/op
ClientGrpc.listUser                         avgt       3   3.765 ± 1.114   ms/op
ClientGrpc.createUser                     sample  326202   2.942 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.241           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.647           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.463           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.906           ms/op
ClientGrpc.existUser                      sample  338510   2.834 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.460           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  324028   2.961 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.572           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.957           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  252120   3.805 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.509           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.792           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
