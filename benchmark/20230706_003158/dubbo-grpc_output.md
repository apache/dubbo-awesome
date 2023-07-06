# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 9.526 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.648 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.567 ±(99.9%) 3.728 ops/ms [Average]
  (min, avg, max) = (10.335, 10.567, 10.719), stdev = 0.204
  CI (99.9%): [6.839, 14.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.734 ops/ms
# Warmup Iteration   3: 10.883 ops/ms
Iteration   1: 11.091 ops/ms
Iteration   2: 11.070 ops/ms
Iteration   3: 11.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.110 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (11.070, 11.110, 11.167), stdev = 0.051
  CI (99.9%): [10.178, 12.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.566 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (10.527, 10.566, 10.621), stdev = 0.049
  CI (99.9%): [9.666, 11.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.729 ops/ms
# Warmup Iteration   2: 7.944 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.139 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (8.067, 8.139, 8.243), stdev = 0.092
  CI (99.9%): [6.454, 9.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (3.017, 3.046, 3.080), stdev = 0.032
  CI (99.9%): [2.461, 3.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.004 ms/op
Iteration   1: 2.862 ±(99.9%) 0.004 ms/op
Iteration   2: 2.811 ±(99.9%) 0.004 ms/op
Iteration   3: 2.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.846 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (2.811, 2.846, 2.865), stdev = 0.031
  CI (99.9%): [2.286, 3.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.008, 3.033, 3.062), stdev = 0.027
  CI (99.9%): [2.537, 3.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.034 ms/op
Iteration   1: 3.968 ±(99.9%) 0.015 ms/op
Iteration   2: 3.761 ±(99.9%) 0.030 ms/op
Iteration   3: 3.918 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.882 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (3.761, 3.882, 3.968), stdev = 0.108
  CI (99.9%): [1.912, 5.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 11.763 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.252 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.159 ms/op
                 createUser·p0.999:  5.571 ms/op
                 createUser·p0.9999: 18.855 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  14.650 ms/op
                 createUser·p0.9999: 35.159 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319177
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24350 
    [ 2.500,  5.000) = 293382 
    [ 5.000,  7.500) = 1108 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.762 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     36.163 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
Iteration   1: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  5.294 ms/op
                 existUser·p0.9999: 11.059 ms/op
                 existUser·p1.00:   11.878 ms/op

Iteration   2: 2.932 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.760 ms/op
                 existUser·p0.9999: 23.071 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.488 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  8.006 ms/op
                 existUser·p0.9999: 15.482 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331214
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46005 
    [ 2.500,  5.000) = 284276 
    [ 5.000,  7.500) = 622 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.277 ms/op
     p(99.9900) =     15.753 ms/op
     p(99.9990) =     23.347 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.625 ms/op
                 getUser·p0.9999: 15.922 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.942 ms/op
                 getUser·p0.9999: 13.474 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 25.573 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318032
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14842 
    [ 2.500,  5.000) = 301901 
    [ 5.000,  7.500) = 935 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.437 ms/op
     p(99.9900) =     23.730 ms/op
     p(99.9990) =     25.881 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
Iteration   1: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 14.498 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.465 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.909 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.470 ms/op
                 listUser·p0.9999: 18.906 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238987
  mean =      4.018 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4191 
    [ 2.500,  5.000) = 208379 
    [ 5.000,  7.500) = 24943 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     16.813 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.567 ± 3.728  ops/ms
ClientGrpc.existUser                       thrpt       3  11.110 ± 0.931  ops/ms
ClientGrpc.getUser                         thrpt       3  10.566 ± 0.899  ops/ms
ClientGrpc.listUser                        thrpt       3   8.139 ± 1.685  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.585   ms/op
ClientGrpc.existUser                        avgt       3   2.846 ± 0.560   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.496   ms/op
ClientGrpc.listUser                         avgt       3   3.882 ± 1.970   ms/op
ClientGrpc.createUser                     sample  319177   3.008 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.252           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.762           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.341           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.241           ms/op
ClientGrpc.existUser                      sample  331214   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.488           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.277           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.753           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.626           ms/op
ClientGrpc.getUser                        sample  318032   3.017 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.527           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.437           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.730           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.952           ms/op
ClientGrpc.listUser                       sample  238987   4.018 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.813           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.087           ms/op
