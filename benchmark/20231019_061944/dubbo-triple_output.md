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
# Warmup Iteration   2: 6.538 ops/ms
# Warmup Iteration   3: 8.843 ops/ms
Iteration   1: 9.831 ops/ms
Iteration   2: 9.895 ops/ms
Iteration   3: 9.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.845 ±(99.9%) 0.812 ops/ms [Average]
  (min, avg, max) = (9.809, 9.845, 9.895), stdev = 0.045
  CI (99.9%): [9.033, 10.657] (assumes normal distribution)


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
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 9.450 ops/ms
# Warmup Iteration   3: 10.233 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 10.281 ops/ms
Iteration   3: 10.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.175 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (10.094, 10.175, 10.281), stdev = 0.096
  CI (99.9%): [8.427, 11.923] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ops/ms
# Warmup Iteration   2: 9.204 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.841 ±(99.9%) 0.753 ops/ms [Average]
  (min, avg, max) = (9.794, 9.841, 9.872), stdev = 0.041
  CI (99.9%): [9.088, 10.594] (assumes normal distribution)


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
# Warmup Iteration   1: 2.885 ops/ms
# Warmup Iteration   2: 7.649 ops/ms
# Warmup Iteration   3: 8.131 ops/ms
Iteration   1: 8.255 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.369 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (8.255, 8.369, 8.490), stdev = 0.117
  CI (99.9%): [6.228, 10.511] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.002 ms/op
Iteration   1: 3.277 ±(99.9%) 0.006 ms/op
Iteration   2: 3.338 ±(99.9%) 0.003 ms/op
Iteration   3: 3.288 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.301 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.277, 3.301, 3.338), stdev = 0.033
  CI (99.9%): [2.707, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 7.238 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.004 ms/op
Iteration   1: 3.205 ±(99.9%) 0.004 ms/op
Iteration   2: 3.087 ±(99.9%) 0.005 ms/op
Iteration   3: 3.156 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.150 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.087, 3.150, 3.205), stdev = 0.059
  CI (99.9%): [2.069, 4.230] (assumes normal distribution)


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
# Warmup Iteration   1: 9.071 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.003 ms/op
Iteration   1: 3.278 ±(99.9%) 0.003 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.178 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.228 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.178, 3.228, 3.278), stdev = 0.050
  CI (99.9%): [2.312, 4.145] (assumes normal distribution)


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
# Warmup Iteration   1: 9.210 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.005 ms/op
Iteration   1: 3.875 ±(99.9%) 0.003 ms/op
Iteration   2: 3.809 ±(99.9%) 0.004 ms/op
Iteration   3: 3.730 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.805 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (3.730, 3.805, 3.875), stdev = 0.073
  CI (99.9%): [2.480, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 8.633 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  17.640 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.029 ms/op
                 createUser·p0.9999: 23.051 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.848 ms/op
                 createUser·p0.999:  16.299 ms/op
                 createUser·p0.9999: 22.778 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287042
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15487 
    [ 2.500,  5.000) = 266832 
    [ 5.000,  7.500) = 3708 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.333 ms/op
     p(99.9900) =     23.154 ms/op
     p(99.9990) =     24.216 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.730 ms/op
                 existUser·p0.9999: 20.872 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.177 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  12.478 ms/op
                 existUser·p0.9999: 23.886 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  14.602 ms/op
                 existUser·p0.9999: 23.330 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300927
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19211 
    [ 2.500,  5.000) = 275949 
    [ 5.000,  7.500) = 4839 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.836 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.013 ms/op
Iteration   1: 3.302 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  16.651 ms/op
                 getUser·p0.9999: 22.376 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 22.329 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.249 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.961 ms/op
                 getUser·p0.9999: 23.215 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293129
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8741 
    [ 2.500,  5.000) = 278010 
    [ 5.000,  7.500) = 5622 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.286 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 10.023 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  18.908 ms/op
                 listUser·p0.9999: 22.220 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.832 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.169 ms/op
                 listUser·p0.9999: 14.270 ms/op
                 listUser·p1.00:   14.418 ms/op

Iteration   3: 3.833 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.043 ms/op
                 listUser·p0.999:  13.381 ms/op
                 listUser·p0.9999: 14.963 ms/op
                 listUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249068
  mean =      3.852 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 242471 
    [ 5.000,  7.500) = 4638 
    [ 7.500, 10.000) = 1114 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.958 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     21.237 ms/op
     p(99.9990) =     22.856 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.845 ± 0.812  ops/ms
ClientPb.existUser                       thrpt       3  10.175 ± 1.748  ops/ms
ClientPb.getUser                         thrpt       3   9.841 ± 0.753  ops/ms
ClientPb.listUser                        thrpt       3   8.369 ± 2.142  ops/ms
ClientPb.createUser                       avgt       3   3.301 ± 0.594   ms/op
ClientPb.existUser                        avgt       3   3.150 ± 1.080   ms/op
ClientPb.getUser                          avgt       3   3.228 ± 0.917   ms/op
ClientPb.listUser                         avgt       3   3.805 ± 1.325   ms/op
ClientPb.createUser                     sample  287042   3.342 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.333           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.154           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.494           ms/op
ClientPb.existUser                      sample  300927   3.187 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.233           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  293129   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.381           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.445           ms/op
ClientPb.listUser                       sample  249068   3.852 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.374           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.958           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.237           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
