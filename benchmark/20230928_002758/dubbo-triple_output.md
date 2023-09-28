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
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.117 ops/ms
# Warmup Iteration   3: 8.440 ops/ms
Iteration   1: 8.964 ops/ms
Iteration   2: 9.130 ops/ms
Iteration   3: 9.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.114 ±(99.9%) 2.603 ops/ms [Average]
  (min, avg, max) = (8.964, 9.114, 9.248), stdev = 0.143
  CI (99.9%): [6.510, 11.717] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 8.011 ops/ms
# Warmup Iteration   3: 9.376 ops/ms
Iteration   1: 9.427 ops/ms
Iteration   2: 9.723 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.596 ±(99.9%) 2.788 ops/ms [Average]
  (min, avg, max) = (9.427, 9.596, 9.723), stdev = 0.153
  CI (99.9%): [6.809, 12.384] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.698 ops/ms
# Warmup Iteration   2: 8.484 ops/ms
# Warmup Iteration   3: 8.854 ops/ms
Iteration   1: 8.741 ops/ms
Iteration   2: 8.713 ops/ms
Iteration   3: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.862 ±(99.9%) 4.284 ops/ms [Average]
  (min, avg, max) = (8.713, 8.862, 9.133), stdev = 0.235
  CI (99.9%): [4.578, 13.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 6.769 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 7.577 ops/ms
Iteration   2: 7.689 ops/ms
Iteration   3: 7.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.643 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (7.577, 7.643, 7.689), stdev = 0.059
  CI (99.9%): [6.573, 8.713] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.714 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.006 ms/op
Iteration   1: 3.562 ±(99.9%) 0.004 ms/op
Iteration   2: 3.616 ±(99.9%) 0.005 ms/op
Iteration   3: 3.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.568 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.525, 3.568, 3.616), stdev = 0.046
  CI (99.9%): [2.733, 4.403] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.911 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.005 ms/op
Iteration   1: 3.494 ±(99.9%) 0.004 ms/op
Iteration   2: 3.344 ±(99.9%) 0.005 ms/op
Iteration   3: 3.394 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.411 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.344, 3.411, 3.494), stdev = 0.076
  CI (99.9%): [2.018, 4.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.174 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.006 ms/op
Iteration   1: 3.572 ±(99.9%) 0.005 ms/op
Iteration   2: 3.550 ±(99.9%) 0.006 ms/op
Iteration   3: 3.505 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.542 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.505, 3.542, 3.572), stdev = 0.034
  CI (99.9%): [2.925, 4.160] (assumes normal distribution)


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
# Warmup Iteration   1: 11.428 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.010 ms/op
Iteration   1: 4.130 ±(99.9%) 0.007 ms/op
Iteration   2: 4.156 ±(99.9%) 0.007 ms/op
Iteration   3: 4.085 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.124 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (4.085, 4.124, 4.156), stdev = 0.036
  CI (99.9%): [3.470, 4.778] (assumes normal distribution)


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
# Warmup Iteration   1: 10.306 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.012 ms/op
Iteration   1: 3.810 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   6.963 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  21.366 ms/op
                 createUser·p0.9999: 23.875 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  21.772 ms/op
                 createUser·p0.9999: 25.519 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   7.329 ms/op
                 createUser·p0.999:  19.041 ms/op
                 createUser·p0.9999: 26.537 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267740
  mean =      3.584 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6724 
    [ 2.500,  5.000) = 248484 
    [ 5.000,  7.500) = 8615 
    [ 7.500, 10.000) = 2968 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     25.534 ms/op
     p(99.9990) =     27.511 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 9.057 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.012 ms/op
Iteration   1: 3.382 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.847 ms/op
                 existUser·p0.999:  21.574 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.495 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  11.937 ms/op
                 existUser·p0.9999: 23.490 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.987 ms/op
                 existUser·p0.999:  23.350 ms/op
                 existUser·p0.9999: 27.722 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279433
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3898 
    [ 2.500,  5.000) = 266437 
    [ 5.000,  7.500) = 7514 
    [ 7.500, 10.000) = 990 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     20.465 ms/op
     p(99.9900) =     26.648 ms/op
     p(99.9990) =     28.438 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.527 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.013 ms/op
Iteration   1: 3.586 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.548 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  13.546 ms/op
                 getUser·p0.9999: 28.277 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   3: 3.540 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  19.942 ms/op
                 getUser·p0.9999: 25.853 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269784
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3444 
    [ 2.500,  5.000) = 257522 
    [ 5.000,  7.500) = 6535 
    [ 7.500, 10.000) = 1785 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.965 ms/op
     p(99.9900) =     26.117 ms/op
     p(99.9990) =     30.373 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 10.914 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
Iteration   1: 4.316 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  19.970 ms/op
                 listUser·p0.9999: 26.144 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 4.178 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.735 ms/op
                 listUser·p0.9999: 17.194 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.197 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 16.403 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226899
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 214580 
    [ 5.000,  7.500) = 8621 
    [ 7.500, 10.000) = 2588 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     15.943 ms/op
     p(99.9900) =     24.483 ms/op
     p(99.9990) =     28.767 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.114 ± 2.603  ops/ms
ClientPb.existUser                       thrpt       3   9.596 ± 2.788  ops/ms
ClientPb.getUser                         thrpt       3   8.862 ± 4.284  ops/ms
ClientPb.listUser                        thrpt       3   7.643 ± 1.070  ops/ms
ClientPb.createUser                       avgt       3   3.568 ± 0.835   ms/op
ClientPb.existUser                        avgt       3   3.411 ± 1.392   ms/op
ClientPb.getUser                          avgt       3   3.542 ± 0.618   ms/op
ClientPb.listUser                         avgt       3   4.124 ± 0.654   ms/op
ClientPb.createUser                     sample  267740   3.584 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.713           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.534           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.722           ms/op
ClientPb.existUser                      sample  279433   3.433 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.247           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  269784   3.558 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.965           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.117           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.540           ms/op
ClientPb.listUser                       sample  226899   4.229 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.362           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.483           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
