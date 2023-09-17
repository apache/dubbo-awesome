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
# Warmup Iteration   1: 2.493 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 9.099 ops/ms
Iteration   1: 9.880 ops/ms
Iteration   2: 9.783 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.873 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (9.783, 9.873, 9.956), stdev = 0.087
  CI (99.9%): [8.286, 11.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 10.229 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 10.209 ops/ms
Iteration   3: 10.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.177 ±(99.9%) 2.950 ops/ms [Average]
  (min, avg, max) = (10.002, 10.177, 10.321), stdev = 0.162
  CI (99.9%): [7.227, 13.127] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 9.336 ops/ms
# Warmup Iteration   3: 9.596 ops/ms
Iteration   1: 9.936 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.856 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (9.796, 9.856, 9.936), stdev = 0.072
  CI (99.9%): [8.540, 11.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.163 ops/ms
Iteration   1: 8.424 ops/ms
Iteration   2: 8.448 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.409 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (8.354, 8.409, 8.448), stdev = 0.049
  CI (99.9%): [7.515, 9.302] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.087 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.003 ms/op
Iteration   1: 3.333 ±(99.9%) 0.005 ms/op
Iteration   2: 3.250 ±(99.9%) 0.004 ms/op
Iteration   3: 3.160 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.247 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.160, 3.247, 3.333), stdev = 0.086
  CI (99.9%): [1.675, 4.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.775 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.002 ms/op
Iteration   1: 3.203 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
Iteration   3: 3.166 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.156 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.101, 3.156, 3.203), stdev = 0.052
  CI (99.9%): [2.215, 4.098] (assumes normal distribution)


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
# Warmup Iteration   1: 8.970 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.294 ±(99.9%) 0.003 ms/op
Iteration   2: 3.151 ±(99.9%) 0.005 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.207 ±(99.9%) 1.390 ms/op [Average]
  (min, avg, max) = (3.151, 3.207, 3.294), stdev = 0.076
  CI (99.9%): [1.817, 4.597] (assumes normal distribution)


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
# Warmup Iteration   1: 8.795 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.005 ms/op
Iteration   1: 3.824 ±(99.9%) 0.005 ms/op
Iteration   2: 3.758 ±(99.9%) 0.007 ms/op
Iteration   3: 3.840 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.807 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.758, 3.807, 3.840), stdev = 0.044
  CI (99.9%): [3.011, 4.603] (assumes normal distribution)


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
# Warmup Iteration   1: 8.557 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 20.976 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 23.006 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.046 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 20.802 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294338
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10473 
    [ 2.500,  5.000) = 279746 
    [ 5.000,  7.500) = 3268 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     15.068 ms/op
     p(99.9900) =     21.996 ms/op
     p(99.9990) =     23.174 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 7.621 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 21.235 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   2: 3.265 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  14.600 ms/op
                 existUser·p0.9999: 22.185 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  13.575 ms/op
                 existUser·p0.9999: 21.326 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302229
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18016 
    [ 2.500,  5.000) = 278539 
    [ 5.000,  7.500) = 4680 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     13.693 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.478 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.292 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 19.469 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.168 ms/op
                 getUser·p0.999:  8.073 ms/op
                 getUser·p0.9999: 21.918 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  15.424 ms/op
                 getUser·p0.9999: 21.559 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296565
  mean =      3.236 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12778 
    [ 2.500,  5.000) = 278882 
    [ 5.000,  7.500) = 4115 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     16.063 ms/op
     p(99.9900) =     21.442 ms/op
     p(99.9990) =     22.974 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 9.546 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.944 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.845 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 14.740 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   3: 3.767 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.308 ms/op
                 listUser·p0.999:  13.477 ms/op
                 listUser·p0.9999: 14.500 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250176
  mean =      3.836 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 243190 
    [ 5.000,  7.500) = 5410 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     19.365 ms/op
     p(99.9990) =     21.904 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.873 ± 1.587  ops/ms
ClientPb.existUser                       thrpt       3  10.177 ± 2.950  ops/ms
ClientPb.getUser                         thrpt       3   9.856 ± 1.316  ops/ms
ClientPb.listUser                        thrpt       3   8.409 ± 0.893  ops/ms
ClientPb.createUser                       avgt       3   3.247 ± 1.572   ms/op
ClientPb.existUser                        avgt       3   3.156 ± 0.941   ms/op
ClientPb.getUser                          avgt       3   3.207 ± 1.390   ms/op
ClientPb.listUser                         avgt       3   3.807 ± 0.796   ms/op
ClientPb.createUser                     sample  294338   3.259 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.765           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.068           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  302229   3.174 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.200           ms/op
ClientPb.getUser                        sample  296565   3.236 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.063           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.442           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.167           ms/op
ClientPb.listUser                       sample  250176   3.836 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
