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
# Warmup Iteration   1: 4.291 ops/ms
# Warmup Iteration   2: 8.853 ops/ms
# Warmup Iteration   3: 9.755 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 10.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.204 ±(99.9%) 3.250 ops/ms [Average]
  (min, avg, max) = (10.037, 10.204, 10.392), stdev = 0.178
  CI (99.9%): [6.954, 13.454] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.809 ops/ms
Iteration   1: 10.835 ops/ms
Iteration   2: 11.057 ops/ms
Iteration   3: 11.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.143 ±(99.9%) 6.535 ops/ms [Average]
  (min, avg, max) = (10.835, 11.143, 11.536), stdev = 0.358
  CI (99.9%): [4.607, 17.678] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ops/ms
# Warmup Iteration   2: 10.116 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.325 ops/ms
Iteration   3: 10.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.393 ±(99.9%) 1.729 ops/ms [Average]
  (min, avg, max) = (10.325, 10.393, 10.501), stdev = 0.095
  CI (99.9%): [8.665, 12.122] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ops/ms
# Warmup Iteration   2: 7.756 ops/ms
# Warmup Iteration   3: 8.094 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.086 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (7.959, 8.086, 8.195), stdev = 0.119
  CI (99.9%): [5.921, 10.251] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.002 ms/op
Iteration   1: 3.146 ±(99.9%) 0.021 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 3.150 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.135 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.108, 3.135, 3.150), stdev = 0.024
  CI (99.9%): [2.706, 3.564] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 2.897 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (2.897, 2.948, 3.000), stdev = 0.051
  CI (99.9%): [2.013, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.004 ms/op
Iteration   2: 3.069 ±(99.9%) 0.004 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.032, 3.058, 3.073), stdev = 0.023
  CI (99.9%): [2.640, 3.476] (assumes normal distribution)


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
# Warmup Iteration   1: 5.513 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.025 ms/op
Iteration   1: 3.926 ±(99.9%) 0.025 ms/op
Iteration   2: 3.935 ±(99.9%) 0.029 ms/op
Iteration   3: 3.946 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.926, 3.936, 3.946), stdev = 0.010
  CI (99.9%): [3.750, 4.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.219 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  13.498 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312343
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18259 
    [ 2.500,  5.000) = 292208 
    [ 5.000,  7.500) = 1325 
    [ 7.500, 10.000) = 178 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     11.343 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     27.648 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.109 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.679 ms/op
                 existUser·p0.9999: 16.648 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.965 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.400 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.502 ms/op
                 existUser·p0.999:  12.345 ms/op
                 existUser·p0.9999: 18.884 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324700
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32227 
    [ 2.500,  5.000) = 290948 
    [ 5.000,  7.500) = 917 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     21.021 ms/op
     p(99.9990) =     22.733 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.484 ms/op
                 getUser·p0.9999: 12.206 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.995 ms/op
                 getUser·p0.9999: 28.541 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  15.385 ms/op
                 getUser·p0.9999: 22.966 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310134
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14080 
    [ 2.500,  5.000) = 294090 
    [ 5.000,  7.500) = 1440 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     10.035 ms/op
     p(99.9900) =     23.002 ms/op
     p(99.9990) =     28.800 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
Iteration   1: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.520 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.565 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.487 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 26.616 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 18.969 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243574
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2363 
    [ 2.500,  5.000) = 225930 
    [ 5.000,  7.500) = 14027 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.720 ms/op
     p(99.9900) =     21.971 ms/op
     p(99.9990) =     26.958 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.204 ± 3.250  ops/ms
ClientGrpc.existUser                       thrpt       3  11.143 ± 6.535  ops/ms
ClientGrpc.getUser                         thrpt       3  10.393 ± 1.729  ops/ms
ClientGrpc.listUser                        thrpt       3   8.086 ± 2.165  ops/ms
ClientGrpc.createUser                       avgt       3   3.135 ± 0.429   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.936   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.418   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 0.186   ms/op
ClientGrpc.createUser                     sample  312343   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.735           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.343           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.362           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.148           ms/op
ClientGrpc.existUser                      sample  324700   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.400           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.831           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  310134   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.035           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.002           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.950           ms/op
ClientGrpc.listUser                       sample  243574   3.939 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.487           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.720           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.971           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
