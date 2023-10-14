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
# Warmup Iteration   1: 4.124 ops/ms
# Warmup Iteration   2: 8.900 ops/ms
# Warmup Iteration   3: 9.912 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.204 ±(99.9%) 2.473 ops/ms [Average]
  (min, avg, max) = (10.054, 10.204, 10.317), stdev = 0.136
  CI (99.9%): [7.731, 12.678] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.244 ops/ms
# Warmup Iteration   2: 9.987 ops/ms
# Warmup Iteration   3: 10.361 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.616 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (10.555, 10.616, 10.698), stdev = 0.073
  CI (99.9%): [9.276, 11.956] (assumes normal distribution)


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
# Warmup Iteration   1: 6.304 ops/ms
# Warmup Iteration   2: 9.825 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.275 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (10.210, 10.275, 10.324), stdev = 0.059
  CI (99.9%): [9.200, 11.351] (assumes normal distribution)


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
# Warmup Iteration   1: 5.355 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.137 ±(99.9%) 4.381 ops/ms [Average]
  (min, avg, max) = (7.928, 8.137, 8.399), stdev = 0.240
  CI (99.9%): [3.756, 12.519] (assumes normal distribution)


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.009 ms/op
Iteration   1: 3.158 ±(99.9%) 0.004 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.124, 3.154, 3.180), stdev = 0.028
  CI (99.9%): [2.641, 3.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.004 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.982, 2.995, 3.012), stdev = 0.015
  CI (99.9%): [2.715, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.002 ms/op
Iteration   1: 3.087 ±(99.9%) 0.004 ms/op
Iteration   2: 3.129 ±(99.9%) 0.005 ms/op
Iteration   3: 3.163 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.126 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.087, 3.126, 3.163), stdev = 0.038
  CI (99.9%): [2.430, 3.822] (assumes normal distribution)


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
# Warmup Iteration   1: 5.545 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.016 ms/op
Iteration   1: 3.993 ±(99.9%) 0.053 ms/op
Iteration   2: 3.857 ±(99.9%) 0.010 ms/op
Iteration   3: 3.969 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.857, 3.940, 3.993), stdev = 0.073
  CI (99.9%): [2.612, 5.268] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.160 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  14.544 ms/op
                 createUser·p0.9999: 19.849 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.980 ms/op
                 createUser·p0.9999: 18.272 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 3.129 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304784
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11128 
    [ 2.500,  5.000) = 291284 
    [ 5.000,  7.500) = 1761 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     13.458 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     27.196 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.694 ms/op
                 existUser·p0.9999: 17.641 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 14.689 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  14.812 ms/op
                 existUser·p0.9999: 24.622 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316891
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23058 
    [ 2.500,  5.000) = 292384 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     22.227 ms/op
     p(99.9990) =     24.931 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 24.310 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.431 ms/op
                 getUser·p0.9999: 29.708 ms/op
                 getUser·p1.00:   31.392 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.391 ms/op
                 getUser·p0.9999: 22.377 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302774
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5258 
    [ 2.500,  5.000) = 296086 
    [ 5.000,  7.500) = 1066 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.469 ms/op
     p(99.9900) =     28.335 ms/op
     p(99.9990) =     30.211 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.009 ms/op
Iteration   1: 4.027 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.864 ms/op
                 listUser·p0.999:  15.066 ms/op
                 listUser·p0.9999: 28.019 ms/op
                 listUser·p1.00:   28.279 ms/op

Iteration   2: 4.030 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 25.040 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  18.000 ms/op
                 listUser·p0.9999: 29.194 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239757
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2362 
    [ 2.500,  5.000) = 220647 
    [ 5.000,  7.500) = 15330 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     28.543 ms/op
     p(99.9990) =     29.249 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.204 ± 2.473  ops/ms
ClientGrpc.existUser                       thrpt       3  10.616 ± 1.340  ops/ms
ClientGrpc.getUser                         thrpt       3  10.275 ± 1.075  ops/ms
ClientGrpc.listUser                        thrpt       3   8.137 ± 4.381  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.280   ms/op
ClientGrpc.getUser                          avgt       3   3.126 ± 0.696   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 1.328   ms/op
ClientGrpc.createUser                     sample  304784   3.150 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.481           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.458           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.034           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.114           ms/op
ClientGrpc.existUser                      sample  316891   3.029 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.490           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.227           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.035           ms/op
ClientGrpc.getUser                        sample  302774   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.807           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.335           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.392           ms/op
ClientGrpc.listUser                       sample  239757   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.993           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.262           ms/op
