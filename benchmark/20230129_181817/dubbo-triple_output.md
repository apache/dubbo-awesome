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
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 6.373 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.453 ops/ms
Iteration   2: 10.230 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.858 ±(99.9%) 7.102 ops/ms [Average]
  (min, avg, max) = (9.453, 9.858, 10.230), stdev = 0.389
  CI (99.9%): [2.756, 16.961] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ops/ms
# Warmup Iteration   2: 9.494 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.342 ±(99.9%) 3.506 ops/ms [Average]
  (min, avg, max) = (10.128, 10.342, 10.499), stdev = 0.192
  CI (99.9%): [6.836, 13.848] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ops/ms
# Warmup Iteration   2: 9.174 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 10.163 ops/ms
Iteration   2: 9.736 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.957 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (9.736, 9.957, 10.163), stdev = 0.214
  CI (99.9%): [6.050, 13.863] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 7.710 ops/ms
# Warmup Iteration   3: 8.589 ops/ms
Iteration   1: 8.606 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.520 ±(99.9%) 3.191 ops/ms [Average]
  (min, avg, max) = (8.318, 8.520, 8.634), stdev = 0.175
  CI (99.9%): [5.329, 11.711] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.212 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.003 ms/op
Iteration   1: 3.154 ±(99.9%) 0.004 ms/op
Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.141, 3.164, 3.196), stdev = 0.028
  CI (99.9%): [2.644, 3.684] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.897 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.191 ±(99.9%) 0.004 ms/op
Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
Iteration   3: 3.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.097, 3.149, 3.191), stdev = 0.048
  CI (99.9%): [2.270, 4.028] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.002 ms/op
Iteration   1: 3.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.261 ±(99.9%) 0.006 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.163, 3.226, 3.261), stdev = 0.055
  CI (99.9%): [2.222, 4.230] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.717 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.006 ms/op
Iteration   1: 3.837 ±(99.9%) 0.007 ms/op
Iteration   2: 3.796 ±(99.9%) 0.006 ms/op
Iteration   3: 3.685 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (3.685, 3.773, 3.837), stdev = 0.078
  CI (99.9%): [2.341, 5.205] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 21.964 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  16.360 ms/op
                 createUser·p0.9999: 23.014 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.353 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  15.874 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288759
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22731 
    [ 2.500,  5.000) = 260967 
    [ 5.000,  7.500) = 4160 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     22.483 ms/op
     p(99.9990) =     23.083 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.028 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  13.316 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  11.181 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 21.689 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306073
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27984 
    [ 2.500,  5.000) = 272682 
    [ 5.000,  7.500) = 4714 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     12.759 ms/op
     p(99.9900) =     20.427 ms/op
     p(99.9990) =     23.915 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.010 ms/op
Iteration   1: 3.163 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 27.168 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   2: 3.199 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  14.467 ms/op
                 getUser·p0.9999: 31.457 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.218 ms/op
                 getUser·p0.9999: 24.019 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301503
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8612 
    [ 2.500,  5.000) = 286953 
    [ 5.000,  7.500) = 4808 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     30.486 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 9.318 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.012 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.154 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.721 ms/op
                 listUser·p0.9999: 24.634 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 3.764 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.847 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.747 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.273 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 19.217 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253230
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 245450 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 1512 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     23.157 ms/op
     p(99.9990) =     25.341 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.858 ± 7.102  ops/ms
ClientPb.existUser                       thrpt       3  10.342 ± 3.506  ops/ms
ClientPb.getUser                         thrpt       3   9.957 ± 3.907  ops/ms
ClientPb.listUser                        thrpt       3   8.520 ± 3.191  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 0.520   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 0.879   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 1.004   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 1.432   ms/op
ClientPb.createUser                     sample  288759   3.325 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.396           ms/op
ClientPb.existUser                      sample  306073   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.427           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.953           ms/op
ClientPb.getUser                        sample  301503   3.182 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.255           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.486           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  253230   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.582           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
