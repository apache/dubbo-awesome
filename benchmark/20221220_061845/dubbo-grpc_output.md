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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 7.410 ops/ms
Iteration   1: 7.546 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.960 ±(99.9%) 6.549 ops/ms [Average]
  (min, avg, max) = (7.546, 7.960, 8.186), stdev = 0.359
  CI (99.9%): [1.410, 14.509] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.876 ops/ms
# Warmup Iteration   2: 7.678 ops/ms
# Warmup Iteration   3: 8.253 ops/ms
Iteration   1: 8.397 ops/ms
Iteration   2: 8.474 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.419 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (8.387, 8.419, 8.474), stdev = 0.047
  CI (99.9%): [7.554, 9.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.904 ops/ms
# Warmup Iteration   2: 7.455 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 7.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.835 ±(99.9%) 4.831 ops/ms [Average]
  (min, avg, max) = (7.540, 7.835, 8.054), stdev = 0.265
  CI (99.9%): [3.004, 12.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.256 ops/ms
# Warmup Iteration   2: 5.922 ops/ms
# Warmup Iteration   3: 6.214 ops/ms
Iteration   1: 6.246 ops/ms
Iteration   2: 6.334 ops/ms
Iteration   3: 6.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.306 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (6.246, 6.306, 6.338), stdev = 0.052
  CI (99.9%): [5.361, 7.252] (assumes normal distribution)


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
# Warmup Iteration   1: 5.939 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.910 ±(99.9%) 0.003 ms/op
Iteration   2: 4.118 ±(99.9%) 0.004 ms/op
Iteration   3: 3.911 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.980 ±(99.9%) 2.181 ms/op [Average]
  (min, avg, max) = (3.910, 3.980, 4.118), stdev = 0.120
  CI (99.9%): [1.799, 6.160] (assumes normal distribution)


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
# Warmup Iteration   1: 5.934 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.003 ms/op
Iteration   1: 4.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.800 ±(99.9%) 0.002 ms/op
Iteration   3: 3.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.923 ±(99.9%) 2.336 ms/op [Average]
  (min, avg, max) = (3.800, 3.923, 4.055), stdev = 0.128
  CI (99.9%): [1.586, 6.259] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.003 ms/op
Iteration   1: 4.352 ±(99.9%) 0.003 ms/op
Iteration   2: 4.235 ±(99.9%) 0.003 ms/op
Iteration   3: 4.222 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.269 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (4.222, 4.269, 4.352), stdev = 0.072
  CI (99.9%): [2.964, 5.574] (assumes normal distribution)


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
# Warmup Iteration   1: 7.682 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.730 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.408 ±(99.9%) 0.029 ms/op
Iteration   1: 5.351 ±(99.9%) 0.025 ms/op
Iteration   2: 5.095 ±(99.9%) 0.018 ms/op
Iteration   3: 5.116 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.187 ±(99.9%) 2.596 ms/op [Average]
  (min, avg, max) = (5.095, 5.187, 5.351), stdev = 0.142
  CI (99.9%): [2.591, 7.784] (assumes normal distribution)


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
# Warmup Iteration   1: 6.456 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.015 ms/op
Iteration   1: 4.170 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  10.380 ms/op
                 createUser·p0.9999: 21.517 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  16.079 ms/op
                 createUser·p0.9999: 24.545 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 4.170 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 24.401 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233111
  mean =      4.119 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4215 
    [ 2.500,  5.000) = 193472 
    [ 5.000,  7.500) = 34002 
    [ 7.500, 10.000) = 1040 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     12.106 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     31.632 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
Iteration   1: 3.901 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  12.287 ms/op
                 existUser·p0.9999: 14.532 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 3.876 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.281 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 17.916 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  11.224 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248532
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8152 
    [ 2.500,  5.000) = 219430 
    [ 5.000,  7.500) = 19119 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     11.910 ms/op
     p(99.9900) =     20.761 ms/op
     p(99.9990) =     22.103 ms/op
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
# Warmup Iteration   1: 6.603 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.013 ms/op
Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.303 ms/op
                 getUser·p0.999:  11.498 ms/op
                 getUser·p0.9999: 20.864 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 4.144 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   7.207 ms/op
                 getUser·p0.999:  10.986 ms/op
                 getUser·p0.9999: 16.316 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   3: 4.154 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.153 ms/op
                 getUser·p0.999:  13.928 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230760
  mean =      4.161 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4371 
    [ 2.500,  5.000) = 190869 
    [ 5.000,  7.500) = 33606 
    [ 7.500, 10.000) = 1504 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     11.587 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     21.541 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 7.634 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.492 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.123 ±(99.9%) 0.018 ms/op
Iteration   1: 4.994 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.425 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.203 ms/op
                 listUser·p0.999:  14.581 ms/op
                 listUser·p0.9999: 16.678 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 5.121 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.308 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 4.885 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  20.826 ms/op
                 listUser·p0.9999: 29.196 ms/op
                 listUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192095
  mean =      4.998 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 374 
    [ 2.500,  5.000) = 117084 
    [ 5.000,  7.500) = 66231 
    [ 7.500, 10.000) = 7131 
    [10.000, 12.500) = 850 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     15.842 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     29.824 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.960 ± 6.549  ops/ms
ClientGrpc.existUser                       thrpt       3   8.419 ± 0.866  ops/ms
ClientGrpc.getUser                         thrpt       3   7.835 ± 4.831  ops/ms
ClientGrpc.listUser                        thrpt       3   6.306 ± 0.946  ops/ms
ClientGrpc.createUser                       avgt       3   3.980 ± 2.181   ms/op
ClientGrpc.existUser                        avgt       3   3.923 ± 2.336   ms/op
ClientGrpc.getUser                          avgt       3   4.269 ± 1.305   ms/op
ClientGrpc.listUser                         avgt       3   5.187 ± 2.596   ms/op
ClientGrpc.createUser                     sample  233111   4.119 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.889           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.865           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.106           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.248           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.717           ms/op
ClientGrpc.existUser                      sample  248532   3.863 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.910           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.761           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  230760   4.161 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.587           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.694           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  192095   4.998 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.842           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.884           ms/op
