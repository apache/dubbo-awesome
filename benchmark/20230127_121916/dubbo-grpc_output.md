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
# Warmup Iteration   1: 4.412 ops/ms
# Warmup Iteration   2: 8.965 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.263 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (10.086, 10.263, 10.379), stdev = 0.156
  CI (99.9%): [7.419, 13.108] (assumes normal distribution)


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
# Warmup Iteration   1: 7.761 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 10.618 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.481 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (10.435, 10.481, 10.565), stdev = 0.073
  CI (99.9%): [9.152, 11.811] (assumes normal distribution)


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
# Warmup Iteration   1: 7.021 ops/ms
# Warmup Iteration   2: 10.221 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 10.170 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.228 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (10.106, 10.228, 10.409), stdev = 0.160
  CI (99.9%): [7.311, 13.145] (assumes normal distribution)


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
# Warmup Iteration   1: 6.057 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.324 ops/ms
Iteration   2: 8.053 ops/ms
Iteration   3: 7.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.003 ±(99.9%) 6.374 ops/ms [Average]
  (min, avg, max) = (7.631, 8.003, 8.324), stdev = 0.349
  CI (99.9%): [1.628, 14.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.010 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.180 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.171, 3.180, 3.191), stdev = 0.010
  CI (99.9%): [2.996, 3.363] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.069 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.051 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.030, 3.051, 3.069), stdev = 0.020
  CI (99.9%): [2.686, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
Iteration   3: 3.159 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.148, 3.158, 3.167), stdev = 0.010
  CI (99.9%): [2.981, 3.334] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.574 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.021 ms/op
Iteration   1: 4.190 ±(99.9%) 0.009 ms/op
Iteration   2: 4.019 ±(99.9%) 0.007 ms/op
Iteration   3: 4.069 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.093 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (4.019, 4.093, 4.190), stdev = 0.088
  CI (99.9%): [2.487, 5.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 12.366 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.374 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.835 ms/op
                 createUser·p0.9999: 16.971 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.115 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.091 ms/op
                 createUser·p0.9999: 31.543 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304140
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16919 
    [ 2.500,  5.000) = 285871 
    [ 5.000,  7.500) = 891 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.747 ms/op
     p(99.9900) =     30.414 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.355 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.679 ms/op
                 existUser·p0.9999: 13.577 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.415 ms/op
                 existUser·p0.9999: 16.462 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 18.145 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310916
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1937 
    [ 1.250,  2.500) = 28730 
    [ 2.500,  3.750) = 244872 
    [ 3.750,  5.000) = 34224 
    [ 5.000,  6.250) = 677 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.350 ms/op
     p(99.9900) =     16.086 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.006 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  10.873 ms/op
                 getUser·p0.9999: 22.156 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.116 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.441 ms/op
                 getUser·p0.9999: 15.399 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.509 ms/op
                 getUser·p0.999:  6.997 ms/op
                 getUser·p0.9999: 22.246 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303022
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16392 
    [ 2.500,  5.000) = 285113 
    [ 5.000,  7.500) = 1123 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     22.066 ms/op
     p(99.9990) =     22.797 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.754 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 15.739 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   2: 4.162 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.468 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 24.858 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 4.020 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.827 ms/op
                 listUser·p0.999:  24.179 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234952
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3608 
    [ 2.500,  5.000) = 197399 
    [ 5.000,  7.500) = 32527 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     28.000 ms/op
     p(99.9990) =     29.870 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.263 ± 2.845  ops/ms
ClientGrpc.existUser                       thrpt       3  10.481 ± 1.329  ops/ms
ClientGrpc.getUser                         thrpt       3  10.228 ± 2.917  ops/ms
ClientGrpc.listUser                        thrpt       3   8.003 ± 6.374  ops/ms
ClientGrpc.createUser                       avgt       3   3.180 ± 0.184   ms/op
ClientGrpc.existUser                        avgt       3   3.051 ± 0.365   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.177   ms/op
ClientGrpc.listUser                         avgt       3   4.093 ± 1.605   ms/op
ClientGrpc.createUser                     sample  304140   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.374           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.747           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.276           ms/op
ClientGrpc.existUser                      sample  310916   3.088 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.355           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.350           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.086           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  303022   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.647           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.066           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  234952   4.089 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.468           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.483           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.966           ms/op
