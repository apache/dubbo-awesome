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
# Warmup Iteration   1: 2.525 ops/ms
# Warmup Iteration   2: 5.948 ops/ms
# Warmup Iteration   3: 7.535 ops/ms
Iteration   1: 8.551 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.295 ±(99.9%) 4.610 ops/ms [Average]
  (min, avg, max) = (8.045, 8.295, 8.551), stdev = 0.253
  CI (99.9%): [3.686, 12.905] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ops/ms
# Warmup Iteration   2: 8.051 ops/ms
# Warmup Iteration   3: 8.719 ops/ms
Iteration   1: 8.793 ops/ms
Iteration   2: 8.960 ops/ms
Iteration   3: 9.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.923 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (8.793, 8.923, 9.016), stdev = 0.116
  CI (99.9%): [6.810, 11.037] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.438 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.373 ±(99.9%) 4.119 ops/ms [Average]
  (min, avg, max) = (8.122, 8.373, 8.559), stdev = 0.226
  CI (99.9%): [4.255, 12.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ops/ms
# Warmup Iteration   2: 5.937 ops/ms
# Warmup Iteration   3: 6.075 ops/ms
Iteration   1: 6.232 ops/ms
Iteration   2: 6.406 ops/ms
Iteration   3: 6.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.330 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (6.232, 6.330, 6.406), stdev = 0.089
  CI (99.9%): [4.701, 7.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.005 ms/op
Iteration   1: 4.025 ±(99.9%) 0.003 ms/op
Iteration   2: 4.021 ±(99.9%) 0.004 ms/op
Iteration   3: 4.113 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.053 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (4.021, 4.053, 4.113), stdev = 0.052
  CI (99.9%): [3.106, 5.001] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.054 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.003 ms/op
Iteration   1: 3.649 ±(99.9%) 0.005 ms/op
Iteration   2: 3.709 ±(99.9%) 0.005 ms/op
Iteration   3: 3.710 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.689 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.649, 3.689, 3.710), stdev = 0.035
  CI (99.9%): [3.044, 4.334] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.930 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.008 ms/op
Iteration   1: 3.987 ±(99.9%) 0.005 ms/op
Iteration   2: 4.101 ±(99.9%) 0.004 ms/op
Iteration   3: 4.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.037 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (3.987, 4.037, 4.101), stdev = 0.059
  CI (99.9%): [2.966, 5.107] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.887 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.352 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.017 ±(99.9%) 0.014 ms/op
Iteration   1: 5.214 ±(99.9%) 0.012 ms/op
Iteration   2: 5.027 ±(99.9%) 0.011 ms/op
Iteration   3: 5.108 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.116 ±(99.9%) 1.717 ms/op [Average]
  (min, avg, max) = (5.027, 5.116, 5.214), stdev = 0.094
  CI (99.9%): [3.399, 6.833] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.992 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.013 ms/op
Iteration   1: 4.014 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  10.213 ms/op
                 createUser·p0.9999: 15.827 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  11.306 ms/op
                 createUser·p0.9999: 17.610 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.976 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  10.299 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 243031
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7173 
    [ 2.500,  5.000) = 214519 
    [ 5.000,  7.500) = 19794 
    [ 7.500, 10.000) = 1235 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     10.550 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     19.960 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.578 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  12.508 ms/op
                 existUser·p0.9999: 14.289 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 3.545 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  11.568 ms/op
                 existUser·p0.9999: 18.348 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.641 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  13.600 ms/op
                 existUser·p0.9999: 16.751 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267810
  mean =      3.588 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 891 
    [ 1.250,  2.500) = 16986 
    [ 2.500,  3.750) = 159319 
    [ 3.750,  5.000) = 79637 
    [ 5.000,  6.250) = 6822 
    [ 6.250,  7.500) = 1846 
    [ 7.500,  8.750) = 1106 
    [ 8.750, 10.000) = 501 
    [10.000, 11.250) = 250 
    [11.250, 12.500) = 165 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     12.684 ms/op
     p(99.9900) =     17.552 ms/op
     p(99.9990) =     18.787 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.601 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.012 ms/op
Iteration   1: 3.745 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  13.409 ms/op
                 getUser·p0.9999: 30.817 ms/op
                 getUser·p1.00:   33.096 ms/op

Iteration   2: 3.831 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  10.462 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 3.797 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  13.072 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253174
  mean =      3.791 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15785 
    [ 2.500,  5.000) = 222018 
    [ 5.000,  7.500) = 13094 
    [ 7.500, 10.000) = 1604 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     32.469 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 7.287 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.192 ±(99.9%) 0.020 ms/op
Iteration   1: 5.088 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  15.403 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 5.087 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 24.656 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   3: 4.924 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  26.776 ms/op
                 listUser·p0.9999: 29.180 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190674
  mean =      5.032 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 501 
    [ 2.500,  5.000) = 116812 
    [ 5.000,  7.500) = 62118 
    [ 7.500, 10.000) = 9432 
    [10.000, 12.500) = 1148 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     28.733 ms/op
     p(99.9990) =     30.365 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.295 ± 4.610  ops/ms
ClientGrpc.existUser                       thrpt       3   8.923 ± 2.113  ops/ms
ClientGrpc.getUser                         thrpt       3   8.373 ± 4.119  ops/ms
ClientGrpc.listUser                        thrpt       3   6.330 ± 1.630  ops/ms
ClientGrpc.createUser                       avgt       3   4.053 ± 0.948   ms/op
ClientGrpc.existUser                        avgt       3   3.689 ± 0.645   ms/op
ClientGrpc.getUser                          avgt       3   4.037 ± 1.070   ms/op
ClientGrpc.listUser                         avgt       3   5.116 ± 1.717   ms/op
ClientGrpc.createUser                     sample  243031   3.946 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.783           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.498           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  267810   3.588 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.201           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.552           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  253174   3.791 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.120           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.258           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.474           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.096           ms/op
ClientGrpc.listUser                       sample  190674   5.032 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.294           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.465           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.733           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.900           ms/op
