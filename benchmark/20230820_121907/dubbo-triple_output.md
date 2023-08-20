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
# Warmup Iteration   1: 1.153 ops/ms
# Warmup Iteration   2: 2.686 ops/ms
# Warmup Iteration   3: 5.683 ops/ms
Iteration   1: 6.315 ops/ms
Iteration   2: 6.515 ops/ms
Iteration   3: 6.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.444 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (6.315, 6.444, 6.515), stdev = 0.112
  CI (99.9%): [4.401, 8.486] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.898 ops/ms
# Warmup Iteration   2: 5.669 ops/ms
# Warmup Iteration   3: 6.607 ops/ms
Iteration   1: 6.733 ops/ms
Iteration   2: 6.471 ops/ms
Iteration   3: 6.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.710 ±(99.9%) 4.158 ops/ms [Average]
  (min, avg, max) = (6.471, 6.710, 6.925), stdev = 0.228
  CI (99.9%): [2.552, 10.867] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.900 ops/ms
# Warmup Iteration   2: 5.503 ops/ms
# Warmup Iteration   3: 6.309 ops/ms
Iteration   1: 5.977 ops/ms
Iteration   2: 6.080 ops/ms
Iteration   3: 5.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.018 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (5.977, 6.018, 6.080), stdev = 0.055
  CI (99.9%): [5.018, 7.018] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.692 ops/ms
# Warmup Iteration   2: 4.527 ops/ms
# Warmup Iteration   3: 5.209 ops/ms
Iteration   1: 5.221 ops/ms
Iteration   2: 5.464 ops/ms
Iteration   3: 5.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.328 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (5.221, 5.328, 5.464), stdev = 0.124
  CI (99.9%): [3.064, 7.593] (assumes normal distribution)


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
# Warmup Iteration   1: 18.134 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.242 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.183 ±(99.9%) 0.013 ms/op
Iteration   1: 5.462 ±(99.9%) 0.010 ms/op
Iteration   2: 5.099 ±(99.9%) 0.012 ms/op
Iteration   3: 5.152 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.238 ±(99.9%) 3.580 ms/op [Average]
  (min, avg, max) = (5.099, 5.238, 5.462), stdev = 0.196
  CI (99.9%): [1.658, 8.817] (assumes normal distribution)


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
# Warmup Iteration   1: 14.749 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.591 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.083 ±(99.9%) 0.009 ms/op
Iteration   1: 4.959 ±(99.9%) 0.007 ms/op
Iteration   2: 4.870 ±(99.9%) 0.010 ms/op
Iteration   3: 5.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.958 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (4.870, 4.958, 5.045), stdev = 0.087
  CI (99.9%): [3.362, 6.553] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.526 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.820 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.121 ±(99.9%) 0.012 ms/op
Iteration   1: 5.006 ±(99.9%) 0.016 ms/op
Iteration   2: 5.307 ±(99.9%) 0.010 ms/op
Iteration   3: 5.070 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.128 ±(99.9%) 2.896 ms/op [Average]
  (min, avg, max) = (5.006, 5.128, 5.307), stdev = 0.159
  CI (99.9%): [2.232, 8.023] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.148 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.575 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.196 ±(99.9%) 0.018 ms/op
Iteration   1: 6.002 ±(99.9%) 0.018 ms/op
Iteration   2: 5.748 ±(99.9%) 0.012 ms/op
Iteration   3: 5.688 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.813 ±(99.9%) 3.048 ms/op [Average]
  (min, avg, max) = (5.688, 5.813, 6.002), stdev = 0.167
  CI (99.9%): [2.765, 8.861] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.122 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.615 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.409 ±(99.9%) 0.023 ms/op
Iteration   1: 5.165 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.083 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.389 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  23.544 ms/op
                 createUser·p0.9999: 28.601 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   2: 4.981 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.064 ms/op
                 createUser·p0.50:   4.784 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   6.783 ms/op
                 createUser·p0.99:   9.037 ms/op
                 createUser·p0.999:  20.934 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   3: 5.085 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.792 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  26.154 ms/op
                 createUser·p0.9999: 32.565 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189195
  mean =      5.076 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 113349 
    [ 5.000,  7.500) = 68321 
    [ 7.500, 10.000) = 5668 
    [10.000, 12.500) = 1331 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     31.493 ms/op
     p(99.9990) =     32.917 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.712 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.610 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.949 ±(99.9%) 0.018 ms/op
Iteration   1: 4.674 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.191 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  12.984 ms/op
                 existUser·p0.9999: 27.989 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   2: 4.879 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.644 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  16.146 ms/op
                 existUser·p0.9999: 37.581 ms/op
                 existUser·p1.00:   39.584 ms/op

Iteration   3: 4.922 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   11.108 ms/op
                 existUser·p0.999:  18.248 ms/op
                 existUser·p0.9999: 38.306 ms/op
                 existUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 199147
  mean =      4.822 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 141651 
    [ 5.000,  7.500) = 51428 
    [ 7.500, 10.000) = 4311 
    [10.000, 12.500) = 1137 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     17.479 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     38.609 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.375 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.019 ms/op
Iteration   1: 5.255 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   11.878 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 29.647 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 5.294 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.496 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   11.438 ms/op
                 getUser·p0.999:  25.070 ms/op
                 getUser·p0.9999: 32.832 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 5.402 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   7.274 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  24.660 ms/op
                 getUser·p0.9999: 30.941 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180395
  mean =      5.316 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 94778 
    [ 5.000,  7.500) = 73669 
    [ 7.500, 10.000) = 8922 
    [10.000, 12.500) = 1834 
    [12.500, 15.000) = 788 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     24.288 ms/op
     p(99.9900) =     30.626 ms/op
     p(99.9990) =     33.238 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 15.998 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.351 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.887 ±(99.9%) 0.023 ms/op
Iteration   1: 5.439 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.076 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  24.972 ms/op
                 listUser·p0.9999: 30.379 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 6.077 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  24.732 ms/op
                 listUser·p0.9999: 47.135 ms/op
                 listUser·p1.00:   48.824 ms/op

Iteration   3: 6.149 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.729 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 25.827 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163403
  mean =      5.871 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 34595 
    [ 5.000, 10.000) = 125818 
    [10.000, 15.000) = 2535 
    [15.000, 20.000) = 197 
    [20.000, 25.000) = 140 
    [25.000, 30.000) = 75 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.458 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     24.222 ms/op
     p(99.9900) =     45.198 ms/op
     p(99.9990) =     48.367 ms/op
     p(99.9999) =     48.824 ms/op
    p(100.0000) =     48.824 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.444 ± 2.043  ops/ms
ClientPb.existUser                       thrpt       3   6.710 ± 4.158  ops/ms
ClientPb.getUser                         thrpt       3   6.018 ± 1.000  ops/ms
ClientPb.listUser                        thrpt       3   5.328 ± 2.264  ops/ms
ClientPb.createUser                       avgt       3   5.238 ± 3.580   ms/op
ClientPb.existUser                        avgt       3   4.958 ± 1.595   ms/op
ClientPb.getUser                          avgt       3   5.128 ± 2.896   ms/op
ClientPb.listUser                         avgt       3   5.813 ± 3.048   ms/op
ClientPb.createUser                     sample  189195   5.076 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.064           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.510           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.493           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  199147   4.822 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.468           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.997           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.709           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.552           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.479           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.584           ms/op
ClientPb.getUser                        sample  180395   5.316 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.485           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.288           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  163403   5.871 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.458           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.436           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.222           ms/op
ClientPb.listUser:listUser·p0.9999      sample          45.198           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.824           ms/op
