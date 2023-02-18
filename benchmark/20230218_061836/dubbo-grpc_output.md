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
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 8.911 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 9.860 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 10.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.077 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (9.860, 10.077, 10.288), stdev = 0.214
  CI (99.9%): [6.170, 13.985] (assumes normal distribution)


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
# Warmup Iteration   1: 7.595 ops/ms
# Warmup Iteration   2: 10.389 ops/ms
# Warmup Iteration   3: 10.725 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.478 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.561 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (10.478, 10.561, 10.711), stdev = 0.131
  CI (99.9%): [8.178, 12.943] (assumes normal distribution)


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
# Warmup Iteration   1: 7.227 ops/ms
# Warmup Iteration   2: 9.982 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 9.985 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.030 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (9.973, 10.030, 10.132), stdev = 0.089
  CI (99.9%): [8.410, 11.651] (assumes normal distribution)


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
# Warmup Iteration   1: 5.333 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 7.926 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.001 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (7.926, 8.001, 8.075), stdev = 0.074
  CI (99.9%): [6.645, 9.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.206 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.137, 3.170, 3.206), stdev = 0.034
  CI (99.9%): [2.543, 3.797] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.002 ms/op
Iteration   1: 2.998 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.975, 2.991, 3.002), stdev = 0.015
  CI (99.9%): [2.724, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.004 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.117, 3.151, 3.213), stdev = 0.053
  CI (99.9%): [2.176, 4.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.767 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.010 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
Iteration   2: 3.969 ±(99.9%) 0.016 ms/op
Iteration   3: 4.019 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.985 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.967, 3.985, 4.019), stdev = 0.029
  CI (99.9%): [3.450, 4.519] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  10.332 ms/op
                 createUser·p0.9999: 15.939 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.931 ms/op
                 createUser·p0.9999: 19.496 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  13.091 ms/op
                 createUser·p0.9999: 21.786 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302025
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27659 
    [ 2.500,  5.000) = 272886 
    [ 5.000,  7.500) = 978 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     10.501 ms/op
     p(99.9900) =     21.194 ms/op
     p(99.9990) =     22.084 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.652 ms/op
                 existUser·p0.9999: 19.888 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  7.331 ms/op
                 existUser·p0.9999: 14.596 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.861 ms/op
                 existUser·p0.9999: 16.978 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317250
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46204 
    [ 2.500,  5.000) = 270048 
    [ 5.000,  7.500) = 716 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.148 ms/op
     p(99.9900) =     19.178 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.232 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.282 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.554 ms/op
                 getUser·p0.9999: 23.494 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.582 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302066
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18184 
    [ 2.500,  5.000) = 282915 
    [ 5.000,  7.500) = 729 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.774 ms/op
     p(99.9900) =     23.914 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.010 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.372 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 15.841 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   3: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 21.426 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240439
  mean =      3.996 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1735 
    [ 2.500,  5.000) = 213303 
    [ 5.000,  7.500) = 24208 
    [ 7.500, 10.000) = 735 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.935 ms/op
     p(99.9000) =     14.247 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.341 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.077 ± 3.907  ops/ms
ClientGrpc.existUser                       thrpt       3  10.561 ± 2.383  ops/ms
ClientGrpc.getUser                         thrpt       3  10.030 ± 1.620  ops/ms
ClientGrpc.listUser                        thrpt       3   8.001 ± 1.356  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.627   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 0.267   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.975   ms/op
ClientGrpc.listUser                         avgt       3   3.985 ± 0.535   ms/op
ClientGrpc.createUser                     sample  302025   3.178 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.501           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.194           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  317250   3.025 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.148           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.178           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  302066   3.176 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.282           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.043           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.774           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.914           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.526           ms/op
ClientGrpc.listUser                       sample  240439   3.996 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.949           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.935           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.247           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
