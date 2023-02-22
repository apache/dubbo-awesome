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
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 10.104 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.146 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (10.104, 10.146, 10.219), stdev = 0.064
  CI (99.9%): [8.977, 11.314] (assumes normal distribution)


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
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 9.842 ops/ms
# Warmup Iteration   3: 10.494 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.140 ops/ms
Iteration   3: 10.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.344 ±(99.9%) 5.757 ops/ms [Average]
  (min, avg, max) = (10.140, 10.344, 10.707), stdev = 0.316
  CI (99.9%): [4.587, 16.101] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ops/ms
# Warmup Iteration   2: 9.653 ops/ms
# Warmup Iteration   3: 9.718 ops/ms
Iteration   1: 10.107 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.196 ±(99.9%) 1.612 ops/ms [Average]
  (min, avg, max) = (10.107, 10.196, 10.284), stdev = 0.088
  CI (99.9%): [8.585, 11.808] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ops/ms
# Warmup Iteration   2: 7.945 ops/ms
# Warmup Iteration   3: 8.651 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 8.560 ops/ms
Iteration   3: 8.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.662 ±(99.9%) 2.366 ops/ms [Average]
  (min, avg, max) = (8.560, 8.662, 8.808), stdev = 0.130
  CI (99.9%): [6.296, 11.028] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.456 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.005 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.108 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.087, 3.108, 3.135), stdev = 0.025
  CI (99.9%): [2.658, 3.557] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.526 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
Iteration   3: 3.074 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.004 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (2.926, 3.004, 3.074), stdev = 0.075
  CI (99.9%): [1.641, 4.368] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.236 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.003 ms/op
Iteration   1: 3.196 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
Iteration   3: 3.294 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.158, 3.216, 3.294), stdev = 0.070
  CI (99.9%): [1.936, 4.496] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.999 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.005 ms/op
Iteration   1: 3.876 ±(99.9%) 0.006 ms/op
Iteration   2: 3.760 ±(99.9%) 0.008 ms/op
Iteration   3: 3.632 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (3.632, 3.756, 3.876), stdev = 0.122
  CI (99.9%): [1.533, 5.978] (assumes normal distribution)


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
# Warmup Iteration   1: 7.810 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  13.369 ms/op
                 createUser·p0.9999: 22.213 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.865 ms/op
                 createUser·p0.9999: 22.051 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   4.791 ms/op
                 createUser·p0.999:  11.806 ms/op
                 createUser·p0.9999: 21.419 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304415
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25093 
    [ 2.500,  5.000) = 274311 
    [ 5.000,  7.500) = 4120 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 166 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     12.871 ms/op
     p(99.9900) =     21.973 ms/op
     p(99.9990) =     22.604 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 7.202 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.797 ms/op
                 existUser·p0.999:  9.323 ms/op
                 existUser·p0.9999: 21.571 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.323 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 21.960 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  13.419 ms/op
                 existUser·p0.9999: 20.266 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316907
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21111 
    [ 2.500,  5.000) = 291887 
    [ 5.000,  7.500) = 3151 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     21.461 ms/op
     p(99.9990) =     22.271 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 7.370 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.010 ms/op
Iteration   1: 3.460 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 19.489 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  19.778 ms/op
                 getUser·p0.9999: 22.704 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.361 ms/op
                 getUser·p0.9999: 24.320 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293452
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21007 
    [ 2.500,  5.000) = 264055 
    [ 5.000,  7.500) = 7349 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     17.549 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.775 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 10.050 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.774 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  18.395 ms/op
                 listUser·p0.9999: 23.185 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 16.290 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   3: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.155 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257232
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 248174 
    [ 5.000,  7.500) = 7263 
    [ 7.500, 10.000) = 1106 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.804 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.146 ± 1.169  ops/ms
ClientPb.existUser                       thrpt       3  10.344 ± 5.757  ops/ms
ClientPb.getUser                         thrpt       3  10.196 ± 1.612  ops/ms
ClientPb.listUser                        thrpt       3   8.662 ± 2.366  ops/ms
ClientPb.createUser                       avgt       3   3.108 ± 0.449   ms/op
ClientPb.existUser                        avgt       3   3.004 ± 1.364   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 1.280   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 2.222   ms/op
ClientPb.createUser                     sample  304415   3.151 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.871           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.973           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.643           ms/op
ClientPb.existUser                      sample  316907   3.027 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.461           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.643           ms/op
ClientPb.getUser                        sample  293452   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  257232   3.727 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.235           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.559           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.823           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
