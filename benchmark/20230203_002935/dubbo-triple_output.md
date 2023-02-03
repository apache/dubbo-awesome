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
# Warmup Iteration   1: 1.064 ops/ms
# Warmup Iteration   2: 2.209 ops/ms
# Warmup Iteration   3: 4.293 ops/ms
Iteration   1: 5.149 ops/ms
Iteration   2: 5.377 ops/ms
Iteration   3: 4.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.113 ±(99.9%) 5.160 ops/ms [Average]
  (min, avg, max) = (4.814, 5.113, 5.377), stdev = 0.283
  CI (99.9%): [≈ 0, 10.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.363 ops/ms
# Warmup Iteration   2: 4.009 ops/ms
# Warmup Iteration   3: 5.650 ops/ms
Iteration   1: 5.992 ops/ms
Iteration   2: 5.885 ops/ms
Iteration   3: 5.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.891 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (5.796, 5.891, 5.992), stdev = 0.098
  CI (99.9%): [4.101, 7.681] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.612 ops/ms
# Warmup Iteration   2: 3.849 ops/ms
# Warmup Iteration   3: 5.586 ops/ms
Iteration   1: 5.432 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.568 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (5.432, 5.568, 5.678), stdev = 0.125
  CI (99.9%): [3.286, 7.850] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.680 ops/ms
# Warmup Iteration   2: 3.798 ops/ms
# Warmup Iteration   3: 4.287 ops/ms
Iteration   1: 4.859 ops/ms
Iteration   2: 4.979 ops/ms
Iteration   3: 4.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.883 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (4.812, 4.883, 4.979), stdev = 0.086
  CI (99.9%): [3.311, 6.456] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 21.733 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 8.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.907 ±(99.9%) 0.012 ms/op
Iteration   1: 5.993 ±(99.9%) 0.013 ms/op
Iteration   2: 5.855 ±(99.9%) 0.021 ms/op
Iteration   3: 5.888 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.912 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (5.855, 5.912, 5.993), stdev = 0.072
  CI (99.9%): [4.597, 7.227] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.423 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.009 ms/op
Iteration   1: 5.428 ±(99.9%) 0.011 ms/op
Iteration   2: 5.288 ±(99.9%) 0.014 ms/op
Iteration   3: 5.168 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.295 ±(99.9%) 2.371 ms/op [Average]
  (min, avg, max) = (5.168, 5.295, 5.428), stdev = 0.130
  CI (99.9%): [2.923, 7.666] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 22.050 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.011 ms/op
Iteration   1: 5.836 ±(99.9%) 0.009 ms/op
Iteration   2: 5.538 ±(99.9%) 0.011 ms/op
Iteration   3: 5.433 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.602 ±(99.9%) 3.812 ms/op [Average]
  (min, avg, max) = (5.433, 5.602, 5.836), stdev = 0.209
  CI (99.9%): [1.790, 9.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.344 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 8.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.579 ±(99.9%) 0.018 ms/op
Iteration   1: 6.826 ±(99.9%) 0.011 ms/op
Iteration   2: 6.684 ±(99.9%) 0.012 ms/op
Iteration   3: 6.540 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.683 ±(99.9%) 2.614 ms/op [Average]
  (min, avg, max) = (6.540, 6.683, 6.826), stdev = 0.143
  CI (99.9%): [4.069, 9.297] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.059 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 7.929 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.026 ±(99.9%) 0.028 ms/op
Iteration   1: 5.711 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   7.102 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  26.445 ms/op
                 createUser·p0.9999: 31.739 ms/op
                 createUser·p1.00:   32.604 ms/op

Iteration   2: 5.661 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   7.946 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  28.030 ms/op
                 createUser·p0.9999: 31.688 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 5.667 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  16.535 ms/op
                 createUser·p0.9999: 38.236 ms/op
                 createUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168888
  mean =      5.680 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 51547 
    [ 5.000,  7.500) = 104732 
    [ 7.500, 10.000) = 9685 
    [10.000, 12.500) = 2050 
    [12.500, 15.000) = 548 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     18.845 ms/op
     p(99.9900) =     37.501 ms/op
     p(99.9990) =     39.534 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.056 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.159 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.711 ±(99.9%) 0.025 ms/op
Iteration   1: 5.497 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   8.053 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  24.904 ms/op
                 existUser·p0.9999: 28.165 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   2: 5.555 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   8.225 ms/op
                 existUser·p0.99:   11.780 ms/op
                 existUser·p0.999:  26.166 ms/op
                 existUser·p0.9999: 29.106 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   3: 5.464 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   9.942 ms/op
                 existUser·p0.999:  13.770 ms/op
                 existUser·p0.9999: 38.203 ms/op
                 existUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174354
  mean =      5.505 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 60020 
    [ 5.000,  7.500) = 103215 
    [ 7.500, 10.000) = 8225 
    [10.000, 12.500) = 2146 
    [12.500, 15.000) = 456 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     20.075 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     39.175 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.804 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.679 ±(99.9%) 0.021 ms/op
Iteration   1: 5.930 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.851 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.809 ms/op
                 getUser·p0.95:   9.421 ms/op
                 getUser·p0.99:   14.696 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 28.666 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 5.890 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.073 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   12.894 ms/op
                 getUser·p0.999:  24.995 ms/op
                 getUser·p0.9999: 35.492 ms/op
                 getUser·p1.00:   36.241 ms/op

Iteration   3: 6.556 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   3.215 ms/op
                 getUser·p0.50:   6.054 ms/op
                 getUser·p0.90:   8.798 ms/op
                 getUser·p0.95:   10.224 ms/op
                 getUser·p0.99:   13.746 ms/op
                 getUser·p0.999:  30.879 ms/op
                 getUser·p0.9999: 40.975 ms/op
                 getUser·p1.00:   41.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 157143
  mean =      6.111 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 40339 
    [ 5.000, 10.000) = 109984 
    [10.000, 15.000) = 5727 
    [15.000, 20.000) = 815 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      8.282 ms/op
     p(95.0000) =      9.716 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     26.490 ms/op
     p(99.9900) =     40.305 ms/op
     p(99.9990) =     41.559 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.788 ±(99.9%) 0.382 ms/op
# Warmup Iteration   2: 9.544 ±(99.9%) 0.083 ms/op
# Warmup Iteration   3: 6.779 ±(99.9%) 0.032 ms/op
Iteration   1: 6.681 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.664 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  28.377 ms/op
                 listUser·p0.9999: 31.701 ms/op
                 listUser·p1.00:   32.276 ms/op

Iteration   2: 6.844 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  29.501 ms/op
                 listUser·p0.9999: 33.466 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   3: 6.805 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   11.975 ms/op
                 listUser·p0.999:  30.834 ms/op
                 listUser·p0.9999: 37.152 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141556
  mean =      6.776 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 2228 
    [ 5.000,  7.500) = 115626 
    [ 7.500, 10.000) = 17989 
    [10.000, 12.500) = 4033 
    [12.500, 15.000) = 906 
    [15.000, 17.500) = 337 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      6.382 ms/op
     p(90.0000) =      8.200 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.894 ms/op
     p(99.9000) =     29.393 ms/op
     p(99.9900) =     35.576 ms/op
     p(99.9990) =     37.787 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.113 ± 5.160  ops/ms
ClientPb.existUser                       thrpt       3   5.891 ± 1.790  ops/ms
ClientPb.getUser                         thrpt       3   5.568 ± 2.282  ops/ms
ClientPb.listUser                        thrpt       3   4.883 ± 1.573  ops/ms
ClientPb.createUser                       avgt       3   5.912 ± 1.315   ms/op
ClientPb.existUser                        avgt       3   5.295 ± 2.371   ms/op
ClientPb.getUser                          avgt       3   5.602 ± 3.812   ms/op
ClientPb.listUser                         avgt       3   6.683 ± 2.614   ms/op
ClientPb.createUser                     sample  168888   5.680 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.126           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.076           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.845           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.501           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.715           ms/op
ClientPb.existUser                      sample  174354   5.505 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.808           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.954           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.322           ms/op
ClientPb.getUser                        sample  157143   6.111 ± 0.017   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.282           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.716           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.664           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.490           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.305           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.746           ms/op
ClientPb.listUser                       sample  141556   6.776 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.664           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.382           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.535           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.894           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.393           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.814           ms/op
