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
# Warmup Iteration   1: 2.229 ops/ms
# Warmup Iteration   2: 6.026 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 9.180 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.248 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (9.180, 9.248, 9.312), stdev = 0.066
  CI (99.9%): [8.041, 10.455] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.699 ops/ms
# Warmup Iteration   2: 8.542 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.582 ops/ms
Iteration   2: 9.657 ops/ms
Iteration   3: 9.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.499 ±(99.9%) 3.869 ops/ms [Average]
  (min, avg, max) = (9.258, 9.499, 9.657), stdev = 0.212
  CI (99.9%): [5.630, 13.368] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 8.527 ops/ms
# Warmup Iteration   3: 8.991 ops/ms
Iteration   1: 8.999 ops/ms
Iteration   2: 8.915 ops/ms
Iteration   3: 9.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.006 ±(99.9%) 1.727 ops/ms [Average]
  (min, avg, max) = (8.915, 9.006, 9.104), stdev = 0.095
  CI (99.9%): [7.279, 10.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 7.170 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 7.785 ops/ms
Iteration   3: 7.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.842 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (7.785, 7.842, 7.917), stdev = 0.068
  CI (99.9%): [6.600, 9.083] (assumes normal distribution)


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
# Warmup Iteration   1: 9.783 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.006 ms/op
Iteration   1: 3.620 ±(99.9%) 0.006 ms/op
Iteration   2: 3.440 ±(99.9%) 0.006 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.504 ±(99.9%) 1.834 ms/op [Average]
  (min, avg, max) = (3.440, 3.504, 3.620), stdev = 0.101
  CI (99.9%): [1.670, 5.339] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.003 ms/op
Iteration   1: 3.415 ±(99.9%) 0.006 ms/op
Iteration   2: 3.316 ±(99.9%) 0.006 ms/op
Iteration   3: 3.386 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.316, 3.372, 3.415), stdev = 0.051
  CI (99.9%): [2.441, 4.304] (assumes normal distribution)


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
# Warmup Iteration   1: 9.248 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.003 ms/op
Iteration   1: 3.536 ±(99.9%) 0.004 ms/op
Iteration   2: 3.516 ±(99.9%) 0.007 ms/op
Iteration   3: 3.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.511 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.481, 3.511, 3.536), stdev = 0.028
  CI (99.9%): [3.005, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 11.117 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.006 ms/op
Iteration   1: 4.207 ±(99.9%) 0.004 ms/op
Iteration   2: 4.196 ±(99.9%) 0.006 ms/op
Iteration   3: 4.111 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.172 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (4.111, 4.172, 4.207), stdev = 0.052
  CI (99.9%): [3.214, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 9.471 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.012 ms/op
Iteration   1: 3.551 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  20.477 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.405 ms/op
                 createUser·p0.999:  21.843 ms/op
                 createUser·p0.9999: 25.613 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  18.709 ms/op
                 createUser·p0.9999: 24.232 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276021
  mean =      3.477 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9324 
    [ 2.500,  5.000) = 259235 
    [ 5.000,  7.500) = 5916 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     25.375 ms/op
     p(99.9990) =     26.369 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 8.777 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  11.240 ms/op
                 existUser·p0.9999: 18.264 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   6.243 ms/op
                 existUser·p0.999:  17.918 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.379 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  17.904 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286041
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 274908 
    [ 5.000,  7.500) = 5344 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     16.317 ms/op
     p(99.9900) =     22.635 ms/op
     p(99.9990) =     24.152 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 9.054 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.012 ms/op
Iteration   1: 3.616 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  17.835 ms/op
                 getUser·p0.9999: 22.418 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.514 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  22.246 ms/op
                 getUser·p0.9999: 24.995 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  19.028 ms/op
                 getUser·p0.9999: 39.896 ms/op
                 getUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272123
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262699 
    [ 5.000, 10.000) = 8771 
    [10.000, 15.000) = 307 
    [15.000, 20.000) = 87 
    [20.000, 25.000) = 186 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     19.526 ms/op
     p(99.9900) =     37.997 ms/op
     p(99.9990) =     40.370 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.028 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.012 ms/op
Iteration   1: 4.131 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  22.261 ms/op
                 listUser·p0.9999: 31.326 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   2: 4.238 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  14.247 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 4.201 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  14.940 ms/op
                 listUser·p0.9999: 18.625 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228945
  mean =      4.190 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 217797 
    [ 5.000,  7.500) = 8022 
    [ 7.500, 10.000) = 2143 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     29.043 ms/op
     p(99.9990) =     32.295 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.248 ± 1.207  ops/ms
ClientPb.existUser                       thrpt       3   9.499 ± 3.869  ops/ms
ClientPb.getUser                         thrpt       3   9.006 ± 1.727  ops/ms
ClientPb.listUser                        thrpt       3   7.842 ± 1.241  ops/ms
ClientPb.createUser                       avgt       3   3.504 ± 1.834   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 0.931   ms/op
ClientPb.getUser                          avgt       3   3.511 ± 0.506   ms/op
ClientPb.listUser                         avgt       3   4.172 ± 0.957   ms/op
ClientPb.createUser                     sample  276021   3.477 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.542           ms/op
ClientPb.existUser                      sample  286041   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.317           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.635           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  272123   3.530 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.750           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.997           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.436           ms/op
ClientPb.listUser                       sample  228945   4.190 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.729           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.506           ms/op
