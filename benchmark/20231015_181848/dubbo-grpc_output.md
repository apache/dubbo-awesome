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
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 6.698 ops/ms
# Warmup Iteration   3: 8.198 ops/ms
Iteration   1: 8.616 ops/ms
Iteration   2: 8.472 ops/ms
Iteration   3: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.566 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (8.472, 8.566, 8.616), stdev = 0.081
  CI (99.9%): [7.080, 10.052] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.951 ops/ms
# Warmup Iteration   2: 8.270 ops/ms
# Warmup Iteration   3: 8.989 ops/ms
Iteration   1: 9.064 ops/ms
Iteration   2: 8.883 ops/ms
Iteration   3: 8.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.949 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (8.883, 8.949, 9.064), stdev = 0.100
  CI (99.9%): [7.121, 10.776] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 7.909 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 8.427 ops/ms
Iteration   2: 8.538 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.469 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (8.427, 8.469, 8.538), stdev = 0.060
  CI (99.9%): [7.366, 9.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ops/ms
# Warmup Iteration   2: 6.151 ops/ms
# Warmup Iteration   3: 6.490 ops/ms
Iteration   1: 6.522 ops/ms
Iteration   2: 6.437 ops/ms
Iteration   3: 6.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.445 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (6.377, 6.445, 6.522), stdev = 0.073
  CI (99.9%): [5.112, 7.779] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.403 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.025 ms/op
Iteration   1: 3.740 ±(99.9%) 0.004 ms/op
Iteration   2: 3.761 ±(99.9%) 0.012 ms/op
Iteration   3: 3.780 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.760 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.740, 3.760, 3.780), stdev = 0.020
  CI (99.9%): [3.396, 4.125] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.147 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.004 ms/op
Iteration   1: 3.740 ±(99.9%) 0.004 ms/op
Iteration   2: 3.605 ±(99.9%) 0.002 ms/op
Iteration   3: 3.594 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.646 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (3.594, 3.646, 3.740), stdev = 0.081
  CI (99.9%): [2.163, 5.129] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.004 ms/op
Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
Iteration   2: 3.866 ±(99.9%) 0.008 ms/op
Iteration   3: 3.722 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.832 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (3.722, 3.832, 3.907), stdev = 0.097
  CI (99.9%): [2.060, 5.604] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.606 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.386 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.890 ±(99.9%) 0.011 ms/op
Iteration   1: 4.875 ±(99.9%) 0.017 ms/op
Iteration   2: 4.840 ±(99.9%) 0.019 ms/op
Iteration   3: 4.835 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.850 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (4.835, 4.850, 4.875), stdev = 0.022
  CI (99.9%): [4.454, 5.246] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.584 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.009 ms/op
Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  10.838 ms/op
                 createUser·p0.9999: 16.740 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.386 ms/op
                 createUser·p0.999:  11.317 ms/op
                 createUser·p0.9999: 19.089 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.722 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  15.616 ms/op
                 createUser·p0.9999: 18.115 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256633
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 6357 
    [ 2.500,  3.750) = 138286 
    [ 3.750,  5.000) = 103245 
    [ 5.000,  6.250) = 6099 
    [ 6.250,  7.500) = 1259 
    [ 7.500,  8.750) = 428 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 82 
    [16.250, 17.500) = 59 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     13.392 ms/op
     p(99.9900) =     18.308 ms/op
     p(99.9990) =     19.347 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.935 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.011 ms/op
Iteration   1: 3.701 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  14.630 ms/op
                 existUser·p0.9999: 26.553 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.656 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 25.829 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.535 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 17.824 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264642
  mean =      3.629 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5409 
    [ 2.500,  5.000) = 252408 
    [ 5.000,  7.500) = 6018 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.344 ms/op
     p(99.9900) =     25.889 ms/op
     p(99.9990) =     26.718 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.646 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.011 ms/op
Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  12.177 ms/op
                 getUser·p0.9999: 18.633 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.804 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.867 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  13.025 ms/op
                 getUser·p0.9999: 23.519 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250320
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5535 
    [ 2.500,  5.000) = 234287 
    [ 5.000,  7.500) = 9054 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     12.294 ms/op
     p(99.9900) =     22.411 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 6.912 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.938 ±(99.9%) 0.017 ms/op
Iteration   1: 4.732 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  16.560 ms/op
                 listUser·p0.9999: 18.682 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 4.844 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  22.771 ms/op
                 listUser·p0.9999: 38.233 ms/op
                 listUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199853
  mean =      4.802 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 491 
    [ 2.500,  5.000) = 148481 
    [ 5.000,  7.500) = 44653 
    [ 7.500, 10.000) = 5127 
    [10.000, 12.500) = 586 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.855 ms/op
     p(99.9000) =     17.868 ms/op
     p(99.9900) =     32.309 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.566 ± 1.486  ops/ms
ClientGrpc.existUser                       thrpt       3   8.949 ± 1.827  ops/ms
ClientGrpc.getUser                         thrpt       3   8.469 ± 1.103  ops/ms
ClientGrpc.listUser                        thrpt       3   6.445 ± 1.333  ops/ms
ClientGrpc.createUser                       avgt       3   3.760 ± 0.364   ms/op
ClientGrpc.existUser                        avgt       3   3.646 ± 1.483   ms/op
ClientGrpc.getUser                          avgt       3   3.832 ± 1.772   ms/op
ClientGrpc.listUser                         avgt       3   4.850 ± 0.396   ms/op
ClientGrpc.createUser                     sample  256633   3.739 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.392           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.825           ms/op
ClientGrpc.existUser                      sample  264642   3.629 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.670           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.890           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.344           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.889           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.870           ms/op
ClientGrpc.getUser                        sample  250320   3.834 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.666           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.595           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.294           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.411           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  199853   4.802 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.268           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.855           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.868           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.309           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.732           ms/op
