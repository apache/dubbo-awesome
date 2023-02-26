# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.033 ops/ms
# Warmup Iteration   2: 5.485 ops/ms
# Warmup Iteration   3: 8.656 ops/ms
Iteration   1: 9.136 ops/ms
Iteration   2: 9.232 ops/ms
Iteration   3: 9.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.215 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (9.136, 9.215, 9.275), stdev = 0.071
  CI (99.9%): [7.916, 10.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.085 ops/ms
# Warmup Iteration   2: 8.735 ops/ms
# Warmup Iteration   3: 9.386 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.825 ops/ms
Iteration   3: 9.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.796 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (9.743, 9.796, 9.825), stdev = 0.046
  CI (99.9%): [8.951, 10.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.814 ops/ms
# Warmup Iteration   2: 8.296 ops/ms
# Warmup Iteration   3: 8.940 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.631 ops/ms
Iteration   3: 8.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.281 ±(99.9%) 6.173 ops/ms [Average]
  (min, avg, max) = (8.955, 9.281, 9.631), stdev = 0.338
  CI (99.9%): [3.108, 15.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.700 ops/ms
# Warmup Iteration   2: 7.082 ops/ms
# Warmup Iteration   3: 7.846 ops/ms
Iteration   1: 7.899 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.171 ±(99.9%) 5.117 ops/ms [Average]
  (min, avg, max) = (7.899, 8.171, 8.460), stdev = 0.280
  CI (99.9%): [3.054, 13.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.107 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.008 ms/op
Iteration   1: 3.447 ±(99.9%) 0.006 ms/op
Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
Iteration   3: 3.522 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.408, 3.459, 3.522), stdev = 0.058
  CI (99.9%): [2.407, 4.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.789 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.005 ms/op
Iteration   1: 3.248 ±(99.9%) 0.011 ms/op
Iteration   2: 3.242 ±(99.9%) 0.007 ms/op
Iteration   3: 3.496 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 2.638 ms/op [Average]
  (min, avg, max) = (3.242, 3.329, 3.496), stdev = 0.145
  CI (99.9%): [0.691, 5.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.227 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
Iteration   1: 3.467 ±(99.9%) 0.007 ms/op
Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
Iteration   3: 3.378 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.409 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.378, 3.409, 3.467), stdev = 0.051
  CI (99.9%): [2.487, 4.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.103 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.008 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
Iteration   2: 3.978 ±(99.9%) 0.011 ms/op
Iteration   3: 4.076 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (3.973, 4.009, 4.076), stdev = 0.058
  CI (99.9%): [2.954, 5.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.060 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  20.059 ms/op
                 createUser·p0.9999: 22.332 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 25.414 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.386 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  16.813 ms/op
                 createUser·p0.9999: 24.303 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283780
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15825 
    [ 2.500,  5.000) = 262505 
    [ 5.000,  7.500) = 4622 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.225 ms/op
     p(99.9900) =     24.433 ms/op
     p(99.9990) =     26.285 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.431 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  17.054 ms/op
                 existUser·p0.9999: 22.569 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.882 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  20.939 ms/op
                 existUser·p0.9999: 26.522 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.319 ms/op
                 existUser·p0.9999: 25.414 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285835
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10644 
    [ 2.500,  5.000) = 269001 
    [ 5.000,  7.500) = 5166 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     16.985 ms/op
     p(99.9900) =     25.226 ms/op
     p(99.9990) =     26.809 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.252 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
Iteration   1: 3.548 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   5.369 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  15.686 ms/op
                 getUser·p0.9999: 23.094 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  20.545 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 3.471 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.207 ms/op
                 getUser·p0.999:  20.505 ms/op
                 getUser·p0.9999: 40.042 ms/op
                 getUser·p1.00:   41.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277233
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267914 
    [ 5.000, 10.000) = 8834 
    [10.000, 15.000) = 196 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 181 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     41.070 ms/op
     p(99.9999) =     41.222 ms/op
    p(100.0000) =     41.222 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.930 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.013 ms/op
Iteration   1: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  19.892 ms/op
                 listUser·p0.9999: 21.801 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 18.849 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.335 ms/op
                 listUser·p0.999:  16.642 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234980
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 223775 
    [ 5.000,  7.500) = 8790 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     21.447 ms/op
     p(99.9990) =     24.483 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.215 ± 1.299  ops/ms
ClientPb.existUser                       thrpt       3   9.796 ± 0.846  ops/ms
ClientPb.getUser                         thrpt       3   9.281 ± 6.173  ops/ms
ClientPb.listUser                        thrpt       3   8.171 ± 5.117  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 1.052   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 2.638   ms/op
ClientPb.getUser                          avgt       3   3.409 ± 0.922   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 1.055   ms/op
ClientPb.createUser                     sample  283780   3.380 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.483           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.225           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.433           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  285835   3.355 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.985           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  277233   3.463 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.794           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.470           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.222           ms/op
ClientPb.listUser                       sample  234980   4.085 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.433           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
