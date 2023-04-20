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
# Warmup Iteration   1: 1.920 ops/ms
# Warmup Iteration   2: 5.093 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 8.518 ops/ms
Iteration   2: 9.378 ops/ms
Iteration   3: 9.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.020 ±(99.9%) 8.161 ops/ms [Average]
  (min, avg, max) = (8.518, 9.020, 9.378), stdev = 0.447
  CI (99.9%): [0.858, 17.181] (assumes normal distribution)


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
# Warmup Iteration   1: 2.715 ops/ms
# Warmup Iteration   2: 8.496 ops/ms
# Warmup Iteration   3: 8.880 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.580 ±(99.9%) 2.444 ops/ms [Average]
  (min, avg, max) = (9.453, 9.580, 9.720), stdev = 0.134
  CI (99.9%): [7.137, 12.024] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.637 ops/ms
# Warmup Iteration   2: 7.444 ops/ms
# Warmup Iteration   3: 8.860 ops/ms
Iteration   1: 8.453 ops/ms
Iteration   2: 9.195 ops/ms
Iteration   3: 9.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.955 ±(99.9%) 7.928 ops/ms [Average]
  (min, avg, max) = (8.453, 8.955, 9.217), stdev = 0.435
  CI (99.9%): [1.027, 16.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 6.376 ops/ms
# Warmup Iteration   3: 7.581 ops/ms
Iteration   1: 7.638 ops/ms
Iteration   2: 8.077 ops/ms
Iteration   3: 8.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.925 ±(99.9%) 4.530 ops/ms [Average]
  (min, avg, max) = (7.638, 7.925, 8.077), stdev = 0.248
  CI (99.9%): [3.395, 12.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.457 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.486 ±(99.9%) 0.012 ms/op
Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
Iteration   3: 3.543 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.497 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.462, 3.497, 3.543), stdev = 0.041
  CI (99.9%): [2.746, 4.248] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.575 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.003 ms/op
Iteration   1: 3.396 ±(99.9%) 0.012 ms/op
Iteration   2: 3.464 ±(99.9%) 0.006 ms/op
Iteration   3: 3.357 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.406 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.357, 3.406, 3.464), stdev = 0.054
  CI (99.9%): [2.415, 4.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.608 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.007 ms/op
Iteration   1: 3.423 ±(99.9%) 0.008 ms/op
Iteration   2: 3.441 ±(99.9%) 0.006 ms/op
Iteration   3: 3.487 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.423, 3.450, 3.487), stdev = 0.033
  CI (99.9%): [2.850, 4.051] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.445 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.008 ms/op
Iteration   1: 4.167 ±(99.9%) 0.011 ms/op
Iteration   2: 3.974 ±(99.9%) 0.013 ms/op
Iteration   3: 3.911 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.017 ±(99.9%) 2.431 ms/op [Average]
  (min, avg, max) = (3.911, 4.017, 4.167), stdev = 0.133
  CI (99.9%): [1.586, 6.449] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.276 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.015 ms/op
Iteration   1: 3.482 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.806 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  22.878 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 3.487 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  24.548 ms/op
                 createUser·p0.9999: 27.547 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.434 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  27.497 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276905
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14071 
    [ 2.500,  5.000) = 256526 
    [ 5.000,  7.500) = 5173 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     23.858 ms/op
     p(99.9900) =     30.845 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.000 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  21.391 ms/op
                 existUser·p0.9999: 28.082 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  22.970 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.877 ms/op
                 existUser·p0.999:  18.236 ms/op
                 existUser·p0.9999: 25.935 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284246
  mean =      3.376 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19636 
    [ 2.500,  5.000) = 258046 
    [ 5.000,  7.500) = 5336 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     18.605 ms/op
     p(99.9900) =     28.120 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 11.488 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.013 ms/op
Iteration   1: 3.629 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 24.143 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.232 ms/op
                 getUser·p0.999:  11.807 ms/op
                 getUser·p0.9999: 25.712 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.481 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  23.893 ms/op
                 getUser·p0.9999: 36.885 ms/op
                 getUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273223
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4260 
    [ 2.500,  5.000) = 260916 
    [ 5.000,  7.500) = 6798 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     17.549 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     37.308 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 11.899 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.016 ms/op
Iteration   1: 4.072 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  21.982 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 4.051 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.633 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237695
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 227609 
    [ 5.000,  7.500) = 7597 
    [ 7.500, 10.000) = 1623 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     25.902 ms/op
     p(99.9990) =     27.644 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.020 ± 8.161  ops/ms
ClientPb.existUser                       thrpt       3   9.580 ± 2.444  ops/ms
ClientPb.getUser                         thrpt       3   8.955 ± 7.928  ops/ms
ClientPb.listUser                        thrpt       3   7.925 ± 4.530  ops/ms
ClientPb.createUser                       avgt       3   3.497 ± 0.751   ms/op
ClientPb.existUser                        avgt       3   3.406 ± 0.990   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 0.601   ms/op
ClientPb.listUser                         avgt       3   4.017 ± 2.431   ms/op
ClientPb.createUser                     sample  276905   3.467 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.378           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.858           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  284246   3.376 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.274           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.605           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.120           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  273223   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.192           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.848           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.552           ms/op
ClientPb.listUser                       sample  237695   4.038 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.902           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.951           ms/op
