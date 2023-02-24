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
# Warmup Iteration   1: 2.722 ops/ms
# Warmup Iteration   2: 5.948 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 10.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.003 ±(99.9%) 3.778 ops/ms [Average]
  (min, avg, max) = (9.871, 10.003, 10.242), stdev = 0.207
  CI (99.9%): [6.226, 13.781] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.310 ops/ms
Iteration   2: 10.124 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.254 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (10.124, 10.254, 10.329), stdev = 0.113
  CI (99.9%): [8.190, 12.319] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.692 ops/ms
# Warmup Iteration   2: 8.955 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 10.115 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.014 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (9.915, 10.014, 10.115), stdev = 0.100
  CI (99.9%): [8.197, 11.832] (assumes normal distribution)


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
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 7.748 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 8.610 ops/ms
Iteration   2: 8.534 ops/ms
Iteration   3: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 1.100 ops/ms [Average]
  (min, avg, max) = (8.534, 8.599, 8.653), stdev = 0.060
  CI (99.9%): [7.498, 9.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.062 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
Iteration   3: 3.063 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.125 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (3.063, 3.125, 3.232), stdev = 0.094
  CI (99.9%): [1.418, 4.832] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.187 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.006 ms/op
Iteration   1: 2.945 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.994 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.971 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.945, 2.971, 2.994), stdev = 0.025
  CI (99.9%): [2.523, 3.419] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.140 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.003 ms/op
Iteration   1: 3.198 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
Iteration   3: 3.222 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.214 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.198, 3.214, 3.222), stdev = 0.014
  CI (99.9%): [2.959, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.006 ms/op
Iteration   1: 3.673 ±(99.9%) 0.010 ms/op
Iteration   2: 3.613 ±(99.9%) 0.011 ms/op
Iteration   3: 3.571 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.619 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.571, 3.619, 3.673), stdev = 0.051
  CI (99.9%): [2.688, 4.549] (assumes normal distribution)


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
# Warmup Iteration   1: 8.589 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
Iteration   1: 3.193 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  17.067 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  10.522 ms/op
                 createUser·p0.9999: 22.145 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.789 ms/op
                 createUser·p0.999:  15.662 ms/op
                 createUser·p0.9999: 21.620 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302774
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11945 
    [ 2.500,  5.000) = 284208 
    [ 5.000,  7.500) = 5595 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     16.883 ms/op
     p(99.9900) =     21.782 ms/op
     p(99.9990) =     23.001 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 7.573 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
Iteration   1: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 20.201 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.536 ms/op
                 existUser·p0.9999: 24.003 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 20.143 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313985
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24601 
    [ 2.500,  5.000) = 284421 
    [ 5.000,  7.500) = 4376 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.888 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  15.158 ms/op
                 getUser·p0.9999: 19.339 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 21.870 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.488 ms/op
                 getUser·p0.999:  10.112 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299892
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10547 
    [ 2.500,  5.000) = 282234 
    [ 5.000,  7.500) = 6111 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     11.589 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.175 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255448
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 248058 
    [ 5.000,  7.500) = 5796 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     19.086 ms/op
     p(99.9990) =     21.482 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.003 ± 3.778  ops/ms
ClientPb.existUser                       thrpt       3  10.254 ± 2.064  ops/ms
ClientPb.getUser                         thrpt       3  10.014 ± 1.818  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 1.100  ops/ms
ClientPb.createUser                       avgt       3   3.125 ± 1.707   ms/op
ClientPb.existUser                        avgt       3   2.971 ± 0.448   ms/op
ClientPb.getUser                          avgt       3   3.214 ± 0.255   ms/op
ClientPb.listUser                         avgt       3   3.619 ± 0.930   ms/op
ClientPb.createUser                     sample  302774   3.168 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.883           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.782           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.265           ms/op
ClientPb.existUser                      sample  313985   3.057 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.069           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  299892   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.589           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.315           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.936           ms/op
ClientPb.listUser                       sample  255448   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.957           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
