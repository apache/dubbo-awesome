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
# Warmup Iteration   1: 4.233 ops/ms
# Warmup Iteration   2: 12.073 ops/ms
# Warmup Iteration   3: 12.109 ops/ms
Iteration   1: 12.608 ops/ms
Iteration   2: 12.483 ops/ms
Iteration   3: 12.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.560 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (12.483, 12.560, 12.608), stdev = 0.067
  CI (99.9%): [11.332, 13.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.897 ops/ms
# Warmup Iteration   2: 12.745 ops/ms
# Warmup Iteration   3: 12.803 ops/ms
Iteration   1: 12.863 ops/ms
Iteration   2: 12.947 ops/ms
Iteration   3: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.886 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (12.848, 12.886, 12.947), stdev = 0.053
  CI (99.9%): [11.911, 13.860] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 12.608 ops/ms
# Warmup Iteration   3: 12.709 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.675 ±(99.9%) 3.505 ops/ms [Average]
  (min, avg, max) = (12.453, 12.675, 12.788), stdev = 0.192
  CI (99.9%): [9.169, 16.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.836 ops/ms
# Warmup Iteration   2: 10.556 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.563 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (10.504, 10.563, 10.627), stdev = 0.062
  CI (99.9%): [9.438, 11.687] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
Iteration   1: 2.628 ±(99.9%) 0.004 ms/op
Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.583 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (2.552, 2.583, 2.628), stdev = 0.040
  CI (99.9%): [1.854, 3.313] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.442, 2.453, 2.462), stdev = 0.010
  CI (99.9%): [2.274, 2.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.496, 2.518, 2.537), stdev = 0.021
  CI (99.9%): [2.142, 2.894] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
Iteration   3: 2.996 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.996, 3.000, 3.006), stdev = 0.005
  CI (99.9%): [2.908, 3.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  12.173 ms/op
                 createUser·p0.9999: 13.711 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 11.600 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.836 ms/op
                 createUser·p0.999:  8.182 ms/op
                 createUser·p0.9999: 9.935 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379644
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 181097 
    [ 2.500,  3.750) = 193898 
    [ 3.750,  5.000) = 3736 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.290 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  7.721 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.069 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  6.286 ms/op
                 existUser·p0.9999: 11.338 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389694
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 188842 
    [ 2.500,  3.750) = 197313 
    [ 3.750,  5.000) = 2600 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.400 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.176 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 13.419 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.230 ms/op
                 getUser·p0.9999: 13.196 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  8.297 ms/op
                 getUser·p0.9999: 11.621 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380307
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 185613 
    [ 2.500,  3.750) = 188201 
    [ 3.750,  5.000) = 5040 
    [ 5.000,  6.250) = 967 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.275 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.789 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.560 ms/op
                 listUser·p0.9999: 10.672 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.777 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314636
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 86184 
    [ 2.500,  3.750) = 187613 
    [ 3.750,  5.000) = 32910 
    [ 5.000,  6.250) = 6166 
    [ 6.250,  7.500) = 937 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.527 ms/op
     p(99.9990) =     12.199 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.560 ± 1.228  ops/ms
ClientPb.existUser                       thrpt       3  12.886 ± 0.975  ops/ms
ClientPb.getUser                         thrpt       3  12.675 ± 3.505  ops/ms
ClientPb.listUser                        thrpt       3  10.563 ± 1.124  ops/ms
ClientPb.createUser                       avgt       3   2.583 ± 0.729   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.376   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.092   ms/op
ClientPb.createUser                     sample  379644   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.755           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.809           ms/op
ClientPb.existUser                      sample  389694   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  380307   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.275           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.222           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.204           ms/op
ClientPb.listUser                       sample  314636   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.796           ms/op
