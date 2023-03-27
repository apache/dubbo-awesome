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
# Warmup Iteration   1: 1.311 ops/ms
# Warmup Iteration   2: 2.534 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 6.018 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 6.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.074 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (5.989, 6.074, 6.215), stdev = 0.123
  CI (99.9%): [3.822, 8.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.777 ops/ms
# Warmup Iteration   2: 5.470 ops/ms
# Warmup Iteration   3: 6.324 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.508 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.473 ±(99.9%) 2.932 ops/ms [Average]
  (min, avg, max) = (6.298, 6.473, 6.614), stdev = 0.161
  CI (99.9%): [3.541, 9.406] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.890 ops/ms
# Warmup Iteration   2: 5.154 ops/ms
# Warmup Iteration   3: 6.340 ops/ms
Iteration   1: 6.175 ops/ms
Iteration   2: 6.221 ops/ms
Iteration   3: 6.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.174 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (6.127, 6.174, 6.221), stdev = 0.047
  CI (99.9%): [5.310, 7.039] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.758 ops/ms
# Warmup Iteration   2: 4.410 ops/ms
# Warmup Iteration   3: 5.219 ops/ms
Iteration   1: 4.987 ops/ms
Iteration   2: 5.207 ops/ms
Iteration   3: 5.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.197 ±(99.9%) 3.723 ops/ms [Average]
  (min, avg, max) = (4.987, 5.197, 5.395), stdev = 0.204
  CI (99.9%): [1.474, 8.919] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.538 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.975 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.632 ±(99.9%) 0.009 ms/op
Iteration   1: 5.254 ±(99.9%) 0.012 ms/op
Iteration   2: 5.172 ±(99.9%) 0.019 ms/op
Iteration   3: 5.122 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.182 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (5.122, 5.182, 5.254), stdev = 0.066
  CI (99.9%): [3.970, 6.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.390 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.347 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.007 ms/op
Iteration   1: 4.852 ±(99.9%) 0.011 ms/op
Iteration   2: 4.847 ±(99.9%) 0.016 ms/op
Iteration   3: 4.887 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.862 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (4.847, 4.862, 4.887), stdev = 0.022
  CI (99.9%): [4.463, 5.261] (assumes normal distribution)


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
# Warmup Iteration   1: 15.473 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.818 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.329 ±(99.9%) 0.008 ms/op
Iteration   1: 5.355 ±(99.9%) 0.013 ms/op
Iteration   2: 5.341 ±(99.9%) 0.011 ms/op
Iteration   3: 5.076 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.257 ±(99.9%) 2.864 ms/op [Average]
  (min, avg, max) = (5.076, 5.257, 5.355), stdev = 0.157
  CI (99.9%): [2.394, 8.121] (assumes normal distribution)


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
# Warmup Iteration   1: 16.070 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 8.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.016 ms/op
Iteration   1: 5.971 ±(99.9%) 0.017 ms/op
Iteration   2: 6.017 ±(99.9%) 0.014 ms/op
Iteration   3: 6.369 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.119 ±(99.9%) 3.968 ms/op [Average]
  (min, avg, max) = (5.971, 6.119, 6.369), stdev = 0.217
  CI (99.9%): [2.151, 10.087] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.738 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.215 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.867 ±(99.9%) 0.027 ms/op
Iteration   1: 5.417 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  21.783 ms/op
                 createUser·p0.9999: 27.882 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 5.341 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.692 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  23.727 ms/op
                 createUser·p0.9999: 27.657 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 5.064 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  24.531 ms/op
                 createUser·p0.9999: 27.308 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182145
  mean =      5.270 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 89825 
    [ 5.000,  7.500) = 84524 
    [ 7.500, 10.000) = 6136 
    [10.000, 12.500) = 1113 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     22.174 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     29.488 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.778 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.670 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.162 ±(99.9%) 0.018 ms/op
Iteration   1: 5.043 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  23.589 ms/op
                 existUser·p0.9999: 31.118 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   2: 4.940 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.046 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  14.320 ms/op
                 existUser·p0.9999: 29.672 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 5.167 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  28.546 ms/op
                 existUser·p0.9999: 32.972 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190082
  mean =      5.048 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 116965 
    [ 5.000,  7.500) = 66038 
    [ 7.500, 10.000) = 5363 
    [10.000, 12.500) = 1065 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.991 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     19.461 ms/op
     p(99.9900) =     31.555 ms/op
     p(99.9990) =     33.862 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 16.419 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.994 ±(99.9%) 0.017 ms/op
Iteration   1: 5.101 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.903 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   6.898 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 30.398 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   2: 5.380 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   7.119 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  25.840 ms/op
                 getUser·p0.9999: 39.329 ms/op
                 getUser·p1.00:   40.174 ms/op

Iteration   3: 5.005 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.003 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   9.447 ms/op
                 getUser·p0.999:  23.438 ms/op
                 getUser·p0.9999: 28.102 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185953
  mean =      5.157 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 106401 
    [ 5.000, 10.000) = 77992 
    [10.000, 15.000) = 1307 
    [15.000, 20.000) = 61 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.903 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.153 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     39.667 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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
# Warmup Iteration   1: 15.973 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.977 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.210 ±(99.9%) 0.022 ms/op
Iteration   1: 5.930 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 30.999 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 6.227 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.006 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  28.606 ms/op
                 listUser·p0.9999: 33.500 ms/op
                 listUser·p1.00:   35.848 ms/op

Iteration   3: 6.177 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.305 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.262 ms/op
                 listUser·p0.999:  23.871 ms/op
                 listUser·p0.9999: 27.491 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157061
  mean =      6.109 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 13924 
    [ 5.000,  7.500) = 131542 
    [ 7.500, 10.000) = 8541 
    [10.000, 12.500) = 2020 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     32.352 ms/op
     p(99.9990) =     34.689 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.074 ± 2.252  ops/ms
ClientPb.existUser                       thrpt       3   6.473 ± 2.932  ops/ms
ClientPb.getUser                         thrpt       3   6.174 ± 0.865  ops/ms
ClientPb.listUser                        thrpt       3   5.197 ± 3.723  ops/ms
ClientPb.createUser                       avgt       3   5.182 ± 1.212   ms/op
ClientPb.existUser                        avgt       3   4.862 ± 0.399   ms/op
ClientPb.getUser                          avgt       3   5.257 ± 2.864   ms/op
ClientPb.listUser                         avgt       3   6.119 ± 3.968   ms/op
ClientPb.createUser                     sample  182145   5.270 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.716           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.722           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.622           ms/op
ClientPb.existUser                      sample  190082   5.048 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.037           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.461           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.555           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  185953   5.157 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.634           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.207           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.174           ms/op
ClientPb.listUser                       sample  157061   6.109 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.207           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.395           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.352           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.848           ms/op
