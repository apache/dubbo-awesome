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
# Warmup Iteration   1: 2.059 ops/ms
# Warmup Iteration   2: 5.435 ops/ms
# Warmup Iteration   3: 8.230 ops/ms
Iteration   1: 8.809 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.073 ±(99.9%) 4.325 ops/ms [Average]
  (min, avg, max) = (8.809, 9.073, 9.268), stdev = 0.237
  CI (99.9%): [4.748, 13.398] (assumes normal distribution)


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
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 9.175 ops/ms
Iteration   1: 9.541 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.606 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (9.541, 9.606, 9.698), stdev = 0.082
  CI (99.9%): [8.105, 11.107] (assumes normal distribution)


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
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.506 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 9.137 ops/ms
Iteration   2: 9.399 ops/ms
Iteration   3: 9.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.218 ±(99.9%) 2.868 ops/ms [Average]
  (min, avg, max) = (9.118, 9.218, 9.399), stdev = 0.157
  CI (99.9%): [6.350, 12.086] (assumes normal distribution)


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
# Warmup Iteration   1: 2.712 ops/ms
# Warmup Iteration   2: 6.875 ops/ms
# Warmup Iteration   3: 7.553 ops/ms
Iteration   1: 7.648 ops/ms
Iteration   2: 7.639 ops/ms
Iteration   3: 7.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.671 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (7.639, 7.671, 7.727), stdev = 0.049
  CI (99.9%): [6.781, 8.562] (assumes normal distribution)


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
# Warmup Iteration   1: 11.520 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.005 ms/op
Iteration   1: 3.482 ±(99.9%) 0.004 ms/op
Iteration   2: 3.548 ±(99.9%) 0.006 ms/op
Iteration   3: 3.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.519 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.482, 3.519, 3.548), stdev = 0.034
  CI (99.9%): [2.902, 4.136] (assumes normal distribution)


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
# Warmup Iteration   1: 8.672 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.003 ms/op
Iteration   1: 3.357 ±(99.9%) 0.005 ms/op
Iteration   2: 3.279 ±(99.9%) 0.012 ms/op
Iteration   3: 3.455 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.363 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.279, 3.363, 3.455), stdev = 0.088
  CI (99.9%): [1.760, 4.967] (assumes normal distribution)


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
# Warmup Iteration   1: 9.275 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.009 ms/op
Iteration   1: 3.556 ±(99.9%) 0.006 ms/op
Iteration   2: 3.423 ±(99.9%) 0.008 ms/op
Iteration   3: 3.472 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (3.423, 3.483, 3.556), stdev = 0.067
  CI (99.9%): [2.255, 4.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.337 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.009 ms/op
Iteration   1: 4.119 ±(99.9%) 0.010 ms/op
Iteration   2: 4.151 ±(99.9%) 0.010 ms/op
Iteration   3: 4.155 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.142 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (4.119, 4.142, 4.155), stdev = 0.020
  CI (99.9%): [3.780, 4.504] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.542 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.011 ms/op
Iteration   1: 3.557 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  21.392 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 3.678 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  23.387 ms/op
                 createUser·p0.9999: 25.733 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.643 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 28.712 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264683
  mean =      3.625 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5263 
    [ 2.500,  5.000) = 247481 
    [ 5.000,  7.500) = 9973 
    [ 7.500, 10.000) = 1295 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.686 ms/op
     p(99.9000) =     20.390 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     29.341 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 10.750 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.012 ms/op
Iteration   1: 3.520 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.833 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   5.519 ms/op
                 existUser·p0.99:   7.302 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 31.553 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  22.675 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 28.009 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275687
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11509 
    [ 2.500,  5.000) = 254958 
    [ 5.000,  7.500) = 7431 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     11.959 ms/op
     p(99.9900) =     30.863 ms/op
     p(99.9990) =     31.918 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 9.981 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.012 ms/op
Iteration   1: 3.666 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   7.044 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 24.094 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.488 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  12.380 ms/op
                 getUser·p0.9999: 25.313 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 3.606 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.931 ms/op
                 getUser·p0.999:  23.046 ms/op
                 getUser·p0.9999: 27.494 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267583
  mean =      3.585 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4970 
    [ 2.500,  5.000) = 253318 
    [ 5.000,  7.500) = 7428 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     25.895 ms/op
     p(99.9990) =     28.463 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 12.036 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
Iteration   1: 4.161 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  22.552 ms/op
                 listUser·p0.9999: 26.593 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 4.354 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  16.002 ms/op
                 listUser·p0.9999: 19.879 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 4.307 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   6.010 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  15.768 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 224656
  mean =      4.272 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 206335 
    [ 5.000,  7.500) = 13897 
    [ 7.500, 10.000) = 3329 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.621 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     17.116 ms/op
     p(99.9900) =     24.906 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.073 ± 4.325  ops/ms
ClientPb.existUser                       thrpt       3   9.606 ± 1.501  ops/ms
ClientPb.getUser                         thrpt       3   9.218 ± 2.868  ops/ms
ClientPb.listUser                        thrpt       3   7.671 ± 0.890  ops/ms
ClientPb.createUser                       avgt       3   3.519 ± 0.617   ms/op
ClientPb.existUser                        avgt       3   3.363 ± 1.603   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 1.228   ms/op
ClientPb.listUser                         avgt       3   4.142 ± 0.362   ms/op
ClientPb.createUser                     sample  264683   3.625 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.686           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.390           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  275687   3.479 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.863           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  267583   3.585 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.808           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.895           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  224656   4.272 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.937           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.621           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.116           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.906           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
