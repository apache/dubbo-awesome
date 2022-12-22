# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.814 ops/ms
# Warmup Iteration   2: 4.784 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.347 ±(99.9%) 2.551 ops/ms [Average]
  (min, avg, max) = (9.231, 9.347, 9.502), stdev = 0.140
  CI (99.9%): [6.795, 11.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 8.309 ops/ms
# Warmup Iteration   3: 9.369 ops/ms
Iteration   1: 9.537 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 9.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.698 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (9.537, 9.698, 9.848), stdev = 0.156
  CI (99.9%): [6.856, 12.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 8.293 ops/ms
# Warmup Iteration   3: 8.598 ops/ms
Iteration   1: 9.263 ops/ms
Iteration   2: 9.161 ops/ms
Iteration   3: 9.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.154 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (9.037, 9.154, 9.263), stdev = 0.113
  CI (99.9%): [7.090, 11.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.453 ops/ms
# Warmup Iteration   2: 7.315 ops/ms
# Warmup Iteration   3: 7.376 ops/ms
Iteration   1: 7.376 ops/ms
Iteration   2: 7.824 ops/ms
Iteration   3: 7.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.601 ±(99.9%) 4.079 ops/ms [Average]
  (min, avg, max) = (7.376, 7.601, 7.824), stdev = 0.224
  CI (99.9%): [3.522, 11.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.829 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.007 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
Iteration   2: 3.581 ±(99.9%) 0.008 ms/op
Iteration   3: 3.771 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.578 ±(99.9%) 3.572 ms/op [Average]
  (min, avg, max) = (3.380, 3.578, 3.771), stdev = 0.196
  CI (99.9%): [0.005, 7.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.003 ms/op
Iteration   1: 3.423 ±(99.9%) 0.003 ms/op
Iteration   2: 3.286 ±(99.9%) 0.007 ms/op
Iteration   3: 3.339 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.349 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (3.286, 3.349, 3.423), stdev = 0.069
  CI (99.9%): [2.097, 4.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.457 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.005 ms/op
Iteration   1: 3.496 ±(99.9%) 0.003 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.452 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.452, 3.483, 3.501), stdev = 0.027
  CI (99.9%): [2.988, 3.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.662 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.009 ms/op
Iteration   1: 4.119 ±(99.9%) 0.010 ms/op
Iteration   2: 4.132 ±(99.9%) 0.009 ms/op
Iteration   3: 4.005 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (4.005, 4.085, 4.132), stdev = 0.070
  CI (99.9%): [2.815, 5.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.611 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.011 ms/op
Iteration   1: 3.578 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  23.192 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  23.692 ms/op
                 createUser·p0.9999: 28.071 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 29.588 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270605
  mean =      3.546 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6016 
    [ 2.500,  5.000) = 254612 
    [ 5.000,  7.500) = 8153 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     27.851 ms/op
     p(99.9990) =     31.116 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.807 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
Iteration   1: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.015 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  20.965 ms/op
                 existUser·p0.9999: 26.784 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.355 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  22.728 ms/op
                 existUser·p0.9999: 32.224 ms/op
                 existUser·p1.00:   32.768 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.663 ms/op
                 existUser·p0.999:  21.587 ms/op
                 existUser·p0.9999: 26.476 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286320
  mean =      3.349 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7699 
    [ 2.500,  5.000) = 272326 
    [ 5.000,  7.500) = 5534 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     30.555 ms/op
     p(99.9990) =     32.557 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.034 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.014 ms/op
Iteration   1: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  21.448 ms/op
                 getUser·p0.9999: 24.763 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  22.924 ms/op
                 getUser·p0.9999: 29.189 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 26.409 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275699
  mean =      3.480 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7139 
    [ 2.500,  5.000) = 262346 
    [ 5.000,  7.500) = 5141 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     21.276 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     30.069 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.562 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.014 ms/op
Iteration   1: 4.073 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  21.120 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.096 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.741 ms/op
                 listUser·p0.9999: 18.848 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.070 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  15.211 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235281
  mean =      4.080 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 225682 
    [ 5.000,  7.500) = 7262 
    [ 7.500, 10.000) = 1476 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     23.100 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.347 ± 2.551  ops/ms
ClientPb.existUser                       thrpt       3   9.698 ± 2.842  ops/ms
ClientPb.getUser                         thrpt       3   9.154 ± 2.064  ops/ms
ClientPb.listUser                        thrpt       3   7.601 ± 4.079  ops/ms
ClientPb.createUser                       avgt       3   3.578 ± 3.572   ms/op
ClientPb.existUser                        avgt       3   3.349 ± 1.252   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 0.495   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.270   ms/op
ClientPb.createUser                     sample  270605   3.546 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.851           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.195           ms/op
ClientPb.existUser                      sample  286320   3.349 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.346           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.594           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.555           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.768           ms/op
ClientPb.getUser                        sample  275699   3.480 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.276           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.853           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.671           ms/op
ClientPb.listUser                       sample  235281   4.080 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.630           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.100           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
