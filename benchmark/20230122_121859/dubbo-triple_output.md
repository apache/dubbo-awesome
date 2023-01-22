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
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 3.877 ops/ms
# Warmup Iteration   3: 7.370 ops/ms
Iteration   1: 7.535 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.989 ±(99.9%) 7.753 ops/ms [Average]
  (min, avg, max) = (7.535, 7.989, 8.378), stdev = 0.425
  CI (99.9%): [0.236, 15.742] (assumes normal distribution)


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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 8.231 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.284 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (8.231, 8.284, 8.316), stdev = 0.046
  CI (99.9%): [7.443, 9.124] (assumes normal distribution)


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
# Warmup Iteration   1: 2.172 ops/ms
# Warmup Iteration   2: 6.484 ops/ms
# Warmup Iteration   3: 7.652 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 7.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.102 ±(99.9%) 2.521 ops/ms [Average]
  (min, avg, max) = (7.943, 8.102, 8.195), stdev = 0.138
  CI (99.9%): [5.581, 10.623] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.965 ops/ms
# Warmup Iteration   2: 5.646 ops/ms
# Warmup Iteration   3: 6.799 ops/ms
Iteration   1: 6.406 ops/ms
Iteration   2: 6.686 ops/ms
Iteration   3: 6.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.640 ±(99.9%) 3.916 ops/ms [Average]
  (min, avg, max) = (6.406, 6.640, 6.828), stdev = 0.215
  CI (99.9%): [2.724, 10.556] (assumes normal distribution)


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
# Warmup Iteration   1: 13.371 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.005 ms/op
Iteration   1: 4.124 ±(99.9%) 0.005 ms/op
Iteration   2: 4.215 ±(99.9%) 0.010 ms/op
Iteration   3: 3.951 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.097 ±(99.9%) 2.452 ms/op [Average]
  (min, avg, max) = (3.951, 4.097, 4.215), stdev = 0.134
  CI (99.9%): [1.645, 6.549] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.002 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.006 ms/op
Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
Iteration   2: 3.967 ±(99.9%) 0.004 ms/op
Iteration   3: 3.903 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.908 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.855, 3.908, 3.967), stdev = 0.056
  CI (99.9%): [2.884, 4.933] (assumes normal distribution)


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
# Warmup Iteration   1: 12.714 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.004 ms/op
Iteration   1: 4.063 ±(99.9%) 0.007 ms/op
Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
Iteration   3: 3.890 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.982 ±(99.9%) 1.590 ms/op [Average]
  (min, avg, max) = (3.890, 3.982, 4.063), stdev = 0.087
  CI (99.9%): [2.393, 5.572] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.737 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.018 ms/op
Iteration   1: 4.834 ±(99.9%) 0.011 ms/op
Iteration   2: 4.575 ±(99.9%) 0.011 ms/op
Iteration   3: 4.693 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.701 ±(99.9%) 2.366 ms/op [Average]
  (min, avg, max) = (4.575, 4.701, 4.834), stdev = 0.130
  CI (99.9%): [2.334, 7.067] (assumes normal distribution)


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
# Warmup Iteration   1: 12.320 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.020 ms/op
Iteration   1: 3.836 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.966 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  13.173 ms/op
                 createUser·p0.9999: 27.612 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.763 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  25.847 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  25.427 ms/op
                 createUser·p0.9999: 29.265 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247697
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 239862 
    [ 5.000,  7.500) = 6092 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 163 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     24.520 ms/op
     p(99.9900) =     28.687 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 11.224 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 5.062 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.013 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 31.412 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   2: 3.922 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  23.986 ms/op
                 existUser·p0.9999: 26.570 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.815 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  14.795 ms/op
                 existUser·p0.9999: 33.214 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249337
  mean =      3.848 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 238159 
    [ 5.000,  7.500) = 9513 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.772 ms/op
     p(99.9000) =     14.948 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     34.178 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 13.237 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.965 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.016 ms/op
Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.886 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.617 ms/op
                 getUser·p0.999:  14.658 ms/op
                 getUser·p0.9999: 23.430 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 4.148 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  17.954 ms/op
                 getUser·p0.9999: 27.085 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 32.928 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237839
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 223567 
    [ 5.000,  7.500) = 12182 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     15.130 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     33.717 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 13.924 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.322 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.019 ms/op
Iteration   1: 4.680 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.068 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  23.514 ms/op
                 listUser·p0.9999: 30.835 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 4.740 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.432 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  20.254 ms/op
                 listUser·p0.9999: 27.296 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   3: 4.747 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.672 ms/op
                 listUser·p0.9999: 18.392 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203273
  mean =      4.722 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 173112 
    [ 5.000,  7.500) = 25361 
    [ 7.500, 10.000) = 3788 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     19.750 ms/op
     p(99.9900) =     29.699 ms/op
     p(99.9990) =     32.668 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.989 ± 7.753  ops/ms
ClientPb.existUser                       thrpt       3   8.284 ± 0.840  ops/ms
ClientPb.getUser                         thrpt       3   8.102 ± 2.521  ops/ms
ClientPb.listUser                        thrpt       3   6.640 ± 3.916  ops/ms
ClientPb.createUser                       avgt       3   4.097 ± 2.452   ms/op
ClientPb.existUser                        avgt       3   3.908 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   3.982 ± 1.590   ms/op
ClientPb.listUser                         avgt       3   4.701 ± 2.366   ms/op
ClientPb.createUser                     sample  247697   3.878 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.604           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.687           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.983           ms/op
ClientPb.existUser                      sample  249337   3.848 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.772           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.948           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.539           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.652           ms/op
ClientPb.getUser                        sample  237839   4.034 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.886           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.130           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.539           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  203273   4.722 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.432           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.750           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.699           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
