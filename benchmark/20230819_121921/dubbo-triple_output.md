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
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 3.753 ops/ms
# Warmup Iteration   3: 7.215 ops/ms
Iteration   1: 7.485 ops/ms
Iteration   2: 7.989 ops/ms
Iteration   3: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.798 ±(99.9%) 4.992 ops/ms [Average]
  (min, avg, max) = (7.485, 7.798, 7.989), stdev = 0.274
  CI (99.9%): [2.807, 12.790] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.353 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.263 ±(99.9%) 3.997 ops/ms [Average]
  (min, avg, max) = (8.013, 8.263, 8.423), stdev = 0.219
  CI (99.9%): [4.266, 12.260] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 6.836 ops/ms
# Warmup Iteration   3: 7.146 ops/ms
Iteration   1: 7.680 ops/ms
Iteration   2: 7.666 ops/ms
Iteration   3: 7.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.725 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (7.666, 7.725, 7.828), stdev = 0.090
  CI (99.9%): [6.091, 9.358] (assumes normal distribution)


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
# Warmup Iteration   1: 2.180 ops/ms
# Warmup Iteration   2: 5.696 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 6.793 ops/ms
Iteration   2: 6.705 ops/ms
Iteration   3: 6.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.668 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (6.507, 6.668, 6.793), stdev = 0.146
  CI (99.9%): [3.998, 9.338] (assumes normal distribution)


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
# Warmup Iteration   1: 15.165 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.832 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.474 ±(99.9%) 0.005 ms/op
Iteration   1: 4.267 ±(99.9%) 0.008 ms/op
Iteration   2: 4.099 ±(99.9%) 0.006 ms/op
Iteration   3: 4.061 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.142 ±(99.9%) 2.001 ms/op [Average]
  (min, avg, max) = (4.061, 4.142, 4.267), stdev = 0.110
  CI (99.9%): [2.141, 6.144] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.668 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.005 ms/op
Iteration   1: 3.933 ±(99.9%) 0.005 ms/op
Iteration   2: 3.874 ±(99.9%) 0.007 ms/op
Iteration   3: 3.823 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.877 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.823, 3.877, 3.933), stdev = 0.055
  CI (99.9%): [2.873, 4.881] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.774 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.900 ±(99.9%) 0.005 ms/op
Iteration   2: 4.025 ±(99.9%) 0.004 ms/op
Iteration   3: 3.934 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.953 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.900, 3.953, 4.025), stdev = 0.064
  CI (99.9%): [2.777, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 14.474 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.719 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.733 ±(99.9%) 0.010 ms/op
Iteration   1: 4.801 ±(99.9%) 0.011 ms/op
Iteration   2: 4.644 ±(99.9%) 0.012 ms/op
Iteration   3: 4.682 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.709 ±(99.9%) 1.492 ms/op [Average]
  (min, avg, max) = (4.644, 4.709, 4.801), stdev = 0.082
  CI (99.9%): [3.217, 6.201] (assumes normal distribution)


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
# Warmup Iteration   1: 12.187 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.892 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.022 ms/op
Iteration   1: 4.105 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  24.510 ms/op
                 createUser·p0.9999: 30.835 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.798 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  12.670 ms/op
                 createUser·p0.9999: 29.032 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 3.970 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.815 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.968 ms/op
                 createUser·p0.999:  28.061 ms/op
                 createUser·p0.9999: 31.030 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237850
  mean =      4.034 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 369 
    [ 2.500,  5.000) = 223272 
    [ 5.000,  7.500) = 11147 
    [ 7.500, 10.000) = 2234 
    [10.000, 12.500) = 513 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     30.776 ms/op
     p(99.9990) =     31.760 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 11.696 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.013 ms/op
Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  12.590 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 27.443 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.982 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   8.331 ms/op
                 existUser·p0.999:  26.286 ms/op
                 existUser·p0.9999: 29.981 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243205
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 352 
    [ 2.500,  5.000) = 230372 
    [ 5.000,  7.500) = 9038 
    [ 7.500, 10.000) = 2463 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     29.317 ms/op
     p(99.9990) =     30.636 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 11.798 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.015 ms/op
Iteration   1: 4.054 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 28.519 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 3.934 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  25.016 ms/op
                 getUser·p0.9999: 29.417 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 4.154 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   8.966 ms/op
                 getUser·p0.999:  19.301 ms/op
                 getUser·p0.9999: 36.438 ms/op
                 getUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237106
  mean =      4.045 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 221923 
    [ 5.000,  7.500) = 10982 
    [ 7.500, 10.000) = 2838 
    [10.000, 12.500) = 767 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     36.996 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 13.076 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.688 ±(99.9%) 0.017 ms/op
Iteration   1: 4.701 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  26.378 ms/op
                 listUser·p0.9999: 31.477 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   2: 4.798 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.633 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.647 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203632
  mean =      4.710 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 177027 
    [ 5.000,  7.500) = 20379 
    [ 7.500, 10.000) = 4879 
    [10.000, 12.500) = 602 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     30.298 ms/op
     p(99.9990) =     32.658 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.798 ± 4.992  ops/ms
ClientPb.existUser                       thrpt       3   8.263 ± 3.997  ops/ms
ClientPb.getUser                         thrpt       3   7.725 ± 1.633  ops/ms
ClientPb.listUser                        thrpt       3   6.668 ± 2.670  ops/ms
ClientPb.createUser                       avgt       3   4.142 ± 2.001   ms/op
ClientPb.existUser                        avgt       3   3.877 ± 1.004   ms/op
ClientPb.getUser                          avgt       3   3.953 ± 1.176   ms/op
ClientPb.listUser                         avgt       3   4.709 ± 1.492   ms/op
ClientPb.createUser                     sample  237850   4.034 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.510           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.776           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.818           ms/op
ClientPb.existUser                      sample  243205   3.949 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.646           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.317           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.900           ms/op
ClientPb.getUser                        sample  237106   4.045 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.988           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.618           ms/op
ClientPb.listUser                       sample  203632   4.710 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.589           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.907           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.298           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834           ms/op
