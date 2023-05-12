# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 6.291 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.335 ±(99.9%) 0.401 ops/ms [Average]
  (min, avg, max) = (8.315, 8.335, 8.359), stdev = 0.022
  CI (99.9%): [7.935, 8.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.642 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 8.941 ops/ms
Iteration   2: 9.441 ops/ms
Iteration   3: 9.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.201 ±(99.9%) 4.580 ops/ms [Average]
  (min, avg, max) = (8.941, 9.201, 9.441), stdev = 0.251
  CI (99.9%): [4.621, 13.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.421 ops/ms
# Warmup Iteration   2: 7.901 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.337 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.491 ±(99.9%) 2.600 ops/ms [Average]
  (min, avg, max) = (8.337, 8.491, 8.619), stdev = 0.143
  CI (99.9%): [5.890, 11.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 6.286 ops/ms
Iteration   1: 6.403 ops/ms
Iteration   2: 6.470 ops/ms
Iteration   3: 6.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.447 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (6.403, 6.447, 6.470), stdev = 0.038
  CI (99.9%): [5.752, 7.142] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.527 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 3.932 ±(99.9%) 0.002 ms/op
Iteration   2: 3.789 ±(99.9%) 0.003 ms/op
Iteration   3: 3.832 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.851 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (3.789, 3.851, 3.932), stdev = 0.073
  CI (99.9%): [2.514, 5.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.091 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.002 ms/op
Iteration   1: 3.498 ±(99.9%) 0.003 ms/op
Iteration   2: 3.533 ±(99.9%) 0.004 ms/op
Iteration   3: 3.670 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.567 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (3.498, 3.567, 3.670), stdev = 0.091
  CI (99.9%): [1.908, 5.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.336 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.005 ms/op
Iteration   1: 3.820 ±(99.9%) 0.003 ms/op
Iteration   2: 3.868 ±(99.9%) 0.002 ms/op
Iteration   3: 3.646 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.778 ±(99.9%) 2.137 ms/op [Average]
  (min, avg, max) = (3.646, 3.778, 3.868), stdev = 0.117
  CI (99.9%): [1.641, 5.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.273 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.013 ms/op
Iteration   1: 5.031 ±(99.9%) 0.008 ms/op
Iteration   2: 5.070 ±(99.9%) 0.014 ms/op
Iteration   3: 5.117 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.073 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (5.031, 5.073, 5.117), stdev = 0.043
  CI (99.9%): [4.280, 5.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.728 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.012 ms/op
Iteration   1: 3.694 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  11.017 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.593 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  11.448 ms/op
                 createUser·p0.9999: 28.115 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.865 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  12.587 ms/op
                 createUser·p0.9999: 34.913 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258449
  mean =      3.714 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10482 
    [ 2.500,  5.000) = 231076 
    [ 5.000,  7.500) = 15489 
    [ 7.500, 10.000) = 984 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     11.920 ms/op
     p(99.9900) =     32.980 ms/op
     p(99.9990) =     35.155 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.390 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.012 ms/op
Iteration   1: 3.484 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  11.804 ms/op
                 existUser·p0.9999: 31.910 ms/op
                 existUser·p1.00:   32.440 ms/op

Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.317 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 33.167 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.701 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   6.894 ms/op
                 existUser·p0.999:  12.327 ms/op
                 existUser·p0.9999: 23.309 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266402
  mean =      3.603 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14241 
    [ 2.500,  5.000) = 238173 
    [ 5.000,  7.500) = 12510 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     32.244 ms/op
     p(99.9990) =     33.424 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.679 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.013 ms/op
Iteration   1: 3.758 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 15.957 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  10.520 ms/op
                 getUser·p0.9999: 21.879 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.783 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  13.135 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251193
  mean =      3.823 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16601 
    [ 2.500,  5.000) = 212084 
    [ 5.000,  7.500) = 20831 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.232 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.340 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.400 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.021 ms/op
Iteration   1: 4.972 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   7.004 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 29.004 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 5.179 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.538 ms/op
                 listUser·p0.999:  20.488 ms/op
                 listUser·p0.9999: 24.516 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 5.080 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  18.677 ms/op
                 listUser·p0.9999: 29.655 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189188
  mean =      5.076 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1683 
    [ 2.500,  5.000) = 109970 
    [ 5.000,  7.500) = 63253 
    [ 7.500, 10.000) = 11786 
    [10.000, 12.500) = 1557 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     29.038 ms/op
     p(99.9990) =     29.961 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.335 ± 0.401  ops/ms
ClientGrpc.existUser                       thrpt       3   9.201 ± 4.580  ops/ms
ClientGrpc.getUser                         thrpt       3   8.491 ± 2.600  ops/ms
ClientGrpc.listUser                        thrpt       3   6.447 ± 0.695  ops/ms
ClientGrpc.createUser                       avgt       3   3.851 ± 1.337   ms/op
ClientGrpc.existUser                        avgt       3   3.567 ± 1.659   ms/op
ClientGrpc.getUser                          avgt       3   3.778 ± 2.137   ms/op
ClientGrpc.listUser                         avgt       3   5.073 ± 0.792   ms/op
ClientGrpc.createUser                     sample  258449   3.714 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.804           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.920           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.980           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.324           ms/op
ClientGrpc.existUser                      sample  266402   3.603 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.993           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.244           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.554           ms/op
ClientGrpc.getUser                        sample  251193   3.823 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.407           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.232           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  189188   5.076 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.981           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.792           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.038           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.048           ms/op
