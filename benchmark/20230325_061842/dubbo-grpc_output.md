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
# Warmup Iteration   1: 4.460 ops/ms
# Warmup Iteration   2: 9.687 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.782 ops/ms
Iteration   2: 10.798 ops/ms
Iteration   3: 10.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.830 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (10.782, 10.830, 10.910), stdev = 0.070
  CI (99.9%): [9.562, 12.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.207 ops/ms
# Warmup Iteration   2: 11.025 ops/ms
# Warmup Iteration   3: 11.227 ops/ms
Iteration   1: 11.342 ops/ms
Iteration   2: 11.348 ops/ms
Iteration   3: 11.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.360 ±(99.9%) 0.474 ops/ms [Average]
  (min, avg, max) = (11.342, 11.360, 11.389), stdev = 0.026
  CI (99.9%): [10.886, 11.833] (assumes normal distribution)


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
# Warmup Iteration   1: 7.549 ops/ms
# Warmup Iteration   2: 10.573 ops/ms
# Warmup Iteration   3: 10.854 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.788 ±(99.9%) 1.029 ops/ms [Average]
  (min, avg, max) = (10.742, 10.788, 10.851), stdev = 0.056
  CI (99.9%): [9.759, 11.817] (assumes normal distribution)


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
# Warmup Iteration   1: 6.359 ops/ms
# Warmup Iteration   2: 8.296 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.413 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.425 ±(99.9%) 0.260 ops/ms [Average]
  (min, avg, max) = (8.413, 8.425, 8.441), stdev = 0.014
  CI (99.9%): [8.165, 8.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.002 ms/op
Iteration   2: 2.930 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (2.930, 2.973, 3.001), stdev = 0.037
  CI (99.9%): [2.290, 3.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.835 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.783 ±(99.9%) 0.004 ms/op
Iteration   1: 2.817 ±(99.9%) 0.003 ms/op
Iteration   2: 2.810 ±(99.9%) 0.004 ms/op
Iteration   3: 2.764 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.797 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.764, 2.797, 2.817), stdev = 0.029
  CI (99.9%): [2.277, 3.317] (assumes normal distribution)


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.898 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.935 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (2.898, 2.935, 2.975), stdev = 0.039
  CI (99.9%): [2.229, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.023 ms/op
Iteration   1: 3.705 ±(99.9%) 0.041 ms/op
Iteration   2: 3.856 ±(99.9%) 0.018 ms/op
Iteration   3: 3.773 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.778 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (3.705, 3.778, 3.856), stdev = 0.076
  CI (99.9%): [2.397, 5.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.221 ms/op
                 createUser·p0.9999: 18.385 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.124 ms/op
                 createUser·p0.9999: 18.153 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.440 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323717
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2492 
    [ 1.250,  2.500) = 30104 
    [ 2.500,  3.750) = 279018 
    [ 3.750,  5.000) = 10829 
    [ 5.000,  6.250) = 825 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 99 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.689 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     19.468 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.880 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.006 ms/op
Iteration   1: 2.796 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.680 ms/op
                 existUser·p0.9999: 13.453 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.157 ms/op
                 existUser·p0.9999: 14.672 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.613 ms/op
                 existUser·p0.9999: 24.958 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340353
  mean =      2.821 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50989 
    [ 2.500,  5.000) = 288232 
    [ 5.000,  7.500) = 881 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     16.070 ms/op
     p(99.9990) =     25.153 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.627 ms/op
                 getUser·p0.9999: 14.586 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 21.111 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 16.092 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323455
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32763 
    [ 2.500,  5.000) = 289566 
    [ 5.000,  7.500) = 927 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.320 ms/op
     p(99.9900) =     18.826 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 5.077 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.009 ms/op
Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.196 ms/op
                 listUser·p0.9999: 18.079 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.891 ms/op
                 listUser·p0.9999: 16.695 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.538 ms/op
                 listUser·p0.999:  14.050 ms/op
                 listUser·p0.9999: 19.248 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252269
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6243 
    [ 2.500,  5.000) = 225080 
    [ 5.000,  7.500) = 19864 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.081 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.118 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.830 ± 1.268  ops/ms
ClientGrpc.existUser                       thrpt       3  11.360 ± 0.474  ops/ms
ClientGrpc.getUser                         thrpt       3  10.788 ± 1.029  ops/ms
ClientGrpc.listUser                        thrpt       3   8.425 ± 0.260  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.683   ms/op
ClientGrpc.existUser                        avgt       3   2.797 ± 0.520   ms/op
ClientGrpc.getUser                          avgt       3   2.935 ± 0.706   ms/op
ClientGrpc.listUser                         avgt       3   3.778 ± 1.380   ms/op
ClientGrpc.createUser                     sample  323717   2.966 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.689           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.759           ms/op
ClientGrpc.existUser                      sample  340353   2.821 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.486           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.070           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.231           ms/op
ClientGrpc.getUser                        sample  323455   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.532           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.320           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.826           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  252269   3.805 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.668           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.081           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.218           ms/op
