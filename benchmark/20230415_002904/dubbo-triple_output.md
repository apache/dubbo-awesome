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
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 7.050 ops/ms
# Warmup Iteration   3: 9.354 ops/ms
Iteration   1: 9.692 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.105 ±(99.9%) 6.632 ops/ms [Average]
  (min, avg, max) = (9.692, 10.105, 10.375), stdev = 0.364
  CI (99.9%): [3.473, 16.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 9.619 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 9.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (9.794, 9.837, 9.882), stdev = 0.044
  CI (99.9%): [9.034, 10.639] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 8.664 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 9.578 ops/ms
Iteration   2: 9.738 ops/ms
Iteration   3: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.809 ±(99.9%) 4.991 ops/ms [Average]
  (min, avg, max) = (9.578, 9.809, 10.111), stdev = 0.274
  CI (99.9%): [4.818, 14.800] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ops/ms
# Warmup Iteration   2: 7.535 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.090 ±(99.9%) 2.662 ops/ms [Average]
  (min, avg, max) = (7.949, 8.090, 8.240), stdev = 0.146
  CI (99.9%): [5.428, 10.752] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.505 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.005 ms/op
Iteration   1: 3.352 ±(99.9%) 0.009 ms/op
Iteration   2: 3.497 ±(99.9%) 0.004 ms/op
Iteration   3: 3.200 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.350 ±(99.9%) 2.715 ms/op [Average]
  (min, avg, max) = (3.200, 3.350, 3.497), stdev = 0.149
  CI (99.9%): [0.635, 6.064] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.623 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.005 ms/op
Iteration   1: 2.929 ±(99.9%) 0.014 ms/op
Iteration   2: 3.113 ±(99.9%) 0.010 ms/op
Iteration   3: 3.142 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.061 ±(99.9%) 2.114 ms/op [Average]
  (min, avg, max) = (2.929, 3.061, 3.142), stdev = 0.116
  CI (99.9%): [0.948, 5.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.133 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.003 ms/op
Iteration   1: 3.366 ±(99.9%) 0.006 ms/op
Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
Iteration   3: 3.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.366, 3.410, 3.454), stdev = 0.044
  CI (99.9%): [2.602, 4.217] (assumes normal distribution)


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
# Warmup Iteration   1: 8.157 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.007 ms/op
Iteration   1: 3.853 ±(99.9%) 0.004 ms/op
Iteration   2: 3.862 ±(99.9%) 0.008 ms/op
Iteration   3: 3.927 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.881 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.853, 3.881, 3.927), stdev = 0.040
  CI (99.9%): [3.145, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 7.857 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.396 ms/op
                 createUser·p0.999:  11.546 ms/op
                 createUser·p0.9999: 23.184 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.430 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  23.744 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.969 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 22.057 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289555
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21007 
    [ 2.500,  5.000) = 264495 
    [ 5.000,  7.500) = 3129 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     25.855 ms/op
     p(99.9990) =     26.647 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 9.464 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.309 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  17.324 ms/op
                 existUser·p0.9999: 23.245 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 3.286 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  15.072 ms/op
                 existUser·p0.9999: 25.728 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.318 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  10.059 ms/op
                 existUser·p0.9999: 26.337 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290165
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4236 
    [ 2.500,  5.000) = 279584 
    [ 5.000,  7.500) = 5180 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.421 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.853 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 8.016 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  21.534 ms/op
                 getUser·p0.9999: 26.362 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.555 ms/op
                 getUser·p0.9999: 27.443 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282779
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4705 
    [ 2.500,  5.000) = 269197 
    [ 5.000,  7.500) = 7546 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     19.100 ms/op
     p(99.9900) =     26.435 ms/op
     p(99.9990) =     27.854 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 8.057 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.590 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.047 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.939 ms/op
                 listUser·p0.9999: 29.839 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 3.608 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.235 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.555 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.055 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  14.325 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 267535
  mean =      3.584 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 261661 
    [ 5.000,  7.500) = 4067 
    [ 7.500, 10.000) = 899 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     22.487 ms/op
     p(99.9990) =     30.485 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.105 ± 6.632  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 0.802  ops/ms
ClientPb.getUser                         thrpt       3   9.809 ± 4.991  ops/ms
ClientPb.listUser                        thrpt       3   8.090 ± 2.662  ops/ms
ClientPb.createUser                       avgt       3   3.350 ± 2.715   ms/op
ClientPb.existUser                        avgt       3   3.061 ± 2.114   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 0.807   ms/op
ClientPb.listUser                         avgt       3   3.881 ± 0.736   ms/op
ClientPb.createUser                     sample  289555   3.314 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.251           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  290165   3.304 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.421           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  282779   3.392 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.985           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.100           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  267535   3.584 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.821           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.453           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.598           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.487           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.507           ms/op
