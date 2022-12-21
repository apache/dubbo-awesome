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
# Warmup Iteration   1: 2.674 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 7.476 ops/ms
Iteration   1: 7.743 ops/ms
Iteration   2: 7.573 ops/ms
Iteration   3: 7.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.626 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (7.563, 7.626, 7.743), stdev = 0.101
  CI (99.9%): [5.781, 9.471] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ops/ms
# Warmup Iteration   2: 7.446 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.982 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (7.925, 7.982, 8.018), stdev = 0.050
  CI (99.9%): [7.066, 8.898] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ops/ms
# Warmup Iteration   2: 6.746 ops/ms
# Warmup Iteration   3: 7.371 ops/ms
Iteration   1: 7.312 ops/ms
Iteration   2: 7.407 ops/ms
Iteration   3: 7.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.294 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (7.163, 7.294, 7.407), stdev = 0.123
  CI (99.9%): [5.052, 9.536] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ops/ms
# Warmup Iteration   2: 5.167 ops/ms
# Warmup Iteration   3: 5.875 ops/ms
Iteration   1: 6.077 ops/ms
Iteration   2: 5.962 ops/ms
Iteration   3: 6.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.059 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (5.962, 6.059, 6.139), stdev = 0.090
  CI (99.9%): [4.425, 7.693] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.616 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.009 ms/op
Iteration   1: 4.193 ±(99.9%) 0.004 ms/op
Iteration   2: 4.352 ±(99.9%) 0.003 ms/op
Iteration   3: 4.158 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.234 ±(99.9%) 1.890 ms/op [Average]
  (min, avg, max) = (4.158, 4.234, 4.352), stdev = 0.104
  CI (99.9%): [2.344, 6.125] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.589 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.002 ms/op
Iteration   1: 4.058 ±(99.9%) 0.005 ms/op
Iteration   2: 4.108 ±(99.9%) 0.003 ms/op
Iteration   3: 4.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.089 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.058, 4.089, 4.108), stdev = 0.027
  CI (99.9%): [3.595, 4.583] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.003 ms/op
Iteration   1: 4.150 ±(99.9%) 0.003 ms/op
Iteration   2: 4.322 ±(99.9%) 0.003 ms/op
Iteration   3: 4.281 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.251 ±(99.9%) 1.645 ms/op [Average]
  (min, avg, max) = (4.150, 4.251, 4.322), stdev = 0.090
  CI (99.9%): [2.606, 5.896] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.751 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.341 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.414 ±(99.9%) 0.023 ms/op
Iteration   1: 5.111 ±(99.9%) 0.013 ms/op
Iteration   2: 5.308 ±(99.9%) 0.017 ms/op
Iteration   3: 5.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.150 ±(99.9%) 2.614 ms/op [Average]
  (min, avg, max) = (5.030, 5.150, 5.308), stdev = 0.143
  CI (99.9%): [2.536, 7.763] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.566 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.012 ms/op
Iteration   1: 4.196 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  12.348 ms/op
                 createUser·p0.9999: 30.105 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  12.430 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 4.157 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.634 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229388
  mean =      4.185 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4473 
    [ 2.500,  5.000) = 186592 
    [ 5.000,  7.500) = 36645 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     12.200 ms/op
     p(99.9900) =     29.432 ms/op
     p(99.9990) =     30.511 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.036 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.012 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  8.899 ms/op
                 existUser·p0.9999: 16.524 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   6.640 ms/op
                 existUser·p0.999:  11.057 ms/op
                 existUser·p0.9999: 18.943 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   3: 4.176 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  11.396 ms/op
                 existUser·p0.9999: 21.770 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236880
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6078 
    [ 2.500,  5.000) = 195969 
    [ 5.000,  7.500) = 33893 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     19.294 ms/op
     p(99.9990) =     22.094 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.217 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.013 ms/op
Iteration   1: 4.233 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 15.747 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 4.269 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 20.300 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   3: 4.534 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 21.922 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221186
  mean =      4.341 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3066 
    [ 2.500,  5.000) = 169335 
    [ 5.000,  7.500) = 46871 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     12.957 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     22.463 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 7.136 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.237 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.020 ms/op
Iteration   1: 5.482 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  22.007 ms/op
                 listUser·p0.9999: 26.872 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 5.488 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 22.255 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 5.686 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.873 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  20.975 ms/op
                 listUser·p0.9999: 28.976 ms/op
                 listUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172998
  mean =      5.550 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 254 
    [ 2.500,  5.000) = 76689 
    [ 5.000,  7.500) = 76143 
    [ 7.500, 10.000) = 17163 
    [10.000, 12.500) = 1994 
    [12.500, 15.000) = 373 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     27.456 ms/op
     p(99.9990) =     29.994 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.626 ± 1.845  ops/ms
ClientGrpc.existUser                       thrpt       3   7.982 ± 0.916  ops/ms
ClientGrpc.getUser                         thrpt       3   7.294 ± 2.242  ops/ms
ClientGrpc.listUser                        thrpt       3   6.059 ± 1.634  ops/ms
ClientGrpc.createUser                       avgt       3   4.234 ± 1.890   ms/op
ClientGrpc.existUser                        avgt       3   4.089 ± 0.494   ms/op
ClientGrpc.getUser                          avgt       3   4.251 ± 1.645   ms/op
ClientGrpc.listUser                         avgt       3   5.150 ± 2.614   ms/op
ClientGrpc.createUser                     sample  229388   4.185 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.045           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.200           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.432           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.605           ms/op
ClientGrpc.existUser                      sample  236880   4.052 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.570           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.294           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  221186   4.341 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.861           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.957           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.447           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  172998   5.550 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.247           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.447           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.456           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
