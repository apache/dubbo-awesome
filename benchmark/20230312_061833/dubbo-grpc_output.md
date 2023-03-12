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
# Warmup Iteration   1: 2.771 ops/ms
# Warmup Iteration   2: 5.926 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.377 ±(99.9%) 2.993 ops/ms [Average]
  (min, avg, max) = (8.188, 8.377, 8.478), stdev = 0.164
  CI (99.9%): [5.384, 11.371] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.444 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 8.614 ops/ms
Iteration   1: 8.981 ops/ms
Iteration   2: 9.037 ops/ms
Iteration   3: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.051 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (8.981, 9.051, 9.136), stdev = 0.079
  CI (99.9%): [7.618, 10.485] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ops/ms
# Warmup Iteration   2: 8.014 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.734 ops/ms
Iteration   3: 8.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.495 ±(99.9%) 4.078 ops/ms [Average]
  (min, avg, max) = (8.291, 8.495, 8.734), stdev = 0.224
  CI (99.9%): [4.417, 12.573] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 5.756 ops/ms
# Warmup Iteration   3: 6.527 ops/ms
Iteration   1: 6.365 ops/ms
Iteration   2: 6.645 ops/ms
Iteration   3: 6.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.569 ±(99.9%) 3.248 ops/ms [Average]
  (min, avg, max) = (6.365, 6.569, 6.696), stdev = 0.178
  CI (99.9%): [3.321, 9.816] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.786 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.008 ms/op
Iteration   1: 3.857 ±(99.9%) 0.003 ms/op
Iteration   2: 3.795 ±(99.9%) 0.003 ms/op
Iteration   3: 4.221 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.958 ±(99.9%) 4.199 ms/op [Average]
  (min, avg, max) = (3.795, 3.958, 4.221), stdev = 0.230
  CI (99.9%): [≈ 0, 8.157] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.003 ms/op
Iteration   1: 3.631 ±(99.9%) 0.004 ms/op
Iteration   2: 3.654 ±(99.9%) 0.003 ms/op
Iteration   3: 3.630 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.638 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (3.630, 3.638, 3.654), stdev = 0.013
  CI (99.9%): [3.395, 3.882] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.264 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.003 ms/op
Iteration   1: 3.885 ±(99.9%) 0.004 ms/op
Iteration   2: 3.739 ±(99.9%) 0.005 ms/op
Iteration   3: 3.823 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.816 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.739, 3.816, 3.885), stdev = 0.073
  CI (99.9%): [2.486, 5.145] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.344 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.017 ms/op
Iteration   1: 4.770 ±(99.9%) 0.025 ms/op
Iteration   2: 4.742 ±(99.9%) 0.013 ms/op
Iteration   3: 4.681 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.731 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (4.681, 4.731, 4.770), stdev = 0.045
  CI (99.9%): [3.908, 5.554] (assumes normal distribution)


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
# Warmup Iteration   1: 5.827 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  12.351 ms/op
                 createUser·p0.9999: 14.603 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.812 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  10.891 ms/op
                 createUser·p0.9999: 15.421 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 3.673 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  16.170 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256938
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7637 
    [ 2.500,  5.000) = 241003 
    [ 5.000,  7.500) = 7203 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     12.043 ms/op
     p(99.9900) =     34.164 ms/op
     p(99.9990) =     35.549 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.804 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.008 ms/op
Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  10.529 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.594 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 17.043 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  12.862 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266558
  mean =      3.599 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 6551 
    [ 2.500,  3.750) = 177877 
    [ 3.750,  5.000) = 76227 
    [ 5.000,  6.250) = 3842 
    [ 6.250,  7.500) = 814 
    [ 7.500,  8.750) = 577 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     10.196 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     18.634 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.756 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
Iteration   1: 3.783 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.589 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  11.317 ms/op
                 getUser·p0.9999: 14.804 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 3.692 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  8.722 ms/op
                 getUser·p0.9999: 16.504 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 3.748 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 20.461 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256592
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7013 
    [ 2.500,  5.000) = 239643 
    [ 5.000,  7.500) = 8937 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     10.755 ms/op
     p(99.9900) =     18.798 ms/op
     p(99.9990) =     21.390 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 6.902 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.039 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.841 ±(99.9%) 0.016 ms/op
Iteration   1: 4.694 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  15.792 ms/op
                 listUser·p0.9999: 17.930 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   2: 4.751 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 20.474 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 4.767 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  23.757 ms/op
                 listUser·p0.9999: 27.689 ms/op
                 listUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202599
  mean =      4.737 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 153705 
    [ 5.000,  7.500) = 41849 
    [ 7.500, 10.000) = 6000 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.839 ms/op
     p(99.9900) =     27.114 ms/op
     p(99.9990) =     28.306 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.377 ± 2.993  ops/ms
ClientGrpc.existUser                       thrpt       3   9.051 ± 1.434  ops/ms
ClientGrpc.getUser                         thrpt       3   8.495 ± 4.078  ops/ms
ClientGrpc.listUser                        thrpt       3   6.569 ± 3.248  ops/ms
ClientGrpc.createUser                       avgt       3   3.958 ± 4.199   ms/op
ClientGrpc.existUser                        avgt       3   3.638 ± 0.243   ms/op
ClientGrpc.getUser                          avgt       3   3.816 ± 1.330   ms/op
ClientGrpc.listUser                         avgt       3   4.731 ± 0.823   ms/op
ClientGrpc.createUser                     sample  256938   3.739 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.972           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.043           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.164           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.652           ms/op
ClientGrpc.existUser                      sample  266558   3.599 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.967           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.196           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.138           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  256592   3.741 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.755           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.798           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  202599   4.737 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.272           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.839           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.114           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.475           ms/op
