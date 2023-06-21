# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.965 ops/ms
# Warmup Iteration   2: 4.813 ops/ms
# Warmup Iteration   3: 8.282 ops/ms
Iteration   1: 8.919 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.201 ±(99.9%) 4.672 ops/ms [Average]
  (min, avg, max) = (8.919, 9.201, 9.418), stdev = 0.256
  CI (99.9%): [4.529, 13.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.810 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 9.063 ops/ms
Iteration   1: 9.571 ops/ms
Iteration   2: 9.662 ops/ms
Iteration   3: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.516 ±(99.9%) 3.274 ops/ms [Average]
  (min, avg, max) = (9.316, 9.516, 9.662), stdev = 0.179
  CI (99.9%): [6.243, 12.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.808 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 8.822 ops/ms
Iteration   1: 8.821 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.071 ±(99.9%) 3.991 ops/ms [Average]
  (min, avg, max) = (8.821, 9.071, 9.228), stdev = 0.219
  CI (99.9%): [5.080, 13.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 6.508 ops/ms
# Warmup Iteration   3: 7.661 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 7.530 ops/ms
Iteration   3: 7.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.722 ±(99.9%) 3.614 ops/ms [Average]
  (min, avg, max) = (7.530, 7.722, 7.926), stdev = 0.198
  CI (99.9%): [4.107, 11.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.524 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.012 ms/op
Iteration   1: 3.576 ±(99.9%) 0.007 ms/op
Iteration   2: 3.434 ±(99.9%) 0.006 ms/op
Iteration   3: 3.477 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.496 ±(99.9%) 1.320 ms/op [Average]
  (min, avg, max) = (3.434, 3.496, 3.576), stdev = 0.072
  CI (99.9%): [2.175, 4.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.916 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.005 ms/op
Iteration   1: 3.360 ±(99.9%) 0.009 ms/op
Iteration   2: 3.348 ±(99.9%) 0.004 ms/op
Iteration   3: 3.444 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.384 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.348, 3.384, 3.444), stdev = 0.052
  CI (99.9%): [2.432, 4.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.516 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.006 ms/op
Iteration   1: 3.410 ±(99.9%) 0.003 ms/op
Iteration   2: 3.497 ±(99.9%) 0.009 ms/op
Iteration   3: 3.551 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.410, 3.486, 3.551), stdev = 0.071
  CI (99.9%): [2.190, 4.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.818 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.008 ms/op
Iteration   1: 4.000 ±(99.9%) 0.011 ms/op
Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
Iteration   3: 4.044 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.031 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (4.000, 4.031, 4.049), stdev = 0.027
  CI (99.9%): [3.540, 4.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.610 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.014 ms/op
Iteration   1: 3.542 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.112 ms/op
                 createUser·p0.999:  19.052 ms/op
                 createUser·p0.9999: 22.508 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  20.874 ms/op
                 createUser·p0.9999: 24.049 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.507 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  21.740 ms/op
                 createUser·p0.9999: 30.044 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272522
  mean =      3.524 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7511 
    [ 2.500,  5.000) = 256732 
    [ 5.000,  7.500) = 7087 
    [ 7.500, 10.000) = 738 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     20.035 ms/op
     p(99.9900) =     28.942 ms/op
     p(99.9990) =     30.475 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.711 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
Iteration   1: 3.408 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 22.191 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.419 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  21.248 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  15.184 ms/op
                 existUser·p0.9999: 28.158 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284160
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17325 
    [ 2.500,  5.000) = 261203 
    [ 5.000,  7.500) = 4880 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     27.282 ms/op
     p(99.9990) =     28.952 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.614 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.921 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.013 ms/op
Iteration   1: 3.585 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 26.028 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 3.506 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 26.686 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.579 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  23.986 ms/op
                 getUser·p0.9999: 43.713 ms/op
                 getUser·p1.00:   46.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269868
  mean =      3.556 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 260330 
    [ 5.000, 10.000) = 9123 
    [10.000, 15.000) = 153 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 119 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.100 ms/op
     p(99.9900) =     42.598 ms/op
     p(99.9990) =     46.419 ms/op
     p(99.9999) =     46.531 ms/op
    p(100.0000) =     46.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.469 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.013 ms/op
Iteration   1: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  21.265 ms/op
                 listUser·p0.9999: 25.972 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.245 ms/op
                 listUser·p0.999:  15.821 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 4.199 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  17.296 ms/op
                 listUser·p0.9999: 24.536 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231369
  mean =      4.147 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 222797 
    [ 5.000,  7.500) = 6050 
    [ 7.500, 10.000) = 1693 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     16.950 ms/op
     p(99.9900) =     25.059 ms/op
     p(99.9990) =     26.237 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.201 ± 4.672  ops/ms
ClientPb.existUser                       thrpt       3   9.516 ± 3.274  ops/ms
ClientPb.getUser                         thrpt       3   9.071 ± 3.991  ops/ms
ClientPb.listUser                        thrpt       3   7.722 ± 3.614  ops/ms
ClientPb.createUser                       avgt       3   3.496 ± 1.320   ms/op
ClientPb.existUser                        avgt       3   3.384 ± 0.952   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 1.296   ms/op
ClientPb.listUser                         avgt       3   4.031 ± 0.491   ms/op
ClientPb.createUser                     sample  272522   3.524 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.035           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.942           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.064           ms/op
ClientPb.existUser                      sample  284160   3.375 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.184           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  269868   3.556 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.413           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.100           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.531           ms/op
ClientPb.listUser                       sample  231369   4.147 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.542           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.950           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
