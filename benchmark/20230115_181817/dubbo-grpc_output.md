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
# Warmup Iteration   1: 3.471 ops/ms
# Warmup Iteration   2: 7.466 ops/ms
# Warmup Iteration   3: 8.314 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.720 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.455 ±(99.9%) 4.192 ops/ms [Average]
  (min, avg, max) = (8.314, 8.455, 8.720), stdev = 0.230
  CI (99.9%): [4.264, 12.647] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 8.663 ops/ms
# Warmup Iteration   3: 8.712 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.708 ops/ms
Iteration   3: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.812 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (8.707, 8.812, 9.019), stdev = 0.180
  CI (99.9%): [5.532, 12.091] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.551 ops/ms
# Warmup Iteration   2: 8.282 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 8.286 ops/ms
Iteration   2: 8.327 ops/ms
Iteration   3: 8.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.266 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (8.187, 8.266, 8.327), stdev = 0.072
  CI (99.9%): [6.955, 9.578] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ops/ms
# Warmup Iteration   2: 5.917 ops/ms
# Warmup Iteration   3: 6.537 ops/ms
Iteration   1: 6.757 ops/ms
Iteration   2: 6.620 ops/ms
Iteration   3: 6.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.686 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (6.620, 6.686, 6.757), stdev = 0.068
  CI (99.9%): [5.438, 7.933] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.007 ms/op
Iteration   1: 3.717 ±(99.9%) 0.003 ms/op
Iteration   2: 3.836 ±(99.9%) 0.003 ms/op
Iteration   3: 3.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.822 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.717, 3.822, 3.913), stdev = 0.099
  CI (99.9%): [2.017, 5.627] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.003 ms/op
Iteration   1: 3.672 ±(99.9%) 0.005 ms/op
Iteration   2: 3.630 ±(99.9%) 0.002 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.631 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.591, 3.631, 3.672), stdev = 0.041
  CI (99.9%): [2.891, 4.371] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.240 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.003 ms/op
Iteration   1: 3.632 ±(99.9%) 0.005 ms/op
Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
Iteration   3: 3.782 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.693 ±(99.9%) 1.433 ms/op [Average]
  (min, avg, max) = (3.632, 3.693, 3.782), stdev = 0.079
  CI (99.9%): [2.260, 5.126] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.406 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.155 ±(99.9%) 0.018 ms/op
Iteration   1: 5.110 ±(99.9%) 0.029 ms/op
Iteration   2: 4.991 ±(99.9%) 0.023 ms/op
Iteration   3: 4.943 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.015 ±(99.9%) 1.560 ms/op [Average]
  (min, avg, max) = (4.943, 5.015, 5.110), stdev = 0.085
  CI (99.9%): [3.455, 6.575] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.513 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  12.026 ms/op
                 createUser·p0.9999: 15.778 ms/op
                 createUser·p1.00:   16.089 ms/op

Iteration   2: 3.859 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.536 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 18.898 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.839 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.312 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248752
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 7303 
    [ 2.500,  3.750) = 110187 
    [ 3.750,  5.000) = 118699 
    [ 5.000,  6.250) = 9446 
    [ 6.250,  7.500) = 1622 
    [ 7.500,  8.750) = 692 
    [ 8.750, 10.000) = 282 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     11.571 ms/op
     p(99.9900) =     18.493 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.010 ms/op
Iteration   1: 3.728 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  12.158 ms/op
                 existUser·p0.9999: 15.241 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.756 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.376 ms/op
                 existUser·p0.999:  9.369 ms/op
                 existUser·p0.9999: 32.243 ms/op
                 existUser·p1.00:   32.506 ms/op

Iteration   3: 3.739 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.195 ms/op
                 existUser·p0.999:  13.734 ms/op
                 existUser·p0.9999: 28.927 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256662
  mean =      3.741 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11756 
    [ 2.500,  5.000) = 233260 
    [ 5.000,  7.500) = 9856 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     31.796 ms/op
     p(99.9990) =     32.422 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  14.920 ms/op
                 getUser·p0.9999: 19.382 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  8.960 ms/op
                 getUser·p0.9999: 27.102 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  13.277 ms/op
                 getUser·p0.9999: 21.575 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250030
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8454 
    [ 2.500,  5.000) = 228641 
    [ 5.000,  7.500) = 11879 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     12.697 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 6.537 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.016 ms/op
Iteration   1: 4.746 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 26.452 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.777 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.636 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.661 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 22.197 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202964
  mean =      4.727 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 316 
    [ 2.500,  5.000) = 154174 
    [ 5.000,  7.500) = 43571 
    [ 7.500, 10.000) = 4326 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     22.656 ms/op
     p(99.9990) =     26.828 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.455 ± 4.192  ops/ms
ClientGrpc.existUser                       thrpt       3   8.812 ± 3.280  ops/ms
ClientGrpc.getUser                         thrpt       3   8.266 ± 1.312  ops/ms
ClientGrpc.listUser                        thrpt       3   6.686 ± 1.248  ops/ms
ClientGrpc.createUser                       avgt       3   3.822 ± 1.805   ms/op
ClientGrpc.existUser                        avgt       3   3.631 ± 0.740   ms/op
ClientGrpc.getUser                          avgt       3   3.693 ± 1.433   ms/op
ClientGrpc.listUser                         avgt       3   5.015 ± 1.560   ms/op
ClientGrpc.createUser                     sample  248752   3.858 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.785           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.537           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.571           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.562           ms/op
ClientGrpc.existUser                      sample  256662   3.741 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.897           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.889           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.993           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.796           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.506           ms/op
ClientGrpc.getUser                        sample  250030   3.839 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.889           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.697           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.689           ms/op
ClientGrpc.listUser                       sample  202964   4.727 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.857           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.323           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.317           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.656           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
