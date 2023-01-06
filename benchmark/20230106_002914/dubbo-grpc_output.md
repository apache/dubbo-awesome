# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ops/ms
# Warmup Iteration   2: 9.567 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.210 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 10.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.216 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (10.181, 10.216, 10.258), stdev = 0.039
  CI (99.9%): [9.506, 10.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.742 ops/ms
# Warmup Iteration   2: 10.643 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.703 ±(99.9%) 3.037 ops/ms [Average]
  (min, avg, max) = (10.546, 10.703, 10.877), stdev = 0.166
  CI (99.9%): [7.666, 13.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.377 ops/ms
# Warmup Iteration   2: 10.175 ops/ms
# Warmup Iteration   3: 10.133 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.231 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.351 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (10.231, 10.351, 10.497), stdev = 0.135
  CI (99.9%): [7.888, 12.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.821 ops/ms
# Warmup Iteration   2: 7.566 ops/ms
# Warmup Iteration   3: 7.887 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.070 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (8.010, 8.070, 8.110), stdev = 0.053
  CI (99.9%): [7.101, 9.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.168 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.152 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.113, 3.152, 3.176), stdev = 0.035
  CI (99.9%): [2.523, 3.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.002 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.001 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.004 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (2.937, 3.004, 3.042), stdev = 0.058
  CI (99.9%): [1.951, 4.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 3.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (2.997, 3.029, 3.059), stdev = 0.031
  CI (99.9%): [2.463, 3.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.006 ms/op
Iteration   1: 4.007 ±(99.9%) 0.020 ms/op
Iteration   2: 4.011 ±(99.9%) 0.045 ms/op
Iteration   3: 4.011 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.010 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (4.007, 4.010, 4.011), stdev = 0.002
  CI (99.9%): [3.969, 4.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.434 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.784 ms/op
                 createUser·p0.9999: 14.905 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.839 ms/op
                 createUser·p0.9999: 17.477 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.023 ms/op
                 createUser·p0.9999: 26.498 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307387
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27487 
    [ 2.500,  5.000) = 278876 
    [ 5.000,  7.500) = 673 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     24.986 ms/op
     p(99.9990) =     26.832 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 13.146 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.571 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.726 ms/op
                 existUser·p0.9999: 14.486 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 24.447 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321176
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44173 
    [ 2.500,  5.000) = 276100 
    [ 5.000,  7.500) = 570 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.624 ms/op
     p(99.9900) =     22.374 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.269 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  10.437 ms/op
                 getUser·p0.9999: 13.134 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  5.669 ms/op
                 getUser·p0.9999: 16.128 ms/op
                 getUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315892
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1986 
    [ 1.250,  2.500) = 20225 
    [ 2.500,  3.750) = 275747 
    [ 3.750,  5.000) = 17037 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.529 ms/op
     p(99.9900) =     14.805 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.011 ms/op
Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.515 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.164 ms/op
                 listUser·p0.9999: 17.888 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 16.333 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 4.086 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.393 ms/op
                 listUser·p0.9999: 37.162 ms/op
                 listUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239988
  mean =      3.997 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5920 
    [ 2.500,  5.000) = 200664 
    [ 5.000,  7.500) = 32256 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     37.880 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.216 ± 0.711  ops/ms
ClientGrpc.existUser                       thrpt       3  10.703 ± 3.037  ops/ms
ClientGrpc.getUser                         thrpt       3  10.351 ± 2.463  ops/ms
ClientGrpc.listUser                        thrpt       3   8.070 ± 0.970  ops/ms
ClientGrpc.createUser                       avgt       3   3.152 ± 0.630   ms/op
ClientGrpc.existUser                        avgt       3   3.004 ± 1.053   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.566   ms/op
ClientGrpc.listUser                         avgt       3   4.010 ± 0.041   ms/op
ClientGrpc.createUser                     sample  307387   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.573           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.986           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  321176   2.989 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.748           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.624           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.374           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.411           ms/op
ClientGrpc.getUser                        sample  315892   3.037 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.269           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.529           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.805           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.400           ms/op
ClientGrpc.listUser                       sample  239988   3.997 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.515           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.324           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.880           ms/op
