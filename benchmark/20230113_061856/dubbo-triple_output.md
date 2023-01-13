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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 6.406 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 9.598 ops/ms
Iteration   3: 9.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.824 ±(99.9%) 3.577 ops/ms [Average]
  (min, avg, max) = (9.598, 9.824, 9.945), stdev = 0.196
  CI (99.9%): [6.247, 13.402] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 9.457 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.556 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.580 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (10.526, 10.580, 10.658), stdev = 0.069
  CI (99.9%): [9.318, 11.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ops/ms
# Warmup Iteration   2: 9.574 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.293 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.923 ±(99.9%) 7.872 ops/ms [Average]
  (min, avg, max) = (9.449, 9.923, 10.293), stdev = 0.431
  CI (99.9%): [2.051, 17.795] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.534 ops/ms
# Warmup Iteration   2: 7.980 ops/ms
# Warmup Iteration   3: 8.614 ops/ms
Iteration   1: 8.648 ops/ms
Iteration   2: 8.427 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.505 ±(99.9%) 2.260 ops/ms [Average]
  (min, avg, max) = (8.427, 8.505, 8.648), stdev = 0.124
  CI (99.9%): [6.245, 10.764] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.842 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.004 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
Iteration   3: 3.111 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 2.018 ms/op [Average]
  (min, avg, max) = (3.111, 3.238, 3.312), stdev = 0.111
  CI (99.9%): [1.220, 5.256] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.324 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.002 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
Iteration   3: 3.155 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.107 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (3.058, 3.107, 3.155), stdev = 0.049
  CI (99.9%): [2.221, 3.993] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.640 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.135 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.149 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.135, 3.149, 3.159), stdev = 0.012
  CI (99.9%): [2.922, 3.377] (assumes normal distribution)


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
# Warmup Iteration   1: 9.028 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.004 ms/op
Iteration   1: 3.696 ±(99.9%) 0.006 ms/op
Iteration   2: 3.716 ±(99.9%) 0.005 ms/op
Iteration   3: 3.733 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.715 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.696, 3.715, 3.733), stdev = 0.019
  CI (99.9%): [3.373, 4.057] (assumes normal distribution)


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
# Warmup Iteration   1: 7.385 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 20.181 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  15.200 ms/op
                 createUser·p0.9999: 22.156 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  14.825 ms/op
                 createUser·p0.9999: 20.250 ms/op
                 createUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304005
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16130 
    [ 2.500,  5.000) = 280185 
    [ 5.000,  7.500) = 6490 
    [ 7.500, 10.000) = 574 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     21.253 ms/op
     p(99.9990) =     22.772 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 6.694 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.860 ms/op
                 existUser·p0.9999: 20.902 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.163 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  11.929 ms/op
                 existUser·p0.9999: 26.011 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 21.818 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307207
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28000 
    [ 2.500,  5.000) = 275010 
    [ 5.000,  7.500) = 3511 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     10.901 ms/op
     p(99.9900) =     25.208 ms/op
     p(99.9990) =     26.774 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 7.489 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  8.888 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.643 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299094
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12577 
    [ 2.500,  5.000) = 280044 
    [ 5.000,  7.500) = 5653 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     15.526 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     30.279 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 8.683 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.011 ms/op
Iteration   1: 3.702 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.541 ms/op
                 listUser·p0.9999: 19.553 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.671 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.695 ms/op
                 listUser·p0.9999: 19.171 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  11.960 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259467
  mean =      3.697 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 252472 
    [ 5.000,  7.500) = 4975 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     20.369 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.824 ± 3.577  ops/ms
ClientPb.existUser                       thrpt       3  10.580 ± 1.262  ops/ms
ClientPb.getUser                         thrpt       3   9.923 ± 7.872  ops/ms
ClientPb.listUser                        thrpt       3   8.505 ± 2.260  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 2.018   ms/op
ClientPb.existUser                        avgt       3   3.107 ± 0.886   ms/op
ClientPb.getUser                          avgt       3   3.149 ± 0.227   ms/op
ClientPb.listUser                         avgt       3   3.715 ± 0.342   ms/op
ClientPb.createUser                     sample  304005   3.154 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.229           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.893           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.253           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.036           ms/op
ClientPb.existUser                      sample  307207   3.123 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.901           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.208           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  299094   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.799           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.200           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.540           ms/op
ClientPb.listUser                       sample  259467   3.697 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.742           ms/op
