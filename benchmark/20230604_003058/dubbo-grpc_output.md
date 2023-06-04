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
# Warmup Iteration   1: 4.092 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 10.101 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.305 ±(99.9%) 1.487 ops/ms [Average]
  (min, avg, max) = (10.211, 10.305, 10.355), stdev = 0.082
  CI (99.9%): [8.818, 11.792] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.975 ops/ms
Iteration   1: 11.147 ops/ms
Iteration   2: 11.196 ops/ms
Iteration   3: 10.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.111 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (10.990, 11.111, 11.196), stdev = 0.107
  CI (99.9%): [9.155, 13.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.029 ops/ms
# Warmup Iteration   2: 9.734 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.376 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (10.315, 10.376, 10.472), stdev = 0.084
  CI (99.9%): [8.836, 11.915] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ops/ms
# Warmup Iteration   2: 7.643 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.935 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (7.806, 7.935, 8.037), stdev = 0.118
  CI (99.9%): [5.785, 10.086] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.089, 3.117, 3.153), stdev = 0.033
  CI (99.9%): [2.516, 3.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.001 ms/op
Iteration   3: 2.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (2.943, 2.957, 2.982), stdev = 0.022
  CI (99.9%): [2.561, 3.354] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.079 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.058, 3.079, 3.108), stdev = 0.026
  CI (99.9%): [2.607, 3.550] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.981 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.021 ms/op
Iteration   1: 4.042 ±(99.9%) 0.029 ms/op
Iteration   2: 4.015 ±(99.9%) 0.021 ms/op
Iteration   3: 3.989 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.989, 4.015, 4.042), stdev = 0.027
  CI (99.9%): [3.526, 4.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 18.932 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 19.321 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.110 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310855
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18259 
    [ 2.500,  5.000) = 290426 
    [ 5.000,  7.500) = 1726 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.393 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.659 ms/op
                 existUser·p0.999:  8.357 ms/op
                 existUser·p0.9999: 18.982 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  8.310 ms/op
                 existUser·p0.9999: 14.206 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 16.342 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325277
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 800 
    [ 1.250,  2.500) = 29635 
    [ 2.500,  3.750) = 282052 
    [ 3.750,  5.000) = 11347 
    [ 5.000,  6.250) = 643 
    [ 6.250,  7.500) = 426 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     18.562 ms/op
     p(99.9990) =     19.227 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 19.350 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.460 ms/op
                 getUser·p0.9999: 14.885 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.606 ms/op
                 getUser·p0.9999: 17.808 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313829
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14150 
    [ 2.500,  5.000) = 297874 
    [ 5.000,  7.500) = 1396 
    [ 7.500, 10.000) = 249 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     18.562 ms/op
     p(99.9990) =     20.602 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.769 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.013 ms/op
Iteration   1: 4.170 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.477 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.411 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.125 ms/op
                 listUser·p0.9999: 20.127 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.075 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.249 ms/op
                 listUser·p0.999:  19.135 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233075
  mean =      4.118 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2222 
    [ 2.500,  5.000) = 201667 
    [ 5.000,  7.500) = 27299 
    [ 7.500, 10.000) = 1353 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.990 ms/op
     p(99.9900) =     25.400 ms/op
     p(99.9990) =     27.078 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.305 ± 1.487  ops/ms
ClientGrpc.existUser                       thrpt       3  11.111 ± 1.957  ops/ms
ClientGrpc.getUser                         thrpt       3  10.376 ± 1.540  ops/ms
ClientGrpc.listUser                        thrpt       3   7.935 ± 2.151  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.601   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.397   ms/op
ClientGrpc.getUser                          avgt       3   3.079 ± 0.472   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 0.490   ms/op
ClientGrpc.createUser                     sample  310855   3.086 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.629           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.393           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.266           ms/op
ClientGrpc.existUser                      sample  325277   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.777           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.807           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  313829   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.808           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.331           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.562           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  233075   4.118 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.335           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.400           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
