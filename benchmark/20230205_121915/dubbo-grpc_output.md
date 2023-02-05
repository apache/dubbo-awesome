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
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 8.276 ops/ms
# Warmup Iteration   3: 9.974 ops/ms
Iteration   1: 9.690 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.717 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (9.690, 9.717, 9.758), stdev = 0.036
  CI (99.9%): [9.053, 10.381] (assumes normal distribution)


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
# Warmup Iteration   1: 7.142 ops/ms
# Warmup Iteration   2: 9.786 ops/ms
# Warmup Iteration   3: 9.874 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 9.910 ops/ms
Iteration   3: 9.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.980 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (9.910, 9.980, 10.080), stdev = 0.089
  CI (99.9%): [8.366, 11.595] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.417 ops/ms
# Warmup Iteration   2: 9.515 ops/ms
# Warmup Iteration   3: 9.733 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.863 ops/ms
Iteration   3: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.809 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (9.732, 9.809, 9.863), stdev = 0.068
  CI (99.9%): [8.561, 11.057] (assumes normal distribution)


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
# Warmup Iteration   1: 5.823 ops/ms
# Warmup Iteration   2: 7.173 ops/ms
# Warmup Iteration   3: 7.283 ops/ms
Iteration   1: 7.445 ops/ms
Iteration   2: 7.416 ops/ms
Iteration   3: 7.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.457 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (7.416, 7.457, 7.511), stdev = 0.049
  CI (99.9%): [6.565, 8.349] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.004 ms/op
Iteration   1: 3.341 ±(99.9%) 0.007 ms/op
Iteration   2: 3.351 ±(99.9%) 0.003 ms/op
Iteration   3: 3.311 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.334 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.311, 3.334, 3.351), stdev = 0.021
  CI (99.9%): [2.953, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.004 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.163 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.124, 3.163, 3.200), stdev = 0.038
  CI (99.9%): [2.464, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.320 ±(99.9%) 0.007 ms/op
Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
Iteration   3: 3.311 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.309 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.296, 3.309, 3.320), stdev = 0.012
  CI (99.9%): [3.086, 3.532] (assumes normal distribution)


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
# Warmup Iteration   1: 6.335 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.012 ms/op
Iteration   1: 4.219 ±(99.9%) 0.011 ms/op
Iteration   2: 4.219 ±(99.9%) 0.011 ms/op
Iteration   3: 4.344 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.261 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (4.219, 4.261, 4.344), stdev = 0.072
  CI (99.9%): [2.951, 5.570] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
Iteration   1: 3.287 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.821 ms/op
                 createUser·p0.9999: 13.551 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.329 ms/op
                 createUser·p0.9999: 14.689 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 3.401 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  10.681 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 288642
  mean =      3.325 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 370 
    [ 1.250,  2.500) = 11775 
    [ 2.500,  3.750) = 213460 
    [ 3.750,  5.000) = 61621 
    [ 5.000,  6.250) = 646 
    [ 6.250,  7.500) = 331 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.234 ms/op
     p(99.9900) =     16.620 ms/op
     p(99.9990) =     17.342 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
Iteration   1: 3.198 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.062 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.151 ms/op
                 existUser·p0.9999: 17.431 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 300419
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 22736 
    [ 2.500,  3.750) = 227731 
    [ 3.750,  5.000) = 48134 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 166 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 32.317 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 21.807 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.830 ms/op
                 getUser·p0.9999: 24.880 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 289821
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11209 
    [ 2.500,  5.000) = 277189 
    [ 5.000,  7.500) = 952 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     30.606 ms/op
     p(99.9990) =     32.739 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 5.531 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.363 ±(99.9%) 0.013 ms/op
Iteration   1: 4.350 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 23.024 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.183 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  16.283 ms/op
                 listUser·p0.9999: 20.581 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.308 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  17.953 ms/op
                 listUser·p0.9999: 21.416 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 224415
  mean =      4.279 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1042 
    [ 2.500,  5.000) = 189487 
    [ 5.000,  7.500) = 31592 
    [ 7.500, 10.000) = 1840 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     16.590 ms/op
     p(99.9900) =     22.628 ms/op
     p(99.9990) =     25.920 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.717 ± 0.664  ops/ms
ClientGrpc.existUser                       thrpt       3   9.980 ± 1.615  ops/ms
ClientGrpc.getUser                         thrpt       3   9.809 ± 1.248  ops/ms
ClientGrpc.listUser                        thrpt       3   7.457 ± 0.892  ops/ms
ClientGrpc.createUser                       avgt       3   3.334 ± 0.381   ms/op
ClientGrpc.existUser                        avgt       3   3.163 ± 0.699   ms/op
ClientGrpc.getUser                          avgt       3   3.309 ± 0.223   ms/op
ClientGrpc.listUser                         avgt       3   4.261 ± 1.310   ms/op
ClientGrpc.createUser                     sample  288642   3.325 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.840           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.297           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.234           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.620           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.465           ms/op
ClientGrpc.existUser                      sample  300419   3.196 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.162           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.252           ms/op
ClientGrpc.getUser                        sample  289821   3.312 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.778           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.277           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.568           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.606           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.834           ms/op
ClientGrpc.listUser                       sample  224415   4.279 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.931           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.084           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.590           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
