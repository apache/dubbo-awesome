# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.309 ops/ms
# Warmup Iteration   2: 5.908 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 9.340 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.493 ±(99.9%) 3.195 ops/ms [Average]
  (min, avg, max) = (9.340, 9.493, 9.684), stdev = 0.175
  CI (99.9%): [6.298, 12.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.243 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 9.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.017 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (9.901, 10.017, 10.144), stdev = 0.122
  CI (99.9%): [7.789, 12.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 9.270 ops/ms
Iteration   1: 9.439 ops/ms
Iteration   2: 9.941 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.708 ±(99.9%) 4.606 ops/ms [Average]
  (min, avg, max) = (9.439, 9.708, 9.941), stdev = 0.252
  CI (99.9%): [5.101, 14.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ops/ms
# Warmup Iteration   2: 7.787 ops/ms
# Warmup Iteration   3: 8.212 ops/ms
Iteration   1: 8.395 ops/ms
Iteration   2: 8.472 ops/ms
Iteration   3: 8.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.390 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (8.305, 8.390, 8.472), stdev = 0.084
  CI (99.9%): [6.863, 9.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.558 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.003 ms/op
Iteration   1: 3.232 ±(99.9%) 0.007 ms/op
Iteration   2: 3.262 ±(99.9%) 0.007 ms/op
Iteration   3: 3.145 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.145, 3.213, 3.262), stdev = 0.061
  CI (99.9%): [2.107, 4.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.612 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.006 ms/op
Iteration   1: 3.232 ±(99.9%) 0.002 ms/op
Iteration   2: 3.096 ±(99.9%) 0.011 ms/op
Iteration   3: 3.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.170 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.096, 3.170, 3.232), stdev = 0.069
  CI (99.9%): [1.912, 4.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.522 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.005 ms/op
Iteration   1: 3.198 ±(99.9%) 0.004 ms/op
Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
Iteration   3: 3.123 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (3.123, 3.178, 3.214), stdev = 0.049
  CI (99.9%): [2.287, 4.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.641 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.007 ms/op
Iteration   1: 3.800 ±(99.9%) 0.009 ms/op
Iteration   2: 3.744 ±(99.9%) 0.010 ms/op
Iteration   3: 3.735 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.759 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.735, 3.759, 3.800), stdev = 0.035
  CI (99.9%): [3.118, 4.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.013 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  14.632 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.749 ms/op
                 createUser·p0.999:  23.522 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.511 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  17.611 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286836
  mean =      3.345 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18276 
    [ 2.500,  5.000) = 261138 
    [ 5.000,  7.500) = 6350 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 26.832 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.181 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.086 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 24.187 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303096
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26266 
    [ 2.500,  5.000) = 271090 
    [ 5.000,  7.500) = 5030 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.065 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.010 ms/op
Iteration   1: 3.303 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 29.457 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.487 ms/op
                 getUser·p0.9999: 22.054 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 22.504 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297742
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12382 
    [ 2.500,  5.000) = 279637 
    [ 5.000,  7.500) = 4777 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.927 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     24.162 ms/op
     p(99.9990) =     29.855 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.147 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  15.806 ms/op
                 listUser·p0.9999: 22.797 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.445 ms/op
                 listUser·p0.999:  14.535 ms/op
                 listUser·p0.9999: 18.794 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.725 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   3.916 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 16.161 ms/op
                 listUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254621
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 245668 
    [ 5.000,  7.500) = 6785 
    [ 7.500, 10.000) = 1474 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     20.992 ms/op
     p(99.9990) =     23.608 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.493 ± 3.195  ops/ms
ClientPb.existUser                       thrpt       3  10.017 ± 2.227  ops/ms
ClientPb.getUser                         thrpt       3   9.708 ± 4.606  ops/ms
ClientPb.listUser                        thrpt       3   8.390 ± 1.527  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 1.107   ms/op
ClientPb.existUser                        avgt       3   3.170 ± 1.258   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 0.892   ms/op
ClientPb.listUser                         avgt       3   3.759 ± 0.641   ms/op
ClientPb.createUser                     sample  286836   3.345 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.511           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.596           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.427           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.312           ms/op
ClientPb.existUser                      sample  303096   3.166 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.810           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.319           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  297742   3.221 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.942           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.927           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.236           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.162           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  254621   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.992           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.921           ms/op
