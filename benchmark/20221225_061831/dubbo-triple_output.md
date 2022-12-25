# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 5.944 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.922 ±(99.9%) 4.270 ops/ms [Average]
  (min, avg, max) = (9.778, 9.922, 10.192), stdev = 0.234
  CI (99.9%): [5.652, 14.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ops/ms
# Warmup Iteration   2: 9.705 ops/ms
# Warmup Iteration   3: 10.094 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.708 ops/ms
Iteration   3: 10.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.587 ±(99.9%) 3.173 ops/ms [Average]
  (min, avg, max) = (10.388, 10.587, 10.708), stdev = 0.174
  CI (99.9%): [7.414, 13.761] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 9.926 ops/ms
Iteration   1: 10.240 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 9.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.004 ±(99.9%) 3.795 ops/ms [Average]
  (min, avg, max) = (9.851, 10.004, 10.240), stdev = 0.208
  CI (99.9%): [6.208, 13.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.508 ops/ms
Iteration   2: 8.492 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.523 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (8.492, 8.523, 8.568), stdev = 0.040
  CI (99.9%): [7.797, 9.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.002 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
Iteration   2: 3.152 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.114 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.063, 3.114, 3.152), stdev = 0.046
  CI (99.9%): [2.277, 3.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.019 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.001 ms/op
Iteration   1: 3.003 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.025 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (3.003, 3.025, 3.038), stdev = 0.019
  CI (99.9%): [2.675, 3.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.850 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.002 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op
Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
Iteration   3: 3.084 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.144 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (3.084, 3.144, 3.183), stdev = 0.053
  CI (99.9%): [2.176, 4.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.241 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.006 ms/op
Iteration   1: 3.655 ±(99.9%) 0.009 ms/op
Iteration   2: 3.723 ±(99.9%) 0.005 ms/op
Iteration   3: 3.721 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.700 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.655, 3.700, 3.723), stdev = 0.039
  CI (99.9%): [2.991, 4.409] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.184 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  9.823 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   2: 3.344 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  15.843 ms/op
                 createUser·p0.9999: 22.652 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293108
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22382 
    [ 2.500,  5.000) = 263668 
    [ 5.000,  7.500) = 5986 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     27.810 ms/op
     p(99.9990) =     28.510 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.675 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.053 ms/op
                 existUser·p0.9999: 22.337 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.220 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.694 ms/op
                 existUser·p0.999:  16.124 ms/op
                 existUser·p0.9999: 22.088 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302667
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21411 
    [ 2.500,  5.000) = 273869 
    [ 5.000,  7.500) = 6616 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.069 ms/op
     p(99.9900) =     21.585 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 19.256 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  19.378 ms/op
                 getUser·p0.9999: 24.446 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294109
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12389 
    [ 2.500,  5.000) = 273179 
    [ 5.000,  7.500) = 7608 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     22.531 ms/op
     p(99.9990) =     25.071 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
Iteration   1: 3.656 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 3.648 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.201 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259930
  mean =      3.689 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 252871 
    [ 5.000,  7.500) = 5099 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     13.601 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     20.428 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.922 ± 4.270  ops/ms
ClientPb.existUser                       thrpt       3  10.587 ± 3.173  ops/ms
ClientPb.getUser                         thrpt       3  10.004 ± 3.795  ops/ms
ClientPb.listUser                        thrpt       3   8.523 ± 0.726  ops/ms
ClientPb.createUser                       avgt       3   3.114 ± 0.836   ms/op
ClientPb.existUser                        avgt       3   3.025 ± 0.350   ms/op
ClientPb.getUser                          avgt       3   3.144 ± 0.969   ms/op
ClientPb.listUser                         avgt       3   3.700 ± 0.709   ms/op
ClientPb.createUser                     sample  293108   3.274 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.803           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.417           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.810           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.541           ms/op
ClientPb.existUser                      sample  302667   3.172 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.100           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.069           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.585           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  294109   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.993           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.531           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  259930   3.689 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.493           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.055           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.546           ms/op
