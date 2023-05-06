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
# Warmup Iteration   1: 4.898 ops/ms
# Warmup Iteration   2: 9.605 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.671 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.495 ±(99.9%) 3.081 ops/ms [Average]
  (min, avg, max) = (10.335, 10.495, 10.671), stdev = 0.169
  CI (99.9%): [7.414, 13.577] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.013 ops/ms
# Warmup Iteration   2: 10.994 ops/ms
# Warmup Iteration   3: 11.316 ops/ms
Iteration   1: 11.343 ops/ms
Iteration   2: 11.119 ops/ms
Iteration   3: 11.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.276 ±(99.9%) 2.490 ops/ms [Average]
  (min, avg, max) = (11.119, 11.276, 11.367), stdev = 0.136
  CI (99.9%): [8.786, 13.766] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.818 ops/ms
# Warmup Iteration   2: 10.635 ops/ms
# Warmup Iteration   3: 10.815 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.664 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (10.548, 10.664, 10.802), stdev = 0.129
  CI (99.9%): [8.318, 13.010] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.811 ops/ms
# Warmup Iteration   2: 7.975 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.255 ops/ms
Iteration   3: 8.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.181 ±(99.9%) 2.493 ops/ms [Average]
  (min, avg, max) = (8.023, 8.181, 8.264), stdev = 0.137
  CI (99.9%): [5.687, 10.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.945 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.929, 2.945, 2.959), stdev = 0.015
  CI (99.9%): [2.668, 3.223] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.913 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.003 ms/op
Iteration   1: 2.828 ±(99.9%) 0.003 ms/op
Iteration   2: 2.858 ±(99.9%) 0.004 ms/op
Iteration   3: 2.813 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.833 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.813, 2.833, 2.858), stdev = 0.023
  CI (99.9%): [2.416, 3.250] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.953 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.945, 2.953, 2.961), stdev = 0.008
  CI (99.9%): [2.810, 3.097] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.045 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.022 ms/op
Iteration   1: 3.980 ±(99.9%) 0.032 ms/op
Iteration   2: 3.870 ±(99.9%) 0.007 ms/op
Iteration   3: 3.929 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.870, 3.926, 3.980), stdev = 0.055
  CI (99.9%): [2.914, 4.938] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.997 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  6.329 ms/op
                 createUser·p0.9999: 12.685 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.708 ms/op
                 createUser·p0.9999: 15.659 ms/op
                 createUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321180
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1853 
    [ 1.250,  2.500) = 25639 
    [ 2.500,  3.750) = 278599 
    [ 3.750,  5.000) = 13952 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.664 ms/op
     p(99.9900) =     17.653 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
Iteration   1: 2.828 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.338 ms/op
                 existUser·p0.9999: 17.226 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.136 ms/op
                 existUser·p0.9999: 18.773 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.883 ms/op
                 existUser·p0.9999: 14.489 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334727
  mean =      2.867 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2686 
    [ 1.250,  2.500) = 47079 
    [ 2.500,  3.750) = 274722 
    [ 3.750,  5.000) = 9001 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 255 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.899 ms/op
     p(99.9900) =     17.533 ms/op
     p(99.9990) =     19.027 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.343 ms/op
                 getUser·p0.9999: 15.634 ms/op
                 getUser·p1.00:   16.024 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.383 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.601 ms/op
                 getUser·p0.9999: 15.334 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 30.055 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322948
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29049 
    [ 2.500,  5.000) = 292729 
    [ 5.000,  7.500) = 866 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.202 ms/op
     p(99.9900) =     26.197 ms/op
     p(99.9990) =     31.173 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.009 ms/op
Iteration   1: 3.984 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.245 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   14.451 ms/op

Iteration   2: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.413 ms/op
                 listUser·p0.9999: 17.253 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.800 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243452
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 3864 
    [ 2.500,  3.750) = 102656 
    [ 3.750,  5.000) = 114880 
    [ 5.000,  6.250) = 16573 
    [ 6.250,  7.500) = 4171 
    [ 7.500,  8.750) = 780 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 146 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.001 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     18.035 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.495 ± 3.081  ops/ms
ClientGrpc.existUser                       thrpt       3  11.276 ± 2.490  ops/ms
ClientGrpc.getUser                         thrpt       3  10.664 ± 2.346  ops/ms
ClientGrpc.listUser                        thrpt       3   8.181 ± 2.493  ops/ms
ClientGrpc.createUser                       avgt       3   2.945 ± 0.278   ms/op
ClientGrpc.existUser                        avgt       3   2.833 ± 0.417   ms/op
ClientGrpc.getUser                          avgt       3   2.953 ± 0.144   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 1.012   ms/op
ClientGrpc.createUser                     sample  321180   2.988 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.518           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.664           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.653           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  334727   2.867 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.652           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.899           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  322948   2.975 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.383           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.202           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.197           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.392           ms/op
ClientGrpc.listUser                       sample  243452   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.044           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.001           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.039           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.842           ms/op
