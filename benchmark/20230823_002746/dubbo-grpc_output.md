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
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 9.233 ops/ms
Iteration   1: 9.404 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.582 ±(99.9%) 2.869 ops/ms [Average]
  (min, avg, max) = (9.404, 9.582, 9.700), stdev = 0.157
  CI (99.9%): [6.713, 12.452] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 10.206 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.136 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (10.044, 10.136, 10.246), stdev = 0.102
  CI (99.9%): [8.272, 12.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ops/ms
# Warmup Iteration   2: 9.189 ops/ms
# Warmup Iteration   3: 9.390 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.578 ops/ms
Iteration   3: 9.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.543 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (9.505, 9.543, 9.578), stdev = 0.036
  CI (99.9%): [8.879, 10.206] (assumes normal distribution)


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
# Warmup Iteration   1: 5.007 ops/ms
# Warmup Iteration   2: 6.719 ops/ms
# Warmup Iteration   3: 7.052 ops/ms
Iteration   1: 7.151 ops/ms
Iteration   2: 7.167 ops/ms
Iteration   3: 7.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.199 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (7.151, 7.199, 7.279), stdev = 0.070
  CI (99.9%): [5.924, 8.474] (assumes normal distribution)


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.363 ±(99.9%) 0.002 ms/op
Iteration   3: 3.328 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.347 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.328, 3.347, 3.363), stdev = 0.017
  CI (99.9%): [3.033, 3.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.004 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.247 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.193 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.107, 3.193, 3.247), stdev = 0.075
  CI (99.9%): [1.822, 4.565] (assumes normal distribution)


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.006 ms/op
Iteration   1: 3.278 ±(99.9%) 0.002 ms/op
Iteration   2: 3.334 ±(99.9%) 0.005 ms/op
Iteration   3: 3.370 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.327 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.278, 3.327, 3.370), stdev = 0.046
  CI (99.9%): [2.482, 4.173] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.954 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.032 ms/op
Iteration   1: 4.475 ±(99.9%) 0.011 ms/op
Iteration   2: 4.524 ±(99.9%) 0.014 ms/op
Iteration   3: 4.496 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.498 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (4.475, 4.498, 4.524), stdev = 0.025
  CI (99.9%): [4.050, 4.947] (assumes normal distribution)


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
Iteration   1: 3.355 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  8.837 ms/op
                 createUser·p0.9999: 16.307 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 3.301 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  9.440 ms/op
                 createUser·p0.9999: 16.493 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.447 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  13.012 ms/op
                 createUser·p0.9999: 20.411 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284972
  mean =      3.367 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11609 
    [ 2.500,  5.000) = 269497 
    [ 5.000,  7.500) = 3091 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     22.161 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 13.843 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  9.953 ms/op
                 existUser·p0.9999: 18.358 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  8.482 ms/op
                 existUser·p0.9999: 17.558 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 302975
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1456 
    [ 1.250,  2.500) = 18206 
    [ 2.500,  3.750) = 254811 
    [ 3.750,  5.000) = 25937 
    [ 5.000,  6.250) = 1673 
    [ 6.250,  7.500) = 422 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 132 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     19.004 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.404 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 15.087 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  14.512 ms/op
                 getUser·p0.9999: 18.336 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.319 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 16.920 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 284565
  mean =      3.372 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 8735 
    [ 2.500,  3.750) = 225970 
    [ 3.750,  5.000) = 46533 
    [ 5.000,  6.250) = 1822 
    [ 6.250,  7.500) = 647 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 159 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      9.412 ms/op
     p(99.9900) =     17.450 ms/op
     p(99.9990) =     18.622 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 6.337 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.013 ms/op
Iteration   1: 4.555 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  18.622 ms/op
                 listUser·p0.9999: 22.378 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 4.470 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.646 ms/op
                 listUser·p0.9999: 21.524 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 4.431 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  19.631 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 214202
  mean =      4.485 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 922 
    [ 2.500,  5.000) = 177456 
    [ 5.000,  7.500) = 32319 
    [ 7.500, 10.000) = 2801 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     18.606 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.370 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.582 ± 2.869  ops/ms
ClientGrpc.existUser                       thrpt       3  10.136 ± 1.864  ops/ms
ClientGrpc.getUser                         thrpt       3   9.543 ± 0.664  ops/ms
ClientGrpc.listUser                        thrpt       3   7.199 ± 1.275  ops/ms
ClientGrpc.createUser                       avgt       3   3.347 ± 0.314   ms/op
ClientGrpc.existUser                        avgt       3   3.193 ± 1.372   ms/op
ClientGrpc.getUser                          avgt       3   3.327 ± 0.845   ms/op
ClientGrpc.listUser                         avgt       3   4.498 ± 0.448   ms/op
ClientGrpc.createUser                     sample  284972   3.367 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.758           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.330           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.072           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  302975   3.167 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.391           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.150           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.334           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  284565   3.372 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.865           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.079           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.412           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.450           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  214202   4.485 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.606           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
