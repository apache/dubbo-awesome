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
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 6.364 ops/ms
# Warmup Iteration   3: 9.301 ops/ms
Iteration   1: 9.566 ops/ms
Iteration   2: 9.623 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.628 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (9.566, 9.628, 9.694), stdev = 0.064
  CI (99.9%): [8.453, 10.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.582 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.009 ops/ms
Iteration   1: 9.906 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.236 ±(99.9%) 5.557 ops/ms [Average]
  (min, avg, max) = (9.906, 10.236, 10.507), stdev = 0.305
  CI (99.9%): [4.679, 15.793] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ops/ms
# Warmup Iteration   2: 8.807 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 9.910 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.838 ±(99.9%) 1.762 ops/ms [Average]
  (min, avg, max) = (9.728, 9.838, 9.910), stdev = 0.097
  CI (99.9%): [8.076, 11.600] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.141 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.233 ±(99.9%) 3.496 ops/ms [Average]
  (min, avg, max) = (8.087, 8.233, 8.450), stdev = 0.192
  CI (99.9%): [4.738, 11.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.005 ms/op
Iteration   1: 3.215 ±(99.9%) 0.005 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.181 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.181, 3.197, 3.215), stdev = 0.017
  CI (99.9%): [2.887, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 7.511 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.105 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.060, 3.105, 3.162), stdev = 0.052
  CI (99.9%): [2.155, 4.056] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.710 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.003 ms/op
Iteration   1: 3.338 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.004 ms/op
Iteration   3: 3.397 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.321 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.229, 3.321, 3.397), stdev = 0.085
  CI (99.9%): [1.766, 4.877] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.447 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.005 ms/op
Iteration   1: 3.893 ±(99.9%) 0.004 ms/op
Iteration   2: 3.988 ±(99.9%) 0.003 ms/op
Iteration   3: 3.908 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.930 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.893, 3.930, 3.988), stdev = 0.051
  CI (99.9%): [3.004, 4.855] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.341 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  11.552 ms/op
                 createUser·p0.9999: 25.861 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  13.045 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.180 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  16.536 ms/op
                 createUser·p0.9999: 25.023 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297177
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25580 
    [ 2.500,  5.000) = 264401 
    [ 5.000,  7.500) = 5838 
    [ 7.500, 10.000) = 952 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     15.736 ms/op
     p(99.9900) =     26.387 ms/op
     p(99.9990) =     27.954 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 8.344 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.617 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  12.377 ms/op
                 existUser·p0.9999: 21.812 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.990 ms/op
                 existUser·p0.999:  9.608 ms/op
                 existUser·p0.9999: 22.680 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300226
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22023 
    [ 2.500,  5.000) = 270987 
    [ 5.000,  7.500) = 5642 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     11.875 ms/op
     p(99.9900) =     21.954 ms/op
     p(99.9990) =     23.592 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 8.469 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.010 ms/op
Iteration   1: 3.239 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  18.210 ms/op
                 getUser·p0.9999: 26.939 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  9.891 ms/op
                 getUser·p0.9999: 23.895 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  15.259 ms/op
                 getUser·p0.9999: 23.758 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297544
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11994 
    [ 2.500,  5.000) = 277560 
    [ 5.000,  7.500) = 6569 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     27.855 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 8.895 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.159 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.015 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 23.251 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 19.690 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  14.374 ms/op
                 listUser·p0.9999: 19.292 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246159
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 235718 
    [ 5.000,  7.500) = 7502 
    [ 7.500, 10.000) = 2065 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     21.271 ms/op
     p(99.9990) =     23.595 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.628 ± 1.174  ops/ms
ClientPb.existUser                       thrpt       3  10.236 ± 5.557  ops/ms
ClientPb.getUser                         thrpt       3   9.838 ± 1.762  ops/ms
ClientPb.listUser                        thrpt       3   8.233 ± 3.496  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 0.310   ms/op
ClientPb.existUser                        avgt       3   3.105 ± 0.951   ms/op
ClientPb.getUser                          avgt       3   3.321 ± 1.556   ms/op
ClientPb.listUser                         avgt       3   3.930 ± 0.925   ms/op
ClientPb.createUser                     sample  297177   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.736           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.387           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  300226   3.198 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.954           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  297544   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.032           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.957           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.100           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.148           ms/op
ClientPb.listUser                       sample  246159   3.898 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.271           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
