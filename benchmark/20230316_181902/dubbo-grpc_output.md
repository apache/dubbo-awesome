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
# Warmup Iteration   1: 4.606 ops/ms
# Warmup Iteration   2: 9.452 ops/ms
# Warmup Iteration   3: 10.656 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.920 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.793 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (10.706, 10.793, 10.920), stdev = 0.112
  CI (99.9%): [8.753, 12.834] (assumes normal distribution)


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
# Warmup Iteration   1: 7.918 ops/ms
# Warmup Iteration   2: 10.849 ops/ms
# Warmup Iteration   3: 11.334 ops/ms
Iteration   1: 11.463 ops/ms
Iteration   2: 11.419 ops/ms
Iteration   3: 11.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.419 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (11.375, 11.419, 11.463), stdev = 0.044
  CI (99.9%): [10.616, 12.223] (assumes normal distribution)


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
# Warmup Iteration   1: 8.164 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.708 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.887 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (10.796, 10.887, 10.944), stdev = 0.080
  CI (99.9%): [9.429, 12.345] (assumes normal distribution)


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
# Warmup Iteration   1: 7.089 ops/ms
# Warmup Iteration   2: 7.987 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.268 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.373 ±(99.9%) 1.667 ops/ms [Average]
  (min, avg, max) = (8.268, 8.373, 8.437), stdev = 0.091
  CI (99.9%): [6.706, 10.040] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.008 ms/op
Iteration   1: 2.973 ±(99.9%) 0.001 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.958 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.967 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.958, 2.967, 2.973), stdev = 0.008
  CI (99.9%): [2.829, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.003 ms/op
Iteration   2: 2.820 ±(99.9%) 0.003 ms/op
Iteration   3: 2.887 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.857 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (2.820, 2.857, 2.887), stdev = 0.034
  CI (99.9%): [2.240, 3.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 2.933 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (2.933, 2.964, 2.998), stdev = 0.033
  CI (99.9%): [2.370, 3.557] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.009 ms/op
Iteration   1: 3.838 ±(99.9%) 0.013 ms/op
Iteration   2: 3.830 ±(99.9%) 0.021 ms/op
Iteration   3: 3.847 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.839 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.830, 3.839, 3.847), stdev = 0.009
  CI (99.9%): [3.681, 3.997] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.007 ms/op
Iteration   1: 2.932 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.914 ms/op
                 createUser·p0.9999: 13.110 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  6.333 ms/op
                 createUser·p0.9999: 12.968 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.286 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.182 ms/op
                 createUser·p0.9999: 16.206 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326725
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1845 
    [ 1.250,  2.500) = 30056 
    [ 2.500,  3.750) = 283703 
    [ 3.750,  5.000) = 9798 
    [ 5.000,  6.250) = 673 
    [ 6.250,  7.500) = 333 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.432 ms/op
     p(99.9900) =     14.379 ms/op
     p(99.9990) =     16.567 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.006 ms/op
Iteration   1: 2.868 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  7.244 ms/op
                 existUser·p0.9999: 12.400 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.810 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.236 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  5.137 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.849 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.388 ms/op
                 existUser·p0.999:  6.571 ms/op
                 existUser·p0.9999: 19.391 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337787
  mean =      2.842 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1903 
    [ 1.250,  2.500) = 44418 
    [ 2.500,  3.750) = 284116 
    [ 3.750,  5.000) = 6669 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.029 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     19.747 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.360 ms/op
                 getUser·p0.9999: 14.502 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.866 ms/op
                 getUser·p0.9999: 18.781 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  11.454 ms/op
                 getUser·p0.9999: 14.964 ms/op
                 getUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326070
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2259 
    [ 1.250,  2.500) = 32197 
    [ 2.500,  3.750) = 279216 
    [ 3.750,  5.000) = 11389 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.839 ms/op
     p(99.9900) =     16.414 ms/op
     p(99.9990) =     18.988 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.010 ms/op
Iteration   1: 3.804 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.579 ms/op
                 listUser·p0.999:  12.138 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   15.843 ms/op

Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.520 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.602 ms/op
                 listUser·p0.9999: 24.106 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.095 ms/op
                 listUser·p0.9999: 24.572 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248777
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6523 
    [ 2.500,  5.000) = 219859 
    [ 5.000,  7.500) = 21318 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.455 ms/op
     p(99.9900) =     23.994 ms/op
     p(99.9990) =     24.905 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.793 ± 2.040  ops/ms
ClientGrpc.existUser                       thrpt       3  11.419 ± 0.803  ops/ms
ClientGrpc.getUser                         thrpt       3  10.887 ± 1.458  ops/ms
ClientGrpc.listUser                        thrpt       3   8.373 ± 1.667  ops/ms
ClientGrpc.createUser                       avgt       3   2.967 ± 0.137   ms/op
ClientGrpc.existUser                        avgt       3   2.857 ± 0.617   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.593   ms/op
ClientGrpc.listUser                         avgt       3   3.839 ± 0.158   ms/op
ClientGrpc.createUser                     sample  326725   2.938 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.286           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.379           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.432           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.379           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.695           ms/op
ClientGrpc.existUser                      sample  337787   2.842 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.535           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.252           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  326070   2.943 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.839           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.414           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  248777   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.455           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.994           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
