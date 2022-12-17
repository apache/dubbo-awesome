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
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 5.521 ops/ms
# Warmup Iteration   3: 7.051 ops/ms
Iteration   1: 7.175 ops/ms
Iteration   2: 7.401 ops/ms
Iteration   3: 7.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.310 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (7.175, 7.310, 7.401), stdev = 0.119
  CI (99.9%): [5.143, 9.476] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ops/ms
# Warmup Iteration   2: 7.459 ops/ms
# Warmup Iteration   3: 7.857 ops/ms
Iteration   1: 8.034 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.915 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (7.748, 7.915, 8.034), stdev = 0.149
  CI (99.9%): [5.192, 10.638] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.852 ops/ms
# Warmup Iteration   2: 7.109 ops/ms
# Warmup Iteration   3: 7.095 ops/ms
Iteration   1: 7.276 ops/ms
Iteration   2: 7.738 ops/ms
Iteration   3: 7.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.542 ±(99.9%) 4.356 ops/ms [Average]
  (min, avg, max) = (7.276, 7.542, 7.738), stdev = 0.239
  CI (99.9%): [3.186, 11.898] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ops/ms
# Warmup Iteration   2: 5.670 ops/ms
# Warmup Iteration   3: 6.077 ops/ms
Iteration   1: 6.257 ops/ms
Iteration   2: 6.221 ops/ms
Iteration   3: 6.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.178 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (6.057, 6.178, 6.257), stdev = 0.107
  CI (99.9%): [4.234, 8.122] (assumes normal distribution)


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
# Warmup Iteration   1: 6.598 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.002 ms/op
Iteration   1: 4.320 ±(99.9%) 0.003 ms/op
Iteration   2: 4.329 ±(99.9%) 0.003 ms/op
Iteration   3: 4.469 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.373 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (4.320, 4.373, 4.469), stdev = 0.084
  CI (99.9%): [2.847, 5.898] (assumes normal distribution)


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
# Warmup Iteration   1: 5.830 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.004 ms/op
Iteration   1: 4.010 ±(99.9%) 0.004 ms/op
Iteration   2: 3.882 ±(99.9%) 0.003 ms/op
Iteration   3: 4.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.974 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.882, 3.974, 4.032), stdev = 0.081
  CI (99.9%): [2.492, 5.457] (assumes normal distribution)


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
# Warmup Iteration   1: 6.084 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.008 ms/op
Iteration   1: 4.243 ±(99.9%) 0.003 ms/op
Iteration   2: 4.221 ±(99.9%) 0.004 ms/op
Iteration   3: 4.228 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.231 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (4.221, 4.231, 4.243), stdev = 0.012
  CI (99.9%): [4.018, 4.444] (assumes normal distribution)


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
# Warmup Iteration   1: 7.098 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.673 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.209 ±(99.9%) 0.012 ms/op
Iteration   1: 5.200 ±(99.9%) 0.016 ms/op
Iteration   2: 5.226 ±(99.9%) 0.008 ms/op
Iteration   3: 5.178 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.201 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (5.178, 5.201, 5.226), stdev = 0.024
  CI (99.9%): [4.767, 5.636] (assumes normal distribution)


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
# Warmup Iteration   1: 6.654 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.012 ms/op
Iteration   1: 4.191 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  13.369 ms/op
                 createUser·p0.9999: 24.481 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  11.157 ms/op
                 createUser·p0.9999: 23.103 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  11.406 ms/op
                 createUser·p0.9999: 23.434 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235540
  mean =      4.073 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6619 
    [ 2.500,  5.000) = 196329 
    [ 5.000,  7.500) = 30925 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     23.345 ms/op
     p(99.9990) =     25.000 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  10.503 ms/op
                 existUser·p0.9999: 16.907 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 3.840 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  11.559 ms/op
                 existUser·p0.9999: 17.051 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 19.264 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244247
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8479 
    [ 2.500,  5.000) = 212901 
    [ 5.000,  7.500) = 21479 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     18.860 ms/op
     p(99.9990) =     19.847 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 6.170 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.013 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 4.150 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  12.297 ms/op
                 getUser·p0.9999: 20.925 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 4.268 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  10.226 ms/op
                 getUser·p0.9999: 24.347 ms/op
                 getUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234504
  mean =      4.092 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5395 
    [ 2.500,  5.000) = 195709 
    [ 5.000,  7.500) = 31779 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     23.498 ms/op
     p(99.9990) =     24.553 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 7.402 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.431 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.072 ±(99.9%) 0.016 ms/op
Iteration   1: 5.250 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  16.503 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 5.201 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.651 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  16.914 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 5.155 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 31.654 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184418
  mean =      5.202 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 221 
    [ 2.500,  5.000) = 94795 
    [ 5.000,  7.500) = 79568 
    [ 7.500, 10.000) = 8193 
    [10.000, 12.500) = 1083 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     29.903 ms/op
     p(99.9990) =     32.630 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.310 ± 2.167  ops/ms
ClientGrpc.existUser                       thrpt       3   7.915 ± 2.723  ops/ms
ClientGrpc.getUser                         thrpt       3   7.542 ± 4.356  ops/ms
ClientGrpc.listUser                        thrpt       3   6.178 ± 1.944  ops/ms
ClientGrpc.createUser                       avgt       3   4.373 ± 1.525   ms/op
ClientGrpc.existUser                        avgt       3   3.974 ± 1.482   ms/op
ClientGrpc.getUser                          avgt       3   4.231 ± 0.213   ms/op
ClientGrpc.listUser                         avgt       3   5.201 ± 0.435   ms/op
ClientGrpc.createUser                     sample  235540   4.073 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.707           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.808           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.845           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.133           ms/op
ClientGrpc.existUser                      sample  244247   3.929 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.879           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.860           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  234504   4.092 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.850           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.717           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.894           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.498           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.642           ms/op
ClientGrpc.listUser                       sample  184418   5.202 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.294           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.768           ms/op
