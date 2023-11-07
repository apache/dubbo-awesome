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
# Warmup Iteration   1: 2.053 ops/ms
# Warmup Iteration   2: 5.644 ops/ms
# Warmup Iteration   3: 8.607 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.351 ops/ms
Iteration   3: 9.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.373 ±(99.9%) 0.395 ops/ms [Average]
  (min, avg, max) = (9.351, 9.373, 9.394), stdev = 0.022
  CI (99.9%): [8.978, 9.767] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.156 ops/ms
# Warmup Iteration   2: 9.108 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.582 ops/ms
Iteration   2: 9.555 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.687 ±(99.9%) 3.739 ops/ms [Average]
  (min, avg, max) = (9.555, 9.687, 9.923), stdev = 0.205
  CI (99.9%): [5.948, 13.426] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ops/ms
# Warmup Iteration   2: 8.552 ops/ms
# Warmup Iteration   3: 9.165 ops/ms
Iteration   1: 9.304 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.291 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (9.236, 9.291, 9.333), stdev = 0.050
  CI (99.9%): [8.379, 10.203] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 6.994 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 7.772 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.909 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (7.772, 7.909, 8.013), stdev = 0.124
  CI (99.9%): [5.651, 10.167] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.652 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.004 ms/op
Iteration   1: 3.456 ±(99.9%) 0.006 ms/op
Iteration   2: 3.545 ±(99.9%) 0.006 ms/op
Iteration   3: 3.461 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.488 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.456, 3.488, 3.545), stdev = 0.050
  CI (99.9%): [2.573, 4.402] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.692 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.004 ms/op
Iteration   1: 3.362 ±(99.9%) 0.002 ms/op
Iteration   2: 3.303 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.343 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.303, 3.343, 3.364), stdev = 0.034
  CI (99.9%): [2.716, 3.970] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.129 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.006 ms/op
Iteration   1: 3.512 ±(99.9%) 0.006 ms/op
Iteration   2: 3.414 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.414, 3.456, 3.512), stdev = 0.050
  CI (99.9%): [2.535, 4.377] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.521 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.004 ms/op
Iteration   1: 4.151 ±(99.9%) 0.006 ms/op
Iteration   2: 4.028 ±(99.9%) 0.006 ms/op
Iteration   3: 4.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.101 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (4.028, 4.101, 4.151), stdev = 0.065
  CI (99.9%): [2.922, 5.280] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.889 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.573 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  12.173 ms/op
                 createUser·p0.9999: 22.202 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  23.019 ms/op
                 createUser·p0.9999: 26.408 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.513 ms/op
                 createUser·p0.9999: 26.939 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271799
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2944 
    [ 2.500,  5.000) = 262249 
    [ 5.000,  7.500) = 5057 
    [ 7.500, 10.000) = 909 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     15.145 ms/op
     p(99.9900) =     26.340 ms/op
     p(99.9990) =     27.960 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.529 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
Iteration   1: 3.309 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  18.837 ms/op
                 existUser·p0.9999: 22.261 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  21.211 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   6.056 ms/op
                 existUser·p0.999:  19.366 ms/op
                 existUser·p0.9999: 26.290 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288850
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4232 
    [ 2.500,  5.000) = 279947 
    [ 5.000,  7.500) = 3552 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.170 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.048 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.581 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  18.879 ms/op
                 getUser·p0.9999: 21.991 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  21.619 ms/op
                 getUser·p0.9999: 24.405 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.559 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  12.717 ms/op
                 getUser·p0.9999: 23.758 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271412
  mean =      3.537 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3783 
    [ 2.500,  5.000) = 260437 
    [ 5.000,  7.500) = 6053 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     23.813 ms/op
     p(99.9990) =     24.716 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.190 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.012 ms/op
Iteration   1: 4.206 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  17.263 ms/op
                 listUser·p0.9999: 23.933 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.121 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.956 ms/op
                 listUser·p0.9999: 16.237 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 4.141 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.527 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 14.980 ms/op
                 listUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230840
  mean =      4.156 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 222713 
    [ 5.000,  7.500) = 6177 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     22.017 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.373 ± 0.395  ops/ms
ClientPb.existUser                       thrpt       3   9.687 ± 3.739  ops/ms
ClientPb.getUser                         thrpt       3   9.291 ± 0.912  ops/ms
ClientPb.listUser                        thrpt       3   7.909 ± 2.258  ops/ms
ClientPb.createUser                       avgt       3   3.488 ± 0.914   ms/op
ClientPb.existUser                        avgt       3   3.343 ± 0.627   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 0.921   ms/op
ClientPb.listUser                         avgt       3   4.101 ± 1.179   ms/op
ClientPb.createUser                     sample  271799   3.528 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.145           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.340           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  288850   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.366           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.170           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.296           ms/op
ClientPb.getUser                        sample  271412   3.537 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.813           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  230840   4.156 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.017           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
