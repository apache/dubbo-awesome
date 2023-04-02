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
# Warmup Iteration   1: 4.731 ops/ms
# Warmup Iteration   2: 9.361 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.666 ops/ms
Iteration   3: 11.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.804 ±(99.9%) 3.485 ops/ms [Average]
  (min, avg, max) = (10.666, 10.804, 11.022), stdev = 0.191
  CI (99.9%): [7.319, 14.289] (assumes normal distribution)


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
# Warmup Iteration   1: 7.645 ops/ms
# Warmup Iteration   2: 10.983 ops/ms
# Warmup Iteration   3: 11.228 ops/ms
Iteration   1: 11.132 ops/ms
Iteration   2: 11.438 ops/ms
Iteration   3: 11.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.264 ±(99.9%) 2.871 ops/ms [Average]
  (min, avg, max) = (11.132, 11.264, 11.438), stdev = 0.157
  CI (99.9%): [8.394, 14.135] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.804 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.712 ops/ms
Iteration   2: 11.026 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.867 ±(99.9%) 2.865 ops/ms [Average]
  (min, avg, max) = (10.712, 10.867, 11.026), stdev = 0.157
  CI (99.9%): [8.002, 13.732] (assumes normal distribution)


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
# Warmup Iteration   1: 6.403 ops/ms
# Warmup Iteration   2: 7.418 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 7.992 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.041 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (7.976, 8.041, 8.154), stdev = 0.098
  CI (99.9%): [6.247, 9.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 2.940 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.947 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.940, 2.947, 2.960), stdev = 0.011
  CI (99.9%): [2.748, 3.147] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.004 ms/op
Iteration   1: 2.827 ±(99.9%) 0.003 ms/op
Iteration   2: 2.818 ±(99.9%) 0.003 ms/op
Iteration   3: 2.862 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.818, 2.836, 2.862), stdev = 0.024
  CI (99.9%): [2.405, 3.266] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.944, 2.956, 2.965), stdev = 0.011
  CI (99.9%): [2.756, 3.156] (assumes normal distribution)


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.037 ms/op
Iteration   1: 3.859 ±(99.9%) 0.037 ms/op
Iteration   2: 3.866 ±(99.9%) 0.024 ms/op
Iteration   3: 3.759 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.828 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (3.759, 3.828, 3.866), stdev = 0.060
  CI (99.9%): [2.730, 4.926] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.324 ms/op
                 createUser·p0.9999: 18.719 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 21.540 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.924 ms/op
                 createUser·p0.9999: 14.287 ms/op
                 createUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318170
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22416 
    [ 2.500,  5.000) = 294376 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.541 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     21.877 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.479 ms/op
                 existUser·p0.9999: 16.848 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  8.215 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.659 ms/op
                 existUser·p0.9999: 14.220 ms/op
                 existUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329994
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46091 
    [ 2.500,  5.000) = 282562 
    [ 5.000,  7.500) = 1009 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     17.761 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.016 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.222 ms/op
                 getUser·p0.9999: 14.097 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.167 ms/op
                 getUser·p0.9999: 17.465 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322405
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1539 
    [ 1.250,  2.500) = 22596 
    [ 2.500,  3.750) = 286963 
    [ 3.750,  5.000) = 9851 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 315 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.304 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     17.465 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.009 ms/op
Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.222 ms/op
                 listUser·p0.9999: 20.042 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 20.357 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.293 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.241 ms/op
                 listUser·p0.9999: 20.877 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248515
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5513 
    [ 2.500,  5.000) = 222215 
    [ 5.000,  7.500) = 19857 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.476 ms/op
     p(99.9900) =     20.485 ms/op
     p(99.9990) =     21.547 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.804 ± 3.485  ops/ms
ClientGrpc.existUser                       thrpt       3  11.264 ± 2.871  ops/ms
ClientGrpc.getUser                         thrpt       3  10.867 ± 2.865  ops/ms
ClientGrpc.listUser                        thrpt       3   8.041 ± 1.794  ops/ms
ClientGrpc.createUser                       avgt       3   2.947 ± 0.200   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.430   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.200   ms/op
ClientGrpc.listUser                         avgt       3   3.828 ± 1.098   ms/op
ClientGrpc.createUser                     sample  318170   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.658           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.541           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.906           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.987           ms/op
ClientGrpc.existUser                      sample  329994   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.761           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  322405   2.975 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.666           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.387           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.533           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.465           ms/op
ClientGrpc.listUser                       sample  248515   3.865 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.293           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.485           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
