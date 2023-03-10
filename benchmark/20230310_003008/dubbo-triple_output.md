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
# Warmup Iteration   1: 2.157 ops/ms
# Warmup Iteration   2: 5.484 ops/ms
# Warmup Iteration   3: 8.719 ops/ms
Iteration   1: 9.306 ops/ms
Iteration   2: 9.019 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.257 ±(99.9%) 3.958 ops/ms [Average]
  (min, avg, max) = (9.019, 9.257, 9.445), stdev = 0.217
  CI (99.9%): [5.298, 13.215] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 10.043 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.891 ±(99.9%) 4.402 ops/ms [Average]
  (min, avg, max) = (9.618, 9.891, 10.078), stdev = 0.241
  CI (99.9%): [5.488, 14.293] (assumes normal distribution)


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
# Warmup Iteration   1: 3.282 ops/ms
# Warmup Iteration   2: 8.567 ops/ms
# Warmup Iteration   3: 8.934 ops/ms
Iteration   1: 9.523 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.554 ±(99.9%) 3.127 ops/ms [Average]
  (min, avg, max) = (9.400, 9.554, 9.739), stdev = 0.171
  CI (99.9%): [6.427, 12.681] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.210 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (8.091, 8.210, 8.339), stdev = 0.124
  CI (99.9%): [5.943, 10.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.395 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.007 ms/op
Iteration   2: 3.403 ±(99.9%) 0.007 ms/op
Iteration   3: 3.312 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.335 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.291, 3.335, 3.403), stdev = 0.060
  CI (99.9%): [2.247, 4.423] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.051 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.005 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
Iteration   2: 3.150 ±(99.9%) 0.012 ms/op
Iteration   3: 3.397 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.264 ±(99.9%) 2.266 ms/op [Average]
  (min, avg, max) = (3.150, 3.264, 3.397), stdev = 0.124
  CI (99.9%): [0.998, 5.530] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.541 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.007 ms/op
Iteration   1: 3.435 ±(99.9%) 0.007 ms/op
Iteration   2: 3.281 ±(99.9%) 0.010 ms/op
Iteration   3: 3.316 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.344 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.281, 3.344, 3.435), stdev = 0.081
  CI (99.9%): [1.873, 4.816] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.222 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.008 ms/op
Iteration   1: 3.980 ±(99.9%) 0.005 ms/op
Iteration   2: 3.982 ±(99.9%) 0.009 ms/op
Iteration   3: 3.960 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.974 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.960, 3.974, 3.982), stdev = 0.012
  CI (99.9%): [3.758, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 9.367 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  19.934 ms/op
                 createUser·p0.9999: 22.331 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  10.638 ms/op
                 createUser·p0.9999: 25.804 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  17.102 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290367
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12082 
    [ 2.500,  5.000) = 274125 
    [ 5.000,  7.500) = 3323 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.024 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.983 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.986 ms/op
                 existUser·p0.9999: 23.169 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.253 ms/op
                 existUser·p0.999:  15.038 ms/op
                 existUser·p0.9999: 23.211 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  13.868 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294559
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18210 
    [ 2.500,  5.000) = 271799 
    [ 5.000,  7.500) = 3765 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.435 ms/op
     p(99.9000) =     13.737 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     26.347 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 8.182 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.011 ms/op
Iteration   1: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  19.206 ms/op
                 getUser·p0.9999: 24.201 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  15.155 ms/op
                 getUser·p0.9999: 26.973 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  18.235 ms/op
                 getUser·p0.9999: 25.807 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289167
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7262 
    [ 2.500,  5.000) = 275694 
    [ 5.000,  7.500) = 5073 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     15.182 ms/op
     p(99.9900) =     26.152 ms/op
     p(99.9990) =     27.336 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 9.970 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  17.240 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 15.630 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.941 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 20.116 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243122
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 234638 
    [ 5.000,  7.500) = 6409 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     28.334 ms/op
     p(99.9990) =     31.134 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.257 ± 3.958  ops/ms
ClientPb.existUser                       thrpt       3   9.891 ± 4.402  ops/ms
ClientPb.getUser                         thrpt       3   9.554 ± 3.127  ops/ms
ClientPb.listUser                        thrpt       3   8.210 ± 2.267  ops/ms
ClientPb.createUser                       avgt       3   3.335 ± 1.088   ms/op
ClientPb.existUser                        avgt       3   3.264 ± 2.266   ms/op
ClientPb.getUser                          avgt       3   3.344 ± 1.471   ms/op
ClientPb.listUser                         avgt       3   3.974 ± 0.216   ms/op
ClientPb.createUser                     sample  290367   3.306 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.262           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.100           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  294559   3.258 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.435           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.921           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  289167   3.317 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.182           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.152           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.787           ms/op
ClientPb.listUser                       sample  243122   3.950 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.334           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
