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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 6.498 ops/ms
# Warmup Iteration   3: 9.210 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 9.683 ops/ms
Iteration   3: 10.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.806 ±(99.9%) 3.263 ops/ms [Average]
  (min, avg, max) = (9.683, 9.806, 10.011), stdev = 0.179
  CI (99.9%): [6.543, 13.070] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.187 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.415 ops/ms
Iteration   3: 10.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.396 ±(99.9%) 3.516 ops/ms [Average]
  (min, avg, max) = (10.195, 10.396, 10.579), stdev = 0.193
  CI (99.9%): [6.880, 13.912] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 9.662 ops/ms
Iteration   1: 9.950 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 9.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.935 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (9.809, 9.935, 10.048), stdev = 0.120
  CI (99.9%): [7.742, 12.128] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 8.300 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.565 ops/ms
Iteration   3: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.473 ±(99.9%) 2.827 ops/ms [Average]
  (min, avg, max) = (8.294, 8.473, 8.565), stdev = 0.155
  CI (99.9%): [5.646, 11.300] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.205 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.003 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
Iteration   3: 3.344 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (3.155, 3.222, 3.344), stdev = 0.106
  CI (99.9%): [1.293, 5.152] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.444 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.005 ms/op
Iteration   2: 3.235 ±(99.9%) 0.004 ms/op
Iteration   3: 3.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.140 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.063, 3.140, 3.235), stdev = 0.087
  CI (99.9%): [1.544, 4.735] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.002 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
Iteration   3: 3.281 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.276 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (3.269, 3.276, 3.281), stdev = 0.006
  CI (99.9%): [3.162, 3.391] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.256 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.004 ms/op
Iteration   1: 3.758 ±(99.9%) 0.004 ms/op
Iteration   2: 3.854 ±(99.9%) 0.007 ms/op
Iteration   3: 3.733 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.782 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.733, 3.782, 3.854), stdev = 0.064
  CI (99.9%): [2.622, 4.941] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.820 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.322 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  18.862 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 18.277 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298992
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18248 
    [ 2.500,  5.000) = 274929 
    [ 5.000,  7.500) = 5015 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     21.765 ms/op
     p(99.9990) =     24.776 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.614 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  15.254 ms/op
                 existUser·p0.9999: 26.345 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  20.372 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  16.573 ms/op
                 existUser·p0.9999: 22.775 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296503
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30170 
    [ 2.500,  5.000) = 260668 
    [ 5.000,  7.500) = 4838 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     17.023 ms/op
     p(99.9900) =     25.058 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.393 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.011 ms/op
Iteration   1: 3.210 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  18.809 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.841 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.252 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 22.371 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299004
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4823 
    [ 2.500,  5.000) = 289139 
    [ 5.000,  7.500) = 4067 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.011 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 3.689 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.700 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.498 ms/op
                 listUser·p0.9999: 17.806 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256899
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 250088 
    [ 5.000,  7.500) = 5249 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     28.752 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.806 ± 3.263  ops/ms
ClientPb.existUser                       thrpt       3  10.396 ± 3.516  ops/ms
ClientPb.getUser                         thrpt       3   9.935 ± 2.193  ops/ms
ClientPb.listUser                        thrpt       3   8.473 ± 2.827  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 1.930   ms/op
ClientPb.existUser                        avgt       3   3.140 ± 1.596   ms/op
ClientPb.getUser                          avgt       3   3.276 ± 0.114   ms/op
ClientPb.listUser                         avgt       3   3.782 ± 1.160   ms/op
ClientPb.createUser                     sample  298992   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.147           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.351           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.765           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  296503   3.233 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.023           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  299004   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.905           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  256899   3.735 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.494           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
