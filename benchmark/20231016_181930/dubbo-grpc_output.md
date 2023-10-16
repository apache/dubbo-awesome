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
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 4.270 ops/ms
# Warmup Iteration   3: 5.857 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 6.088 ops/ms
Iteration   3: 6.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.041 ±(99.9%) 8.372 ops/ms [Average]
  (min, avg, max) = (5.560, 6.041, 6.474), stdev = 0.459
  CI (99.9%): [≈ 0, 14.412] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ops/ms
# Warmup Iteration   2: 6.230 ops/ms
# Warmup Iteration   3: 6.678 ops/ms
Iteration   1: 6.966 ops/ms
Iteration   2: 7.043 ops/ms
Iteration   3: 6.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.997 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (6.966, 6.997, 7.043), stdev = 0.040
  CI (99.9%): [6.259, 7.735] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 5.724 ops/ms
# Warmup Iteration   3: 6.121 ops/ms
Iteration   1: 6.297 ops/ms
Iteration   2: 6.569 ops/ms
Iteration   3: 6.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.499 ±(99.9%) 3.231 ops/ms [Average]
  (min, avg, max) = (6.297, 6.499, 6.629), stdev = 0.177
  CI (99.9%): [3.268, 9.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 4.671 ops/ms
# Warmup Iteration   3: 4.775 ops/ms
Iteration   1: 4.971 ops/ms
Iteration   2: 5.143 ops/ms
Iteration   3: 4.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.015 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (4.931, 5.015, 5.143), stdev = 0.113
  CI (99.9%): [2.954, 7.075] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.495 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.140 ±(99.9%) 0.015 ms/op
Iteration   1: 4.933 ±(99.9%) 0.008 ms/op
Iteration   2: 4.871 ±(99.9%) 0.004 ms/op
Iteration   3: 4.943 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.915 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (4.871, 4.915, 4.943), stdev = 0.039
  CI (99.9%): [4.202, 5.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.703 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.748 ±(99.9%) 0.004 ms/op
Iteration   1: 4.675 ±(99.9%) 0.005 ms/op
Iteration   2: 4.656 ±(99.9%) 0.003 ms/op
Iteration   3: 4.476 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.602 ±(99.9%) 2.002 ms/op [Average]
  (min, avg, max) = (4.476, 4.602, 4.675), stdev = 0.110
  CI (99.9%): [2.601, 6.604] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.610 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.199 ±(99.9%) 0.008 ms/op
Iteration   1: 4.729 ±(99.9%) 0.004 ms/op
Iteration   2: 4.879 ±(99.9%) 0.005 ms/op
Iteration   3: 4.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.813 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (4.729, 4.813, 4.879), stdev = 0.076
  CI (99.9%): [3.418, 6.208] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.567 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 7.111 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.141 ±(99.9%) 0.025 ms/op
Iteration   1: 6.067 ±(99.9%) 0.011 ms/op
Iteration   2: 6.222 ±(99.9%) 0.017 ms/op
Iteration   3: 6.056 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.115 ±(99.9%) 1.694 ms/op [Average]
  (min, avg, max) = (6.056, 6.115, 6.222), stdev = 0.093
  CI (99.9%): [4.422, 7.809] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.839 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.549 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.017 ms/op
Iteration   1: 4.907 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.767 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 27.819 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 5.027 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   6.849 ms/op
                 createUser·p0.99:   9.535 ms/op
                 createUser·p0.999:  14.356 ms/op
                 createUser·p0.9999: 25.645 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 4.843 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  24.905 ms/op
                 createUser·p0.9999: 28.784 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 194775
  mean =      4.925 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1434 
    [ 2.500,  5.000) = 118925 
    [ 5.000,  7.500) = 68974 
    [ 7.500, 10.000) = 4008 
    [10.000, 12.500) = 984 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     16.087 ms/op
     p(99.9900) =     28.067 ms/op
     p(99.9990) =     28.874 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.053 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.015 ms/op
Iteration   1: 4.747 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   4.571 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  12.413 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 4.573 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.439 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  12.515 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 4.707 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.603 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 19.897 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 205330
  mean =      4.675 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3409 
    [ 2.500,  5.000) = 140253 
    [ 5.000,  7.500) = 57003 
    [ 7.500, 10.000) = 3843 
    [10.000, 12.500) = 571 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     23.589 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.028 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.384 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.951 ±(99.9%) 0.017 ms/op
Iteration   1: 4.816 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   6.660 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  12.739 ms/op
                 getUser·p0.9999: 17.186 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   2: 4.907 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.743 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  11.772 ms/op
                 getUser·p0.9999: 25.376 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 4.831 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 18.703 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 197886
  mean =      4.851 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1946 
    [ 2.500,  5.000) = 125040 
    [ 5.000,  7.500) = 66388 
    [ 7.500, 10.000) = 3741 
    [10.000, 12.500) = 624 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     22.926 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.520 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.066 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.191 ±(99.9%) 0.025 ms/op
Iteration   1: 6.130 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   11.459 ms/op
                 listUser·p0.999:  17.833 ms/op
                 listUser·p0.9999: 20.304 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 6.494 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   8.864 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.815 ms/op
                 listUser·p0.999:  21.731 ms/op
                 listUser·p0.9999: 34.144 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   3: 6.399 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  22.905 ms/op
                 listUser·p0.9999: 24.970 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 151528
  mean =      6.337 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 27541 
    [ 5.000,  7.500) = 95796 
    [ 7.500, 10.000) = 22093 
    [10.000, 12.500) = 4491 
    [12.500, 15.000) = 913 
    [15.000, 17.500) = 314 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      8.552 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     20.430 ms/op
     p(99.9900) =     32.645 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.041 ± 8.372  ops/ms
ClientGrpc.existUser                       thrpt       3   6.997 ± 0.738  ops/ms
ClientGrpc.getUser                         thrpt       3   6.499 ± 3.231  ops/ms
ClientGrpc.listUser                        thrpt       3   5.015 ± 2.060  ops/ms
ClientGrpc.createUser                       avgt       3   4.915 ± 0.714   ms/op
ClientGrpc.existUser                        avgt       3   4.602 ± 2.002   ms/op
ClientGrpc.getUser                          avgt       3   4.813 ± 1.395   ms/op
ClientGrpc.listUser                         avgt       3   6.115 ± 1.694   ms/op
ClientGrpc.createUser                     sample  194775   4.925 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.155           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.824           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.087           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.067           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.967           ms/op
ClientGrpc.existUser                      sample  205330   4.675 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.439           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.898           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.749           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.287           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.218           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  197886   4.851 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.077           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.054           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.619           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.926           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  151528   6.337 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.452           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.634           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.534           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.430           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.645           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.275           ms/op
