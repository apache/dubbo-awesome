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
# Warmup Iteration   1: 4.000 ops/ms
# Warmup Iteration   2: 9.413 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 10.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.734 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (10.579, 10.734, 10.844), stdev = 0.138
  CI (99.9%): [8.217, 13.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.629 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 11.022 ops/ms
Iteration   1: 11.073 ops/ms
Iteration   2: 10.802 ops/ms
Iteration   3: 11.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.015 ±(99.9%) 3.484 ops/ms [Average]
  (min, avg, max) = (10.802, 11.015, 11.171), stdev = 0.191
  CI (99.9%): [7.532, 14.499] (assumes normal distribution)


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
# Warmup Iteration   1: 7.112 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.469 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.712 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (10.600, 10.712, 10.899), stdev = 0.162
  CI (99.9%): [7.748, 13.676] (assumes normal distribution)


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
# Warmup Iteration   1: 5.406 ops/ms
# Warmup Iteration   2: 8.030 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.268 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.198 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (8.123, 8.198, 8.268), stdev = 0.072
  CI (99.9%): [6.879, 9.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.067 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.034 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (2.986, 3.034, 3.067), stdev = 0.042
  CI (99.9%): [2.262, 3.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.002 ms/op
Iteration   1: 2.801 ±(99.9%) 0.004 ms/op
Iteration   2: 2.860 ±(99.9%) 0.002 ms/op
Iteration   3: 2.871 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (2.801, 2.844, 2.871), stdev = 0.038
  CI (99.9%): [2.156, 3.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.005, 3.021, 3.040), stdev = 0.018
  CI (99.9%): [2.699, 3.344] (assumes normal distribution)


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
# Warmup Iteration   1: 5.089 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.018 ms/op
Iteration   2: 3.797 ±(99.9%) 0.020 ms/op
Iteration   3: 3.912 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.862 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.797, 3.862, 3.912), stdev = 0.059
  CI (99.9%): [2.781, 4.944] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.597 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 19.298 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.830 ms/op
                 createUser·p0.9999: 14.858 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311655
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24319 
    [ 2.500,  5.000) = 285712 
    [ 5.000,  7.500) = 1197 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     21.256 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.005 ms/op
Iteration   1: 2.900 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  6.444 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.850 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.234 ms/op
                 existUser·p0.9999: 13.169 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   3.881 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332643
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31627 
    [ 2.500,  5.000) = 300063 
    [ 5.000,  7.500) = 758 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.408 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     15.854 ms/op
     p(99.9990) =     26.414 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.078 ms/op
                 getUser·p0.9999: 13.326 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.884 ms/op
                 getUser·p0.9999: 17.007 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319928
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 712 
    [ 1.250,  2.500) = 23293 
    [ 2.500,  3.750) = 282049 
    [ 3.750,  5.000) = 12557 
    [ 5.000,  6.250) = 755 
    [ 6.250,  7.500) = 325 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     16.664 ms/op
     p(99.9990) =     17.728 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.267 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.571 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  17.204 ms/op
                 listUser·p0.9999: 26.764 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.241 ms/op
                 listUser·p0.9999: 17.939 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247493
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3196 
    [ 2.500,  5.000) = 224917 
    [ 5.000,  7.500) = 18345 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     25.027 ms/op
     p(99.9990) =     27.023 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.734 ± 2.517  ops/ms
ClientGrpc.existUser                       thrpt       3  11.015 ± 3.484  ops/ms
ClientGrpc.getUser                         thrpt       3  10.712 ± 2.964  ops/ms
ClientGrpc.listUser                        thrpt       3   8.198 ± 1.319  ops/ms
ClientGrpc.createUser                       avgt       3   3.034 ± 0.772   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.688   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.323   ms/op
ClientGrpc.listUser                         avgt       3   3.862 ± 1.081   ms/op
ClientGrpc.createUser                     sample  311655   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.256           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  332643   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.567           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.854           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  319928   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.664           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  247493   3.878 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.954           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.027           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
