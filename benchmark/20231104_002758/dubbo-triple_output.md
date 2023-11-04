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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 8.439 ops/ms
Iteration   1: 9.037 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.168 ±(99.9%) 2.350 ops/ms [Average]
  (min, avg, max) = (9.037, 9.168, 9.294), stdev = 0.129
  CI (99.9%): [6.818, 11.518] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ops/ms
# Warmup Iteration   2: 9.155 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.762 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.639 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (9.563, 9.639, 9.762), stdev = 0.108
  CI (99.9%): [7.677, 11.601] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 8.257 ops/ms
# Warmup Iteration   3: 8.914 ops/ms
Iteration   1: 9.250 ops/ms
Iteration   2: 9.179 ops/ms
Iteration   3: 9.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.238 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (9.179, 9.238, 9.284), stdev = 0.054
  CI (99.9%): [8.260, 10.215] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 7.218 ops/ms
# Warmup Iteration   3: 7.803 ops/ms
Iteration   1: 7.750 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 7.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.749 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (7.640, 7.749, 7.857), stdev = 0.109
  CI (99.9%): [5.769, 9.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.353 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.003 ms/op
Iteration   1: 3.612 ±(99.9%) 0.004 ms/op
Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
Iteration   3: 3.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.532 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.464, 3.532, 3.612), stdev = 0.075
  CI (99.9%): [2.171, 4.894] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.003 ms/op
Iteration   1: 3.447 ±(99.9%) 0.005 ms/op
Iteration   2: 3.349 ±(99.9%) 0.004 ms/op
Iteration   3: 3.344 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 1.060 ms/op [Average]
  (min, avg, max) = (3.344, 3.380, 3.447), stdev = 0.058
  CI (99.9%): [2.320, 4.440] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.968 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.003 ms/op
Iteration   1: 3.659 ±(99.9%) 0.002 ms/op
Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
Iteration   3: 3.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.523 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (3.435, 3.523, 3.659), stdev = 0.119
  CI (99.9%): [1.348, 5.698] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.591 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.006 ms/op
Iteration   1: 4.085 ±(99.9%) 0.010 ms/op
Iteration   2: 4.108 ±(99.9%) 0.006 ms/op
Iteration   3: 4.136 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.109 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (4.085, 4.109, 4.136), stdev = 0.026
  CI (99.9%): [3.643, 4.576] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.279 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.011 ms/op
Iteration   1: 3.516 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  20.419 ms/op
                 createUser·p0.9999: 22.902 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  22.276 ms/op
                 createUser·p0.9999: 25.446 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.615 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  14.328 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270511
  mean =      3.547 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4766 
    [ 2.500,  5.000) = 260147 
    [ 5.000,  7.500) = 4673 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.889 ms/op
     p(99.9000) =     15.933 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     26.538 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.745 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.346 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  12.396 ms/op
                 existUser·p0.9999: 21.196 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 24.632 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 3.325 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.633 ms/op
                 existUser·p0.999:  16.675 ms/op
                 existUser·p0.9999: 26.915 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284777
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7318 
    [ 2.500,  5.000) = 272237 
    [ 5.000,  7.500) = 4433 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.816 ms/op
     p(99.9900) =     25.314 ms/op
     p(99.9990) =     27.923 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.066 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.011 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  19.734 ms/op
                 getUser·p0.9999: 22.241 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   2: 3.467 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.994 ms/op
                 getUser·p0.999:  21.725 ms/op
                 getUser·p0.9999: 24.798 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.442 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  18.124 ms/op
                 getUser·p0.9999: 26.696 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277821
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2180 
    [ 2.500,  5.000) = 269569 
    [ 5.000,  7.500) = 5057 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     18.630 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 9.723 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.143 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 22.637 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 4.119 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.051 ms/op
                 listUser·p0.999:  14.915 ms/op
                 listUser·p0.9999: 16.785 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 4.136 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.609 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232222
  mean =      4.133 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 224345 
    [ 5.000,  7.500) = 6257 
    [ 7.500, 10.000) = 985 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.201 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     22.949 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.168 ± 2.350  ops/ms
ClientPb.existUser                       thrpt       3   9.639 ± 1.962  ops/ms
ClientPb.getUser                         thrpt       3   9.238 ± 0.977  ops/ms
ClientPb.listUser                        thrpt       3   7.749 ± 1.980  ops/ms
ClientPb.createUser                       avgt       3   3.532 ± 1.362   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 1.060   ms/op
ClientPb.getUser                          avgt       3   3.523 ± 2.175   ms/op
ClientPb.listUser                         avgt       3   4.109 ± 0.467   ms/op
ClientPb.createUser                     sample  270511   3.547 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.933           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.347           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.739           ms/op
ClientPb.existUser                      sample  284777   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  277821   3.455 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.630           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.100           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  232222   4.133 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.201           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.922           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.790           ms/op
