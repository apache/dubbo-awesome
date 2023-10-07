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
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.884 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.300 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (10.284, 10.300, 10.324), stdev = 0.021
  CI (99.9%): [9.908, 10.691] (assumes normal distribution)


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
# Warmup Iteration   1: 7.257 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.956 ops/ms
Iteration   2: 10.785 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.824 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (10.730, 10.824, 10.956), stdev = 0.118
  CI (99.9%): [8.680, 12.968] (assumes normal distribution)


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
# Warmup Iteration   1: 7.072 ops/ms
# Warmup Iteration   2: 9.827 ops/ms
# Warmup Iteration   3: 10.338 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 10.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.246 ±(99.9%) 2.838 ops/ms [Average]
  (min, avg, max) = (10.072, 10.246, 10.372), stdev = 0.156
  CI (99.9%): [7.407, 13.084] (assumes normal distribution)


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
# Warmup Iteration   1: 5.679 ops/ms
# Warmup Iteration   2: 7.859 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.027 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (7.914, 8.027, 8.121), stdev = 0.104
  CI (99.9%): [6.122, 9.931] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.135 ±(99.9%) 0.004 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.099, 3.121, 3.135), stdev = 0.019
  CI (99.9%): [2.767, 3.475] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.935 ±(99.9%) 0.003 ms/op
Iteration   2: 2.964 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.935, 2.960, 2.981), stdev = 0.024
  CI (99.9%): [2.529, 3.391] (assumes normal distribution)


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.004 ms/op
Iteration   1: 3.123 ±(99.9%) 0.003 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.111 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.080, 3.111, 3.128), stdev = 0.026
  CI (99.9%): [2.633, 3.588] (assumes normal distribution)


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
# Warmup Iteration   1: 5.990 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.027 ms/op
Iteration   1: 3.939 ±(99.9%) 0.017 ms/op
Iteration   2: 3.857 ±(99.9%) 0.012 ms/op
Iteration   3: 3.752 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 1.711 ms/op [Average]
  (min, avg, max) = (3.752, 3.849, 3.939), stdev = 0.094
  CI (99.9%): [2.139, 5.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.002 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  15.043 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308776
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13411 
    [ 2.500,  5.000) = 293448 
    [ 5.000,  7.500) = 1275 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     23.262 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.087 ms/op
                 existUser·p0.9999: 21.416 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 24.743 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 2.890 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 16.200 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322659
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32284 
    [ 2.500,  5.000) = 288777 
    [ 5.000,  7.500) = 1239 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.736 ms/op
     p(99.9900) =     21.485 ms/op
     p(99.9990) =     25.322 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.888 ms/op
                 getUser·p0.9999: 19.900 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.835 ms/op
                 getUser·p0.9999: 20.798 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.903 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309801
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13647 
    [ 2.500,  5.000) = 294384 
    [ 5.000,  7.500) = 1361 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     21.202 ms/op
     p(99.9990) =     22.750 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.546 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.556 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.929 ms/op
                 listUser·p0.999:  14.833 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 3.978 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 19.135 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242006
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3419 
    [ 2.500,  5.000) = 221199 
    [ 5.000,  7.500) = 16164 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     23.907 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.300 ± 0.391  ops/ms
ClientGrpc.existUser                       thrpt       3  10.824 ± 2.144  ops/ms
ClientGrpc.getUser                         thrpt       3  10.246 ± 2.838  ops/ms
ClientGrpc.listUser                        thrpt       3   8.027 ± 1.904  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 0.354   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.431   ms/op
ClientGrpc.getUser                          avgt       3   3.111 ± 0.478   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 1.711   ms/op
ClientGrpc.createUser                     sample  308776   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.683           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.940           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.429           ms/op
ClientGrpc.existUser                      sample  322659   2.973 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.624           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.736           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.485           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.461           ms/op
ClientGrpc.getUser                        sample  309801   3.097 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.066           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.202           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.069           ms/op
ClientGrpc.listUser                       sample  242006   3.965 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.841           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.907           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
