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
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 5.314 ops/ms
# Warmup Iteration   3: 9.080 ops/ms
Iteration   1: 9.149 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.270 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (9.149, 9.270, 9.462), stdev = 0.168
  CI (99.9%): [6.199, 12.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ops/ms
# Warmup Iteration   2: 9.114 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (9.965, 10.128, 10.317), stdev = 0.177
  CI (99.9%): [6.890, 13.365] (assumes normal distribution)


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
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 8.796 ops/ms
# Warmup Iteration   3: 9.761 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.639 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.705 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (9.639, 9.705, 9.819), stdev = 0.099
  CI (99.9%): [7.897, 11.513] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 7.990 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.217 ±(99.9%) 0.754 ops/ms [Average]
  (min, avg, max) = (8.174, 8.217, 8.256), stdev = 0.041
  CI (99.9%): [7.463, 8.971] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.169 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.005 ms/op
Iteration   1: 3.301 ±(99.9%) 0.003 ms/op
Iteration   2: 3.352 ±(99.9%) 0.007 ms/op
Iteration   3: 3.271 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.308 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.271, 3.308, 3.352), stdev = 0.041
  CI (99.9%): [2.562, 4.054] (assumes normal distribution)


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
# Warmup Iteration   1: 6.319 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.004 ms/op
Iteration   1: 3.100 ±(99.9%) 0.008 ms/op
Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.016, 3.090, 3.153), stdev = 0.069
  CI (99.9%): [1.829, 4.350] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.391 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.004 ms/op
Iteration   1: 3.250 ±(99.9%) 0.005 ms/op
Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
Iteration   3: 3.236 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.260 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.236, 3.260, 3.294), stdev = 0.030
  CI (99.9%): [2.707, 3.813] (assumes normal distribution)


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
# Warmup Iteration   1: 9.743 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.007 ms/op
Iteration   1: 3.796 ±(99.9%) 0.012 ms/op
Iteration   2: 3.743 ±(99.9%) 0.010 ms/op
Iteration   3: 3.748 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.762 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.743, 3.762, 3.796), stdev = 0.029
  CI (99.9%): [3.231, 4.294] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.976 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.010 ms/op
Iteration   1: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  18.438 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  12.648 ms/op
                 createUser·p0.9999: 23.433 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.370 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.488 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  19.506 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289032
  mean =      3.320 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23305 
    [ 2.500,  5.000) = 256702 
    [ 5.000,  7.500) = 7724 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     17.792 ms/op
     p(99.9900) =     25.041 ms/op
     p(99.9990) =     26.972 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 7.598 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
Iteration   1: 3.119 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 22.658 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  12.817 ms/op
                 existUser·p0.9999: 23.236 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  10.028 ms/op
                 existUser·p0.9999: 25.396 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301578
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10402 
    [ 2.500,  5.000) = 283955 
    [ 5.000,  7.500) = 5665 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     23.457 ms/op
     p(99.9990) =     25.949 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.221 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  15.912 ms/op
                 getUser·p0.9999: 20.885 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.319 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  18.377 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 22.646 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287615
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11720 
    [ 2.500,  5.000) = 266643 
    [ 5.000,  7.500) = 7788 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     12.524 ms/op
     p(99.9900) =     25.336 ms/op
     p(99.9990) =     27.308 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 9.903 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.013 ms/op
Iteration   1: 3.852 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 26.686 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 3.847 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.240 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.835 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  13.769 ms/op
                 listUser·p0.9999: 16.308 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249442
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 240926 
    [ 5.000,  7.500) = 6064 
    [ 7.500, 10.000) = 1447 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     14.624 ms/op
     p(99.9900) =     25.956 ms/op
     p(99.9990) =     27.068 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.270 ± 3.071  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 3.238  ops/ms
ClientPb.getUser                         thrpt       3   9.705 ± 1.808  ops/ms
ClientPb.listUser                        thrpt       3   8.217 ± 0.754  ops/ms
ClientPb.createUser                       avgt       3   3.308 ± 0.746   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 1.261   ms/op
ClientPb.getUser                          avgt       3   3.260 ± 0.553   ms/op
ClientPb.listUser                         avgt       3   3.762 ± 0.532   ms/op
ClientPb.createUser                     sample  289032   3.320 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.488           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.792           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.041           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.099           ms/op
ClientPb.existUser                      sample  301578   3.183 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.895           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  287615   3.335 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.196           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.524           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.336           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  249442   3.845 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.552           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.624           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
