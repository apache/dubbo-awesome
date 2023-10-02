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
# Warmup Iteration   1: 3.959 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.748 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.287 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (10.196, 10.287, 10.352), stdev = 0.082
  CI (99.9%): [8.795, 11.780] (assumes normal distribution)


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
# Warmup Iteration   1: 7.523 ops/ms
# Warmup Iteration   2: 10.392 ops/ms
# Warmup Iteration   3: 10.581 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.809 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.680 ±(99.9%) 2.168 ops/ms [Average]
  (min, avg, max) = (10.575, 10.680, 10.809), stdev = 0.119
  CI (99.9%): [8.512, 12.847] (assumes normal distribution)


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
# Warmup Iteration   1: 6.737 ops/ms
# Warmup Iteration   2: 9.834 ops/ms
# Warmup Iteration   3: 10.260 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 10.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.269 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (10.194, 10.269, 10.370), stdev = 0.091
  CI (99.9%): [8.603, 11.934] (assumes normal distribution)


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
# Warmup Iteration   1: 6.306 ops/ms
# Warmup Iteration   2: 7.632 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 8.312 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.162 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (8.085, 8.162, 8.312), stdev = 0.130
  CI (99.9%): [5.783, 10.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.157 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.132, 3.157, 3.183), stdev = 0.025
  CI (99.9%): [2.695, 3.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.997 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.997 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.986, 2.997, 3.008), stdev = 0.011
  CI (99.9%): [2.792, 3.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.004 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.102 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.074, 3.102, 3.150), stdev = 0.041
  CI (99.9%): [2.347, 3.858] (assumes normal distribution)


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
# Warmup Iteration   1: 5.454 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.016 ms/op
Iteration   1: 3.907 ±(99.9%) 0.019 ms/op
Iteration   2: 3.909 ±(99.9%) 0.020 ms/op
Iteration   3: 3.948 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.907, 3.921, 3.948), stdev = 0.023
  CI (99.9%): [3.502, 4.340] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.707 ms/op
                 createUser·p0.9999: 23.716 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 18.311 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   3: 3.131 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.229 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306797
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15886 
    [ 2.500,  5.000) = 288986 
    [ 5.000,  7.500) = 1538 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.072 ms/op
     p(99.9900) =     23.767 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.467 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 26.519 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 2.949 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.375 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.824 ms/op
                 existUser·p0.999:  11.536 ms/op
                 existUser·p0.9999: 30.150 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322791
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33344 
    [ 2.500,  5.000) = 287493 
    [ 5.000,  7.500) = 1303 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     27.057 ms/op
     p(99.9990) =     30.663 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.870 ms/op
                 getUser·p0.9999: 15.497 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.576 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 14.797 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.486 ms/op
                 getUser·p0.9999: 16.740 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306782
  mean =      3.129 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 302 
    [ 1.250,  2.500) = 9640 
    [ 2.500,  3.750) = 274593 
    [ 3.750,  5.000) = 20182 
    [ 5.000,  6.250) = 952 
    [ 6.250,  7.500) = 590 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     16.324 ms/op
     p(99.9990) =     18.102 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 5.560 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.010 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 20.182 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 22.408 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243190
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2835 
    [ 2.500,  5.000) = 225461 
    [ 5.000,  7.500) = 13578 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     20.175 ms/op
     p(99.9990) =     24.768 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.287 ± 1.493  ops/ms
ClientGrpc.existUser                       thrpt       3  10.680 ± 2.168  ops/ms
ClientGrpc.getUser                         thrpt       3  10.269 ± 1.666  ops/ms
ClientGrpc.listUser                        thrpt       3   8.162 ± 2.379  ops/ms
ClientGrpc.createUser                       avgt       3   3.157 ± 0.462   ms/op
ClientGrpc.existUser                        avgt       3   2.997 ± 0.205   ms/op
ClientGrpc.getUser                          avgt       3   3.102 ± 0.756   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 0.419   ms/op
ClientGrpc.createUser                     sample  306797   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.072           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.767           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  322791   2.975 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.375           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.057           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.835           ms/op
ClientGrpc.getUser                        sample  306782   3.129 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.324           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.005           ms/op
ClientGrpc.listUser                       sample  243190   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.845           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.175           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
