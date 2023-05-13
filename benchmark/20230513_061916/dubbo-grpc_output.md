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
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 5.838 ops/ms
# Warmup Iteration   3: 7.000 ops/ms
Iteration   1: 7.265 ops/ms
Iteration   2: 7.685 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.585 ±(99.9%) 5.157 ops/ms [Average]
  (min, avg, max) = (7.265, 7.585, 7.804), stdev = 0.283
  CI (99.9%): [2.428, 12.742] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ops/ms
# Warmup Iteration   2: 7.259 ops/ms
# Warmup Iteration   3: 7.959 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.596 ops/ms
Iteration   3: 8.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.545 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (8.406, 8.545, 8.634), stdev = 0.122
  CI (99.9%): [6.311, 10.779] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.425 ops/ms
# Warmup Iteration   2: 7.418 ops/ms
# Warmup Iteration   3: 7.616 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.985 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (7.866, 7.985, 8.130), stdev = 0.134
  CI (99.9%): [5.536, 10.433] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ops/ms
# Warmup Iteration   2: 5.443 ops/ms
# Warmup Iteration   3: 6.047 ops/ms
Iteration   1: 5.996 ops/ms
Iteration   2: 6.117 ops/ms
Iteration   3: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.091 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (5.996, 6.091, 6.161), stdev = 0.086
  CI (99.9%): [4.530, 7.652] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.674 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.010 ms/op
Iteration   1: 4.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.926 ±(99.9%) 0.002 ms/op
Iteration   3: 3.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.986 ±(99.9%) 1.567 ms/op [Average]
  (min, avg, max) = (3.926, 3.986, 4.084), stdev = 0.086
  CI (99.9%): [2.419, 5.553] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.476 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.005 ms/op
Iteration   1: 3.756 ±(99.9%) 0.002 ms/op
Iteration   2: 3.573 ±(99.9%) 0.005 ms/op
Iteration   3: 3.742 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.690 ±(99.9%) 1.858 ms/op [Average]
  (min, avg, max) = (3.573, 3.690, 3.756), stdev = 0.102
  CI (99.9%): [1.832, 5.549] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.968 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.003 ms/op
Iteration   1: 4.140 ±(99.9%) 0.008 ms/op
Iteration   2: 4.188 ±(99.9%) 0.004 ms/op
Iteration   3: 4.312 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.213 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (4.140, 4.213, 4.312), stdev = 0.089
  CI (99.9%): [2.590, 5.837] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.606 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.012 ms/op
Iteration   1: 5.253 ±(99.9%) 0.013 ms/op
Iteration   2: 5.086 ±(99.9%) 0.012 ms/op
Iteration   3: 5.068 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.136 ±(99.9%) 1.857 ms/op [Average]
  (min, avg, max) = (5.068, 5.136, 5.253), stdev = 0.102
  CI (99.9%): [3.279, 6.992] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.022 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.015 ms/op
Iteration   1: 4.222 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  13.390 ms/op
                 createUser·p0.9999: 21.654 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.976 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  12.600 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  11.244 ms/op
                 createUser·p0.9999: 25.022 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 238148
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5197 
    [ 2.500,  5.000) = 204673 
    [ 5.000,  7.500) = 25771 
    [ 7.500, 10.000) = 1898 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     13.023 ms/op
     p(99.9900) =     25.604 ms/op
     p(99.9990) =     26.464 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 5.310 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
Iteration   1: 3.821 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.446 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 16.272 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.858 ms/op
                 existUser·p0.999:  11.555 ms/op
                 existUser·p0.9999: 20.066 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 3.922 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  17.131 ms/op
                 existUser·p0.9999: 21.622 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243481
  mean =      3.941 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8390 
    [ 2.500,  5.000) = 209427 
    [ 5.000,  7.500) = 22936 
    [ 7.500, 10.000) = 1977 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     13.525 ms/op
     p(99.9900) =     21.058 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 6.343 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.014 ms/op
Iteration   1: 4.290 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.279 ms/op
                 getUser·p0.999:  12.315 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 4.092 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  11.417 ms/op
                 getUser·p0.9999: 24.817 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 4.023 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  12.351 ms/op
                 getUser·p0.9999: 23.925 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 232421
  mean =      4.132 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7329 
    [ 2.500,  5.000) = 191323 
    [ 5.000,  7.500) = 31050 
    [ 7.500, 10.000) = 2159 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     26.926 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.090 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.550 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.292 ±(99.9%) 0.020 ms/op
Iteration   1: 5.416 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  15.613 ms/op
                 listUser·p0.9999: 24.880 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 5.522 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  18.838 ms/op
                 listUser·p0.9999: 26.221 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 5.473 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.289 ms/op
                 listUser·p0.999:  27.176 ms/op
                 listUser·p0.9999: 48.234 ms/op
                 listUser·p1.00:   55.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175501
  mean =      5.470 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81949 
    [ 5.000, 10.000) = 90199 
    [10.000, 15.000) = 2935 
    [15.000, 20.000) = 226 
    [20.000, 25.000) = 75 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 30 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     47.972 ms/op
     p(99.9990) =     54.221 ms/op
     p(99.9999) =     55.706 ms/op
    p(100.0000) =     55.706 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.585 ± 5.157  ops/ms
ClientGrpc.existUser                       thrpt       3   8.545 ± 2.234  ops/ms
ClientGrpc.getUser                         thrpt       3   7.985 ± 2.448  ops/ms
ClientGrpc.listUser                        thrpt       3   6.091 ± 1.561  ops/ms
ClientGrpc.createUser                       avgt       3   3.986 ± 1.567   ms/op
ClientGrpc.existUser                        avgt       3   3.690 ± 1.858   ms/op
ClientGrpc.getUser                          avgt       3   4.213 ± 1.623   ms/op
ClientGrpc.listUser                         avgt       3   5.136 ± 1.857   ms/op
ClientGrpc.createUser                     sample  238148   4.030 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.023           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.604           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.509           ms/op
ClientGrpc.existUser                      sample  243481   3.941 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.391           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.525           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.058           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.372           ms/op
ClientGrpc.getUser                        sample  232421   4.132 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.841           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.300           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.009           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.278           ms/op
ClientGrpc.listUser                       sample  175501   5.470 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.452           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.125           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.184           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          47.972           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          55.706           ms/op
