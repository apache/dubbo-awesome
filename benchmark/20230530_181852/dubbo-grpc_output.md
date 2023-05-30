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
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 8.439 ops/ms
# Warmup Iteration   3: 9.826 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.518 ±(99.9%) 6.477 ops/ms [Average]
  (min, avg, max) = (10.181, 10.518, 10.889), stdev = 0.355
  CI (99.9%): [4.041, 16.995] (assumes normal distribution)


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
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 10.565 ops/ms
# Warmup Iteration   3: 10.810 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 10.950 ops/ms
Iteration   3: 10.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.950 ±(99.9%) 0.765 ops/ms [Average]
  (min, avg, max) = (10.909, 10.950, 10.992), stdev = 0.042
  CI (99.9%): [10.185, 11.715] (assumes normal distribution)


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
# Warmup Iteration   1: 6.919 ops/ms
# Warmup Iteration   2: 9.875 ops/ms
# Warmup Iteration   3: 10.349 ops/ms
Iteration   1: 10.320 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.371 ±(99.9%) 1.752 ops/ms [Average]
  (min, avg, max) = (10.311, 10.371, 10.482), stdev = 0.096
  CI (99.9%): [8.619, 12.124] (assumes normal distribution)


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
# Warmup Iteration   1: 5.522 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 8.122 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.027 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (7.984, 8.027, 8.082), stdev = 0.050
  CI (99.9%): [7.111, 8.943] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.328 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.041 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (3.032, 3.041, 3.050), stdev = 0.009
  CI (99.9%): [2.874, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.003 ms/op
Iteration   1: 2.933 ±(99.9%) 0.001 ms/op
Iteration   2: 2.926 ±(99.9%) 0.001 ms/op
Iteration   3: 2.858 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (2.858, 2.906, 2.933), stdev = 0.041
  CI (99.9%): [2.155, 3.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.032, 3.047, 3.071), stdev = 0.021
  CI (99.9%): [2.662, 3.432] (assumes normal distribution)


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
# Warmup Iteration   1: 5.342 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.036 ms/op
Iteration   1: 3.927 ±(99.9%) 0.005 ms/op
Iteration   2: 4.037 ±(99.9%) 0.015 ms/op
Iteration   3: 3.931 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.927, 3.965, 4.037), stdev = 0.062
  CI (99.9%): [2.831, 5.098] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.471 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.634 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313074
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19268 
    [ 2.500,  5.000) = 292362 
    [ 5.000,  7.500) = 965 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     19.061 ms/op
     p(99.9990) =     20.607 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.805 ±(99.9%) 0.007 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.543 ms/op
                 existUser·p0.9999: 13.235 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.449 ms/op
                 existUser·p0.9999: 14.960 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.642 ms/op
                 existUser·p0.9999: 17.824 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332160
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1214 
    [ 1.250,  2.500) = 42134 
    [ 2.500,  3.750) = 280214 
    [ 3.750,  5.000) = 7601 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.896 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     18.132 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.884 ms/op
                 getUser·p0.9999: 12.861 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.956 ms/op
                 getUser·p0.9999: 15.193 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.111 ms/op
                 getUser·p0.9999: 18.246 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318150
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 463 
    [ 1.250,  2.500) = 17507 
    [ 2.500,  3.750) = 285616 
    [ 3.750,  5.000) = 13142 
    [ 5.000,  6.250) = 830 
    [ 6.250,  7.500) = 306 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.370 ms/op
     p(99.9900) =     16.783 ms/op
     p(99.9990) =     18.568 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 5.905 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  12.925 ms/op
                 listUser·p0.9999: 16.743 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 3.935 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  18.471 ms/op
                 listUser·p0.9999: 27.034 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   3: 3.926 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  18.128 ms/op
                 listUser·p0.9999: 25.292 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243735
  mean =      3.935 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2970 
    [ 2.500,  5.000) = 219679 
    [ 5.000,  7.500) = 19712 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     26.661 ms/op
     p(99.9990) =     29.405 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.518 ± 6.477  ops/ms
ClientGrpc.existUser                       thrpt       3  10.950 ± 0.765  ops/ms
ClientGrpc.getUser                         thrpt       3  10.371 ± 1.752  ops/ms
ClientGrpc.listUser                        thrpt       3   8.027 ± 0.916  ops/ms
ClientGrpc.createUser                       avgt       3   3.041 ± 0.167   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.751   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 1.133   ms/op
ClientGrpc.createUser                     sample  313074   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.061           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  332160   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.561           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.896           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  318150   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.783           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.038           ms/op
ClientGrpc.listUser                       sample  243735   3.935 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.800           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
