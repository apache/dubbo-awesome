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
# Warmup Iteration   1: 3.030 ops/ms
# Warmup Iteration   2: 6.251 ops/ms
# Warmup Iteration   3: 7.916 ops/ms
Iteration   1: 8.186 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.071 ±(99.9%) 2.091 ops/ms [Average]
  (min, avg, max) = (7.956, 8.071, 8.186), stdev = 0.115
  CI (99.9%): [5.980, 10.162] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.606 ops/ms
# Warmup Iteration   2: 8.095 ops/ms
# Warmup Iteration   3: 8.547 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.724 ops/ms
Iteration   3: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.578 ±(99.9%) 3.583 ops/ms [Average]
  (min, avg, max) = (8.355, 8.578, 8.724), stdev = 0.196
  CI (99.9%): [4.995, 12.160] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.117 ops/ms
# Warmup Iteration   2: 7.558 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.308 ±(99.9%) 2.521 ops/ms [Average]
  (min, avg, max) = (8.191, 8.308, 8.460), stdev = 0.138
  CI (99.9%): [5.788, 10.829] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ops/ms
# Warmup Iteration   2: 5.787 ops/ms
# Warmup Iteration   3: 6.583 ops/ms
Iteration   1: 6.537 ops/ms
Iteration   2: 6.596 ops/ms
Iteration   3: 6.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.564 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (6.537, 6.564, 6.596), stdev = 0.030
  CI (99.9%): [6.020, 7.108] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.003 ms/op
Iteration   1: 3.924 ±(99.9%) 0.003 ms/op
Iteration   2: 3.906 ±(99.9%) 0.003 ms/op
Iteration   3: 3.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.934 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.906, 3.934, 3.973), stdev = 0.035
  CI (99.9%): [3.300, 4.568] (assumes normal distribution)


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
# Warmup Iteration   1: 5.212 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.005 ms/op
Iteration   1: 3.700 ±(99.9%) 0.003 ms/op
Iteration   2: 3.817 ±(99.9%) 0.003 ms/op
Iteration   3: 3.773 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.763 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.700, 3.763, 3.817), stdev = 0.059
  CI (99.9%): [2.684, 4.842] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.413 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.002 ms/op
Iteration   1: 3.937 ±(99.9%) 0.003 ms/op
Iteration   2: 3.848 ±(99.9%) 0.005 ms/op
Iteration   3: 3.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.898 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.848, 3.898, 3.937), stdev = 0.046
  CI (99.9%): [3.060, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 6.508 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.268 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.987 ±(99.9%) 0.013 ms/op
Iteration   1: 4.724 ±(99.9%) 0.016 ms/op
Iteration   2: 4.902 ±(99.9%) 0.014 ms/op
Iteration   3: 4.739 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.788 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (4.724, 4.788, 4.902), stdev = 0.099
  CI (99.9%): [2.983, 6.594] (assumes normal distribution)


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
# Warmup Iteration   1: 5.509 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   6.927 ms/op
                 createUser·p0.999:  13.070 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  10.071 ms/op
                 createUser·p0.9999: 18.182 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 32.467 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 241793
  mean =      3.969 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6255 
    [ 2.500,  5.000) = 215800 
    [ 5.000,  7.500) = 18374 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     11.738 ms/op
     p(99.9900) =     31.714 ms/op
     p(99.9990) =     32.760 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 5.039 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.010 ms/op
Iteration   1: 3.816 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 17.604 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.681 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  9.277 ms/op
                 existUser·p0.9999: 16.830 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.823 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  10.634 ms/op
                 existUser·p0.9999: 19.658 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254343
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11568 
    [ 2.500,  5.000) = 229569 
    [ 5.000,  7.500) = 11879 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     17.517 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 5.536 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
Iteration   1: 3.977 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 16.185 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   2: 3.971 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.167 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 18.543 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.894 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.199 ms/op
                 getUser·p0.999:  13.284 ms/op
                 getUser·p0.9999: 34.326 ms/op
                 getUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243151
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6592 
    [ 2.500,  5.000) = 219045 
    [ 5.000,  7.500) = 15667 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     11.434 ms/op
     p(99.9900) =     33.337 ms/op
     p(99.9990) =     34.706 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 6.969 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.082 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.016 ms/op
Iteration   1: 4.900 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  17.719 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 4.918 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.188 ms/op
                 listUser·p0.999:  18.906 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.820 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196631
  mean =      4.879 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 735 
    [ 2.500,  5.000) = 136091 
    [ 5.000,  7.500) = 52958 
    [ 7.500, 10.000) = 5828 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     18.800 ms/op
     p(99.9900) =     23.604 ms/op
     p(99.9990) =     24.580 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.071 ± 2.091  ops/ms
ClientGrpc.existUser                       thrpt       3   8.578 ± 3.583  ops/ms
ClientGrpc.getUser                         thrpt       3   8.308 ± 2.521  ops/ms
ClientGrpc.listUser                        thrpt       3   6.564 ± 0.544  ops/ms
ClientGrpc.createUser                       avgt       3   3.934 ± 0.634   ms/op
ClientGrpc.existUser                        avgt       3   3.763 ± 1.079   ms/op
ClientGrpc.getUser                          avgt       3   3.898 ± 0.838   ms/op
ClientGrpc.listUser                         avgt       3   4.788 ± 1.806   ms/op
ClientGrpc.createUser                     sample  241793   3.969 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.761           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.738           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.714           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.341           ms/op
ClientGrpc.existUser                      sample  254343   3.772 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.901           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.043           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.517           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.725           ms/op
ClientGrpc.getUser                        sample  243151   3.947 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.899           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.955           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.434           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.337           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.800           ms/op
ClientGrpc.listUser                       sample  196631   4.879 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.831           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.800           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.604           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
