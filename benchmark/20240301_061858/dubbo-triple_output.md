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
# Warmup Iteration   1: 4.993 ops/ms
# Warmup Iteration   2: 12.278 ops/ms
# Warmup Iteration   3: 12.362 ops/ms
Iteration   1: 12.512 ops/ms
Iteration   2: 12.469 ops/ms
Iteration   3: 12.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.503 ±(99.9%) 0.560 ops/ms [Average]
  (min, avg, max) = (12.469, 12.503, 12.529), stdev = 0.031
  CI (99.9%): [11.943, 13.064] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.203 ops/ms
# Warmup Iteration   2: 13.181 ops/ms
# Warmup Iteration   3: 13.543 ops/ms
Iteration   1: 13.632 ops/ms
Iteration   2: 13.576 ops/ms
Iteration   3: 13.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.543 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (13.421, 13.543, 13.632), stdev = 0.110
  CI (99.9%): [11.544, 15.542] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.886 ops/ms
# Warmup Iteration   2: 12.731 ops/ms
# Warmup Iteration   3: 12.995 ops/ms
Iteration   1: 12.923 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 13.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.899 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (12.739, 12.899, 13.035), stdev = 0.150
  CI (99.9%): [10.170, 15.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.708 ops/ms
# Warmup Iteration   2: 10.757 ops/ms
# Warmup Iteration   3: 10.734 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.864 ops/ms
Iteration   3: 10.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.879 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (10.802, 10.879, 10.970), stdev = 0.085
  CI (99.9%): [9.329, 12.429] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.009 ms/op
Iteration   1: 2.489 ±(99.9%) 0.011 ms/op
Iteration   2: 2.429 ±(99.9%) 0.010 ms/op
Iteration   3: 2.495 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (2.429, 2.471, 2.495), stdev = 0.036
  CI (99.9%): [1.805, 3.137] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
Iteration   2: 2.363 ±(99.9%) 0.005 ms/op
Iteration   3: 2.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.394 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.363, 2.394, 2.419), stdev = 0.029
  CI (99.9%): [1.874, 2.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.006 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (2.462, 2.487, 2.505), stdev = 0.022
  CI (99.9%): [2.084, 2.889] (assumes normal distribution)


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
Iteration   1: 2.891 ±(99.9%) 0.011 ms/op
Iteration   2: 2.870 ±(99.9%) 0.011 ms/op
Iteration   3: 2.841 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.867 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.841, 2.867, 2.891), stdev = 0.025
  CI (99.9%): [2.408, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.006 ms/op
Iteration   1: 2.428 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.363 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.139 ms/op
                 createUser·p0.9999: 14.524 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 2.387 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.322 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 12.789 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.445 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.143 ms/op
                 createUser·p0.999:  7.594 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394282
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 299 
    [ 1.250,  2.500) = 221788 
    [ 2.500,  3.750) = 164710 
    [ 3.750,  5.000) = 6546 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      7.050 ms/op
     p(99.9900) =     13.706 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.450 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.352 ±(99.9%) 0.006 ms/op
Iteration   1: 2.281 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.249 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  5.430 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.347 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.290 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  6.966 ms/op
                 existUser·p0.9999: 16.413 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   3: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.351 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  8.936 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 410812
  mean =      2.334 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 307 
    [ 1.250,  2.500) = 252927 
    [ 2.500,  3.750) = 152549 
    [ 3.750,  5.000) = 4202 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     17.950 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  11.954 ms/op
                 getUser·p0.9999: 14.291 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.766 ms/op
                 getUser·p0.9999: 14.709 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   3: 2.569 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.366 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.232 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  9.709 ms/op
                 getUser·p0.9999: 12.470 ms/op
                 getUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378700
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 234 
    [ 1.250,  2.500) = 190320 
    [ 2.500,  3.750) = 179017 
    [ 3.750,  5.000) = 7059 
    [ 5.000,  6.250) = 1172 
    [ 6.250,  7.500) = 420 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.721 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     15.682 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.011 ms/op
Iteration   1: 3.067 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.616 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  10.617 ms/op
                 listUser·p0.9999: 19.034 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 3.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.394 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.177 ms/op
                 listUser·p0.999:  12.435 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 2.940 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.373 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  10.998 ms/op
                 listUser·p0.9999: 14.201 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318398
  mean =      3.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111994 
    [ 2.500,  5.000) = 196147 
    [ 5.000,  7.500) = 9098 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.827 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.503 ± 0.560  ops/ms
ClientPb.existUser                       thrpt       3  13.543 ± 1.999  ops/ms
ClientPb.getUser                         thrpt       3  12.899 ± 2.729  ops/ms
ClientPb.listUser                        thrpt       3  10.879 ± 1.550  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.666   ms/op
ClientPb.existUser                        avgt       3   2.394 ± 0.520   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.403   ms/op
ClientPb.listUser                         avgt       3   2.867 ± 0.460   ms/op
ClientPb.createUser                     sample  394282   2.433 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.610           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.050           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.706           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.516           ms/op
ClientPb.existUser                      sample  410812   2.334 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.667           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.286           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.406           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.743           ms/op
ClientPb.getUser                        sample  378700   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.366           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.721           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.336           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.187           ms/op
ClientPb.listUser                       sample  318398   3.013 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.373           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.502           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
