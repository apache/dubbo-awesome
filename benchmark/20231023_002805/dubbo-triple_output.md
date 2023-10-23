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
# Warmup Iteration   1: 2.656 ops/ms
# Warmup Iteration   2: 6.746 ops/ms
# Warmup Iteration   3: 9.195 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 9.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.821 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (9.788, 9.821, 9.843), stdev = 0.030
  CI (99.9%): [9.278, 10.365] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 9.576 ops/ms
# Warmup Iteration   3: 10.049 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.333 ±(99.9%) 4.831 ops/ms [Average]
  (min, avg, max) = (10.028, 10.333, 10.493), stdev = 0.265
  CI (99.9%): [5.503, 15.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ops/ms
# Warmup Iteration   2: 9.191 ops/ms
# Warmup Iteration   3: 9.713 ops/ms
Iteration   1: 10.138 ops/ms
Iteration   2: 10.087 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.076 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (10.003, 10.076, 10.138), stdev = 0.068
  CI (99.9%): [8.836, 11.316] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.377 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.517 ops/ms
Iteration   3: 8.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.464 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (8.373, 8.464, 8.517), stdev = 0.079
  CI (99.9%): [7.023, 9.905] (assumes normal distribution)


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
# Warmup Iteration   1: 8.958 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.002 ms/op
Iteration   1: 3.271 ±(99.9%) 0.005 ms/op
Iteration   2: 3.331 ±(99.9%) 0.004 ms/op
Iteration   3: 3.308 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.303 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.271, 3.303, 3.331), stdev = 0.030
  CI (99.9%): [2.758, 3.848] (assumes normal distribution)


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
# Warmup Iteration   1: 7.547 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.034, 3.112, 3.171), stdev = 0.070
  CI (99.9%): [1.834, 4.390] (assumes normal distribution)


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
# Warmup Iteration   1: 8.239 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.187 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.196 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.176, 3.196, 3.226), stdev = 0.026
  CI (99.9%): [2.719, 3.674] (assumes normal distribution)


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
# Warmup Iteration   1: 9.708 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.004 ms/op
Iteration   1: 3.851 ±(99.9%) 0.005 ms/op
Iteration   2: 3.784 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.829 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.784, 3.829, 3.853), stdev = 0.039
  CI (99.9%): [3.111, 4.548] (assumes normal distribution)


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
# Warmup Iteration   1: 8.357 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
Iteration   1: 3.163 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  19.390 ms/op
                 createUser·p0.9999: 22.311 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.331 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  18.752 ms/op
                 createUser·p0.9999: 22.734 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  15.422 ms/op
                 createUser·p0.9999: 26.841 ms/op
                 createUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296014
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16554 
    [ 2.500,  5.000) = 275487 
    [ 5.000,  7.500) = 3007 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.973 ms/op
     p(99.9900) =     25.769 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 7.127 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  18.383 ms/op
                 existUser·p0.9999: 20.436 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.269 ms/op
                 existUser·p0.9999: 26.674 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 19.986 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302307
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20744 
    [ 2.500,  5.000) = 276828 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     27.000 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 7.739 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  18.243 ms/op
                 getUser·p0.9999: 21.119 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  14.194 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  8.855 ms/op
                 getUser·p0.9999: 21.384 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290592
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11359 
    [ 2.500,  5.000) = 273135 
    [ 5.000,  7.500) = 5021 
    [ 7.500, 10.000) = 692 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     13.937 ms/op
     p(99.9900) =     21.756 ms/op
     p(99.9990) =     23.176 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 8.558 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
Iteration   1: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.810 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.138 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 31.578 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.617 ms/op
                 listUser·p0.999:  13.195 ms/op
                 listUser·p0.9999: 15.415 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247952
  mean =      3.868 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 240913 
    [ 5.000,  7.500) = 5328 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     22.420 ms/op
     p(99.9990) =     31.969 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.821 ± 0.544  ops/ms
ClientPb.existUser                       thrpt       3  10.333 ± 4.831  ops/ms
ClientPb.getUser                         thrpt       3  10.076 ± 1.240  ops/ms
ClientPb.listUser                        thrpt       3   8.464 ± 1.441  ops/ms
ClientPb.createUser                       avgt       3   3.303 ± 0.545   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 1.278   ms/op
ClientPb.getUser                          avgt       3   3.196 ± 0.477   ms/op
ClientPb.listUser                         avgt       3   3.829 ± 0.719   ms/op
ClientPb.createUser                     sample  296014   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.803           ms/op
ClientPb.existUser                      sample  302307   3.176 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.320           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.723           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  290592   3.301 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.937           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.626           ms/op
ClientPb.listUser                       sample  247952   3.868 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.566           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
