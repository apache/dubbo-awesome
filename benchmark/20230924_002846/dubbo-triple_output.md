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
# Warmup Iteration   1: 2.246 ops/ms
# Warmup Iteration   2: 5.348 ops/ms
# Warmup Iteration   3: 8.773 ops/ms
Iteration   1: 9.357 ops/ms
Iteration   2: 9.313 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.343 ±(99.9%) 0.485 ops/ms [Average]
  (min, avg, max) = (9.313, 9.343, 9.360), stdev = 0.027
  CI (99.9%): [8.858, 9.828] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.261 ops/ms
# Warmup Iteration   2: 8.893 ops/ms
# Warmup Iteration   3: 9.347 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 9.846 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.828 ±(99.9%) 1.154 ops/ms [Average]
  (min, avg, max) = (9.757, 9.828, 9.879), stdev = 0.063
  CI (99.9%): [8.673, 10.982] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 8.956 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.405 ops/ms
Iteration   2: 9.695 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.520 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (9.405, 9.520, 9.695), stdev = 0.155
  CI (99.9%): [6.700, 12.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.351 ops/ms
# Warmup Iteration   2: 7.342 ops/ms
# Warmup Iteration   3: 7.735 ops/ms
Iteration   1: 8.034 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.979 ±(99.9%) 1.430 ops/ms [Average]
  (min, avg, max) = (7.889, 7.979, 8.034), stdev = 0.078
  CI (99.9%): [6.548, 9.409] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.724 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.005 ms/op
Iteration   1: 3.411 ±(99.9%) 0.006 ms/op
Iteration   2: 3.495 ±(99.9%) 0.004 ms/op
Iteration   3: 3.402 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.436 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (3.402, 3.436, 3.495), stdev = 0.051
  CI (99.9%): [2.504, 4.368] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.802 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.004 ms/op
Iteration   1: 3.274 ±(99.9%) 0.003 ms/op
Iteration   2: 3.326 ±(99.9%) 0.003 ms/op
Iteration   3: 3.317 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.274, 3.306, 3.326), stdev = 0.028
  CI (99.9%): [2.802, 3.809] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.754 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.002 ms/op
Iteration   1: 3.438 ±(99.9%) 0.004 ms/op
Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
Iteration   3: 3.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.417, 3.436, 3.452), stdev = 0.018
  CI (99.9%): [3.108, 3.763] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.299 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.007 ms/op
Iteration   1: 4.037 ±(99.9%) 0.008 ms/op
Iteration   2: 4.038 ±(99.9%) 0.007 ms/op
Iteration   3: 4.057 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.044 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (4.037, 4.044, 4.057), stdev = 0.012
  CI (99.9%): [3.833, 4.255] (assumes normal distribution)


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
# Warmup Iteration   1: 9.410 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.079 ms/op
                 createUser·p0.9999: 22.195 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.440 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  21.265 ms/op
                 createUser·p0.9999: 24.693 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  17.776 ms/op
                 createUser·p0.9999: 24.604 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277348
  mean =      3.463 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5836 
    [ 2.500,  5.000) = 266916 
    [ 5.000,  7.500) = 3517 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.419 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
Iteration   1: 3.316 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.208 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 20.262 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  18.727 ms/op
                 existUser·p0.9999: 22.900 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.359 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.735 ms/op
                 existUser·p0.999:  16.522 ms/op
                 existUser·p0.9999: 22.724 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287567
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4470 
    [ 2.500,  5.000) = 278807 
    [ 5.000,  7.500) = 3203 
    [ 7.500, 10.000) = 514 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.010 ms/op
Iteration   1: 3.516 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.005 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  14.366 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   2: 3.409 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.130 ms/op
                 getUser·p0.999:  20.782 ms/op
                 getUser·p0.9999: 24.019 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278633
  mean =      3.444 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3702 
    [ 2.500,  5.000) = 267643 
    [ 5.000,  7.500) = 5823 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     15.558 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.856 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 10.077 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.011 ms/op
Iteration   1: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  19.720 ms/op
                 listUser·p0.9999: 26.846 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.133 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.865 ms/op
                 listUser·p0.99:   7.337 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 17.253 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 4.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.432 ms/op
                 listUser·p0.9999: 15.535 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235632
  mean =      4.071 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 227178 
    [ 5.000,  7.500) = 6635 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     25.686 ms/op
     p(99.9990) =     27.226 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.343 ± 0.485  ops/ms
ClientPb.existUser                       thrpt       3   9.828 ± 1.154  ops/ms
ClientPb.getUser                         thrpt       3   9.520 ± 2.819  ops/ms
ClientPb.listUser                        thrpt       3   7.979 ± 1.430  ops/ms
ClientPb.createUser                       avgt       3   3.436 ± 0.932   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.504   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   4.044 ± 0.211   ms/op
ClientPb.createUser                     sample  277348   3.463 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.631           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  287567   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.544           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.757           ms/op
ClientPb.getUser                        sample  278633   3.444 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.897           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.558           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.707           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345           ms/op
ClientPb.listUser                       sample  235632   4.071 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.598           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.329           ms/op
