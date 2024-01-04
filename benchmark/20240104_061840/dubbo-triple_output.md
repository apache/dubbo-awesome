# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.027 ops/ms
# Warmup Iteration   2: 11.750 ops/ms
# Warmup Iteration   3: 12.244 ops/ms
Iteration   1: 12.386 ops/ms
Iteration   2: 12.470 ops/ms
Iteration   3: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.440 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (12.386, 12.440, 12.470), stdev = 0.047
  CI (99.9%): [11.575, 13.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.998 ops/ms
# Warmup Iteration   2: 12.875 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.905 ops/ms
Iteration   2: 12.859 ops/ms
Iteration   3: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.902 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (12.859, 12.902, 12.940), stdev = 0.041
  CI (99.9%): [12.162, 13.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 12.368 ops/ms
# Warmup Iteration   3: 12.586 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.626 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (12.549, 12.626, 12.680), stdev = 0.069
  CI (99.9%): [11.376, 13.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.573 ops/ms
# Warmup Iteration   2: 10.377 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.652 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (10.616, 10.652, 10.693), stdev = 0.038
  CI (99.9%): [9.951, 11.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.511, 2.528, 2.545), stdev = 0.017
  CI (99.9%): [2.217, 2.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.460, 2.476, 2.502), stdev = 0.023
  CI (99.9%): [2.057, 2.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
Iteration   3: 2.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.515, 2.524, 2.539), stdev = 0.013
  CI (99.9%): [2.279, 2.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (3.029, 3.036, 3.041), stdev = 0.006
  CI (99.9%): [2.924, 3.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  11.966 ms/op
                 createUser·p0.9999: 14.257 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  6.817 ms/op
                 createUser·p0.9999: 11.422 ms/op
                 createUser·p1.00:   12.141 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 10.973 ms/op
                 createUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384333
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 186647 
    [ 2.500,  3.750) = 193199 
    [ 3.750,  5.000) = 3417 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.376 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  9.965 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.088 ms/op
                 existUser·p0.9999: 12.682 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.913 ms/op
                 existUser·p0.999:  8.323 ms/op
                 existUser·p0.9999: 11.103 ms/op
                 existUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386215
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 189887 
    [ 2.500,  3.750) = 192648 
    [ 3.750,  5.000) = 2800 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.900 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.390 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 13.098 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  8.417 ms/op
                 getUser·p0.9999: 11.790 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376072
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 182297 
    [ 2.500,  3.750) = 189000 
    [ 3.750,  5.000) = 3637 
    [ 5.000,  6.250) = 681 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      7.241 ms/op
     p(99.9900) =     13.458 ms/op
     p(99.9990) =     13.930 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.622 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.451 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319516
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 92323 
    [ 2.500,  3.750) = 188574 
    [ 3.750,  5.000) = 31829 
    [ 5.000,  6.250) = 5418 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     11.797 ms/op
     p(99.9990) =     12.660 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.440 ± 0.865  ops/ms
ClientPb.existUser                       thrpt       3  12.902 ± 0.739  ops/ms
ClientPb.getUser                         thrpt       3  12.626 ± 1.251  ops/ms
ClientPb.listUser                        thrpt       3  10.652 ± 0.702  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.419   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.246   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.111   ms/op
ClientPb.createUser                     sample  384333   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.006           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.487           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.533           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  386215   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.800           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.438           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  376072   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.791           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.458           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  319516   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.777           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.797           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
