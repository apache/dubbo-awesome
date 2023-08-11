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
# Warmup Iteration   1: 2.517 ops/ms
# Warmup Iteration   2: 5.719 ops/ms
# Warmup Iteration   3: 8.710 ops/ms
Iteration   1: 9.742 ops/ms
Iteration   2: 9.532 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.588 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (9.489, 9.588, 9.742), stdev = 0.135
  CI (99.9%): [7.119, 12.056] (assumes normal distribution)


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
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.680 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 9.934 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.009 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (9.934, 10.009, 10.137), stdev = 0.111
  CI (99.9%): [7.981, 12.037] (assumes normal distribution)


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
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 8.877 ops/ms
# Warmup Iteration   3: 8.966 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 9.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.673 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (9.612, 9.673, 9.730), stdev = 0.059
  CI (99.9%): [8.597, 10.750] (assumes normal distribution)


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
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 7.290 ops/ms
# Warmup Iteration   3: 8.410 ops/ms
Iteration   1: 8.252 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.296 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (8.241, 8.296, 8.394), stdev = 0.086
  CI (99.9%): [6.734, 9.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.651 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.005 ms/op
Iteration   1: 3.430 ±(99.9%) 0.007 ms/op
Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
Iteration   3: 3.261 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.322 ±(99.9%) 1.716 ms/op [Average]
  (min, avg, max) = (3.261, 3.322, 3.430), stdev = 0.094
  CI (99.9%): [1.606, 5.039] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.003 ms/op
Iteration   1: 3.230 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.004 ms/op
Iteration   3: 3.162 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.169 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.115, 3.169, 3.230), stdev = 0.058
  CI (99.9%): [2.112, 4.226] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.827 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.005 ms/op
Iteration   1: 3.371 ±(99.9%) 0.005 ms/op
Iteration   2: 3.250 ±(99.9%) 0.004 ms/op
Iteration   3: 3.343 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.321 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.250, 3.321, 3.371), stdev = 0.063
  CI (99.9%): [2.164, 4.478] (assumes normal distribution)


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
# Warmup Iteration   1: 9.577 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.009 ms/op
Iteration   1: 3.880 ±(99.9%) 0.005 ms/op
Iteration   2: 3.771 ±(99.9%) 0.006 ms/op
Iteration   3: 3.802 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.818 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.771, 3.818, 3.880), stdev = 0.056
  CI (99.9%): [2.793, 4.843] (assumes normal distribution)


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
# Warmup Iteration   1: 8.436 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.011 ms/op
Iteration   1: 3.233 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  20.972 ms/op
                 createUser·p0.9999: 23.679 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 24.517 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 24.642 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294913
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18883 
    [ 2.500,  5.000) = 267886 
    [ 5.000,  7.500) = 6802 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 164 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     24.396 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 8.314 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.450 ms/op
                 existUser·p0.99:   6.356 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 22.312 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.710 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.238 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  14.652 ms/op
                 existUser·p0.9999: 25.498 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300034
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20686 
    [ 2.500,  5.000) = 270560 
    [ 5.000,  7.500) = 7279 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 8.146 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.011 ms/op
Iteration   1: 3.385 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  21.052 ms/op
                 getUser·p0.9999: 28.100 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.071 ms/op
                 getUser·p0.999:  12.194 ms/op
                 getUser·p0.9999: 24.101 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  14.954 ms/op
                 getUser·p0.9999: 24.118 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287630
  mean =      3.336 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9897 
    [ 2.500,  5.000) = 267215 
    [ 5.000,  7.500) = 8964 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.126 ms/op
     p(99.9900) =     26.664 ms/op
     p(99.9990) =     29.053 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 9.058 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.013 ms/op
Iteration   1: 3.856 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  21.329 ms/op
                 listUser·p0.9999: 24.599 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.124 ms/op
                 listUser·p0.999:  16.398 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 14.991 ms/op
                 listUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245562
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 232979 
    [ 5.000,  7.500) = 9642 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 591 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     15.326 ms/op
     p(99.9900) =     24.296 ms/op
     p(99.9990) =     27.559 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.588 ± 2.469  ops/ms
ClientPb.existUser                       thrpt       3  10.009 ± 2.028  ops/ms
ClientPb.getUser                         thrpt       3   9.673 ± 1.076  ops/ms
ClientPb.listUser                        thrpt       3   8.296 ± 1.562  ops/ms
ClientPb.createUser                       avgt       3   3.322 ± 1.716   ms/op
ClientPb.existUser                        avgt       3   3.169 ± 1.057   ms/op
ClientPb.getUser                          avgt       3   3.321 ± 1.157   ms/op
ClientPb.listUser                         avgt       3   3.818 ± 1.025   ms/op
ClientPb.createUser                     sample  294913   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.300           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.793           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  300034   3.198 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.320           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.002           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.640           ms/op
ClientPb.getUser                        sample  287630   3.336 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.126           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.664           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  245562   3.908 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.326           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
