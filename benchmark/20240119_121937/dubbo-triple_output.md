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
# Warmup Iteration   1: 5.039 ops/ms
# Warmup Iteration   2: 12.514 ops/ms
# Warmup Iteration   3: 12.774 ops/ms
Iteration   1: 12.802 ops/ms
Iteration   2: 12.856 ops/ms
Iteration   3: 12.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.871 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (12.802, 12.871, 12.955), stdev = 0.078
  CI (99.9%): [11.456, 14.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.553 ops/ms
# Warmup Iteration   2: 13.337 ops/ms
# Warmup Iteration   3: 13.231 ops/ms
Iteration   1: 13.313 ops/ms
Iteration   2: 13.421 ops/ms
Iteration   3: 13.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.325 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (13.241, 13.325, 13.421), stdev = 0.091
  CI (99.9%): [11.673, 14.978] (assumes normal distribution)


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
# Warmup Iteration   1: 7.588 ops/ms
# Warmup Iteration   2: 12.852 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.348 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.641 ±(99.9%) 4.669 ops/ms [Average]
  (min, avg, max) = (12.348, 12.641, 12.820), stdev = 0.256
  CI (99.9%): [7.972, 17.310] (assumes normal distribution)


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
# Warmup Iteration   1: 6.919 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 10.697 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.795 ops/ms
Iteration   3: 10.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.783 ±(99.9%) 0.375 ops/ms [Average]
  (min, avg, max) = (10.759, 10.783, 10.795), stdev = 0.021
  CI (99.9%): [10.407, 11.158] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.513, 2.540, 2.562), stdev = 0.025
  CI (99.9%): [2.084, 2.996] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.420, 2.424, 2.430), stdev = 0.005
  CI (99.9%): [2.332, 2.516] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.471, 2.483, 2.502), stdev = 0.016
  CI (99.9%): [2.188, 2.778] (assumes normal distribution)


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.005 ms/op
Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
Iteration   3: 3.030 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.030, 3.042, 3.049), stdev = 0.011
  CI (99.9%): [2.850, 3.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.755 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.220 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 13.812 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  9.266 ms/op
                 createUser·p0.9999: 12.342 ms/op
                 createUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378656
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 183345 
    [ 2.500,  3.750) = 191047 
    [ 3.750,  5.000) = 3214 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 165 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.607 ms/op
     p(99.9900) =     13.748 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  5.841 ms/op
                 existUser·p0.9999: 13.350 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.353 ms/op
                 existUser·p0.9999: 13.324 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.536 ms/op
                 existUser·p0.999:  7.701 ms/op
                 existUser·p0.9999: 12.317 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391837
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 195643 
    [ 2.500,  3.750) = 193502 
    [ 3.750,  5.000) = 1977 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      6.889 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.715 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 14.424 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  9.248 ms/op
                 getUser·p0.9999: 14.327 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  8.867 ms/op
                 getUser·p0.9999: 11.248 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381351
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186769 
    [ 2.500,  3.750) = 189296 
    [ 3.750,  5.000) = 4435 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.941 ms/op
     p(99.9990) =     15.257 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.008 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.811 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.242 ms/op
                 listUser·p0.9999: 13.399 ms/op
                 listUser·p1.00:   14.909 ms/op

Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 12.190 ms/op
                 listUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318885
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 94626 
    [ 2.500,  3.750) = 183675 
    [ 3.750,  5.000) = 32713 
    [ 5.000,  6.250) = 6345 
    [ 6.250,  7.500) = 633 
    [ 7.500,  8.750) = 292 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     14.002 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.871 ± 1.415  ops/ms
ClientPb.existUser                       thrpt       3  13.325 ± 1.652  ops/ms
ClientPb.getUser                         thrpt       3  12.641 ± 4.669  ops/ms
ClientPb.listUser                        thrpt       3  10.783 ± 0.375  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.456   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.295   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.192   ms/op
ClientPb.createUser                     sample  378656   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.607           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.748           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.533           ms/op
ClientPb.existUser                      sample  391837   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.844           ms/op
ClientPb.getUser                        sample  381351   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.897           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.941           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  318885   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.909           ms/op
