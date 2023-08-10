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
# Warmup Iteration   1: 3.925 ops/ms
# Warmup Iteration   2: 8.953 ops/ms
# Warmup Iteration   3: 9.934 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.423 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (10.358, 10.423, 10.477), stdev = 0.061
  CI (99.9%): [9.318, 11.528] (assumes normal distribution)


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
# Warmup Iteration   1: 7.115 ops/ms
# Warmup Iteration   2: 10.197 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 10.831 ops/ms
Iteration   2: 11.311 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.988 ±(99.9%) 5.105 ops/ms [Average]
  (min, avg, max) = (10.822, 10.988, 11.311), stdev = 0.280
  CI (99.9%): [5.883, 16.093] (assumes normal distribution)


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
# Warmup Iteration   1: 6.337 ops/ms
# Warmup Iteration   2: 9.670 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.306 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (10.266, 10.306, 10.353), stdev = 0.044
  CI (99.9%): [9.506, 11.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.993 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.881 ops/ms
Iteration   2: 7.948 ops/ms
Iteration   3: 7.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.919 ±(99.9%) 0.629 ops/ms [Average]
  (min, avg, max) = (7.881, 7.919, 7.948), stdev = 0.034
  CI (99.9%): [7.290, 8.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.005 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (3.063, 3.084, 3.117), stdev = 0.029
  CI (99.9%): [2.554, 3.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.881 ±(99.9%) 0.003 ms/op
Iteration   2: 2.833 ±(99.9%) 0.004 ms/op
Iteration   3: 2.901 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (2.833, 2.872, 2.901), stdev = 0.035
  CI (99.9%): [2.239, 3.504] (assumes normal distribution)


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
# Warmup Iteration   1: 4.404 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.083 ±(99.9%) 0.004 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (3.054, 3.067, 3.083), stdev = 0.015
  CI (99.9%): [2.795, 3.338] (assumes normal distribution)


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
# Warmup Iteration   1: 5.735 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
Iteration   2: 3.979 ±(99.9%) 0.020 ms/op
Iteration   3: 4.027 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.995 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.978, 3.995, 4.027), stdev = 0.028
  CI (99.9%): [3.482, 4.507] (assumes normal distribution)


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
# Warmup Iteration   2: 3.192 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  9.220 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.300 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  12.810 ms/op
                 createUser·p0.9999: 20.315 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  12.207 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313012
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20082 
    [ 2.500,  5.000) = 290845 
    [ 5.000,  7.500) = 1418 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     12.402 ms/op
     p(99.9900) =     21.191 ms/op
     p(99.9990) =     22.077 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.306 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.214 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.225 ms/op
                 existUser·p0.9999: 15.792 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.769 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  8.047 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336781
  mean =      2.852 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3381 
    [ 1.250,  2.500) = 53979 
    [ 2.500,  3.750) = 267958 
    [ 3.750,  5.000) = 9795 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 369 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.917 ms/op
     p(99.9900) =     18.601 ms/op
     p(99.9990) =     19.452 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.076 ms/op
                 getUser·p0.9999: 20.731 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.858 ms/op
                 getUser·p0.9999: 21.020 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313289
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20169 
    [ 2.500,  5.000) = 291154 
    [ 5.000,  7.500) = 1392 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.712 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 5.457 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.012 ms/op
Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.679 ms/op
                 listUser·p0.9999: 22.226 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.995 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.050 ms/op
                 listUser·p0.9999: 23.952 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   3: 4.081 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  16.425 ms/op
                 listUser·p0.9999: 21.412 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237258
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2837 
    [ 2.500,  5.000) = 207108 
    [ 5.000,  7.500) = 25137 
    [ 7.500, 10.000) = 1684 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.150 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     25.359 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.423 ± 1.105  ops/ms
ClientGrpc.existUser                       thrpt       3  10.988 ± 5.105  ops/ms
ClientGrpc.getUser                         thrpt       3  10.306 ± 0.800  ops/ms
ClientGrpc.listUser                        thrpt       3   7.919 ± 0.629  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 0.530   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.632   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.271   ms/op
ClientGrpc.listUser                         avgt       3   3.995 ± 0.512   ms/op
ClientGrpc.createUser                     sample  313012   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.300           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.402           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.191           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  336781   2.852 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.306           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.917           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.601           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  313289   3.062 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.729           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.712           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  237258   4.049 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.150           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.461           ms/op
