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
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 7.293 ops/ms
# Warmup Iteration   3: 8.723 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.533 ops/ms
Iteration   3: 8.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.523 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (8.397, 8.523, 8.638), stdev = 0.121
  CI (99.9%): [6.317, 10.729] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.116 ops/ms
# Warmup Iteration   2: 8.776 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 9.052 ops/ms
Iteration   2: 9.155 ops/ms
Iteration   3: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.378 ±(99.9%) 8.739 ops/ms [Average]
  (min, avg, max) = (9.052, 9.378, 9.928), stdev = 0.479
  CI (99.9%): [0.639, 18.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.005 ops/ms
# Warmup Iteration   2: 8.403 ops/ms
# Warmup Iteration   3: 8.737 ops/ms
Iteration   1: 8.653 ops/ms
Iteration   2: 8.899 ops/ms
Iteration   3: 8.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.731 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (8.642, 8.731, 8.899), stdev = 0.146
  CI (99.9%): [6.075, 11.387] (assumes normal distribution)


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
# Warmup Iteration   1: 4.392 ops/ms
# Warmup Iteration   2: 6.093 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.746 ops/ms
Iteration   2: 6.794 ops/ms
Iteration   3: 6.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.785 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (6.746, 6.785, 6.814), stdev = 0.035
  CI (99.9%): [6.147, 7.422] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.436 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.010 ms/op
Iteration   1: 3.652 ±(99.9%) 0.004 ms/op
Iteration   2: 3.533 ±(99.9%) 0.004 ms/op
Iteration   3: 3.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.579 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.533, 3.579, 3.652), stdev = 0.064
  CI (99.9%): [2.419, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.006 ms/op
Iteration   1: 3.632 ±(99.9%) 0.004 ms/op
Iteration   2: 3.644 ±(99.9%) 0.003 ms/op
Iteration   3: 3.560 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.612 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.560, 3.612, 3.644), stdev = 0.045
  CI (99.9%): [2.784, 4.440] (assumes normal distribution)


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
# Warmup Iteration   1: 5.633 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.005 ms/op
Iteration   1: 3.782 ±(99.9%) 0.003 ms/op
Iteration   2: 3.729 ±(99.9%) 0.002 ms/op
Iteration   3: 3.730 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.747 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.729, 3.747, 3.782), stdev = 0.030
  CI (99.9%): [3.201, 4.293] (assumes normal distribution)


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
# Warmup Iteration   1: 6.558 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.110 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.014 ms/op
Iteration   1: 4.632 ±(99.9%) 0.007 ms/op
Iteration   2: 4.376 ±(99.9%) 0.007 ms/op
Iteration   3: 4.600 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.536 ±(99.9%) 2.543 ms/op [Average]
  (min, avg, max) = (4.376, 4.536, 4.632), stdev = 0.139
  CI (99.9%): [1.993, 7.079] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  13.184 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 27.327 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.661 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  12.698 ms/op
                 createUser·p0.9999: 29.819 ms/op
                 createUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259899
  mean =      3.694 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4825 
    [ 2.500,  5.000) = 249858 
    [ 5.000,  7.500) = 4450 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     30.160 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.007 ms/op
Iteration   1: 3.576 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  7.446 ms/op
                 existUser·p0.9999: 14.044 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 3.585 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.122 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 15.458 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 3.522 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  17.957 ms/op
                 existUser·p0.9999: 24.410 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269595
  mean =      3.561 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16596 
    [ 2.500,  5.000) = 248872 
    [ 5.000,  7.500) = 3475 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     12.901 ms/op
     p(99.9900) =     22.972 ms/op
     p(99.9990) =     24.848 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 5.676 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.008 ms/op
Iteration   1: 3.621 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  11.120 ms/op
                 getUser·p0.9999: 14.978 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 3.879 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  9.211 ms/op
                 getUser·p0.9999: 17.704 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 23.177 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256374
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6903 
    [ 2.500,  5.000) = 242864 
    [ 5.000,  7.500) = 5954 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     22.208 ms/op
     p(99.9990) =     23.472 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.046 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.014 ms/op
Iteration   1: 4.807 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 17.883 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 4.789 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.009 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.746 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  21.189 ms/op
                 listUser·p0.9999: 23.774 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200800
  mean =      4.780 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 349 
    [ 2.500,  5.000) = 148605 
    [ 5.000,  7.500) = 47098 
    [ 7.500, 10.000) = 3949 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     16.502 ms/op
     p(99.9900) =     23.066 ms/op
     p(99.9990) =     24.346 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.523 ± 2.206  ops/ms
ClientGrpc.existUser                       thrpt       3   9.378 ± 8.739  ops/ms
ClientGrpc.getUser                         thrpt       3   8.731 ± 2.656  ops/ms
ClientGrpc.listUser                        thrpt       3   6.785 ± 0.637  ops/ms
ClientGrpc.createUser                       avgt       3   3.579 ± 1.160   ms/op
ClientGrpc.existUser                        avgt       3   3.612 ± 0.828   ms/op
ClientGrpc.getUser                          avgt       3   3.747 ± 0.546   ms/op
ClientGrpc.listUser                         avgt       3   4.536 ± 2.543   ms/op
ClientGrpc.createUser                     sample  259899   3.694 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.886           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.541           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.245           ms/op
ClientGrpc.existUser                      sample  269595   3.561 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.837           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.901           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.972           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  256374   3.741 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.899           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.994           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.208           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  200800   4.780 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.278           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.502           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.066           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
