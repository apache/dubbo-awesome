# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 6.513 ops/ms
# Warmup Iteration   3: 9.055 ops/ms
Iteration   1: 9.305 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.627 ±(99.9%) 5.222 ops/ms [Average]
  (min, avg, max) = (9.305, 9.627, 9.851), stdev = 0.286
  CI (99.9%): [4.406, 14.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.265 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 9.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.016 ±(99.9%) 4.170 ops/ms [Average]
  (min, avg, max) = (9.815, 10.016, 10.265), stdev = 0.229
  CI (99.9%): [5.846, 14.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.394 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 9.266 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.796 ±(99.9%) 5.329 ops/ms [Average]
  (min, avg, max) = (9.473, 9.796, 10.042), stdev = 0.292
  CI (99.9%): [4.466, 15.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.181 ops/ms
# Warmup Iteration   2: 7.279 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.556 ops/ms
Iteration   3: 8.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.409 ±(99.9%) 2.320 ops/ms [Average]
  (min, avg, max) = (8.334, 8.409, 8.556), stdev = 0.127
  CI (99.9%): [6.089, 10.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.630 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.010 ms/op
Iteration   1: 3.220 ±(99.9%) 0.002 ms/op
Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
Iteration   3: 3.179 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.196 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.179, 3.196, 3.220), stdev = 0.021
  CI (99.9%): [2.807, 3.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.992 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
Iteration   3: 3.106 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.086 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.044, 3.086, 3.108), stdev = 0.036
  CI (99.9%): [2.425, 3.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.660 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.003 ms/op
Iteration   1: 3.382 ±(99.9%) 0.003 ms/op
Iteration   2: 3.183 ±(99.9%) 0.003 ms/op
Iteration   3: 3.251 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.272 ±(99.9%) 1.836 ms/op [Average]
  (min, avg, max) = (3.183, 3.272, 3.382), stdev = 0.101
  CI (99.9%): [1.436, 5.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.625 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.007 ms/op
Iteration   1: 3.744 ±(99.9%) 0.008 ms/op
Iteration   2: 3.744 ±(99.9%) 0.007 ms/op
Iteration   3: 3.724 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.724, 3.738, 3.744), stdev = 0.012
  CI (99.9%): [3.527, 3.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.404 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  15.514 ms/op
                 createUser·p0.9999: 23.233 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  16.669 ms/op
                 createUser·p0.9999: 23.246 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297263
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17102 
    [ 2.500,  5.000) = 275108 
    [ 5.000,  7.500) = 4216 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.932 ms/op
     p(99.9900) =     23.078 ms/op
     p(99.9990) =     23.496 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.210 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.464 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.063 ms/op
                 existUser·p0.9999: 20.383 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  13.892 ms/op
                 existUser·p0.9999: 28.410 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  11.452 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296883
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26660 
    [ 2.500,  5.000) = 264411 
    [ 5.000,  7.500) = 5157 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     12.802 ms/op
     p(99.9900) =     27.402 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.579 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 22.049 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  10.434 ms/op
                 getUser·p0.9999: 22.219 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.941 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293072
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14071 
    [ 2.500,  5.000) = 271840 
    [ 5.000,  7.500) = 6121 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     11.648 ms/op
     p(99.9900) =     22.600 ms/op
     p(99.9990) =     24.906 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.924 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.442 ms/op
                 listUser·p0.9999: 26.838 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.929 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 14.973 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247113
  mean =      3.880 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 237448 
    [ 5.000,  7.500) = 7605 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     24.946 ms/op
     p(99.9990) =     27.300 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.627 ± 5.222  ops/ms
ClientPb.existUser                       thrpt       3  10.016 ± 4.170  ops/ms
ClientPb.getUser                         thrpt       3   9.796 ± 5.329  ops/ms
ClientPb.listUser                        thrpt       3   8.409 ± 2.320  ops/ms
ClientPb.createUser                       avgt       3   3.196 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   3.086 ± 0.661   ms/op
ClientPb.getUser                          avgt       3   3.272 ± 1.836   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 0.211   ms/op
ClientPb.createUser                     sample  297263   3.229 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.078           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.691           ms/op
ClientPb.existUser                      sample  296883   3.234 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.802           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.738           ms/op
ClientPb.getUser                        sample  293072   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.648           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.600           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.969           ms/op
ClientPb.listUser                       sample  247113   3.880 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.249           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.946           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
