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
# Warmup Iteration   1: 2.661 ops/ms
# Warmup Iteration   2: 6.667 ops/ms
# Warmup Iteration   3: 9.089 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.700 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (9.700, 9.797, 9.904), stdev = 0.102
  CI (99.9%): [7.934, 11.660] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.975 ops/ms
Iteration   1: 9.792 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.061 ±(99.9%) 7.895 ops/ms [Average]
  (min, avg, max) = (9.792, 10.061, 10.560), stdev = 0.433
  CI (99.9%): [2.167, 17.956] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.518 ops/ms
# Warmup Iteration   2: 9.342 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 9.960 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.072 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (9.960, 10.072, 10.215), stdev = 0.131
  CI (99.9%): [7.689, 12.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.493 ops/ms
Iteration   1: 8.718 ops/ms
Iteration   2: 8.451 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 2.483 ops/ms [Average]
  (min, avg, max) = (8.451, 8.599, 8.718), stdev = 0.136
  CI (99.9%): [6.116, 11.082] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.776 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.003 ms/op
Iteration   1: 3.331 ±(99.9%) 0.010 ms/op
Iteration   2: 3.323 ±(99.9%) 0.008 ms/op
Iteration   3: 3.300 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.318 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.300, 3.318, 3.331), stdev = 0.016
  CI (99.9%): [3.022, 3.614] (assumes normal distribution)


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
# Warmup Iteration   1: 7.617 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.005 ms/op
Iteration   1: 3.199 ±(99.9%) 0.008 ms/op
Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (2.997, 3.102, 3.199), stdev = 0.101
  CI (99.9%): [1.254, 4.951] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.381 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.003 ms/op
Iteration   1: 3.247 ±(99.9%) 0.004 ms/op
Iteration   2: 3.235 ±(99.9%) 0.005 ms/op
Iteration   3: 3.218 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.218, 3.233, 3.247), stdev = 0.014
  CI (99.9%): [2.973, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 9.390 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.006 ms/op
Iteration   1: 3.821 ±(99.9%) 0.005 ms/op
Iteration   2: 3.706 ±(99.9%) 0.011 ms/op
Iteration   3: 3.720 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (3.706, 3.749, 3.821), stdev = 0.063
  CI (99.9%): [2.609, 4.889] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.232 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
Iteration   1: 3.111 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 20.462 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  17.984 ms/op
                 createUser·p0.9999: 22.539 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  14.189 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302947
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19668 
    [ 2.500,  5.000) = 278474 
    [ 5.000,  7.500) = 3777 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 196 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.960 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     23.231 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 7.915 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 25.134 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.937 ms/op
                 existUser·p0.9999: 20.350 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306165
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18600 
    [ 2.500,  5.000) = 282715 
    [ 5.000,  7.500) = 4256 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.586 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.987 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.262 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  19.754 ms/op
                 getUser·p0.9999: 25.937 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  16.810 ms/op
                 getUser·p0.9999: 22.060 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297697
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12702 
    [ 2.500,  5.000) = 278123 
    [ 5.000,  7.500) = 5731 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     26.492 ms/op
     p(99.9990) =     29.462 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 8.622 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.011 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  16.875 ms/op
                 listUser·p0.9999: 20.762 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.730 ms/op
                 listUser·p0.999:  15.987 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 3.677 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  11.583 ms/op
                 listUser·p0.9999: 14.259 ms/op
                 listUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257804
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 252185 
    [ 5.000,  7.500) = 3831 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     21.241 ms/op
     p(99.9990) =     22.457 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 1.863  ops/ms
ClientPb.existUser                       thrpt       3  10.061 ± 7.895  ops/ms
ClientPb.getUser                         thrpt       3  10.072 ± 2.383  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 2.483  ops/ms
ClientPb.createUser                       avgt       3   3.318 ± 0.296   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.849   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 1.140   ms/op
ClientPb.createUser                     sample  302947   3.167 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.960           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.103           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.396           ms/op
ClientPb.existUser                      sample  306165   3.135 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  297697   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.857           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.492           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  257804   3.723 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.233           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.938           ms/op
