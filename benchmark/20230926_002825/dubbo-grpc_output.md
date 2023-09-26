# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.745 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 5.814 ops/ms
Iteration   1: 5.798 ops/ms
Iteration   2: 6.192 ops/ms
Iteration   3: 6.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.094 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (5.798, 6.094, 6.292), stdev = 0.261
  CI (99.9%): [1.324, 10.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ops/ms
# Warmup Iteration   2: 5.996 ops/ms
# Warmup Iteration   3: 6.421 ops/ms
Iteration   1: 6.713 ops/ms
Iteration   2: 6.715 ops/ms
Iteration   3: 6.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.689 ±(99.9%) 0.798 ops/ms [Average]
  (min, avg, max) = (6.639, 6.689, 6.715), stdev = 0.044
  CI (99.9%): [5.891, 7.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.303 ops/ms
# Warmup Iteration   2: 5.571 ops/ms
# Warmup Iteration   3: 6.170 ops/ms
Iteration   1: 6.257 ops/ms
Iteration   2: 6.171 ops/ms
Iteration   3: 6.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.268 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (6.171, 6.268, 6.376), stdev = 0.103
  CI (99.9%): [4.390, 8.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 4.542 ops/ms
# Warmup Iteration   3: 4.946 ops/ms
Iteration   1: 4.972 ops/ms
Iteration   2: 5.171 ops/ms
Iteration   3: 5.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.059 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (4.972, 5.059, 5.171), stdev = 0.102
  CI (99.9%): [3.199, 6.919] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.710 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.325 ±(99.9%) 0.007 ms/op
Iteration   1: 5.123 ±(99.9%) 0.004 ms/op
Iteration   2: 4.996 ±(99.9%) 0.004 ms/op
Iteration   3: 4.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.039 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (4.996, 5.039, 5.123), stdev = 0.073
  CI (99.9%): [3.716, 6.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.297 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.321 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.014 ms/op
Iteration   1: 4.760 ±(99.9%) 0.006 ms/op
Iteration   2: 4.723 ±(99.9%) 0.005 ms/op
Iteration   3: 4.649 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.711 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (4.649, 4.711, 4.760), stdev = 0.056
  CI (99.9%): [3.684, 5.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.497 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.108 ±(99.9%) 0.017 ms/op
Iteration   1: 5.070 ±(99.9%) 0.005 ms/op
Iteration   2: 4.995 ±(99.9%) 0.004 ms/op
Iteration   3: 5.094 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.053 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (4.995, 5.053, 5.094), stdev = 0.052
  CI (99.9%): [4.110, 5.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 10.058 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.868 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.525 ±(99.9%) 0.034 ms/op
Iteration   1: 6.374 ±(99.9%) 0.027 ms/op
Iteration   2: 6.190 ±(99.9%) 0.017 ms/op
Iteration   3: 6.557 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.373 ±(99.9%) 3.348 ms/op [Average]
  (min, avg, max) = (6.190, 6.373, 6.557), stdev = 0.184
  CI (99.9%): [3.025, 9.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 8.653 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 5.620 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.018 ms/op
Iteration   1: 4.944 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.041 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  13.200 ms/op
                 createUser·p0.9999: 18.990 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 5.189 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  16.614 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 4.946 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.396 ms/op
                 createUser·p0.999:  22.127 ms/op
                 createUser·p0.9999: 24.757 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 191063
  mean =      5.024 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2499 
    [ 2.500,  5.000) = 107721 
    [ 5.000,  7.500) = 74138 
    [ 7.500, 10.000) = 5122 
    [10.000, 12.500) = 972 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     18.381 ms/op
     p(99.9900) =     24.008 ms/op
     p(99.9990) =     25.076 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 7.146 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.203 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.017 ms/op
Iteration   1: 4.885 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.742 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  14.905 ms/op
                 existUser·p0.9999: 31.712 ms/op
                 existUser·p1.00:   32.408 ms/op

Iteration   2: 4.797 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   6.693 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 28.300 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 4.726 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   8.820 ms/op
                 existUser·p0.999:  12.015 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 199908
  mean =      4.802 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3445 
    [ 2.500,  5.000) = 127359 
    [ 5.000,  7.500) = 63766 
    [ 7.500, 10.000) = 4151 
    [10.000, 12.500) = 796 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     31.032 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.516 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.144 ±(99.9%) 0.017 ms/op
Iteration   1: 5.074 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.060 ms/op
                 getUser·p0.999:  14.072 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 4.998 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 5.039 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  18.333 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 190635
  mean =      5.037 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2848 
    [ 2.500,  5.000) = 103182 
    [ 5.000,  7.500) = 78561 
    [ 7.500, 10.000) = 4781 
    [10.000, 12.500) = 806 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     14.708 ms/op
     p(99.9900) =     27.552 ms/op
     p(99.9990) =     28.392 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.319 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 7.210 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.693 ±(99.9%) 0.029 ms/op
Iteration   1: 6.701 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   9.142 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 21.493 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 6.658 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   9.224 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   13.631 ms/op
                 listUser·p0.999:  19.754 ms/op
                 listUser·p0.9999: 29.483 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   3: 6.497 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  22.643 ms/op
                 listUser·p0.9999: 26.744 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 145103
  mean =      6.618 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 21613 
    [ 5.000,  7.500) = 88884 
    [ 7.500, 10.000) = 26020 
    [10.000, 12.500) = 6204 
    [12.500, 15.000) = 1738 
    [15.000, 17.500) = 301 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      9.110 ms/op
     p(95.0000) =     10.289 ms/op
     p(99.0000) =     13.303 ms/op
     p(99.9000) =     20.440 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     31.380 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.094 ± 4.770  ops/ms
ClientGrpc.existUser                       thrpt       3   6.689 ± 0.798  ops/ms
ClientGrpc.getUser                         thrpt       3   6.268 ± 1.877  ops/ms
ClientGrpc.listUser                        thrpt       3   5.059 ± 1.860  ops/ms
ClientGrpc.createUser                       avgt       3   5.039 ± 1.324   ms/op
ClientGrpc.existUser                        avgt       3   4.711 ± 1.027   ms/op
ClientGrpc.getUser                          avgt       3   5.053 ± 0.944   ms/op
ClientGrpc.listUser                         avgt       3   6.373 ± 3.348   ms/op
ClientGrpc.createUser                     sample  191063   5.024 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.137           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.102           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.585           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.381           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.008           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  199908   4.802 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.815           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.070           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.175           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.032           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.408           ms/op
ClientGrpc.getUser                        sample  190635   5.037 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.145           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.382           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.241           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.708           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.552           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.541           ms/op
ClientGrpc.listUser                       sample  145103   6.618 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.743           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.289           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.303           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.440           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.214           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
