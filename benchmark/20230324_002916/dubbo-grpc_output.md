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
# Warmup Iteration   1: 2.461 ops/ms
# Warmup Iteration   2: 5.815 ops/ms
# Warmup Iteration   3: 7.262 ops/ms
Iteration   1: 7.383 ops/ms
Iteration   2: 7.471 ops/ms
Iteration   3: 7.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.478 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (7.383, 7.478, 7.578), stdev = 0.098
  CI (99.9%): [5.691, 9.264] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.983 ops/ms
# Warmup Iteration   2: 7.508 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.252 ops/ms
Iteration   2: 8.587 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.331 ±(99.9%) 4.142 ops/ms [Average]
  (min, avg, max) = (8.154, 8.331, 8.587), stdev = 0.227
  CI (99.9%): [4.189, 12.473] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ops/ms
# Warmup Iteration   2: 6.881 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.966 ops/ms
Iteration   2: 7.610 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.901 ±(99.9%) 4.831 ops/ms [Average]
  (min, avg, max) = (7.610, 7.901, 8.127), stdev = 0.265
  CI (99.9%): [3.070, 12.732] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ops/ms
# Warmup Iteration   2: 5.539 ops/ms
# Warmup Iteration   3: 5.900 ops/ms
Iteration   1: 5.736 ops/ms
Iteration   2: 5.659 ops/ms
Iteration   3: 6.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.798 ±(99.9%) 3.276 ops/ms [Average]
  (min, avg, max) = (5.659, 5.798, 6.001), stdev = 0.180
  CI (99.9%): [2.522, 9.074] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.003 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.032 ms/op
Iteration   1: 4.227 ±(99.9%) 0.005 ms/op
Iteration   2: 4.115 ±(99.9%) 0.004 ms/op
Iteration   3: 4.176 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.173 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (4.115, 4.173, 4.227), stdev = 0.056
  CI (99.9%): [3.148, 5.197] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.007 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.965 ±(99.9%) 0.002 ms/op
Iteration   2: 3.855 ±(99.9%) 0.004 ms/op
Iteration   3: 3.818 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.879 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (3.818, 3.879, 3.965), stdev = 0.076
  CI (99.9%): [2.488, 5.270] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.239 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.004 ms/op
Iteration   1: 4.288 ±(99.9%) 0.007 ms/op
Iteration   2: 4.143 ±(99.9%) 0.005 ms/op
Iteration   3: 4.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.186 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (4.128, 4.186, 4.288), stdev = 0.088
  CI (99.9%): [2.574, 5.798] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.807 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.016 ms/op
Iteration   1: 5.344 ±(99.9%) 0.013 ms/op
Iteration   2: 5.211 ±(99.9%) 0.012 ms/op
Iteration   3: 5.430 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.328 ±(99.9%) 2.009 ms/op [Average]
  (min, avg, max) = (5.211, 5.328, 5.430), stdev = 0.110
  CI (99.9%): [3.319, 7.337] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.015 ms/op
Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  13.009 ms/op
                 createUser·p0.9999: 22.529 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  13.894 ms/op
                 createUser·p0.9999: 23.567 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  12.365 ms/op
                 createUser·p0.9999: 25.606 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234623
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4795 
    [ 2.500,  5.000) = 203789 
    [ 5.000,  7.500) = 23667 
    [ 7.500, 10.000) = 1650 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.408 ms/op
     p(99.9900) =     23.401 ms/op
     p(99.9990) =     26.072 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.982 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.012 ms/op
Iteration   1: 3.839 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 3.759 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  13.646 ms/op
                 existUser·p0.9999: 16.792 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 3.985 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.652 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 20.475 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248704
  mean =      3.859 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7577 
    [ 2.500,  5.000) = 221523 
    [ 5.000,  7.500) = 16902 
    [ 7.500, 10.000) = 1815 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     13.243 ms/op
     p(99.9900) =     19.436 ms/op
     p(99.9990) =     21.143 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.014 ms/op
Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  13.178 ms/op
                 getUser·p0.9999: 20.845 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 4.126 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  17.085 ms/op
                 getUser·p0.9999: 21.971 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 4.319 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 18.566 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231242
  mean =      4.149 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8186 
    [ 2.500,  5.000) = 189450 
    [ 5.000,  7.500) = 30540 
    [ 7.500, 10.000) = 2225 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     20.570 ms/op
     p(99.9990) =     22.563 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.372 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.741 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.023 ms/op
Iteration   1: 5.172 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   10.448 ms/op
                 listUser·p0.999:  20.584 ms/op
                 listUser·p0.9999: 23.417 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 5.344 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  24.549 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 5.474 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 26.186 ms/op
                 listUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180305
  mean =      5.327 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 538 
    [ 2.500,  5.000) = 89020 
    [ 5.000,  7.500) = 75867 
    [ 7.500, 10.000) = 11959 
    [10.000, 12.500) = 2065 
    [12.500, 15.000) = 397 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     26.672 ms/op
     p(99.9990) =     27.963 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.478 ± 1.786  ops/ms
ClientGrpc.existUser                       thrpt       3   8.331 ± 4.142  ops/ms
ClientGrpc.getUser                         thrpt       3   7.901 ± 4.831  ops/ms
ClientGrpc.listUser                        thrpt       3   5.798 ± 3.276  ops/ms
ClientGrpc.createUser                       avgt       3   4.173 ± 1.025   ms/op
ClientGrpc.existUser                        avgt       3   3.879 ± 1.391   ms/op
ClientGrpc.getUser                          avgt       3   4.186 ± 1.612   ms/op
ClientGrpc.listUser                         avgt       3   5.328 ± 2.009   ms/op
ClientGrpc.createUser                     sample  234623   4.088 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.904           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.520           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.408           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.401           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.116           ms/op
ClientGrpc.existUser                      sample  248704   3.859 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.668           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.243           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.436           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  231242   4.149 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.894           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.110           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.271           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.570           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.298           ms/op
ClientGrpc.listUser                       sample  180305   5.327 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.513           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.672           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.279           ms/op
