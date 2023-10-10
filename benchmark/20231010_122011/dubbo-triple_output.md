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
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 5.219 ops/ms
# Warmup Iteration   3: 8.097 ops/ms
Iteration   1: 8.697 ops/ms
Iteration   2: 8.876 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.704 ±(99.9%) 3.078 ops/ms [Average]
  (min, avg, max) = (8.539, 8.704, 8.876), stdev = 0.169
  CI (99.9%): [5.626, 11.782] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.452 ops/ms
# Warmup Iteration   2: 7.839 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 9.186 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.160 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (9.068, 9.160, 9.225), stdev = 0.082
  CI (99.9%): [7.672, 10.648] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 7.460 ops/ms
# Warmup Iteration   3: 8.593 ops/ms
Iteration   1: 8.464 ops/ms
Iteration   2: 8.316 ops/ms
Iteration   3: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.496 ±(99.9%) 3.599 ops/ms [Average]
  (min, avg, max) = (8.316, 8.496, 8.707), stdev = 0.197
  CI (99.9%): [4.896, 12.095] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.180 ops/ms
# Warmup Iteration   2: 6.064 ops/ms
# Warmup Iteration   3: 7.298 ops/ms
Iteration   1: 7.174 ops/ms
Iteration   2: 7.403 ops/ms
Iteration   3: 7.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.335 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (7.174, 7.335, 7.427), stdev = 0.140
  CI (99.9%): [4.786, 9.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.046 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.008 ms/op
Iteration   1: 3.710 ±(99.9%) 0.005 ms/op
Iteration   2: 3.677 ±(99.9%) 0.007 ms/op
Iteration   3: 3.654 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.680 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.654, 3.680, 3.710), stdev = 0.028
  CI (99.9%): [3.164, 4.196] (assumes normal distribution)


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
# Warmup Iteration   1: 10.810 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.003 ms/op
Iteration   1: 3.467 ±(99.9%) 0.008 ms/op
Iteration   2: 3.539 ±(99.9%) 0.006 ms/op
Iteration   3: 3.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.512 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.467, 3.512, 3.539), stdev = 0.039
  CI (99.9%): [2.798, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 11.014 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.007 ms/op
Iteration   1: 3.613 ±(99.9%) 0.005 ms/op
Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
Iteration   3: 3.584 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.603 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.584, 3.603, 3.613), stdev = 0.017
  CI (99.9%): [3.300, 3.907] (assumes normal distribution)


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
# Warmup Iteration   1: 12.723 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.009 ms/op
Iteration   1: 4.191 ±(99.9%) 0.006 ms/op
Iteration   2: 4.255 ±(99.9%) 0.008 ms/op
Iteration   3: 4.307 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.251 ±(99.9%) 1.060 ms/op [Average]
  (min, avg, max) = (4.191, 4.251, 4.307), stdev = 0.058
  CI (99.9%): [3.191, 5.311] (assumes normal distribution)


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
# Warmup Iteration   1: 11.133 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.014 ms/op
Iteration   1: 3.725 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   5.051 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  22.287 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   2: 3.567 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 26.838 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.569 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  24.053 ms/op
                 createUser·p0.9999: 29.229 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265300
  mean =      3.619 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2800 
    [ 2.500,  5.000) = 252718 
    [ 5.000,  7.500) = 7886 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     22.666 ms/op
     p(99.9900) =     28.668 ms/op
     p(99.9990) =     30.300 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 9.216 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.010 ms/op
Iteration   1: 3.543 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   7.609 ms/op
                 existUser·p0.999:  24.286 ms/op
                 existUser·p0.9999: 28.592 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  13.740 ms/op
                 existUser·p0.9999: 35.979 ms/op
                 existUser·p1.00:   36.700 ms/op

Iteration   3: 3.578 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  24.854 ms/op
                 existUser·p0.9999: 33.951 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 270337
  mean =      3.553 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3068 
    [ 2.500,  5.000) = 256404 
    [ 5.000,  7.500) = 8092 
    [ 7.500, 10.000) = 2056 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     24.161 ms/op
     p(99.9900) =     34.666 ms/op
     p(99.9990) =     36.392 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.047 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.013 ms/op
Iteration   1: 3.641 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  21.827 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.583 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  15.640 ms/op
                 getUser·p0.9999: 25.597 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.670 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   8.126 ms/op
                 getUser·p0.999:  25.323 ms/op
                 getUser·p0.9999: 30.141 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264338
  mean =      3.631 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1615 
    [ 2.500,  5.000) = 250967 
    [ 5.000,  7.500) = 8775 
    [ 7.500, 10.000) = 2237 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     19.278 ms/op
     p(99.9900) =     29.041 ms/op
     p(99.9990) =     31.022 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 13.570 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.758 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.016 ms/op
Iteration   1: 4.377 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  23.623 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 4.386 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   9.245 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 27.680 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 4.251 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.922 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 221194
  mean =      4.337 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 207203 
    [ 5.000,  7.500) = 9620 
    [ 7.500, 10.000) = 3026 
    [10.000, 12.500) = 516 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 283 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     18.109 ms/op
     p(99.9900) =     25.621 ms/op
     p(99.9990) =     27.944 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.704 ± 3.078  ops/ms
ClientPb.existUser                       thrpt       3   9.160 ± 1.488  ops/ms
ClientPb.getUser                         thrpt       3   8.496 ± 3.599  ops/ms
ClientPb.listUser                        thrpt       3   7.335 ± 2.549  ops/ms
ClientPb.createUser                       avgt       3   3.680 ± 0.516   ms/op
ClientPb.existUser                        avgt       3   3.512 ± 0.714   ms/op
ClientPb.getUser                          avgt       3   3.603 ± 0.303   ms/op
ClientPb.listUser                         avgt       3   4.251 ± 1.060   ms/op
ClientPb.createUser                     sample  265300   3.619 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.666           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.668           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  270337   3.553 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.520           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.161           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.666           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.700           ms/op
ClientPb.getUser                        sample  264338   3.631 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.555           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.278           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  221194   4.337 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.109           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.621           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.984           ms/op
