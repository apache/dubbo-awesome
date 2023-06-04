# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 8.040 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.475 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (8.341, 8.475, 8.600), stdev = 0.130
  CI (99.9%): [6.101, 10.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.781 ops/ms
# Warmup Iteration   2: 8.189 ops/ms
# Warmup Iteration   3: 8.886 ops/ms
Iteration   1: 8.913 ops/ms
Iteration   2: 8.859 ops/ms
Iteration   3: 8.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.919 ±(99.9%) 1.148 ops/ms [Average]
  (min, avg, max) = (8.859, 8.919, 8.984), stdev = 0.063
  CI (99.9%): [7.770, 10.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.535 ops/ms
Iteration   1: 8.550 ops/ms
Iteration   2: 8.556 ops/ms
Iteration   3: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.600 ±(99.9%) 1.484 ops/ms [Average]
  (min, avg, max) = (8.550, 8.600, 8.694), stdev = 0.081
  CI (99.9%): [7.116, 10.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ops/ms
# Warmup Iteration   2: 6.146 ops/ms
# Warmup Iteration   3: 6.626 ops/ms
Iteration   1: 6.585 ops/ms
Iteration   2: 6.610 ops/ms
Iteration   3: 6.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.586 ±(99.9%) 0.429 ops/ms [Average]
  (min, avg, max) = (6.563, 6.586, 6.610), stdev = 0.024
  CI (99.9%): [6.157, 7.015] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.008 ms/op
Iteration   1: 3.786 ±(99.9%) 0.004 ms/op
Iteration   2: 3.781 ±(99.9%) 0.004 ms/op
Iteration   3: 3.662 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.743 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.662, 3.743, 3.786), stdev = 0.070
  CI (99.9%): [2.465, 5.021] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.006 ms/op
Iteration   1: 3.557 ±(99.9%) 0.003 ms/op
Iteration   2: 3.592 ±(99.9%) 0.005 ms/op
Iteration   3: 3.637 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.595 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.557, 3.595, 3.637), stdev = 0.040
  CI (99.9%): [2.866, 4.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.005 ms/op
Iteration   1: 3.845 ±(99.9%) 0.003 ms/op
Iteration   2: 3.733 ±(99.9%) 0.004 ms/op
Iteration   3: 3.750 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.776 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (3.733, 3.776, 3.845), stdev = 0.060
  CI (99.9%): [2.677, 4.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.490 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.015 ms/op
Iteration   1: 4.806 ±(99.9%) 0.013 ms/op
Iteration   2: 4.818 ±(99.9%) 0.015 ms/op
Iteration   3: 4.808 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.811 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (4.806, 4.811, 4.818), stdev = 0.007
  CI (99.9%): [4.692, 4.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.963 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.009 ms/op
Iteration   1: 3.791 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  12.461 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 3.856 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  10.126 ms/op
                 createUser·p0.9999: 25.441 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.766 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.624 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  12.760 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252510
  mean =      3.804 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3939 
    [ 2.500,  5.000) = 241366 
    [ 5.000,  7.500) = 6272 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     12.312 ms/op
     p(99.9900) =     24.863 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.313 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.009 ms/op
Iteration   1: 3.525 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.738 ms/op
                 existUser·p0.999:  8.835 ms/op
                 existUser·p0.9999: 14.809 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   2: 3.647 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 15.962 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   3: 3.595 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  8.767 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267535
  mean =      3.588 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13873 
    [ 2.500,  5.000) = 246515 
    [ 5.000,  7.500) = 6398 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     18.694 ms/op
     p(99.9990) =     20.020 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.419 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
Iteration   1: 3.759 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  10.583 ms/op
                 getUser·p0.9999: 15.654 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   3: 3.820 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.385 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 21.221 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253463
  mean =      3.787 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7719 
    [ 2.500,  5.000) = 235744 
    [ 5.000,  7.500) = 8844 
    [ 7.500, 10.000) = 840 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     19.813 ms/op
     p(99.9990) =     21.395 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.078 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.983 ±(99.9%) 0.017 ms/op
Iteration   1: 4.980 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  16.570 ms/op
                 listUser·p0.9999: 18.860 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.950 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.495 ms/op
                 listUser·p0.9999: 20.250 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 5.014 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 23.613 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192710
  mean =      4.981 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 125265 
    [ 5.000,  7.500) = 60642 
    [ 7.500, 10.000) = 5707 
    [10.000, 12.500) = 474 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     16.885 ms/op
     p(99.9900) =     22.985 ms/op
     p(99.9990) =     23.992 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.475 ± 2.374  ops/ms
ClientGrpc.existUser                       thrpt       3   8.919 ± 1.148  ops/ms
ClientGrpc.getUser                         thrpt       3   8.600 ± 1.484  ops/ms
ClientGrpc.listUser                        thrpt       3   6.586 ± 0.429  ops/ms
ClientGrpc.createUser                       avgt       3   3.743 ± 1.278   ms/op
ClientGrpc.existUser                        avgt       3   3.595 ± 0.729   ms/op
ClientGrpc.getUser                          avgt       3   3.776 ± 1.098   ms/op
ClientGrpc.listUser                         avgt       3   4.811 ± 0.119   ms/op
ClientGrpc.createUser                     sample  252510   3.804 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.841           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.312           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.863           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.821           ms/op
ClientGrpc.existUser                      sample  267535   3.588 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.913           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.694           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  253463   3.787 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.385           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.764           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.813           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  192710   4.981 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.885           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.985           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
