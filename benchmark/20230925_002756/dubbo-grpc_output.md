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
# Warmup Iteration   1: 4.045 ops/ms
# Warmup Iteration   2: 8.918 ops/ms
# Warmup Iteration   3: 9.705 ops/ms
Iteration   1: 10.095 ops/ms
Iteration   2: 9.985 ops/ms
Iteration   3: 10.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.032 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (9.985, 10.032, 10.095), stdev = 0.057
  CI (99.9%): [8.999, 11.064] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.195 ops/ms
# Warmup Iteration   2: 10.288 ops/ms
# Warmup Iteration   3: 10.583 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.650 ±(99.9%) 4.006 ops/ms [Average]
  (min, avg, max) = (10.508, 10.650, 10.903), stdev = 0.220
  CI (99.9%): [6.644, 14.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.365 ops/ms
# Warmup Iteration   2: 9.927 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.312 ops/ms
Iteration   2: 10.141 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.246 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (10.141, 10.246, 10.312), stdev = 0.092
  CI (99.9%): [8.575, 11.917] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.101 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (8.013, 8.101, 8.212), stdev = 0.101
  CI (99.9%): [6.257, 9.945] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.517 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.001 ms/op
Iteration   1: 3.123 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.093 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.041, 3.093, 3.123), stdev = 0.045
  CI (99.9%): [2.277, 3.908] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (2.909, 2.972, 3.011), stdev = 0.055
  CI (99.9%): [1.968, 3.976] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.381 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.004 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.139 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.112, 3.139, 3.170), stdev = 0.029
  CI (99.9%): [2.609, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.014 ms/op
Iteration   1: 3.948 ±(99.9%) 0.033 ms/op
Iteration   2: 3.921 ±(99.9%) 0.008 ms/op
Iteration   3: 3.772 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.880 ±(99.9%) 1.727 ms/op [Average]
  (min, avg, max) = (3.772, 3.880, 3.948), stdev = 0.095
  CI (99.9%): [2.153, 5.608] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.803 ms/op
                 createUser·p0.9999: 16.134 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 3.221 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 14.453 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 3.145 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.181 ms/op
                 createUser·p0.9999: 15.742 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302496
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 7444 
    [ 2.500,  3.750) = 267819 
    [ 3.750,  5.000) = 25135 
    [ 5.000,  6.250) = 968 
    [ 6.250,  7.500) = 478 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     16.972 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.586 ms/op
                 existUser·p0.9999: 16.607 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  12.093 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 14.727 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317496
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 739 
    [ 1.250,  2.500) = 20539 
    [ 2.500,  3.750) = 284299 
    [ 3.750,  5.000) = 10254 
    [ 5.000,  6.250) = 835 
    [ 6.250,  7.500) = 362 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     15.151 ms/op
     p(99.9990) =     16.774 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.755 ms/op
                 getUser·p0.9999: 21.410 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.476 ms/op
                 getUser·p0.9999: 23.844 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.488 ms/op
                 getUser·p0.9999: 24.652 ms/op
                 getUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308069
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10799 
    [ 2.500,  5.000) = 295620 
    [ 5.000,  7.500) = 1358 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     23.599 ms/op
     p(99.9990) =     25.349 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.010 ms/op
Iteration   1: 3.978 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.362 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   2: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.562 ms/op
                 listUser·p0.9999: 16.598 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.917 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.750 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.646 ms/op
                 listUser·p0.999:  15.046 ms/op
                 listUser·p0.9999: 24.494 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243259
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2099 
    [ 2.500,  5.000) = 226272 
    [ 5.000,  7.500) = 13921 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     15.081 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.810 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.032 ± 1.032  ops/ms
ClientGrpc.existUser                       thrpt       3  10.650 ± 4.006  ops/ms
ClientGrpc.getUser                         thrpt       3  10.246 ± 1.671  ops/ms
ClientGrpc.listUser                        thrpt       3   8.101 ± 1.844  ops/ms
ClientGrpc.createUser                       avgt       3   3.093 ± 0.815   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 1.004   ms/op
ClientGrpc.getUser                          avgt       3   3.139 ± 0.531   ms/op
ClientGrpc.listUser                         avgt       3   3.880 ± 1.727   ms/op
ClientGrpc.createUser                     sample  302496   3.173 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.622           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.830           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.663           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.236           ms/op
ClientGrpc.existUser                      sample  317496   3.024 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.732           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  308069   3.114 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.455           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.599           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.526           ms/op
ClientGrpc.listUser                       sample  243259   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.750           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.081           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
