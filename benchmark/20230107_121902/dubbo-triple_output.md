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
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 5.146 ops/ms
# Warmup Iteration   3: 8.850 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.736 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.590 ±(99.9%) 2.426 ops/ms [Average]
  (min, avg, max) = (9.475, 9.590, 9.736), stdev = 0.133
  CI (99.9%): [7.165, 12.016] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 8.991 ops/ms
# Warmup Iteration   3: 10.070 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 9.830 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.000 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (9.830, 10.000, 10.199), stdev = 0.186
  CI (99.9%): [6.605, 13.395] (assumes normal distribution)


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
# Warmup Iteration   1: 2.961 ops/ms
# Warmup Iteration   2: 7.717 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.575 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.421 ±(99.9%) 2.696 ops/ms [Average]
  (min, avg, max) = (9.281, 9.421, 9.575), stdev = 0.148
  CI (99.9%): [6.724, 12.117] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.104 ±(99.9%) 3.407 ops/ms [Average]
  (min, avg, max) = (7.913, 8.104, 8.286), stdev = 0.187
  CI (99.9%): [4.697, 11.511] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.040 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.007 ms/op
Iteration   1: 3.381 ±(99.9%) 0.010 ms/op
Iteration   2: 3.262 ±(99.9%) 0.014 ms/op
Iteration   3: 3.350 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.331 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (3.262, 3.331, 3.381), stdev = 0.062
  CI (99.9%): [2.206, 4.456] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.004 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op
Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
Iteration   3: 3.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.220 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.195, 3.220, 3.264), stdev = 0.039
  CI (99.9%): [2.514, 3.926] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.070 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.006 ms/op
Iteration   1: 3.389 ±(99.9%) 0.002 ms/op
Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
Iteration   3: 3.311 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.330 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.288, 3.330, 3.389), stdev = 0.053
  CI (99.9%): [2.360, 4.299] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.859 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
Iteration   2: 3.892 ±(99.9%) 0.012 ms/op
Iteration   3: 3.915 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.942 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.892, 3.942, 4.020), stdev = 0.068
  CI (99.9%): [2.702, 5.182] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.031 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.011 ms/op
Iteration   1: 3.376 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  20.620 ms/op
                 createUser·p0.9999: 29.790 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.857 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283220
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4794 
    [ 2.500,  5.000) = 270722 
    [ 5.000,  7.500) = 6315 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.739 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.287 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 24.416 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  23.575 ms/op
                 existUser·p0.9999: 36.962 ms/op
                 existUser·p1.00:   37.880 ms/op

Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.236 ms/op
                 existUser·p0.999:  18.583 ms/op
                 existUser·p0.9999: 25.413 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287210
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5518 
    [ 2.500,  5.000) = 276783 
    [ 5.000,  7.500) = 3670 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     35.780 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 8.687 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  19.726 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 3.486 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  21.471 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.359 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  17.548 ms/op
                 getUser·p0.9999: 24.919 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280437
  mean =      3.423 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13373 
    [ 2.500,  5.000) = 260290 
    [ 5.000,  7.500) = 5781 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     18.074 ms/op
     p(99.9900) =     27.262 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 10.333 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.014 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.811 ms/op
                 listUser·p0.9999: 23.879 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 3.907 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 21.326 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 3.884 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 17.392 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245106
  mean =      3.915 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 236386 
    [ 5.000,  7.500) = 7096 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     23.117 ms/op
     p(99.9990) =     25.249 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.590 ± 2.426  ops/ms
ClientPb.existUser                       thrpt       3  10.000 ± 3.395  ops/ms
ClientPb.getUser                         thrpt       3   9.421 ± 2.696  ops/ms
ClientPb.listUser                        thrpt       3   8.104 ± 3.407  ops/ms
ClientPb.createUser                       avgt       3   3.331 ± 1.125   ms/op
ClientPb.existUser                        avgt       3   3.220 ± 0.706   ms/op
ClientPb.getUser                          avgt       3   3.330 ± 0.970   ms/op
ClientPb.listUser                         avgt       3   3.942 ± 1.240   ms/op
ClientPb.createUser                     sample  283220   3.389 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.376           ms/op
ClientPb.existUser                      sample  287210   3.339 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.499           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.780           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  280437   3.423 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.454           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  245106   3.915 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.362           ms/op
