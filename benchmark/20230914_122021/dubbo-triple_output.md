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
# Warmup Iteration   1: 0.785 ops/ms
# Warmup Iteration   2: 1.632 ops/ms
# Warmup Iteration   3: 3.036 ops/ms
Iteration   1: 4.427 ops/ms
Iteration   2: 4.704 ops/ms
Iteration   3: 4.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.677 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (4.427, 4.677, 4.899), stdev = 0.237
  CI (99.9%): [0.356, 8.997] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.200 ops/ms
# Warmup Iteration   2: 3.741 ops/ms
# Warmup Iteration   3: 4.983 ops/ms
Iteration   1: 4.836 ops/ms
Iteration   2: 4.932 ops/ms
Iteration   3: 5.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.953 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (4.836, 4.953, 5.091), stdev = 0.129
  CI (99.9%): [2.604, 7.302] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.260 ops/ms
# Warmup Iteration   2: 3.060 ops/ms
# Warmup Iteration   3: 4.577 ops/ms
Iteration   1: 4.591 ops/ms
Iteration   2: 4.678 ops/ms
Iteration   3: 4.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.677 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (4.591, 4.677, 4.761), stdev = 0.085
  CI (99.9%): [3.124, 6.229] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.146 ops/ms
# Warmup Iteration   2: 2.634 ops/ms
# Warmup Iteration   3: 3.907 ops/ms
Iteration   1: 4.126 ops/ms
Iteration   2: 4.144 ops/ms
Iteration   3: 4.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.162 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (4.126, 4.162, 4.217), stdev = 0.048
  CI (99.9%): [3.285, 5.040] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 25.253 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 10.332 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.761 ±(99.9%) 0.015 ms/op
Iteration   1: 6.865 ±(99.9%) 0.013 ms/op
Iteration   2: 6.614 ±(99.9%) 0.008 ms/op
Iteration   3: 6.452 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.644 ±(99.9%) 3.795 ms/op [Average]
  (min, avg, max) = (6.452, 6.644, 6.865), stdev = 0.208
  CI (99.9%): [2.849, 10.438] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 21.427 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 7.983 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.141 ±(99.9%) 0.011 ms/op
Iteration   1: 6.279 ±(99.9%) 0.011 ms/op
Iteration   2: 6.247 ±(99.9%) 0.010 ms/op
Iteration   3: 6.130 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.219 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (6.130, 6.219, 6.279), stdev = 0.078
  CI (99.9%): [4.788, 7.650] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 22.380 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 8.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.513 ±(99.9%) 0.014 ms/op
Iteration   1: 6.459 ±(99.9%) 0.011 ms/op
Iteration   2: 6.347 ±(99.9%) 0.010 ms/op
Iteration   3: 6.224 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.343 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (6.224, 6.343, 6.459), stdev = 0.118
  CI (99.9%): [4.193, 8.494] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 26.281 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 12.098 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 8.485 ±(99.9%) 0.018 ms/op
Iteration   1: 7.715 ±(99.9%) 0.020 ms/op
Iteration   2: 7.670 ±(99.9%) 0.012 ms/op
Iteration   3: 7.687 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.691 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (7.670, 7.691, 7.715), stdev = 0.023
  CI (99.9%): [7.276, 8.105] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 21.658 ±(99.9%) 0.372 ms/op
