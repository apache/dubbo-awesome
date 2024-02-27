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
# Warmup Iteration   1: 5.475 ops/ms
# Warmup Iteration   2: 12.170 ops/ms
# Warmup Iteration   3: 12.422 ops/ms
Iteration   1: 12.635 ops/ms
Iteration   2: 12.789 ops/ms
Iteration   3: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.729 ±(99.9%) 1.499 ops/ms [Average]
  (min, avg, max) = (12.635, 12.729, 12.789), stdev = 0.082
  CI (99.9%): [11.230, 14.228] (assumes normal distribution)


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
# Warmup Iteration   1: 8.096 ops/ms
# Warmup Iteration   2: 13.060 ops/ms
# Warmup Iteration   3: 13.165 ops/ms
Iteration   1: 13.279 ops/ms
Iteration   2: 13.317 ops/ms
Iteration   3: 13.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.257 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (13.174, 13.257, 13.317), stdev = 0.074
  CI (99.9%): [11.908, 14.605] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.856 ops/ms
# Warmup Iteration   2: 12.685 ops/ms
# Warmup Iteration   3: 12.958 ops/ms
Iteration   1: 13.051 ops/ms
Iteration   2: 12.957 ops/ms
Iteration   3: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.989 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (12.957, 12.989, 13.051), stdev = 0.053
  CI (99.9%): [12.018, 13.960] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.632 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.790 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 10.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.794 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (10.750, 10.794, 10.843), stdev = 0.047
  CI (99.9%): [9.943, 11.646] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.486, 2.495, 2.511), stdev = 0.014
  CI (99.9%): [2.235, 2.754] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.419 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.419, 2.435, 2.444), stdev = 0.014
  CI (99.9%): [2.186, 2.683] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.002 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (2.471, 2.486, 2.505), stdev = 0.017
  CI (99.9%): [2.169, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.004 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.984, 2.998, 3.012), stdev = 0.014
  CI (99.9%): [2.742, 3.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.764 ms/op
                 createUser·p0.9999: 13.342 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 12.242 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 11.315 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383246
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184964 
    [ 2.500,  3.750) = 194167 
    [ 3.750,  5.000) = 3302 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.331 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 13.235 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.804 ms/op
                 existUser·p0.9999: 12.857 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395246
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 198494 
    [ 2.500,  3.750) = 193564 
    [ 3.750,  5.000) = 2374 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 132 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     12.935 ms/op
     p(99.9990) =     13.634 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  6.436 ms/op
                 getUser·p0.9999: 12.797 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.122 ms/op
                 getUser·p0.9999: 12.784 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.887 ms/op
                 getUser·p0.9999: 11.208 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385890
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 192306 
    [ 2.500,  3.750) = 189068 
    [ 3.750,  5.000) = 3234 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.317 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     13.507 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.942 ms/op
                 listUser·p0.9999: 11.904 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.621 ms/op
                 listUser·p0.9999: 12.246 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 11.207 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321650
  mean =      2.981 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 97087 
    [ 2.500,  3.750) = 188513 
    [ 3.750,  5.000) = 29272 
    [ 5.000,  6.250) = 5301 
    [ 6.250,  7.500) = 665 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.729 ± 1.499  ops/ms
ClientPb.existUser                       thrpt       3  13.257 ± 1.348  ops/ms
ClientPb.getUser                         thrpt       3  12.989 ± 0.971  ops/ms
ClientPb.listUser                        thrpt       3  10.794 ± 0.852  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.259   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.249   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.317   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.256   ms/op
ClientPb.createUser                     sample  383246   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.701           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.315           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.186           ms/op
ClientPb.existUser                      sample  395246   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.950           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  385890   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.628           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.317           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.698           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.828           ms/op
ClientPb.listUser                       sample  321650   2.981 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.751           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
