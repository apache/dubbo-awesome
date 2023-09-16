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
# Warmup Iteration   1: 2.242 ops/ms
# Warmup Iteration   2: 5.842 ops/ms
# Warmup Iteration   3: 9.022 ops/ms
Iteration   1: 9.614 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.681 ±(99.9%) 3.302 ops/ms [Average]
  (min, avg, max) = (9.543, 9.681, 9.886), stdev = 0.181
  CI (99.9%): [6.379, 12.983] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ops/ms
# Warmup Iteration   2: 9.476 ops/ms
# Warmup Iteration   3: 10.045 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.357 ops/ms
Iteration   3: 10.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.219 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (10.098, 10.219, 10.357), stdev = 0.130
  CI (99.9%): [7.849, 12.590] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 9.821 ops/ms
Iteration   2: 10.117 ops/ms
Iteration   3: 9.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.884 ±(99.9%) 3.797 ops/ms [Average]
  (min, avg, max) = (9.715, 9.884, 10.117), stdev = 0.208
  CI (99.9%): [6.087, 13.682] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.254 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.270 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (8.254, 8.270, 8.298), stdev = 0.025
  CI (99.9%): [7.819, 8.720] (assumes normal distribution)


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
# Warmup Iteration   1: 9.478 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.003 ms/op
Iteration   1: 3.276 ±(99.9%) 0.005 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.247 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.242 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.204, 3.242, 3.276), stdev = 0.036
  CI (99.9%): [2.582, 3.902] (assumes normal distribution)


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
# Warmup Iteration   1: 7.430 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.005 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.235 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.156 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.093, 3.156, 3.235), stdev = 0.072
  CI (99.9%): [1.833, 4.479] (assumes normal distribution)


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
# Warmup Iteration   1: 7.424 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.003 ms/op
Iteration   1: 3.322 ±(99.9%) 0.002 ms/op
Iteration   2: 3.285 ±(99.9%) 0.005 ms/op
Iteration   3: 3.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.301 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.285, 3.301, 3.322), stdev = 0.019
  CI (99.9%): [2.957, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 8.431 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.005 ms/op
Iteration   1: 3.905 ±(99.9%) 0.005 ms/op
Iteration   2: 3.834 ±(99.9%) 0.003 ms/op
Iteration   3: 3.893 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.877 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.834, 3.877, 3.905), stdev = 0.038
  CI (99.9%): [3.190, 4.564] (assumes normal distribution)


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
# Warmup Iteration   1: 8.019 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
Iteration   1: 3.249 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  11.483 ms/op
                 createUser·p0.9999: 21.042 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.313 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 22.851 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.207 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 20.386 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291089
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14222 
    [ 2.500,  5.000) = 272499 
    [ 5.000,  7.500) = 3482 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     17.233 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.449 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.801 ms/op
                 existUser·p0.9999: 19.923 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.779 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  14.659 ms/op
                 existUser·p0.9999: 21.852 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303863
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17200 
    [ 2.500,  5.000) = 281201 
    [ 5.000,  7.500) = 4564 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.935 ms/op
     p(99.9900) =     22.302 ms/op
     p(99.9990) =     23.188 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 7.644 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  16.691 ms/op
                 getUser·p0.9999: 19.071 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  17.653 ms/op
                 getUser·p0.9999: 20.948 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 21.515 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289192
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10780 
    [ 2.500,  5.000) = 271476 
    [ 5.000,  7.500) = 6032 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     16.610 ms/op
     p(99.9900) =     21.040 ms/op
     p(99.9990) =     22.031 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 9.508 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.938 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.032 ms/op
                 listUser·p0.9999: 20.934 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 15.909 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   3: 3.938 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.054 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246483
  mean =      3.893 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 239409 
    [ 5.000,  7.500) = 5323 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.858 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     19.148 ms/op
     p(99.9990) =     21.341 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.681 ± 3.302  ops/ms
ClientPb.existUser                       thrpt       3  10.219 ± 2.371  ops/ms
ClientPb.getUser                         thrpt       3   9.884 ± 3.797  ops/ms
ClientPb.listUser                        thrpt       3   8.270 ± 0.451  ops/ms
ClientPb.createUser                       avgt       3   3.242 ± 0.660   ms/op
ClientPb.existUser                        avgt       3   3.156 ± 1.323   ms/op
ClientPb.getUser                          avgt       3   3.301 ± 0.343   ms/op
ClientPb.listUser                         avgt       3   3.877 ± 0.687   ms/op
ClientPb.createUser                     sample  291089   3.297 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.975           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.987           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  303863   3.158 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.935           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.302           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.757           ms/op
ClientPb.getUser                        sample  289192   3.317 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.040           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.479           ms/op
ClientPb.listUser                       sample  246483   3.893 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.264           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.858           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.148           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
