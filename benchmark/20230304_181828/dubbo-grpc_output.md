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
# Warmup Iteration   1: 3.292 ops/ms
# Warmup Iteration   2: 7.386 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 8.816 ops/ms
Iteration   2: 8.883 ops/ms
Iteration   3: 8.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.777 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (8.633, 8.777, 8.883), stdev = 0.130
  CI (99.9%): [6.414, 11.141] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.195 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 8.786 ops/ms
Iteration   1: 9.068 ops/ms
Iteration   2: 9.000 ops/ms
Iteration   3: 8.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.019 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (8.989, 9.019, 9.068), stdev = 0.043
  CI (99.9%): [8.240, 9.797] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.691 ops/ms
# Warmup Iteration   2: 8.081 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.587 ops/ms
Iteration   2: 8.484 ops/ms
Iteration   3: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.539 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (8.484, 8.539, 8.587), stdev = 0.052
  CI (99.9%): [7.591, 9.486] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ops/ms
# Warmup Iteration   2: 6.272 ops/ms
# Warmup Iteration   3: 6.885 ops/ms
Iteration   1: 6.932 ops/ms
Iteration   2: 6.617 ops/ms
Iteration   3: 6.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.804 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (6.617, 6.804, 6.932), stdev = 0.166
  CI (99.9%): [3.780, 9.829] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.317 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.002 ms/op
Iteration   1: 3.839 ±(99.9%) 0.004 ms/op
Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
Iteration   3: 3.883 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.786 ±(99.9%) 2.408 ms/op [Average]
  (min, avg, max) = (3.635, 3.786, 3.883), stdev = 0.132
  CI (99.9%): [1.377, 6.194] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.005 ms/op
Iteration   1: 3.570 ±(99.9%) 0.003 ms/op
Iteration   2: 3.452 ±(99.9%) 0.004 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.538 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (3.452, 3.538, 3.591), stdev = 0.075
  CI (99.9%): [2.173, 4.902] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.004 ms/op
Iteration   1: 3.710 ±(99.9%) 0.003 ms/op
Iteration   2: 3.785 ±(99.9%) 0.004 ms/op
Iteration   3: 3.818 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.771 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.710, 3.771, 3.818), stdev = 0.055
  CI (99.9%): [2.762, 4.780] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.991 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.014 ms/op
Iteration   1: 4.674 ±(99.9%) 0.009 ms/op
Iteration   2: 4.740 ±(99.9%) 0.024 ms/op
Iteration   3: 4.618 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.677 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (4.618, 4.677, 4.740), stdev = 0.061
  CI (99.9%): [3.570, 5.785] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.322 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.009 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  12.133 ms/op
                 createUser·p0.9999: 14.488 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   2: 3.684 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 22.467 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  8.224 ms/op
                 createUser·p0.9999: 19.674 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258598
  mean =      3.710 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8219 
    [ 2.500,  5.000) = 244771 
    [ 5.000,  7.500) = 5144 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      9.313 ms/op
     p(99.9900) =     21.702 ms/op
     p(99.9990) =     22.801 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  7.708 ms/op
                 existUser·p0.9999: 14.662 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.444 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.835 ms/op
                 existUser·p0.9999: 14.790 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 3.666 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.827 ms/op
                 existUser·p0.9999: 19.440 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271173
  mean =      3.538 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 393 
    [ 1.250,  2.500) = 13501 
    [ 2.500,  3.750) = 161869 
    [ 3.750,  5.000) = 91974 
    [ 5.000,  6.250) = 2805 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     19.034 ms/op
     p(99.9990) =     19.755 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
Iteration   1: 3.671 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 16.829 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.643 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  7.966 ms/op
                 getUser·p0.9999: 16.522 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 3.691 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  8.051 ms/op
                 getUser·p0.9999: 18.296 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261585
  mean =      3.669 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 7292 
    [ 2.500,  3.750) = 142709 
    [ 3.750,  5.000) = 106429 
    [ 5.000,  6.250) = 4122 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =      8.384 ms/op
     p(99.9900) =     17.446 ms/op
     p(99.9990) =     18.683 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 6.009 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.163 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.015 ms/op
Iteration   1: 4.557 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  14.624 ms/op
                 listUser·p0.9999: 16.809 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 4.681 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  16.199 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   3: 4.756 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.424 ms/op
                 listUser·p0.999:  19.946 ms/op
                 listUser·p0.9999: 31.293 ms/op
                 listUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205811
  mean =      4.663 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 416 
    [ 2.500,  5.000) = 160772 
    [ 5.000,  7.500) = 40738 
    [ 7.500, 10.000) = 3331 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     16.256 ms/op
     p(99.9900) =     30.642 ms/op
     p(99.9990) =     31.695 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.777 ± 2.363  ops/ms
ClientGrpc.existUser                       thrpt       3   9.019 ± 0.779  ops/ms
ClientGrpc.getUser                         thrpt       3   8.539 ± 0.947  ops/ms
ClientGrpc.listUser                        thrpt       3   6.804 ± 3.025  ops/ms
ClientGrpc.createUser                       avgt       3   3.786 ± 2.408   ms/op
ClientGrpc.existUser                        avgt       3   3.538 ± 1.364   ms/op
ClientGrpc.getUser                          avgt       3   3.771 ± 1.009   ms/op
ClientGrpc.listUser                         avgt       3   4.677 ± 1.108   ms/op
ClientGrpc.createUser                     sample  258598   3.710 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.024           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.313           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.702           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  271173   3.538 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.151           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.034           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  261585   3.669 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.384           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.446           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.940           ms/op
ClientGrpc.listUser                       sample  205811   4.663 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.966           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.256           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.642           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.096           ms/op
