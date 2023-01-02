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
# Warmup Iteration   1: 2.536 ops/ms
# Warmup Iteration   2: 6.219 ops/ms
# Warmup Iteration   3: 9.101 ops/ms
Iteration   1: 9.875 ops/ms
Iteration   2: 10.012 ops/ms
Iteration   3: 10.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.065 ±(99.9%) 4.050 ops/ms [Average]
  (min, avg, max) = (9.875, 10.065, 10.309), stdev = 0.222
  CI (99.9%): [6.015, 14.115] (assumes normal distribution)


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
# Warmup Iteration   1: 3.258 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.095 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.204 ±(99.9%) 6.005 ops/ms [Average]
  (min, avg, max) = (9.944, 10.204, 10.574), stdev = 0.329
  CI (99.9%): [4.199, 16.210] (assumes normal distribution)


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
# Warmup Iteration   1: 3.354 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.089 ops/ms
Iteration   3: 9.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.936 ±(99.9%) 3.243 ops/ms [Average]
  (min, avg, max) = (9.741, 9.936, 10.089), stdev = 0.178
  CI (99.9%): [6.693, 13.179] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.554 ±(99.9%) 4.912 ops/ms [Average]
  (min, avg, max) = (8.315, 8.554, 8.846), stdev = 0.269
  CI (99.9%): [3.642, 13.467] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.624 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.004 ms/op
Iteration   1: 3.170 ±(99.9%) 0.002 ms/op
Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
Iteration   3: 3.170 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.165 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.155, 3.165, 3.170), stdev = 0.009
  CI (99.9%): [3.008, 3.323] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.001 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.021 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.000, 3.021, 3.051), stdev = 0.026
  CI (99.9%): [2.546, 3.497] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.237 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.005 ms/op
Iteration   1: 3.276 ±(99.9%) 0.005 ms/op
Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
Iteration   3: 3.248 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.241, 3.255, 3.276), stdev = 0.018
  CI (99.9%): [2.920, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 9.020 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.006 ms/op
Iteration   1: 3.669 ±(99.9%) 0.009 ms/op
Iteration   2: 3.695 ±(99.9%) 0.007 ms/op
Iteration   3: 3.664 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.676 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.664, 3.676, 3.695), stdev = 0.017
  CI (99.9%): [3.375, 3.978] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  18.270 ms/op
                 createUser·p0.9999: 23.969 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  14.025 ms/op
                 createUser·p0.9999: 22.873 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  14.760 ms/op
                 createUser·p0.9999: 18.212 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299326
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21070 
    [ 2.500,  5.000) = 272741 
    [ 5.000,  7.500) = 4506 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     15.052 ms/op
     p(99.9900) =     22.874 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.295 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  12.859 ms/op
                 existUser·p0.9999: 18.711 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 20.306 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.238 ms/op
                 existUser·p0.9999: 20.431 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315658
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14655 
    [ 2.500,  5.000) = 294967 
    [ 5.000,  7.500) = 5341 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     11.939 ms/op
     p(99.9900) =     20.167 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 7.261 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 26.551 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.273 ms/op
                 getUser·p0.95:   3.474 ms/op
                 getUser·p0.99:   4.109 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 27.128 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  14.609 ms/op
                 getUser·p0.9999: 19.229 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 307107
  mean =      3.124 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9477 
    [ 2.500,  5.000) = 291448 
    [ 5.000,  7.500) = 5165 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     26.495 ms/op
     p(99.9990) =     30.184 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 9.512 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 21.384 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.754 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 15.007 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   3: 3.768 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.878 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254269
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 246451 
    [ 5.000,  7.500) = 5911 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     22.032 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.065 ± 4.050  ops/ms
ClientPb.existUser                       thrpt       3  10.204 ± 6.005  ops/ms
ClientPb.getUser                         thrpt       3   9.936 ± 3.243  ops/ms
ClientPb.listUser                        thrpt       3   8.554 ± 4.912  ops/ms
ClientPb.createUser                       avgt       3   3.165 ± 0.157   ms/op
ClientPb.existUser                        avgt       3   3.021 ± 0.475   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.676 ± 0.302   ms/op
ClientPb.createUser                     sample  299326   3.204 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.233           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.874           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.936           ms/op
ClientPb.existUser                      sample  315658   3.040 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.939           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.167           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.168           ms/op
ClientPb.getUser                        sample  307107   3.124 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.303           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.495           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  254269   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
