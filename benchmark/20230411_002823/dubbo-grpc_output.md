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
# Warmup Iteration   1: 4.752 ops/ms
# Warmup Iteration   2: 9.534 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.641 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (10.598, 10.641, 10.706), stdev = 0.057
  CI (99.9%): [9.597, 11.684] (assumes normal distribution)


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
# Warmup Iteration   1: 8.693 ops/ms
# Warmup Iteration   2: 10.845 ops/ms
# Warmup Iteration   3: 11.251 ops/ms
Iteration   1: 11.449 ops/ms
Iteration   2: 11.574 ops/ms
Iteration   3: 11.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.459 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (11.355, 11.459, 11.574), stdev = 0.110
  CI (99.9%): [9.456, 13.463] (assumes normal distribution)


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
# Warmup Iteration   1: 7.678 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 10.801 ops/ms
Iteration   1: 10.919 ops/ms
Iteration   2: 10.866 ops/ms
Iteration   3: 10.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.913 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (10.866, 10.913, 10.955), stdev = 0.045
  CI (99.9%): [10.093, 11.734] (assumes normal distribution)


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
# Warmup Iteration   1: 5.841 ops/ms
# Warmup Iteration   2: 8.199 ops/ms
# Warmup Iteration   3: 8.280 ops/ms
Iteration   1: 8.276 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.327 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (8.276, 8.327, 8.379), stdev = 0.051
  CI (99.9%): [7.389, 9.265] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.969 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.956, 2.969, 2.983), stdev = 0.014
  CI (99.9%): [2.718, 3.220] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.801 ±(99.9%) 0.004 ms/op
Iteration   1: 2.859 ±(99.9%) 0.002 ms/op
Iteration   2: 2.796 ±(99.9%) 0.005 ms/op
Iteration   3: 2.786 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.814 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (2.786, 2.814, 2.859), stdev = 0.040
  CI (99.9%): [2.091, 3.537] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.650 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.913 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.939 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.913, 2.939, 2.958), stdev = 0.023
  CI (99.9%): [2.520, 3.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.010 ms/op
Iteration   1: 3.883 ±(99.9%) 0.035 ms/op
Iteration   2: 3.825 ±(99.9%) 0.005 ms/op
Iteration   3: 3.850 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.853 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (3.825, 3.853, 3.883), stdev = 0.029
  CI (99.9%): [3.323, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
Iteration   1: 2.902 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.535 ms/op
                 createUser·p0.9999: 15.581 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  12.448 ms/op
                 createUser·p0.9999: 16.619 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   3: 2.962 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.764 ms/op
                 createUser·p0.9999: 14.317 ms/op
                 createUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326683
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2192 
    [ 1.250,  2.500) = 35176 
    [ 2.500,  3.750) = 277041 
    [ 3.750,  5.000) = 11358 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     15.685 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.523 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.802 ±(99.9%) 0.006 ms/op
Iteration   1: 2.799 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.286 ms/op
                 existUser·p0.999:  7.110 ms/op
                 existUser·p0.9999: 25.742 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 2.767 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.446 ms/op
                 existUser·p0.9999: 13.761 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  9.783 ms/op
                 existUser·p0.9999: 22.486 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341767
  mean =      2.807 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60599 
    [ 2.500,  5.000) = 280211 
    [ 5.000,  7.500) = 657 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     23.915 ms/op
     p(99.9990) =     25.873 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.701 ms/op
                 getUser·p0.9999: 18.730 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 2.934 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.184 ms/op
                 getUser·p0.9999: 15.832 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.873 ms/op
                 getUser·p0.9999: 15.023 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327041
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2479 
    [ 1.250,  2.500) = 31446 
    [ 2.500,  3.750) = 280909 
    [ 3.750,  5.000) = 11019 
    [ 5.000,  6.250) = 682 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.987 ms/op
     p(99.9900) =     17.016 ms/op
     p(99.9990) =     19.029 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.009 ms/op
Iteration   1: 3.867 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  12.069 ms/op
                 listUser·p0.9999: 15.757 ms/op
                 listUser·p1.00:   16.597 ms/op

Iteration   2: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.414 ms/op
                 listUser·p0.9999: 15.451 ms/op
                 listUser·p1.00:   15.811 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 21.426 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246305
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3759 
    [ 2.500,  5.000) = 222272 
    [ 5.000,  7.500) = 19081 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     12.562 ms/op
     p(99.9900) =     20.177 ms/op
     p(99.9990) =     21.513 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.641 ± 1.044  ops/ms
ClientGrpc.existUser                       thrpt       3  11.459 ± 2.004  ops/ms
ClientGrpc.getUser                         thrpt       3  10.913 ± 0.820  ops/ms
ClientGrpc.listUser                        thrpt       3   8.327 ± 0.938  ops/ms
ClientGrpc.createUser                       avgt       3   2.969 ± 0.251   ms/op
ClientGrpc.existUser                        avgt       3   2.814 ± 0.723   ms/op
ClientGrpc.getUser                          avgt       3   2.939 ± 0.419   ms/op
ClientGrpc.listUser                         avgt       3   3.853 ± 0.530   ms/op
ClientGrpc.createUser                     sample  326683   2.940 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.781           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.685           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.170           ms/op
ClientGrpc.existUser                      sample  341767   2.807 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.470           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.915           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  327041   2.935 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.602           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.987           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.016           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  246305   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.905           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.562           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.177           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
