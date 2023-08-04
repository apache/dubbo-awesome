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
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 6.328 ops/ms
# Warmup Iteration   3: 7.903 ops/ms
Iteration   1: 8.345 ops/ms
Iteration   2: 8.416 ops/ms
Iteration   3: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.398 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (8.345, 8.398, 8.433), stdev = 0.046
  CI (99.9%): [7.551, 9.244] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.398 ops/ms
# Warmup Iteration   2: 8.365 ops/ms
# Warmup Iteration   3: 8.733 ops/ms
Iteration   1: 8.892 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 9.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.866 ±(99.9%) 3.726 ops/ms [Average]
  (min, avg, max) = (8.650, 8.866, 9.056), stdev = 0.204
  CI (99.9%): [5.140, 12.593] (assumes normal distribution)


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
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 7.811 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.553 ops/ms
Iteration   3: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.508 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (8.428, 8.508, 8.553), stdev = 0.070
  CI (99.9%): [7.235, 9.781] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ops/ms
# Warmup Iteration   2: 6.042 ops/ms
# Warmup Iteration   3: 6.391 ops/ms
Iteration   1: 6.446 ops/ms
Iteration   2: 6.452 ops/ms
Iteration   3: 6.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.485 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (6.446, 6.485, 6.558), stdev = 0.063
  CI (99.9%): [5.336, 7.634] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.005 ms/op
Iteration   1: 3.695 ±(99.9%) 0.004 ms/op
Iteration   2: 3.851 ±(99.9%) 0.004 ms/op
Iteration   3: 3.798 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.782 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.695, 3.782, 3.851), stdev = 0.079
  CI (99.9%): [2.337, 5.226] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.963 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.004 ms/op
Iteration   1: 3.624 ±(99.9%) 0.004 ms/op
Iteration   2: 3.609 ±(99.9%) 0.003 ms/op
Iteration   3: 3.659 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.631 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.609, 3.631, 3.659), stdev = 0.026
  CI (99.9%): [3.162, 4.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.010 ms/op
Iteration   1: 3.899 ±(99.9%) 0.004 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.764 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.810 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.764, 3.810, 3.899), stdev = 0.077
  CI (99.9%): [2.407, 5.213] (assumes normal distribution)


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
# Warmup Iteration   1: 6.285 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.799 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.011 ms/op
Iteration   1: 4.916 ±(99.9%) 0.016 ms/op
Iteration   2: 4.931 ±(99.9%) 0.015 ms/op
Iteration   3: 5.039 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.962 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (4.916, 4.962, 5.039), stdev = 0.067
  CI (99.9%): [3.742, 6.182] (assumes normal distribution)


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
# Warmup Iteration   1: 5.758 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.013 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  12.594 ms/op
                 createUser·p0.9999: 18.791 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.746 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  13.435 ms/op
                 createUser·p0.9999: 17.793 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  9.847 ms/op
                 createUser·p0.9999: 27.385 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256904
  mean =      3.735 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8924 
    [ 2.500,  5.000) = 238702 
    [ 5.000,  7.500) = 7842 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     12.421 ms/op
     p(99.9900) =     26.310 ms/op
     p(99.9990) =     27.755 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 5.271 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.009 ms/op
Iteration   1: 3.529 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  11.990 ms/op
                 existUser·p0.9999: 15.448 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 3.671 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.326 ms/op
                 existUser·p0.999:  10.943 ms/op
                 existUser·p0.9999: 16.569 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.690 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.293 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 36.110 ms/op
                 existUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264494
  mean =      3.628 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7893 
    [ 2.500,  5.000) = 248641 
    [ 5.000,  7.500) = 6821 
    [ 7.500, 10.000) = 788 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     35.622 ms/op
     p(99.9990) =     36.199 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 5.442 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.011 ms/op
Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 15.313 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   2: 3.775 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  12.810 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.816 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  13.423 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253197
  mean =      3.793 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7579 
    [ 2.500,  5.000) = 234245 
    [ 5.000,  7.500) = 9980 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     12.596 ms/op
     p(99.9900) =     23.048 ms/op
     p(99.9990) =     23.919 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 5.911 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.521 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.944 ±(99.9%) 0.015 ms/op
Iteration   1: 4.919 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.127 ms/op
                 listUser·p0.999:  17.417 ms/op
                 listUser·p0.9999: 21.250 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 4.925 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  17.792 ms/op
                 listUser·p0.9999: 20.332 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.984 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.296 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 25.925 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194317
  mean =      4.943 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 213 
    [ 2.500,  5.000) = 133059 
    [ 5.000,  7.500) = 53829 
    [ 7.500, 10.000) = 6091 
    [10.000, 12.500) = 673 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     25.095 ms/op
     p(99.9990) =     26.857 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.398 ± 0.847  ops/ms
ClientGrpc.existUser                       thrpt       3   8.866 ± 3.726  ops/ms
ClientGrpc.getUser                         thrpt       3   8.508 ± 1.273  ops/ms
ClientGrpc.listUser                        thrpt       3   6.485 ± 1.149  ops/ms
ClientGrpc.createUser                       avgt       3   3.782 ± 1.445   ms/op
ClientGrpc.existUser                        avgt       3   3.631 ± 0.469   ms/op
ClientGrpc.getUser                          avgt       3   3.810 ± 1.403   ms/op
ClientGrpc.listUser                         avgt       3   4.962 ± 1.220   ms/op
ClientGrpc.createUser                     sample  256904   3.735 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.210           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.310           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.918           ms/op
ClientGrpc.existUser                      sample  264494   3.628 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.898           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.087           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.912           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.241           ms/op
ClientGrpc.getUser                        sample  253197   3.793 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.755           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.562           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.596           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.048           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  194317   4.943 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.366           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.285           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.095           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
