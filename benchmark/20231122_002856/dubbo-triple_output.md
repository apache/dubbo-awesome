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
# Warmup Iteration   1: 4.625 ops/ms
# Warmup Iteration   2: 12.159 ops/ms
# Warmup Iteration   3: 12.328 ops/ms
Iteration   1: 12.525 ops/ms
Iteration   2: 12.478 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.522 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (12.478, 12.522, 12.563), stdev = 0.042
  CI (99.9%): [11.752, 13.291] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.887 ops/ms
# Warmup Iteration   2: 13.097 ops/ms
# Warmup Iteration   3: 13.073 ops/ms
Iteration   1: 13.082 ops/ms
Iteration   2: 13.180 ops/ms
Iteration   3: 13.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.147 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (13.082, 13.147, 13.180), stdev = 0.056
  CI (99.9%): [12.116, 14.178] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.466 ops/ms
# Warmup Iteration   2: 12.226 ops/ms
# Warmup Iteration   3: 12.677 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 12.603 ops/ms
Iteration   3: 12.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.588 ±(99.9%) 3.788 ops/ms [Average]
  (min, avg, max) = (12.374, 12.588, 12.788), stdev = 0.208
  CI (99.9%): [8.800, 16.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.603 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.513 ±(99.9%) 0.409 ops/ms [Average]
  (min, avg, max) = (10.488, 10.513, 10.531), stdev = 0.022
  CI (99.9%): [10.105, 10.922] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.596 ±(99.9%) 0.005 ms/op
Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
Iteration   3: 2.526 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (2.526, 2.552, 2.596), stdev = 0.038
  CI (99.9%): [1.863, 3.242] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.439, 2.444, 2.453), stdev = 0.007
  CI (99.9%): [2.312, 2.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.526 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.507, 2.526, 2.538), stdev = 0.016
  CI (99.9%): [2.225, 2.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.678 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.012, 3.035, 3.048), stdev = 0.020
  CI (99.9%): [2.664, 3.407] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  9.596 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 12.003 ms/op
                 createUser·p1.00:   12.239 ms/op

Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 11.715 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380087
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 181843 
    [ 2.500,  3.750) = 193435 
    [ 3.750,  5.000) = 3536 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.559 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  8.822 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.546 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383292
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 191440 
    [ 2.500,  3.750) = 187472 
    [ 3.750,  5.000) = 3425 
    [ 5.000,  6.250) = 468 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     15.305 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.548 ms/op
                 getUser·p0.999:  11.274 ms/op
                 getUser·p0.9999: 14.173 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.334 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  10.197 ms/op
                 getUser·p0.9999: 13.213 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  8.489 ms/op
                 getUser·p0.9999: 10.507 ms/op
                 getUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377323
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 182872 
    [ 2.500,  3.750) = 185869 
    [ 3.750,  5.000) = 6063 
    [ 5.000,  6.250) = 1890 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.471 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.348 ms/op
                 listUser·p0.9999: 10.682 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.971 ms/op
                 listUser·p0.9999: 12.461 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314749
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 84902 
    [ 2.500,  3.750) = 187612 
    [ 3.750,  5.000) = 34690 
    [ 5.000,  6.250) = 6128 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.542 ms/op
     p(99.9990) =     13.142 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.522 ± 0.770  ops/ms
ClientPb.existUser                       thrpt       3  13.147 ± 1.031  ops/ms
ClientPb.getUser                         thrpt       3  12.588 ± 3.788  ops/ms
ClientPb.listUser                        thrpt       3  10.513 ± 0.409  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.689   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.132   ms/op
ClientPb.getUser                          avgt       3   2.526 ± 0.300   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.372   ms/op
ClientPb.createUser                     sample  380087   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.850           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.844           ms/op
ClientPb.existUser                      sample  383292   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.662           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.849           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.992           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.417           ms/op
ClientPb.getUser                        sample  377323   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.879           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.897           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  314749   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.287           ms/op
