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
# Warmup Iteration   1: 4.602 ops/ms
# Warmup Iteration   2: 9.626 ops/ms
# Warmup Iteration   3: 10.698 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.395 ±(99.9%) 4.784 ops/ms [Average]
  (min, avg, max) = (10.093, 10.395, 10.564), stdev = 0.262
  CI (99.9%): [5.610, 15.179] (assumes normal distribution)


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
# Warmup Iteration   1: 8.133 ops/ms
# Warmup Iteration   2: 10.978 ops/ms
# Warmup Iteration   3: 10.987 ops/ms
Iteration   1: 10.953 ops/ms
Iteration   2: 10.982 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.003 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (10.953, 11.003, 11.075), stdev = 0.064
  CI (99.9%): [9.838, 12.169] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.787 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 4.422 ops/ms [Average]
  (min, avg, max) = (10.305, 10.577, 10.770), stdev = 0.242
  CI (99.9%): [6.155, 15.000] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.422 ops/ms
# Warmup Iteration   2: 8.039 ops/ms
# Warmup Iteration   3: 8.347 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 8.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.133 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (8.045, 8.133, 8.178), stdev = 0.076
  CI (99.9%): [6.754, 9.511] (assumes normal distribution)


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.002 ms/op
Iteration   1: 2.944 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.969 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.944, 2.969, 3.008), stdev = 0.034
  CI (99.9%): [2.349, 3.589] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.900 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.935 ±(99.9%) 0.002 ms/op
Iteration   2: 2.901 ±(99.9%) 0.002 ms/op
Iteration   3: 2.886 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.886, 2.907, 2.935), stdev = 0.025
  CI (99.9%): [2.453, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.002 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (2.972, 3.023, 3.070), stdev = 0.049
  CI (99.9%): [2.129, 3.917] (assumes normal distribution)


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
# Warmup Iteration   1: 5.021 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.021 ms/op
Iteration   1: 3.994 ±(99.9%) 0.015 ms/op
Iteration   2: 3.985 ±(99.9%) 0.016 ms/op
Iteration   3: 4.085 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.985, 4.021, 4.085), stdev = 0.055
  CI (99.9%): [3.013, 5.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.011 ms/op
                 createUser·p0.9999: 14.733 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.256 ms/op
                 createUser·p0.9999: 15.937 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.214 ms/op
                 createUser·p0.9999: 19.672 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315303
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31251 
    [ 2.500,  5.000) = 283155 
    [ 5.000,  7.500) = 672 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     17.874 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.701 ms/op
                 existUser·p0.9999: 17.303 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   2: 2.824 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.741 ms/op
                 existUser·p0.9999: 16.466 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.970 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332894
  mean =      2.883 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4238 
    [ 1.250,  2.500) = 58408 
    [ 2.500,  3.750) = 255735 
    [ 3.750,  5.000) = 13694 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.226 ms/op
     p(99.9900) =     16.686 ms/op
     p(99.9990) =     18.197 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.505 ms/op
                 getUser·p0.9999: 17.214 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  6.062 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.434 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.602 ms/op
                 getUser·p0.9999: 16.155 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320594
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37670 
    [ 2.500,  5.000) = 282041 
    [ 5.000,  7.500) = 674 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      6.446 ms/op
     p(99.9900) =     20.927 ms/op
     p(99.9990) =     22.144 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 5.071 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.010 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.273 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  11.174 ms/op
                 listUser·p0.9999: 13.974 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.709 ms/op
                 listUser·p0.9999: 21.796 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.508 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.084 ms/op
                 listUser·p0.9999: 23.433 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238749
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4130 
    [ 2.500,  5.000) = 200257 
    [ 5.000,  7.500) = 33242 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.273 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     13.709 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.764 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.395 ± 4.784  ops/ms
ClientGrpc.existUser                       thrpt       3  11.003 ± 1.166  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 4.422  ops/ms
ClientGrpc.listUser                        thrpt       3   8.133 ± 1.378  ops/ms
ClientGrpc.createUser                       avgt       3   2.969 ± 0.620   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.454   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.894   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 1.008   ms/op
ClientGrpc.createUser                     sample  315303   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.507           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.824           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.874           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.480           ms/op
ClientGrpc.existUser                      sample  332894   2.883 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.226           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.686           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  320594   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.434           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.446           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.927           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.184           ms/op
ClientGrpc.listUser                       sample  238749   4.022 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.273           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.709           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.086           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
