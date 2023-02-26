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
# Warmup Iteration   1: 4.719 ops/ms
# Warmup Iteration   2: 9.277 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 10.260 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.221 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (10.179, 10.221, 10.260), stdev = 0.040
  CI (99.9%): [9.483, 10.959] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 10.789 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.912 ops/ms
Iteration   2: 10.946 ops/ms
Iteration   3: 10.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.908 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (10.866, 10.908, 10.946), stdev = 0.040
  CI (99.9%): [10.175, 11.642] (assumes normal distribution)


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
# Warmup Iteration   1: 8.291 ops/ms
# Warmup Iteration   2: 10.125 ops/ms
# Warmup Iteration   3: 10.392 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.264 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (10.194, 10.264, 10.316), stdev = 0.063
  CI (99.9%): [9.111, 11.417] (assumes normal distribution)


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
# Warmup Iteration   1: 5.697 ops/ms
# Warmup Iteration   2: 7.612 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 7.821 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.044 ±(99.9%) 3.604 ops/ms [Average]
  (min, avg, max) = (7.821, 8.044, 8.197), stdev = 0.198
  CI (99.9%): [4.440, 11.648] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.102, 3.141, 3.161), stdev = 0.034
  CI (99.9%): [2.526, 3.757] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.002 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.032 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.018, 3.032, 3.049), stdev = 0.016
  CI (99.9%): [2.744, 3.320] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.155 ±(99.9%) 0.002 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.155 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.128, 3.155, 3.182), stdev = 0.027
  CI (99.9%): [2.658, 3.652] (assumes normal distribution)


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.016 ms/op
Iteration   1: 3.943 ±(99.9%) 0.008 ms/op
Iteration   2: 4.131 ±(99.9%) 0.027 ms/op
Iteration   3: 3.944 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.006 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (3.943, 4.006, 4.131), stdev = 0.108
  CI (99.9%): [2.031, 5.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.225 ms/op
                 createUser·p0.9999: 16.007 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.056 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  14.631 ms/op
                 createUser·p0.9999: 32.498 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302726
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19550 
    [ 2.500,  5.000) = 281878 
    [ 5.000,  7.500) = 841 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.343 ms/op
     p(99.9900) =     31.594 ms/op
     p(99.9990) =     32.865 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.239 ms/op
                 existUser·p0.9999: 11.290 ms/op
                 existUser·p1.00:   12.042 ms/op

Iteration   2: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.176 ms/op
                 existUser·p0.9999: 16.242 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.149 ms/op
                 existUser·p0.9999: 14.764 ms/op
                 existUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325125
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3607 
    [ 1.250,  2.500) = 45531 
    [ 2.500,  3.750) = 257143 
    [ 3.750,  5.000) = 18074 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.577 ms/op
     p(99.9900) =     15.556 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.350 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.103 ms/op
                 getUser·p0.9999: 17.425 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.527 ms/op
                 getUser·p0.9999: 13.997 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.637 ms/op
                 getUser·p0.9999: 16.012 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313437
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1962 
    [ 1.250,  2.500) = 24319 
    [ 2.500,  3.750) = 263237 
    [ 3.750,  5.000) = 22614 
    [ 5.000,  6.250) = 720 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.333 ms/op
     p(99.9900) =     16.574 ms/op
     p(99.9990) =     18.173 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.798 ms/op
                 listUser·p0.999:  12.287 ms/op
                 listUser·p0.9999: 14.008 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   2: 3.882 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.506 ms/op
                 listUser·p0.999:  13.953 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244280
  mean =      3.928 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2825 
    [ 2.500,  5.000) = 221584 
    [ 5.000,  7.500) = 18985 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     27.799 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.221 ± 0.738  ops/ms
ClientGrpc.existUser                       thrpt       3  10.908 ± 0.733  ops/ms
ClientGrpc.getUser                         thrpt       3  10.264 ± 1.153  ops/ms
ClientGrpc.listUser                        thrpt       3   8.044 ± 3.604  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 0.615   ms/op
ClientGrpc.existUser                        avgt       3   3.032 ± 0.288   ms/op
ClientGrpc.getUser                          avgt       3   3.155 ± 0.497   ms/op
ClientGrpc.listUser                         avgt       3   4.006 ± 1.975   ms/op
ClientGrpc.createUser                     sample  302726   3.171 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.510           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.343           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.594           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.965           ms/op
ClientGrpc.existUser                      sample  325125   2.951 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.577           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  313437   3.063 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.350           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.333           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.574           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.350           ms/op
ClientGrpc.listUser                       sample  244280   3.928 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.772           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.271           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.673           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
