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
# Warmup Iteration   1: 4.417 ops/ms
# Warmup Iteration   2: 11.850 ops/ms
# Warmup Iteration   3: 12.031 ops/ms
Iteration   1: 12.405 ops/ms
Iteration   2: 12.432 ops/ms
Iteration   3: 12.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.390 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (12.332, 12.390, 12.432), stdev = 0.052
  CI (99.9%): [11.440, 13.340] (assumes normal distribution)


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
# Warmup Iteration   1: 7.455 ops/ms
# Warmup Iteration   2: 12.658 ops/ms
# Warmup Iteration   3: 12.558 ops/ms
Iteration   1: 12.796 ops/ms
Iteration   2: 12.848 ops/ms
Iteration   3: 12.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.778 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (12.690, 12.778, 12.848), stdev = 0.081
  CI (99.9%): [11.304, 14.252] (assumes normal distribution)


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
# Warmup Iteration   1: 7.519 ops/ms
# Warmup Iteration   2: 12.315 ops/ms
# Warmup Iteration   3: 12.595 ops/ms
Iteration   1: 12.486 ops/ms
Iteration   2: 12.467 ops/ms
Iteration   3: 12.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.488 ±(99.9%) 0.420 ops/ms [Average]
  (min, avg, max) = (12.467, 12.488, 12.513), stdev = 0.023
  CI (99.9%): [12.068, 12.909] (assumes normal distribution)


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
# Warmup Iteration   1: 6.632 ops/ms
# Warmup Iteration   2: 10.323 ops/ms
# Warmup Iteration   3: 10.438 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.486 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (10.430, 10.486, 10.517), stdev = 0.049
  CI (99.9%): [9.600, 11.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.616 ±(99.9%) 0.004 ms/op
Iteration   1: 2.648 ±(99.9%) 0.004 ms/op
Iteration   2: 2.656 ±(99.9%) 0.005 ms/op
Iteration   3: 2.632 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.645 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.632, 2.645, 2.656), stdev = 0.012
  CI (99.9%): [2.422, 2.869] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.534 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.527, 2.534, 2.547), stdev = 0.011
  CI (99.9%): [2.333, 2.735] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.594 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.569 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.544, 2.569, 2.594), stdev = 0.025
  CI (99.9%): [2.112, 3.025] (assumes normal distribution)


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.005 ms/op
Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
Iteration   3: 3.056 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.066 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (3.056, 3.066, 3.078), stdev = 0.011
  CI (99.9%): [2.860, 3.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 2.738 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  12.125 ms/op
                 createUser·p0.9999: 14.002 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 15.218 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 2.590 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.833 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370177
  mean =      2.590 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 175814 
    [ 2.500,  3.750) = 189906 
    [ 3.750,  5.000) = 3629 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      9.205 ms/op
     p(99.9900) =     14.171 ms/op
     p(99.9990) =     15.422 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  12.365 ms/op
                 existUser·p0.9999: 14.166 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.668 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381426
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 185693 
    [ 2.500,  3.750) = 192397 
    [ 3.750,  5.000) = 2381 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.480 ms/op
     p(99.9900) =     13.875 ms/op
     p(99.9990) =     14.880 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  6.625 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 15.221 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  8.106 ms/op
                 getUser·p0.9999: 12.592 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378666
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 184362 
    [ 2.500,  3.750) = 189326 
    [ 3.750,  5.000) = 3868 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      7.681 ms/op
     p(99.9900) =     15.309 ms/op
     p(99.9990) =     18.554 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.853 ms/op
                 listUser·p0.9999: 12.340 ms/op
                 listUser·p1.00:   13.074 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.577 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.969 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.107 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.653 ms/op
                 listUser·p0.9999: 13.606 ms/op
                 listUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312330
  mean =      3.071 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 80696 
    [ 2.500,  3.750) = 189240 
    [ 3.750,  5.000) = 34274 
    [ 5.000,  6.250) = 6505 
    [ 6.250,  7.500) = 795 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 319 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     13.071 ms/op
     p(99.9990) =     14.197 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.390 ± 0.950  ops/ms
ClientPb.existUser                       thrpt       3  12.778 ± 1.474  ops/ms
ClientPb.getUser                         thrpt       3  12.488 ± 0.420  ops/ms
ClientPb.listUser                        thrpt       3  10.486 ± 0.886  ops/ms
ClientPb.createUser                       avgt       3   2.645 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   2.534 ± 0.201   ms/op
ClientPb.getUser                          avgt       3   2.569 ± 0.457   ms/op
ClientPb.listUser                         avgt       3   3.066 ± 0.207   ms/op
ClientPb.createUser                     sample  370177   2.590 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.769           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.205           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.171           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.466           ms/op
ClientPb.existUser                      sample  381426   2.515 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.744           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.480           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.875           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.959           ms/op
ClientPb.getUser                        sample  378666   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.722           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.681           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.309           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.235           ms/op
ClientPb.listUser                       sample  312330   3.071 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.775           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.483           ms/op
