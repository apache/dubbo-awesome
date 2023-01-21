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
# Warmup Iteration   1: 4.523 ops/ms
# Warmup Iteration   2: 9.195 ops/ms
# Warmup Iteration   3: 9.981 ops/ms
Iteration   1: 10.088 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.014 ±(99.9%) 2.291 ops/ms [Average]
  (min, avg, max) = (9.869, 10.014, 10.088), stdev = 0.126
  CI (99.9%): [7.723, 12.304] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ops/ms
# Warmup Iteration   2: 10.009 ops/ms
# Warmup Iteration   3: 10.219 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 10.432 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.372 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (10.200, 10.372, 10.482), stdev = 0.150
  CI (99.9%): [7.630, 13.113] (assumes normal distribution)


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
# Warmup Iteration   1: 6.662 ops/ms
# Warmup Iteration   2: 9.861 ops/ms
# Warmup Iteration   3: 9.871 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.187 ops/ms
Iteration   3: 10.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.175 ±(99.9%) 0.792 ops/ms [Average]
  (min, avg, max) = (10.127, 10.175, 10.211), stdev = 0.043
  CI (99.9%): [9.383, 10.966] (assumes normal distribution)


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
# Warmup Iteration   1: 5.189 ops/ms
# Warmup Iteration   2: 7.447 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.671 ops/ms
Iteration   2: 7.582 ops/ms
Iteration   3: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.732 ±(99.9%) 3.439 ops/ms [Average]
  (min, avg, max) = (7.582, 7.732, 7.944), stdev = 0.189
  CI (99.9%): [4.293, 11.171] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.006 ms/op
Iteration   1: 3.236 ±(99.9%) 0.002 ms/op
Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.187 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (3.102, 3.187, 3.236), stdev = 0.074
  CI (99.9%): [1.846, 4.528] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.002 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 3.144 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 1.745 ms/op [Average]
  (min, avg, max) = (2.952, 3.048, 3.144), stdev = 0.096
  CI (99.9%): [1.303, 4.793] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.002 ms/op
Iteration   1: 3.226 ±(99.9%) 0.004 ms/op
Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
Iteration   3: 3.250 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.242 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.226, 3.242, 3.250), stdev = 0.014
  CI (99.9%): [2.989, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 5.584 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.013 ms/op
Iteration   1: 4.129 ±(99.9%) 0.012 ms/op
Iteration   2: 4.116 ±(99.9%) 0.014 ms/op
Iteration   3: 4.094 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.113 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (4.094, 4.113, 4.129), stdev = 0.018
  CI (99.9%): [3.790, 4.435] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.006 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.012 ms/op
                 createUser·p0.9999: 13.794 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.675 ms/op
                 createUser·p0.9999: 14.478 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 3.273 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.310 ms/op
                 createUser·p0.9999: 17.374 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301892
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1310 
    [ 1.250,  2.500) = 19329 
    [ 2.500,  3.750) = 241956 
    [ 3.750,  5.000) = 37967 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.052 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     16.837 ms/op
     p(99.9990) =     17.726 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 13.039 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.357 ms/op
                 existUser·p0.9999: 15.003 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.406 ms/op
                 existUser·p0.999:  7.785 ms/op
                 existUser·p0.9999: 21.049 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314137
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35580 
    [ 2.500,  5.000) = 277651 
    [ 5.000,  7.500) = 639 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.150 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.557 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.510 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.762 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.242 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299615
  mean =      3.202 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17391 
    [ 2.500,  5.000) = 280923 
    [ 5.000,  7.500) = 994 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.067 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.012 ms/op
Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.937 ms/op
                 listUser·p0.9999: 20.829 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 4.091 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.330 ms/op
                 listUser·p0.9999: 21.474 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.468 ms/op
                 listUser·p0.9999: 24.841 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236083
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1303 
    [ 2.500,  5.000) = 209275 
    [ 5.000,  7.500) = 24068 
    [ 7.500, 10.000) = 949 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     26.572 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.014 ± 2.291  ops/ms
ClientGrpc.existUser                       thrpt       3  10.372 ± 2.742  ops/ms
ClientGrpc.getUser                         thrpt       3  10.175 ± 0.792  ops/ms
ClientGrpc.listUser                        thrpt       3   7.732 ± 3.439  ops/ms
ClientGrpc.createUser                       avgt       3   3.187 ± 1.341   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 1.745   ms/op
ClientGrpc.getUser                          avgt       3   3.242 ± 0.253   ms/op
ClientGrpc.listUser                         avgt       3   4.113 ± 0.322   ms/op
ClientGrpc.createUser                     sample  301892   3.181 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.052           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.837           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.859           ms/op
ClientGrpc.existUser                      sample  314137   3.055 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.150           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.988           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  299615   3.202 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.197           ms/op
ClientGrpc.listUser                       sample  236083   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.801           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
