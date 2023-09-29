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
# Warmup Iteration   1: 0.905 ops/ms
# Warmup Iteration   2: 1.970 ops/ms
# Warmup Iteration   3: 4.415 ops/ms
Iteration   1: 5.201 ops/ms
Iteration   2: 5.204 ops/ms
Iteration   3: 5.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.266 ±(99.9%) 2.016 ops/ms [Average]
  (min, avg, max) = (5.201, 5.266, 5.394), stdev = 0.110
  CI (99.9%): [3.250, 7.282] (assumes normal distribution)


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
# Warmup Iteration   1: 1.240 ops/ms
# Warmup Iteration   2: 4.085 ops/ms
# Warmup Iteration   3: 5.313 ops/ms
Iteration   1: 5.393 ops/ms
Iteration   2: 5.560 ops/ms
Iteration   3: 5.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.525 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (5.393, 5.525, 5.623), stdev = 0.119
  CI (99.9%): [3.359, 7.691] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.335 ops/ms
# Warmup Iteration   2: 3.988 ops/ms
# Warmup Iteration   3: 5.179 ops/ms
Iteration   1: 5.094 ops/ms
Iteration   2: 5.255 ops/ms
Iteration   3: 5.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.210 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (5.094, 5.210, 5.281), stdev = 0.101
  CI (99.9%): [3.366, 7.054] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.314 ops/ms
# Warmup Iteration   2: 3.331 ops/ms
# Warmup Iteration   3: 4.311 ops/ms
Iteration   1: 4.554 ops/ms
Iteration   2: 4.549 ops/ms
Iteration   3: 4.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.545 ±(99.9%) 0.217 ops/ms [Average]
  (min, avg, max) = (4.532, 4.545, 4.554), stdev = 0.012
  CI (99.9%): [4.328, 4.762] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.309 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.630 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.134 ±(99.9%) 0.009 ms/op
Iteration   1: 6.225 ±(99.9%) 0.007 ms/op
Iteration   2: 5.977 ±(99.9%) 0.009 ms/op
Iteration   3: 6.181 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.128 ±(99.9%) 2.411 ms/op [Average]
  (min, avg, max) = (5.977, 6.128, 6.225), stdev = 0.132
  CI (99.9%): [3.716, 8.539] (assumes normal distribution)


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
# Warmup Iteration   1: 20.302 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.992 ±(99.9%) 0.009 ms/op
Iteration   1: 5.909 ±(99.9%) 0.009 ms/op
Iteration   2: 5.485 ±(99.9%) 0.016 ms/op
Iteration   3: 5.605 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.666 ±(99.9%) 3.982 ms/op [Average]
  (min, avg, max) = (5.485, 5.666, 5.909), stdev = 0.218
  CI (99.9%): [1.684, 9.649] (assumes normal distribution)


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
# Warmup Iteration   1: 20.358 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 7.402 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.221 ±(99.9%) 0.014 ms/op
Iteration   1: 5.860 ±(99.9%) 0.009 ms/op
Iteration   2: 6.024 ±(99.9%) 0.012 ms/op
Iteration   3: 5.891 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.925 ±(99.9%) 1.589 ms/op [Average]
  (min, avg, max) = (5.860, 5.925, 6.024), stdev = 0.087
  CI (99.9%): [4.336, 7.514] (assumes normal distribution)


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
# Warmup Iteration   1: 20.744 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 8.690 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 7.304 ±(99.9%) 0.009 ms/op
Iteration   1: 7.013 ±(99.9%) 0.009 ms/op
Iteration   2: 6.982 ±(99.9%) 0.015 ms/op
Iteration   3: 7.080 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.025 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (6.982, 7.025, 7.080), stdev = 0.050
  CI (99.9%): [6.106, 7.944] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.744 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 9.990 ±(99.9%) 0.091 ms/op
# Warmup Iteration   3: 6.863 ±(99.9%) 0.040 ms/op
Iteration   1: 6.163 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   8.126 ms/op
                 createUser·p0.95:   9.896 ms/op
                 createUser·p0.99:   14.909 ms/op
                 createUser·p0.999:  29.630 ms/op
                 createUser·p0.9999: 33.542 ms/op
                 createUser·p1.00:   37.224 ms/op

Iteration   2: 6.115 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   5.538 ms/op
                 createUser·p0.90:   8.126 ms/op
                 createUser·p0.95:   9.693 ms/op
                 createUser·p0.99:   13.263 ms/op
                 createUser·p0.999:  30.704 ms/op
                 createUser·p0.9999: 38.476 ms/op
                 createUser·p1.00:   38.928 ms/op

Iteration   3: 6.021 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.613 ms/op
                 createUser·p0.50:   5.579 ms/op
                 createUser·p0.90:   7.602 ms/op
                 createUser·p0.95:   9.191 ms/op
                 createUser·p0.99:   13.140 ms/op
                 createUser·p0.999:  20.249 ms/op
                 createUser·p0.9999: 36.222 ms/op
                 createUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157146
  mean =      6.099 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 27260 
    [ 5.000,  7.500) = 110569 
    [ 7.500, 10.000) = 12702 
    [10.000, 12.500) = 4130 
    [12.500, 15.000) = 1368 
    [15.000, 17.500) = 556 
    [17.500, 20.000) = 197 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      7.897 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     13.959 ms/op
     p(99.9000) =     30.212 ms/op
     p(99.9900) =     36.588 ms/op
     p(99.9990) =     38.741 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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
