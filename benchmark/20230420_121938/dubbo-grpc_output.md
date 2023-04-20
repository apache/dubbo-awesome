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
# Warmup Iteration   1: 4.681 ops/ms
# Warmup Iteration   2: 9.575 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.853 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (10.764, 10.853, 10.954), stdev = 0.096
  CI (99.9%): [9.106, 12.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.487 ops/ms
# Warmup Iteration   2: 10.887 ops/ms
# Warmup Iteration   3: 11.312 ops/ms
Iteration   1: 11.357 ops/ms
Iteration   2: 11.663 ops/ms
Iteration   3: 11.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.469 ±(99.9%) 3.075 ops/ms [Average]
  (min, avg, max) = (11.357, 11.469, 11.663), stdev = 0.169
  CI (99.9%): [8.393, 14.544] (assumes normal distribution)


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
# Warmup Iteration   1: 7.587 ops/ms
# Warmup Iteration   2: 10.590 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.834 ops/ms
Iteration   2: 10.750 ops/ms
Iteration   3: 10.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.851 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (10.750, 10.851, 10.969), stdev = 0.111
  CI (99.9%): [8.831, 12.871] (assumes normal distribution)


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
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 7.987 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 8.301 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.397 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (8.301, 8.397, 8.564), stdev = 0.145
  CI (99.9%): [5.748, 11.046] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.010 ms/op
Iteration   1: 2.987 ±(99.9%) 0.003 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.962 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (2.928, 2.962, 2.987), stdev = 0.030
  CI (99.9%): [2.409, 3.514] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.901 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.811 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.004 ms/op
Iteration   2: 2.866 ±(99.9%) 0.002 ms/op
Iteration   3: 2.779 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.825 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (2.779, 2.825, 2.866), stdev = 0.044
  CI (99.9%): [2.027, 3.624] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.004 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.962, 2.978, 2.991), stdev = 0.015
  CI (99.9%): [2.707, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 5.353 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.026 ms/op
Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
Iteration   2: 3.881 ±(99.9%) 0.024 ms/op
Iteration   3: 3.881 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.787, 3.850, 3.881), stdev = 0.054
  CI (99.9%): [2.863, 4.836] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
Iteration   1: 2.936 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.905 ms/op
                 createUser·p0.9999: 12.994 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  12.671 ms/op
                 createUser·p0.9999: 21.798 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.675 ms/op
                 createUser·p0.9999: 14.450 ms/op
                 createUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323914
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31767 
    [ 2.500,  5.000) = 290817 
    [ 5.000,  7.500) = 1010 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     21.120 ms/op
     p(99.9990) =     21.947 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.892 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.812 ±(99.9%) 0.006 ms/op
Iteration   1: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.203 ms/op
                 existUser·p0.9999: 16.441 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   2: 2.762 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.352 ms/op
                 existUser·p0.9999: 13.559 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.796 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.155 ms/op
                 existUser·p0.9999: 18.518 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341272
  mean =      2.810 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4994 
    [ 1.250,  2.500) = 54764 
    [ 2.500,  3.750) = 270882 
    [ 3.750,  5.000) = 9491 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     16.689 ms/op
     p(99.9990) =     19.746 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.350 ms/op
                 getUser·p0.9999: 13.361 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.911 ms/op
                 getUser·p0.9999: 12.865 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  5.972 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323543
  mean =      2.963 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2232 
    [ 1.250,  2.500) = 27719 
    [ 2.500,  3.750) = 280257 
    [ 3.750,  5.000) = 12303 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 110 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.426 ms/op
     p(99.9900) =     15.023 ms/op
     p(99.9990) =     15.602 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.651 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.329 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.787 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   6.451 ms/op
                 listUser·p0.999:  14.817 ms/op
                 listUser·p0.9999: 22.960 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.847 ms/op
                 listUser·p0.9999: 20.372 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250559
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4049 
    [ 2.500,  5.000) = 230362 
    [ 5.000,  7.500) = 14910 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.622 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     22.379 ms/op
     p(99.9990) =     23.118 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.853 ± 1.746  ops/ms
ClientGrpc.existUser                       thrpt       3  11.469 ± 3.075  ops/ms
ClientGrpc.getUser                         thrpt       3  10.851 ± 2.020  ops/ms
ClientGrpc.listUser                        thrpt       3   8.397 ± 2.649  ops/ms
ClientGrpc.createUser                       avgt       3   2.962 ± 0.553   ms/op
ClientGrpc.existUser                        avgt       3   2.825 ± 0.798   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.271   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.987   ms/op
ClientGrpc.createUser                     sample  323914   2.964 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.463           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.120           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.987           ms/op
ClientGrpc.existUser                      sample  341272   2.810 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.651           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.689           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  323543   2.963 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.426           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.023           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.679           ms/op
ClientGrpc.listUser                       sample  250559   3.837 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.994           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.622           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.379           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
