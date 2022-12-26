# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 9.008 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 10.225 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.150 ±(99.9%) 3.741 ops/ms [Average]
  (min, avg, max) = (9.918, 10.150, 10.307), stdev = 0.205
  CI (99.9%): [6.409, 13.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.203 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.544 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (10.476, 10.544, 10.596), stdev = 0.061
  CI (99.9%): [9.427, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.682 ops/ms
# Warmup Iteration   2: 10.027 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.314 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (10.263, 10.314, 10.365), stdev = 0.051
  CI (99.9%): [9.382, 11.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.219 ops/ms
# Warmup Iteration   2: 7.661 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 7.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.947 ±(99.9%) 2.391 ops/ms [Average]
  (min, avg, max) = (7.807, 7.947, 8.066), stdev = 0.131
  CI (99.9%): [5.556, 10.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.472 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.144 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.185 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.152 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.126, 3.152, 3.185), stdev = 0.030
  CI (99.9%): [2.603, 3.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.976, 2.995, 3.012), stdev = 0.018
  CI (99.9%): [2.662, 3.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.394 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.001 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.110 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.091, 3.110, 3.145), stdev = 0.030
  CI (99.9%): [2.562, 3.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.040 ms/op
Iteration   1: 4.026 ±(99.9%) 0.005 ms/op
Iteration   2: 4.017 ±(99.9%) 0.024 ms/op
Iteration   3: 4.007 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.017 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (4.007, 4.017, 4.026), stdev = 0.009
  CI (99.9%): [3.852, 4.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.085 ms/op
                 createUser·p0.9999: 13.074 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.770 ms/op
                 createUser·p0.9999: 21.599 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301260
  mean =      3.186 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28200 
    [ 2.500,  5.000) = 269555 
    [ 5.000,  7.500) = 2911 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     21.025 ms/op
     p(99.9990) =     22.281 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.548 ms/op
                 existUser·p0.9999: 13.031 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.062 ms/op
                 existUser·p0.9999: 15.221 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325829
  mean =      2.947 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3217 
    [ 1.250,  2.500) = 50867 
    [ 2.500,  3.750) = 250667 
    [ 3.750,  5.000) = 19890 
    [ 5.000,  6.250) = 576 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.612 ms/op
     p(99.9900) =     17.545 ms/op
     p(99.9990) =     18.718 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.829 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.512 ms/op
                 getUser·p0.9999: 14.729 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.076 ms/op
                 getUser·p0.9999: 13.876 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.267 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.433 ms/op
                 getUser·p0.9999: 23.182 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307477
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25339 
    [ 2.500,  5.000) = 280870 
    [ 5.000,  7.500) = 967 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.267 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.443 ms/op
     p(99.9900) =     21.652 ms/op
     p(99.9990) =     23.618 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.077 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.564 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   16.597 ms/op

Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.936 ms/op
                 listUser·p0.9999: 21.759 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 27.064 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240117
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1827 
    [ 2.500,  5.000) = 214151 
    [ 5.000,  7.500) = 22763 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     15.839 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.341 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.150 ± 3.741  ops/ms
ClientGrpc.existUser                       thrpt       3  10.544 ± 1.117  ops/ms
ClientGrpc.getUser                         thrpt       3  10.314 ± 0.933  ops/ms
ClientGrpc.listUser                        thrpt       3   7.947 ± 2.391  ops/ms
ClientGrpc.createUser                       avgt       3   3.152 ± 0.548   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.334   ms/op
ClientGrpc.getUser                          avgt       3   3.110 ± 0.548   ms/op
ClientGrpc.listUser                         avgt       3   4.017 ± 0.165   ms/op
ClientGrpc.createUser                     sample  301260   3.186 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.466           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.025           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.413           ms/op
ClientGrpc.existUser                      sample  325829   2.947 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.612           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.545           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.907           ms/op
ClientGrpc.getUser                        sample  307477   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.267           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.443           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.652           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  240117   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.839           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
