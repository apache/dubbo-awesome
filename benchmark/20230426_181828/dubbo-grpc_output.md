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
# Warmup Iteration   1: 4.622 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 10.333 ops/ms
Iteration   1: 10.462 ops/ms
Iteration   2: 10.931 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.691 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (10.462, 10.691, 10.931), stdev = 0.235
  CI (99.9%): [6.408, 14.974] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.820 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 11.083 ops/ms
Iteration   1: 11.441 ops/ms
Iteration   2: 11.063 ops/ms
Iteration   3: 11.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.256 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (11.063, 11.256, 11.441), stdev = 0.189
  CI (99.9%): [7.799, 14.713] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ops/ms
# Warmup Iteration   2: 10.181 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.770 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.658 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (10.524, 10.658, 10.770), stdev = 0.124
  CI (99.9%): [8.387, 12.929] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.427 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 8.050 ops/ms
Iteration   1: 8.100 ops/ms
Iteration   2: 8.145 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.135 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (8.100, 8.135, 8.161), stdev = 0.032
  CI (99.9%): [7.553, 8.718] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.004 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (2.972, 2.997, 3.031), stdev = 0.031
  CI (99.9%): [2.435, 3.558] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.003 ms/op
Iteration   1: 2.894 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.765 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.850 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (2.765, 2.850, 2.894), stdev = 0.074
  CI (99.9%): [1.500, 4.200] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (2.986, 3.033, 3.066), stdev = 0.042
  CI (99.9%): [2.265, 3.802] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.007 ms/op
Iteration   1: 3.853 ±(99.9%) 0.017 ms/op
Iteration   2: 3.906 ±(99.9%) 0.023 ms/op
Iteration   3: 3.896 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.853, 3.885, 3.906), stdev = 0.028
  CI (99.9%): [3.371, 4.399] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.116 ms/op
                 createUser·p0.9999: 12.666 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 18.214 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.838 ms/op
                 createUser·p0.9999: 17.476 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317220
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 584 
    [ 1.250,  2.500) = 19643 
    [ 2.500,  3.750) = 283210 
    [ 3.750,  5.000) = 12357 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.069 ms/op
     p(99.9900) =     17.606 ms/op
     p(99.9990) =     19.355 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.599 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
Iteration   1: 2.873 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  5.990 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 18.085 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 18.944 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331780
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1504 
    [ 1.250,  2.500) = 33889 
    [ 2.500,  3.750) = 289759 
    [ 3.750,  5.000) = 5685 
    [ 5.000,  6.250) = 519 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.137 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     19.619 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.900 ms/op
                 getUser·p0.9999: 12.731 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.354 ms/op
                 getUser·p0.9999: 14.394 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.505 ms/op
                 getUser·p0.9999: 17.693 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314522
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 15445 
    [ 2.500,  3.750) = 283145 
    [ 3.750,  5.000) = 14543 
    [ 5.000,  6.250) = 737 
    [ 6.250,  7.500) = 214 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.188 ms/op
     p(99.9900) =     16.879 ms/op
     p(99.9990) =     17.919 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.011 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 15.570 ms/op
                 listUser·p1.00:   16.237 ms/op

Iteration   2: 3.999 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 27.918 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.590 ms/op
                 listUser·p0.9999: 25.784 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240216
  mean =      3.994 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4862 
    [ 2.500,  5.000) = 209384 
    [ 5.000,  7.500) = 24573 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     28.220 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.691 ± 4.283  ops/ms
ClientGrpc.existUser                       thrpt       3  11.256 ± 3.457  ops/ms
ClientGrpc.getUser                         thrpt       3  10.658 ± 2.271  ops/ms
ClientGrpc.listUser                        thrpt       3   8.135 ± 0.582  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.562   ms/op
ClientGrpc.existUser                        avgt       3   2.850 ± 1.350   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.769   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 0.514   ms/op
ClientGrpc.createUser                     sample  317220   3.028 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.069           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.606           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  331780   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.630           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.137           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  314522   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.188           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.879           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.990           ms/op
ClientGrpc.listUser                       sample  240216   3.994 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.344           ms/op
