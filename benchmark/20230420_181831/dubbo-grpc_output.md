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
# Warmup Iteration   1: 2.272 ops/ms
# Warmup Iteration   2: 5.454 ops/ms
# Warmup Iteration   3: 7.127 ops/ms
Iteration   1: 6.975 ops/ms
Iteration   2: 6.876 ops/ms
Iteration   3: 6.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.948 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (6.876, 6.948, 6.991), stdev = 0.062
  CI (99.9%): [5.813, 8.082] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ops/ms
# Warmup Iteration   2: 7.324 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.643 ops/ms
Iteration   2: 8.660 ops/ms
Iteration   3: 8.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.607 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (8.517, 8.607, 8.660), stdev = 0.078
  CI (99.9%): [7.184, 10.029] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ops/ms
# Warmup Iteration   2: 6.812 ops/ms
# Warmup Iteration   3: 7.224 ops/ms
Iteration   1: 7.443 ops/ms
Iteration   2: 7.640 ops/ms
Iteration   3: 7.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.588 ±(99.9%) 2.327 ops/ms [Average]
  (min, avg, max) = (7.443, 7.588, 7.682), stdev = 0.128
  CI (99.9%): [5.261, 9.916] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ops/ms
# Warmup Iteration   2: 5.332 ops/ms
# Warmup Iteration   3: 5.440 ops/ms
Iteration   1: 5.446 ops/ms
Iteration   2: 5.526 ops/ms
Iteration   3: 5.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.489 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (5.446, 5.489, 5.526), stdev = 0.040
  CI (99.9%): [4.752, 6.226] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.014 ms/op
Iteration   1: 4.226 ±(99.9%) 0.005 ms/op
Iteration   2: 4.148 ±(99.9%) 0.004 ms/op
Iteration   3: 4.223 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.199 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (4.148, 4.199, 4.226), stdev = 0.044
  CI (99.9%): [3.387, 5.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.226 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.005 ms/op
Iteration   1: 3.798 ±(99.9%) 0.006 ms/op
Iteration   2: 3.957 ±(99.9%) 0.003 ms/op
Iteration   3: 3.875 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.877 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.798, 3.877, 3.957), stdev = 0.079
  CI (99.9%): [2.427, 5.327] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.379 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.005 ms/op
Iteration   1: 4.538 ±(99.9%) 0.013 ms/op
Iteration   2: 4.504 ±(99.9%) 0.003 ms/op
Iteration   3: 4.192 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.411 ±(99.9%) 3.478 ms/op [Average]
  (min, avg, max) = (4.192, 4.411, 4.538), stdev = 0.191
  CI (99.9%): [0.934, 7.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.994 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.525 ±(99.9%) 0.014 ms/op
Iteration   1: 5.261 ±(99.9%) 0.014 ms/op
Iteration   2: 5.325 ±(99.9%) 0.009 ms/op
Iteration   3: 5.568 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.385 ±(99.9%) 2.956 ms/op [Average]
  (min, avg, max) = (5.261, 5.385, 5.568), stdev = 0.162
  CI (99.9%): [2.429, 8.340] (assumes normal distribution)


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
# Warmup Iteration   1: 7.025 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.016 ms/op
Iteration   1: 4.298 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 25.166 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 4.198 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  18.421 ms/op
                 createUser·p0.9999: 33.513 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 4.220 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  15.002 ms/op
                 createUser·p0.9999: 34.210 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226550
  mean =      4.238 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7181 
    [ 2.500,  5.000) = 186677 
    [ 5.000,  7.500) = 29091 
    [ 7.500, 10.000) = 2343 
    [10.000, 12.500) = 627 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     18.430 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 6.324 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.015 ms/op
Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  16.529 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  11.061 ms/op
                 existUser·p0.9999: 20.794 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.940 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  18.540 ms/op
                 existUser·p0.9999: 21.329 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242214
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9753 
    [ 2.500,  5.000) = 211023 
    [ 5.000,  7.500) = 19014 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     21.259 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.066 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.013 ms/op
Iteration   1: 4.257 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   7.955 ms/op
                 getUser·p0.999:  16.171 ms/op
                 getUser·p0.9999: 19.283 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 4.259 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  15.090 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   3: 4.184 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   8.266 ms/op
                 getUser·p0.999:  17.831 ms/op
                 getUser·p0.9999: 20.756 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226643
  mean =      4.233 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6090 
    [ 2.500,  5.000) = 186794 
    [ 5.000,  7.500) = 31183 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 317 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     19.475 ms/op
     p(99.9990) =     21.085 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.409 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.840 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.427 ±(99.9%) 0.021 ms/op
Iteration   1: 5.349 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.323 ms/op
                 listUser·p0.999:  21.842 ms/op
                 listUser·p0.9999: 26.674 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 5.356 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  20.336 ms/op
                 listUser·p0.9999: 23.136 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 5.464 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.949 ms/op
                 listUser·p0.999:  25.325 ms/op
                 listUser·p0.9999: 28.887 ms/op
                 listUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178149
  mean =      5.389 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 384 
    [ 2.500,  5.000) = 82725 
    [ 5.000,  7.500) = 81471 
    [ 7.500, 10.000) = 10933 
    [10.000, 12.500) = 1640 
    [12.500, 15.000) = 416 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     27.871 ms/op
     p(99.9990) =     29.414 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.948 ± 1.135  ops/ms
ClientGrpc.existUser                       thrpt       3   8.607 ± 1.422  ops/ms
ClientGrpc.getUser                         thrpt       3   7.588 ± 2.327  ops/ms
ClientGrpc.listUser                        thrpt       3   5.489 ± 0.737  ops/ms
ClientGrpc.createUser                       avgt       3   4.199 ± 0.812   ms/op
ClientGrpc.existUser                        avgt       3   3.877 ± 1.450   ms/op
ClientGrpc.getUser                          avgt       3   4.411 ± 3.478   ms/op
ClientGrpc.listUser                         avgt       3   5.385 ± 2.956   ms/op
ClientGrpc.createUser                     sample  226550   4.238 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.994           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.667           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.997           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.406           ms/op
ClientGrpc.existUser                      sample  242214   3.965 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.481           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.942           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.259           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.675           ms/op
ClientGrpc.getUser                        sample  226643   4.233 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.071           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          16.843           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.475           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  178149   5.389 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.929           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.069           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.732           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.020           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.491           ms/op
