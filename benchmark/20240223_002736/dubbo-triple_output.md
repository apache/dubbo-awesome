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
# Warmup Iteration   1: 4.688 ops/ms
# Warmup Iteration   2: 12.065 ops/ms
# Warmup Iteration   3: 12.144 ops/ms
Iteration   1: 12.291 ops/ms
Iteration   2: 12.362 ops/ms
Iteration   3: 12.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.384 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (12.291, 12.384, 12.499), stdev = 0.106
  CI (99.9%): [10.455, 14.312] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.971 ops/ms
# Warmup Iteration   2: 12.678 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 12.993 ops/ms
Iteration   2: 13.147 ops/ms
Iteration   3: 13.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.060 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (12.993, 13.060, 13.147), stdev = 0.079
  CI (99.9%): [11.626, 14.494] (assumes normal distribution)


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
# Warmup Iteration   1: 7.529 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.844 ops/ms
Iteration   1: 12.609 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (12.609, 12.689, 12.779), stdev = 0.086
  CI (99.9%): [11.128, 14.251] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.531 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.663 ±(99.9%) 0.428 ops/ms [Average]
  (min, avg, max) = (10.637, 10.663, 10.683), stdev = 0.023
  CI (99.9%): [10.235, 11.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.565 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.531, 2.544, 2.565), stdev = 0.019
  CI (99.9%): [2.202, 2.885] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.003 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.459, 2.471, 2.487), stdev = 0.014
  CI (99.9%): [2.209, 2.732] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.512, 2.519, 2.528), stdev = 0.008
  CI (99.9%): [2.367, 2.672] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
Iteration   2: 3.003 ±(99.9%) 0.007 ms/op
Iteration   3: 3.005 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.014 ms/op [Average]
  (min, avg, max) = (3.003, 3.004, 3.005), stdev = 0.001
  CI (99.9%): [2.989, 3.018] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  11.300 ms/op
                 createUser·p0.9999: 13.401 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.601 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 10.533 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375538
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 180219 
    [ 2.500,  3.750) = 191424 
    [ 3.750,  5.000) = 3053 
    [ 5.000,  6.250) = 345 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.789 ms/op
     p(99.9900) =     12.836 ms/op
     p(99.9990) =     13.799 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  6.276 ms/op
                 existUser·p0.9999: 15.952 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.930 ms/op
                 existUser·p0.9999: 12.985 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  8.627 ms/op
                 existUser·p0.9999: 11.584 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391755
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 192558 
    [ 2.500,  3.750) = 195803 
    [ 3.750,  5.000) = 2519 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.589 ms/op
     p(99.9900) =     14.120 ms/op
     p(99.9990) =     16.160 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  5.283 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.590 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  9.725 ms/op
                 getUser·p0.9999: 13.364 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 12.119 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377213
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 182621 
    [ 2.500,  3.750) = 188640 
    [ 3.750,  5.000) = 4516 
    [ 5.000,  6.250) = 826 
    [ 6.250,  7.500) = 143 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.120 ms/op
     p(99.9000) =      8.614 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.482 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.727 ms/op
                 listUser·p0.9999: 12.971 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 12.660 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.278 ms/op
                 listUser·p0.9999: 10.981 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311046
  mean =      3.083 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 80062 
    [ 2.500,  3.750) = 186643 
    [ 3.750,  5.000) = 35571 
    [ 5.000,  6.250) = 7141 
    [ 6.250,  7.500) = 866 
    [ 7.500,  8.750) = 265 
    [ 8.750, 10.000) = 190 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.360 ms/op
     p(99.9990) =     13.562 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.384 ± 1.928  ops/ms
ClientPb.existUser                       thrpt       3  13.060 ± 1.434  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 1.561  ops/ms
ClientPb.listUser                        thrpt       3  10.663 ± 0.428  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.342   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.262   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.014   ms/op
ClientPb.createUser                     sample  375538   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.789           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.836           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.844           ms/op
ClientPb.existUser                      sample  391755   2.448 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.667           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.120           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.302           ms/op
ClientPb.getUser                        sample  377213   2.543 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.120           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.614           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  311046   3.083 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.360           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
