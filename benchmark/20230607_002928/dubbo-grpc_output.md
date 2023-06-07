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
# Warmup Iteration   1: 3.901 ops/ms
# Warmup Iteration   2: 8.714 ops/ms
# Warmup Iteration   3: 10.042 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.479 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (10.338, 10.479, 10.629), stdev = 0.146
  CI (99.9%): [7.820, 13.139] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.087 ops/ms
# Warmup Iteration   2: 10.251 ops/ms
# Warmup Iteration   3: 10.831 ops/ms
Iteration   1: 11.015 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 11.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.991 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (10.837, 10.991, 11.120), stdev = 0.143
  CI (99.9%): [8.376, 13.605] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.856 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.499 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.671 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (10.480, 10.671, 10.796), stdev = 0.168
  CI (99.9%): [7.613, 13.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.108 ops/ms
Iteration   1: 8.121 ops/ms
Iteration   2: 8.238 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.163 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (8.121, 8.163, 8.238), stdev = 0.065
  CI (99.9%): [6.970, 9.355] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.009 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (2.975, 3.039, 3.095), stdev = 0.061
  CI (99.9%): [1.932, 4.146] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.002 ms/op
Iteration   1: 2.889 ±(99.9%) 0.002 ms/op
Iteration   2: 2.897 ±(99.9%) 0.002 ms/op
Iteration   3: 2.815 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (2.815, 2.867, 2.897), stdev = 0.045
  CI (99.9%): [2.044, 3.689] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.054 ±(99.9%) 0.004 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (3.044, 3.052, 3.059), stdev = 0.007
  CI (99.9%): [2.920, 3.185] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.328 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.020 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
Iteration   2: 3.946 ±(99.9%) 0.023 ms/op
Iteration   3: 3.951 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.946, 3.958, 3.976), stdev = 0.016
  CI (99.9%): [3.671, 4.244] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.771 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.638 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 14.068 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 18.797 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315896
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 849 
    [ 1.250,  2.500) = 24706 
    [ 2.500,  3.750) = 274008 
    [ 3.750,  5.000) = 14319 
    [ 5.000,  6.250) = 1018 
    [ 6.250,  7.500) = 451 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     17.905 ms/op
     p(99.9990) =     19.093 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
Iteration   1: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.312 ms/op
                 existUser·p0.999:  5.904 ms/op
                 existUser·p0.9999: 12.874 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 20.050 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 18.546 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332384
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47232 
    [ 2.500,  5.000) = 284267 
    [ 5.000,  7.500) = 587 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.834 ms/op
     p(99.9900) =     18.924 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.517 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.033 ms/op
                 getUser·p0.9999: 11.928 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.249 ms/op
                 getUser·p0.9999: 13.762 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.332 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319002
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 531 
    [ 1.250,  2.500) = 18096 
    [ 2.500,  3.750) = 287111 
    [ 3.750,  5.000) = 11637 
    [ 5.000,  6.250) = 975 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     17.341 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.311 ms/op
                 listUser·p0.9999: 17.816 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.872 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 20.636 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.436 ms/op
                 listUser·p0.9999: 21.429 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244495
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3124 
    [ 2.500,  5.000) = 218381 
    [ 5.000,  7.500) = 21676 
    [ 7.500, 10.000) = 861 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     16.556 ms/op
     p(99.9900) =     21.022 ms/op
     p(99.9990) =     22.038 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.479 ± 2.660  ops/ms
ClientGrpc.existUser                       thrpt       3  10.991 ± 2.614  ops/ms
ClientGrpc.getUser                         thrpt       3  10.671 ± 3.058  ops/ms
ClientGrpc.listUser                        thrpt       3   8.163 ± 1.192  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 1.107   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.822   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.133   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.287   ms/op
ClientGrpc.createUser                     sample  315896   3.043 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.542           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.044           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.905           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.235           ms/op
ClientGrpc.existUser                      sample  332384   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.834           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.924           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  319002   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.341           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  244495   3.924 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.726           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.556           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.022           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
