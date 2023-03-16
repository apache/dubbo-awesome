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
# Warmup Iteration   1: 3.926 ops/ms
# Warmup Iteration   2: 8.639 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.460 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (10.232, 10.460, 10.660), stdev = 0.215
  CI (99.9%): [6.534, 14.386] (assumes normal distribution)


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
# Warmup Iteration   1: 7.123 ops/ms
# Warmup Iteration   2: 10.586 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 11.075 ops/ms
Iteration   2: 10.709 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.890 ±(99.9%) 3.346 ops/ms [Average]
  (min, avg, max) = (10.709, 10.890, 11.075), stdev = 0.183
  CI (99.9%): [7.543, 14.236] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.706 ops/ms
# Warmup Iteration   2: 9.865 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.432 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.433 ±(99.9%) 1.650 ops/ms [Average]
  (min, avg, max) = (10.343, 10.433, 10.523), stdev = 0.090
  CI (99.9%): [8.782, 12.083] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ops/ms
# Warmup Iteration   2: 7.770 ops/ms
# Warmup Iteration   3: 7.960 ops/ms
Iteration   1: 7.815 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.920 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (7.815, 7.920, 8.036), stdev = 0.111
  CI (99.9%): [5.900, 9.939] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.128 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.101, 3.128, 3.167), stdev = 0.034
  CI (99.9%): [2.507, 3.750] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.815 ±(99.9%) 0.004 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.001 ms/op
Iteration   3: 2.950 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.946, 2.954, 2.965), stdev = 0.010
  CI (99.9%): [2.772, 3.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.075 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.064, 3.075, 3.094), stdev = 0.017
  CI (99.9%): [2.774, 3.376] (assumes normal distribution)


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
# Warmup Iteration   1: 4.913 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.017 ms/op
Iteration   1: 3.907 ±(99.9%) 0.009 ms/op
Iteration   2: 4.083 ±(99.9%) 0.042 ms/op
Iteration   3: 4.053 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (3.907, 4.014, 4.083), stdev = 0.094
  CI (99.9%): [2.294, 5.734] (assumes normal distribution)


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  6.713 ms/op
                 createUser·p0.9999: 25.983 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.748 ms/op
                 createUser·p0.9999: 22.023 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.138 ms/op
                 createUser·p0.9999: 23.575 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313715
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14854 
    [ 2.500,  5.000) = 297883 
    [ 5.000,  7.500) = 642 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.850 ms/op
     p(99.9900) =     25.023 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  7.559 ms/op
                 existUser·p0.9999: 19.401 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 2.985 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  5.841 ms/op
                 existUser·p0.9999: 13.214 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.949 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323955
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21115 
    [ 2.500,  5.000) = 302117 
    [ 5.000,  7.500) = 490 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     23.318 ms/op
     p(99.9990) =     26.567 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 4.460 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.706 ms/op
                 getUser·p0.9999: 13.791 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.641 ms/op
                 getUser·p0.9999: 15.095 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.750 ms/op
                 getUser·p0.9999: 26.367 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309254
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14472 
    [ 2.500,  5.000) = 293627 
    [ 5.000,  7.500) = 792 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.067 ms/op
     p(99.9900) =     25.627 ms/op
     p(99.9990) =     27.060 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 5.724 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.011 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.582 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.033 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 4.031 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.176 ms/op
                 listUser·p0.9999: 26.085 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   3: 4.023 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 21.728 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238424
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3351 
    [ 2.500,  5.000) = 209500 
    [ 5.000,  7.500) = 24278 
    [ 7.500, 10.000) = 911 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     15.165 ms/op
     p(99.9900) =     25.728 ms/op
     p(99.9990) =     27.008 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.460 ± 3.926  ops/ms
ClientGrpc.existUser                       thrpt       3  10.890 ± 3.346  ops/ms
ClientGrpc.getUser                         thrpt       3  10.433 ± 1.650  ops/ms
ClientGrpc.listUser                        thrpt       3   7.920 ± 2.020  ops/ms
ClientGrpc.createUser                       avgt       3   3.128 ± 0.622   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.182   ms/op
ClientGrpc.getUser                          avgt       3   3.075 ± 0.301   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 1.720   ms/op
ClientGrpc.createUser                     sample  313715   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.595           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.850           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.023           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  323955   2.962 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.318           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  309254   3.104 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.881           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.067           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  238424   4.026 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.582           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.165           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.728           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
