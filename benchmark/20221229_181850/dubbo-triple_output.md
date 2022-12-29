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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.908 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 8.913 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.268 ±(99.9%) 5.648 ops/ms [Average]
  (min, avg, max) = (8.913, 9.268, 9.481), stdev = 0.310
  CI (99.9%): [3.620, 14.916] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.901 ops/ms
# Warmup Iteration   2: 8.529 ops/ms
# Warmup Iteration   3: 9.462 ops/ms
Iteration   1: 9.635 ops/ms
Iteration   2: 9.688 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.628 ±(99.9%) 1.171 ops/ms [Average]
  (min, avg, max) = (9.561, 9.628, 9.688), stdev = 0.064
  CI (99.9%): [8.457, 10.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.844 ops/ms
# Warmup Iteration   3: 8.988 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.396 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.523 ±(99.9%) 4.173 ops/ms [Average]
  (min, avg, max) = (9.387, 9.523, 9.787), stdev = 0.229
  CI (99.9%): [5.351, 13.696] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 7.977 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.254 ±(99.9%) 2.691 ops/ms [Average]
  (min, avg, max) = (8.149, 8.254, 8.423), stdev = 0.148
  CI (99.9%): [5.563, 10.946] (assumes normal distribution)


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
# Warmup Iteration   1: 9.946 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
Iteration   1: 3.368 ±(99.9%) 0.004 ms/op
Iteration   2: 3.298 ±(99.9%) 0.011 ms/op
Iteration   3: 3.390 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.352 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.298, 3.352, 3.390), stdev = 0.048
  CI (99.9%): [2.472, 4.232] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.340 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.009 ms/op
Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
Iteration   3: 3.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.206 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.145, 3.206, 3.247), stdev = 0.054
  CI (99.9%): [2.216, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 8.257 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.004 ms/op
Iteration   1: 3.427 ±(99.9%) 0.010 ms/op
Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
Iteration   3: 3.348 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.368 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.328, 3.368, 3.427), stdev = 0.053
  CI (99.9%): [2.409, 4.327] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.042 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.980 ±(99.9%) 0.006 ms/op
Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
Iteration   3: 3.896 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.930 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.896, 3.930, 3.980), stdev = 0.044
  CI (99.9%): [3.125, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 10.819 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.013 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 23.287 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  23.962 ms/op
                 createUser·p0.9999: 28.119 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.140 ms/op
                 createUser·p0.999:  19.653 ms/op
                 createUser·p0.9999: 23.972 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282563
  mean =      3.396 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9254 
    [ 2.500,  5.000) = 265086 
    [ 5.000,  7.500) = 7255 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     27.615 ms/op
     p(99.9990) =     28.756 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 8.774 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  14.688 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 3.424 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  21.561 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  10.351 ms/op
                 existUser·p0.9999: 25.895 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290936
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10722 
    [ 2.500,  5.000) = 272394 
    [ 5.000,  7.500) = 6792 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     25.392 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.011 ms/op
Iteration   1: 3.506 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  21.649 ms/op
                 getUser·p0.9999: 27.160 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   2: 3.431 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.837 ms/op
                 getUser·p0.999:  21.651 ms/op
                 getUser·p0.9999: 25.079 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  18.884 ms/op
                 getUser·p0.9999: 26.497 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276487
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18798 
    [ 2.500,  5.000) = 248773 
    [ 5.000,  7.500) = 7805 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     20.988 ms/op
     p(99.9900) =     26.586 ms/op
     p(99.9990) =     28.057 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 10.819 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.015 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.839 ms/op
                 listUser·p0.999:  22.275 ms/op
                 listUser·p0.9999: 25.544 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 4.003 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.804 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 17.696 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237072
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 226754 
    [ 5.000,  7.500) = 8056 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.285 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     24.399 ms/op
     p(99.9990) =     26.137 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.268 ± 5.648  ops/ms
ClientPb.existUser                       thrpt       3   9.628 ± 1.171  ops/ms
ClientPb.getUser                         thrpt       3   9.523 ± 4.173  ops/ms
ClientPb.listUser                        thrpt       3   8.254 ± 2.691  ops/ms
ClientPb.createUser                       avgt       3   3.352 ± 0.880   ms/op
ClientPb.existUser                        avgt       3   3.206 ± 0.990   ms/op
ClientPb.getUser                          avgt       3   3.368 ± 0.959   ms/op
ClientPb.listUser                         avgt       3   3.930 ± 0.805   ms/op
ClientPb.createUser                     sample  282563   3.396 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.345           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.786           ms/op
ClientPb.existUser                      sample  290936   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.827           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  276487   3.473 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.586           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.115           ms/op
ClientPb.listUser                       sample  237072   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.873           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.285           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.598           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.399           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
