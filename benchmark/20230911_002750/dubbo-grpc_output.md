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
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 9.865 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.306 ±(99.9%) 3.052 ops/ms [Average]
  (min, avg, max) = (10.113, 10.306, 10.412), stdev = 0.167
  CI (99.9%): [7.254, 13.358] (assumes normal distribution)


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
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 10.341 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 10.923 ops/ms
Iteration   3: 10.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.887 ±(99.9%) 0.716 ops/ms [Average]
  (min, avg, max) = (10.845, 10.887, 10.923), stdev = 0.039
  CI (99.9%): [10.171, 11.604] (assumes normal distribution)


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
# Warmup Iteration   1: 6.482 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.203 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.215 ±(99.9%) 3.911 ops/ms [Average]
  (min, avg, max) = (10.034, 10.215, 10.452), stdev = 0.214
  CI (99.9%): [6.303, 14.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.362 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 7.916 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 7.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.862 ±(99.9%) 3.613 ops/ms [Average]
  (min, avg, max) = (7.643, 7.862, 8.027), stdev = 0.198
  CI (99.9%): [4.249, 11.475] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.096 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.114 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.096, 3.114, 3.128), stdev = 0.016
  CI (99.9%): [2.815, 3.413] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 2.936 ±(99.9%) 0.003 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.934 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.932, 2.934, 2.936), stdev = 0.002
  CI (99.9%): [2.897, 2.971] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.086 ±(99.9%) 0.004 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.049, 3.069, 3.086), stdev = 0.019
  CI (99.9%): [2.722, 3.416] (assumes normal distribution)


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
# Warmup Iteration   1: 5.498 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.031 ms/op
Iteration   1: 4.159 ±(99.9%) 0.017 ms/op
Iteration   2: 4.033 ±(99.9%) 0.010 ms/op
Iteration   3: 4.086 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.093 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (4.033, 4.093, 4.159), stdev = 0.063
  CI (99.9%): [2.940, 5.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.691 ms/op
                 createUser·p0.9999: 14.395 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  8.354 ms/op
                 createUser·p0.9999: 16.079 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309256
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16291 
    [ 2.500,  5.000) = 290713 
    [ 5.000,  7.500) = 1648 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     25.103 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.687 ms/op
                 existUser·p0.9999: 13.116 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 19.994 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  12.442 ms/op
                 existUser·p0.9999: 18.325 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323451
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31950 
    [ 2.500,  5.000) = 289566 
    [ 5.000,  7.500) = 1260 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     18.393 ms/op
     p(99.9990) =     20.210 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.650 ms/op
                 getUser·p0.9999: 14.044 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.682 ms/op
                 getUser·p0.9999: 18.889 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313808
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15372 
    [ 2.500,  5.000) = 296391 
    [ 5.000,  7.500) = 1730 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     20.894 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 5.900 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.011 ms/op
Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  14.630 ms/op
                 listUser·p0.9999: 16.882 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.447 ms/op
                 listUser·p0.9999: 21.344 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.147 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 20.328 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233429
  mean =      4.112 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1737 
    [ 2.500,  5.000) = 205727 
    [ 5.000,  7.500) = 23679 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.485 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.306 ± 3.052  ops/ms
ClientGrpc.existUser                       thrpt       3  10.887 ± 0.716  ops/ms
ClientGrpc.getUser                         thrpt       3  10.215 ± 3.911  ops/ms
ClientGrpc.listUser                        thrpt       3   7.862 ± 3.613  ops/ms
ClientGrpc.createUser                       avgt       3   3.114 ± 0.299   ms/op
ClientGrpc.existUser                        avgt       3   2.934 ± 0.037   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.347   ms/op
ClientGrpc.listUser                         avgt       3   4.093 ± 1.153   ms/op
ClientGrpc.createUser                     sample  309256   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.515           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.355           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.103           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  323451   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.781           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.393           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  313808   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.327           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.894           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  233429   4.112 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.178           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.463           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.450           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.004           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
