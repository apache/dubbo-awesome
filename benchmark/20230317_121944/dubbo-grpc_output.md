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
# Warmup Iteration   1: 3.894 ops/ms
# Warmup Iteration   2: 8.949 ops/ms
# Warmup Iteration   3: 10.154 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.515 ±(99.9%) 1.071 ops/ms [Average]
  (min, avg, max) = (10.455, 10.515, 10.572), stdev = 0.059
  CI (99.9%): [9.445, 11.586] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.663 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.996 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 10.853 ops/ms
Iteration   3: 10.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.818 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (10.674, 10.818, 10.928), stdev = 0.130
  CI (99.9%): [8.441, 13.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.598 ops/ms
# Warmup Iteration   2: 9.953 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.363 ±(99.9%) 1.201 ops/ms [Average]
  (min, avg, max) = (10.295, 10.363, 10.426), stdev = 0.066
  CI (99.9%): [9.162, 11.564] (assumes normal distribution)


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
# Warmup Iteration   1: 5.882 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.964 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.964 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (7.880, 7.964, 8.025), stdev = 0.075
  CI (99.9%): [6.596, 9.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.073 ±(99.9%) 0.012 ms/op
Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.038, 3.056, 3.073), stdev = 0.018
  CI (99.9%): [2.729, 3.384] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.002 ms/op
Iteration   1: 2.928 ±(99.9%) 0.002 ms/op
Iteration   2: 2.919 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.919, 2.926, 2.932), stdev = 0.007
  CI (99.9%): [2.807, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (3.067, 3.071, 3.078), stdev = 0.006
  CI (99.9%): [2.969, 3.174] (assumes normal distribution)


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
# Warmup Iteration   1: 5.437 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.026 ms/op
Iteration   1: 4.109 ±(99.9%) 0.037 ms/op
Iteration   2: 3.938 ±(99.9%) 0.045 ms/op
Iteration   3: 3.960 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.002 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.938, 4.002, 4.109), stdev = 0.093
  CI (99.9%): [2.299, 5.706] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  6.850 ms/op
                 createUser·p0.9999: 13.370 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  12.011 ms/op
                 createUser·p0.9999: 19.311 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.992 ms/op
                 createUser·p0.9999: 17.812 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315858
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 871 
    [ 1.250,  2.500) = 21950 
    [ 2.500,  3.750) = 276871 
    [ 3.750,  5.000) = 14744 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.985 ms/op
     p(99.9900) =     18.565 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.005 ms/op
Iteration   1: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.589 ms/op
                 existUser·p0.9999: 31.293 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   2: 2.902 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 14.384 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.919 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  7.780 ms/op
                 existUser·p0.9999: 17.959 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329252
  mean =      2.916 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38130 
    [ 2.500,  5.000) = 289793 
    [ 5.000,  7.500) = 1000 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     19.299 ms/op
     p(99.9990) =     31.513 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 4.403 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.364 ms/op
                 getUser·p0.9999: 13.376 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.945 ms/op
                 getUser·p0.9999: 18.398 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.182 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315195
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25407 
    [ 2.500,  5.000) = 288367 
    [ 5.000,  7.500) = 1059 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.787 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.011 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.724 ms/op
                 listUser·p0.9999: 26.278 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   2: 3.966 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.019 ms/op
                 listUser·p0.9999: 16.738 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  17.214 ms/op
                 listUser·p0.9999: 27.962 ms/op
                 listUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242951
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3109 
    [ 2.500,  5.000) = 219314 
    [ 5.000,  7.500) = 19196 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     26.598 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.515 ± 1.071  ops/ms
ClientGrpc.existUser                       thrpt       3  10.818 ± 2.378  ops/ms
ClientGrpc.getUser                         thrpt       3  10.363 ± 1.201  ops/ms
ClientGrpc.listUser                        thrpt       3   7.964 ± 1.368  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.328   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 0.119   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.103   ms/op
ClientGrpc.listUser                         avgt       3   4.002 ± 1.703   ms/op
ClientGrpc.createUser                     sample  315858   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.985           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.565           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  329252   2.916 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.786           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.299           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.588           ms/op
ClientGrpc.getUser                        sample  315195   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.857           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.787           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.448           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  242951   3.950 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.401           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.598           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.901           ms/op
