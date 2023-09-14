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
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 8.273 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.315 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (10.213, 10.315, 10.403), stdev = 0.096
  CI (99.9%): [8.571, 12.058] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.716 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (10.608, 10.716, 10.847), stdev = 0.121
  CI (99.9%): [8.500, 12.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.095 ops/ms
# Warmup Iteration   2: 9.936 ops/ms
# Warmup Iteration   3: 10.191 ops/ms
Iteration   1: 10.236 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.240 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (10.198, 10.240, 10.284), stdev = 0.043
  CI (99.9%): [9.455, 11.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.371 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.398 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (8.316, 8.398, 8.544), stdev = 0.126
  CI (99.9%): [6.098, 10.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.068, 3.098, 3.115), stdev = 0.026
  CI (99.9%): [2.616, 3.581] (assumes normal distribution)


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 2.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (2.891, 2.973, 3.043), stdev = 0.077
  CI (99.9%): [1.574, 4.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.077 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.061, 3.077, 3.090), stdev = 0.015
  CI (99.9%): [2.808, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.999 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.029 ms/op
Iteration   1: 3.677 ±(99.9%) 0.022 ms/op
Iteration   2: 3.786 ±(99.9%) 0.053 ms/op
Iteration   3: 3.834 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.766 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (3.677, 3.766, 3.834), stdev = 0.080
  CI (99.9%): [2.301, 5.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.515 ms/op
                 createUser·p0.9999: 18.232 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 15.306 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.262 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.977 ms/op
                 createUser·p0.9999: 17.740 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312892
  mean =      3.069 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11783 
    [ 2.500,  5.000) = 299549 
    [ 5.000,  7.500) = 1165 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.262 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     20.002 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.019 ms/op
                 existUser·p0.999:  6.799 ms/op
                 existUser·p0.9999: 14.959 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 14.893 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.166 ms/op
                 existUser·p0.9999: 16.632 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324862
  mean =      2.956 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1441 
    [ 1.250,  2.500) = 29183 
    [ 2.500,  3.750) = 282394 
    [ 3.750,  5.000) = 10520 
    [ 5.000,  6.250) = 743 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.918 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.139 ms/op
     p(99.9900) =     15.025 ms/op
     p(99.9990) =     17.023 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 14.822 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  5.829 ms/op
                 getUser·p0.9999: 14.178 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 19.487 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313946
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 321 
    [ 1.250,  2.500) = 9721 
    [ 2.500,  3.750) = 291838 
    [ 3.750,  5.000) = 10576 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.859 ms/op
     p(99.9900) =     18.915 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.009 ms/op
Iteration   1: 3.833 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  11.747 ms/op
                 listUser·p0.9999: 16.503 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.878 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 20.210 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  13.949 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249710
  mean =      3.845 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1716 
    [ 2.500,  5.000) = 236022 
    [ 5.000,  7.500) = 11090 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     12.670 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     21.742 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.315 ± 1.743  ops/ms
ClientGrpc.existUser                       thrpt       3  10.716 ± 2.216  ops/ms
ClientGrpc.getUser                         thrpt       3  10.240 ± 0.785  ops/ms
ClientGrpc.listUser                        thrpt       3   8.398 ± 2.300  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.483   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 1.399   ms/op
ClientGrpc.getUser                          avgt       3   3.077 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   3.766 ± 1.465   ms/op
ClientGrpc.createUser                     sample  312892   3.069 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.262           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  324862   2.956 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.918           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.139           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.025           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  313946   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.859           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.915           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  249710   3.845 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.670           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.055           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.200           ms/op
