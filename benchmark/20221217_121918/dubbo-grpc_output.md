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
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 5.732 ops/ms
# Warmup Iteration   3: 7.329 ops/ms
Iteration   1: 7.250 ops/ms
Iteration   2: 7.512 ops/ms
Iteration   3: 7.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.477 ±(99.9%) 3.854 ops/ms [Average]
  (min, avg, max) = (7.250, 7.477, 7.668), stdev = 0.211
  CI (99.9%): [3.623, 11.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 7.247 ops/ms
# Warmup Iteration   3: 7.811 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.839 ±(99.9%) 3.098 ops/ms [Average]
  (min, avg, max) = (7.650, 7.839, 7.980), stdev = 0.170
  CI (99.9%): [4.741, 10.936] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 6.448 ops/ms
# Warmup Iteration   3: 6.864 ops/ms
Iteration   1: 7.251 ops/ms
Iteration   2: 7.444 ops/ms
Iteration   3: 7.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.366 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (7.251, 7.366, 7.444), stdev = 0.101
  CI (99.9%): [5.515, 9.216] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.547 ops/ms
# Warmup Iteration   2: 5.089 ops/ms
# Warmup Iteration   3: 5.698 ops/ms
Iteration   1: 5.971 ops/ms
Iteration   2: 5.893 ops/ms
Iteration   3: 6.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.971 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (5.893, 5.971, 6.050), stdev = 0.078
  CI (99.9%): [4.546, 7.396] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.777 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.496 ±(99.9%) 0.020 ms/op
Iteration   1: 4.452 ±(99.9%) 0.002 ms/op
Iteration   2: 4.348 ±(99.9%) 0.003 ms/op
Iteration   3: 4.376 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.392 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (4.348, 4.392, 4.452), stdev = 0.054
  CI (99.9%): [3.412, 5.371] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.851 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.004 ms/op
Iteration   1: 4.199 ±(99.9%) 0.005 ms/op
Iteration   2: 4.094 ±(99.9%) 0.003 ms/op
Iteration   3: 4.168 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.154 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (4.094, 4.154, 4.199), stdev = 0.054
  CI (99.9%): [3.163, 5.144] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.829 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.015 ms/op
Iteration   1: 4.195 ±(99.9%) 0.004 ms/op
Iteration   2: 4.220 ±(99.9%) 0.004 ms/op
Iteration   3: 4.261 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.225 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (4.195, 4.225, 4.261), stdev = 0.033
  CI (99.9%): [3.619, 4.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.894 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.660 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.444 ±(99.9%) 0.016 ms/op
Iteration   1: 5.312 ±(99.9%) 0.013 ms/op
Iteration   2: 5.557 ±(99.9%) 0.045 ms/op
Iteration   3: 5.586 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.485 ±(99.9%) 2.743 ms/op [Average]
  (min, avg, max) = (5.312, 5.485, 5.586), stdev = 0.150
  CI (99.9%): [2.742, 8.228] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.483 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.013 ms/op
Iteration   1: 4.356 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 16.573 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.402 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.407 ms/op
                 createUser·p0.999:  12.339 ms/op
                 createUser·p0.9999: 17.406 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 4.360 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  11.803 ms/op
                 createUser·p0.9999: 17.913 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224877
  mean =      4.270 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 2794 
    [ 2.500,  3.750) = 69114 
    [ 3.750,  5.000) = 111510 
    [ 5.000,  6.250) = 33560 
    [ 6.250,  7.500) = 5286 
    [ 7.500,  8.750) = 1357 
    [ 8.750, 10.000) = 581 
    [10.000, 11.250) = 318 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     17.368 ms/op
     p(99.9990) =     18.629 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 5.941 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  12.542 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.988 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 29.327 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   3: 4.139 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  13.473 ms/op
                 existUser·p0.9999: 22.782 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237667
  mean =      4.041 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9418 
    [ 2.500,  5.000) = 196312 
    [ 5.000,  7.500) = 29656 
    [ 7.500, 10.000) = 1723 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     27.999 ms/op
     p(99.9990) =     29.581 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 6.094 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
Iteration   1: 4.183 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.878 ms/op
                 getUser·p0.999:  11.546 ms/op
                 getUser·p0.9999: 20.131 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 4.150 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  12.217 ms/op
                 getUser·p0.9999: 40.782 ms/op
                 getUser·p1.00:   41.288 ms/op

Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   6.972 ms/op
                 getUser·p0.999:  12.023 ms/op
                 getUser·p0.9999: 34.946 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231291
  mean =      4.149 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 198790 
    [ 5.000, 10.000) = 32009 
    [10.000, 15.000) = 364 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 19 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     11.988 ms/op
     p(99.9900) =     40.231 ms/op
     p(99.9990) =     41.116 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.757 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.021 ms/op
Iteration   1: 5.491 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  18.924 ms/op
                 listUser·p0.9999: 23.288 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 5.366 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  20.059 ms/op
                 listUser·p0.9999: 35.720 ms/op
                 listUser·p1.00:   42.533 ms/op

Iteration   3: 5.372 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  25.816 ms/op
                 listUser·p0.9999: 33.819 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177434
  mean =      5.409 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 84583 
    [ 5.000, 10.000) = 90503 
    [10.000, 15.000) = 1980 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 104 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.464 ms/op
     p(99.9000) =     20.990 ms/op
     p(99.9900) =     34.882 ms/op
     p(99.9990) =     38.778 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.477 ± 3.854  ops/ms
ClientGrpc.existUser                       thrpt       3   7.839 ± 3.098  ops/ms
ClientGrpc.getUser                         thrpt       3   7.366 ± 1.850  ops/ms
ClientGrpc.listUser                        thrpt       3   5.971 ± 1.425  ops/ms
ClientGrpc.createUser                       avgt       3   4.392 ± 0.979   ms/op
ClientGrpc.existUser                        avgt       3   4.154 ± 0.991   ms/op
ClientGrpc.getUser                          avgt       3   4.225 ± 0.607   ms/op
ClientGrpc.listUser                         avgt       3   5.485 ± 2.743   ms/op
ClientGrpc.createUser                     sample  224877   4.270 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.402           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.009           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  237667   4.041 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.938           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.718           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.632           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.999           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.721           ms/op
ClientGrpc.getUser                        sample  231291   4.149 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.940           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.676           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          40.231           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          41.288           ms/op
ClientGrpc.listUser                       sample  177434   5.409 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.822           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.464           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.882           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          42.533           ms/op
