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
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 4.947 ops/ms
# Warmup Iteration   3: 6.730 ops/ms
Iteration   1: 6.804 ops/ms
Iteration   2: 6.994 ops/ms
Iteration   3: 7.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.974 ±(99.9%) 2.944 ops/ms [Average]
  (min, avg, max) = (6.804, 6.974, 7.124), stdev = 0.161
  CI (99.9%): [4.030, 9.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.236 ops/ms
# Warmup Iteration   2: 6.578 ops/ms
# Warmup Iteration   3: 7.158 ops/ms
Iteration   1: 7.179 ops/ms
Iteration   2: 7.074 ops/ms
Iteration   3: 7.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.205 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (7.074, 7.205, 7.363), stdev = 0.146
  CI (99.9%): [4.538, 9.872] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ops/ms
# Warmup Iteration   2: 6.327 ops/ms
# Warmup Iteration   3: 6.845 ops/ms
Iteration   1: 7.041 ops/ms
Iteration   2: 7.043 ops/ms
Iteration   3: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.041 ±(99.9%) 0.025 ops/ms [Average]
  (min, avg, max) = (7.040, 7.041, 7.043), stdev = 0.001
  CI (99.9%): [7.016, 7.066] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 4.734 ops/ms
# Warmup Iteration   3: 5.084 ops/ms
Iteration   1: 5.214 ops/ms
Iteration   2: 5.534 ops/ms
Iteration   3: 5.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.395 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (5.214, 5.395, 5.534), stdev = 0.164
  CI (99.9%): [2.408, 8.382] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.703 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.946 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.004 ms/op
Iteration   1: 4.676 ±(99.9%) 0.004 ms/op
Iteration   2: 4.568 ±(99.9%) 0.004 ms/op
Iteration   3: 4.656 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.633 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (4.568, 4.633, 4.676), stdev = 0.057
  CI (99.9%): [3.588, 5.678] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.402 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.007 ms/op
Iteration   1: 4.363 ±(99.9%) 0.003 ms/op
Iteration   2: 4.209 ±(99.9%) 0.005 ms/op
Iteration   3: 4.314 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.295 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (4.209, 4.295, 4.363), stdev = 0.079
  CI (99.9%): [2.857, 5.733] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.021 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.015 ms/op
Iteration   1: 4.552 ±(99.9%) 0.004 ms/op
Iteration   2: 4.541 ±(99.9%) 0.003 ms/op
Iteration   3: 4.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.527 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (4.488, 4.527, 4.552), stdev = 0.034
  CI (99.9%): [3.904, 5.149] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.506 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.031 ±(99.9%) 0.024 ms/op
Iteration   1: 5.845 ±(99.9%) 0.024 ms/op
Iteration   2: 5.986 ±(99.9%) 0.021 ms/op
Iteration   3: 6.108 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.980 ±(99.9%) 2.395 ms/op [Average]
  (min, avg, max) = (5.845, 5.980, 6.108), stdev = 0.131
  CI (99.9%): [3.584, 8.375] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.308 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.015 ms/op
Iteration   1: 4.539 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  14.802 ms/op
                 createUser·p0.9999: 22.898 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 4.541 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  11.053 ms/op
                 createUser·p0.9999: 25.033 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 4.638 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  11.865 ms/op
                 createUser·p0.9999: 27.929 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209898
  mean =      4.572 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2311 
    [ 2.500,  5.000) = 151247 
    [ 5.000,  7.500) = 54216 
    [ 7.500, 10.000) = 1644 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     12.832 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     28.204 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.264 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.011 ms/op
Iteration   1: 4.386 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  10.356 ms/op
                 existUser·p0.9999: 17.338 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 4.214 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  13.388 ms/op
                 existUser·p0.9999: 17.056 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   3: 4.355 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.942 ms/op
                 existUser·p0.99:   8.012 ms/op
                 existUser·p0.999:  10.954 ms/op
                 existUser·p0.9999: 20.687 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222215
  mean =      4.317 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2898 
    [ 2.500,  5.000) = 181888 
    [ 5.000,  7.500) = 35052 
    [ 7.500, 10.000) = 1946 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     11.039 ms/op
     p(99.9900) =     20.145 ms/op
     p(99.9990) =     21.114 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 6.954 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.013 ms/op
Iteration   1: 4.581 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   7.987 ms/op
                 getUser·p0.999:  12.472 ms/op
                 getUser·p0.9999: 17.630 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 4.680 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  12.796 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 4.503 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 22.459 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209243
  mean =      4.587 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4033 
    [ 2.500,  5.000) = 147975 
    [ 5.000,  7.500) = 54477 
    [ 7.500, 10.000) = 2110 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     12.841 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 8.894 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.242 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.167 ±(99.9%) 0.026 ms/op
Iteration   1: 6.337 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.387 ms/op
                 listUser·p0.99:   13.615 ms/op
                 listUser·p0.999:  21.758 ms/op
                 listUser·p0.9999: 23.262 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 5.900 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  17.577 ms/op
                 listUser·p0.9999: 24.431 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 5.844 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  20.391 ms/op
                 listUser·p0.9999: 37.980 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159451
  mean =      6.019 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 40954 
    [ 5.000,  7.500) = 95923 
    [ 7.500, 10.000) = 17065 
    [10.000, 12.500) = 3928 
    [12.500, 15.000) = 910 
    [15.000, 17.500) = 315 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      8.102 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     38.418 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.974 ± 2.944  ops/ms
ClientGrpc.existUser                       thrpt       3   7.205 ± 2.667  ops/ms
ClientGrpc.getUser                         thrpt       3   7.041 ± 0.025  ops/ms
ClientGrpc.listUser                        thrpt       3   5.395 ± 2.987  ops/ms
ClientGrpc.createUser                       avgt       3   4.633 ± 1.045   ms/op
ClientGrpc.existUser                        avgt       3   4.295 ± 1.438   ms/op
ClientGrpc.getUser                          avgt       3   4.527 ± 0.623   ms/op
ClientGrpc.listUser                         avgt       3   5.980 ± 2.395   ms/op
ClientGrpc.createUser                     sample  209898   4.572 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.887           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.512           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.832           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.199           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.312           ms/op
ClientGrpc.existUser                      sample  222215   4.317 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.610           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.039           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.145           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  209243   4.587 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.837           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.226           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.873           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.841           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.692           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  159451   6.019 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.980           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.306           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.337           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.914           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.535           ms/op
