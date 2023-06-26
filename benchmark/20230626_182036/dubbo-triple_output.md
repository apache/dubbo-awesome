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
# Warmup Iteration   1: 2.409 ops/ms
# Warmup Iteration   2: 5.504 ops/ms
# Warmup Iteration   3: 8.618 ops/ms
Iteration   1: 9.451 ops/ms
Iteration   2: 9.278 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.511 ±(99.9%) 4.906 ops/ms [Average]
  (min, avg, max) = (9.278, 9.511, 9.805), stdev = 0.269
  CI (99.9%): [4.606, 14.417] (assumes normal distribution)


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
# Warmup Iteration   1: 3.643 ops/ms
# Warmup Iteration   2: 9.417 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.247 ops/ms
Iteration   2: 10.378 ops/ms
Iteration   3: 9.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.190 ±(99.9%) 4.031 ops/ms [Average]
  (min, avg, max) = (9.946, 10.190, 10.378), stdev = 0.221
  CI (99.9%): [6.159, 14.222] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 9.125 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.703 ops/ms
Iteration   2: 9.772 ops/ms
Iteration   3: 9.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.693 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (9.605, 9.693, 9.772), stdev = 0.084
  CI (99.9%): [8.156, 11.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.369 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.465 ±(99.9%) 2.377 ops/ms [Average]
  (min, avg, max) = (8.369, 8.465, 8.613), stdev = 0.130
  CI (99.9%): [6.088, 10.841] (assumes normal distribution)


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
# Warmup Iteration   1: 8.877 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.005 ms/op
Iteration   1: 3.428 ±(99.9%) 0.006 ms/op
Iteration   2: 3.307 ±(99.9%) 0.007 ms/op
Iteration   3: 3.281 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.339 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (3.281, 3.339, 3.428), stdev = 0.079
  CI (99.9%): [1.907, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 7.558 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.004 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
Iteration   2: 3.293 ±(99.9%) 0.004 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.192 ±(99.9%) 2.082 ms/op [Average]
  (min, avg, max) = (3.068, 3.192, 3.293), stdev = 0.114
  CI (99.9%): [1.110, 5.273] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.005 ms/op
Iteration   1: 3.408 ±(99.9%) 0.008 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.312 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.288 ±(99.9%) 2.446 ms/op [Average]
  (min, avg, max) = (3.143, 3.288, 3.408), stdev = 0.134
  CI (99.9%): [0.842, 5.733] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.609 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.005 ms/op
Iteration   1: 3.813 ±(99.9%) 0.004 ms/op
Iteration   2: 3.794 ±(99.9%) 0.009 ms/op
Iteration   3: 3.709 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.709, 3.772, 3.813), stdev = 0.055
  CI (99.9%): [2.762, 4.782] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.224 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  10.946 ms/op
                 createUser·p0.9999: 28.377 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297384
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13071 
    [ 2.500,  5.000) = 278870 
    [ 5.000,  7.500) = 4657 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.928 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     29.235 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.552 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.694 ms/op
                 existUser·p0.9999: 20.286 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   3: 3.314 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.065 ms/op
                 existUser·p0.9999: 21.748 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295975
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27377 
    [ 2.500,  5.000) = 262955 
    [ 5.000,  7.500) = 5027 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     32.606 ms/op
     p(99.9990) =     34.084 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 8.336 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.011 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  17.772 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  12.327 ms/op
                 getUser·p0.9999: 23.235 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.378 ms/op
                 getUser·p0.9999: 22.122 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296874
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8031 
    [ 2.500,  5.000) = 283396 
    [ 5.000,  7.500) = 4782 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     15.553 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.675 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.357 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.803 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.665 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  11.616 ms/op
                 listUser·p0.9999: 21.603 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256155
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 250336 
    [ 5.000,  7.500) = 3937 
    [ 7.500, 10.000) = 1212 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.919 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     21.641 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.511 ± 4.906  ops/ms
ClientPb.existUser                       thrpt       3  10.190 ± 4.031  ops/ms
ClientPb.getUser                         thrpt       3   9.693 ± 1.537  ops/ms
ClientPb.listUser                        thrpt       3   8.465 ± 2.377  ops/ms
ClientPb.createUser                       avgt       3   3.339 ± 1.432   ms/op
ClientPb.existUser                        avgt       3   3.192 ± 2.082   ms/op
ClientPb.getUser                          avgt       3   3.288 ± 2.446   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 1.010   ms/op
ClientPb.createUser                     sample  297384   3.227 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.928           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.969           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819           ms/op
ClientPb.existUser                      sample  295975   3.242 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  296874   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.553           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.773           ms/op
ClientPb.listUser                       sample  256155   3.743 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.205           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.218           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
