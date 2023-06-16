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
# Warmup Iteration   2: 6.937 ops/ms
# Warmup Iteration   3: 9.639 ops/ms
Iteration   1: 9.758 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 10.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.933 ±(99.9%) 3.749 ops/ms [Average]
  (min, avg, max) = (9.758, 9.933, 10.159), stdev = 0.205
  CI (99.9%): [6.184, 13.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 10.148 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 10.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.262 ±(99.9%) 2.540 ops/ms [Average]
  (min, avg, max) = (10.109, 10.262, 10.380), stdev = 0.139
  CI (99.9%): [7.722, 12.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ops/ms
# Warmup Iteration   2: 9.367 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 10.046 ops/ms
Iteration   2: 10.426 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.963 ±(99.9%) 9.297 ops/ms [Average]
  (min, avg, max) = (9.417, 9.963, 10.426), stdev = 0.510
  CI (99.9%): [0.666, 19.260] (assumes normal distribution)


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
# Warmup Iteration   1: 3.146 ops/ms
# Warmup Iteration   2: 7.557 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.635 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.404 ±(99.9%) 3.779 ops/ms [Average]
  (min, avg, max) = (8.236, 8.404, 8.635), stdev = 0.207
  CI (99.9%): [4.625, 12.182] (assumes normal distribution)


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
# Warmup Iteration   1: 8.183 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.006 ms/op
Iteration   1: 3.327 ±(99.9%) 0.005 ms/op
Iteration   2: 3.174 ±(99.9%) 0.003 ms/op
Iteration   3: 3.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.224 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (3.171, 3.224, 3.327), stdev = 0.089
  CI (99.9%): [1.601, 4.847] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
Iteration   3: 3.154 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.053, 3.102, 3.154), stdev = 0.051
  CI (99.9%): [2.180, 4.025] (assumes normal distribution)


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
# Warmup Iteration   1: 7.981 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.004 ms/op
Iteration   1: 3.202 ±(99.9%) 0.008 ms/op
Iteration   2: 3.323 ±(99.9%) 0.007 ms/op
Iteration   3: 3.235 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.253 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.202, 3.253, 3.323), stdev = 0.063
  CI (99.9%): [2.105, 4.402] (assumes normal distribution)


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
# Warmup Iteration   1: 8.370 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.005 ms/op
Iteration   1: 3.693 ±(99.9%) 0.006 ms/op
Iteration   2: 3.762 ±(99.9%) 0.007 ms/op
Iteration   3: 3.773 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.743 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.693, 3.743, 3.773), stdev = 0.043
  CI (99.9%): [2.951, 4.535] (assumes normal distribution)


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
# Warmup Iteration   1: 7.380 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.285 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  13.160 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  13.467 ms/op
                 createUser·p0.9999: 22.223 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  15.319 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297395
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19974 
    [ 2.500,  5.000) = 271877 
    [ 5.000,  7.500) = 4554 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.170 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 6.993 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 18.828 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.459 ms/op
                 existUser·p0.9999: 20.472 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309712
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22247 
    [ 2.500,  5.000) = 283274 
    [ 5.000,  7.500) = 3371 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     20.890 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 7.773 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
Iteration   1: 3.301 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  15.727 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  11.941 ms/op
                 getUser·p0.9999: 22.273 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  11.661 ms/op
                 getUser·p0.9999: 21.272 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293377
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9359 
    [ 2.500,  5.000) = 275532 
    [ 5.000,  7.500) = 7332 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     14.688 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.579 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 9.936 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
Iteration   1: 3.841 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  16.807 ms/op
                 listUser·p0.9999: 20.622 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.783 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 17.680 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252331
  mean =      3.802 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 244357 
    [ 5.000,  7.500) = 5694 
    [ 7.500, 10.000) = 1437 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     19.424 ms/op
     p(99.9990) =     20.839 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.933 ± 3.749  ops/ms
ClientPb.existUser                       thrpt       3  10.262 ± 2.540  ops/ms
ClientPb.getUser                         thrpt       3   9.963 ± 9.297  ops/ms
ClientPb.listUser                        thrpt       3   8.404 ± 3.779  ops/ms
ClientPb.createUser                       avgt       3   3.224 ± 1.623   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.923   ms/op
ClientPb.getUser                          avgt       3   3.253 ± 1.148   ms/op
ClientPb.listUser                         avgt       3   3.743 ± 0.792   ms/op
ClientPb.createUser                     sample  297395   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.319           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  309712   3.099 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.923           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.955           ms/op
ClientPb.getUser                        sample  293377   3.269 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.909           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.688           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.987           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.069           ms/op
ClientPb.listUser                       sample  252331   3.802 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.501           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.939           ms/op
