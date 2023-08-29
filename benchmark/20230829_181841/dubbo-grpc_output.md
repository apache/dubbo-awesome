# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ops/ms
# Warmup Iteration   2: 8.084 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 10.108 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.103 ±(99.9%) 1.903 ops/ms [Average]
  (min, avg, max) = (9.996, 10.103, 10.204), stdev = 0.104
  CI (99.9%): [8.200, 12.006] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.128 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 10.886 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.830 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (10.735, 10.830, 10.886), stdev = 0.083
  CI (99.9%): [9.324, 12.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ops/ms
# Warmup Iteration   2: 9.999 ops/ms
# Warmup Iteration   3: 10.160 ops/ms
Iteration   1: 10.326 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.406 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (10.326, 10.406, 10.450), stdev = 0.069
  CI (99.9%): [9.141, 11.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.706 ops/ms
Iteration   2: 7.782 ops/ms
Iteration   3: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.729 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (7.699, 7.729, 7.782), stdev = 0.046
  CI (99.9%): [6.886, 8.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.009 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.107 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.064, 3.107, 3.156), stdev = 0.046
  CI (99.9%): [2.261, 3.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.003 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.941 ±(99.9%) 0.003 ms/op
Iteration   3: 2.973 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.941, 2.962, 2.973), stdev = 0.018
  CI (99.9%): [2.634, 3.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.004 ms/op
Iteration   1: 3.097 ±(99.9%) 0.003 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.132 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.097, 3.132, 3.158), stdev = 0.031
  CI (99.9%): [2.561, 3.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.018 ms/op
Iteration   1: 4.120 ±(99.9%) 0.009 ms/op
Iteration   2: 4.100 ±(99.9%) 0.018 ms/op
Iteration   3: 4.131 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.117 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (4.100, 4.117, 4.131), stdev = 0.015
  CI (99.9%): [3.835, 4.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  9.073 ms/op
                 createUser·p0.9999: 23.845 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  9.068 ms/op
                 createUser·p0.9999: 14.713 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  9.467 ms/op
                 createUser·p0.9999: 21.223 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309941
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19906 
    [ 2.500,  5.000) = 286666 
    [ 5.000,  7.500) = 2586 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      9.192 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     24.016 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  10.841 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 15.800 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319758
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1182 
    [ 1.250,  2.500) = 29700 
    [ 2.500,  3.750) = 273015 
    [ 3.750,  5.000) = 13062 
    [ 5.000,  6.250) = 1421 
    [ 6.250,  7.500) = 496 
    [ 7.500,  8.750) = 350 
    [ 8.750, 10.000) = 184 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     18.780 ms/op
     p(99.9990) =     19.674 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 13.623 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 18.444 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.171 ms/op
                 getUser·p0.9999: 17.555 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306467
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 626 
    [ 1.250,  2.500) = 15673 
    [ 2.500,  3.750) = 264759 
    [ 3.750,  5.000) = 22469 
    [ 5.000,  6.250) = 1636 
    [ 6.250,  7.500) = 678 
    [ 7.500,  8.750) = 298 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      8.905 ms/op
     p(99.9900) =     17.772 ms/op
     p(99.9990) =     18.708 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.011 ms/op
Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 20.302 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 4.108 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.852 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.056 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  18.651 ms/op
                 listUser·p0.9999: 28.901 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234000
  mean =      4.104 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2063 
    [ 2.500,  5.000) = 206290 
    [ 5.000,  7.500) = 23344 
    [ 7.500, 10.000) = 1720 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.103 ± 1.903  ops/ms
ClientGrpc.existUser                       thrpt       3  10.830 ± 1.507  ops/ms
ClientGrpc.getUser                         thrpt       3  10.406 ± 1.265  ops/ms
ClientGrpc.listUser                        thrpt       3   7.729 ± 0.843  ops/ms
ClientGrpc.createUser                       avgt       3   3.107 ± 0.847   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.328   ms/op
ClientGrpc.getUser                          avgt       3   3.132 ± 0.570   ms/op
ClientGrpc.listUser                         avgt       3   4.117 ± 0.282   ms/op
ClientGrpc.createUser                     sample  309941   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.079           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.192           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.398           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  319758   3.002 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.240           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.780           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  306467   3.133 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.555           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.905           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.772           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  234000   4.104 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.180           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.179           ms/op
