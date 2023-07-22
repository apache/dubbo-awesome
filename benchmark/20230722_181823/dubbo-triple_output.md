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
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 5.493 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 9.369 ops/ms
Iteration   3: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.166 ±(99.9%) 5.281 ops/ms [Average]
  (min, avg, max) = (8.834, 9.166, 9.369), stdev = 0.289
  CI (99.9%): [3.884, 14.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 8.941 ops/ms
# Warmup Iteration   3: 9.416 ops/ms
Iteration   1: 10.031 ops/ms
Iteration   2: 10.138 ops/ms
Iteration   3: 9.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.966 ±(99.9%) 3.851 ops/ms [Average]
  (min, avg, max) = (9.731, 9.966, 10.138), stdev = 0.211
  CI (99.9%): [6.115, 13.817] (assumes normal distribution)


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
# Warmup Iteration   1: 2.936 ops/ms
# Warmup Iteration   2: 8.459 ops/ms
# Warmup Iteration   3: 8.950 ops/ms
Iteration   1: 9.246 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.439 ±(99.9%) 4.762 ops/ms [Average]
  (min, avg, max) = (9.246, 9.439, 9.736), stdev = 0.261
  CI (99.9%): [4.677, 14.201] (assumes normal distribution)


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
# Warmup Iteration   1: 2.904 ops/ms
# Warmup Iteration   2: 7.136 ops/ms
# Warmup Iteration   3: 7.950 ops/ms
Iteration   1: 7.853 ops/ms
Iteration   2: 8.092 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.011 ±(99.9%) 2.500 ops/ms [Average]
  (min, avg, max) = (7.853, 8.011, 8.092), stdev = 0.137
  CI (99.9%): [5.511, 10.511] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.567 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.006 ms/op
Iteration   1: 3.540 ±(99.9%) 0.008 ms/op
Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
Iteration   3: 3.461 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.461 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.380, 3.461, 3.540), stdev = 0.080
  CI (99.9%): [2.001, 4.921] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.006 ms/op
Iteration   1: 3.257 ±(99.9%) 0.011 ms/op
Iteration   2: 3.263 ±(99.9%) 0.006 ms/op
Iteration   3: 3.377 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (3.257, 3.299, 3.377), stdev = 0.068
  CI (99.9%): [2.065, 4.532] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.972 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.004 ms/op
Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
Iteration   3: 3.340 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.500 ±(99.9%) 2.981 ms/op [Average]
  (min, avg, max) = (3.340, 3.500, 3.667), stdev = 0.163
  CI (99.9%): [0.519, 6.481] (assumes normal distribution)


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
# Warmup Iteration   1: 11.984 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.007 ms/op
Iteration   1: 4.096 ±(99.9%) 0.008 ms/op
Iteration   2: 4.085 ±(99.9%) 0.010 ms/op
Iteration   3: 4.042 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.074 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (4.042, 4.074, 4.096), stdev = 0.028
  CI (99.9%): [3.557, 4.592] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.274 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.015 ms/op
Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.004 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.499 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  22.162 ms/op
                 createUser·p0.9999: 32.454 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.010 ms/op
                 createUser·p0.999:  21.845 ms/op
                 createUser·p0.9999: 31.796 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277343
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4753 
    [ 2.500,  5.000) = 265191 
    [ 5.000,  7.500) = 6221 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     33.381 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 9.050 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.460 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  9.301 ms/op
                 existUser·p0.9999: 21.474 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.419 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  19.198 ms/op
                 existUser·p0.9999: 22.762 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.546 ms/op
                 existUser·p0.999:  18.571 ms/op
                 existUser·p0.9999: 26.092 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281708
  mean =      3.405 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16726 
    [ 2.500,  5.000) = 258829 
    [ 5.000,  7.500) = 4911 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     12.904 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     26.757 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 8.997 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.480 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  22.776 ms/op
                 getUser·p0.9999: 25.022 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 26.262 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277303
  mean =      3.461 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13385 
    [ 2.500,  5.000) = 256448 
    [ 5.000,  7.500) = 6471 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 10.436 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.629 ms/op
                 listUser·p0.999:  19.829 ms/op
                 listUser·p0.9999: 24.610 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.835 ms/op
                 listUser·p0.9999: 29.437 ms/op
                 listUser·p1.00:   30.638 ms/op

Iteration   3: 3.905 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240515
  mean =      3.991 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 232730 
    [ 5.000,  7.500) = 5624 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     28.470 ms/op
     p(99.9990) =     30.625 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.166 ± 5.281  ops/ms
ClientPb.existUser                       thrpt       3   9.966 ± 3.851  ops/ms
ClientPb.getUser                         thrpt       3   9.439 ± 4.762  ops/ms
ClientPb.listUser                        thrpt       3   8.011 ± 2.500  ops/ms
ClientPb.createUser                       avgt       3   3.461 ± 1.460   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 1.233   ms/op
ClientPb.getUser                          avgt       3   3.500 ± 2.981   ms/op
ClientPb.listUser                         avgt       3   4.074 ± 0.518   ms/op
ClientPb.createUser                     sample  277343   3.459 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.654           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  281708   3.405 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.667           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.904           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.870           ms/op
ClientPb.getUser                        sample  277303   3.461 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.133           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.230           ms/op
ClientPb.listUser                       sample  240515   3.991 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.470           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.638           ms/op
