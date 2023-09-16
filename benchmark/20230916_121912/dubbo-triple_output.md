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
# Warmup Iteration   1: 2.079 ops/ms
# Warmup Iteration   2: 6.130 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 9.052 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.252 ±(99.9%) 4.267 ops/ms [Average]
  (min, avg, max) = (9.052, 9.252, 9.509), stdev = 0.234
  CI (99.9%): [4.985, 13.520] (assumes normal distribution)


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
# Warmup Iteration   1: 3.057 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.439 ops/ms
Iteration   1: 9.761 ops/ms
Iteration   2: 9.888 ops/ms
Iteration   3: 9.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.768 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (9.655, 9.768, 9.888), stdev = 0.117
  CI (99.9%): [7.637, 11.899] (assumes normal distribution)


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
# Warmup Iteration   1: 3.374 ops/ms
# Warmup Iteration   2: 8.683 ops/ms
# Warmup Iteration   3: 9.197 ops/ms
Iteration   1: 9.223 ops/ms
Iteration   2: 9.270 ops/ms
Iteration   3: 9.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.187 ±(99.9%) 1.918 ops/ms [Average]
  (min, avg, max) = (9.069, 9.187, 9.270), stdev = 0.105
  CI (99.9%): [7.269, 11.106] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 7.145 ops/ms
# Warmup Iteration   3: 7.252 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 7.835 ops/ms
Iteration   3: 7.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (7.740, 7.780, 7.835), stdev = 0.049
  CI (99.9%): [6.878, 8.682] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.535 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.003 ms/op
Iteration   1: 3.429 ±(99.9%) 0.006 ms/op
Iteration   2: 3.434 ±(99.9%) 0.005 ms/op
Iteration   3: 3.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.442 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.429, 3.442, 3.462), stdev = 0.018
  CI (99.9%): [3.122, 3.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.427 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.004 ms/op
Iteration   1: 3.300 ±(99.9%) 0.004 ms/op
Iteration   2: 3.274 ±(99.9%) 0.005 ms/op
Iteration   3: 3.358 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.311 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.274, 3.311, 3.358), stdev = 0.043
  CI (99.9%): [2.525, 4.096] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.163 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.006 ms/op
Iteration   1: 3.430 ±(99.9%) 0.004 ms/op
Iteration   2: 3.502 ±(99.9%) 0.004 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.399, 3.444, 3.502), stdev = 0.053
  CI (99.9%): [2.480, 4.407] (assumes normal distribution)


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
# Warmup Iteration   1: 9.612 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.009 ms/op
Iteration   1: 4.120 ±(99.9%) 0.005 ms/op
Iteration   2: 4.037 ±(99.9%) 0.006 ms/op
Iteration   3: 4.027 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.061 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (4.027, 4.061, 4.120), stdev = 0.051
  CI (99.9%): [3.124, 4.998] (assumes normal distribution)


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
# Warmup Iteration   1: 9.702 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.012 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.089 ms/op
                 createUser·p0.999:  21.331 ms/op
                 createUser·p0.9999: 23.753 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  24.210 ms/op
                 createUser·p0.9999: 26.207 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  18.009 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275624
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8921 
    [ 2.500,  5.000) = 261757 
    [ 5.000,  7.500) = 3568 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     18.264 ms/op
     p(99.9900) =     25.868 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 7.856 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.287 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  7.657 ms/op
                 existUser·p0.9999: 22.434 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  22.301 ms/op
                 existUser·p0.9999: 26.458 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   3: 3.295 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.715 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 30.985 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289478
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8365 
    [ 2.500,  5.000) = 275741 
    [ 5.000,  7.500) = 4400 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     29.329 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 10.067 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.010 ms/op
Iteration   1: 3.629 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 24.104 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  22.352 ms/op
                 getUser·p0.9999: 25.219 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  20.205 ms/op
                 getUser·p0.9999: 24.951 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273311
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4358 
    [ 2.500,  5.000) = 260431 
    [ 5.000,  7.500) = 6521 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.911 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.929 ms/op
     p(99.9000) =     19.000 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.350 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.712 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 24.415 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   2: 4.039 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.998 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.657 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237669
  mean =      4.038 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 229985 
    [ 5.000,  7.500) = 5921 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     22.230 ms/op
     p(99.9990) =     25.588 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.252 ± 4.267  ops/ms
ClientPb.existUser                       thrpt       3   9.768 ± 2.131  ops/ms
ClientPb.getUser                         thrpt       3   9.187 ± 1.918  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 0.902  ops/ms
ClientPb.createUser                       avgt       3   3.442 ± 0.319   ms/op
ClientPb.existUser                        avgt       3   3.311 ± 0.786   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.963   ms/op
ClientPb.listUser                         avgt       3   4.061 ± 0.937   ms/op
ClientPb.createUser                     sample  275624   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.868           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.870           ms/op
ClientPb.existUser                      sample  289478   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  273311   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.911           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.929           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.000           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.707           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  237669   4.038 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.247           ms/op
