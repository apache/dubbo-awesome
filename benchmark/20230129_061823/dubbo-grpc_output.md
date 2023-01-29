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
# Warmup Iteration   1: 4.399 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.210 ops/ms
Iteration   3: 10.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.185 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (10.151, 10.185, 10.210), stdev = 0.031
  CI (99.9%): [9.623, 10.748] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.532 ops/ms
# Warmup Iteration   2: 10.081 ops/ms
# Warmup Iteration   3: 10.886 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.708 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (10.594, 10.708, 10.832), stdev = 0.119
  CI (99.9%): [8.532, 12.884] (assumes normal distribution)


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
# Warmup Iteration   1: 6.709 ops/ms
# Warmup Iteration   2: 9.981 ops/ms
# Warmup Iteration   3: 10.184 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.273 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.285 ±(99.9%) 2.125 ops/ms [Average]
  (min, avg, max) = (10.174, 10.285, 10.406), stdev = 0.116
  CI (99.9%): [8.159, 12.410] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 7.924 ops/ms
Iteration   3: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.932 ±(99.9%) 0.188 ops/ms [Average]
  (min, avg, max) = (7.924, 7.932, 7.944), stdev = 0.010
  CI (99.9%): [7.744, 8.120] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.002 ms/op
Iteration   1: 3.255 ±(99.9%) 0.006 ms/op
Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (3.113, 3.163, 3.255), stdev = 0.080
  CI (99.9%): [1.710, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.001 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.047 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (2.968, 3.047, 3.113), stdev = 0.074
  CI (99.9%): [1.706, 4.389] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.126, 3.158, 3.175), stdev = 0.028
  CI (99.9%): [2.652, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.007 ms/op
Iteration   1: 3.975 ±(99.9%) 0.019 ms/op
Iteration   2: 3.956 ±(99.9%) 0.040 ms/op
Iteration   3: 3.928 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.928, 3.953, 3.975), stdev = 0.024
  CI (99.9%): [3.516, 4.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.006 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.934 ms/op
                 createUser·p0.9999: 19.656 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.454 ms/op
                 createUser·p0.9999: 18.643 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.168 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  10.650 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303037
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22497 
    [ 2.500,  5.000) = 279640 
    [ 5.000,  7.500) = 585 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     29.678 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.960 ms/op
                 existUser·p0.9999: 12.224 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  12.309 ms/op
                 existUser·p0.9999: 17.737 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.205 ms/op
                 existUser·p0.9999: 16.512 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317897
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45851 
    [ 2.500,  5.000) = 271258 
    [ 5.000,  7.500) = 524 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.039 ms/op
     p(99.9900) =     17.034 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 4.324 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.683 ms/op
                 getUser·p0.9999: 13.265 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.241 ms/op
                 getUser·p0.9999: 15.002 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 15.973 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303803
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 21681 
    [ 2.500,  3.750) = 239590 
    [ 3.750,  5.000) = 41244 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.840 ms/op
     p(99.9900) =     14.700 ms/op
     p(99.9990) =     16.498 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.011 ms/op
Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.280 ms/op
                 listUser·p0.9999: 20.773 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.282 ms/op
                 listUser·p0.9999: 19.821 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.487 ms/op
                 listUser·p0.9999: 22.301 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243472
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2615 
    [ 2.500,  5.000) = 218314 
    [ 5.000,  7.500) = 21468 
    [ 7.500, 10.000) = 670 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.921 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     20.490 ms/op
     p(99.9990) =     23.794 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.185 ± 0.563  ops/ms
ClientGrpc.existUser                       thrpt       3  10.708 ± 2.176  ops/ms
ClientGrpc.getUser                         thrpt       3  10.285 ± 2.125  ops/ms
ClientGrpc.listUser                        thrpt       3   7.932 ± 0.188  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 1.453   ms/op
ClientGrpc.existUser                        avgt       3   3.047 ± 1.342   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 0.437   ms/op
ClientGrpc.createUser                     sample  303037   3.169 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.678           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.080           ms/op
ClientGrpc.existUser                      sample  317897   3.015 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.039           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.034           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.637           ms/op
ClientGrpc.getUser                        sample  303803   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.675           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.840           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.700           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  243472   3.943 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.921           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.490           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
