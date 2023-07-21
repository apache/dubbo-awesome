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
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 7.120 ops/ms
# Warmup Iteration   3: 9.451 ops/ms
Iteration   1: 9.846 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.929 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (9.846, 9.929, 10.046), stdev = 0.104
  CI (99.9%): [8.033, 11.825] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 9.558 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 10.166 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.139 ±(99.9%) 3.444 ops/ms [Average]
  (min, avg, max) = (9.938, 10.139, 10.313), stdev = 0.189
  CI (99.9%): [6.696, 13.583] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ops/ms
# Warmup Iteration   2: 9.392 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.892 ±(99.9%) 6.499 ops/ms [Average]
  (min, avg, max) = (9.490, 9.892, 10.169), stdev = 0.356
  CI (99.9%): [3.393, 16.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 7.774 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.465 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.355, 8.465, 8.564), stdev = 0.105
  CI (99.9%): [6.553, 10.377] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.063 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.192 ±(99.9%) 0.005 ms/op
Iteration   2: 3.331 ±(99.9%) 0.006 ms/op
Iteration   3: 3.161 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.161, 3.228, 3.331), stdev = 0.091
  CI (99.9%): [1.573, 4.884] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.004 ms/op
Iteration   1: 3.125 ±(99.9%) 0.009 ms/op
Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
Iteration   3: 3.029 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.127 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (3.029, 3.127, 3.226), stdev = 0.099
  CI (99.9%): [1.326, 4.927] (assumes normal distribution)


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
# Warmup Iteration   1: 7.953 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.004 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
Iteration   3: 3.175 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.175, 3.188, 3.194), stdev = 0.011
  CI (99.9%): [2.989, 3.387] (assumes normal distribution)


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
# Warmup Iteration   1: 9.064 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.007 ms/op
Iteration   1: 3.773 ±(99.9%) 0.008 ms/op
Iteration   2: 3.860 ±(99.9%) 0.007 ms/op
Iteration   3: 3.830 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.821 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.773, 3.821, 3.860), stdev = 0.044
  CI (99.9%): [3.015, 4.627] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.618 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.011 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.974 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 21.275 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  15.743 ms/op
                 createUser·p0.9999: 24.731 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  15.124 ms/op
                 createUser·p0.9999: 20.276 ms/op
                 createUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291461
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16497 
    [ 2.500,  5.000) = 266621 
    [ 5.000,  7.500) = 7395 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     21.786 ms/op
     p(99.9990) =     24.942 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.561 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.659 ms/op
                 existUser·p0.999:  11.380 ms/op
                 existUser·p0.9999: 21.258 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 21.483 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  14.129 ms/op
                 existUser·p0.9999: 20.291 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304108
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21551 
    [ 2.500,  5.000) = 276050 
    [ 5.000,  7.500) = 5537 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     21.220 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 7.529 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.010 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 22.096 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  10.010 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296871
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9803 
    [ 2.500,  5.000) = 279153 
    [ 5.000,  7.500) = 6878 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.498 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 9.262 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.047 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 21.050 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.923 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.204 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   3: 3.773 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.825 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 14.911 ms/op
                 listUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255805
  mean =      3.751 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 249173 
    [ 5.000,  7.500) = 4729 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 378 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.890 ms/op
     p(99.9900) =     20.002 ms/op
     p(99.9990) =     21.786 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.929 ± 1.896  ops/ms
ClientPb.existUser                       thrpt       3  10.139 ± 3.444  ops/ms
ClientPb.getUser                         thrpt       3   9.892 ± 6.499  ops/ms
ClientPb.listUser                        thrpt       3   8.465 ± 1.912  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 1.656   ms/op
ClientPb.existUser                        avgt       3   3.127 ± 1.801   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   3.821 ± 0.806   ms/op
ClientPb.createUser                     sample  291461   3.295 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.786           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  304108   3.158 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.566           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.220           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.086           ms/op
ClientPb.getUser                        sample  296871   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  255805   3.751 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.890           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.002           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.381           ms/op
