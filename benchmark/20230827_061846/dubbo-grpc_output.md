# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 7.298 ops/ms
# Warmup Iteration   3: 8.899 ops/ms
Iteration   1: 9.424 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.453 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (9.410, 9.453, 9.525), stdev = 0.063
  CI (99.9%): [8.303, 10.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.197 ops/ms
# Warmup Iteration   2: 9.380 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.389 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.408 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (10.209, 10.408, 10.625), stdev = 0.209
  CI (99.9%): [6.598, 14.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ops/ms
# Warmup Iteration   2: 9.828 ops/ms
# Warmup Iteration   3: 10.242 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 9.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.021 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (9.768, 10.021, 10.306), stdev = 0.271
  CI (99.9%): [5.085, 14.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 7.459 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 7.826 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (7.826, 7.926, 8.041), stdev = 0.109
  CI (99.9%): [5.945, 9.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.975 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.259 ±(99.9%) 0.003 ms/op
Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 1.520 ms/op [Average]
  (min, avg, max) = (3.109, 3.163, 3.259), stdev = 0.083
  CI (99.9%): [1.644, 4.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 2.935 ±(99.9%) 0.004 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.953 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.935, 2.953, 2.962), stdev = 0.016
  CI (99.9%): [2.667, 3.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.113 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.088, 3.113, 3.127), stdev = 0.022
  CI (99.9%): [2.712, 3.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.018 ms/op
Iteration   1: 4.002 ±(99.9%) 0.016 ms/op
Iteration   2: 4.022 ±(99.9%) 0.018 ms/op
Iteration   3: 4.040 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (4.002, 4.021, 4.040), stdev = 0.019
  CI (99.9%): [3.667, 4.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 12.348 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 14.412 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  9.874 ms/op
                 createUser·p0.9999: 21.848 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309179
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22882 
    [ 2.500,  5.000) = 283658 
    [ 5.000,  7.500) = 2031 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      8.844 ms/op
     p(99.9900) =     21.138 ms/op
     p(99.9990) =     22.848 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 13.214 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.812 ms/op
                 existUser·p0.9999: 18.225 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   3: 3.515 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  13.565 ms/op
                 existUser·p0.9999: 17.717 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291777
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 713 
    [ 1.250,  2.500) = 16668 
    [ 2.500,  3.750) = 225438 
    [ 3.750,  5.000) = 40161 
    [ 5.000,  6.250) = 5561 
    [ 6.250,  7.500) = 1627 
    [ 7.500,  8.750) = 896 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     17.442 ms/op
     p(99.9990) =     19.538 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
Iteration   1: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  11.258 ms/op
                 getUser·p0.9999: 13.576 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 15.389 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  10.785 ms/op
                 getUser·p0.9999: 18.773 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292161
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 547 
    [ 1.250,  2.500) = 11865 
    [ 2.500,  3.750) = 244348 
    [ 3.750,  5.000) = 28523 
    [ 5.000,  6.250) = 2688 
    [ 6.250,  7.500) = 1603 
    [ 7.500,  8.750) = 1337 
    [ 8.750, 10.000) = 697 
    [10.000, 11.250) = 253 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     11.302 ms/op
     p(99.9900) =     17.688 ms/op
     p(99.9990) =     19.767 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.442 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.099 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 16.816 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  20.906 ms/op
                 listUser·p0.9999: 24.554 ms/op
                 listUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234998
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2932 
    [ 2.500,  5.000) = 204219 
    [ 5.000,  7.500) = 25898 
    [ 7.500, 10.000) = 1419 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     23.478 ms/op
     p(99.9990) =     24.848 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.453 ± 1.150  ops/ms
ClientGrpc.existUser                       thrpt       3  10.408 ± 3.810  ops/ms
ClientGrpc.getUser                         thrpt       3  10.021 ± 4.936  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 1.980  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 1.520   ms/op
ClientGrpc.existUser                        avgt       3   2.953 ± 0.285   ms/op
ClientGrpc.getUser                          avgt       3   3.113 ± 0.402   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 0.354   ms/op
ClientGrpc.createUser                     sample  309179   3.104 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.844           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.138           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.265           ms/op
ClientGrpc.existUser                      sample  291777   3.293 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.769           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.178           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.414           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.436           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.442           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  292161   3.283 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.302           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.688           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  234998   4.088 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.037           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.478           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.969           ms/op
