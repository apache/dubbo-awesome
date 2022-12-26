# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.462 ops/ms
# Warmup Iteration   2: 7.220 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.778 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.612 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (8.494, 8.612, 8.778), stdev = 0.148
  CI (99.9%): [5.915, 11.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.013 ops/ms
# Warmup Iteration   2: 8.337 ops/ms
# Warmup Iteration   3: 9.066 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.271 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.156 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (9.036, 9.156, 9.271), stdev = 0.117
  CI (99.9%): [7.015, 11.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.655 ops/ms
# Warmup Iteration   2: 8.271 ops/ms
# Warmup Iteration   3: 8.713 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.629 ±(99.9%) 4.340 ops/ms [Average]
  (min, avg, max) = (8.416, 8.629, 8.886), stdev = 0.238
  CI (99.9%): [4.289, 12.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 6.323 ops/ms
Iteration   1: 6.947 ops/ms
Iteration   2: 6.502 ops/ms
Iteration   3: 6.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.674 ±(99.9%) 4.363 ops/ms [Average]
  (min, avg, max) = (6.502, 6.674, 6.947), stdev = 0.239
  CI (99.9%): [2.311, 11.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.047 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.015 ms/op
Iteration   1: 3.751 ±(99.9%) 0.003 ms/op
Iteration   2: 3.853 ±(99.9%) 0.003 ms/op
Iteration   3: 3.701 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.768 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (3.701, 3.768, 3.853), stdev = 0.078
  CI (99.9%): [2.354, 5.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.003 ms/op
Iteration   1: 3.468 ±(99.9%) 0.004 ms/op
Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
Iteration   3: 3.629 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.530 ±(99.9%) 1.570 ms/op [Average]
  (min, avg, max) = (3.468, 3.530, 3.629), stdev = 0.086
  CI (99.9%): [1.960, 5.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.015 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.005 ms/op
Iteration   1: 3.656 ±(99.9%) 0.002 ms/op
Iteration   2: 3.646 ±(99.9%) 0.004 ms/op
Iteration   3: 3.662 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.655 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.646, 3.655, 3.662), stdev = 0.008
  CI (99.9%): [3.508, 3.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.350 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.976 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.010 ms/op
Iteration   1: 4.612 ±(99.9%) 0.010 ms/op
Iteration   2: 4.728 ±(99.9%) 0.030 ms/op
Iteration   3: 4.401 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.580 ±(99.9%) 3.027 ms/op [Average]
  (min, avg, max) = (4.401, 4.580, 4.728), stdev = 0.166
  CI (99.9%): [1.554, 7.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.011 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 19.969 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.865 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  14.799 ms/op
                 createUser·p0.9999: 25.148 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.832 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.221 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 19.408 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249245
  mean =      3.851 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10814 
    [ 2.500,  5.000) = 222043 
    [ 5.000,  7.500) = 15222 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     10.596 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     25.412 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.009 ms/op
Iteration   1: 3.532 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  9.035 ms/op
                 existUser·p0.9999: 15.398 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   2: 3.572 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 16.778 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  12.230 ms/op
                 existUser·p0.9999: 26.774 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270004
  mean =      3.560 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13877 
    [ 2.500,  5.000) = 248678 
    [ 5.000,  7.500) = 6524 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.551 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.141 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.009 ms/op
Iteration   1: 3.607 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.038 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 3.588 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.721 ms/op
                 getUser·p0.999:  9.735 ms/op
                 getUser·p0.9999: 21.894 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.640 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 25.107 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265846
  mean =      3.611 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11607 
    [ 2.500,  5.000) = 246659 
    [ 5.000,  7.500) = 6517 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =      9.554 ms/op
     p(99.9900) =     24.262 ms/op
     p(99.9990) =     26.095 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.037 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.017 ms/op
Iteration   1: 4.790 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   8.413 ms/op
                 listUser·p0.999:  14.537 ms/op
                 listUser·p0.9999: 20.927 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 4.701 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  16.039 ms/op
                 listUser·p0.9999: 23.580 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.683 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 24.364 ms/op
                 listUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203152
  mean =      4.724 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 718 
    [ 2.500,  5.000) = 151015 
    [ 5.000,  7.500) = 46350 
    [ 7.500, 10.000) = 4332 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     23.812 ms/op
     p(99.9990) =     27.327 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.612 ± 2.697  ops/ms
ClientGrpc.existUser                       thrpt       3   9.156 ± 2.141  ops/ms
ClientGrpc.getUser                         thrpt       3   8.629 ± 4.340  ops/ms
ClientGrpc.listUser                        thrpt       3   6.674 ± 4.363  ops/ms
ClientGrpc.createUser                       avgt       3   3.768 ± 1.414   ms/op
ClientGrpc.existUser                        avgt       3   3.530 ± 1.570   ms/op
ClientGrpc.getUser                          avgt       3   3.655 ± 0.147   ms/op
ClientGrpc.listUser                         avgt       3   4.580 ± 3.027   ms/op
ClientGrpc.createUser                     sample  249245   3.851 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.807           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.316           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.596           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.559           ms/op
ClientGrpc.existUser                      sample  270004   3.560 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.659           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.378           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.934           ms/op
ClientGrpc.getUser                        sample  265846   3.611 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.495           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.554           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  203152   4.724 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.048           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.334           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.812           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
