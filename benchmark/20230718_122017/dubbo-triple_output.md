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
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 8.399 ops/ms
Iteration   1: 9.168 ops/ms
Iteration   2: 9.287 ops/ms
Iteration   3: 9.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.209 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (9.168, 9.209, 9.287), stdev = 0.068
  CI (99.9%): [7.965, 10.453] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 8.402 ops/ms
# Warmup Iteration   3: 9.080 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 9.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.582 ±(99.9%) 5.145 ops/ms [Average]
  (min, avg, max) = (9.274, 9.582, 9.827), stdev = 0.282
  CI (99.9%): [4.437, 14.727] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 9.210 ops/ms
Iteration   1: 9.069 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 8.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.211 ±(99.9%) 6.990 ops/ms [Average]
  (min, avg, max) = (8.920, 9.211, 9.645), stdev = 0.383
  CI (99.9%): [2.221, 16.202] (assumes normal distribution)


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
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 6.916 ops/ms
# Warmup Iteration   3: 7.409 ops/ms
Iteration   1: 7.559 ops/ms
Iteration   2: 7.805 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.788 ±(99.9%) 4.035 ops/ms [Average]
  (min, avg, max) = (7.559, 7.788, 8.000), stdev = 0.221
  CI (99.9%): [3.753, 11.823] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.205 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.010 ms/op
Iteration   1: 3.439 ±(99.9%) 0.008 ms/op
Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
Iteration   3: 3.521 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.480 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.439, 3.480, 3.521), stdev = 0.041
  CI (99.9%): [2.736, 4.224] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.004 ms/op
Iteration   1: 3.601 ±(99.9%) 0.004 ms/op
Iteration   2: 3.359 ±(99.9%) 0.004 ms/op
Iteration   3: 3.482 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.480 ±(99.9%) 2.209 ms/op [Average]
  (min, avg, max) = (3.359, 3.480, 3.601), stdev = 0.121
  CI (99.9%): [1.272, 5.689] (assumes normal distribution)


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.003 ms/op
Iteration   1: 3.533 ±(99.9%) 0.003 ms/op
Iteration   2: 3.470 ±(99.9%) 0.008 ms/op
Iteration   3: 3.389 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.464 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.389, 3.464, 3.533), stdev = 0.072
  CI (99.9%): [2.151, 4.777] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.186 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.009 ms/op
Iteration   1: 4.057 ±(99.9%) 0.008 ms/op
Iteration   2: 4.096 ±(99.9%) 0.005 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.056 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (4.015, 4.056, 4.096), stdev = 0.041
  CI (99.9%): [3.316, 4.796] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.890 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.010 ms/op
Iteration   1: 3.630 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  21.164 ms/op
                 createUser·p0.9999: 28.548 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  20.804 ms/op
                 createUser·p0.9999: 28.178 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.506 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  20.406 ms/op
                 createUser·p0.9999: 26.898 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270165
  mean =      3.553 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6059 
    [ 2.500,  5.000) = 255818 
    [ 5.000,  7.500) = 7081 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     20.830 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     29.458 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 8.120 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.700 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  18.349 ms/op
                 existUser·p0.9999: 24.488 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.993 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 24.893 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 30.189 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286140
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2141 
    [ 2.500,  5.000) = 278069 
    [ 5.000,  7.500) = 4943 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     28.846 ms/op
     p(99.9990) =     30.712 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 9.248 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.012 ms/op
Iteration   1: 3.539 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  22.071 ms/op
                 getUser·p0.9999: 30.671 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  20.775 ms/op
                 getUser·p0.9999: 29.586 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 3.560 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  20.847 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270749
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4902 
    [ 2.500,  5.000) = 258041 
    [ 5.000,  7.500) = 6416 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     21.438 ms/op
     p(99.9900) =     29.449 ms/op
     p(99.9990) =     31.011 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 11.746 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  22.176 ms/op
                 listUser·p0.9999: 37.224 ms/op
                 listUser·p1.00:   38.732 ms/op

Iteration   2: 4.111 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.077 ms/op
                 listUser·p0.9999: 16.493 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.057 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.190 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233848
  mean =      4.105 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 224491 
    [ 5.000,  7.500) = 7302 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     35.707 ms/op
     p(99.9990) =     37.508 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.209 ± 1.244  ops/ms
ClientPb.existUser                       thrpt       3   9.582 ± 5.145  ops/ms
ClientPb.getUser                         thrpt       3   9.211 ± 6.990  ops/ms
ClientPb.listUser                        thrpt       3   7.788 ± 4.035  ops/ms
ClientPb.createUser                       avgt       3   3.480 ± 0.744   ms/op
ClientPb.existUser                        avgt       3   3.480 ± 2.209   ms/op
ClientPb.getUser                          avgt       3   3.464 ± 1.313   ms/op
ClientPb.listUser                         avgt       3   4.056 ± 0.740   ms/op
ClientPb.createUser                     sample  270165   3.553 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  286140   3.355 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.846           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.818           ms/op
ClientPb.getUser                        sample  270749   3.543 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.449           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  233848   4.105 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.732           ms/op
