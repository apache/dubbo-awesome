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
# Warmup Iteration   1: 1.713 ops/ms
# Warmup Iteration   2: 3.996 ops/ms
# Warmup Iteration   3: 7.197 ops/ms
Iteration   1: 7.354 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.884 ±(99.9%) 8.396 ops/ms [Average]
  (min, avg, max) = (7.354, 7.884, 8.188), stdev = 0.460
  CI (99.9%): [≈ 0, 16.279] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.415 ops/ms
# Warmup Iteration   2: 6.814 ops/ms
# Warmup Iteration   3: 8.127 ops/ms
Iteration   1: 8.611 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.516 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (8.431, 8.516, 8.611), stdev = 0.090
  CI (99.9%): [6.867, 10.166] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 6.717 ops/ms
# Warmup Iteration   3: 7.663 ops/ms
Iteration   1: 8.082 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.200 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (8.082, 8.200, 8.274), stdev = 0.103
  CI (99.9%): [6.321, 10.078] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.114 ops/ms
# Warmup Iteration   2: 5.551 ops/ms
# Warmup Iteration   3: 6.641 ops/ms
Iteration   1: 6.581 ops/ms
Iteration   2: 6.731 ops/ms
Iteration   3: 7.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.845 ±(99.9%) 6.137 ops/ms [Average]
  (min, avg, max) = (6.581, 6.845, 7.224), stdev = 0.336
  CI (99.9%): [0.708, 12.982] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.632 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.009 ms/op
Iteration   1: 4.031 ±(99.9%) 0.010 ms/op
Iteration   2: 3.930 ±(99.9%) 0.005 ms/op
Iteration   3: 4.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.015 ±(99.9%) 1.417 ms/op [Average]
  (min, avg, max) = (3.930, 4.015, 4.083), stdev = 0.078
  CI (99.9%): [2.597, 5.432] (assumes normal distribution)


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
# Warmup Iteration   1: 13.251 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.009 ms/op
Iteration   1: 3.720 ±(99.9%) 0.006 ms/op
Iteration   2: 3.988 ±(99.9%) 0.007 ms/op
Iteration   3: 3.798 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.835 ±(99.9%) 2.511 ms/op [Average]
  (min, avg, max) = (3.720, 3.835, 3.988), stdev = 0.138
  CI (99.9%): [1.324, 6.346] (assumes normal distribution)


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
# Warmup Iteration   1: 14.234 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.306 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.008 ms/op
Iteration   1: 4.133 ±(99.9%) 0.004 ms/op
Iteration   2: 4.243 ±(99.9%) 0.003 ms/op
Iteration   3: 4.215 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.197 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (4.133, 4.197, 4.243), stdev = 0.057
  CI (99.9%): [3.158, 5.236] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.015 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.559 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.831 ±(99.9%) 0.010 ms/op
Iteration   1: 4.827 ±(99.9%) 0.009 ms/op
Iteration   2: 4.683 ±(99.9%) 0.010 ms/op
Iteration   3: 4.794 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.768 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (4.683, 4.768, 4.827), stdev = 0.075
  CI (99.9%): [3.397, 6.139] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.406 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 5.324 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
Iteration   1: 4.028 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   8.685 ms/op
                 createUser·p0.999:  23.396 ms/op
                 createUser·p0.9999: 25.864 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 3.999 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.748 ms/op
                 createUser·p0.999:  13.926 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 4.053 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   7.046 ms/op
                 createUser·p0.999:  30.835 ms/op
                 createUser·p0.9999: 34.341 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238395
  mean =      4.027 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 406 
    [ 2.500,  5.000) = 225195 
    [ 5.000,  7.500) = 9938 
    [ 7.500, 10.000) = 1980 
    [10.000, 12.500) = 514 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     33.111 ms/op
     p(99.9990) =     35.238 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.605 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.015 ms/op
Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  11.707 ms/op
                 existUser·p0.9999: 24.334 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.848 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   7.822 ms/op
                 existUser·p0.999:  23.186 ms/op
                 existUser·p0.9999: 25.604 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.964 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   8.947 ms/op
                 existUser·p0.999:  18.383 ms/op
                 existUser·p0.9999: 27.129 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247729
  mean =      3.876 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 234811 
    [ 5.000,  7.500) = 9765 
    [ 7.500, 10.000) = 1758 
    [10.000, 12.500) = 661 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     26.189 ms/op
     p(99.9990) =     27.839 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.233 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.016 ms/op
Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  20.408 ms/op
                 getUser·p0.9999: 32.594 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   2: 4.160 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.989 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  11.752 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  14.318 ms/op
                 getUser·p0.9999: 27.469 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230620
  mean =      4.159 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 211245 
    [ 5.000,  7.500) = 16181 
    [ 7.500, 10.000) = 2215 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     32.176 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 16.012 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.540 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.893 ±(99.9%) 0.019 ms/op
Iteration   1: 4.801 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  26.759 ms/op
                 listUser·p0.9999: 29.633 ms/op
                 listUser·p1.00:   30.343 ms/op

Iteration   2: 4.865 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  19.715 ms/op
                 listUser·p0.9999: 23.531 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 4.752 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199806
  mean =      4.806 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 162669 
    [ 5.000,  7.500) = 30336 
    [ 7.500, 10.000) = 4977 
    [10.000, 12.500) = 1079 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     21.312 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.884 ± 8.396  ops/ms
ClientPb.existUser                       thrpt       3   8.516 ± 1.649  ops/ms
ClientPb.getUser                         thrpt       3   8.200 ± 1.878  ops/ms
ClientPb.listUser                        thrpt       3   6.845 ± 6.137  ops/ms
ClientPb.createUser                       avgt       3   4.015 ± 1.417   ms/op
ClientPb.existUser                        avgt       3   3.835 ± 2.511   ms/op
ClientPb.getUser                          avgt       3   4.197 ± 1.039   ms/op
ClientPb.listUser                         avgt       3   4.768 ± 1.371   ms/op
ClientPb.createUser                     sample  238395   4.027 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.386           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.840           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.396           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.111           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  247729   3.876 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.815           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.285           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.886           ms/op
ClientPb.getUser                        sample  230620   4.159 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.552           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.071           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  199806   4.806 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.312           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.032           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.343           ms/op
