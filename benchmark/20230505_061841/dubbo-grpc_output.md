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
# Warmup Iteration   1: 2.762 ops/ms
# Warmup Iteration   2: 6.478 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.383 ops/ms
Iteration   2: 8.760 ops/ms
Iteration   3: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.612 ±(99.9%) 3.674 ops/ms [Average]
  (min, avg, max) = (8.383, 8.612, 8.760), stdev = 0.201
  CI (99.9%): [4.938, 12.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.963 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.324 ops/ms
Iteration   1: 9.389 ops/ms
Iteration   2: 9.265 ops/ms
Iteration   3: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.290 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (9.216, 9.290, 9.389), stdev = 0.089
  CI (99.9%): [7.669, 10.911] (assumes normal distribution)


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
# Warmup Iteration   1: 5.389 ops/ms
# Warmup Iteration   2: 8.310 ops/ms
# Warmup Iteration   3: 8.779 ops/ms
Iteration   1: 8.948 ops/ms
Iteration   2: 9.050 ops/ms
Iteration   3: 8.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.944 ±(99.9%) 1.969 ops/ms [Average]
  (min, avg, max) = (8.834, 8.944, 9.050), stdev = 0.108
  CI (99.9%): [6.975, 10.913] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ops/ms
# Warmup Iteration   2: 6.131 ops/ms
# Warmup Iteration   3: 6.702 ops/ms
Iteration   1: 6.979 ops/ms
Iteration   2: 6.714 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.805 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (6.714, 6.805, 6.979), stdev = 0.151
  CI (99.9%): [4.058, 9.552] (assumes normal distribution)


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
# Warmup Iteration   1: 5.476 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.005 ms/op
Iteration   1: 3.654 ±(99.9%) 0.004 ms/op
Iteration   2: 3.592 ±(99.9%) 0.005 ms/op
Iteration   3: 3.694 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.647 ±(99.9%) 0.940 ms/op [Average]
  (min, avg, max) = (3.592, 3.647, 3.694), stdev = 0.052
  CI (99.9%): [2.706, 4.587] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.767 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.005 ms/op
Iteration   1: 3.552 ±(99.9%) 0.003 ms/op
Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
Iteration   3: 3.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.523 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.497, 3.523, 3.552), stdev = 0.028
  CI (99.9%): [3.016, 4.029] (assumes normal distribution)


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.004 ms/op
Iteration   1: 3.702 ±(99.9%) 0.004 ms/op
Iteration   2: 3.682 ±(99.9%) 0.004 ms/op
Iteration   3: 3.648 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.678 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.648, 3.678, 3.702), stdev = 0.028
  CI (99.9%): [3.176, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 6.248 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.016 ms/op
Iteration   1: 4.804 ±(99.9%) 0.020 ms/op
Iteration   2: 4.831 ±(99.9%) 0.020 ms/op
Iteration   3: 4.889 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.841 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (4.804, 4.841, 4.889), stdev = 0.043
  CI (99.9%): [4.055, 5.627] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.306 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.010 ms/op
Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  11.459 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   2: 3.563 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 32.572 ms/op
                 createUser·p1.00:   32.866 ms/op

Iteration   3: 3.668 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  10.680 ms/op
                 createUser·p0.9999: 26.322 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265605
  mean =      3.613 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14223 
    [ 2.500,  5.000) = 241566 
    [ 5.000,  7.500) = 8532 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     33.012 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.010 ms/op
Iteration   1: 3.547 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  10.411 ms/op
                 existUser·p0.9999: 15.317 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 3.468 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  10.236 ms/op
                 existUser·p0.9999: 28.861 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  11.303 ms/op
                 existUser·p0.9999: 31.675 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275958
  mean =      3.477 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10184 
    [ 2.500,  5.000) = 257614 
    [ 5.000,  7.500) = 6518 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.442 ms/op
     p(99.9000) =     10.929 ms/op
     p(99.9900) =     31.274 ms/op
     p(99.9990) =     33.767 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 5.428 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.011 ms/op
Iteration   1: 3.756 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  10.313 ms/op
                 getUser·p0.9999: 14.458 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 3.616 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  8.319 ms/op
                 getUser·p0.9999: 19.174 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  13.730 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260710
  mean =      3.683 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7241 
    [ 2.500,  5.000) = 243697 
    [ 5.000,  7.500) = 8713 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     24.665 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 7.372 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.148 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.821 ±(99.9%) 0.016 ms/op
Iteration   1: 4.851 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 21.280 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 4.823 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 25.419 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.957 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  21.888 ms/op
                 listUser·p0.9999: 29.176 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196862
  mean =      4.876 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 249 
    [ 2.500,  5.000) = 141344 
    [ 5.000,  7.500) = 48502 
    [ 7.500, 10.000) = 5470 
    [10.000, 12.500) = 762 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     27.109 ms/op
     p(99.9990) =     29.691 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.612 ± 3.674  ops/ms
ClientGrpc.existUser                       thrpt       3   9.290 ± 1.621  ops/ms
ClientGrpc.getUser                         thrpt       3   8.944 ± 1.969  ops/ms
ClientGrpc.listUser                        thrpt       3   6.805 ± 2.747  ops/ms
ClientGrpc.createUser                       avgt       3   3.647 ± 0.940   ms/op
ClientGrpc.existUser                        avgt       3   3.523 ± 0.506   ms/op
ClientGrpc.getUser                          avgt       3   3.678 ± 0.502   ms/op
ClientGrpc.listUser                         avgt       3   4.841 ± 0.786   ms/op
ClientGrpc.createUser                     sample  265605   3.613 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.502           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.012           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.686           ms/op
ClientGrpc.existUser                      sample  275958   3.477 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.442           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.274           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.817           ms/op
ClientGrpc.getUser                        sample  260710   3.683 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.893           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.665           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.051           ms/op
ClientGrpc.listUser                       sample  196862   4.876 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.632           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.159           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.316           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.109           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.786           ms/op
