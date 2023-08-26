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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.617 ops/ms
# Warmup Iteration   3: 8.513 ops/ms
Iteration   1: 9.048 ops/ms
Iteration   2: 9.209 ops/ms
Iteration   3: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.166 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (9.048, 9.166, 9.241), stdev = 0.103
  CI (99.9%): [7.279, 11.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 8.936 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.740 ±(99.9%) 3.124 ops/ms [Average]
  (min, avg, max) = (9.581, 9.740, 9.922), stdev = 0.171
  CI (99.9%): [6.616, 12.863] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 7.982 ops/ms
# Warmup Iteration   3: 8.776 ops/ms
Iteration   1: 9.057 ops/ms
Iteration   2: 8.934 ops/ms
Iteration   3: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.069 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (8.934, 9.069, 9.216), stdev = 0.142
  CI (99.9%): [6.486, 11.652] (assumes normal distribution)


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
# Warmup Iteration   1: 3.048 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 7.602 ops/ms
Iteration   1: 7.507 ops/ms
Iteration   2: 7.819 ops/ms
Iteration   3: 7.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.703 ±(99.9%) 3.112 ops/ms [Average]
  (min, avg, max) = (7.507, 7.703, 7.819), stdev = 0.171
  CI (99.9%): [4.591, 10.815] (assumes normal distribution)


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
# Warmup Iteration   1: 9.437 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.006 ms/op
Iteration   1: 3.452 ±(99.9%) 0.003 ms/op
Iteration   2: 3.481 ±(99.9%) 0.004 ms/op
Iteration   3: 3.457 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.463 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.452, 3.463, 3.481), stdev = 0.015
  CI (99.9%): [3.188, 3.739] (assumes normal distribution)


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
# Warmup Iteration   1: 8.751 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.004 ms/op
Iteration   1: 3.404 ±(99.9%) 0.007 ms/op
Iteration   2: 3.388 ±(99.9%) 0.004 ms/op
Iteration   3: 3.307 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.366 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.307, 3.366, 3.404), stdev = 0.052
  CI (99.9%): [2.416, 4.317] (assumes normal distribution)


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
# Warmup Iteration   1: 9.596 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.004 ms/op
Iteration   1: 3.440 ±(99.9%) 0.004 ms/op
Iteration   2: 3.449 ±(99.9%) 0.004 ms/op
Iteration   3: 3.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.460 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.440, 3.460, 3.492), stdev = 0.028
  CI (99.9%): [2.956, 3.965] (assumes normal distribution)


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
# Warmup Iteration   1: 10.603 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.007 ms/op
Iteration   1: 4.054 ±(99.9%) 0.009 ms/op
Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.991 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.909, 3.991, 4.054), stdev = 0.075
  CI (99.9%): [2.628, 5.353] (assumes normal distribution)


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
# Warmup Iteration   1: 9.171 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.182 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  24.065 ms/op
                 createUser·p0.9999: 27.221 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.453 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  23.178 ms/op
                 createUser·p0.9999: 30.874 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277949
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7484 
    [ 2.500,  5.000) = 264458 
    [ 5.000,  7.500) = 4680 
    [ 7.500, 10.000) = 716 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     21.547 ms/op
     p(99.9900) =     30.258 ms/op
     p(99.9990) =     31.694 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.243 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
Iteration   1: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  20.933 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  12.137 ms/op
                 existUser·p0.9999: 25.604 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.325 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  19.769 ms/op
                 existUser·p0.9999: 26.263 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286074
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15886 
    [ 2.500,  5.000) = 262048 
    [ 5.000,  7.500) = 6619 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     25.703 ms/op
     p(99.9990) =     28.385 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 8.974 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.013 ms/op
Iteration   1: 3.535 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  10.806 ms/op
                 getUser·p0.9999: 24.640 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.483 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  28.953 ms/op
                 getUser·p0.9999: 33.292 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.570 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  20.988 ms/op
                 getUser·p0.9999: 35.783 ms/op
                 getUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271764
  mean =      3.529 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4474 
    [ 2.500,  5.000) = 257872 
    [ 5.000,  7.500) = 7898 
    [ 7.500, 10.000) = 1024 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     16.535 ms/op
     p(99.9900) =     34.580 ms/op
     p(99.9990) =     36.213 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 10.655 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.015 ms/op
Iteration   1: 4.191 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  21.279 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   30.704 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.708 ms/op
                 listUser·p0.999:  17.174 ms/op
                 listUser·p0.9999: 22.876 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233806
  mean =      4.104 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 220729 
    [ 5.000,  7.500) = 9888 
    [ 7.500, 10.000) = 2164 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     16.698 ms/op
     p(99.9900) =     27.873 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.166 ± 1.887  ops/ms
ClientPb.existUser                       thrpt       3   9.740 ± 3.124  ops/ms
ClientPb.getUser                         thrpt       3   9.069 ± 2.583  ops/ms
ClientPb.listUser                        thrpt       3   7.703 ± 3.112  ops/ms
ClientPb.createUser                       avgt       3   3.463 ± 0.276   ms/op
ClientPb.existUser                        avgt       3   3.366 ± 0.950   ms/op
ClientPb.getUser                          avgt       3   3.460 ± 0.505   ms/op
ClientPb.listUser                         avgt       3   3.991 ± 1.363   ms/op
ClientPb.createUser                     sample  277949   3.453 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.726           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  286074   3.356 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.703           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  271764   3.529 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.692           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.535           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.580           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.504           ms/op
ClientPb.listUser                       sample  233806   4.104 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.075           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.698           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.704           ms/op
