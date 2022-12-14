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
# Warmup Iteration   1: 4.429 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.605 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.232 ±(99.9%) 3.462 ops/ms [Average]
  (min, avg, max) = (10.084, 10.232, 10.446), stdev = 0.190
  CI (99.9%): [6.770, 13.694] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.888 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.643 ops/ms
Iteration   1: 11.022 ops/ms
Iteration   2: 10.838 ops/ms
Iteration   3: 10.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.897 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (10.831, 10.897, 11.022), stdev = 0.108
  CI (99.9%): [8.922, 12.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.313 ops/ms
# Warmup Iteration   2: 10.068 ops/ms
# Warmup Iteration   3: 10.213 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.407 ±(99.9%) 1.101 ops/ms [Average]
  (min, avg, max) = (10.362, 10.407, 10.475), stdev = 0.060
  CI (99.9%): [9.306, 11.508] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.960 ops/ms
# Warmup Iteration   2: 7.650 ops/ms
# Warmup Iteration   3: 7.884 ops/ms
Iteration   1: 7.886 ops/ms
Iteration   2: 7.855 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.921 ±(99.9%) 1.639 ops/ms [Average]
  (min, avg, max) = (7.855, 7.921, 8.024), stdev = 0.090
  CI (99.9%): [6.282, 9.561] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.011 ms/op
Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
Iteration   3: 3.128 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (3.030, 3.116, 3.190), stdev = 0.080
  CI (99.9%): [1.651, 4.581] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.008 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (2.950, 3.008, 3.053), stdev = 0.053
  CI (99.9%): [2.044, 3.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.064, 3.104, 3.129), stdev = 0.035
  CI (99.9%): [2.459, 3.749] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.624 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.039 ms/op
Iteration   1: 3.874 ±(99.9%) 0.010 ms/op
Iteration   2: 3.831 ±(99.9%) 0.012 ms/op
Iteration   3: 3.971 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (3.831, 3.892, 3.971), stdev = 0.072
  CI (99.9%): [2.585, 5.199] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.202 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.086 ms/op
                 createUser·p0.9999: 13.943 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.241 ms/op
                 createUser·p0.9999: 14.382 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  11.606 ms/op
                 createUser·p0.9999: 27.445 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306612
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24504 
    [ 2.500,  5.000) = 280897 
    [ 5.000,  7.500) = 731 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.934 ms/op
     p(99.9900) =     26.586 ms/op
     p(99.9990) =     27.912 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 13.558 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 14.616 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 16.965 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320381
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1671 
    [ 1.250,  2.500) = 44565 
    [ 2.500,  3.750) = 251303 
    [ 3.750,  5.000) = 22098 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 122 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.428 ms/op
     p(99.9900) =     16.327 ms/op
     p(99.9990) =     18.879 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 12.478 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.364 ms/op
                 getUser·p0.9999: 15.312 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.839 ms/op
                 getUser·p0.9999: 28.379 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312202
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30657 
    [ 2.500,  5.000) = 280486 
    [ 5.000,  7.500) = 786 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     29.991 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
Iteration   1: 3.966 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 15.007 ms/op
                 listUser·p1.00:   16.204 ms/op

Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.496 ms/op
                 listUser·p0.9999: 16.115 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.059 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244700
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2190 
    [ 2.500,  5.000) = 221108 
    [ 5.000,  7.500) = 20410 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.325 ms/op
     p(99.9900) =     20.432 ms/op
     p(99.9990) =     22.482 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.232 ± 3.462  ops/ms
ClientGrpc.existUser                       thrpt       3  10.897 ± 1.975  ops/ms
ClientGrpc.getUser                         thrpt       3  10.407 ± 1.101  ops/ms
ClientGrpc.listUser                        thrpt       3   7.921 ± 1.639  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 1.465   ms/op
ClientGrpc.existUser                        avgt       3   3.008 ± 0.964   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.645   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 1.307   ms/op
ClientGrpc.createUser                     sample  306612   3.131 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.934           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.586           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.082           ms/op
ClientGrpc.existUser                      sample  320381   2.995 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.428           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.327           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  312202   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.780           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.722           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.278           ms/op
ClientGrpc.listUser                       sample  244700   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.007           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.325           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.432           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
