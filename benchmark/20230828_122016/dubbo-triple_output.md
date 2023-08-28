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
# Warmup Iteration   1: 2.348 ops/ms
# Warmup Iteration   2: 5.841 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 9.420 ops/ms
Iteration   2: 9.496 ops/ms
Iteration   3: 9.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.494 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (9.420, 9.494, 9.565), stdev = 0.073
  CI (99.9%): [8.169, 10.818] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 9.114 ops/ms
# Warmup Iteration   3: 9.691 ops/ms
Iteration   1: 10.119 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.147 ±(99.9%) 3.729 ops/ms [Average]
  (min, avg, max) = (9.958, 10.147, 10.364), stdev = 0.204
  CI (99.9%): [6.418, 13.876] (assumes normal distribution)


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
# Warmup Iteration   1: 3.328 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 9.415 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.837 ±(99.9%) 3.458 ops/ms [Average]
  (min, avg, max) = (9.647, 9.837, 10.026), stdev = 0.190
  CI (99.9%): [6.379, 13.295] (assumes normal distribution)


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
# Warmup Iteration   1: 2.970 ops/ms
# Warmup Iteration   2: 7.115 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.403 ops/ms
Iteration   3: 8.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.309 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (8.233, 8.309, 8.403), stdev = 0.086
  CI (99.9%): [6.735, 9.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.007 ms/op
Iteration   1: 3.331 ±(99.9%) 0.002 ms/op
Iteration   2: 3.320 ±(99.9%) 0.007 ms/op
Iteration   3: 3.156 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (3.156, 3.269, 3.331), stdev = 0.098
  CI (99.9%): [1.484, 5.054] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.330 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.004 ms/op
Iteration   1: 3.288 ±(99.9%) 0.003 ms/op
Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
Iteration   3: 3.162 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.223 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.162, 3.223, 3.288), stdev = 0.063
  CI (99.9%): [2.071, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 8.737 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.004 ms/op
Iteration   1: 3.326 ±(99.9%) 0.006 ms/op
Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
Iteration   3: 3.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.261 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (3.200, 3.261, 3.326), stdev = 0.063
  CI (99.9%): [2.107, 4.415] (assumes normal distribution)


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
# Warmup Iteration   1: 9.132 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.979 ±(99.9%) 0.005 ms/op
Iteration   2: 3.886 ±(99.9%) 0.008 ms/op
Iteration   3: 3.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.886, 3.939, 3.979), stdev = 0.048
  CI (99.9%): [3.067, 4.812] (assumes normal distribution)


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
# Warmup Iteration   1: 8.442 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  12.134 ms/op
                 createUser·p0.9999: 21.142 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.220 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  20.337 ms/op
                 createUser·p0.9999: 29.013 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  18.390 ms/op
                 createUser·p0.9999: 37.239 ms/op
                 createUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295028
  mean =      3.253 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8798 
    [ 2.500,  5.000) = 279609 
    [ 5.000,  7.500) = 5016 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     18.873 ms/op
     p(99.9900) =     34.800 ms/op
     p(99.9990) =     37.955 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 7.844 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
Iteration   1: 3.293 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 21.557 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  17.099 ms/op
                 existUser·p0.9999: 23.005 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.541 ms/op
                 existUser·p0.999:  13.964 ms/op
                 existUser·p0.9999: 29.236 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291490
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25621 
    [ 2.500,  5.000) = 258300 
    [ 5.000,  7.500) = 6119 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     12.631 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.011 ms/op
Iteration   1: 3.334 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  16.926 ms/op
                 getUser·p0.9999: 20.231 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.297 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 28.298 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.115 ms/op
                 getUser·p0.999:  13.472 ms/op
                 getUser·p0.9999: 25.080 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289007
  mean =      3.320 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17858 
    [ 2.500,  5.000) = 261064 
    [ 5.000,  7.500) = 8387 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     28.657 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.250 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.013 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  16.806 ms/op
                 listUser·p0.9999: 18.926 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   8.058 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 18.924 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251739
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 242128 
    [ 5.000,  7.500) = 6896 
    [ 7.500, 10.000) = 1752 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.673 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     18.934 ms/op
     p(99.9990) =     21.154 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.494 ± 1.325  ops/ms
ClientPb.existUser                       thrpt       3  10.147 ± 3.729  ops/ms
ClientPb.getUser                         thrpt       3   9.837 ± 3.458  ops/ms
ClientPb.listUser                        thrpt       3   8.309 ± 1.574  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 1.785   ms/op
ClientPb.existUser                        avgt       3   3.223 ± 1.152   ms/op
ClientPb.getUser                          avgt       3   3.261 ± 1.154   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 0.872   ms/op
ClientPb.createUser                     sample  295028   3.253 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.800           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.273           ms/op
ClientPb.existUser                      sample  291490   3.291 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  289007   3.320 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.492           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.869           ms/op
ClientPb.listUser                       sample  251739   3.817 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.673           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.934           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.053           ms/op
