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
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.919 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.519 ±(99.9%) 6.356 ops/ms [Average]
  (min, avg, max) = (10.282, 10.519, 10.919), stdev = 0.348
  CI (99.9%): [4.163, 16.875] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.110 ops/ms
# Warmup Iteration   2: 10.515 ops/ms
# Warmup Iteration   3: 10.983 ops/ms
Iteration   1: 11.169 ops/ms
Iteration   2: 10.944 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.040 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (10.944, 11.040, 11.169), stdev = 0.116
  CI (99.9%): [8.927, 13.153] (assumes normal distribution)


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
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 10.953 ops/ms
Iteration   3: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.662 ±(99.9%) 6.279 ops/ms [Average]
  (min, avg, max) = (10.283, 10.662, 10.953), stdev = 0.344
  CI (99.9%): [4.384, 16.941] (assumes normal distribution)


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
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 7.798 ops/ms
# Warmup Iteration   3: 8.111 ops/ms
Iteration   1: 7.966 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.027 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (7.966, 8.027, 8.133), stdev = 0.092
  CI (99.9%): [6.349, 9.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (2.982, 3.062, 3.111), stdev = 0.070
  CI (99.9%): [1.789, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.004 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.866 ±(99.9%) 0.002 ms/op
Iteration   3: 2.856 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (2.856, 2.884, 2.930), stdev = 0.040
  CI (99.9%): [2.146, 3.622] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.022, 3.028, 3.036), stdev = 0.007
  CI (99.9%): [2.899, 3.157] (assumes normal distribution)


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
# Warmup Iteration   1: 4.980 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.015 ms/op
Iteration   1: 3.923 ±(99.9%) 0.038 ms/op
Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
Iteration   3: 3.883 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.912 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.883, 3.912, 3.930), stdev = 0.025
  CI (99.9%): [3.452, 4.372] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.178 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.235 ms/op
                 createUser·p0.9999: 11.283 ms/op
                 createUser·p1.00:   11.780 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.560 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  10.956 ms/op
                 createUser·p0.9999: 16.378 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307202
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 990 
    [ 1.250,  2.500) = 28856 
    [ 2.500,  3.750) = 240018 
    [ 3.750,  5.000) = 36259 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.248 ms/op
     p(99.9900) =     14.308 ms/op
     p(99.9990) =     16.692 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.429 ms/op
                 existUser·p0.9999: 11.717 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.602 ms/op
                 existUser·p0.9999: 12.516 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.372 ms/op
                 existUser·p0.9999: 12.905 ms/op
                 existUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331851
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2623 
    [ 1.250,  2.500) = 52280 
    [ 2.500,  3.750) = 264499 
    [ 3.750,  5.000) = 11782 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     12.577 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 12.980 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.310 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  5.988 ms/op
                 getUser·p0.9999: 15.860 ms/op
                 getUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311931
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29338 
    [ 2.500,  5.000) = 281869 
    [ 5.000,  7.500) = 483 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.015 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.120 ms/op
                 listUser·p0.9999: 19.359 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 18.515 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.638 ms/op
                 listUser·p0.9999: 26.141 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244087
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4726 
    [ 2.500,  5.000) = 213812 
    [ 5.000,  7.500) = 24559 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.745 ms/op
     p(99.9900) =     25.218 ms/op
     p(99.9990) =     26.532 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.519 ± 6.356  ops/ms
ClientGrpc.existUser                       thrpt       3  11.040 ± 2.113  ops/ms
ClientGrpc.getUser                         thrpt       3  10.662 ± 6.279  ops/ms
ClientGrpc.listUser                        thrpt       3   8.027 ± 1.678  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 1.273   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.738   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.129   ms/op
ClientGrpc.listUser                         avgt       3   3.912 ± 0.460   ms/op
ClientGrpc.createUser                     sample  307202   3.124 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.707           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.248           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.843           ms/op
ClientGrpc.existUser                      sample  331851   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.598           ms/op
ClientGrpc.getUser                        sample  311931   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.922           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.972           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  244087   3.934 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.736           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.745           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.218           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
