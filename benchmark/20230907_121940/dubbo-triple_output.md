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
# Warmup Iteration   1: 2.545 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 9.513 ops/ms
Iteration   1: 10.288 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.340 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (10.288, 10.340, 10.379), stdev = 0.047
  CI (99.9%): [9.480, 11.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 9.591 ops/ms
Iteration   1: 9.576 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 8.098 ops/ms [Average]
  (min, avg, max) = (9.576, 10.060, 10.448), stdev = 0.444
  CI (99.9%): [1.963, 18.158] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.086 ops/ms
# Warmup Iteration   2: 9.072 ops/ms
# Warmup Iteration   3: 9.156 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.709 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.634 ±(99.9%) 5.611 ops/ms [Average]
  (min, avg, max) = (9.296, 9.634, 9.897), stdev = 0.308
  CI (99.9%): [4.023, 15.245] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 6.944 ops/ms
# Warmup Iteration   3: 7.593 ops/ms
Iteration   1: 8.001 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 7.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 3.604 ops/ms [Average]
  (min, avg, max) = (7.620, 7.780, 8.001), stdev = 0.198
  CI (99.9%): [4.176, 11.384] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.505 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.006 ms/op
Iteration   1: 3.568 ±(99.9%) 0.007 ms/op
Iteration   2: 3.472 ±(99.9%) 0.005 ms/op
Iteration   3: 3.437 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.493 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.437, 3.493, 3.568), stdev = 0.068
  CI (99.9%): [2.256, 4.729] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.062 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.003 ms/op
Iteration   1: 3.309 ±(99.9%) 0.007 ms/op
Iteration   2: 3.304 ±(99.9%) 0.004 ms/op
Iteration   3: 3.117 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.243 ±(99.9%) 1.996 ms/op [Average]
  (min, avg, max) = (3.117, 3.243, 3.309), stdev = 0.109
  CI (99.9%): [1.247, 5.239] (assumes normal distribution)


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
# Warmup Iteration   1: 8.868 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.003 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
Iteration   3: 3.374 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.297 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.237, 3.297, 3.374), stdev = 0.070
  CI (99.9%): [2.023, 4.572] (assumes normal distribution)


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
# Warmup Iteration   1: 10.161 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.005 ms/op
Iteration   1: 4.017 ±(99.9%) 0.006 ms/op
Iteration   2: 3.903 ±(99.9%) 0.015 ms/op
Iteration   3: 4.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.984 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.903, 3.984, 4.032), stdev = 0.070
  CI (99.9%): [2.701, 5.267] (assumes normal distribution)


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
# Warmup Iteration   1: 9.145 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.011 ms/op
Iteration   1: 3.445 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  20.426 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 3.575 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  22.610 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.412 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  20.427 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276087
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11556 
    [ 2.500,  5.000) = 256496 
    [ 5.000,  7.500) = 6158 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     20.674 ms/op
     p(99.9900) =     26.679 ms/op
     p(99.9990) =     28.580 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 8.984 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  10.594 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   6.022 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 37.028 ms/op
                 existUser·p1.00:   37.552 ms/op

Iteration   3: 3.504 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  22.183 ms/op
                 existUser·p0.9999: 53.400 ms/op
                 existUser·p1.00:   53.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294135
  mean =      3.268 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 287338 
    [ 5.000, 10.000) = 6460 
    [10.000, 15.000) = 81 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 154 
    [25.000, 30.000) = 35 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 32 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     52.494 ms/op
     p(99.9990) =     53.547 ms/op
     p(99.9999) =     53.608 ms/op
    p(100.0000) =     53.608 ms/op


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
# Warmup Iteration   1: 8.383 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
Iteration   1: 3.424 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  20.920 ms/op
                 getUser·p0.9999: 35.214 ms/op
                 getUser·p1.00:   39.453 ms/op

Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  14.741 ms/op
                 getUser·p0.9999: 28.770 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.370 ms/op
                 getUser·p0.999:  16.695 ms/op
                 getUser·p0.9999: 26.609 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279902
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6822 
    [ 2.500,  5.000) = 263297 
    [ 5.000,  7.500) = 8020 
    [ 7.500, 10.000) = 1275 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     38.052 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 9.347 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.013 ms/op
Iteration   1: 3.889 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  20.173 ms/op
                 listUser·p0.9999: 23.192 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.153 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.651 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  14.157 ms/op
                 listUser·p0.9999: 15.274 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250009
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 240695 
    [ 5.000,  7.500) = 6611 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.340 ± 0.859  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 8.098  ops/ms
ClientPb.getUser                         thrpt       3   9.634 ± 5.611  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 3.604  ops/ms
ClientPb.createUser                       avgt       3   3.493 ± 1.236   ms/op
ClientPb.existUser                        avgt       3   3.243 ± 1.996   ms/op
ClientPb.getUser                          avgt       3   3.297 ± 1.274   ms/op
ClientPb.listUser                         avgt       3   3.984 ± 1.283   ms/op
ClientPb.createUser                     sample  276087   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.674           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.679           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.738           ms/op
ClientPb.existUser                      sample  294135   3.268 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.584           ms/op
ClientPb.existUser:existUser·p0.9999    sample          52.494           ms/op
ClientPb.existUser:existUser·p1.00      sample          53.608           ms/op
ClientPb.getUser                        sample  279902   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.013           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  250009   3.840 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