# Warmup Iteration   2: 8.024 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.095 ±(99.9%) 0.040 ms/op
Iteration   1: 6.481 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   2.712 ms/op
                 createUser·p0.50:   5.825 ms/op
                 createUser·p0.90:   8.929 ms/op
                 createUser·p0.95:   10.453 ms/op
                 createUser·p0.99:   15.264 ms/op
                 createUser·p0.999:  27.613 ms/op
                 createUser·p0.9999: 31.623 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   2: 6.340 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   5.792 ms/op
                 createUser·p0.90:   8.348 ms/op
                 createUser·p0.95:   9.748 ms/op
                 createUser·p0.99:   14.205 ms/op
                 createUser·p0.999:  29.365 ms/op
                 createUser·p0.9999: 31.814 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   3: 6.563 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   5.997 ms/op
                 createUser·p0.90:   8.913 ms/op
                 createUser·p0.95:   10.322 ms/op
                 createUser·p0.99:   13.271 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 37.273 ms/op
                 createUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 148483
  mean =      6.460 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 18366 
    [ 5.000, 10.000) = 121998 
    [10.000, 15.000) = 7038 
    [15.000, 20.000) = 863 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      5.874 ms/op
     p(90.0000) =      8.700 ms/op
     p(95.0000) =     10.174 ms/op
     p(99.0000) =     14.303 ms/op
     p(99.9000) =     27.890 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     40.680 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 21.904 ±(99.9%) 0.532 ms/op
# Warmup Iteration   2: 9.915 ±(99.9%) 0.097 ms/op
# Warmup Iteration   3: 6.710 ±(99.9%) 0.040 ms/op
Iteration   1: 6.419 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.531 ms/op
                 existUser·p0.50:   5.800 ms/op
                 existUser·p0.90:   9.060 ms/op
                 existUser·p0.95:   10.502 ms/op
                 existUser·p0.99:   13.631 ms/op
                 existUser·p0.999:  20.454 ms/op
                 existUser·p0.9999: 29.852 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   2: 6.217 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.572 ms/op
                 existUser·p0.50:   5.669 ms/op
                 existUser·p0.90:   8.380 ms/op
                 existUser·p0.95:   9.994 ms/op
                 existUser·p0.99:   13.943 ms/op
                 existUser·p0.999:  29.810 ms/op
                 existUser·p0.9999: 32.492 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 5.991 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   2.535 ms/op
                 existUser·p0.50:   5.431 ms/op
                 existUser·p0.90:   7.995 ms/op
                 existUser·p0.95:   9.519 ms/op
                 existUser·p0.99:   13.140 ms/op
                 existUser·p0.999:  19.256 ms/op
                 existUser·p0.9999: 37.159 ms/op
                 existUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 154591
  mean =      6.204 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 39890 
    [ 5.000,  7.500) = 88710 
    [ 7.500, 10.000) = 18127 
    [10.000, 12.500) = 5359 
    [12.500, 15.000) = 1669 
    [15.000, 17.500) = 405 
    [17.500, 20.000) = 203 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.531 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      8.503 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     13.485 ms/op
     p(99.9000) =     23.049 ms/op
     p(99.9900) =     35.728 ms/op
     p(99.9990) =     37.629 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:14
# Fork: 1 of 1
# Warmup Iteration   1: 23.252 ±(99.9%) 0.432 ms/op
# Warmup Iteration   2: 8.151 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.746 ±(99.9%) 0.035 ms/op
Iteration   1: 6.646 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   2.417 ms/op
                 getUser·p0.50:   6.054 ms/op
                 getUser·p0.90:   9.142 ms/op
                 getUser·p0.95:   10.568 ms/op
                 getUser·p0.99:   14.483 ms/op
                 getUser·p0.999:  30.897 ms/op
                 getUser·p0.9999: 36.385 ms/op
                 getUser·p1.00:   39.453 ms/op

Iteration   2: 6.748 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   2.875 ms/op
                 getUser·p0.50:   6.029 ms/op
                 getUser·p0.90:   9.617 ms/op
                 getUser·p0.95:   11.338 ms/op
                 getUser·p0.99:   16.531 ms/op
                 getUser·p0.999:  27.184 ms/op
                 getUser·p0.9999: 36.275 ms/op
                 getUser·p1.00:   38.339 ms/op

