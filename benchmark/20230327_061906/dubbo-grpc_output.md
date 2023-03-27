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
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 9.268 ops/ms
# Warmup Iteration   3: 10.351 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.769 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.638 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (10.532, 10.638, 10.769), stdev = 0.120
  CI (99.9%): [8.444, 12.833] (assumes normal distribution)


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
# Warmup Iteration   1: 7.742 ops/ms
# Warmup Iteration   2: 10.658 ops/ms
# Warmup Iteration   3: 11.121 ops/ms
Iteration   1: 11.115 ops/ms
Iteration   2: 11.192 ops/ms
Iteration   3: 11.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.289 ±(99.9%) 4.344 ops/ms [Average]
  (min, avg, max) = (11.115, 11.289, 11.561), stdev = 0.238
  CI (99.9%): [6.945, 15.633] (assumes normal distribution)


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
# Warmup Iteration   1: 7.162 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.624 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (10.544, 10.624, 10.714), stdev = 0.086
  CI (99.9%): [9.062, 12.186] (assumes normal distribution)


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
# Warmup Iteration   1: 5.413 ops/ms
# Warmup Iteration   2: 7.801 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.418 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.366 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (8.324, 8.366, 8.418), stdev = 0.048
  CI (99.9%): [7.492, 9.240] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.960, 2.975, 2.996), stdev = 0.019
  CI (99.9%): [2.629, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.002 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.002 ms/op
Iteration   3: 2.953 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.941 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.919, 2.941, 2.953), stdev = 0.020
  CI (99.9%): [2.582, 3.300] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.004 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.997, 3.004, 3.013), stdev = 0.008
  CI (99.9%): [2.851, 3.156] (assumes normal distribution)


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
# Warmup Iteration   1: 5.414 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.018 ms/op
Iteration   1: 3.855 ±(99.9%) 0.013 ms/op
Iteration   2: 3.826 ±(99.9%) 0.028 ms/op
Iteration   3: 3.950 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.877 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.826, 3.877, 3.950), stdev = 0.065
  CI (99.9%): [2.693, 5.060] (assumes normal distribution)


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.846 ms/op
                 createUser·p0.9999: 20.393 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.554 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.206 ms/op
                 createUser·p0.9999: 21.214 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319466
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23936 
    [ 2.500,  5.000) = 293992 
    [ 5.000,  7.500) = 1172 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.385 ms/op
     p(99.9900) =     20.580 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.005 ms/op
Iteration   1: 2.835 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  5.964 ms/op
                 existUser·p0.9999: 12.173 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.005 ms/op
                 existUser·p0.999:  6.434 ms/op
                 existUser·p0.9999: 13.187 ms/op
                 existUser·p1.00:   15.729 ms/op

Iteration   3: 2.807 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 16.259 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338296
  mean =      2.839 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1539 
    [ 1.250,  2.500) = 47337 
    [ 2.500,  3.750) = 283245 
    [ 3.750,  5.000) = 5515 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =      6.396 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     17.420 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.794 ms/op
                 getUser·p0.9999: 12.777 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.215 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 2.968 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  6.210 ms/op
                 getUser·p0.9999: 21.818 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320757
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20772 
    [ 2.500,  5.000) = 298670 
    [ 5.000,  7.500) = 997 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.459 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.009 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.220 ms/op
                 listUser·p0.9999: 16.427 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.683 ms/op
                 listUser·p0.9999: 18.075 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250339
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3599 
    [ 2.500,  5.000) = 228887 
    [ 5.000,  7.500) = 16965 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     14.183 ms/op
     p(99.9900) =     18.775 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.638 ± 2.195  ops/ms
ClientGrpc.existUser                       thrpt       3  11.289 ± 4.344  ops/ms
ClientGrpc.getUser                         thrpt       3  10.624 ± 1.562  ops/ms
ClientGrpc.listUser                        thrpt       3   8.366 ± 0.874  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.346   ms/op
ClientGrpc.existUser                        avgt       3   2.941 ± 0.359   ms/op
ClientGrpc.getUser                          avgt       3   3.004 ± 0.153   ms/op
ClientGrpc.listUser                         avgt       3   3.877 ± 1.184   ms/op
ClientGrpc.createUser                     sample  319466   3.007 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.522           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.385           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.580           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  338296   2.839 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.587           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.232           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.396           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.827           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  320757   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.459           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  250339   3.836 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.183           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.775           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.808           ms/op
