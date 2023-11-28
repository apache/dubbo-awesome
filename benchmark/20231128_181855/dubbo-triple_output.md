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
# Warmup Iteration   1: 4.415 ops/ms
# Warmup Iteration   2: 11.689 ops/ms
# Warmup Iteration   3: 12.192 ops/ms
Iteration   1: 12.476 ops/ms
Iteration   2: 12.593 ops/ms
Iteration   3: 12.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.505 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (12.446, 12.505, 12.593), stdev = 0.077
  CI (99.9%): [11.091, 13.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 13.008 ops/ms
# Warmup Iteration   3: 13.083 ops/ms
Iteration   1: 13.088 ops/ms
Iteration   2: 12.985 ops/ms
Iteration   3: 12.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.023 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (12.985, 13.023, 13.088), stdev = 0.056
  CI (99.9%): [11.998, 14.049] (assumes normal distribution)


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
# Warmup Iteration   1: 7.052 ops/ms
# Warmup Iteration   2: 12.304 ops/ms
# Warmup Iteration   3: 12.463 ops/ms
Iteration   1: 12.642 ops/ms
Iteration   2: 12.592 ops/ms
Iteration   3: 12.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.517 ±(99.9%) 3.197 ops/ms [Average]
  (min, avg, max) = (12.317, 12.517, 12.642), stdev = 0.175
  CI (99.9%): [9.321, 15.714] (assumes normal distribution)


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
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.299 ops/ms
Iteration   2: 10.468 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.428 ±(99.9%) 2.080 ops/ms [Average]
  (min, avg, max) = (10.299, 10.428, 10.516), stdev = 0.114
  CI (99.9%): [8.348, 12.508] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (2.547, 2.562, 2.588), stdev = 0.022
  CI (99.9%): [2.160, 2.965] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.481 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.469, 2.481, 2.495), stdev = 0.013
  CI (99.9%): [2.245, 2.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (2.511, 2.524, 2.547), stdev = 0.020
  CI (99.9%): [2.155, 2.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.935 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.055 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.035, 3.055, 3.074), stdev = 0.019
  CI (99.9%): [2.700, 3.410] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.724 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  12.061 ms/op
                 createUser·p0.9999: 13.737 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  11.188 ms/op
                 createUser·p0.9999: 14.565 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.738 ms/op
                 createUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381048
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183995 
    [ 2.500,  3.750) = 192380 
    [ 3.750,  5.000) = 3510 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 164 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     13.712 ms/op
     p(99.9990) =     14.822 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  11.202 ms/op
                 existUser·p0.9999: 14.306 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.375 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  8.740 ms/op
                 existUser·p0.9999: 11.608 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384763
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 188450 
    [ 2.500,  3.750) = 192485 
    [ 3.750,  5.000) = 2896 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     13.771 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  12.612 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  10.138 ms/op
                 getUser·p0.9999: 13.837 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  9.193 ms/op
                 getUser·p0.9999: 11.555 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378462
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 184478 
    [ 2.500,  3.750) = 187877 
    [ 3.750,  5.000) = 4636 
    [ 5.000,  6.250) = 868 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 146 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      9.856 ms/op
     p(99.9900) =     13.880 ms/op
     p(99.9990) =     14.448 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.905 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 12.914 ms/op
                 listUser·p1.00:   15.778 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   3: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.322 ms/op
                 listUser·p0.9999: 13.952 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312974
  mean =      3.063 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 82130 
    [ 2.500,  3.750) = 188445 
    [ 3.750,  5.000) = 34300 
    [ 5.000,  6.250) = 6262 
    [ 6.250,  7.500) = 904 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 241 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     14.627 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.505 ± 1.413  ops/ms
ClientPb.existUser                       thrpt       3  13.023 ± 1.026  ops/ms
ClientPb.getUser                         thrpt       3  12.517 ± 3.197  ops/ms
ClientPb.listUser                        thrpt       3  10.428 ± 2.080  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.403   ms/op
ClientPb.existUser                        avgt       3   2.481 ± 0.236   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.369   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.355   ms/op
ClientPb.createUser                     sample  381048   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.712           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.187           ms/op
ClientPb.existUser                      sample  384763   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.996           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.771           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  378462   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.848           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.856           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.880           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  312974   3.063 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.730           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.778           ms/op
