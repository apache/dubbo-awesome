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
# Warmup Iteration   1: 3.633 ops/ms
# Warmup Iteration   2: 7.842 ops/ms
# Warmup Iteration   3: 9.473 ops/ms
Iteration   1: 10.025 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 10.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.046 ±(99.9%) 1.345 ops/ms [Average]
  (min, avg, max) = (9.984, 10.046, 10.127), stdev = 0.074
  CI (99.9%): [8.701, 11.390] (assumes normal distribution)


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
# Warmup Iteration   1: 6.439 ops/ms
# Warmup Iteration   2: 9.961 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.661 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (10.610, 10.661, 10.701), stdev = 0.046
  CI (99.9%): [9.819, 11.503] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ops/ms
# Warmup Iteration   2: 9.306 ops/ms
# Warmup Iteration   3: 10.110 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.329 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.222 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (10.113, 10.222, 10.329), stdev = 0.108
  CI (99.9%): [8.260, 12.185] (assumes normal distribution)


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
# Warmup Iteration   1: 4.888 ops/ms
# Warmup Iteration   2: 7.319 ops/ms
# Warmup Iteration   3: 7.360 ops/ms
Iteration   1: 7.479 ops/ms
Iteration   2: 7.730 ops/ms
Iteration   3: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.636 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (7.479, 7.636, 7.730), stdev = 0.137
  CI (99.9%): [5.134, 10.137] (assumes normal distribution)


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.008 ms/op
Iteration   1: 3.208 ±(99.9%) 0.017 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.173 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.192 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.173, 3.192, 3.208), stdev = 0.017
  CI (99.9%): [2.875, 3.508] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (2.958, 3.000, 3.029), stdev = 0.037
  CI (99.9%): [2.324, 3.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
Iteration   3: 3.107 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (3.107, 3.157, 3.202), stdev = 0.048
  CI (99.9%): [2.287, 4.027] (assumes normal distribution)


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
# Warmup Iteration   1: 6.048 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.022 ms/op
Iteration   1: 4.236 ±(99.9%) 0.024 ms/op
Iteration   2: 4.262 ±(99.9%) 0.024 ms/op
Iteration   3: 4.248 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.249 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (4.236, 4.249, 4.262), stdev = 0.013
  CI (99.9%): [4.006, 4.491] (assumes normal distribution)


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
# Warmup Iteration   1: 4.992 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  11.438 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  8.022 ms/op
                 createUser·p0.9999: 19.559 ms/op
                 createUser·p1.00:   19.988 ms/op

Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 19.068 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298451
  mean =      3.215 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12368 
    [ 2.500,  5.000) = 283494 
    [ 5.000,  7.500) = 1853 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     23.308 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.985 ms/op
                 existUser·p0.9999: 15.934 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.303 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 19.280 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  10.882 ms/op
                 existUser·p0.9999: 28.817 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316807
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19798 
    [ 2.500,  5.000) = 295286 
    [ 5.000,  7.500) = 1158 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.670 ms/op
     p(99.9900) =     27.874 ms/op
     p(99.9990) =     30.365 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  11.323 ms/op
                 getUser·p0.9999: 15.513 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 3.187 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  10.846 ms/op
                 getUser·p0.9999: 15.118 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.716 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  10.146 ms/op
                 getUser·p0.9999: 18.413 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301880
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11519 
    [ 2.500,  5.000) = 287996 
    [ 5.000,  7.500) = 1652 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     18.643 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 6.012 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.392 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.315 ±(99.9%) 0.013 ms/op
Iteration   1: 4.228 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.505 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 16.545 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  15.764 ms/op
                 listUser·p0.9999: 19.794 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.199 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  19.599 ms/op
                 listUser·p0.9999: 24.535 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228441
  mean =      4.204 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 958 
    [ 2.500,  5.000) = 197261 
    [ 5.000,  7.500) = 27810 
    [ 7.500, 10.000) = 1934 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     23.472 ms/op
     p(99.9990) =     24.731 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.046 ± 1.345  ops/ms
ClientGrpc.existUser                       thrpt       3  10.661 ± 0.842  ops/ms
ClientGrpc.getUser                         thrpt       3  10.222 ± 1.962  ops/ms
ClientGrpc.listUser                        thrpt       3   7.636 ± 2.502  ops/ms
ClientGrpc.createUser                       avgt       3   3.192 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.676   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.870   ms/op
ClientGrpc.listUser                         avgt       3   4.249 ± 0.242   ms/op
ClientGrpc.createUser                     sample  298451   3.215 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.338           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.314           ms/op
ClientGrpc.existUser                      sample  316807   3.030 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.670           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.874           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.507           ms/op
ClientGrpc.getUser                        sample  301880   3.178 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.152           ms/op
ClientGrpc.listUser                       sample  228441   4.204 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.006           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.472           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
