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
# Warmup Iteration   1: 2.699 ops/ms
# Warmup Iteration   2: 5.992 ops/ms
# Warmup Iteration   3: 9.138 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.913 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.818 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (9.743, 9.818, 9.913), stdev = 0.087
  CI (99.9%): [8.238, 11.398] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ops/ms
# Warmup Iteration   2: 9.577 ops/ms
# Warmup Iteration   3: 10.275 ops/ms
Iteration   1: 9.928 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.131 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (9.928, 10.131, 10.251), stdev = 0.177
  CI (99.9%): [6.895, 13.367] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 8.794 ops/ms
# Warmup Iteration   3: 9.949 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 9.603 ops/ms
Iteration   3: 9.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.861 ±(99.9%) 4.268 ops/ms [Average]
  (min, avg, max) = (9.603, 9.861, 10.060), stdev = 0.234
  CI (99.9%): [5.592, 14.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 7.765 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.413 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (8.350, 8.413, 8.488), stdev = 0.070
  CI (99.9%): [7.144, 9.682] (assumes normal distribution)


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
# Warmup Iteration   1: 7.417 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.002 ms/op
Iteration   1: 3.237 ±(99.9%) 0.005 ms/op
Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
Iteration   3: 3.222 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.222, 3.238, 3.255), stdev = 0.017
  CI (99.9%): [2.932, 3.545] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.222 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.063, 3.097, 3.117), stdev = 0.029
  CI (99.9%): [2.564, 3.630] (assumes normal distribution)


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
# Warmup Iteration   1: 8.407 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.004 ms/op
Iteration   1: 3.296 ±(99.9%) 0.004 ms/op
Iteration   2: 3.269 ±(99.9%) 0.002 ms/op
Iteration   3: 3.217 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.261 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.217, 3.261, 3.296), stdev = 0.040
  CI (99.9%): [2.532, 3.990] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.004 ms/op
Iteration   1: 3.855 ±(99.9%) 0.004 ms/op
Iteration   2: 3.784 ±(99.9%) 0.006 ms/op
Iteration   3: 3.827 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.822 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.784, 3.822, 3.855), stdev = 0.036
  CI (99.9%): [3.168, 4.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
Iteration   1: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 18.644 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  17.959 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 19.537 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296742
  mean =      3.233 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16798 
    [ 2.500,  5.000) = 275981 
    [ 5.000,  7.500) = 3084 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     23.267 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.369 ms/op
                 existUser·p0.999:  17.198 ms/op
                 existUser·p0.9999: 20.643 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 19.954 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302399
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22354 
    [ 2.500,  5.000) = 274867 
    [ 5.000,  7.500) = 4400 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.716 ms/op
     p(99.9900) =     20.694 ms/op
     p(99.9990) =     22.566 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 9.329 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  15.974 ms/op
                 getUser·p0.9999: 17.868 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.154 ms/op
                 getUser·p0.999:  14.224 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  13.662 ms/op
                 getUser·p0.9999: 19.771 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295297
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7560 
    [ 2.500,  5.000) = 281382 
    [ 5.000,  7.500) = 5385 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     19.840 ms/op
     p(99.9990) =     20.694 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.045 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.012 ms/op
Iteration   1: 3.869 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.718 ms/op
                 listUser·p0.9999: 19.488 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.788 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.064 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.838 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 18.696 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.762 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.844 ms/op
                 listUser·p0.9999: 18.655 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252074
  mean =      3.806 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 245092 
    [ 5.000,  7.500) = 5511 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 379 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     19.090 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.818 ± 1.580  ops/ms
ClientPb.existUser                       thrpt       3  10.131 ± 3.236  ops/ms
ClientPb.getUser                         thrpt       3   9.861 ± 4.268  ops/ms
ClientPb.listUser                        thrpt       3   8.413 ± 1.269  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.533   ms/op
ClientPb.getUser                          avgt       3   3.261 ± 0.729   ms/op
ClientPb.listUser                         avgt       3   3.822 ± 0.654   ms/op
ClientPb.createUser                     sample  296742   3.233 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.560           ms/op
ClientPb.existUser                      sample  302399   3.174 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.716           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.694           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  295297   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.030           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.287           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.840           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.561           ms/op
ClientPb.listUser                       sample  252074   3.806 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.090           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.644           ms/op