# Warmup Iteration   1: 19.022 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 7.912 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.175 ±(99.9%) 0.028 ms/op
Iteration   1: 6.189 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   5.669 ms/op
                 existUser·p0.90:   8.184 ms/op
                 existUser·p0.95:   9.617 ms/op
                 existUser·p0.99:   13.271 ms/op
                 existUser·p0.999:  29.699 ms/op
                 existUser·p0.9999: 47.830 ms/op
                 existUser·p1.00:   48.955 ms/op

Iteration   2: 5.960 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.848 ms/op
                 existUser·p0.95:   9.585 ms/op
                 existUser·p0.99:   13.566 ms/op
                 existUser·p0.999:  19.409 ms/op
                 existUser·p0.9999: 28.365 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 5.825 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   5.390 ms/op
                 existUser·p0.90:   7.201 ms/op
                 existUser·p0.95:   8.569 ms/op
                 existUser·p0.99:   13.156 ms/op
                 existUser·p0.999:  30.605 ms/op
                 existUser·p0.9999: 42.075 ms/op
                 existUser·p1.00:   71.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 160200
  mean =      5.988 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37937 
    [ 5.000, 10.000) = 116601 
    [10.000, 15.000) = 4766 
    [15.000, 20.000) = 566 
    [20.000, 25.000) = 99 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 76 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 29 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     13.402 ms/op
     p(99.9000) =     28.967 ms/op
     p(99.9900) =     45.875 ms/op
     p(99.9990) =     58.006 ms/op
     p(99.9999) =     71.696 ms/op
    p(100.0000) =     71.696 ms/op


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
# Warmup Iteration   1: 20.070 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 8.289 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.161 ±(99.9%) 0.028 ms/op
Iteration   1: 5.960 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.376 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.478 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   13.877 ms/op
                 getUser·p0.999:  37.487 ms/op
                 getUser·p0.9999: 42.533 ms/op
                 getUser·p1.00:   42.926 ms/op

Iteration   2: 5.704 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.003 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   8.233 ms/op
                 getUser·p0.99:   12.091 ms/op
                 getUser·p0.999:  28.995 ms/op
                 getUser·p0.9999: 38.535 ms/op
                 getUser·p1.00:   39.125 ms/op

Iteration   3: 5.852 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.580 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   12.120 ms/op
                 getUser·p0.999:  18.874 ms/op
                 getUser·p0.9999: 33.393 ms/op
                 getUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164349
  mean =      5.837 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 39093 
    [ 5.000, 10.000) = 120274 
    [10.000, 15.000) = 4291 
    [15.000, 20.000) = 430 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 39 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 55 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.763 ms/op
     p(99.9000) =     27.594 ms/op
     p(99.9900) =     41.219 ms/op
     p(99.9990) =     42.884 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


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
# Warmup Iteration   1: 24.695 ±(99.9%) 0.426 ms/op
# Warmup Iteration   2: 9.083 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 7.173 ±(99.9%) 0.037 ms/op
Iteration   1: 6.909 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.551 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.453 ms/op
                 listUser·p0.99:   13.685 ms/op
                 listUser·p0.999:  28.041 ms/op
                 listUser·p0.9999: 37.805 ms/op
                 listUser·p1.00:   38.732 ms/op

Iteration   2: 7.052 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.650 ms/op
                 listUser·p0.99:   14.909 ms/op
                 listUser·p0.999:  31.031 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   35.783 ms/op

Iteration   3: 6.982 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.088 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.530 ms/op
                 listUser·p0.95:   10.502 ms/op
                 listUser·p0.99:   13.484 ms/op
                 listUser·p0.999:  31.529 ms/op
                 listUser·p0.9999: 44.040 ms/op
                 listUser·p1.00:   44.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137451
  mean =      6.981 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2403 
    [ 5.000, 10.000) = 126666 
    [10.000, 15.000) = 7456 
    [15.000, 20.000) = 542 
    [20.000, 25.000) = 113 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 101 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      8.634 ms/op
     p(95.0000) =     10.535 ms/op
     p(99.0000) =     14.008 ms/op
     p(99.9000) =     30.689 ms/op
     p(99.9900) =     42.566 ms/op
     p(99.9990) =     44.466 ms/op
     p(99.9999) =     44.564 ms/op
    p(100.0000) =     44.564 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.266 ± 2.016  ops/ms
ClientPb.existUser                       thrpt       3   5.525 ± 2.166  ops/ms
ClientPb.getUser                         thrpt       3   5.210 ± 1.844  ops/ms
ClientPb.listUser                        thrpt       3   4.545 ± 0.217  ops/ms
ClientPb.createUser                       avgt       3   6.128 ± 2.411   ms/op
ClientPb.existUser                        avgt       3   5.666 ± 3.982   ms/op
ClientPb.getUser                          avgt       3   5.925 ± 1.589   ms/op
ClientPb.listUser                         avgt       3   7.025 ± 0.919   ms/op
ClientPb.createUser                     sample  157146   6.099 ± 0.017   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.897           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.634           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.959           ms/op
ClientPb.createUser:createUser·p0.999   sample          30.212           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.588           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.928           ms/op
ClientPb.existUser                      sample  160200   5.988 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.702           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.339           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.402           ms/op
ClientPb.existUser:existUser·p0.999     sample          28.967           ms/op
ClientPb.existUser:existUser·p0.9999    sample          45.875           ms/op
ClientPb.existUser:existUser·p1.00      sample          71.696           ms/op
ClientPb.getUser                        sample  164349   5.837 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.003           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.763           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.219           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.926           ms/op
ClientPb.listUser                       sample  137451   6.981 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.551           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.535           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.008           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.689           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.566           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.564           ms/op
