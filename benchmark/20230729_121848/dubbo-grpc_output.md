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
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 6.711 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.192 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (8.086, 8.192, 8.272), stdev = 0.096
  CI (99.9%): [6.444, 9.940] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ops/ms
# Warmup Iteration   2: 8.363 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 8.543 ops/ms
Iteration   2: 9.084 ops/ms
Iteration   3: 9.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.968 ±(99.9%) 6.938 ops/ms [Average]
  (min, avg, max) = (8.543, 8.968, 9.277), stdev = 0.380
  CI (99.9%): [2.030, 15.906] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.566 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.317 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.368 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (8.317, 8.368, 8.437), stdev = 0.062
  CI (99.9%): [7.236, 9.500] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ops/ms
# Warmup Iteration   2: 6.204 ops/ms
# Warmup Iteration   3: 6.827 ops/ms
Iteration   1: 6.612 ops/ms
Iteration   2: 6.704 ops/ms
Iteration   3: 6.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.734 ±(99.9%) 2.548 ops/ms [Average]
  (min, avg, max) = (6.612, 6.734, 6.886), stdev = 0.140
  CI (99.9%): [4.186, 9.282] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.014 ms/op
Iteration   1: 3.934 ±(99.9%) 0.004 ms/op
Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
Iteration   3: 3.753 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.860 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.753, 3.860, 3.934), stdev = 0.095
  CI (99.9%): [2.132, 5.589] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.169 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.005 ms/op
Iteration   1: 3.539 ±(99.9%) 0.004 ms/op
Iteration   2: 3.551 ±(99.9%) 0.002 ms/op
Iteration   3: 3.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.543 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (3.538, 3.543, 3.551), stdev = 0.007
  CI (99.9%): [3.417, 3.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.004 ms/op
Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
Iteration   2: 3.853 ±(99.9%) 0.004 ms/op
Iteration   3: 3.787 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.826 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.787, 3.826, 3.853), stdev = 0.034
  CI (99.9%): [3.197, 4.454] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.190 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.117 ±(99.9%) 0.010 ms/op
Iteration   1: 5.064 ±(99.9%) 0.017 ms/op
Iteration   2: 4.877 ±(99.9%) 0.018 ms/op
Iteration   3: 4.863 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.935 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (4.863, 4.935, 5.064), stdev = 0.112
  CI (99.9%): [2.885, 6.984] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.882 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 17.577 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.783 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  11.379 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  14.305 ms/op
                 createUser·p0.9999: 20.431 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254778
  mean =      3.766 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8737 
    [ 2.500,  5.000) = 232189 
    [ 5.000,  7.500) = 12268 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     11.214 ms/op
     p(99.9900) =     26.118 ms/op
     p(99.9990) =     27.358 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 5.206 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.011 ms/op
Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  11.958 ms/op
                 existUser·p0.9999: 21.099 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.702 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  10.855 ms/op
                 existUser·p0.9999: 25.627 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.636 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 22.682 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260022
  mean =      3.691 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7711 
    [ 2.500,  5.000) = 239380 
    [ 5.000,  7.500) = 11094 
    [ 7.500, 10.000) = 1454 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     24.575 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
Iteration   1: 3.784 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.430 ms/op
                 getUser·p0.999:  14.344 ms/op
                 getUser·p0.9999: 17.487 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 3.770 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  11.279 ms/op
                 getUser·p0.9999: 16.893 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  13.274 ms/op
                 getUser·p0.9999: 22.008 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253111
  mean =      3.792 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6124 
    [ 2.500,  5.000) = 234602 
    [ 5.000,  7.500) = 10741 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     12.663 ms/op
     p(99.9900) =     21.609 ms/op
     p(99.9990) =     22.363 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.374 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.407 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.015 ±(99.9%) 0.018 ms/op
Iteration   1: 5.072 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  17.261 ms/op
                 listUser·p0.9999: 29.528 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   2: 4.939 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.312 ms/op
                 listUser·p0.999:  19.102 ms/op
                 listUser·p0.9999: 26.281 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   3: 5.052 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  20.962 ms/op
                 listUser·p0.9999: 25.036 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191176
  mean =      5.020 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 121849 
    [ 5.000,  7.500) = 59919 
    [ 7.500, 10.000) = 7138 
    [10.000, 12.500) = 1142 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     19.524 ms/op
     p(99.9900) =     26.469 ms/op
     p(99.9990) =     29.935 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.192 ± 1.748  ops/ms
ClientGrpc.existUser                       thrpt       3   8.968 ± 6.938  ops/ms
ClientGrpc.getUser                         thrpt       3   8.368 ± 1.132  ops/ms
ClientGrpc.listUser                        thrpt       3   6.734 ± 2.548  ops/ms
ClientGrpc.createUser                       avgt       3   3.860 ± 1.729   ms/op
ClientGrpc.existUser                        avgt       3   3.543 ± 0.126   ms/op
ClientGrpc.getUser                          avgt       3   3.826 ± 0.629   ms/op
ClientGrpc.listUser                         avgt       3   4.935 ± 2.049   ms/op
ClientGrpc.createUser                     sample  254778   3.766 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.855           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.783           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.214           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.118           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  260022   3.691 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.575           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.083           ms/op
ClientGrpc.getUser                        sample  253111   3.792 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.784           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.513           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.663           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.609           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  191176   5.020 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.524           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.469           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
