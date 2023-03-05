# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.675 ops/ms
# Warmup Iteration   2: 3.886 ops/ms
# Warmup Iteration   3: 7.488 ops/ms
Iteration   1: 7.581 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.985 ±(99.9%) 6.415 ops/ms [Average]
  (min, avg, max) = (7.581, 7.985, 8.225), stdev = 0.352
  CI (99.9%): [1.570, 14.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.468 ops/ms
# Warmup Iteration   2: 7.115 ops/ms
# Warmup Iteration   3: 8.508 ops/ms
Iteration   1: 8.512 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.558 ±(99.9%) 2.021 ops/ms [Average]
  (min, avg, max) = (8.477, 8.558, 8.684), stdev = 0.111
  CI (99.9%): [6.537, 10.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 6.415 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 8.366 ops/ms
Iteration   2: 8.206 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.320 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (8.206, 8.320, 8.387), stdev = 0.099
  CI (99.9%): [6.514, 10.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.180 ops/ms
# Warmup Iteration   2: 5.885 ops/ms
# Warmup Iteration   3: 6.820 ops/ms
Iteration   1: 7.059 ops/ms
Iteration   2: 6.972 ops/ms
Iteration   3: 6.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.950 ±(99.9%) 2.232 ops/ms [Average]
  (min, avg, max) = (6.818, 6.950, 7.059), stdev = 0.122
  CI (99.9%): [4.718, 9.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.449 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.971 ±(99.9%) 0.007 ms/op
Iteration   2: 3.865 ±(99.9%) 0.006 ms/op
Iteration   3: 3.887 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.908 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.865, 3.908, 3.971), stdev = 0.056
  CI (99.9%): [2.885, 4.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.644 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
Iteration   2: 3.782 ±(99.9%) 0.004 ms/op
Iteration   3: 3.809 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.796 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.782, 3.796, 3.809), stdev = 0.013
  CI (99.9%): [3.555, 4.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.733 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.008 ms/op
Iteration   1: 4.139 ±(99.9%) 0.004 ms/op
Iteration   2: 3.971 ±(99.9%) 0.005 ms/op
Iteration   3: 3.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.980 ±(99.9%) 2.801 ms/op [Average]
  (min, avg, max) = (3.832, 3.980, 4.139), stdev = 0.154
  CI (99.9%): [1.179, 6.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.772 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.589 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.743 ±(99.9%) 0.009 ms/op
Iteration   1: 4.664 ±(99.9%) 0.012 ms/op
Iteration   2: 4.507 ±(99.9%) 0.012 ms/op
Iteration   3: 4.595 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.589 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (4.507, 4.589, 4.664), stdev = 0.078
  CI (99.9%): [3.157, 6.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.919 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.017 ms/op
Iteration   1: 4.118 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  23.157 ms/op
                 createUser·p0.9999: 32.344 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   2: 4.093 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 41.353 ms/op
                 createUser·p1.00:   41.812 ms/op

Iteration   3: 3.947 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   5.119 ms/op
                 createUser·p0.99:   6.804 ms/op
                 createUser·p0.999:  27.555 ms/op
                 createUser·p0.9999: 31.031 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236807
  mean =      4.051 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 219089 
    [ 5.000, 10.000) = 17134 
    [10.000, 15.000) = 312 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.380 ms/op
     p(99.9000) =     23.206 ms/op
     p(99.9900) =     39.867 ms/op
     p(99.9990) =     41.633 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.096 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  22.589 ms/op
                 existUser·p0.9999: 24.709 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.770 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 27.149 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 3.784 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  27.047 ms/op
                 existUser·p0.9999: 34.341 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254101
  mean =      3.779 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 359 
    [ 2.500,  5.000) = 245278 
    [ 5.000,  7.500) = 6704 
    [ 7.500, 10.000) = 1360 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     21.941 ms/op
     p(99.9900) =     32.498 ms/op
     p(99.9990) =     34.961 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.919 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.016 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  18.514 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   6.123 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  23.315 ms/op
                 getUser·p0.9999: 26.500 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.976 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.273 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  12.363 ms/op
                 getUser·p0.9999: 32.137 ms/op
                 getUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237897
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 224563 
    [ 5.000,  7.500) = 10454 
    [ 7.500, 10.000) = 2049 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.804 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     18.553 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.229 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.415 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.774 ±(99.9%) 0.017 ms/op
Iteration   1: 4.799 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   9.353 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 28.234 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 4.639 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  19.695 ms/op
                 listUser·p0.9999: 21.499 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.798 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  17.356 ms/op
                 listUser·p0.9999: 19.344 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202432
  mean =      4.744 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 166139 
    [ 5.000,  7.500) = 31125 
    [ 7.500, 10.000) = 3743 
    [10.000, 12.500) = 813 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.926 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     26.232 ms/op
     p(99.9990) =     28.933 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.985 ± 6.415  ops/ms
ClientPb.existUser                       thrpt       3   8.558 ± 2.021  ops/ms
ClientPb.getUser                         thrpt       3   8.320 ± 1.806  ops/ms
ClientPb.listUser                        thrpt       3   6.950 ± 2.232  ops/ms
ClientPb.createUser                       avgt       3   3.908 ± 1.023   ms/op
ClientPb.existUser                        avgt       3   3.796 ± 0.242   ms/op
ClientPb.getUser                          avgt       3   3.980 ± 2.801   ms/op
ClientPb.listUser                         avgt       3   4.589 ± 1.432   ms/op
ClientPb.createUser                     sample  236807   4.051 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.380           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.206           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.867           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.812           ms/op
ClientPb.existUser                      sample  254101   3.779 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.626           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.941           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.498           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  237897   4.034 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.553           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.279           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  202432   4.744 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.519           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.926           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.694           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.232           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.491           ms/op
