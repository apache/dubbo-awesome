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
# Warmup Iteration   1: 4.904 ops/ms
# Warmup Iteration   2: 9.448 ops/ms
# Warmup Iteration   3: 10.278 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.579 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (10.436, 10.579, 10.707), stdev = 0.136
  CI (99.9%): [8.092, 13.066] (assumes normal distribution)


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
# Warmup Iteration   1: 7.836 ops/ms
# Warmup Iteration   2: 10.399 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.907 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.821 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (10.763, 10.821, 10.907), stdev = 0.076
  CI (99.9%): [9.431, 12.212] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.034 ops/ms
# Warmup Iteration   2: 10.182 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.337 ops/ms
Iteration   2: 10.297 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.330 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (10.297, 10.330, 10.356), stdev = 0.030
  CI (99.9%): [9.778, 10.882] (assumes normal distribution)


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
# Warmup Iteration   1: 5.954 ops/ms
# Warmup Iteration   2: 7.941 ops/ms
# Warmup Iteration   3: 7.985 ops/ms
Iteration   1: 8.140 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.113 ±(99.9%) 3.013 ops/ms [Average]
  (min, avg, max) = (7.936, 8.113, 8.263), stdev = 0.165
  CI (99.9%): [5.100, 11.126] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.182 ±(99.9%) 0.002 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 1.439 ms/op [Average]
  (min, avg, max) = (3.024, 3.105, 3.182), stdev = 0.079
  CI (99.9%): [1.666, 4.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.002 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (2.970, 2.974, 2.979), stdev = 0.004
  CI (99.9%): [2.892, 3.056] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.060, 3.087, 3.103), stdev = 0.024
  CI (99.9%): [2.653, 3.521] (assumes normal distribution)


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.008 ms/op
Iteration   1: 3.911 ±(99.9%) 0.044 ms/op
Iteration   2: 3.871 ±(99.9%) 0.066 ms/op
Iteration   3: 3.836 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (3.836, 3.873, 3.911), stdev = 0.038
  CI (99.9%): [3.183, 4.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.398 ms/op
                 createUser·p0.9999: 14.535 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  7.885 ms/op
                 createUser·p0.9999: 15.745 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.107 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  10.567 ms/op
                 createUser·p0.9999: 29.514 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315290
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31517 
    [ 2.500,  5.000) = 282848 
    [ 5.000,  7.500) = 509 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      9.252 ms/op
     p(99.9900) =     28.817 ms/op
     p(99.9990) =     29.809 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  5.800 ms/op
                 existUser·p0.9999: 11.222 ms/op
                 existUser·p1.00:   11.485 ms/op

Iteration   2: 2.856 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.071 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  9.166 ms/op
                 existUser·p0.9999: 13.704 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331746
  mean =      2.893 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58135 
    [ 2.500,  5.000) = 272886 
    [ 5.000,  7.500) = 511 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      5.952 ms/op
     p(99.9900) =     14.445 ms/op
     p(99.9990) =     21.858 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  10.600 ms/op
                 getUser·p0.9999: 11.871 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.393 ms/op
                 getUser·p0.9999: 14.622 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.338 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.579 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.951 ms/op
                 getUser·p0.9999: 15.606 ms/op
                 getUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315534
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1575 
    [ 1.250,  2.500) = 29517 
    [ 2.500,  3.750) = 262877 
    [ 3.750,  5.000) = 20488 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 322 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.921 ms/op
     p(99.9900) =     14.294 ms/op
     p(99.9990) =     16.120 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.543 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.622 ms/op
                 listUser·p0.9999: 20.046 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.103 ms/op
                 listUser·p0.9999: 22.807 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 3.987 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.763 ms/op
                 listUser·p0.9999: 23.919 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243791
  mean =      3.941 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6689 
    [ 2.500,  5.000) = 208895 
    [ 5.000,  7.500) = 26971 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.792 ms/op
     p(99.9000) =     15.732 ms/op
     p(99.9900) =     22.696 ms/op
     p(99.9990) =     24.431 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.579 ± 2.487  ops/ms
ClientGrpc.existUser                       thrpt       3  10.821 ± 1.390  ops/ms
ClientGrpc.getUser                         thrpt       3  10.330 ± 0.552  ops/ms
ClientGrpc.listUser                        thrpt       3   8.113 ± 3.013  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 1.439   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.082   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.434   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.690   ms/op
ClientGrpc.createUser                     sample  315290   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.578           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.252           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.817           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.884           ms/op
ClientGrpc.existUser                      sample  331746   2.893 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.649           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.952           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.445           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  315534   3.039 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.338           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.921           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.294           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.269           ms/op
ClientGrpc.listUser                       sample  243791   3.941 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.543           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.792           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.732           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.696           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
