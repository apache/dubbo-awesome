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
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 5.796 ops/ms
# Warmup Iteration   3: 7.159 ops/ms
Iteration   1: 7.552 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.736 ±(99.9%) 3.137 ops/ms [Average]
  (min, avg, max) = (7.552, 7.736, 7.893), stdev = 0.172
  CI (99.9%): [4.599, 10.874] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.462 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 8.032 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.351 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (8.295, 8.351, 8.459), stdev = 0.093
  CI (99.9%): [6.648, 10.054] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.595 ops/ms
Iteration   1: 8.069 ops/ms
Iteration   2: 7.811 ops/ms
Iteration   3: 7.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.854 ±(99.9%) 3.591 ops/ms [Average]
  (min, avg, max) = (7.683, 7.854, 8.069), stdev = 0.197
  CI (99.9%): [4.264, 11.445] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.660 ops/ms
# Warmup Iteration   2: 5.471 ops/ms
# Warmup Iteration   3: 5.892 ops/ms
Iteration   1: 6.171 ops/ms
Iteration   2: 6.036 ops/ms
Iteration   3: 6.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.097 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (6.036, 6.097, 6.171), stdev = 0.068
  CI (99.9%): [4.851, 7.344] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.013 ms/op
Iteration   1: 4.107 ±(99.9%) 0.004 ms/op
Iteration   2: 4.048 ±(99.9%) 0.002 ms/op
Iteration   3: 3.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.032 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (3.942, 4.032, 4.107), stdev = 0.084
  CI (99.9%): [2.508, 5.556] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.558 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.003 ms/op
Iteration   1: 3.818 ±(99.9%) 0.003 ms/op
Iteration   2: 3.686 ±(99.9%) 0.003 ms/op
Iteration   3: 3.784 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.763 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (3.686, 3.763, 3.818), stdev = 0.068
  CI (99.9%): [2.516, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 6.415 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.003 ms/op
Iteration   1: 4.093 ±(99.9%) 0.003 ms/op
Iteration   2: 4.176 ±(99.9%) 0.002 ms/op
Iteration   3: 4.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.109 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (4.057, 4.109, 4.176), stdev = 0.061
  CI (99.9%): [2.995, 5.223] (assumes normal distribution)


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
# Warmup Iteration   1: 8.041 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.723 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.023 ms/op
Iteration   1: 5.213 ±(99.9%) 0.016 ms/op
Iteration   2: 5.404 ±(99.9%) 0.023 ms/op
Iteration   3: 5.400 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.339 ±(99.9%) 1.989 ms/op [Average]
  (min, avg, max) = (5.213, 5.339, 5.404), stdev = 0.109
  CI (99.9%): [3.350, 7.328] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  11.630 ms/op
                 createUser·p0.9999: 21.377 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 4.108 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  12.015 ms/op
                 createUser·p0.9999: 22.158 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  11.648 ms/op
                 createUser·p0.9999: 22.297 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235075
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4981 
    [ 2.500,  5.000) = 203994 
    [ 5.000,  7.500) = 24627 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     24.017 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 5.474 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.011 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  10.612 ms/op
                 existUser·p0.9999: 16.991 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 3.935 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.321 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 18.516 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 3.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.637 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 25.104 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248972
  mean =      3.854 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5458 
    [ 2.500,  5.000) = 228298 
    [ 5.000,  7.500) = 13940 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     10.569 ms/op
     p(99.9900) =     22.646 ms/op
     p(99.9990) =     25.412 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 6.031 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
Iteration   1: 4.036 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  14.323 ms/op
                 getUser·p0.9999: 46.470 ms/op
                 getUser·p1.00:   48.300 ms/op

Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  9.938 ms/op
                 getUser·p0.9999: 30.251 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   3: 4.205 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   6.786 ms/op
                 getUser·p0.999:  11.270 ms/op
                 getUser·p0.9999: 33.404 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233591
  mean =      4.109 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 208372 
    [ 5.000, 10.000) = 24892 
    [10.000, 15.000) = 199 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 26 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 42 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     45.917 ms/op
     p(99.9990) =     48.015 ms/op
     p(99.9999) =     48.300 ms/op
    p(100.0000) =     48.300 ms/op


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
# Warmup Iteration   1: 7.442 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.743 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.376 ±(99.9%) 0.019 ms/op
Iteration   1: 5.381 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  17.517 ms/op
                 listUser·p0.9999: 24.285 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 5.397 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  16.740 ms/op
                 listUser·p0.9999: 19.766 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 5.467 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  21.021 ms/op
                 listUser·p0.9999: 33.422 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177182
  mean =      5.415 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 156 
    [ 2.500,  5.000) = 70261 
    [ 5.000,  7.500) = 96327 
    [ 7.500, 10.000) = 8986 
    [10.000, 12.500) = 1067 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     31.139 ms/op
     p(99.9990) =     35.777 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.736 ± 3.137  ops/ms
ClientGrpc.existUser                       thrpt       3   8.351 ± 1.703  ops/ms
ClientGrpc.getUser                         thrpt       3   7.854 ± 3.591  ops/ms
ClientGrpc.listUser                        thrpt       3   6.097 ± 1.246  ops/ms
ClientGrpc.createUser                       avgt       3   4.032 ± 1.524   ms/op
ClientGrpc.existUser                        avgt       3   3.763 ± 1.246   ms/op
ClientGrpc.getUser                          avgt       3   4.109 ± 1.114   ms/op
ClientGrpc.listUser                         avgt       3   5.339 ± 1.989   ms/op
ClientGrpc.createUser                     sample  235075   4.081 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.824           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.764           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.118           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  248972   3.854 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.455           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.494           ms/op
ClientGrpc.getUser                        sample  233591   4.109 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.994           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.668           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          45.917           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          48.300           ms/op
ClientGrpc.listUser                       sample  177182   5.415 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.337           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.733           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.139           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.979           ms/op
