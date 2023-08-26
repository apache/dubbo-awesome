# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.412 ops/ms
# Warmup Iteration   2: 4.851 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.015 ops/ms
Iteration   2: 9.753 ops/ms
Iteration   3: 9.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.539 ±(99.9%) 8.326 ops/ms [Average]
  (min, avg, max) = (9.015, 9.539, 9.849), stdev = 0.456
  CI (99.9%): [1.212, 17.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ops/ms
# Warmup Iteration   2: 8.300 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.224 ops/ms
Iteration   2: 10.004 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.222 ±(99.9%) 3.969 ops/ms [Average]
  (min, avg, max) = (10.004, 10.222, 10.439), stdev = 0.218
  CI (99.9%): [6.253, 14.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.426 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.806 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 10.060 ops/ms
Iteration   3: 9.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.004 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (9.968, 10.004, 10.060), stdev = 0.049
  CI (99.9%): [9.111, 10.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.475 ops/ms
Iteration   1: 8.478 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.417 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (8.332, 8.417, 8.478), stdev = 0.076
  CI (99.9%): [7.028, 9.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.003 ms/op
Iteration   1: 3.256 ±(99.9%) 0.007 ms/op
Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.223 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.196, 3.223, 3.256), stdev = 0.030
  CI (99.9%): [2.673, 3.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.635 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.005 ms/op
Iteration   1: 3.219 ±(99.9%) 0.004 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.144 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (3.045, 3.144, 3.219), stdev = 0.090
  CI (99.9%): [1.511, 4.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.004 ms/op
Iteration   1: 3.284 ±(99.9%) 0.005 ms/op
Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
Iteration   3: 3.241 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.232 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.171, 3.232, 3.284), stdev = 0.057
  CI (99.9%): [2.193, 4.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.514 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.734 ±(99.9%) 0.006 ms/op
Iteration   2: 3.806 ±(99.9%) 0.004 ms/op
Iteration   3: 3.782 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.774 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.734, 3.774, 3.806), stdev = 0.037
  CI (99.9%): [3.099, 4.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.394 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.011 ms/op
Iteration   1: 3.327 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  19.777 ms/op
                 createUser·p0.9999: 27.583 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 3.293 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  17.356 ms/op
                 createUser·p0.9999: 32.493 ms/op
                 createUser·p1.00:   33.358 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.835 ms/op
                 createUser·p0.9999: 20.635 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294598
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22107 
    [ 2.500,  5.000) = 265110 
    [ 5.000,  7.500) = 5986 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     30.964 ms/op
     p(99.9990) =     33.294 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.199 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.098 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   6.123 ms/op
                 existUser·p0.999:  10.868 ms/op
                 existUser·p0.9999: 23.517 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 23.591 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.031 ms/op
                 existUser·p0.9999: 24.684 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307260
  mean =      3.120 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14915 
    [ 2.500,  5.000) = 285359 
    [ 5.000,  7.500) = 5800 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     10.973 ms/op
     p(99.9900) =     24.257 ms/op
     p(99.9990) =     25.088 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.760 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
Iteration   1: 3.298 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.459 ms/op
                 getUser·p0.9999: 22.417 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  17.106 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.403 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  20.183 ms/op
                 getUser·p0.9999: 23.370 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290022
  mean =      3.310 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20043 
    [ 2.500,  5.000) = 260969 
    [ 5.000,  7.500) = 7291 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 220 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.320 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.234 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.013 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.708 ms/op
                 listUser·p0.9999: 22.622 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 16.672 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.134 ms/op
                 listUser·p0.9999: 20.827 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252375
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 242486 
    [ 5.000,  7.500) = 7542 
    [ 7.500, 10.000) = 1622 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     14.756 ms/op
     p(99.9900) =     21.938 ms/op
     p(99.9990) =     22.919 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.539 ± 8.326  ops/ms
ClientPb.existUser                       thrpt       3  10.222 ± 3.969  ops/ms
ClientPb.getUser                         thrpt       3  10.004 ± 0.893  ops/ms
ClientPb.listUser                        thrpt       3   8.417 ± 1.390  ops/ms
ClientPb.createUser                       avgt       3   3.223 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   3.144 ± 1.633   ms/op
ClientPb.getUser                          avgt       3   3.232 ± 1.039   ms/op
ClientPb.listUser                         avgt       3   3.774 ± 0.675   ms/op
ClientPb.createUser                     sample  294598   3.256 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.980           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.964           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.358           ms/op
ClientPb.existUser                      sample  307260   3.120 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.973           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.257           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.690           ms/op
ClientPb.getUser                        sample  290022   3.310 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.909           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.531           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.445           ms/op
ClientPb.listUser                       sample  252375   3.803 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.756           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.938           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
