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
# Warmup Iteration   1: 5.424 ops/ms
# Warmup Iteration   2: 12.305 ops/ms
# Warmup Iteration   3: 12.501 ops/ms
Iteration   1: 12.721 ops/ms
Iteration   2: 12.880 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.813 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (12.721, 12.813, 12.880), stdev = 0.082
  CI (99.9%): [11.319, 14.307] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.184 ops/ms
# Warmup Iteration   2: 13.156 ops/ms
# Warmup Iteration   3: 13.273 ops/ms
Iteration   1: 13.251 ops/ms
Iteration   2: 13.095 ops/ms
Iteration   3: 13.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.201 ±(99.9%) 1.680 ops/ms [Average]
  (min, avg, max) = (13.095, 13.201, 13.257), stdev = 0.092
  CI (99.9%): [11.521, 14.881] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 12.783 ops/ms
# Warmup Iteration   3: 12.981 ops/ms
Iteration   1: 13.155 ops/ms
Iteration   2: 13.199 ops/ms
Iteration   3: 13.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.146 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (13.084, 13.146, 13.199), stdev = 0.058
  CI (99.9%): [12.089, 14.202] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.807 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.809 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.756 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (10.701, 10.756, 10.809), stdev = 0.054
  CI (99.9%): [9.772, 11.741] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.504, 2.514, 2.527), stdev = 0.012
  CI (99.9%): [2.302, 2.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.004 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.408 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.408, 2.420, 2.440), stdev = 0.018
  CI (99.9%): [2.099, 2.741] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.461, 2.470, 2.485), stdev = 0.014
  CI (99.9%): [2.221, 2.719] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.004 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.013, 3.030, 3.042), stdev = 0.015
  CI (99.9%): [2.762, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  9.938 ms/op
                 createUser·p0.9999: 14.732 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  6.789 ms/op
                 createUser·p0.9999: 11.921 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.124 ms/op
                 createUser·p0.9999: 10.700 ms/op
                 createUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387031
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 190639 
    [ 2.500,  3.750) = 191770 
    [ 3.750,  5.000) = 3532 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      8.076 ms/op
     p(99.9900) =     13.264 ms/op
     p(99.9990) =     15.422 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.254 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.504 ms/op
                 existUser·p0.999:  7.083 ms/op
                 existUser·p0.9999: 11.873 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 11.292 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398513
  mean =      2.407 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 201554 
    [ 2.500,  3.750) = 194232 
    [ 3.750,  5.000) = 1994 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      9.232 ms/op
     p(99.9900) =     12.897 ms/op
     p(99.9990) =     14.927 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  9.891 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  8.324 ms/op
                 getUser·p0.9999: 13.632 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  7.411 ms/op
                 getUser·p0.9999: 12.681 ms/op
                 getUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385546
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 191736 
    [ 2.500,  3.750) = 189056 
    [ 3.750,  5.000) = 3545 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.549 ms/op
     p(99.9900) =     13.761 ms/op
     p(99.9990) =     14.551 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.802 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.325 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.356 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.424 ms/op
                 listUser·p0.9999: 12.898 ms/op
                 listUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322754
  mean =      2.972 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 97915 
    [ 2.500,  3.750) = 187795 
    [ 3.750,  5.000) = 29896 
    [ 5.000,  6.250) = 5830 
    [ 6.250,  7.500) = 541 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.492 ms/op
     p(99.9000) =      9.114 ms/op
     p(99.9900) =     12.365 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.813 ± 1.494  ops/ms
ClientPb.existUser                       thrpt       3  13.201 ± 1.680  ops/ms
ClientPb.getUser                         thrpt       3  13.146 ± 1.056  ops/ms
ClientPb.listUser                        thrpt       3  10.756 ± 0.985  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.212   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.321   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.249   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.268   ms/op
ClientPb.createUser                     sample  387031   2.478 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.076           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.483           ms/op
ClientPb.existUser                      sample  398513   2.407 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.768           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.232           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  385546   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.761           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  322754   2.972 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.865           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.492           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.114           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.861           ms/op
