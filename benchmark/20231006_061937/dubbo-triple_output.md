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
# Warmup Iteration   1: 1.850 ops/ms
# Warmup Iteration   2: 4.211 ops/ms
# Warmup Iteration   3: 7.480 ops/ms
Iteration   1: 7.110 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.534 ±(99.9%) 6.872 ops/ms [Average]
  (min, avg, max) = (7.110, 7.534, 7.829), stdev = 0.377
  CI (99.9%): [0.662, 14.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.664 ops/ms
Iteration   3: 8.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.729 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (8.644, 8.729, 8.878), stdev = 0.130
  CI (99.9%): [6.366, 11.092] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 7.727 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.317 ±(99.9%) 4.909 ops/ms [Average]
  (min, avg, max) = (8.133, 8.317, 8.626), stdev = 0.269
  CI (99.9%): [3.408, 13.226] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 5.717 ops/ms
# Warmup Iteration   3: 6.713 ops/ms
Iteration   1: 7.075 ops/ms
Iteration   2: 6.903 ops/ms
Iteration   3: 6.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.934 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (6.824, 6.934, 7.075), stdev = 0.128
  CI (99.9%): [4.594, 9.274] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 12.693 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.625 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.007 ms/op
Iteration   1: 3.832 ±(99.9%) 0.006 ms/op
Iteration   2: 3.814 ±(99.9%) 0.007 ms/op
Iteration   3: 3.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.841 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (3.814, 3.841, 3.878), stdev = 0.033
  CI (99.9%): [3.241, 4.442] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.374 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.005 ms/op
Iteration   1: 3.723 ±(99.9%) 0.007 ms/op
Iteration   2: 3.732 ±(99.9%) 0.009 ms/op
Iteration   3: 4.066 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.841 ±(99.9%) 3.570 ms/op [Average]
  (min, avg, max) = (3.723, 3.841, 4.066), stdev = 0.196
  CI (99.9%): [0.270, 7.411] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 11.201 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
Iteration   1: 3.915 ±(99.9%) 0.006 ms/op
Iteration   2: 3.829 ±(99.9%) 0.005 ms/op
Iteration   3: 3.752 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.832 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (3.752, 3.832, 3.915), stdev = 0.081
  CI (99.9%): [2.348, 5.316] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.430 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.870 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.956 ±(99.9%) 0.008 ms/op
Iteration   1: 4.305 ±(99.9%) 0.007 ms/op
Iteration   2: 4.431 ±(99.9%) 0.006 ms/op
Iteration   3: 4.446 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.394 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (4.305, 4.394, 4.446), stdev = 0.078
  CI (99.9%): [2.979, 5.809] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.861 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.020 ms/op
Iteration   1: 3.809 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.649 ms/op
                 createUser·p0.99:   8.323 ms/op
                 createUser·p0.999:  15.452 ms/op
                 createUser·p0.9999: 24.124 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.687 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 26.269 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 3.816 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  28.413 ms/op
                 createUser·p0.9999: 32.231 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254562
  mean =      3.770 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4736 
    [ 2.500,  5.000) = 231982 
    [ 5.000,  7.500) = 13599 
    [ 7.500, 10.000) = 2991 
    [10.000, 12.500) = 650 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     30.918 ms/op
     p(99.9990) =     32.664 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.064 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.012 ms/op
Iteration   1: 3.751 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  12.628 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.742 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  21.987 ms/op
                 existUser·p0.9999: 29.867 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 3.694 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   8.540 ms/op
                 existUser·p0.999:  16.404 ms/op
                 existUser·p0.9999: 27.110 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257278
  mean =      3.729 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6916 
    [ 2.500,  5.000) = 229445 
    [ 5.000,  7.500) = 16505 
    [ 7.500, 10.000) = 3273 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     30.189 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 9.802 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.014 ms/op
Iteration   1: 4.337 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  17.343 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.909 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  19.172 ms/op
                 getUser·p0.9999: 27.224 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.975 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  21.843 ms/op
                 getUser·p0.9999: 26.637 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236021
  mean =      4.065 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3848 
    [ 2.500,  5.000) = 197274 
    [ 5.000,  7.500) = 26004 
    [ 7.500, 10.000) = 6794 
    [10.000, 12.500) = 1319 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     19.463 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     27.927 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 16.554 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.698 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.800 ±(99.9%) 0.020 ms/op
Iteration   1: 4.785 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.684 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  23.660 ms/op
                 listUser·p0.9999: 26.519 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.556 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  17.230 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.493 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  19.460 ms/op
                 listUser·p0.9999: 26.404 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208245
  mean =      4.608 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 170453 
    [ 5.000,  7.500) = 28493 
    [ 7.500, 10.000) = 6596 
    [10.000, 12.500) = 1719 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     21.086 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.476 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.534 ± 6.872  ops/ms
ClientPb.existUser                       thrpt       3   8.729 ± 2.363  ops/ms
ClientPb.getUser                         thrpt       3   8.317 ± 4.909  ops/ms
ClientPb.listUser                        thrpt       3   6.934 ± 2.340  ops/ms
ClientPb.createUser                       avgt       3   3.841 ± 0.600   ms/op
ClientPb.existUser                        avgt       3   3.841 ± 3.570   ms/op
ClientPb.getUser                          avgt       3   3.832 ± 1.484   ms/op
ClientPb.listUser                         avgt       3   4.394 ± 1.415   ms/op
ClientPb.createUser                     sample  254562   3.770 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.494           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.536           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.918           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  257278   3.729 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.364           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.377           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  236021   4.065 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.094           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.765           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.463           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  208245   4.608 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.931           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.469           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.086           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.313           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.393           ms/op
