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
# Warmup Iteration   1: 2.363 ops/ms
# Warmup Iteration   2: 5.530 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.669 ops/ms
Iteration   3: 9.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.713 ±(99.9%) 1.840 ops/ms [Average]
  (min, avg, max) = (9.641, 9.713, 9.828), stdev = 0.101
  CI (99.9%): [7.872, 11.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ops/ms
# Warmup Iteration   2: 9.586 ops/ms
# Warmup Iteration   3: 9.773 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.084 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (10.027, 10.084, 10.141), stdev = 0.057
  CI (99.9%): [9.045, 11.123] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ops/ms
# Warmup Iteration   2: 9.323 ops/ms
# Warmup Iteration   3: 8.860 ops/ms
Iteration   1: 9.803 ops/ms
Iteration   2: 9.429 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.615 ±(99.9%) 3.406 ops/ms [Average]
  (min, avg, max) = (9.429, 9.615, 9.803), stdev = 0.187
  CI (99.9%): [6.210, 13.021] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 7.515 ops/ms
# Warmup Iteration   3: 8.116 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.393 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (8.277, 8.393, 8.553), stdev = 0.143
  CI (99.9%): [5.783, 11.003] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.750 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.007 ms/op
Iteration   1: 3.289 ±(99.9%) 0.005 ms/op
Iteration   2: 3.184 ±(99.9%) 0.005 ms/op
Iteration   3: 3.205 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.226 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.184, 3.226, 3.289), stdev = 0.056
  CI (99.9%): [2.212, 4.240] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.705 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.157 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.078 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (3.008, 3.078, 3.157), stdev = 0.075
  CI (99.9%): [1.714, 4.441] (assumes normal distribution)


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
# Warmup Iteration   1: 8.318 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.004 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
Iteration   3: 3.256 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.155, 3.192, 3.256), stdev = 0.056
  CI (99.9%): [2.174, 4.210] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.204 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.005 ms/op
Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
Iteration   2: 3.758 ±(99.9%) 0.007 ms/op
Iteration   3: 3.688 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.733 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.688, 3.733, 3.758), stdev = 0.039
  CI (99.9%): [3.017, 4.449] (assumes normal distribution)


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
# Warmup Iteration   1: 7.381 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.010 ms/op
Iteration   1: 3.217 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 30.214 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.799 ms/op
                 createUser·p0.999:  10.799 ms/op
                 createUser·p0.9999: 22.370 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  11.017 ms/op
                 createUser·p0.9999: 19.422 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294919
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26276 
    [ 2.500,  5.000) = 261911 
    [ 5.000,  7.500) = 5432 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     15.992 ms/op
     p(99.9900) =     28.886 ms/op
     p(99.9990) =     30.882 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 25.824 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   2: 3.210 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  11.213 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   3: 3.150 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300235
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17014 
    [ 2.500,  5.000) = 275187 
    [ 5.000,  7.500) = 6933 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     25.230 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 6.724 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.013 ms/op
Iteration   1: 3.300 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  11.172 ms/op
                 getUser·p0.9999: 19.835 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  18.076 ms/op
                 getUser·p0.9999: 20.790 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 3.366 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  14.811 ms/op
                 getUser·p0.9999: 26.755 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287345
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19216 
    [ 2.500,  5.000) = 259836 
    [ 5.000,  7.500) = 6823 
    [ 7.500, 10.000) = 1021 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     25.011 ms/op
     p(99.9990) =     27.013 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 9.240 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.012 ms/op
Iteration   1: 3.774 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  19.432 ms/op
                 listUser·p0.9999: 26.691 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 3.804 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 22.289 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253297
  mean =      3.786 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 244124 
    [ 5.000,  7.500) = 6369 
    [ 7.500, 10.000) = 1936 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     25.089 ms/op
     p(99.9990) =     27.604 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.713 ± 1.840  ops/ms
ClientPb.existUser                       thrpt       3  10.084 ± 1.039  ops/ms
ClientPb.getUser                         thrpt       3   9.615 ± 3.406  ops/ms
ClientPb.listUser                        thrpt       3   8.393 ± 2.610  ops/ms
ClientPb.createUser                       avgt       3   3.226 ± 1.014   ms/op
ClientPb.existUser                        avgt       3   3.078 ± 1.364   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   3.733 ± 0.716   ms/op
ClientPb.createUser                     sample  294919   3.255 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.975           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.992           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  300235   3.196 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.230           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  287345   3.339 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.811           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.011           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  253297   3.786 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.194           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.089           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
