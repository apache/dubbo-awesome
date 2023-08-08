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
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 6.925 ops/ms
Iteration   1: 7.196 ops/ms
Iteration   2: 7.384 ops/ms
Iteration   3: 7.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.339 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (7.196, 7.339, 7.436), stdev = 0.126
  CI (99.9%): [5.036, 9.642] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ops/ms
# Warmup Iteration   2: 7.114 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.077 ±(99.9%) 3.447 ops/ms [Average]
  (min, avg, max) = (7.957, 8.077, 8.295), stdev = 0.189
  CI (99.9%): [4.630, 11.524] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ops/ms
# Warmup Iteration   2: 6.640 ops/ms
# Warmup Iteration   3: 7.189 ops/ms
Iteration   1: 7.269 ops/ms
Iteration   2: 7.320 ops/ms
Iteration   3: 7.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.375 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (7.269, 7.375, 7.535), stdev = 0.141
  CI (99.9%): [4.805, 9.945] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.431 ops/ms
# Warmup Iteration   2: 5.151 ops/ms
# Warmup Iteration   3: 5.484 ops/ms
Iteration   1: 5.502 ops/ms
Iteration   2: 5.796 ops/ms
Iteration   3: 5.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.669 ±(99.9%) 2.758 ops/ms [Average]
  (min, avg, max) = (5.502, 5.669, 5.796), stdev = 0.151
  CI (99.9%): [2.912, 8.427] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.112 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.004 ms/op
Iteration   1: 4.281 ±(99.9%) 0.004 ms/op
Iteration   2: 4.340 ±(99.9%) 0.005 ms/op
Iteration   3: 4.335 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.319 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (4.281, 4.319, 4.340), stdev = 0.033
  CI (99.9%): [3.722, 4.915] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.840 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.003 ms/op
Iteration   2: 3.954 ±(99.9%) 0.003 ms/op
Iteration   3: 3.899 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.931 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.899, 3.931, 3.954), stdev = 0.029
  CI (99.9%): [3.411, 4.451] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.290 ±(99.9%) 0.009 ms/op
Iteration   1: 4.194 ±(99.9%) 0.004 ms/op
Iteration   2: 4.233 ±(99.9%) 0.004 ms/op
Iteration   3: 4.245 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.224 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (4.194, 4.224, 4.245), stdev = 0.027
  CI (99.9%): [3.733, 4.715] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.350 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.809 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.018 ms/op
Iteration   1: 5.458 ±(99.9%) 0.027 ms/op
Iteration   2: 5.612 ±(99.9%) 0.018 ms/op
Iteration   3: 5.658 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.576 ±(99.9%) 1.912 ms/op [Average]
  (min, avg, max) = (5.458, 5.576, 5.658), stdev = 0.105
  CI (99.9%): [3.664, 7.488] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.454 ±(99.9%) 0.016 ms/op
Iteration   1: 4.292 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  16.712 ms/op
                 createUser·p0.9999: 21.547 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 4.330 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   8.274 ms/op
                 createUser·p0.999:  12.718 ms/op
                 createUser·p0.9999: 21.909 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 4.329 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.737 ms/op
                 createUser·p0.999:  14.664 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222372
  mean =      4.317 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8485 
    [ 2.500,  5.000) = 175148 
    [ 5.000,  7.500) = 35135 
    [ 7.500, 10.000) = 2539 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     14.428 ms/op
     p(99.9900) =     28.034 ms/op
     p(99.9990) =     29.109 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.065 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.014 ms/op
Iteration   1: 4.114 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   8.205 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 4.142 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.823 ms/op
                 existUser·p0.999:  13.641 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 4.208 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   8.817 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 23.108 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230923
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8954 
    [ 2.500,  5.000) = 191064 
    [ 5.000,  7.500) = 27509 
    [ 7.500, 10.000) = 2475 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     22.246 ms/op
     p(99.9990) =     23.628 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 6.611 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.013 ms/op
Iteration   1: 4.551 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  12.549 ms/op
                 getUser·p0.9999: 17.497 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 4.427 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  12.951 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.405 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  15.997 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215199
  mean =      4.460 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3978 
    [ 2.500,  5.000) = 163683 
    [ 5.000,  7.500) = 43904 
    [ 7.500, 10.000) = 2842 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     13.661 ms/op
     p(99.9900) =     32.915 ms/op
     p(99.9990) =     36.090 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 7.983 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.082 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.630 ±(99.9%) 0.022 ms/op
Iteration   1: 5.702 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.129 ms/op
                 listUser·p0.999:  17.329 ms/op
                 listUser·p0.9999: 23.814 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   2: 5.715 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.475 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 21.425 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 5.677 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  22.277 ms/op
                 listUser·p0.9999: 31.752 ms/op
                 listUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168463
  mean =      5.698 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 54082 
    [ 5.000,  7.500) = 97370 
    [ 7.500, 10.000) = 13474 
    [10.000, 12.500) = 2373 
    [12.500, 15.000) = 562 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.504 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     30.643 ms/op
     p(99.9990) =     32.451 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.339 ± 2.303  ops/ms
ClientGrpc.existUser                       thrpt       3   8.077 ± 3.447  ops/ms
ClientGrpc.getUser                         thrpt       3   7.375 ± 2.570  ops/ms
ClientGrpc.listUser                        thrpt       3   5.669 ± 2.758  ops/ms
ClientGrpc.createUser                       avgt       3   4.319 ± 0.597   ms/op
ClientGrpc.existUser                        avgt       3   3.931 ± 0.520   ms/op
ClientGrpc.getUser                          avgt       3   4.224 ± 0.491   ms/op
ClientGrpc.listUser                         avgt       3   5.576 ± 1.912   ms/op
ClientGrpc.createUser                     sample  222372   4.317 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.900           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.428           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.034           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  230923   4.154 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.298           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.287           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.246           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  215199   4.460 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.137           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.421           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.661           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.915           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.307           ms/op
ClientGrpc.listUser                       sample  168463   5.698 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.728           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.504           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.338           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.473           ms/op
