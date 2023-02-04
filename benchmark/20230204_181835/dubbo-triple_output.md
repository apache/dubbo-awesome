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
# Warmup Iteration   1: 2.681 ops/ms
# Warmup Iteration   2: 6.701 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 10.156 ops/ms
Iteration   3: 10.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.013 ±(99.9%) 3.000 ops/ms [Average]
  (min, avg, max) = (9.833, 10.013, 10.156), stdev = 0.164
  CI (99.9%): [7.014, 13.013] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.417 ops/ms
# Warmup Iteration   2: 9.323 ops/ms
# Warmup Iteration   3: 9.785 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 9.930 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.278 ±(99.9%) 5.989 ops/ms [Average]
  (min, avg, max) = (9.930, 10.278, 10.583), stdev = 0.328
  CI (99.9%): [4.289, 16.267] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.543 ops/ms
# Warmup Iteration   2: 9.283 ops/ms
# Warmup Iteration   3: 9.463 ops/ms
Iteration   1: 9.746 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 9.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.904 ±(99.9%) 5.592 ops/ms [Average]
  (min, avg, max) = (9.709, 9.904, 10.257), stdev = 0.307
  CI (99.9%): [4.312, 15.496] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.392 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.274 ±(99.9%) 2.478 ops/ms [Average]
  (min, avg, max) = (8.125, 8.274, 8.392), stdev = 0.136
  CI (99.9%): [5.796, 10.751] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.663 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.006 ms/op
Iteration   1: 3.299 ±(99.9%) 0.007 ms/op
Iteration   2: 3.379 ±(99.9%) 0.003 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.289 ±(99.9%) 1.722 ms/op [Average]
  (min, avg, max) = (3.191, 3.289, 3.379), stdev = 0.094
  CI (99.9%): [1.567, 5.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.750 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.004 ms/op
Iteration   1: 3.201 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
Iteration   3: 3.240 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.146 ±(99.9%) 2.382 ms/op [Average]
  (min, avg, max) = (2.997, 3.146, 3.240), stdev = 0.131
  CI (99.9%): [0.764, 5.529] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.304 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.002 ms/op
Iteration   1: 3.201 ±(99.9%) 0.006 ms/op
Iteration   2: 3.258 ±(99.9%) 0.005 ms/op
Iteration   3: 3.143 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.143, 3.201, 3.258), stdev = 0.058
  CI (99.9%): [2.150, 4.252] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.481 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.006 ms/op
Iteration   1: 3.756 ±(99.9%) 0.008 ms/op
Iteration   2: 3.783 ±(99.9%) 0.008 ms/op
Iteration   3: 3.698 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.746 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.698, 3.746, 3.783), stdev = 0.043
  CI (99.9%): [2.953, 4.538] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.506 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
Iteration   1: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  19.930 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.631 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.322 ms/op
                 createUser·p0.999:  14.947 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298716
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18196 
    [ 2.500,  5.000) = 274977 
    [ 5.000,  7.500) = 4497 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     16.033 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     24.249 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 22.617 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 22.138 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  8.343 ms/op
                 existUser·p0.9999: 24.248 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312179
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13838 
    [ 2.500,  5.000) = 294278 
    [ 5.000,  7.500) = 3580 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     11.585 ms/op
     p(99.9900) =     22.799 ms/op
     p(99.9990) =     25.048 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.895 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.345 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  17.917 ms/op
                 getUser·p0.9999: 20.906 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.258 ms/op
                 getUser·p0.9999: 24.801 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  14.667 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290727
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17827 
    [ 2.500,  5.000) = 265131 
    [ 5.000,  7.500) = 6857 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.324 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.506 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.676 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 23.807 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 3.799 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  13.993 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247641
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 238422 
    [ 5.000,  7.500) = 6755 
    [ 7.500, 10.000) = 1604 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     21.380 ms/op
     p(99.9990) =     30.240 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.013 ± 3.000  ops/ms
ClientPb.existUser                       thrpt       3  10.278 ± 5.989  ops/ms
ClientPb.getUser                         thrpt       3   9.904 ± 5.592  ops/ms
ClientPb.listUser                        thrpt       3   8.274 ± 2.478  ops/ms
ClientPb.createUser                       avgt       3   3.289 ± 1.722   ms/op
ClientPb.existUser                        avgt       3   3.146 ± 2.382   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 1.051   ms/op
ClientPb.listUser                         avgt       3   3.746 ± 0.792   ms/op
ClientPb.createUser                     sample  298716   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.073           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.033           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.118           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  312179   3.075 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.036           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.585           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.799           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  290727   3.301 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.324           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  247641   3.872 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
