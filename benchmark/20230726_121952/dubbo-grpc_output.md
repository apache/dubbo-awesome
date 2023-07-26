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
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 6.420 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 8.304 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 8.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.517 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (8.304, 8.517, 8.636), stdev = 0.185
  CI (99.9%): [5.142, 11.892] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.957 ops/ms
# Warmup Iteration   2: 8.690 ops/ms
# Warmup Iteration   3: 8.848 ops/ms
Iteration   1: 9.131 ops/ms
Iteration   2: 9.313 ops/ms
Iteration   3: 9.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.356 ±(99.9%) 4.555 ops/ms [Average]
  (min, avg, max) = (9.131, 9.356, 9.625), stdev = 0.250
  CI (99.9%): [4.801, 13.911] (assumes normal distribution)


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
# Warmup Iteration   1: 5.396 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 8.889 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.595 ±(99.9%) 4.782 ops/ms [Average]
  (min, avg, max) = (8.385, 8.595, 8.889), stdev = 0.262
  CI (99.9%): [3.813, 13.378] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ops/ms
# Warmup Iteration   2: 6.097 ops/ms
# Warmup Iteration   3: 6.621 ops/ms
Iteration   1: 6.619 ops/ms
Iteration   2: 6.331 ops/ms
Iteration   3: 6.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.424 ±(99.9%) 3.083 ops/ms [Average]
  (min, avg, max) = (6.323, 6.424, 6.619), stdev = 0.169
  CI (99.9%): [3.341, 9.508] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.477 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.005 ms/op
Iteration   1: 3.777 ±(99.9%) 0.003 ms/op
Iteration   2: 3.781 ±(99.9%) 0.006 ms/op
Iteration   3: 3.734 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.764 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.734, 3.764, 3.781), stdev = 0.026
  CI (99.9%): [3.288, 4.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.002 ms/op
Iteration   1: 3.534 ±(99.9%) 0.001 ms/op
Iteration   2: 3.581 ±(99.9%) 0.003 ms/op
Iteration   3: 3.636 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.584 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.534, 3.584, 3.636), stdev = 0.051
  CI (99.9%): [2.655, 4.512] (assumes normal distribution)


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
# Warmup Iteration   1: 5.349 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.005 ms/op
Iteration   1: 3.741 ±(99.9%) 0.004 ms/op
Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
Iteration   3: 3.653 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.724 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.653, 3.724, 3.778), stdev = 0.064
  CI (99.9%): [2.548, 4.899] (assumes normal distribution)


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
# Warmup Iteration   1: 6.941 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.008 ±(99.9%) 0.015 ms/op
Iteration   1: 4.882 ±(99.9%) 0.009 ms/op
Iteration   2: 4.881 ±(99.9%) 0.018 ms/op
Iteration   3: 4.663 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.809 ±(99.9%) 2.301 ms/op [Average]
  (min, avg, max) = (4.663, 4.809, 4.882), stdev = 0.126
  CI (99.9%): [2.508, 7.110] (assumes normal distribution)


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
# Warmup Iteration   1: 5.847 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.009 ms/op
Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.977 ms/op
                 createUser·p0.999:  13.522 ms/op
                 createUser·p0.9999: 15.739 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  13.741 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   3: 3.772 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  11.981 ms/op
                 createUser·p0.9999: 19.269 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254031
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 5948 
    [ 2.500,  3.750) = 135751 
    [ 3.750,  5.000) = 99338 
    [ 5.000,  6.250) = 9323 
    [ 6.250,  7.500) = 2065 
    [ 7.500,  8.750) = 690 
    [ 8.750, 10.000) = 342 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 85 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.706 ms/op
     p(99.9900) =     17.518 ms/op
     p(99.9990) =     19.766 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 5.353 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.009 ms/op
Iteration   1: 3.564 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  8.833 ms/op
                 existUser·p0.9999: 15.385 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 3.564 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.848 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 18.089 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.394 ms/op
                 existUser·p0.9999: 20.272 ms/op
                 existUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271246
  mean =      3.539 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11874 
    [ 2.500,  5.000) = 252168 
    [ 5.000,  7.500) = 6508 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     20.466 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.652 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  10.865 ms/op
                 getUser·p0.9999: 15.532 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.177 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 17.657 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 3.783 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 25.577 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 244851
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10732 
    [ 2.500,  5.000) = 212609 
    [ 5.000,  7.500) = 19538 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     12.176 ms/op
     p(99.9900) =     23.872 ms/op
     p(99.9990) =     26.393 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 7.034 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.455 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.018 ms/op
Iteration   1: 5.002 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.830 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  17.050 ms/op
                 listUser·p0.9999: 25.317 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.888 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.463 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  18.061 ms/op
                 listUser·p0.9999: 29.259 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   3: 4.892 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   10.016 ms/op
                 listUser·p0.999:  22.139 ms/op
                 listUser·p0.9999: 38.797 ms/op
                 listUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194710
  mean =      4.927 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 793 
    [ 2.500,  5.000) = 131361 
    [ 5.000,  7.500) = 52713 
    [ 7.500, 10.000) = 8210 
    [10.000, 12.500) = 977 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     19.113 ms/op
     p(99.9900) =     38.177 ms/op
     p(99.9990) =     38.997 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.517 ± 3.375  ops/ms
ClientGrpc.existUser                       thrpt       3   9.356 ± 4.555  ops/ms
ClientGrpc.getUser                         thrpt       3   8.595 ± 4.782  ops/ms
ClientGrpc.listUser                        thrpt       3   6.424 ± 3.083  ops/ms
ClientGrpc.createUser                       avgt       3   3.764 ± 0.476   ms/op
ClientGrpc.existUser                        avgt       3   3.584 ± 0.928   ms/op
ClientGrpc.getUser                          avgt       3   3.724 ± 1.176   ms/op
ClientGrpc.listUser                         avgt       3   4.809 ± 2.301   ms/op
ClientGrpc.createUser                     sample  254031   3.780 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.706           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.518           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  271246   3.539 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.546           ms/op
ClientGrpc.getUser                        sample  244851   3.922 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.836           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.209           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.872           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.670           ms/op
ClientGrpc.listUser                       sample  194710   4.927 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.048           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.113           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.177           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.059           ms/op
