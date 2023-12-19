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
# Warmup Iteration   1: 5.333 ops/ms
# Warmup Iteration   2: 12.242 ops/ms
# Warmup Iteration   3: 12.359 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.686 ops/ms
Iteration   3: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.654 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (12.588, 12.654, 12.688), stdev = 0.057
  CI (99.9%): [11.610, 13.698] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.358 ops/ms
# Warmup Iteration   2: 13.098 ops/ms
# Warmup Iteration   3: 13.123 ops/ms
Iteration   1: 13.142 ops/ms
Iteration   2: 13.169 ops/ms
Iteration   3: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.136 ±(99.9%) 0.673 ops/ms [Average]
  (min, avg, max) = (13.096, 13.136, 13.169), stdev = 0.037
  CI (99.9%): [12.463, 13.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.777 ops/ms
# Warmup Iteration   2: 12.681 ops/ms
# Warmup Iteration   3: 12.884 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 13.003 ops/ms
Iteration   3: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.926 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (12.886, 12.926, 13.003), stdev = 0.067
  CI (99.9%): [11.710, 14.142] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.095 ops/ms
# Warmup Iteration   2: 10.682 ops/ms
# Warmup Iteration   3: 10.673 ops/ms
Iteration   1: 10.780 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.730 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (10.628, 10.730, 10.783), stdev = 0.089
  CI (99.9%): [9.110, 12.350] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.519, 2.532, 2.548), stdev = 0.015
  CI (99.9%): [2.261, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.461, 2.467, 2.477), stdev = 0.009
  CI (99.9%): [2.307, 2.627] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.493, 2.499, 2.508), stdev = 0.008
  CI (99.9%): [2.357, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
Iteration   3: 3.003 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.003, 3.018, 3.031), stdev = 0.014
  CI (99.9%): [2.756, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.811 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 13.992 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.456 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.083 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 11.076 ms/op
                 createUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380838
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 183022 
    [ 2.500,  3.750) = 193286 
    [ 3.750,  5.000) = 3732 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     13.398 ms/op
     p(99.9990) =     14.208 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  6.625 ms/op
                 existUser·p0.9999: 14.664 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.741 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  7.848 ms/op
                 existUser·p0.9999: 10.911 ms/op
                 existUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391119
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 193036 
    [ 2.500,  3.750) = 194574 
    [ 3.750,  5.000) = 2626 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.724 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.783 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  6.726 ms/op
                 getUser·p0.9999: 14.478 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  9.769 ms/op
                 getUser·p0.9999: 16.482 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  8.425 ms/op
                 getUser·p0.9999: 11.508 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383501
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 189101 
    [ 2.500,  3.750) = 190167 
    [ 3.750,  5.000) = 3423 
    [ 5.000,  6.250) = 340 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     14.592 ms/op
     p(99.9990) =     16.837 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.921 ms/op
                 listUser·p0.9999: 11.117 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.654 ms/op
                 listUser·p0.9999: 10.689 ms/op
                 listUser·p1.00:   10.781 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.656 ms/op
                 listUser·p0.9999: 11.230 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315843
  mean =      3.037 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 86708 
    [ 2.500,  3.750) = 189095 
    [ 3.750,  5.000) = 32563 
    [ 5.000,  6.250) = 6002 
    [ 6.250,  7.500) = 738 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.098 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.654 ± 1.044  ops/ms
ClientPb.existUser                       thrpt       3  13.136 ± 0.673  ops/ms
ClientPb.getUser                         thrpt       3  12.926 ± 1.216  ops/ms
ClientPb.listUser                        thrpt       3  10.730 ± 1.620  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.143   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.262   ms/op
ClientPb.createUser                     sample  380838   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.645           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.421           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  391119   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.598           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.724           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.073           ms/op
ClientPb.getUser                        sample  383501   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.734           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.170           ms/op
ClientPb.listUser                       sample  315843   3.037 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.930           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.098           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.747           ms/op
