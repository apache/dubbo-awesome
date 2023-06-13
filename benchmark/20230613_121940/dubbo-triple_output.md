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
# Warmup Iteration   1: 2.283 ops/ms
# Warmup Iteration   2: 6.173 ops/ms
# Warmup Iteration   3: 9.328 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 10.137 ops/ms
Iteration   3: 9.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.949 ±(99.9%) 3.509 ops/ms [Average]
  (min, avg, max) = (9.752, 9.949, 10.137), stdev = 0.192
  CI (99.9%): [6.440, 13.458] (assumes normal distribution)


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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.566 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.186 ±(99.9%) 7.770 ops/ms [Average]
  (min, avg, max) = (9.909, 10.186, 10.677), stdev = 0.426
  CI (99.9%): [2.416, 17.956] (assumes normal distribution)


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
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 8.669 ops/ms
# Warmup Iteration   3: 9.563 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 10.231 ops/ms
Iteration   3: 9.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.038 ±(99.9%) 4.398 ops/ms [Average]
  (min, avg, max) = (9.768, 10.038, 10.231), stdev = 0.241
  CI (99.9%): [5.639, 14.436] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 7.774 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.439 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (8.372, 8.439, 8.511), stdev = 0.070
  CI (99.9%): [7.168, 9.710] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.134 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.005 ms/op
Iteration   1: 3.214 ±(99.9%) 0.006 ms/op
Iteration   2: 3.199 ±(99.9%) 0.005 ms/op
Iteration   3: 3.180 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.198 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.180, 3.198, 3.214), stdev = 0.017
  CI (99.9%): [2.892, 3.504] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
Iteration   3: 3.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.130 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.062, 3.130, 3.249), stdev = 0.104
  CI (99.9%): [1.239, 5.021] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.384 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.004 ms/op
Iteration   2: 3.180 ±(99.9%) 0.005 ms/op
Iteration   3: 3.305 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.257 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.180, 3.257, 3.305), stdev = 0.067
  CI (99.9%): [2.029, 4.484] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.428 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.009 ms/op
Iteration   1: 3.763 ±(99.9%) 0.008 ms/op
Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
Iteration   3: 3.658 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.658, 3.727, 3.763), stdev = 0.060
  CI (99.9%): [2.637, 4.818] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.600 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
Iteration   1: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  10.895 ms/op
                 createUser·p0.9999: 26.404 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  10.152 ms/op
                 createUser·p0.9999: 24.319 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.742 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295456
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19608 
    [ 2.500,  5.000) = 270838 
    [ 5.000,  7.500) = 4299 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     15.916 ms/op
     p(99.9900) =     24.853 ms/op
     p(99.9990) =     26.676 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 7.333 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 19.632 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  9.405 ms/op
                 existUser·p0.9999: 26.503 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303035
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30846 
    [ 2.500,  5.000) = 266560 
    [ 5.000,  7.500) = 5069 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     25.451 ms/op
     p(99.9990) =     26.901 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.591 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
Iteration   1: 3.377 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  18.113 ms/op
                 getUser·p0.9999: 25.478 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  10.764 ms/op
                 getUser·p0.9999: 23.080 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  11.877 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293463
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18427 
    [ 2.500,  5.000) = 268673 
    [ 5.000,  7.500) = 5548 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     17.614 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 9.406 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.011 ms/op
Iteration   1: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 23.005 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.745 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.132 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 3.745 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.395 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.052 ms/op
                 listUser·p0.9999: 14.909 ms/op
                 listUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255530
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 247732 
    [ 5.000,  7.500) = 6517 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     23.506 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.949 ± 3.509  ops/ms
ClientPb.existUser                       thrpt       3  10.186 ± 7.770  ops/ms
ClientPb.getUser                         thrpt       3  10.038 ± 4.398  ops/ms
ClientPb.listUser                        thrpt       3   8.439 ± 1.271  ops/ms
ClientPb.createUser                       avgt       3   3.198 ± 0.306   ms/op
ClientPb.existUser                        avgt       3   3.130 ± 1.891   ms/op
ClientPb.getUser                          avgt       3   3.257 ± 1.227   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 1.091   ms/op
ClientPb.createUser                     sample  295456   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.916           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.804           ms/op
ClientPb.existUser                      sample  303035   3.166 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.847           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  293463   3.269 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.614           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.921           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.313           ms/op
ClientPb.listUser                       sample  255530   3.756 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.150           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.988           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
