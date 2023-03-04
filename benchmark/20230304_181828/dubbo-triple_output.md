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
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.378 ops/ms
# Warmup Iteration   3: 8.919 ops/ms
Iteration   1: 9.184 ops/ms
Iteration   2: 9.168 ops/ms
Iteration   3: 9.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.248 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (9.168, 9.248, 9.393), stdev = 0.125
  CI (99.9%): [6.960, 11.537] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 8.942 ops/ms
# Warmup Iteration   3: 9.314 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 9.800 ops/ms
Iteration   3: 9.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.688 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (9.585, 9.688, 9.800), stdev = 0.108
  CI (99.9%): [7.722, 11.653] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 8.404 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 9.602 ops/ms
Iteration   2: 9.278 ops/ms
Iteration   3: 9.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.310 ±(99.9%) 5.068 ops/ms [Average]
  (min, avg, max) = (9.049, 9.310, 9.602), stdev = 0.278
  CI (99.9%): [4.242, 14.378] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.786 ops/ms
# Warmup Iteration   2: 7.035 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 7.957 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.005 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (7.957, 8.005, 8.080), stdev = 0.066
  CI (99.9%): [6.805, 9.204] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.263 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.012 ms/op
Iteration   1: 3.415 ±(99.9%) 0.006 ms/op
Iteration   2: 3.479 ±(99.9%) 0.007 ms/op
Iteration   3: 3.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.462 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.415, 3.462, 3.492), stdev = 0.042
  CI (99.9%): [2.705, 4.219] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.599 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.003 ms/op
Iteration   1: 3.231 ±(99.9%) 0.004 ms/op
Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
Iteration   3: 3.435 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 1.879 ms/op [Average]
  (min, avg, max) = (3.231, 3.324, 3.435), stdev = 0.103
  CI (99.9%): [1.445, 5.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.899 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.005 ms/op
Iteration   1: 3.568 ±(99.9%) 0.008 ms/op
Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
Iteration   3: 3.359 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.490 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (3.359, 3.490, 3.568), stdev = 0.114
  CI (99.9%): [1.407, 5.573] (assumes normal distribution)


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
# Warmup Iteration   1: 10.441 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.009 ms/op
Iteration   1: 3.920 ±(99.9%) 0.012 ms/op
Iteration   2: 3.954 ±(99.9%) 0.014 ms/op
Iteration   3: 3.891 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.922 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.891, 3.922, 3.954), stdev = 0.032
  CI (99.9%): [3.343, 4.500] (assumes normal distribution)


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
# Warmup Iteration   1: 9.402 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  19.385 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   5.000 ms/op
                 createUser·p0.999:  14.601 ms/op
                 createUser·p0.9999: 24.765 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  15.396 ms/op
                 createUser·p0.9999: 22.455 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283449
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14003 
    [ 2.500,  5.000) = 262166 
    [ 5.000,  7.500) = 6132 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     15.470 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     25.275 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 9.170 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.032 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.583 ms/op
                 existUser·p0.999:  10.803 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  18.898 ms/op
                 existUser·p0.9999: 32.342 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285605
  mean =      3.361 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8298 
    [ 2.500,  5.000) = 271654 
    [ 5.000,  7.500) = 4513 
    [ 7.500, 10.000) = 693 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.622 ms/op
     p(99.9900) =     31.210 ms/op
     p(99.9990) =     33.007 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 10.429 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.008 ms/op
Iteration   1: 3.607 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 32.314 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.324 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  22.348 ms/op
                 getUser·p0.9999: 26.112 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.415 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  18.952 ms/op
                 getUser·p0.9999: 25.699 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273429
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7409 
    [ 2.500,  5.000) = 256959 
    [ 5.000,  7.500) = 7362 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     21.056 ms/op
     p(99.9900) =     28.616 ms/op
     p(99.9990) =     32.707 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 10.481 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  21.325 ms/op
                 listUser·p0.9999: 25.085 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.068 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.948 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  15.288 ms/op
                 listUser·p0.9999: 19.068 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239320
  mean =      4.008 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 230558 
    [ 5.000,  7.500) = 6265 
    [ 7.500, 10.000) = 1504 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     15.428 ms/op
     p(99.9900) =     24.185 ms/op
     p(99.9990) =     26.311 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.248 ± 2.288  ops/ms
ClientPb.existUser                       thrpt       3   9.688 ± 1.965  ops/ms
ClientPb.getUser                         thrpt       3   9.310 ± 5.068  ops/ms
ClientPb.listUser                        thrpt       3   8.005 ± 1.199  ops/ms
ClientPb.createUser                       avgt       3   3.462 ± 0.757   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 1.879   ms/op
ClientPb.getUser                          avgt       3   3.490 ± 2.083   ms/op
ClientPb.listUser                         avgt       3   3.922 ± 0.579   ms/op
ClientPb.createUser                     sample  283449   3.386 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.241           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.183           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.494           ms/op
ClientPb.existUser                      sample  285605   3.361 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.622           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.210           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.260           ms/op
ClientPb.getUser                        sample  273429   3.509 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.056           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.616           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  239320   4.008 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.887           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.428           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
