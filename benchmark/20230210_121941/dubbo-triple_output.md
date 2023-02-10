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
# Warmup Iteration   1: 1.587 ops/ms
# Warmup Iteration   2: 3.718 ops/ms
# Warmup Iteration   3: 7.402 ops/ms
Iteration   1: 7.703 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.125 ±(99.9%) 6.666 ops/ms [Average]
  (min, avg, max) = (7.703, 8.125, 8.340), stdev = 0.365
  CI (99.9%): [1.459, 14.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.931 ops/ms
# Warmup Iteration   2: 7.707 ops/ms
# Warmup Iteration   3: 8.507 ops/ms
Iteration   1: 8.780 ops/ms
Iteration   2: 8.616 ops/ms
Iteration   3: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.628 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (8.488, 8.628, 8.780), stdev = 0.147
  CI (99.9%): [5.955, 11.302] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.998 ops/ms
# Warmup Iteration   2: 6.336 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.617 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.379 ±(99.9%) 3.898 ops/ms [Average]
  (min, avg, max) = (8.203, 8.379, 8.617), stdev = 0.214
  CI (99.9%): [4.481, 12.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 6.005 ops/ms
# Warmup Iteration   3: 6.947 ops/ms
Iteration   1: 7.072 ops/ms
Iteration   2: 7.012 ops/ms
Iteration   3: 7.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.038 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (7.012, 7.038, 7.072), stdev = 0.031
  CI (99.9%): [6.482, 7.595] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.615 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.960 ±(99.9%) 0.007 ms/op
Iteration   2: 3.967 ±(99.9%) 0.008 ms/op
Iteration   3: 3.782 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.903 ±(99.9%) 1.913 ms/op [Average]
  (min, avg, max) = (3.782, 3.903, 3.967), stdev = 0.105
  CI (99.9%): [1.990, 5.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.507 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.011 ms/op
Iteration   1: 3.699 ±(99.9%) 0.006 ms/op
Iteration   2: 3.806 ±(99.9%) 0.003 ms/op
Iteration   3: 3.662 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.722 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.662, 3.722, 3.806), stdev = 0.075
  CI (99.9%): [2.360, 5.085] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.178 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.008 ms/op
Iteration   1: 3.991 ±(99.9%) 0.005 ms/op
Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
Iteration   3: 3.964 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.969 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.952, 3.969, 3.991), stdev = 0.020
  CI (99.9%): [3.602, 4.336] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.526 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.009 ms/op
Iteration   1: 4.534 ±(99.9%) 0.010 ms/op
Iteration   2: 4.397 ±(99.9%) 0.013 ms/op
Iteration   3: 4.581 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.504 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (4.397, 4.504, 4.581), stdev = 0.096
  CI (99.9%): [2.757, 6.250] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.893 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.017 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  21.395 ms/op
                 createUser·p0.9999: 24.599 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 25.157 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 4.010 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  24.253 ms/op
                 createUser·p0.9999: 34.211 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242744
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 563 
    [ 2.500,  5.000) = 231071 
    [ 5.000,  7.500) = 9463 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     21.734 ms/op
     p(99.9900) =     32.235 ms/op
     p(99.9990) =     34.706 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.704 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
Iteration   1: 3.740 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  11.331 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  21.671 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  14.828 ms/op
                 existUser·p0.9999: 28.769 ms/op
                 existUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252615
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 517 
    [ 2.500,  5.000) = 242086 
    [ 5.000,  7.500) = 8616 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     28.139 ms/op
     p(99.9990) =     29.507 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.120 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
Iteration   1: 3.913 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  23.535 ms/op
                 getUser·p0.9999: 37.290 ms/op
                 getUser·p1.00:   38.666 ms/op

Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  25.474 ms/op
                 getUser·p0.9999: 31.967 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.032 ms/op
                 getUser·p0.999:  9.481 ms/op
                 getUser·p0.9999: 32.926 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244393
  mean =      3.926 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194 
    [ 2.500,  5.000) = 234038 
    [ 5.000,  7.500) = 7730 
    [ 7.500, 10.000) = 1979 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.480 ms/op
     p(99.9000) =     23.527 ms/op
     p(99.9900) =     37.028 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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
# Warmup Iteration   1: 11.879 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.017 ms/op
Iteration   1: 4.679 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  25.362 ms/op
                 listUser·p0.9999: 30.364 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   2: 4.404 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  18.593 ms/op
                 listUser·p0.9999: 21.356 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 4.445 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212973
  mean =      4.506 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 194412 
    [ 5.000,  7.500) = 14446 
    [ 7.500, 10.000) = 3185 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     29.711 ms/op
     p(99.9990) =     31.034 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.125 ± 6.666  ops/ms
ClientPb.existUser                       thrpt       3   8.628 ± 2.674  ops/ms
ClientPb.getUser                         thrpt       3   8.379 ± 3.898  ops/ms
ClientPb.listUser                        thrpt       3   7.038 ± 0.557  ops/ms
ClientPb.createUser                       avgt       3   3.903 ± 1.913   ms/op
ClientPb.existUser                        avgt       3   3.722 ± 1.363   ms/op
ClientPb.getUser                          avgt       3   3.969 ± 0.367   ms/op
ClientPb.listUser                         avgt       3   4.504 ± 1.746   ms/op
ClientPb.createUser                     sample  242744   3.954 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.198           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.734           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.235           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  252615   3.799 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.139           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.557           ms/op
ClientPb.getUser                        sample  244393   3.926 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.527           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.666           ms/op
ClientPb.listUser                       sample  212973   4.506 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.159           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.350           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.711           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.883           ms/op
