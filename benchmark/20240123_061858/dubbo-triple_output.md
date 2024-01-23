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
# Warmup Iteration   1: 5.246 ops/ms
# Warmup Iteration   2: 12.406 ops/ms
# Warmup Iteration   3: 12.529 ops/ms
Iteration   1: 12.656 ops/ms
Iteration   2: 12.716 ops/ms
Iteration   3: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.755 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (12.656, 12.755, 12.894), stdev = 0.124
  CI (99.9%): [10.495, 15.016] (assumes normal distribution)


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
# Warmup Iteration   1: 8.723 ops/ms
# Warmup Iteration   2: 13.243 ops/ms
# Warmup Iteration   3: 13.259 ops/ms
Iteration   1: 13.215 ops/ms
Iteration   2: 12.978 ops/ms
Iteration   3: 13.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.157 ±(99.9%) 2.889 ops/ms [Average]
  (min, avg, max) = (12.978, 13.157, 13.279), stdev = 0.158
  CI (99.9%): [10.268, 16.047] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.783 ops/ms
# Warmup Iteration   2: 12.964 ops/ms
# Warmup Iteration   3: 13.104 ops/ms
Iteration   1: 13.045 ops/ms
Iteration   2: 13.314 ops/ms
Iteration   3: 13.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.165 ±(99.9%) 2.497 ops/ms [Average]
  (min, avg, max) = (13.045, 13.165, 13.314), stdev = 0.137
  CI (99.9%): [10.668, 15.662] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ops/ms
# Warmup Iteration   2: 10.745 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.765 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.720 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (10.691, 10.720, 10.765), stdev = 0.040
  CI (99.9%): [9.993, 11.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.470, 2.478, 2.484), stdev = 0.007
  CI (99.9%): [2.352, 2.605] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
Iteration   2: 2.405 ±(99.9%) 0.003 ms/op
Iteration   3: 2.406 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.018 ms/op [Average]
  (min, avg, max) = (2.405, 2.406, 2.407), stdev = 0.001
  CI (99.9%): [2.388, 2.424] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (2.442, 2.463, 2.504), stdev = 0.035
  CI (99.9%): [1.820, 3.106] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.004 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
Iteration   3: 2.952 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.952, 2.968, 2.979), stdev = 0.014
  CI (99.9%): [2.710, 3.226] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  8.918 ms/op
                 createUser·p0.9999: 16.073 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.054 ms/op
                 createUser·p0.9999: 12.632 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  8.250 ms/op
                 createUser·p0.9999: 10.737 ms/op
                 createUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386408
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188153 
    [ 2.500,  3.750) = 194014 
    [ 3.750,  5.000) = 3096 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.006 ms/op
     p(99.9900) =     13.900 ms/op
     p(99.9990) =     16.718 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.007 ms/op
Iteration   1: 2.405 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.351 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.339 ms/op
                 existUser·p0.9999: 17.390 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 2.437 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   3.105 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 14.439 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   3: 2.361 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.314 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  10.184 ms/op
                 existUser·p0.9999: 13.492 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399598
  mean =      2.401 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235108 
    [ 2.500,  5.000) = 162419 
    [ 5.000,  7.500) = 1428 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.351 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.412 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     15.390 ms/op
     p(99.9990) =     17.728 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.007 ms/op
Iteration   1: 2.492 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   3.232 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.407 ms/op
                 getUser·p0.9999: 15.338 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 2.464 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.408 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.473 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  10.844 ms/op
                 getUser·p0.9999: 15.615 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 2.536 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.329 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.289 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  11.318 ms/op
                 getUser·p0.9999: 15.909 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384081
  mean =      2.497 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206857 
    [ 2.500,  5.000) = 174533 
    [ 5.000,  7.500) = 2065 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     11.315 ms/op
     p(99.9900) =     15.804 ms/op
     p(99.9990) =     18.896 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.010 ms/op
Iteration   1: 3.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  10.191 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   40.239 ms/op

Iteration   2: 3.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.550 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  10.733 ms/op
                 listUser·p0.9999: 14.860 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  10.895 ms/op
                 listUser·p0.9999: 13.015 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316178
  mean =      3.034 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 305405 
    [ 5.000, 10.000) = 10318 
    [10.000, 15.000) = 447 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     10.614 ms/op
     p(99.9900) =     14.101 ms/op
     p(99.9990) =     16.740 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.755 ± 2.261  ops/ms
ClientPb.existUser                       thrpt       3  13.157 ± 2.889  ops/ms
ClientPb.getUser                         thrpt       3  13.165 ± 2.497  ops/ms
ClientPb.listUser                        thrpt       3  10.720 ± 0.727  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.127   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.018   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.643   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.258   ms/op
ClientPb.createUser                     sample  386408   2.482 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.655           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.006           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.900           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.876           ms/op
ClientPb.existUser                      sample  399598   2.401 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.515           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.339           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.390           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.790           ms/op
ClientPb.getUser                        sample  384081   2.497 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.425           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.625           ms/op
ClientPb.listUser                       sample  316178   3.034 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.239           ms/op
