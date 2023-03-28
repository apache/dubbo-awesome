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
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 8.933 ops/ms
# Warmup Iteration   3: 9.662 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.544 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (10.404, 10.544, 10.647), stdev = 0.126
  CI (99.9%): [8.244, 12.845] (assumes normal distribution)


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
# Warmup Iteration   1: 7.586 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.954 ops/ms
Iteration   1: 11.099 ops/ms
Iteration   2: 11.085 ops/ms
Iteration   3: 10.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.051 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (10.968, 11.051, 11.099), stdev = 0.072
  CI (99.9%): [9.739, 12.363] (assumes normal distribution)


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
# Warmup Iteration   1: 6.993 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.515 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.653 ±(99.9%) 0.775 ops/ms [Average]
  (min, avg, max) = (10.611, 10.653, 10.696), stdev = 0.042
  CI (99.9%): [9.878, 11.428] (assumes normal distribution)


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
# Warmup Iteration   1: 5.860 ops/ms
# Warmup Iteration   2: 7.929 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 8.226 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.263 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (8.146, 8.263, 8.415), stdev = 0.138
  CI (99.9%): [5.739, 10.786] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.018 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.000, 3.018, 3.047), stdev = 0.025
  CI (99.9%): [2.554, 3.482] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.002 ms/op
Iteration   2: 2.921 ±(99.9%) 0.002 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (2.864, 2.908, 2.939), stdev = 0.039
  CI (99.9%): [2.194, 3.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.016 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.010, 3.016, 3.027), stdev = 0.009
  CI (99.9%): [2.854, 3.179] (assumes normal distribution)


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.030 ms/op
Iteration   1: 3.879 ±(99.9%) 0.015 ms/op
Iteration   2: 3.834 ±(99.9%) 0.010 ms/op
Iteration   3: 3.981 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (3.834, 3.898, 3.981), stdev = 0.075
  CI (99.9%): [2.525, 5.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.527 ms/op
                 createUser·p0.999:  6.553 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   2: 2.956 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  7.996 ms/op
                 createUser·p0.9999: 15.879 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.477 ms/op
                 createUser·p0.999:  9.643 ms/op
                 createUser·p0.9999: 17.810 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314959
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1140 
    [ 1.250,  2.500) = 25387 
    [ 2.500,  3.750) = 265436 
    [ 3.750,  5.000) = 21316 
    [ 5.000,  6.250) = 985 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     16.991 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.460 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 13.776 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.954 ms/op
                 existUser·p0.9999: 16.678 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331727
  mean =      2.893 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1498 
    [ 1.250,  2.500) = 41241 
    [ 2.500,  3.750) = 280192 
    [ 3.750,  5.000) = 7701 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.539 ms/op
     p(99.9900) =     15.772 ms/op
     p(99.9990) =     17.094 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.503 ms/op
                 getUser·p0.999:  7.898 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 14.933 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.788 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318979
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 728 
    [ 1.250,  2.500) = 22601 
    [ 2.500,  3.750) = 282391 
    [ 3.750,  5.000) = 11891 
    [ 5.000,  6.250) = 728 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     18.672 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 5.081 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.009 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.452 ms/op
                 listUser·p0.9999: 16.101 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  14.512 ms/op
                 listUser·p0.9999: 24.303 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.136 ms/op
                 listUser·p0.9999: 23.966 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249260
  mean =      3.854 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2450 
    [ 2.500,  5.000) = 229822 
    [ 5.000,  7.500) = 16049 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     14.049 ms/op
     p(99.9900) =     23.792 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.544 ± 2.300  ops/ms
ClientGrpc.existUser                       thrpt       3  11.051 ± 1.312  ops/ms
ClientGrpc.getUser                         thrpt       3  10.653 ± 0.775  ops/ms
ClientGrpc.listUser                        thrpt       3   8.263 ± 2.523  ops/ms
ClientGrpc.createUser                       avgt       3   3.018 ± 0.464   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.715   ms/op
ClientGrpc.getUser                          avgt       3   3.016 ± 0.162   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 1.373   ms/op
ClientGrpc.createUser                     sample  314959   3.047 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.991           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.990           ms/op
ClientGrpc.existUser                      sample  331727   2.893 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.648           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.772           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.105           ms/op
ClientGrpc.getUser                        sample  318979   3.006 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.776           ms/op
ClientGrpc.listUser                       sample  249260   3.854 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.040           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.049           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.792           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.904           ms/op
