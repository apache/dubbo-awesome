# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 5.814 ops/ms
# Warmup Iteration   3: 8.785 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.408 ops/ms
Iteration   3: 9.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.389 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (9.303, 9.389, 9.457), stdev = 0.079
  CI (99.9%): [7.949, 10.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.292 ops/ms
# Warmup Iteration   2: 9.024 ops/ms
# Warmup Iteration   3: 9.191 ops/ms
Iteration   1: 9.443 ops/ms
Iteration   2: 9.772 ops/ms
Iteration   3: 9.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.581 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (9.443, 9.581, 9.772), stdev = 0.171
  CI (99.9%): [6.467, 12.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.899 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.045 ops/ms
Iteration   1: 9.161 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.320 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (9.161, 9.320, 9.442), stdev = 0.144
  CI (99.9%): [6.692, 11.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.048 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.891 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (7.813, 7.891, 7.945), stdev = 0.069
  CI (99.9%): [6.631, 9.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.325 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.006 ms/op
Iteration   1: 3.534 ±(99.9%) 0.006 ms/op
Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
Iteration   3: 3.380 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.449 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (3.380, 3.449, 3.534), stdev = 0.078
  CI (99.9%): [2.019, 4.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.502 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.003 ms/op
Iteration   1: 3.334 ±(99.9%) 0.003 ms/op
Iteration   2: 3.313 ±(99.9%) 0.003 ms/op
Iteration   3: 3.396 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.348 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.313, 3.348, 3.396), stdev = 0.043
  CI (99.9%): [2.555, 4.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.068 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.003 ms/op
Iteration   1: 3.444 ±(99.9%) 0.005 ms/op
Iteration   2: 3.388 ±(99.9%) 0.004 ms/op
Iteration   3: 3.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.420 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.388, 3.420, 3.444), stdev = 0.029
  CI (99.9%): [2.896, 3.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.895 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.006 ms/op
Iteration   1: 4.060 ±(99.9%) 0.009 ms/op
Iteration   2: 4.010 ±(99.9%) 0.005 ms/op
Iteration   3: 4.054 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.041 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.010, 4.041, 4.060), stdev = 0.027
  CI (99.9%): [3.547, 4.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.996 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.731 ms/op
                 createUser·p0.999:  18.307 ms/op
                 createUser·p0.9999: 21.825 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.937 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.016 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 24.694 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274728
  mean =      3.494 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3809 
    [ 2.500,  5.000) = 265581 
    [ 5.000,  7.500) = 4191 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     23.452 ms/op
     p(99.9990) =     25.797 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  14.318 ms/op
                 existUser·p0.9999: 23.312 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  16.160 ms/op
                 existUser·p0.9999: 27.755 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  17.368 ms/op
                 existUser·p0.9999: 26.045 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287270
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10778 
    [ 2.500,  5.000) = 271716 
    [ 5.000,  7.500) = 3763 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     15.347 ms/op
     p(99.9900) =     26.780 ms/op
     p(99.9990) =     28.877 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.413 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 23.348 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  21.614 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.383 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.073 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  15.343 ms/op
                 getUser·p0.9999: 23.644 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280323
  mean =      3.426 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8794 
    [ 2.500,  5.000) = 265875 
    [ 5.000,  7.500) = 4606 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.188 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.744 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.012 ms/op
Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  19.130 ms/op
                 listUser·p0.9999: 24.852 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.036 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.624 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 16.336 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 4.015 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.255 ms/op
                 listUser·p0.999:  14.888 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238243
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 229630 
    [ 5.000,  7.500) = 6828 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     15.004 ms/op
     p(99.9900) =     23.795 ms/op
     p(99.9990) =     25.468 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.389 ± 1.440  ops/ms
ClientPb.existUser                       thrpt       3   9.581 ± 3.115  ops/ms
ClientPb.getUser                         thrpt       3   9.320 ± 2.628  ops/ms
ClientPb.listUser                        thrpt       3   7.891 ± 1.259  ops/ms
ClientPb.createUser                       avgt       3   3.449 ± 1.431   ms/op
ClientPb.existUser                        avgt       3   3.348 ± 0.793   ms/op
ClientPb.getUser                          avgt       3   3.420 ± 0.524   ms/op
ClientPb.listUser                         avgt       3   4.041 ± 0.494   ms/op
ClientPb.createUser                     sample  274728   3.494 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.859           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.452           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  287270   3.340 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.347           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.780           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  280323   3.426 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.707           ms/op
ClientPb.listUser                       sample  238243   4.028 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.004           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.795           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
