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
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 8.362 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.597 ops/ms
Iteration   2: 9.683 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.761 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (9.597, 9.761, 10.003), stdev = 0.214
  CI (99.9%): [5.858, 13.664] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.928 ops/ms
# Warmup Iteration   2: 9.385 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.653 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.159 ±(99.9%) 8.098 ops/ms [Average]
  (min, avg, max) = (9.653, 10.159, 10.482), stdev = 0.444
  CI (99.9%): [2.061, 18.257] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 9.220 ops/ms
# Warmup Iteration   3: 9.541 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 9.657 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.859 ±(99.9%) 3.495 ops/ms [Average]
  (min, avg, max) = (9.657, 9.859, 10.038), stdev = 0.192
  CI (99.9%): [6.364, 13.354] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.271 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.469 ops/ms
Iteration   1: 7.655 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 7.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.707 ±(99.9%) 4.070 ops/ms [Average]
  (min, avg, max) = (7.514, 7.707, 7.951), stdev = 0.223
  CI (99.9%): [3.637, 11.777] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.001 ms/op
Iteration   1: 3.228 ±(99.9%) 0.002 ms/op
Iteration   2: 3.356 ±(99.9%) 0.002 ms/op
Iteration   3: 3.406 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.330 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (3.228, 3.330, 3.406), stdev = 0.091
  CI (99.9%): [1.662, 4.998] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.003 ms/op
Iteration   1: 3.199 ±(99.9%) 0.003 ms/op
Iteration   2: 3.180 ±(99.9%) 0.001 ms/op
Iteration   3: 3.238 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.206 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.180, 3.206, 3.238), stdev = 0.029
  CI (99.9%): [2.669, 3.743] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.002 ms/op
Iteration   1: 3.300 ±(99.9%) 0.002 ms/op
Iteration   2: 3.314 ±(99.9%) 0.004 ms/op
Iteration   3: 3.352 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.322 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (3.300, 3.322, 3.352), stdev = 0.027
  CI (99.9%): [2.830, 3.814] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.045 ms/op
Iteration   1: 4.176 ±(99.9%) 0.022 ms/op
Iteration   2: 4.060 ±(99.9%) 0.005 ms/op
Iteration   3: 4.079 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.105 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (4.060, 4.105, 4.176), stdev = 0.063
  CI (99.9%): [2.964, 5.246] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.007 ms/op
Iteration   1: 3.437 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  9.091 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.260 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  10.629 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.085 ms/op
                 createUser·p0.999:  13.574 ms/op
                 createUser·p0.9999: 21.135 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 286414
  mean =      3.351 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9557 
    [ 2.500,  5.000) = 274079 
    [ 5.000,  7.500) = 2161 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     10.315 ms/op
     p(99.9900) =     21.072 ms/op
     p(99.9990) =     22.050 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.271 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  8.588 ms/op
                 existUser·p0.9999: 14.051 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.605 ms/op
                 existUser·p0.999:  6.715 ms/op
                 existUser·p0.9999: 14.482 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  6.946 ms/op
                 existUser·p0.9999: 28.661 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 301805
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19647 
    [ 2.500,  5.000) = 280168 
    [ 5.000,  7.500) = 1651 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.743 ms/op
     p(99.9900) =     26.754 ms/op
     p(99.9990) =     28.932 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.007 ms/op
Iteration   1: 3.288 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.231 ms/op
                 getUser·p0.9999: 14.615 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 3.299 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.018 ms/op
                 getUser·p0.9999: 16.191 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.265 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.442 ms/op
                 getUser·p0.9999: 21.830 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292248
  mean =      3.284 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12583 
    [ 2.500,  5.000) = 277646 
    [ 5.000,  7.500) = 1610 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.466 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     22.063 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 5.816 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.010 ms/op
Iteration   1: 4.134 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  14.049 ms/op
                 listUser·p0.9999: 16.196 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   2: 4.076 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.868 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.448 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 4.268 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   4.182 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.565 ms/op
                 listUser·p0.999:  15.896 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230915
  mean =      4.158 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1148 
    [ 2.500,  5.000) = 213768 
    [ 5.000,  7.500) = 14122 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     14.976 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     19.907 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.761 ± 3.903  ops/ms
ClientGrpc.existUser                       thrpt       3  10.159 ± 8.098  ops/ms
ClientGrpc.getUser                         thrpt       3   9.859 ± 3.495  ops/ms
ClientGrpc.listUser                        thrpt       3   7.707 ± 4.070  ops/ms
ClientGrpc.createUser                       avgt       3   3.330 ± 1.668   ms/op
ClientGrpc.existUser                        avgt       3   3.206 ± 0.537   ms/op
ClientGrpc.getUser                          avgt       3   3.322 ± 0.492   ms/op
ClientGrpc.listUser                         avgt       3   4.105 ± 1.141   ms/op
ClientGrpc.createUser                     sample  286414   3.351 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.289           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.315           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.072           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  301805   3.181 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.743           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.754           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.000           ms/op
ClientGrpc.getUser                        sample  292248   3.284 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.488           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.240           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.466           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.054           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.315           ms/op
ClientGrpc.listUser                       sample  230915   4.158 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.945           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.067           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.976           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.990           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.775           ms/op
