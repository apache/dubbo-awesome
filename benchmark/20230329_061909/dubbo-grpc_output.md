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
# Warmup Iteration   1: 3.756 ops/ms
# Warmup Iteration   2: 9.415 ops/ms
# Warmup Iteration   3: 10.017 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.494 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (10.404, 10.494, 10.561), stdev = 0.081
  CI (99.9%): [9.016, 11.973] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.759 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.900 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.998 ops/ms
Iteration   3: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.012 ±(99.9%) 2.050 ops/ms [Average]
  (min, avg, max) = (10.908, 11.012, 11.131), stdev = 0.112
  CI (99.9%): [8.963, 13.062] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ops/ms
# Warmup Iteration   2: 10.056 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (10.366, 10.455, 10.607), stdev = 0.132
  CI (99.9%): [8.042, 12.869] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.330 ops/ms
# Warmup Iteration   2: 7.879 ops/ms
# Warmup Iteration   3: 7.778 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.972 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (7.908, 7.972, 8.037), stdev = 0.064
  CI (99.9%): [6.798, 9.146] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.276 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.011 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.070 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.035, 3.070, 3.109), stdev = 0.037
  CI (99.9%): [2.393, 3.747] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.868 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (2.868, 2.912, 2.935), stdev = 0.038
  CI (99.9%): [2.213, 3.612] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.087 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.022, 3.052, 3.087), stdev = 0.033
  CI (99.9%): [2.456, 3.648] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.019 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
Iteration   2: 3.972 ±(99.9%) 0.008 ms/op
Iteration   3: 4.009 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.995 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (3.972, 3.995, 4.009), stdev = 0.020
  CI (99.9%): [3.632, 4.358] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.642 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.223 ms/op
                 createUser·p0.9999: 14.053 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.931 ms/op
                 createUser·p0.9999: 15.735 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  14.826 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310371
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 516 
    [ 1.250,  2.500) = 18301 
    [ 2.500,  3.750) = 268951 
    [ 3.750,  5.000) = 20467 
    [ 5.000,  6.250) = 1236 
    [ 6.250,  7.500) = 408 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.497 ms/op
     p(99.9900) =     17.527 ms/op
     p(99.9990) =     18.114 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 14.712 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.240 ms/op
                 existUser·p0.999:  7.543 ms/op
                 existUser·p0.9999: 14.356 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.392 ms/op
                 existUser·p0.9999: 18.583 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325181
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 641 
    [ 1.250,  2.500) = 34740 
    [ 2.500,  3.750) = 278078 
    [ 3.750,  5.000) = 10378 
    [ 5.000,  6.250) = 671 
    [ 6.250,  7.500) = 348 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     18.185 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.690 ms/op
                 getUser·p0.9999: 17.193 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 3.059 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.532 ms/op
                 getUser·p0.9999: 15.738 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.098 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312179
  mean =      3.073 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 281 
    [ 1.250,  2.500) = 11472 
    [ 2.500,  3.750) = 283798 
    [ 3.750,  5.000) = 14803 
    [ 5.000,  6.250) = 1096 
    [ 6.250,  7.500) = 435 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.412 ms/op
     p(99.9900) =     17.746 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 5.642 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.553 ms/op
                 listUser·p0.9999: 24.514 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.993 ms/op
                 listUser·p0.999:  16.616 ms/op
                 listUser·p0.9999: 19.986 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.052 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  21.987 ms/op
                 listUser·p0.9999: 26.552 ms/op
                 listUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239425
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2227 
    [ 2.500,  5.000) = 211428 
    [ 5.000,  7.500) = 24145 
    [ 7.500, 10.000) = 1079 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.125 ms/op
     p(99.9000) =     16.862 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     28.509 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.494 ± 1.479  ops/ms
ClientGrpc.existUser                       thrpt       3  11.012 ± 2.050  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 2.414  ops/ms
ClientGrpc.listUser                        thrpt       3   7.972 ± 1.174  ops/ms
ClientGrpc.createUser                       avgt       3   3.070 ± 0.677   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.700   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.596   ms/op
ClientGrpc.listUser                         avgt       3   3.995 ± 0.363   ms/op
ClientGrpc.createUser                     sample  310371   3.091 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.497           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  325181   2.949 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.755           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.907           ms/op
ClientGrpc.getUser                        sample  312179   3.073 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.674           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.412           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.746           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.038           ms/op
ClientGrpc.listUser                       sample  239425   4.011 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.946           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.125           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.862           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.904           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.770           ms/op
