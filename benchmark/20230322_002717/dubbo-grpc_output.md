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
# Warmup Iteration   1: 2.500 ops/ms
# Warmup Iteration   2: 6.142 ops/ms
# Warmup Iteration   3: 7.256 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 7.419 ops/ms
Iteration   3: 7.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.476 ±(99.9%) 3.185 ops/ms [Average]
  (min, avg, max) = (7.338, 7.476, 7.672), stdev = 0.175
  CI (99.9%): [4.291, 10.662] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ops/ms
# Warmup Iteration   2: 7.012 ops/ms
# Warmup Iteration   3: 7.501 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.906 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (7.859, 7.906, 7.966), stdev = 0.055
  CI (99.9%): [6.900, 8.911] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ops/ms
# Warmup Iteration   2: 6.574 ops/ms
# Warmup Iteration   3: 7.556 ops/ms
Iteration   1: 7.685 ops/ms
Iteration   2: 7.787 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.708 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (7.653, 7.708, 7.787), stdev = 0.070
  CI (99.9%): [6.430, 8.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ops/ms
# Warmup Iteration   2: 5.049 ops/ms
# Warmup Iteration   3: 5.552 ops/ms
Iteration   1: 5.482 ops/ms
Iteration   2: 5.836 ops/ms
Iteration   3: 5.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.698 ±(99.9%) 3.453 ops/ms [Average]
  (min, avg, max) = (5.482, 5.698, 5.836), stdev = 0.189
  CI (99.9%): [2.245, 9.151] (assumes normal distribution)


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
# Warmup Iteration   1: 6.159 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.010 ms/op
Iteration   1: 4.100 ±(99.9%) 0.003 ms/op
Iteration   2: 4.043 ±(99.9%) 0.002 ms/op
Iteration   3: 4.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.055 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (4.022, 4.055, 4.100), stdev = 0.040
  CI (99.9%): [3.319, 4.791] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.004 ms/op
Iteration   1: 3.788 ±(99.9%) 0.003 ms/op
Iteration   2: 3.811 ±(99.9%) 0.002 ms/op
Iteration   3: 3.806 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.802 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (3.788, 3.802, 3.811), stdev = 0.012
  CI (99.9%): [3.582, 4.022] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.562 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.003 ms/op
Iteration   1: 4.117 ±(99.9%) 0.003 ms/op
Iteration   2: 4.171 ±(99.9%) 0.003 ms/op
Iteration   3: 4.025 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.104 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (4.025, 4.104, 4.171), stdev = 0.074
  CI (99.9%): [2.763, 5.446] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.468 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.223 ±(99.9%) 0.027 ms/op
Iteration   1: 5.084 ±(99.9%) 0.015 ms/op
Iteration   2: 5.313 ±(99.9%) 0.010 ms/op
Iteration   3: 5.204 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.201 ±(99.9%) 2.089 ms/op [Average]
  (min, avg, max) = (5.084, 5.201, 5.313), stdev = 0.115
  CI (99.9%): [3.111, 7.290] (assumes normal distribution)


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
# Warmup Iteration   1: 6.058 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.012 ms/op
Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  12.877 ms/op
                 createUser·p0.9999: 20.416 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  14.912 ms/op
                 createUser·p0.9999: 34.610 ms/op
                 createUser·p1.00:   35.193 ms/op

Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  13.009 ms/op
                 createUser·p0.9999: 26.091 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237298
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2141 
    [ 2.500,  5.000) = 212975 
    [ 5.000,  7.500) = 20636 
    [ 7.500, 10.000) = 1086 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     33.483 ms/op
     p(99.9990) =     35.037 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 5.725 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
Iteration   1: 4.049 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.671 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 15.198 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   2: 3.718 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 17.203 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.837 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  8.241 ms/op
                 existUser·p0.9999: 18.754 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248392
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 7229 
    [ 2.500,  3.750) = 111161 
    [ 3.750,  5.000) = 112484 
    [ 5.000,  6.250) = 14625 
    [ 6.250,  7.500) = 1937 
    [ 7.500,  8.750) = 560 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     17.705 ms/op
     p(99.9990) =     19.105 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 6.120 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 16.629 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 4.143 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  10.053 ms/op
                 getUser·p0.9999: 16.894 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.091 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  15.906 ms/op
                 getUser·p0.9999: 36.122 ms/op
                 getUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233740
  mean =      4.105 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3529 
    [ 2.500,  5.000) = 204719 
    [ 5.000,  7.500) = 24002 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     11.031 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 7.098 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.662 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.127 ±(99.9%) 0.018 ms/op
Iteration   1: 5.231 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  17.232 ms/op
                 listUser·p0.9999: 19.916 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 5.180 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.499 ms/op
                 listUser·p0.999:  16.304 ms/op
                 listUser·p0.9999: 20.207 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 5.033 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 21.625 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186383
  mean =      5.147 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 160 
    [ 2.500,  5.000) = 99013 
    [ 5.000,  7.500) = 77483 
    [ 7.500, 10.000) = 8484 
    [10.000, 12.500) = 786 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     20.429 ms/op
     p(99.9990) =     22.337 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.476 ± 3.185  ops/ms
ClientGrpc.existUser                       thrpt       3   7.906 ± 1.005  ops/ms
ClientGrpc.getUser                         thrpt       3   7.708 ± 1.279  ops/ms
ClientGrpc.listUser                        thrpt       3   5.698 ± 3.453  ops/ms
ClientGrpc.createUser                       avgt       3   4.055 ± 0.736   ms/op
ClientGrpc.existUser                        avgt       3   3.802 ± 0.220   ms/op
ClientGrpc.getUser                          avgt       3   4.104 ± 1.341   ms/op
ClientGrpc.listUser                         avgt       3   5.201 ± 2.089   ms/op
ClientGrpc.createUser                     sample  237298   4.046 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.876           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.775           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.156           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.483           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.193           ms/op
ClientGrpc.existUser                      sample  248392   3.863 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.705           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  233740   4.105 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.009           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.031           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.783           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.372           ms/op
ClientGrpc.listUser                       sample  186383   5.147 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.434           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.421           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
