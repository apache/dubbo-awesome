# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.065 ops/ms
# Warmup Iteration   2: 2.490 ops/ms
# Warmup Iteration   3: 5.531 ops/ms
Iteration   1: 6.092 ops/ms
Iteration   2: 5.917 ops/ms
Iteration   3: 6.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.114 ±(99.9%) 3.832 ops/ms [Average]
  (min, avg, max) = (5.917, 6.114, 6.335), stdev = 0.210
  CI (99.9%): [2.283, 9.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.468 ops/ms
# Warmup Iteration   2: 4.582 ops/ms
# Warmup Iteration   3: 6.299 ops/ms
Iteration   1: 6.620 ops/ms
Iteration   2: 6.650 ops/ms
Iteration   3: 6.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.625 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (6.605, 6.625, 6.650), stdev = 0.023
  CI (99.9%): [6.203, 7.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.439 ops/ms
# Warmup Iteration   2: 4.450 ops/ms
# Warmup Iteration   3: 6.048 ops/ms
Iteration   1: 5.643 ops/ms
Iteration   2: 6.121 ops/ms
Iteration   3: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.962 ±(99.9%) 5.031 ops/ms [Average]
  (min, avg, max) = (5.643, 5.962, 6.121), stdev = 0.276
  CI (99.9%): [0.931, 10.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.462 ops/ms
# Warmup Iteration   2: 3.882 ops/ms
# Warmup Iteration   3: 4.888 ops/ms
Iteration   1: 5.165 ops/ms
Iteration   2: 5.250 ops/ms
Iteration   3: 5.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.217 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (5.165, 5.217, 5.250), stdev = 0.046
  CI (99.9%): [4.380, 6.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.196 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.496 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.671 ±(99.9%) 0.010 ms/op
Iteration   1: 5.623 ±(99.9%) 0.011 ms/op
Iteration   2: 5.516 ±(99.9%) 0.013 ms/op
Iteration   3: 5.244 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.461 ±(99.9%) 3.565 ms/op [Average]
  (min, avg, max) = (5.244, 5.461, 5.623), stdev = 0.195
  CI (99.9%): [1.895, 9.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.642 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.256 ±(99.9%) 0.009 ms/op
Iteration   1: 4.967 ±(99.9%) 0.014 ms/op
Iteration   2: 4.861 ±(99.9%) 0.011 ms/op
Iteration   3: 5.013 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.947 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (4.861, 4.947, 5.013), stdev = 0.078
  CI (99.9%): [3.526, 6.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.546 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.481 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.007 ms/op
Iteration   1: 5.460 ±(99.9%) 0.006 ms/op
Iteration   2: 5.420 ±(99.9%) 0.011 ms/op
Iteration   3: 5.288 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.389 ±(99.9%) 1.644 ms/op [Average]
  (min, avg, max) = (5.288, 5.389, 5.460), stdev = 0.090
  CI (99.9%): [3.745, 7.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.089 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.208 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.966 ±(99.9%) 0.013 ms/op
Iteration   1: 6.020 ±(99.9%) 0.012 ms/op
Iteration   2: 5.918 ±(99.9%) 0.014 ms/op
Iteration   3: 6.053 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.997 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (5.918, 5.997, 6.053), stdev = 0.070
  CI (99.9%): [4.712, 7.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.569 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 6.863 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.027 ms/op
Iteration   1: 5.326 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.105 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  19.200 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 5.156 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.261 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  20.066 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 5.260 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.086 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  22.015 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182868
  mean =      5.246 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 90326 
    [ 5.000,  7.500) = 85758 
    [ 7.500, 10.000) = 5320 
    [10.000, 12.500) = 827 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     20.329 ms/op
     p(99.9900) =     25.550 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.800 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.233 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.187 ±(99.9%) 0.022 ms/op
Iteration   1: 4.980 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   10.013 ms/op
                 existUser·p0.999:  15.146 ms/op
                 existUser·p0.9999: 28.088 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 5.099 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   6.947 ms/op
                 existUser·p0.99:   9.693 ms/op
                 existUser·p0.999:  24.881 ms/op
                 existUser·p0.9999: 29.688 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   3: 4.956 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   5.956 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  20.938 ms/op
                 existUser·p0.9999: 29.739 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191492
  mean =      5.011 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 126519 
    [ 5.000,  7.500) = 57942 
    [ 7.500, 10.000) = 5163 
    [10.000, 12.500) = 1184 
    [12.500, 15.000) = 456 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.087 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.167 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.115 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.347 ±(99.9%) 0.019 ms/op
Iteration   1: 5.293 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   8.184 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  23.464 ms/op
                 getUser·p0.9999: 28.402 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   2: 5.283 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   12.381 ms/op
                 getUser·p0.999:  24.496 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   3: 5.147 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.437 ms/op
                 getUser·p0.999:  25.535 ms/op
                 getUser·p0.9999: 35.556 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183225
  mean =      5.240 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 105389 
    [ 5.000,  7.500) = 66447 
    [ 7.500, 10.000) = 8171 
    [10.000, 12.500) = 1840 
    [12.500, 15.000) = 724 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     24.324 ms/op
     p(99.9900) =     32.899 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.117 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.441 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.023 ms/op
Iteration   1: 6.021 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  26.558 ms/op
                 listUser·p0.9999: 29.865 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 5.695 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  26.631 ms/op
                 listUser·p0.9999: 30.225 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   3: 5.854 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.538 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.752 ms/op
                 listUser·p0.999:  19.671 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163989
  mean =      5.854 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 16677 
    [ 5.000,  7.500) = 137359 
    [ 7.500, 10.000) = 7075 
    [10.000, 12.500) = 1804 
    [12.500, 15.000) = 570 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     29.806 ms/op
     p(99.9990) =     30.559 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.114 ± 3.832  ops/ms
ClientPb.existUser                       thrpt       3   6.625 ± 0.422  ops/ms
ClientPb.getUser                         thrpt       3   5.962 ± 5.031  ops/ms
ClientPb.listUser                        thrpt       3   5.217 ± 0.837  ops/ms
ClientPb.createUser                       avgt       3   5.461 ± 3.565   ms/op
ClientPb.existUser                        avgt       3   4.947 ± 1.421   ms/op
ClientPb.getUser                          avgt       3   5.389 ± 1.644   ms/op
ClientPb.listUser                         avgt       3   5.997 ± 1.285   ms/op
ClientPb.createUser                     sample  182868   5.246 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.552           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.329           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  191492   5.011 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.195           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.896           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.426           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  183225   5.240 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.452           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.518           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.324           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.899           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.635           ms/op
ClientPb.listUser                       sample  163989   5.854 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.043           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.690           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.806           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.769           ms/op
