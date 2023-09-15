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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 5.972 ops/ms
# Warmup Iteration   3: 8.849 ops/ms
Iteration   1: 9.245 ops/ms
Iteration   2: 9.451 ops/ms
Iteration   3: 9.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.386 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (9.245, 9.386, 9.463), stdev = 0.122
  CI (99.9%): [7.156, 11.617] (assumes normal distribution)


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
# Warmup Iteration   1: 3.333 ops/ms
# Warmup Iteration   2: 9.283 ops/ms
# Warmup Iteration   3: 9.360 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 9.749 ops/ms
Iteration   3: 9.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.830 ±(99.9%) 2.299 ops/ms [Average]
  (min, avg, max) = (9.749, 9.830, 9.975), stdev = 0.126
  CI (99.9%): [7.531, 12.129] (assumes normal distribution)


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
# Warmup Iteration   1: 2.941 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 9.136 ops/ms
Iteration   1: 9.132 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.325 ±(99.9%) 3.281 ops/ms [Average]
  (min, avg, max) = (9.132, 9.325, 9.487), stdev = 0.180
  CI (99.9%): [6.044, 12.607] (assumes normal distribution)


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
# Warmup Iteration   1: 2.664 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 7.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.905 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (7.808, 7.905, 8.061), stdev = 0.137
  CI (99.9%): [5.407, 10.403] (assumes normal distribution)


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
# Warmup Iteration   1: 9.843 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.005 ms/op
Iteration   1: 3.538 ±(99.9%) 0.004 ms/op
Iteration   2: 3.389 ±(99.9%) 0.006 ms/op
Iteration   3: 3.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (3.389, 3.458, 3.538), stdev = 0.075
  CI (99.9%): [2.088, 4.827] (assumes normal distribution)


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
# Warmup Iteration   1: 9.213 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.003 ms/op
Iteration   1: 3.373 ±(99.9%) 0.003 ms/op
Iteration   2: 3.324 ±(99.9%) 0.002 ms/op
Iteration   3: 3.241 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.312 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (3.241, 3.312, 3.373), stdev = 0.067
  CI (99.9%): [2.091, 4.534] (assumes normal distribution)


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
# Warmup Iteration   1: 8.437 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.004 ms/op
Iteration   1: 3.416 ±(99.9%) 0.003 ms/op
Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
Iteration   3: 3.476 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.416, 3.444, 3.476), stdev = 0.030
  CI (99.9%): [2.895, 3.993] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.329 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.007 ms/op
Iteration   1: 4.125 ±(99.9%) 0.006 ms/op
Iteration   2: 4.029 ±(99.9%) 0.009 ms/op
Iteration   3: 4.067 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.074 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (4.029, 4.074, 4.125), stdev = 0.048
  CI (99.9%): [3.195, 4.953] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.222 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.008 ms/op
Iteration   1: 3.604 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   5.967 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  16.463 ms/op
                 createUser·p0.9999: 19.092 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.475 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  17.299 ms/op
                 createUser·p0.9999: 20.073 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.417 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  18.339 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274531
  mean =      3.497 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7495 
    [ 2.500,  5.000) = 257079 
    [ 5.000,  7.500) = 8822 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 185 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     16.756 ms/op
     p(99.9900) =     21.284 ms/op
     p(99.9990) =     24.027 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.800 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  17.160 ms/op
                 existUser·p0.9999: 19.668 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 21.534 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.407 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   7.065 ms/op
                 existUser·p0.999:  17.676 ms/op
                 existUser·p0.9999: 27.028 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290003
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6777 
    [ 2.500,  5.000) = 276344 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.859 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 8.794 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.535 ms/op
                 getUser·p0.999:  17.985 ms/op
                 getUser·p0.9999: 20.208 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  20.284 ms/op
                 getUser·p0.9999: 22.689 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.412 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 23.974 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278821
  mean =      3.441 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5304 
    [ 2.500,  5.000) = 268084 
    [ 5.000,  7.500) = 4186 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.028 ms/op
     p(99.9000) =     15.855 ms/op
     p(99.9900) =     22.936 ms/op
     p(99.9990) =     24.295 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.059 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.013 ms/op
Iteration   1: 4.136 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  16.800 ms/op
                 listUser·p0.9999: 22.958 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.150 ms/op
                 listUser·p0.9999: 16.369 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 4.050 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.453 ms/op
                 listUser·p0.9999: 16.542 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233569
  mean =      4.106 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 223742 
    [ 5.000,  7.500) = 7427 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     21.550 ms/op
     p(99.9990) =     23.604 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.386 ± 2.230  ops/ms
ClientPb.existUser                       thrpt       3   9.830 ± 2.299  ops/ms
ClientPb.getUser                         thrpt       3   9.325 ± 3.281  ops/ms
ClientPb.listUser                        thrpt       3   7.905 ± 2.498  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 1.369   ms/op
ClientPb.existUser                        avgt       3   3.312 ± 1.222   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.549   ms/op
ClientPb.listUser                         avgt       3   4.074 ± 0.879   ms/op
ClientPb.createUser                     sample  274531   3.497 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.780           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.756           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.284           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  290003   3.309 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.013           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.402           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.918           ms/op
ClientPb.getUser                        sample  278821   3.441 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.028           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.855           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.412           ms/op
ClientPb.listUser                       sample  233569   4.106 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.124           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.921           ms/op
