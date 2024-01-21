# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ops/ms
# Warmup Iteration   2: 12.250 ops/ms
# Warmup Iteration   3: 12.557 ops/ms
Iteration   1: 12.881 ops/ms
Iteration   2: 12.994 ops/ms
Iteration   3: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.946 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (12.881, 12.946, 12.994), stdev = 0.059
  CI (99.9%): [11.873, 14.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ops/ms
# Warmup Iteration   2: 13.236 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.155 ops/ms
Iteration   2: 13.216 ops/ms
Iteration   3: 12.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.120 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (12.988, 13.120, 13.216), stdev = 0.118
  CI (99.9%): [10.965, 15.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.048 ops/ms
# Warmup Iteration   2: 12.743 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.995 ±(99.9%) 0.314 ops/ms [Average]
  (min, avg, max) = (12.984, 12.995, 13.015), stdev = 0.017
  CI (99.9%): [12.681, 13.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.629 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (10.564, 10.629, 10.688), stdev = 0.062
  CI (99.9%): [9.500, 11.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.493, 2.508, 2.528), stdev = 0.018
  CI (99.9%): [2.184, 2.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.004 ms/op
Iteration   2: 2.400 ±(99.9%) 0.003 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.413 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.400, 2.413, 2.423), stdev = 0.012
  CI (99.9%): [2.202, 2.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
Iteration   3: 2.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.451 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.438, 2.451, 2.467), stdev = 0.015
  CI (99.9%): [2.182, 2.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.975, 2.996, 3.025), stdev = 0.026
  CI (99.9%): [2.524, 3.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.763 ms/op
                 createUser·p0.999:  11.171 ms/op
                 createUser·p0.9999: 14.077 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.180 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  7.965 ms/op
                 createUser·p0.9999: 9.601 ms/op
                 createUser·p1.00:   9.765 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383233
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 184993 
    [ 2.500,  3.750) = 194419 
    [ 3.750,  5.000) = 3055 
    [ 5.000,  6.250) = 296 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.975 ms/op
     p(99.9900) =     13.020 ms/op
     p(99.9990) =     14.194 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
Iteration   1: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.161 ms/op
                 existUser·p0.9999: 13.496 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  7.215 ms/op
                 existUser·p0.9999: 13.366 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.652 ms/op
                 existUser·p0.999:  8.560 ms/op
                 existUser·p0.9999: 11.202 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397291
  mean =      2.415 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 201370 
    [ 2.500,  3.750) = 193021 
    [ 3.750,  5.000) = 2006 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =      7.821 ms/op
     p(99.9900) =     13.292 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  6.626 ms/op
                 getUser·p0.9999: 14.056 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 13.323 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.239 ms/op
                 getUser·p0.9999: 10.895 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388276
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 193911 
    [ 2.500,  3.750) = 189630 
    [ 3.750,  5.000) = 3306 
    [ 5.000,  6.250) = 945 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      6.529 ms/op
     p(99.9900) =     13.372 ms/op
     p(99.9990) =     14.526 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.585 ms/op
                 listUser·p0.9999: 10.738 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.366 ms/op
                 listUser·p0.9999: 11.229 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.481 ms/op
                 listUser·p0.999:  9.144 ms/op
                 listUser·p0.9999: 12.371 ms/op
                 listUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318202
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 91128 
    [ 2.500,  3.750) = 186763 
    [ 3.750,  5.000) = 32995 
    [ 5.000,  6.250) = 5938 
    [ 6.250,  7.500) = 611 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.008 ms/op
     p(99.9900) =     11.363 ms/op
     p(99.9990) =     12.922 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.946 ± 1.073  ops/ms
ClientPb.existUser                       thrpt       3  13.120 ± 2.155  ops/ms
ClientPb.getUser                         thrpt       3  12.995 ± 0.314  ops/ms
ClientPb.listUser                        thrpt       3  10.629 ± 1.130  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.324   ms/op
ClientPb.existUser                        avgt       3   2.413 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.451 ± 0.269   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.472   ms/op
ClientPb.createUser                     sample  383233   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.763           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.020           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  397291   2.415 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.521           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.821           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.292           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  388276   2.470 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.529           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.372           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  318202   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.826           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
