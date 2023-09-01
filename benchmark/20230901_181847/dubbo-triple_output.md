# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 6.061 ops/ms
# Warmup Iteration   3: 9.058 ops/ms
Iteration   1: 9.337 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.428 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (9.337, 9.428, 9.481), stdev = 0.079
  CI (99.9%): [7.993, 10.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 9.904 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 9.925 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.964 ±(99.9%) 3.920 ops/ms [Average]
  (min, avg, max) = (9.772, 9.964, 10.196), stdev = 0.215
  CI (99.9%): [6.044, 13.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 9.821 ops/ms
Iteration   1: 9.564 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.701 ±(99.9%) 3.760 ops/ms [Average]
  (min, avg, max) = (9.564, 9.701, 9.938), stdev = 0.206
  CI (99.9%): [5.941, 13.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.485 ops/ms
# Warmup Iteration   2: 7.815 ops/ms
# Warmup Iteration   3: 8.033 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.253 ops/ms
Iteration   3: 8.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.313 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (8.187, 8.313, 8.500), stdev = 0.165
  CI (99.9%): [5.302, 11.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.929 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.007 ms/op
Iteration   1: 3.402 ±(99.9%) 0.008 ms/op
Iteration   2: 3.345 ±(99.9%) 0.005 ms/op
Iteration   3: 3.241 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.330 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (3.241, 3.330, 3.402), stdev = 0.082
  CI (99.9%): [1.842, 4.817] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.003 ms/op
Iteration   1: 3.119 ±(99.9%) 0.003 ms/op
Iteration   2: 3.210 ±(99.9%) 0.006 ms/op
Iteration   3: 3.131 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.153 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.119, 3.153, 3.210), stdev = 0.050
  CI (99.9%): [2.242, 4.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.117 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.002 ms/op
Iteration   1: 3.200 ±(99.9%) 0.004 ms/op
Iteration   2: 3.137 ±(99.9%) 0.005 ms/op
Iteration   3: 3.338 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.225 ±(99.9%) 1.880 ms/op [Average]
  (min, avg, max) = (3.137, 3.225, 3.338), stdev = 0.103
  CI (99.9%): [1.345, 5.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.317 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.006 ms/op
Iteration   1: 4.020 ±(99.9%) 0.008 ms/op
Iteration   2: 3.840 ±(99.9%) 0.009 ms/op
Iteration   3: 3.776 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.879 ±(99.9%) 2.308 ms/op [Average]
  (min, avg, max) = (3.776, 3.879, 4.020), stdev = 0.127
  CI (99.9%): [1.570, 6.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.549 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.012 ms/op
Iteration   1: 3.355 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  18.478 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  19.937 ms/op
                 createUser·p0.9999: 22.724 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.735 ms/op
                 createUser·p0.9999: 24.158 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291734
  mean =      3.289 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20048 
    [ 2.500,  5.000) = 264410 
    [ 5.000,  7.500) = 5895 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     19.121 ms/op
     p(99.9900) =     24.728 ms/op
     p(99.9990) =     26.321 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.010 ms/op
Iteration   1: 3.185 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.668 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 34.144 ms/op
                 existUser·p1.00:   36.766 ms/op

Iteration   2: 3.392 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.408 ms/op
                 existUser·p0.999:  21.004 ms/op
                 existUser·p0.9999: 25.348 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.323 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  18.700 ms/op
                 existUser·p0.9999: 29.360 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291082
  mean =      3.298 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13645 
    [ 2.500,  5.000) = 268224 
    [ 5.000,  7.500) = 7523 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     16.201 ms/op
     p(99.9900) =     32.329 ms/op
     p(99.9990) =     35.256 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.654 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.011 ms/op
Iteration   1: 3.426 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  20.327 ms/op
                 getUser·p0.9999: 24.783 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.599 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  19.104 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  15.177 ms/op
                 getUser·p0.9999: 23.130 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282792
  mean =      3.394 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17791 
    [ 2.500,  5.000) = 255775 
    [ 5.000,  7.500) = 7677 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     15.716 ms/op
     p(99.9900) =     23.944 ms/op
     p(99.9990) =     25.385 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.074 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.013 ms/op
Iteration   1: 4.540 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   30.081 ms/op
                 listUser·p0.999:  42.895 ms/op
                 listUser·p0.9999: 69.724 ms/op
                 listUser·p1.00:   71.959 ms/op

Iteration   2: 4.611 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   30.376 ms/op
                 listUser·p0.999:  44.022 ms/op
                 listUser·p0.9999: 52.756 ms/op
                 listUser·p1.00:   53.543 ms/op

Iteration   3: 4.576 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   29.950 ms/op
                 listUser·p0.999:  54.277 ms/op
                 listUser·p0.9999: 73.010 ms/op
                 listUser·p1.00:   82.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209672
  mean =      4.576 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 194681 
    [ 5.000, 10.000) = 9296 
    [10.000, 15.000) = 866 
    [15.000, 20.000) = 504 
    [20.000, 25.000) = 606 
    [25.000, 30.000) = 1564 
    [30.000, 35.000) = 1347 
    [35.000, 40.000) = 439 
    [40.000, 45.000) = 146 
    [45.000, 50.000) = 63 
    [50.000, 55.000) = 72 
    [55.000, 60.000) = 25 
    [60.000, 65.000) = 20 
    [65.000, 70.000) = 20 
    [70.000, 75.000) = 21 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      6.701 ms/op
     p(99.0000) =     30.114 ms/op
     p(99.9000) =     45.766 ms/op
     p(99.9900) =     70.272 ms/op
     p(99.9990) =     79.633 ms/op
     p(99.9999) =     82.051 ms/op
    p(100.0000) =     82.051 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.428 ± 1.435  ops/ms
ClientPb.existUser                       thrpt       3   9.964 ± 3.920  ops/ms
ClientPb.getUser                         thrpt       3   9.701 ± 3.760  ops/ms
ClientPb.listUser                        thrpt       3   8.313 ± 3.011  ops/ms
ClientPb.createUser                       avgt       3   3.330 ± 1.488   ms/op
ClientPb.existUser                        avgt       3   3.153 ± 0.911   ms/op
ClientPb.getUser                          avgt       3   3.225 ± 1.880   ms/op
ClientPb.listUser                         avgt       3   3.879 ± 2.308   ms/op
ClientPb.createUser                     sample  291734   3.289 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.121           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.728           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  291082   3.298 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.083           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.201           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.766           ms/op
ClientPb.getUser                        sample  282792   3.394 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.221           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.390           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.944           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.494           ms/op
ClientPb.listUser                       sample  209672   4.576 ± 0.030   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.200           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.99        sample          30.114           ms/op
ClientPb.listUser:listUser·p0.999       sample          45.766           ms/op
ClientPb.listUser:listUser·p0.9999      sample          70.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          82.051           ms/op
