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
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.053 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.864 ops/ms
Iteration   2: 8.909 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.969 ±(99.9%) 2.645 ops/ms [Average]
  (min, avg, max) = (8.864, 8.969, 9.134), stdev = 0.145
  CI (99.9%): [6.324, 11.614] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ops/ms
# Warmup Iteration   2: 8.934 ops/ms
# Warmup Iteration   3: 9.227 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.922 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (9.793, 9.922, 10.023), stdev = 0.117
  CI (99.9%): [7.782, 12.062] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.580 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 8.684 ops/ms
Iteration   2: 8.947 ops/ms
Iteration   3: 8.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.824 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (8.684, 8.824, 8.947), stdev = 0.132
  CI (99.9%): [6.412, 11.235] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 6.274 ops/ms
# Warmup Iteration   3: 6.619 ops/ms
Iteration   1: 6.827 ops/ms
Iteration   2: 6.835 ops/ms
Iteration   3: 6.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.808 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (6.761, 6.808, 6.835), stdev = 0.041
  CI (99.9%): [6.064, 7.552] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.003 ms/op
Iteration   1: 3.661 ±(99.9%) 0.005 ms/op
Iteration   2: 3.650 ±(99.9%) 0.002 ms/op
Iteration   3: 3.535 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.615 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.535, 3.615, 3.661), stdev = 0.070
  CI (99.9%): [2.347, 4.883] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.007 ms/op
Iteration   1: 3.270 ±(99.9%) 0.003 ms/op
Iteration   2: 3.342 ±(99.9%) 0.002 ms/op
Iteration   3: 3.243 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.285 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (3.243, 3.285, 3.342), stdev = 0.051
  CI (99.9%): [2.351, 4.220] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.004 ms/op
Iteration   1: 3.560 ±(99.9%) 0.003 ms/op
Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
Iteration   3: 3.584 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.580 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.560, 3.580, 3.597), stdev = 0.019
  CI (99.9%): [3.232, 3.928] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.799 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.682 ±(99.9%) 0.021 ms/op
Iteration   1: 4.677 ±(99.9%) 0.016 ms/op
Iteration   2: 4.599 ±(99.9%) 0.010 ms/op
Iteration   3: 4.778 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.685 ±(99.9%) 1.631 ms/op [Average]
  (min, avg, max) = (4.599, 4.685, 4.778), stdev = 0.089
  CI (99.9%): [3.053, 6.316] (assumes normal distribution)


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
# Warmup Iteration   1: 5.475 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.012 ms/op
Iteration   1: 3.577 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.965 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 28.739 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 3.563 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  11.059 ms/op
                 createUser·p0.9999: 25.593 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.567 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  8.838 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268831
  mean =      3.569 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6240 
    [ 2.500,  5.000) = 254301 
    [ 5.000,  7.500) = 7245 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     10.292 ms/op
     p(99.9900) =     26.677 ms/op
     p(99.9990) =     28.879 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.336 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  8.374 ms/op
                 existUser·p0.9999: 18.776 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.385 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.368 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 22.692 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287372
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14287 
    [ 2.500,  5.000) = 267179 
    [ 5.000,  7.500) = 5032 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.359 ms/op
     p(99.9900) =     23.151 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.419 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
Iteration   1: 3.663 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.413 ms/op
                 getUser·p0.9999: 16.119 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.553 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  8.086 ms/op
                 getUser·p0.9999: 18.383 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 19.855 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267520
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17148 
    [ 2.500,  5.000) = 238944 
    [ 5.000,  7.500) = 10427 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     10.182 ms/op
     p(99.9900) =     19.046 ms/op
     p(99.9990) =     20.315 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 6.575 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.139 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.018 ms/op
Iteration   1: 4.751 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.684 ms/op
                 listUser·p0.9999: 22.648 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 4.608 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.830 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.733 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.837 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  21.791 ms/op
                 listUser·p0.9999: 29.303 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203030
  mean =      4.730 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1131 
    [ 2.500,  5.000) = 143298 
    [ 5.000,  7.500) = 51076 
    [ 7.500, 10.000) = 6479 
    [10.000, 12.500) = 564 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     17.593 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.914 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.969 ± 2.645  ops/ms
ClientGrpc.existUser                       thrpt       3   9.922 ± 2.140  ops/ms
ClientGrpc.getUser                         thrpt       3   8.824 ± 2.412  ops/ms
ClientGrpc.listUser                        thrpt       3   6.808 ± 0.744  ops/ms
ClientGrpc.createUser                       avgt       3   3.615 ± 1.268   ms/op
ClientGrpc.existUser                        avgt       3   3.285 ± 0.934   ms/op
ClientGrpc.getUser                          avgt       3   3.580 ± 0.348   ms/op
ClientGrpc.listUser                         avgt       3   4.685 ± 1.631   ms/op
ClientGrpc.createUser                     sample  268831   3.569 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.705           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.988           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.292           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.677           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.032           ms/op
ClientGrpc.existUser                      sample  287372   3.340 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.675           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.693           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.359           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.805           ms/op
ClientGrpc.getUser                        sample  267520   3.587 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.182           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.046           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  203030   4.730 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.294           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.593           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.246           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.048           ms/op
