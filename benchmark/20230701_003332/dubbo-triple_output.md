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
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 5.379 ops/ms
# Warmup Iteration   3: 9.029 ops/ms
Iteration   1: 9.782 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.736 ±(99.9%) 3.227 ops/ms [Average]
  (min, avg, max) = (9.541, 9.736, 9.886), stdev = 0.177
  CI (99.9%): [6.509, 12.963] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 8.410 ops/ms
# Warmup Iteration   3: 9.966 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 9.909 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.300 ±(99.9%) 6.383 ops/ms [Average]
  (min, avg, max) = (9.909, 10.300, 10.583), stdev = 0.350
  CI (99.9%): [3.917, 16.683] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 9.725 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 10.047 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.707 ±(99.9%) 5.564 ops/ms [Average]
  (min, avg, max) = (9.458, 9.707, 10.047), stdev = 0.305
  CI (99.9%): [4.143, 15.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 7.118 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.372 ±(99.9%) 4.141 ops/ms [Average]
  (min, avg, max) = (8.191, 8.372, 8.627), stdev = 0.227
  CI (99.9%): [4.230, 12.513] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.847 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.006 ms/op
Iteration   1: 3.365 ±(99.9%) 0.006 ms/op
Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 1.632 ms/op [Average]
  (min, avg, max) = (3.186, 3.273, 3.365), stdev = 0.089
  CI (99.9%): [1.641, 4.906] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.883 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.003 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
Iteration   2: 3.143 ±(99.9%) 0.005 ms/op
Iteration   3: 3.263 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.241 ±(99.9%) 1.617 ms/op [Average]
  (min, avg, max) = (3.143, 3.241, 3.316), stdev = 0.089
  CI (99.9%): [1.623, 4.858] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.766 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.005 ms/op
Iteration   1: 3.327 ±(99.9%) 0.007 ms/op
Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
Iteration   3: 3.219 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.285 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (3.219, 3.285, 3.327), stdev = 0.058
  CI (99.9%): [2.229, 4.341] (assumes normal distribution)


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
# Warmup Iteration   1: 10.024 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.007 ms/op
Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
Iteration   2: 3.782 ±(99.9%) 0.009 ms/op
Iteration   3: 3.879 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.799 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.738, 3.799, 3.879), stdev = 0.072
  CI (99.9%): [2.484, 5.115] (assumes normal distribution)


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
# Warmup Iteration   1: 9.479 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.011 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  12.227 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.623 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 24.610 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  14.701 ms/op
                 createUser·p0.9999: 23.492 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294184
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8073 
    [ 2.500,  5.000) = 281242 
    [ 5.000,  7.500) = 4113 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     23.841 ms/op
     p(99.9990) =     24.807 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 8.622 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  13.761 ms/op
                 existUser·p0.9999: 21.747 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.230 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  16.138 ms/op
                 existUser·p0.9999: 24.422 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  14.863 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294384
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8655 
    [ 2.500,  5.000) = 280224 
    [ 5.000,  7.500) = 4441 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     24.201 ms/op
     p(99.9990) =     25.037 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 9.169 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.011 ms/op
Iteration   1: 3.351 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 20.494 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  19.934 ms/op
                 getUser·p0.9999: 22.795 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  13.668 ms/op
                 getUser·p0.9999: 22.868 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287086
  mean =      3.343 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17164 
    [ 2.500,  5.000) = 259551 
    [ 5.000,  7.500) = 9091 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.933 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 10.427 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.489 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 22.382 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 19.199 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 16.896 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244358
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 235875 
    [ 5.000,  7.500) = 5849 
    [ 7.500, 10.000) = 1828 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     16.132 ms/op
     p(99.9900) =     21.926 ms/op
     p(99.9990) =     22.902 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.736 ± 3.227  ops/ms
ClientPb.existUser                       thrpt       3  10.300 ± 6.383  ops/ms
ClientPb.getUser                         thrpt       3   9.707 ± 5.564  ops/ms
ClientPb.listUser                        thrpt       3   8.372 ± 4.141  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 1.632   ms/op
ClientPb.existUser                        avgt       3   3.241 ± 1.617   ms/op
ClientPb.getUser                          avgt       3   3.285 ± 1.056   ms/op
ClientPb.listUser                         avgt       3   3.799 ± 1.316   ms/op
ClientPb.createUser                     sample  294184   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.841           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.100           ms/op
ClientPb.existUser                      sample  294384   3.258 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.201           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  287086   3.343 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  244358   3.924 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.132           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.926           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
