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
# Warmup Iteration   1: 2.328 ops/ms
# Warmup Iteration   2: 5.326 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 9.893 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.847 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (9.664, 9.847, 9.984), stdev = 0.165
  CI (99.9%): [6.844, 12.850] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.504 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (10.382, 10.504, 10.596), stdev = 0.110
  CI (99.9%): [8.491, 12.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 8.676 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 9.909 ops/ms
Iteration   2: 10.186 ops/ms
Iteration   3: 10.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.054 ±(99.9%) 2.530 ops/ms [Average]
  (min, avg, max) = (9.909, 10.054, 10.186), stdev = 0.139
  CI (99.9%): [7.524, 12.583] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 6.885 ops/ms
# Warmup Iteration   3: 8.395 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.404 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.415 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (8.332, 8.415, 8.510), stdev = 0.090
  CI (99.9%): [6.782, 10.049] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.536 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
Iteration   2: 3.309 ±(99.9%) 0.007 ms/op
Iteration   3: 3.142 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (3.128, 3.193, 3.309), stdev = 0.101
  CI (99.9%): [1.356, 5.030] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.004 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.060 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.045, 3.060, 3.070), stdev = 0.013
  CI (99.9%): [2.823, 3.296] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.218 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.004 ms/op
Iteration   1: 3.245 ±(99.9%) 0.004 ms/op
Iteration   2: 3.273 ±(99.9%) 0.004 ms/op
Iteration   3: 3.282 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.266 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.245, 3.266, 3.282), stdev = 0.019
  CI (99.9%): [2.922, 3.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.007 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
Iteration   2: 3.694 ±(99.9%) 0.011 ms/op
Iteration   3: 3.659 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.716 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (3.659, 3.716, 3.794), stdev = 0.070
  CI (99.9%): [2.433, 4.998] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.789 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  11.815 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  18.678 ms/op
                 createUser·p0.9999: 25.134 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 21.994 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300345
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27242 
    [ 2.500,  5.000) = 268292 
    [ 5.000,  7.500) = 3950 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     15.231 ms/op
     p(99.9900) =     23.949 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.523 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
Iteration   1: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  10.959 ms/op
                 existUser·p0.9999: 23.750 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.045 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  14.190 ms/op
                 existUser·p0.9999: 23.756 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306269
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16164 
    [ 2.500,  5.000) = 285388 
    [ 5.000,  7.500) = 3836 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.666 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 9.695 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.012 ms/op
Iteration   1: 3.154 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  15.221 ms/op
                 getUser·p0.9999: 24.211 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  20.055 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  11.451 ms/op
                 getUser·p0.9999: 21.045 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295185
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16026 
    [ 2.500,  5.000) = 271356 
    [ 5.000,  7.500) = 6715 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     15.218 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.048 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 23.173 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.742 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 15.401 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 19.917 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250299
  mean =      3.833 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 241933 
    [ 5.000,  7.500) = 6448 
    [ 7.500, 10.000) = 1300 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     22.117 ms/op
     p(99.9990) =     23.904 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.847 ± 3.003  ops/ms
ClientPb.existUser                       thrpt       3  10.504 ± 2.013  ops/ms
ClientPb.getUser                         thrpt       3  10.054 ± 2.530  ops/ms
ClientPb.listUser                        thrpt       3   8.415 ± 1.634  ops/ms
ClientPb.createUser                       avgt       3   3.193 ± 1.837   ms/op
ClientPb.existUser                        avgt       3   3.060 ± 0.236   ms/op
ClientPb.getUser                          avgt       3   3.266 ± 0.345   ms/op
ClientPb.listUser                         avgt       3   3.716 ± 1.282   ms/op
ClientPb.createUser                     sample  300345   3.195 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.231           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.949           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  306269   3.133 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  295185   3.254 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.641           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.936           ms/op
ClientPb.listUser                       sample  250299   3.833 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.262           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.168           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
