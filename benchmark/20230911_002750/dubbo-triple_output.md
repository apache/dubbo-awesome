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
# Warmup Iteration   1: 2.713 ops/ms
# Warmup Iteration   2: 6.507 ops/ms
# Warmup Iteration   3: 9.434 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 10.086 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.975 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (9.839, 9.975, 10.086), stdev = 0.126
  CI (99.9%): [7.685, 12.265] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ops/ms
# Warmup Iteration   2: 9.694 ops/ms
# Warmup Iteration   3: 9.832 ops/ms
Iteration   1: 9.951 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.198 ±(99.9%) 3.909 ops/ms [Average]
  (min, avg, max) = (9.951, 10.198, 10.324), stdev = 0.214
  CI (99.9%): [6.289, 14.107] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.718 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.862 ops/ms
Iteration   3: 9.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.684 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (9.557, 9.684, 9.862), stdev = 0.159
  CI (99.9%): [6.779, 12.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.362 ops/ms
Iteration   3: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.393 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (8.359, 8.393, 8.458), stdev = 0.056
  CI (99.9%): [7.363, 9.423] (assumes normal distribution)


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
# Warmup Iteration   1: 8.657 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.004 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.220 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.172, 3.220, 3.306), stdev = 0.074
  CI (99.9%): [1.864, 4.577] (assumes normal distribution)


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
# Warmup Iteration   1: 7.913 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.006 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.151 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.101, 3.151, 3.186), stdev = 0.044
  CI (99.9%): [2.341, 3.961] (assumes normal distribution)


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
# Warmup Iteration   1: 8.528 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.002 ms/op
Iteration   2: 3.367 ±(99.9%) 0.004 ms/op
Iteration   3: 3.178 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 1.929 ms/op [Average]
  (min, avg, max) = (3.178, 3.245, 3.367), stdev = 0.106
  CI (99.9%): [1.316, 5.173] (assumes normal distribution)


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
# Warmup Iteration   1: 9.020 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.006 ms/op
Iteration   1: 3.810 ±(99.9%) 0.008 ms/op
Iteration   2: 3.867 ±(99.9%) 0.007 ms/op
Iteration   3: 3.797 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.797, 3.825, 3.867), stdev = 0.037
  CI (99.9%): [3.148, 4.501] (assumes normal distribution)


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
# Warmup Iteration   1: 8.523 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  12.072 ms/op
                 createUser·p0.9999: 28.703 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   2: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  12.139 ms/op
                 createUser·p0.9999: 23.121 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  15.614 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294955
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24535 
    [ 2.500,  5.000) = 261717 
    [ 5.000,  7.500) = 7037 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     15.484 ms/op
     p(99.9900) =     23.380 ms/op
     p(99.9990) =     29.365 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 7.195 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.009 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.784 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  10.028 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 24.082 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  19.375 ms/op
                 existUser·p0.9999: 24.425 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298825
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18523 
    [ 2.500,  5.000) = 272453 
    [ 5.000,  7.500) = 6732 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     23.928 ms/op
     p(99.9990) =     24.578 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 8.646 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.012 ms/op
Iteration   1: 3.380 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  15.904 ms/op
                 getUser·p0.9999: 18.826 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.232 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  10.126 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.071 ms/op
                 getUser·p0.999:  18.058 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289766
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11467 
    [ 2.500,  5.000) = 268599 
    [ 5.000,  7.500) = 8251 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.891 ms/op
     p(99.9900) =     26.183 ms/op
     p(99.9990) =     27.668 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 9.259 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.012 ms/op
Iteration   1: 3.777 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 30.507 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 17.615 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  13.192 ms/op
                 listUser·p0.9999: 19.714 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252796
  mean =      3.793 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 245328 
    [ 5.000,  7.500) = 4963 
    [ 7.500, 10.000) = 1739 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     14.569 ms/op
     p(99.9900) =     29.646 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.975 ± 2.290  ops/ms
ClientPb.existUser                       thrpt       3  10.198 ± 3.909  ops/ms
ClientPb.getUser                         thrpt       3   9.684 ± 2.904  ops/ms
ClientPb.listUser                        thrpt       3   8.393 ± 1.030  ops/ms
ClientPb.createUser                       avgt       3   3.220 ± 1.356   ms/op
ClientPb.existUser                        avgt       3   3.151 ± 0.810   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 1.929   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 0.677   ms/op
ClientPb.createUser                     sample  294955   3.254 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.484           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.380           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  298825   3.211 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.732           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.928           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  289766   3.313 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.183           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  252796   3.793 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.569           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.646           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.473           ms/op
