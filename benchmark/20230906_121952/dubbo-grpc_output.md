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
# Warmup Iteration   1: 4.016 ops/ms
# Warmup Iteration   2: 8.497 ops/ms
# Warmup Iteration   3: 9.882 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.371 ±(99.9%) 0.516 ops/ms [Average]
  (min, avg, max) = (10.346, 10.371, 10.402), stdev = 0.028
  CI (99.9%): [9.854, 10.887] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ops/ms
# Warmup Iteration   2: 10.311 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.885 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.747 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (10.617, 10.747, 10.885), stdev = 0.134
  CI (99.9%): [8.297, 13.197] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.811 ops/ms
# Warmup Iteration   2: 9.776 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.236 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.292 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (10.234, 10.292, 10.407), stdev = 0.099
  CI (99.9%): [8.481, 12.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ops/ms
# Warmup Iteration   2: 7.322 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.773 ops/ms
Iteration   2: 7.580 ops/ms
Iteration   3: 7.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.695 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (7.580, 7.695, 7.773), stdev = 0.102
  CI (99.9%): [5.842, 9.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.011 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.133 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.043, 3.096, 3.133), stdev = 0.047
  CI (99.9%): [2.243, 3.949] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.947, 2.957, 2.970), stdev = 0.012
  CI (99.9%): [2.742, 3.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.113 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.085, 3.113, 3.133), stdev = 0.025
  CI (99.9%): [2.659, 3.567] (assumes normal distribution)


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
# Warmup Iteration   1: 5.104 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.015 ms/op
Iteration   1: 4.050 ±(99.9%) 0.029 ms/op
Iteration   2: 4.080 ±(99.9%) 0.018 ms/op
Iteration   3: 4.116 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.082 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (4.050, 4.082, 4.116), stdev = 0.033
  CI (99.9%): [3.479, 4.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.039 ms/op
                 createUser·p0.9999: 18.798 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.873 ms/op
                 createUser·p0.999:  12.111 ms/op
                 createUser·p0.9999: 28.296 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310337
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17389 
    [ 2.500,  5.000) = 290536 
    [ 5.000,  7.500) = 1740 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.639 ms/op
     p(99.9900) =     26.836 ms/op
     p(99.9990) =     28.826 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.092 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.876 ms/op
                 existUser·p0.9999: 14.585 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.897 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 16.351 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328750
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2508 
    [ 1.250,  2.500) = 32395 
    [ 2.500,  3.750) = 284210 
    [ 3.750,  5.000) = 7903 
    [ 5.000,  6.250) = 714 
    [ 6.250,  7.500) = 469 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     15.018 ms/op
     p(99.9990) =     16.931 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.263 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.750 ms/op
                 getUser·p0.999:  8.197 ms/op
                 getUser·p0.9999: 19.045 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.640 ms/op
                 getUser·p0.9999: 25.050 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309136
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13252 
    [ 2.500,  5.000) = 293613 
    [ 5.000,  7.500) = 1823 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.322 ms/op
     p(99.9900) =     33.134 ms/op
     p(99.9990) =     34.073 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 6.025 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.012 ms/op
Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 15.452 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 21.003 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  17.784 ms/op
                 listUser·p0.9999: 27.474 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234786
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2044 
    [ 2.500,  5.000) = 206114 
    [ 5.000,  7.500) = 24580 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     26.740 ms/op
     p(99.9990) =     27.786 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.371 ± 0.516  ops/ms
ClientGrpc.existUser                       thrpt       3  10.747 ± 2.450  ops/ms
ClientGrpc.getUser                         thrpt       3  10.292 ± 1.811  ops/ms
ClientGrpc.listUser                        thrpt       3   7.695 ± 1.853  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.853   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.216   ms/op
ClientGrpc.getUser                          avgt       3   3.113 ± 0.454   ms/op
ClientGrpc.listUser                         avgt       3   4.082 ± 0.603   ms/op
ClientGrpc.createUser                     sample  310337   3.095 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.639           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.836           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.032           ms/op
ClientGrpc.existUser                      sample  328750   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.531           ms/op
ClientGrpc.getUser                        sample  309136   3.105 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.322           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.134           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.144           ms/op
ClientGrpc.listUser                       sample  234786   4.089 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.239           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.740           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
