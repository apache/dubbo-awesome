# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.253 ops/ms
# Warmup Iteration   2: 6.164 ops/ms
# Warmup Iteration   3: 9.321 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 9.725 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.620 ±(99.9%) 2.926 ops/ms [Average]
  (min, avg, max) = (9.436, 9.620, 9.725), stdev = 0.160
  CI (99.9%): [6.694, 12.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ops/ms
# Warmup Iteration   2: 9.471 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.375 ±(99.9%) 3.687 ops/ms [Average]
  (min, avg, max) = (10.146, 10.375, 10.528), stdev = 0.202
  CI (99.9%): [6.688, 14.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.106 ops/ms
# Warmup Iteration   2: 8.972 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.218 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.171 ±(99.9%) 1.113 ops/ms [Average]
  (min, avg, max) = (10.102, 10.171, 10.218), stdev = 0.061
  CI (99.9%): [9.058, 11.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ops/ms
# Warmup Iteration   2: 7.586 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 8.775 ops/ms
Iteration   2: 8.392 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.401 ±(99.9%) 6.736 ops/ms [Average]
  (min, avg, max) = (8.036, 8.401, 8.775), stdev = 0.369
  CI (99.9%): [1.665, 15.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.051 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
Iteration   2: 3.215 ±(99.9%) 0.006 ms/op
Iteration   3: 3.207 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.124, 3.182, 3.215), stdev = 0.050
  CI (99.9%): [2.264, 4.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op
Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
Iteration   3: 3.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.160, 3.204, 3.227), stdev = 0.038
  CI (99.9%): [2.505, 3.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.011 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.007 ms/op
Iteration   1: 3.296 ±(99.9%) 0.011 ms/op
Iteration   2: 3.288 ±(99.9%) 0.006 ms/op
Iteration   3: 3.185 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.256 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (3.185, 3.256, 3.296), stdev = 0.062
  CI (99.9%): [2.126, 4.386] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.438 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.005 ms/op
Iteration   1: 3.629 ±(99.9%) 0.013 ms/op
Iteration   2: 3.858 ±(99.9%) 0.002 ms/op
Iteration   3: 3.854 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.781 ±(99.9%) 2.389 ms/op [Average]
  (min, avg, max) = (3.629, 3.781, 3.858), stdev = 0.131
  CI (99.9%): [1.392, 6.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.024 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.804 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 22.875 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.576 ms/op
                 createUser·p0.999:  14.003 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  13.115 ms/op
                 createUser·p0.9999: 21.367 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295850
  mean =      3.243 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14774 
    [ 2.500,  5.000) = 275025 
    [ 5.000,  7.500) = 5268 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     19.404 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.422 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.160 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.843 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 28.463 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 3.102 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  12.317 ms/op
                 existUser·p0.9999: 24.620 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308266
  mean =      3.116 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21585 
    [ 2.500,  5.000) = 281814 
    [ 5.000,  7.500) = 4048 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.662 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
Iteration   1: 3.383 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.088 ms/op
                 getUser·p0.999:  19.006 ms/op
                 getUser·p0.9999: 25.413 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 3.291 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.274 ms/op
                 getUser·p0.999:  13.333 ms/op
                 getUser·p0.9999: 35.736 ms/op
                 getUser·p1.00:   37.421 ms/op

Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  11.188 ms/op
                 getUser·p0.9999: 27.132 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289742
  mean =      3.309 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10772 
    [ 2.500,  5.000) = 271110 
    [ 5.000,  7.500) = 6465 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     17.556 ms/op
     p(99.9900) =     34.408 ms/op
     p(99.9990) =     36.838 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.259 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.014 ms/op
Iteration   1: 3.852 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 21.345 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.749 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.718 ms/op
                 listUser·p0.999:  15.705 ms/op
                 listUser·p0.9999: 18.510 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.790 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.091 ms/op
                 listUser·p0.9999: 20.727 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252801
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1101 
    [ 2.500,  5.000) = 242756 
    [ 5.000,  7.500) = 7063 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.061 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     21.970 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.620 ± 2.926  ops/ms
ClientPb.existUser                       thrpt       3  10.375 ± 3.687  ops/ms
ClientPb.getUser                         thrpt       3  10.171 ± 1.113  ops/ms
ClientPb.listUser                        thrpt       3   8.401 ± 6.736  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 0.918   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 0.699   ms/op
ClientPb.getUser                          avgt       3   3.256 ± 1.130   ms/op
ClientPb.listUser                         avgt       3   3.781 ± 2.389   ms/op
ClientPb.createUser                     sample  295850   3.243 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.122           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.404           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.592           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  308266   3.116 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.961           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  289742   3.309 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.877           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.556           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.408           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.421           ms/op
ClientPb.listUser                       sample  252801   3.797 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.998           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.061           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
