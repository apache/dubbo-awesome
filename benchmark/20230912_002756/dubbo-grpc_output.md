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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 9.210 ops/ms
Iteration   2: 9.490 ops/ms
Iteration   3: 9.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.380 ±(99.9%) 2.725 ops/ms [Average]
  (min, avg, max) = (9.210, 9.380, 9.490), stdev = 0.149
  CI (99.9%): [6.656, 12.105] (assumes normal distribution)


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
# Warmup Iteration   1: 6.270 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 9.666 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 9.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.748 ±(99.9%) 3.813 ops/ms [Average]
  (min, avg, max) = (9.593, 9.748, 9.986), stdev = 0.209
  CI (99.9%): [5.936, 13.561] (assumes normal distribution)


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
# Warmup Iteration   1: 6.119 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.438 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.387 ±(99.9%) 1.046 ops/ms [Average]
  (min, avg, max) = (9.325, 9.387, 9.438), stdev = 0.057
  CI (99.9%): [8.341, 10.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 6.667 ops/ms
# Warmup Iteration   3: 7.100 ops/ms
Iteration   1: 7.164 ops/ms
Iteration   2: 7.230 ops/ms
Iteration   3: 7.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.158 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (7.080, 7.158, 7.230), stdev = 0.076
  CI (99.9%): [5.779, 8.537] (assumes normal distribution)


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
# Warmup Iteration   1: 4.891 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.379 ±(99.9%) 0.003 ms/op
Iteration   2: 3.377 ±(99.9%) 0.002 ms/op
Iteration   3: 3.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.418 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.377, 3.418, 3.498), stdev = 0.069
  CI (99.9%): [2.153, 4.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.556 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.002 ms/op
Iteration   2: 3.192 ±(99.9%) 0.002 ms/op
Iteration   3: 3.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.190 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (3.187, 3.190, 3.192), stdev = 0.003
  CI (99.9%): [3.141, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.003 ms/op
Iteration   1: 3.424 ±(99.9%) 0.003 ms/op
Iteration   2: 3.347 ±(99.9%) 0.003 ms/op
Iteration   3: 3.339 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.370 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.339, 3.370, 3.424), stdev = 0.047
  CI (99.9%): [2.515, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.433 ±(99.9%) 0.020 ms/op
Iteration   1: 4.584 ±(99.9%) 0.019 ms/op
Iteration   2: 4.623 ±(99.9%) 0.025 ms/op
Iteration   3: 4.693 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.633 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (4.584, 4.633, 4.693), stdev = 0.055
  CI (99.9%): [3.622, 5.645] (assumes normal distribution)


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
# Warmup Iteration   1: 5.020 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.464 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 21.007 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.502 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  11.481 ms/op
                 createUser·p0.9999: 21.845 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 277181
  mean =      3.463 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10632 
    [ 2.500,  5.000) = 258811 
    [ 5.000,  7.500) = 6623 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     21.440 ms/op
     p(99.9990) =     23.164 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  11.903 ms/op
                 existUser·p0.9999: 17.578 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  11.666 ms/op
                 existUser·p0.9999: 18.728 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287059
  mean =      3.344 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16258 
    [ 2.500,  5.000) = 264637 
    [ 5.000,  7.500) = 4944 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     20.293 ms/op
     p(99.9990) =     21.898 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.561 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.009 ms/op
Iteration   1: 3.530 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 18.444 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 3.444 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  9.779 ms/op
                 getUser·p0.9999: 20.155 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 3.510 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 17.560 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 274785
  mean =      3.494 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11138 
    [ 2.500,  5.000) = 254858 
    [ 5.000,  7.500) = 7778 
    [ 7.500, 10.000) = 756 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     18.236 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 6.219 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.017 ms/op
Iteration   1: 4.598 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  14.318 ms/op
                 listUser·p0.9999: 15.534 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.487 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.828 ms/op
                 listUser·p0.999:  16.598 ms/op
                 listUser·p0.9999: 28.860 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   3: 4.420 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.433 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  17.151 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213269
  mean =      4.501 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1929 
    [ 2.500,  5.000) = 161322 
    [ 5.000,  7.500) = 44164 
    [ 7.500, 10.000) = 4722 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     28.006 ms/op
     p(99.9990) =     29.089 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.380 ± 2.725  ops/ms
ClientGrpc.existUser                       thrpt       3   9.748 ± 3.813  ops/ms
ClientGrpc.getUser                         thrpt       3   9.387 ± 1.046  ops/ms
ClientGrpc.listUser                        thrpt       3   7.158 ± 1.379  ops/ms
ClientGrpc.createUser                       avgt       3   3.418 ± 1.265   ms/op
ClientGrpc.existUser                        avgt       3   3.190 ± 0.049   ms/op
ClientGrpc.getUser                          avgt       3   3.370 ± 0.856   ms/op
ClientGrpc.listUser                         avgt       3   4.633 ± 1.011   ms/op
ClientGrpc.createUser                     sample  277181   3.463 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.638           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.367           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.223           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.440           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  287059   3.344 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.293           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  274785   3.494 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.852           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.601           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.236           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  213269   4.501 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.433           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.219           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.006           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.768           ms/op
