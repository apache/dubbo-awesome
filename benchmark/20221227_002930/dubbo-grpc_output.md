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
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 8.780 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.802 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (9.716, 9.802, 9.867), stdev = 0.077
  CI (99.9%): [8.390, 11.213] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.810 ops/ms
# Warmup Iteration   2: 10.039 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.395 ±(99.9%) 0.573 ops/ms [Average]
  (min, avg, max) = (10.362, 10.395, 10.424), stdev = 0.031
  CI (99.9%): [9.821, 10.968] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.685 ops/ms
# Warmup Iteration   2: 9.600 ops/ms
# Warmup Iteration   3: 9.999 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 9.867 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.913 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (9.851, 9.913, 10.021), stdev = 0.094
  CI (99.9%): [8.207, 11.619] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.239 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 7.854 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.983 ±(99.9%) 3.384 ops/ms [Average]
  (min, avg, max) = (7.854, 7.983, 8.196), stdev = 0.186
  CI (99.9%): [4.599, 11.367] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.198 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.177, 3.198, 3.227), stdev = 0.026
  CI (99.9%): [2.726, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.002 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 3.029 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.013 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (2.946, 3.013, 3.065), stdev = 0.061
  CI (99.9%): [1.897, 4.129] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.002 ms/op
Iteration   1: 3.179 ±(99.9%) 0.002 ms/op
Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
Iteration   3: 3.149 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.186 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.149, 3.186, 3.231), stdev = 0.041
  CI (99.9%): [2.432, 3.941] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.019 ms/op
Iteration   1: 3.993 ±(99.9%) 0.007 ms/op
Iteration   2: 4.093 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (3.909, 3.998, 4.093), stdev = 0.092
  CI (99.9%): [2.316, 5.680] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.186 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.057 ms/op
                 createUser·p0.9999: 17.430 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.161 ms/op
                 createUser·p0.9999: 23.582 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.154 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  10.488 ms/op
                 createUser·p0.9999: 39.294 ms/op
                 createUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305073
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 303721 
    [ 5.000, 10.000) = 1107 
    [10.000, 15.000) = 59 
    [15.000, 20.000) = 119 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     35.061 ms/op
     p(99.9990) =     40.105 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.198 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.251 ms/op
                 existUser·p0.9999: 13.281 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.398 ms/op
                 existUser·p0.9999: 14.511 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.016 ms/op
                 existUser·p0.9999: 15.298 ms/op
                 existUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316868
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 696 
    [ 1.250,  2.500) = 41564 
    [ 2.500,  3.750) = 246607 
    [ 3.750,  5.000) = 27340 
    [ 5.000,  6.250) = 347 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.227 ms/op
     p(99.9900) =     14.849 ms/op
     p(99.9990) =     15.445 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.007 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  12.412 ms/op
                 getUser·p0.9999: 15.680 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.582 ms/op
                 getUser·p0.9999: 16.305 ms/op
                 getUser·p1.00:   16.581 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.335 ms/op
                 getUser·p0.9999: 17.625 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299306
  mean =      3.207 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 18436 
    [ 2.500,  3.750) = 237394 
    [ 3.750,  5.000) = 41981 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 70 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     16.602 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.011 ms/op
Iteration   1: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 24.098 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.023 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.910 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.234 ms/op
                 listUser·p0.9999: 21.885 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240385
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1353 
    [ 2.500,  5.000) = 215062 
    [ 5.000,  7.500) = 22816 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.853 ms/op
     p(99.9900) =     23.459 ms/op
     p(99.9990) =     25.611 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.802 ± 1.411  ops/ms
ClientGrpc.existUser                       thrpt       3  10.395 ± 0.573  ops/ms
ClientGrpc.getUser                         thrpt       3   9.913 ± 1.706  ops/ms
ClientGrpc.listUser                        thrpt       3   7.983 ± 3.384  ops/ms
ClientGrpc.createUser                       avgt       3   3.198 ± 0.472   ms/op
ClientGrpc.existUser                        avgt       3   3.013 ± 1.116   ms/op
ClientGrpc.getUser                          avgt       3   3.186 ± 0.755   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 1.682   ms/op
ClientGrpc.createUser                     sample  305073   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.392           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.002           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.167           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.061           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.174           ms/op
ClientGrpc.existUser                      sample  316868   3.029 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.227           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.849           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.548           ms/op
ClientGrpc.getUser                        sample  299306   3.207 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.456           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.602           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.317           ms/op
ClientGrpc.listUser                       sample  240385   3.991 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.853           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.459           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
