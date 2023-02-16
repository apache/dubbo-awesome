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
# Warmup Iteration   1: 1.978 ops/ms
# Warmup Iteration   2: 4.904 ops/ms
# Warmup Iteration   3: 6.363 ops/ms
Iteration   1: 6.421 ops/ms
Iteration   2: 6.536 ops/ms
Iteration   3: 6.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.502 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (6.421, 6.502, 6.549), stdev = 0.070
  CI (99.9%): [5.220, 7.784] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ops/ms
# Warmup Iteration   2: 6.842 ops/ms
# Warmup Iteration   3: 6.957 ops/ms
Iteration   1: 7.310 ops/ms
Iteration   2: 7.243 ops/ms
Iteration   3: 7.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.197 ±(99.9%) 2.574 ops/ms [Average]
  (min, avg, max) = (7.039, 7.197, 7.310), stdev = 0.141
  CI (99.9%): [4.623, 9.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ops/ms
# Warmup Iteration   2: 6.370 ops/ms
# Warmup Iteration   3: 6.555 ops/ms
Iteration   1: 6.628 ops/ms
Iteration   2: 6.711 ops/ms
Iteration   3: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.744 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (6.628, 6.744, 6.892), stdev = 0.135
  CI (99.9%): [4.284, 9.203] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ops/ms
# Warmup Iteration   2: 4.654 ops/ms
# Warmup Iteration   3: 5.055 ops/ms
Iteration   1: 5.058 ops/ms
Iteration   2: 5.179 ops/ms
Iteration   3: 5.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.132 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (5.058, 5.132, 5.179), stdev = 0.065
  CI (99.9%): [3.947, 6.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.118 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.004 ms/op
Iteration   1: 4.856 ±(99.9%) 0.004 ms/op
Iteration   2: 4.882 ±(99.9%) 0.005 ms/op
Iteration   3: 4.717 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.819 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (4.717, 4.819, 4.882), stdev = 0.089
  CI (99.9%): [3.203, 6.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.005 ms/op
Iteration   1: 4.463 ±(99.9%) 0.004 ms/op
Iteration   2: 4.238 ±(99.9%) 0.004 ms/op
Iteration   3: 4.210 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.304 ±(99.9%) 2.533 ms/op [Average]
  (min, avg, max) = (4.210, 4.304, 4.463), stdev = 0.139
  CI (99.9%): [1.770, 6.837] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.644 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.004 ms/op
Iteration   1: 4.677 ±(99.9%) 0.007 ms/op
Iteration   2: 4.592 ±(99.9%) 0.005 ms/op
Iteration   3: 4.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.583 ±(99.9%) 1.794 ms/op [Average]
  (min, avg, max) = (4.481, 4.583, 4.677), stdev = 0.098
  CI (99.9%): [2.789, 6.378] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.167 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 6.346 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.831 ±(99.9%) 0.026 ms/op
Iteration   1: 6.020 ±(99.9%) 0.039 ms/op
Iteration   2: 5.978 ±(99.9%) 0.015 ms/op
Iteration   3: 5.860 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.953 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (5.860, 5.953, 6.020), stdev = 0.083
  CI (99.9%): [4.436, 7.470] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.990 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.890 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.014 ms/op
Iteration   1: 4.753 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   6.144 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  15.653 ms/op
                 createUser·p0.9999: 20.122 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 4.804 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.562 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  15.750 ms/op
                 createUser·p0.9999: 22.655 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 4.497 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.283 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  14.776 ms/op
                 createUser·p0.9999: 21.619 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205029
  mean =      4.681 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3584 
    [ 2.500,  5.000) = 133802 
    [ 5.000,  7.500) = 63506 
    [ 7.500, 10.000) = 3238 
    [10.000, 12.500) = 481 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.913 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.014 ms/op
Iteration   1: 4.311 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   8.161 ms/op
                 existUser·p0.999:  13.682 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 4.325 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   4.243 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.185 ms/op
                 existUser·p0.99:   8.360 ms/op
                 existUser·p0.999:  14.485 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 4.420 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   7.889 ms/op
                 existUser·p0.999:  11.575 ms/op
                 existUser·p0.9999: 30.041 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220472
  mean =      4.351 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11378 
    [ 2.500,  5.000) = 157981 
    [ 5.000,  7.500) = 47655 
    [ 7.500, 10.000) = 2783 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     30.723 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.334 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.017 ms/op
Iteration   1: 4.880 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  16.302 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 5.011 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   6.496 ms/op
                 getUser·p0.95:   7.242 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  13.488 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 4.951 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 22.171 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 194088
  mean =      4.947 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2921 
    [ 2.500,  5.000) = 109231 
    [ 5.000,  7.500) = 74856 
    [ 7.500, 10.000) = 5766 
    [10.000, 12.500) = 923 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     15.480 ms/op
     p(99.9900) =     20.958 ms/op
     p(99.9990) =     23.896 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.671 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.182 ±(99.9%) 0.026 ms/op
Iteration   1: 6.190 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  16.739 ms/op
                 listUser·p0.9999: 25.619 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   2: 6.183 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.403 ms/op
                 listUser·p0.999:  19.274 ms/op
                 listUser·p0.9999: 21.195 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 6.290 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  31.415 ms/op
                 listUser·p0.9999: 36.773 ms/op
                 listUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154347
  mean =      6.221 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 38256 
    [ 5.000,  7.500) = 85757 
    [ 7.500, 10.000) = 23850 
    [10.000, 12.500) = 5015 
    [12.500, 15.000) = 857 
    [15.000, 17.500) = 292 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      8.634 ms/op
     p(95.0000) =      9.699 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     35.820 ms/op
     p(99.9990) =     37.517 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.502 ± 1.282  ops/ms
ClientGrpc.existUser                       thrpt       3   7.197 ± 2.574  ops/ms
ClientGrpc.getUser                         thrpt       3   6.744 ± 2.459  ops/ms
ClientGrpc.listUser                        thrpt       3   5.132 ± 1.185  ops/ms
ClientGrpc.createUser                       avgt       3   4.819 ± 1.616   ms/op
ClientGrpc.existUser                        avgt       3   4.304 ± 2.533   ms/op
ClientGrpc.getUser                          avgt       3   4.583 ± 1.794   ms/op
ClientGrpc.listUser                         avgt       3   5.953 ± 1.517   ms/op
ClientGrpc.createUser                     sample  205029   4.681 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.087           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.537           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.450           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.594           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  220472   4.351 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.985           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.136           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.151           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.992           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.835           ms/op
ClientGrpc.getUser                        sample  194088   4.947 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.141           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.078           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.437           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.480           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.958           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  154347   6.221 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.222           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.497           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.820           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.552           ms/op
