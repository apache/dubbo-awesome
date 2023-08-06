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
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 4.072 ops/ms
# Warmup Iteration   3: 6.482 ops/ms
Iteration   1: 6.350 ops/ms
Iteration   2: 6.605 ops/ms
Iteration   3: 7.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.689 ±(99.9%) 7.091 ops/ms [Average]
  (min, avg, max) = (6.350, 6.689, 7.113), stdev = 0.389
  CI (99.9%): [≈ 0, 13.781] (assumes normal distribution)


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
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 6.924 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.576 ops/ms
Iteration   2: 7.523 ops/ms
Iteration   3: 7.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.573 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (7.523, 7.573, 7.619), stdev = 0.048
  CI (99.9%): [6.696, 8.450] (assumes normal distribution)


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
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 7.074 ops/ms
Iteration   1: 7.127 ops/ms
Iteration   2: 7.365 ops/ms
Iteration   3: 7.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.294 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (7.127, 7.294, 7.390), stdev = 0.145
  CI (99.9%): [4.654, 9.934] (assumes normal distribution)


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
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 5.318 ops/ms
# Warmup Iteration   3: 5.939 ops/ms
Iteration   1: 5.698 ops/ms
Iteration   2: 5.874 ops/ms
Iteration   3: 6.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.955 ±(99.9%) 5.576 ops/ms [Average]
  (min, avg, max) = (5.698, 5.955, 6.293), stdev = 0.306
  CI (99.9%): [0.379, 11.531] (assumes normal distribution)


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
# Warmup Iteration   1: 13.647 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.012 ms/op
Iteration   1: 4.561 ±(99.9%) 0.012 ms/op
Iteration   2: 4.537 ±(99.9%) 0.013 ms/op
Iteration   3: 4.574 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.557 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (4.537, 4.557, 4.574), stdev = 0.019
  CI (99.9%): [4.218, 4.897] (assumes normal distribution)


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
# Warmup Iteration   1: 10.160 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.008 ms/op
Iteration   1: 4.169 ±(99.9%) 0.013 ms/op
Iteration   2: 4.220 ±(99.9%) 0.008 ms/op
Iteration   3: 4.235 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.208 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (4.169, 4.208, 4.235), stdev = 0.034
  CI (99.9%): [3.579, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 10.811 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.547 ±(99.9%) 0.007 ms/op
Iteration   1: 4.660 ±(99.9%) 0.010 ms/op
Iteration   2: 4.444 ±(99.9%) 0.008 ms/op
Iteration   3: 4.563 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.556 ±(99.9%) 1.968 ms/op [Average]
  (min, avg, max) = (4.444, 4.556, 4.660), stdev = 0.108
  CI (99.9%): [2.588, 6.523] (assumes normal distribution)


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
# Warmup Iteration   1: 13.849 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.603 ±(99.9%) 0.014 ms/op
Iteration   1: 5.597 ±(99.9%) 0.012 ms/op
Iteration   2: 5.692 ±(99.9%) 0.016 ms/op
Iteration   3: 5.688 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.659 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (5.597, 5.659, 5.692), stdev = 0.054
  CI (99.9%): [4.682, 6.636] (assumes normal distribution)


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
# Warmup Iteration   1: 14.280 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 5.677 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.378 ±(99.9%) 0.022 ms/op
Iteration   1: 4.863 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   10.104 ms/op
                 createUser·p0.999:  18.225 ms/op
                 createUser·p0.9999: 26.294 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 4.728 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.972 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  23.233 ms/op
                 createUser·p0.9999: 29.728 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 5.231 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.281 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.291 ms/op
                 createUser·p0.99:   10.018 ms/op
                 createUser·p0.999:  26.999 ms/op
                 createUser·p0.9999: 30.010 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 194496
  mean =      4.931 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 127872 
    [ 5.000,  7.500) = 59508 
    [ 7.500, 10.000) = 5196 
    [10.000, 12.500) = 1230 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     28.919 ms/op
     p(99.9990) =     30.426 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 12.782 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.016 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.017 ms/op
Iteration   1: 4.721 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.089 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   5.680 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  18.579 ms/op
                 existUser·p0.9999: 23.141 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 4.740 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  19.426 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 4.654 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.890 ms/op
                 existUser·p0.95:   6.660 ms/op
                 existUser·p0.99:   9.290 ms/op
                 existUser·p0.999:  19.014 ms/op
                 existUser·p0.9999: 25.674 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203940
  mean =      4.705 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 152637 
    [ 5.000,  7.500) = 45042 
    [ 7.500, 10.000) = 4147 
    [10.000, 12.500) = 1332 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     26.212 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 13.241 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.016 ms/op
Iteration   1: 4.876 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   7.053 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  23.916 ms/op
                 getUser·p0.9999: 32.408 ms/op
                 getUser·p1.00:   43.450 ms/op

Iteration   2: 4.621 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  14.621 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 5.032 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   5.841 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  25.127 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198474
  mean =      4.837 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 139579 
    [ 5.000, 10.000) = 57349 
    [10.000, 15.000) = 1200 
    [15.000, 20.000) = 88 
    [20.000, 25.000) = 146 
    [25.000, 30.000) = 82 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     31.364 ms/op
     p(99.9990) =     33.125 ms/op
     p(99.9999) =     43.450 ms/op
    p(100.0000) =     43.450 ms/op


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
# Warmup Iteration   1: 15.966 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.139 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.502 ±(99.9%) 0.019 ms/op
Iteration   1: 5.342 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  20.187 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 5.123 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.822 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   9.976 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 22.677 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 5.202 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  21.054 ms/op
                 listUser·p0.9999: 27.094 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 183818
  mean =      5.221 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 97744 
    [ 5.000,  7.500) = 78884 
    [ 7.500, 10.000) = 5146 
    [10.000, 12.500) = 1292 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 190 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     20.519 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.137 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.689 ± 7.091  ops/ms
ClientPb.existUser                       thrpt       3   7.573 ± 0.877  ops/ms
ClientPb.getUser                         thrpt       3   7.294 ± 2.640  ops/ms
ClientPb.listUser                        thrpt       3   5.955 ± 5.576  ops/ms
ClientPb.createUser                       avgt       3   4.557 ± 0.340   ms/op
ClientPb.existUser                        avgt       3   4.208 ± 0.629   ms/op
ClientPb.getUser                          avgt       3   4.556 ± 1.968   ms/op
ClientPb.listUser                         avgt       3   5.659 ± 0.977   ms/op
ClientPb.createUser                     sample  194496   4.931 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.065           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.980           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.560           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.919           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  203940   4.705 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.619           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.929           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.137           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.166           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.247           ms/op
ClientPb.getUser                        sample  198474   4.837 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.364           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.450           ms/op
ClientPb.listUser                       sample  183818   5.221 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.330           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
