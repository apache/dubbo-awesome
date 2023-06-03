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
# Warmup Iteration   1: 3.330 ops/ms
# Warmup Iteration   2: 7.324 ops/ms
# Warmup Iteration   3: 8.833 ops/ms
Iteration   1: 9.093 ops/ms
Iteration   2: 9.144 ops/ms
Iteration   3: 9.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.118 ±(99.9%) 0.469 ops/ms [Average]
  (min, avg, max) = (9.093, 9.118, 9.144), stdev = 0.026
  CI (99.9%): [8.649, 9.587] (assumes normal distribution)


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
# Warmup Iteration   1: 6.214 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 9.742 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 9.492 ops/ms
Iteration   3: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.770 ±(99.9%) 4.419 ops/ms [Average]
  (min, avg, max) = (9.492, 9.770, 9.938), stdev = 0.242
  CI (99.9%): [5.350, 14.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.612 ops/ms
# Warmup Iteration   2: 8.725 ops/ms
# Warmup Iteration   3: 9.066 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.246 ±(99.9%) 0.520 ops/ms [Average]
  (min, avg, max) = (9.213, 9.246, 9.263), stdev = 0.028
  CI (99.9%): [8.726, 9.765] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ops/ms
# Warmup Iteration   2: 6.695 ops/ms
# Warmup Iteration   3: 7.070 ops/ms
Iteration   1: 6.957 ops/ms
Iteration   2: 7.047 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.005 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (6.957, 7.005, 7.047), stdev = 0.045
  CI (99.9%): [6.183, 7.827] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.003 ms/op
Iteration   1: 3.503 ±(99.9%) 0.004 ms/op
Iteration   2: 3.440 ±(99.9%) 0.003 ms/op
Iteration   3: 3.475 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.472 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.440, 3.472, 3.503), stdev = 0.032
  CI (99.9%): [2.894, 4.051] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.003 ms/op
Iteration   2: 3.313 ±(99.9%) 0.004 ms/op
Iteration   3: 3.315 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.326 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.313, 3.326, 3.350), stdev = 0.021
  CI (99.9%): [2.950, 3.702] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.236 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.005 ms/op
Iteration   1: 3.521 ±(99.9%) 0.004 ms/op
Iteration   2: 3.428 ±(99.9%) 0.004 ms/op
Iteration   3: 3.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.468 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (3.428, 3.468, 3.521), stdev = 0.048
  CI (99.9%): [2.594, 4.342] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.581 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.748 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.590 ±(99.9%) 0.024 ms/op
Iteration   1: 4.440 ±(99.9%) 0.009 ms/op
Iteration   2: 4.338 ±(99.9%) 0.005 ms/op
Iteration   3: 4.538 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.439 ±(99.9%) 1.829 ms/op [Average]
  (min, avg, max) = (4.338, 4.439, 4.538), stdev = 0.100
  CI (99.9%): [2.610, 6.268] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.807 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.007 ms/op
Iteration   1: 3.513 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  12.809 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 3.552 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.097 ms/op
                 createUser·p0.999:  8.467 ms/op
                 createUser·p0.9999: 16.498 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.672 ms/op
                 createUser·p0.999:  19.151 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273756
  mean =      3.508 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6274 
    [ 2.500,  5.000) = 264547 
    [ 5.000,  7.500) = 2462 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     11.063 ms/op
     p(99.9900) =     26.812 ms/op
     p(99.9990) =     30.033 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.007 ms/op
Iteration   1: 3.341 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  7.448 ms/op
                 existUser·p0.9999: 15.565 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 3.313 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 15.565 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   3: 3.363 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.827 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287655
  mean =      3.339 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 6868 
    [ 2.500,  3.750) = 245410 
    [ 3.750,  5.000) = 32472 
    [ 5.000,  6.250) = 1788 
    [ 6.250,  7.500) = 452 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     17.015 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.452 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  7.963 ms/op
                 getUser·p0.9999: 14.671 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.526 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  15.455 ms/op
                 getUser·p0.9999: 16.350 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  7.104 ms/op
                 getUser·p0.9999: 20.048 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275125
  mean =      3.489 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9748 
    [ 2.500,  5.000) = 261289 
    [ 5.000,  7.500) = 3716 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =      8.190 ms/op
     p(99.9900) =     19.398 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 6.728 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 4.572 ±(99.9%) 0.013 ms/op
Iteration   1: 4.579 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.763 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.565 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  17.592 ms/op
                 listUser·p0.9999: 26.967 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 4.541 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  17.415 ms/op
                 listUser·p0.9999: 20.904 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210563
  mean =      4.562 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 175410 
    [ 5.000,  7.500) = 31583 
    [ 7.500, 10.000) = 2777 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.187 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.118 ± 0.469  ops/ms
ClientGrpc.existUser                       thrpt       3   9.770 ± 4.419  ops/ms
ClientGrpc.getUser                         thrpt       3   9.246 ± 0.520  ops/ms
ClientGrpc.listUser                        thrpt       3   7.005 ± 0.822  ops/ms
ClientGrpc.createUser                       avgt       3   3.472 ± 0.578   ms/op
ClientGrpc.existUser                        avgt       3   3.326 ± 0.376   ms/op
ClientGrpc.getUser                          avgt       3   3.468 ± 0.874   ms/op
ClientGrpc.listUser                         avgt       3   4.439 ± 1.829   ms/op
ClientGrpc.createUser                     sample  273756   3.508 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.816           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.038           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.063           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.812           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  287655   3.339 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.024           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  275125   3.489 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.623           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.398           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  210563   4.562 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.848           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.593           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.280           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.263           ms/op
