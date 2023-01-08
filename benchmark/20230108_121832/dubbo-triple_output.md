# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 6.412 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 9.738 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.080 ±(99.9%) 5.718 ops/ms [Average]
  (min, avg, max) = (9.738, 10.080, 10.355), stdev = 0.313
  CI (99.9%): [4.362, 15.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 9.333 ops/ms
# Warmup Iteration   3: 10.644 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.918 ops/ms
Iteration   3: 10.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.758 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (10.667, 10.758, 10.918), stdev = 0.138
  CI (99.9%): [8.232, 13.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 9.239 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 10.039 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.133 ±(99.9%) 7.500 ops/ms [Average]
  (min, avg, max) = (9.777, 10.133, 10.583), stdev = 0.411
  CI (99.9%): [2.633, 17.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 7.839 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.536 ops/ms
Iteration   3: 8.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.484 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (8.382, 8.484, 8.536), stdev = 0.088
  CI (99.9%): [6.875, 10.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.086 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.063, 3.086, 3.124), stdev = 0.033
  CI (99.9%): [2.489, 3.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.383 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.120 ±(99.9%) 0.008 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.031 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (2.985, 3.031, 3.120), stdev = 0.078
  CI (99.9%): [1.612, 4.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.449 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.004 ms/op
Iteration   1: 3.382 ±(99.9%) 0.004 ms/op
Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
Iteration   3: 3.249 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.254 ±(99.9%) 2.282 ms/op [Average]
  (min, avg, max) = (3.132, 3.254, 3.382), stdev = 0.125
  CI (99.9%): [0.973, 5.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.924 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.005 ms/op
Iteration   1: 3.679 ±(99.9%) 0.008 ms/op
Iteration   2: 3.781 ±(99.9%) 0.007 ms/op
Iteration   3: 3.626 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.695 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.626, 3.695, 3.781), stdev = 0.079
  CI (99.9%): [2.253, 5.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.885 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.009 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 20.103 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  16.408 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  15.761 ms/op
                 createUser·p0.9999: 23.998 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306402
  mean =      3.132 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25617 
    [ 2.500,  5.000) = 275997 
    [ 5.000,  7.500) = 3766 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     15.869 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     25.721 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  13.086 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.124 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 28.255 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.296 ms/op
                 existUser·p0.9999: 21.631 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311932
  mean =      3.077 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21879 
    [ 2.500,  5.000) = 284080 
    [ 5.000,  7.500) = 4867 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     26.929 ms/op
     p(99.9990) =     28.755 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.179 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.011 ms/op
Iteration   1: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  10.377 ms/op
                 getUser·p0.9999: 21.743 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 21.567 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  11.418 ms/op
                 getUser·p0.9999: 20.479 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 307922
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23338 
    [ 2.500,  5.000) = 278730 
    [ 5.000,  7.500) = 5053 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.712 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.873 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.012 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.456 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 18.922 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.733 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.834 ms/op
                 listUser·p0.9999: 16.078 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257982
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 116 
    [ 2.500,  3.750) = 197773 
    [ 3.750,  5.000) = 52409 
    [ 5.000,  6.250) = 3228 
    [ 6.250,  7.500) = 2675 
    [ 7.500,  8.750) = 754 
    [ 8.750, 10.000) = 387 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 167 
    [13.750, 15.000) = 134 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     19.216 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.080 ± 5.718  ops/ms
ClientPb.existUser                       thrpt       3  10.758 ± 2.526  ops/ms
ClientPb.getUser                         thrpt       3  10.133 ± 7.500  ops/ms
ClientPb.listUser                        thrpt       3   8.484 ± 1.609  ops/ms
ClientPb.createUser                       avgt       3   3.086 ± 0.597   ms/op
ClientPb.existUser                        avgt       3   3.031 ± 1.418   ms/op
ClientPb.getUser                          avgt       3   3.254 ± 2.282   ms/op
ClientPb.listUser                         avgt       3   3.695 ± 1.442   ms/op
ClientPb.createUser                     sample  306402   3.132 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.085           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.869           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.904           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  311932   3.077 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.820           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.929           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  307922   3.114 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.158           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.970           ms/op
ClientPb.listUser                       sample  257982   3.718 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.269           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.333           ms/op
