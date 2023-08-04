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
# Warmup Iteration   1: 2.478 ops/ms
# Warmup Iteration   2: 6.416 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.467 ops/ms
Iteration   2: 10.150 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.872 ±(99.9%) 6.546 ops/ms [Average]
  (min, avg, max) = (9.467, 9.872, 10.150), stdev = 0.359
  CI (99.9%): [3.326, 16.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 9.079 ops/ms
# Warmup Iteration   3: 9.754 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.352 ±(99.9%) 4.439 ops/ms [Average]
  (min, avg, max) = (10.096, 10.352, 10.580), stdev = 0.243
  CI (99.9%): [5.914, 14.791] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 9.858 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.941 ops/ms
Iteration   3: 9.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.811 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (9.646, 9.811, 9.941), stdev = 0.150
  CI (99.9%): [7.072, 12.549] (assumes normal distribution)


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
# Warmup Iteration   1: 2.976 ops/ms
# Warmup Iteration   2: 7.248 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.461 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.412 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (8.303, 8.412, 8.472), stdev = 0.094
  CI (99.9%): [6.690, 10.134] (assumes normal distribution)


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
# Warmup Iteration   1: 8.443 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.004 ms/op
Iteration   1: 3.378 ±(99.9%) 0.003 ms/op
Iteration   2: 3.364 ±(99.9%) 0.006 ms/op
Iteration   3: 3.139 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.294 ±(99.9%) 2.450 ms/op [Average]
  (min, avg, max) = (3.139, 3.294, 3.378), stdev = 0.134
  CI (99.9%): [0.844, 5.744] (assumes normal distribution)


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
# Warmup Iteration   1: 6.715 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.004 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.140 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.087, 3.140, 3.212), stdev = 0.065
  CI (99.9%): [1.953, 4.326] (assumes normal distribution)


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
# Warmup Iteration   1: 7.448 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.002 ms/op
Iteration   2: 3.227 ±(99.9%) 0.006 ms/op
Iteration   3: 3.212 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.205 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.176, 3.205, 3.227), stdev = 0.026
  CI (99.9%): [2.734, 3.676] (assumes normal distribution)


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
# Warmup Iteration   1: 8.618 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.005 ms/op
Iteration   1: 3.808 ±(99.9%) 0.005 ms/op
Iteration   2: 3.805 ±(99.9%) 0.007 ms/op
Iteration   3: 3.764 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.792 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.764, 3.792, 3.808), stdev = 0.025
  CI (99.9%): [3.340, 4.244] (assumes normal distribution)


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
# Warmup Iteration   1: 7.190 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
Iteration   1: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  10.666 ms/op
                 createUser·p0.9999: 22.979 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.649 ms/op
                 createUser·p0.999:  20.569 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.586 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291566
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19583 
    [ 2.500,  5.000) = 264258 
    [ 5.000,  7.500) = 6573 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     14.969 ms/op
     p(99.9900) =     21.884 ms/op
     p(99.9990) =     23.437 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 7.038 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.707 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 23.396 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  11.032 ms/op
                 existUser·p0.9999: 22.316 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296165
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23967 
    [ 2.500,  5.000) = 263050 
    [ 5.000,  7.500) = 8060 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     10.581 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.732 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 7.165 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.014 ms/op
Iteration   1: 3.304 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  11.491 ms/op
                 getUser·p0.9999: 19.878 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 22.229 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  16.733 ms/op
                 getUser·p0.9999: 25.160 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290885
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22797 
    [ 2.500,  5.000) = 259362 
    [ 5.000,  7.500) = 7433 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     13.614 ms/op
     p(99.9900) =     23.587 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.012 ms/op
Iteration   1: 3.829 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.402 ms/op
                 listUser·p0.999:  14.593 ms/op
                 listUser·p0.9999: 19.059 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 19.782 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249770
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 79 
    [ 2.500,  3.750) = 159289 
    [ 3.750,  5.000) = 79646 
    [ 5.000,  6.250) = 3634 
    [ 6.250,  7.500) = 3806 
    [ 7.500,  8.750) = 1531 
    [ 8.750, 10.000) = 956 
    [10.000, 11.250) = 233 
    [11.250, 12.500) = 210 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 103 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     19.335 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.872 ± 6.546  ops/ms
ClientPb.existUser                       thrpt       3  10.352 ± 4.439  ops/ms
ClientPb.getUser                         thrpt       3   9.811 ± 2.739  ops/ms
ClientPb.listUser                        thrpt       3   8.412 ± 1.722  ops/ms
ClientPb.createUser                       avgt       3   3.294 ± 2.450   ms/op
ClientPb.existUser                        avgt       3   3.140 ± 1.186   ms/op
ClientPb.getUser                          avgt       3   3.205 ± 0.471   ms/op
ClientPb.listUser                         avgt       3   3.792 ± 0.452   ms/op
ClientPb.createUser                     sample  291566   3.293 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.969           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.884           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.790           ms/op
ClientPb.existUser                      sample  296165   3.238 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.581           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.774           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  290885   3.298 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.614           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.587           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  249770   3.841 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.118           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.890           ms/op