Iteration   3: 6.537 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   5.890 ms/op
                 getUser·p0.90:   8.995 ms/op
                 getUser·p0.95:   10.453 ms/op
                 getUser·p0.99:   14.893 ms/op
                 getUser·p0.999:  31.753 ms/op
                 getUser·p0.9999: 36.504 ms/op
                 getUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 144450
  mean =      6.643 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 21663 
    [ 5.000,  7.500) = 90802 
    [ 7.500, 10.000) = 21715 
    [10.000, 12.500) = 6468 
    [12.500, 15.000) = 2290 
    [15.000, 17.500) = 694 
    [17.500, 20.000) = 401 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 58 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      9.241 ms/op
     p(95.0000) =     10.781 ms/op
     p(99.0000) =     15.122 ms/op
     p(99.9000) =     31.031 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     39.365 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.338 ±(99.9%) 0.578 ms/op
# Warmup Iteration   2: 10.146 ±(99.9%) 0.087 ms/op
# Warmup Iteration   3: 8.006 ±(99.9%) 0.045 ms/op
Iteration   1: 8.084 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   7.283 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   13.124 ms/op
                 listUser·p0.99:   18.055 ms/op
                 listUser·p0.999:  32.694 ms/op
                 listUser·p0.9999: 36.962 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   2: 7.632 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   6.906 ms/op
                 listUser·p0.90:   10.404 ms/op
                 listUser·p0.95:   12.026 ms/op
                 listUser·p0.99:   16.077 ms/op
                 listUser·p0.999:  30.577 ms/op
                 listUser·p0.9999: 33.686 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   3: 7.563 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   3.375 ms/op
                 listUser·p0.50:   6.971 ms/op
                 listUser·p0.90:   10.043 ms/op
                 listUser·p0.95:   11.731 ms/op
                 listUser·p0.99:   15.548 ms/op
                 listUser·p0.999:  34.300 ms/op
                 listUser·p0.9999: 42.271 ms/op
                 listUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 123740
  mean =      7.753 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1728 
    [ 5.000, 10.000) = 106089 
    [10.000, 15.000) = 13817 
    [15.000, 20.000) = 1594 
    [20.000, 25.000) = 230 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 136 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      7.045 ms/op
     p(90.0000) =     10.617 ms/op
     p(95.0000) =     12.255 ms/op
     p(99.0000) =     16.581 ms/op
     p(99.9000) =     32.162 ms/op
     p(99.9900) =     41.517 ms/op
     p(99.9990) =     42.536 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


# Run complete. Total time: 00:13:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   4.677 ± 4.321  ops/ms
ClientPb.existUser                       thrpt       3   4.953 ± 2.349  ops/ms
ClientPb.getUser                         thrpt       3   4.677 ± 1.552  ops/ms
ClientPb.listUser                        thrpt       3   4.162 ± 0.878  ops/ms
ClientPb.createUser                       avgt       3   6.644 ± 3.795   ms/op
ClientPb.existUser                        avgt       3   6.219 ± 1.431   ms/op
ClientPb.getUser                          avgt       3   6.343 ± 2.151   ms/op
ClientPb.listUser                         avgt       3   7.691 ± 0.414   ms/op
ClientPb.createUser                     sample  148483   6.460 ± 0.018   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.116           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.700           ms/op
ClientPb.createUser:createUser·p0.95    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.99    sample          14.303           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.890           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.157           ms/op
ClientPb.existUser                      sample  154591   6.204 ± 0.017   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.503           ms/op
ClientPb.existUser:existUser·p0.95      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.485           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.049           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.728           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  144450   6.643 ± 0.020   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.363           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.90          sample           9.241           ms/op
ClientPb.getUser:getUser·p0.95          sample          10.781           ms/op
ClientPb.getUser:getUser·p0.99          sample          15.122           ms/op
ClientPb.getUser:getUser·p0.999         sample          31.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.372           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  123740   7.753 ± 0.024   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.963           ms/op
ClientPb.listUser:listUser·p0.50        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.90        sample          10.617           ms/op
ClientPb.listUser:listUser·p0.95        sample          12.255           ms/op
ClientPb.listUser:listUser·p0.99        sample          16.581           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.162           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.598           ms/op
