# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 9.508 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.446 ±(99.9%) 4.124 ops/ms [Average]
  (min, avg, max) = (10.222, 10.446, 10.674), stdev = 0.226
  CI (99.9%): [6.322, 14.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ops/ms
# Warmup Iteration   2: 10.499 ops/ms
# Warmup Iteration   3: 10.956 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.991 ops/ms
Iteration   3: 10.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.863 ±(99.9%) 4.109 ops/ms [Average]
  (min, avg, max) = (10.603, 10.863, 10.996), stdev = 0.225
  CI (99.9%): [6.755, 14.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.608 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.459 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (10.360, 10.459, 10.605), stdev = 0.129
  CI (99.9%): [8.103, 12.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.506 ops/ms
# Warmup Iteration   2: 7.480 ops/ms
# Warmup Iteration   3: 7.609 ops/ms
Iteration   1: 7.529 ops/ms
Iteration   2: 7.903 ops/ms
Iteration   3: 7.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.746 ±(99.9%) 3.542 ops/ms [Average]
  (min, avg, max) = (7.529, 7.746, 7.903), stdev = 0.194
  CI (99.9%): [4.204, 11.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.267 ±(99.9%) 0.002 ms/op
Iteration   2: 3.328 ±(99.9%) 0.002 ms/op
Iteration   3: 3.300 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.298 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (3.267, 3.298, 3.328), stdev = 0.031
  CI (99.9%): [2.734, 3.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.002 ms/op
Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
Iteration   3: 3.227 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.191 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (3.154, 3.191, 3.227), stdev = 0.036
  CI (99.9%): [2.527, 3.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.398 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.002 ms/op
Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
Iteration   3: 3.194 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.233 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.194, 3.233, 3.257), stdev = 0.034
  CI (99.9%): [2.615, 3.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.015 ms/op
Iteration   1: 4.194 ±(99.9%) 0.040 ms/op
Iteration   2: 4.179 ±(99.9%) 0.038 ms/op
Iteration   3: 4.007 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.127 ±(99.9%) 1.895 ms/op [Average]
  (min, avg, max) = (4.007, 4.127, 4.194), stdev = 0.104
  CI (99.9%): [2.232, 6.022] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.006 ms/op
Iteration   1: 3.226 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.515 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.304 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 13.881 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 24.978 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294796
  mean =      3.257 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19115 
    [ 2.500,  5.000) = 274555 
    [ 5.000,  7.500) = 692 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.477 ms/op
     p(99.9900) =     23.610 ms/op
     p(99.9990) =     25.300 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  9.140 ms/op
                 existUser·p0.9999: 11.657 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.960 ms/op
                 existUser·p0.9999: 14.635 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.902 ms/op
                 existUser·p0.9999: 20.738 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308895
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28757 
    [ 2.500,  5.000) = 279043 
    [ 5.000,  7.500) = 693 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     19.009 ms/op
     p(99.9990) =     21.061 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
Iteration   1: 3.262 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.581 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.222 ms/op
                 getUser·p0.9999: 17.931 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.175 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.590 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.948 ms/op
                 getUser·p0.9999: 27.116 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296267
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21053 
    [ 2.500,  5.000) = 274049 
    [ 5.000,  7.500) = 869 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.508 ms/op
     p(99.9900) =     25.103 ms/op
     p(99.9990) =     27.364 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.099 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.013 ms/op
Iteration   1: 4.278 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.604 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  14.111 ms/op
                 listUser·p0.9999: 16.222 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.195 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.182 ms/op
                 listUser·p0.9999: 23.081 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.320 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  18.151 ms/op
                 listUser·p0.9999: 21.306 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225094
  mean =      4.264 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4346 
    [ 2.500,  5.000) = 173790 
    [ 5.000,  7.500) = 45004 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     15.530 ms/op
     p(99.9900) =     22.757 ms/op
     p(99.9990) =     23.347 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.446 ± 4.124  ops/ms
ClientGrpc.existUser                       thrpt       3  10.863 ± 4.109  ops/ms
ClientGrpc.getUser                         thrpt       3  10.459 ± 2.356  ops/ms
ClientGrpc.listUser                        thrpt       3   7.746 ± 3.542  ops/ms
ClientGrpc.createUser                       avgt       3   3.298 ± 0.564   ms/op
ClientGrpc.existUser                        avgt       3   3.191 ± 0.664   ms/op
ClientGrpc.getUser                          avgt       3   3.233 ± 0.618   ms/op
ClientGrpc.listUser                         avgt       3   4.127 ± 1.895   ms/op
ClientGrpc.createUser                     sample  294796   3.257 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.738           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.477           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.610           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.428           ms/op
ClientGrpc.existUser                      sample  308895   3.108 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.146           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.167           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.009           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  296267   3.239 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.581           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.269           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.508           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.103           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.492           ms/op
ClientGrpc.listUser                       sample  225094   4.264 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.604           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.047           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.530           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.757           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
