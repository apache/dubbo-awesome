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
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 6.458 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.498 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (8.406, 8.498, 8.650), stdev = 0.133
  CI (99.9%): [6.078, 10.917] (assumes normal distribution)


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
# Warmup Iteration   1: 5.473 ops/ms
# Warmup Iteration   2: 8.228 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.960 ops/ms
Iteration   2: 8.608 ops/ms
Iteration   3: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.804 ±(99.9%) 3.273 ops/ms [Average]
  (min, avg, max) = (8.608, 8.804, 8.960), stdev = 0.179
  CI (99.9%): [5.531, 12.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ops/ms
# Warmup Iteration   2: 7.798 ops/ms
# Warmup Iteration   3: 8.160 ops/ms
Iteration   1: 8.250 ops/ms
Iteration   2: 8.207 ops/ms
Iteration   3: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.385 ±(99.9%) 4.963 ops/ms [Average]
  (min, avg, max) = (8.207, 8.385, 8.698), stdev = 0.272
  CI (99.9%): [3.421, 13.348] (assumes normal distribution)


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
# Warmup Iteration   1: 5.080 ops/ms
# Warmup Iteration   2: 5.819 ops/ms
# Warmup Iteration   3: 6.374 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.497 ops/ms
Iteration   3: 6.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.530 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (6.467, 6.530, 6.624), stdev = 0.083
  CI (99.9%): [5.011, 8.049] (assumes normal distribution)


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
# Warmup Iteration   1: 5.943 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.008 ms/op
Iteration   1: 3.713 ±(99.9%) 0.008 ms/op
Iteration   2: 3.748 ±(99.9%) 0.006 ms/op
Iteration   3: 3.707 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.723 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.707, 3.723, 3.748), stdev = 0.022
  CI (99.9%): [3.323, 4.122] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.004 ms/op
Iteration   1: 3.550 ±(99.9%) 0.003 ms/op
Iteration   2: 3.539 ±(99.9%) 0.003 ms/op
Iteration   3: 3.522 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.537 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.522, 3.537, 3.550), stdev = 0.014
  CI (99.9%): [3.274, 3.800] (assumes normal distribution)


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
# Warmup Iteration   1: 5.150 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.003 ms/op
Iteration   1: 3.780 ±(99.9%) 0.005 ms/op
Iteration   2: 3.746 ±(99.9%) 0.008 ms/op
Iteration   3: 3.759 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.762 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.746, 3.762, 3.780), stdev = 0.017
  CI (99.9%): [3.446, 4.077] (assumes normal distribution)


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
# Warmup Iteration   1: 6.298 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.250 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.787 ±(99.9%) 0.020 ms/op
Iteration   1: 4.758 ±(99.9%) 0.033 ms/op
Iteration   2: 4.780 ±(99.9%) 0.014 ms/op
Iteration   3: 4.856 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.798 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (4.758, 4.798, 4.856), stdev = 0.051
  CI (99.9%): [3.863, 5.734] (assumes normal distribution)


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
# Warmup Iteration   1: 5.531 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
Iteration   1: 3.692 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  10.368 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.725 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.246 ms/op
                 createUser·p0.999:  13.831 ms/op
                 createUser·p0.9999: 26.901 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.636 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.507 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  15.845 ms/op
                 createUser·p0.9999: 28.351 ms/op
                 createUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260462
  mean =      3.684 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6697 
    [ 2.500,  5.000) = 246898 
    [ 5.000,  7.500) = 5754 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     13.837 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     28.632 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 5.253 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.008 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  16.271 ms/op
                 existUser·p0.9999: 29.049 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   2: 3.486 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.149 ms/op
                 existUser·p0.999:  7.903 ms/op
                 existUser·p0.9999: 17.951 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 3.547 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  15.578 ms/op
                 existUser·p0.9999: 20.838 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274910
  mean =      3.492 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11949 
    [ 2.500,  5.000) = 259245 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.313 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     13.274 ms/op
     p(99.9900) =     23.217 ms/op
     p(99.9990) =     29.516 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.008 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.981 ms/op
                 getUser·p0.999:  14.630 ms/op
                 getUser·p0.9999: 31.247 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   2: 3.698 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  15.395 ms/op
                 getUser·p0.9999: 23.092 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.748 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.699 ms/op
                 getUser·p0.999:  11.036 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256589
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4232 
    [ 2.500,  5.000) = 246823 
    [ 5.000,  7.500) = 4526 
    [ 7.500, 10.000) = 547 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.703 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     31.650 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 7.479 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.020 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.795 ±(99.9%) 0.013 ms/op
Iteration   1: 4.742 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  14.444 ms/op
                 listUser·p0.9999: 24.585 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.708 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.717 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  17.208 ms/op
                 listUser·p0.9999: 27.230 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203224
  mean =      4.723 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 362 
    [ 2.500,  5.000) = 162595 
    [ 5.000,  7.500) = 36273 
    [ 7.500, 10.000) = 3319 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.849 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.498 ± 2.420  ops/ms
ClientGrpc.existUser                       thrpt       3   8.804 ± 3.273  ops/ms
ClientGrpc.getUser                         thrpt       3   8.385 ± 4.963  ops/ms
ClientGrpc.listUser                        thrpt       3   6.530 ± 1.519  ops/ms
ClientGrpc.createUser                       avgt       3   3.723 ± 0.400   ms/op
ClientGrpc.existUser                        avgt       3   3.537 ± 0.263   ms/op
ClientGrpc.getUser                          avgt       3   3.762 ± 0.315   ms/op
ClientGrpc.listUser                         avgt       3   4.798 ± 0.936   ms/op
ClientGrpc.createUser                     sample  260462   3.684 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.792           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.837           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.656           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.738           ms/op
ClientGrpc.existUser                      sample  274910   3.492 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.313           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.274           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.819           ms/op
ClientGrpc.getUser                        sample  256589   3.741 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.134           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.752           ms/op
ClientGrpc.listUser                       sample  203224   4.723 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.423           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.316           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.592           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
