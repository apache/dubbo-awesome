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
# Warmup Iteration   1: 4.999 ops/ms
# Warmup Iteration   2: 9.076 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.206 ±(99.9%) 3.653 ops/ms [Average]
  (min, avg, max) = (10.088, 10.206, 10.437), stdev = 0.200
  CI (99.9%): [6.553, 13.859] (assumes normal distribution)


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
# Warmup Iteration   1: 7.685 ops/ms
# Warmup Iteration   2: 10.506 ops/ms
# Warmup Iteration   3: 10.953 ops/ms
Iteration   1: 10.401 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 11.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.648 ±(99.9%) 6.223 ops/ms [Average]
  (min, avg, max) = (10.401, 10.648, 11.037), stdev = 0.341
  CI (99.9%): [4.425, 16.871] (assumes normal distribution)


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
# Warmup Iteration   1: 6.956 ops/ms
# Warmup Iteration   2: 10.124 ops/ms
# Warmup Iteration   3: 10.075 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.350 ±(99.9%) 5.736 ops/ms [Average]
  (min, avg, max) = (10.049, 10.350, 10.677), stdev = 0.314
  CI (99.9%): [4.614, 16.087] (assumes normal distribution)


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
# Warmup Iteration   1: 6.619 ops/ms
# Warmup Iteration   2: 7.884 ops/ms
# Warmup Iteration   3: 7.916 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.060 ±(99.9%) 1.903 ops/ms [Average]
  (min, avg, max) = (7.963, 8.060, 8.171), stdev = 0.104
  CI (99.9%): [6.157, 9.963] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.004 ms/op
Iteration   2: 3.143 ±(99.9%) 0.004 ms/op
Iteration   3: 3.205 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.159 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.130, 3.159, 3.205), stdev = 0.040
  CI (99.9%): [2.426, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.965 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.989 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.965, 2.989, 3.012), stdev = 0.023
  CI (99.9%): [2.565, 3.414] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.207 ±(99.9%) 0.002 ms/op
Iteration   3: 3.192 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.167 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.102, 3.167, 3.207), stdev = 0.057
  CI (99.9%): [2.128, 4.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.015 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
Iteration   2: 4.065 ±(99.9%) 0.006 ms/op
Iteration   3: 3.986 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.012 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.986, 4.012, 4.065), stdev = 0.046
  CI (99.9%): [3.181, 4.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.242 ms/op
                 createUser·p0.9999: 10.578 ms/op
                 createUser·p1.00:   11.043 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.294 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.442 ms/op
                 createUser·p0.9999: 20.285 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  11.335 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306934
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17041 
    [ 2.500,  5.000) = 288801 
    [ 5.000,  7.500) = 710 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.849 ms/op
     p(99.9900) =     18.917 ms/op
     p(99.9990) =     20.770 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.243 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.163 ms/op
                 existUser·p0.9999: 12.307 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.256 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.259 ms/op
                 existUser·p0.9999: 19.076 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320305
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37463 
    [ 2.500,  5.000) = 281548 
    [ 5.000,  7.500) = 1033 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.243 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.862 ms/op
     p(99.9900) =     17.825 ms/op
     p(99.9990) =     20.336 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.282 ms/op
                 getUser·p0.9999: 12.412 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.722 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.676 ms/op
                 getUser·p0.9999: 13.343 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.155 ms/op
                 getUser·p0.9999: 17.435 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314418
  mean =      3.053 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1977 
    [ 1.250,  2.500) = 20276 
    [ 2.500,  3.750) = 274545 
    [ 3.750,  5.000) = 16485 
    [ 5.000,  6.250) = 796 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.357 ms/op
     p(99.9900) =     16.264 ms/op
     p(99.9990) =     18.322 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.974 ms/op
                 listUser·p0.999:  12.280 ms/op
                 listUser·p0.9999: 18.616 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.039 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.959 ms/op
                 listUser·p0.999:  17.980 ms/op
                 listUser·p0.9999: 22.876 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237198
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3992 
    [ 2.500,  5.000) = 201305 
    [ 5.000,  7.500) = 30540 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.903 ms/op
     p(99.9900) =     22.259 ms/op
     p(99.9990) =     23.196 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.206 ± 3.653  ops/ms
ClientGrpc.existUser                       thrpt       3  10.648 ± 6.223  ops/ms
ClientGrpc.getUser                         thrpt       3  10.350 ± 5.736  ops/ms
ClientGrpc.listUser                        thrpt       3   8.060 ± 1.903  ops/ms
ClientGrpc.createUser                       avgt       3   3.159 ± 0.733   ms/op
ClientGrpc.existUser                        avgt       3   2.989 ± 0.425   ms/op
ClientGrpc.getUser                          avgt       3   3.167 ± 1.039   ms/op
ClientGrpc.listUser                         avgt       3   4.012 ± 0.831   ms/op
ClientGrpc.createUser                     sample  306934   3.126 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.294           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.849           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.917           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.939           ms/op
ClientGrpc.existUser                      sample  320305   2.995 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.243           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.825           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.414           ms/op
ClientGrpc.getUser                        sample  314418   3.053 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.264           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  237198   4.044 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.903           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.259           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
