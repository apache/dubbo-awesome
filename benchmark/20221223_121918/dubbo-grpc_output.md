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
# Warmup Iteration   1: 4.850 ops/ms
# Warmup Iteration   2: 9.689 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.468 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (10.388, 10.468, 10.539), stdev = 0.076
  CI (99.9%): [9.086, 11.851] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 10.810 ops/ms
Iteration   1: 10.973 ops/ms
Iteration   2: 10.918 ops/ms
Iteration   3: 11.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.012 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (10.918, 11.012, 11.145), stdev = 0.118
  CI (99.9%): [8.855, 13.169] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.840 ops/ms
# Warmup Iteration   2: 10.665 ops/ms
# Warmup Iteration   3: 10.832 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.706 ±(99.9%) 2.299 ops/ms [Average]
  (min, avg, max) = (10.591, 10.706, 10.841), stdev = 0.126
  CI (99.9%): [8.407, 13.005] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.037 ops/ms
# Warmup Iteration   2: 7.763 ops/ms
# Warmup Iteration   3: 8.052 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.470 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.324 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (8.177, 8.324, 8.470), stdev = 0.146
  CI (99.9%): [5.654, 10.995] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (2.956, 3.006, 3.038), stdev = 0.044
  CI (99.9%): [2.206, 3.806] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.002 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.960, 2.967, 2.979), stdev = 0.010
  CI (99.9%): [2.780, 3.153] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.997 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.991, 2.997, 3.003), stdev = 0.006
  CI (99.9%): [2.882, 3.111] (assumes normal distribution)


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.043 ms/op
Iteration   1: 4.072 ±(99.9%) 0.019 ms/op
Iteration   2: 3.986 ±(99.9%) 0.012 ms/op
Iteration   3: 3.882 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.980 ±(99.9%) 1.742 ms/op [Average]
  (min, avg, max) = (3.882, 3.980, 4.072), stdev = 0.095
  CI (99.9%): [2.238, 5.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.863 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  8.349 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 17.522 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309153
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1124 
    [ 1.250,  2.500) = 24217 
    [ 2.500,  3.750) = 252637 
    [ 3.750,  5.000) = 30136 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     15.843 ms/op
     p(99.9990) =     17.885 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  5.109 ms/op
                 existUser·p0.9999: 11.301 ms/op
                 existUser·p1.00:   11.649 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  7.887 ms/op
                 existUser·p0.9999: 21.137 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.833 ms/op
                 existUser·p0.9999: 15.663 ms/op
                 existUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330577
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56085 
    [ 2.500,  5.000) = 273797 
    [ 5.000,  7.500) = 432 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.877 ms/op
     p(99.9900) =     16.134 ms/op
     p(99.9990) =     21.584 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.255 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  5.767 ms/op
                 getUser·p0.9999: 12.191 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.398 ms/op
                 getUser·p0.9999: 12.750 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.093 ms/op
                 getUser·p0.9999: 17.317 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317812
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1450 
    [ 1.250,  2.500) = 25737 
    [ 2.500,  3.750) = 271933 
    [ 3.750,  5.000) = 17914 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.255 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.391 ms/op
     p(99.9900) =     16.779 ms/op
     p(99.9990) =     18.049 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.451 ms/op
                 listUser·p0.9999: 14.827 ms/op
                 listUser·p1.00:   15.679 ms/op

Iteration   2: 3.883 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.639 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 22.758 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.008 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.036 ms/op
                 listUser·p0.999:  13.394 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242170
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6906 
    [ 2.500,  5.000) = 203991 
    [ 5.000,  7.500) = 30070 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.591 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.468 ± 1.383  ops/ms
ClientGrpc.existUser                       thrpt       3  11.012 ± 2.157  ops/ms
ClientGrpc.getUser                         thrpt       3  10.706 ± 2.299  ops/ms
ClientGrpc.listUser                        thrpt       3   8.324 ± 2.670  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.800   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 0.187   ms/op
ClientGrpc.getUser                          avgt       3   2.997 ± 0.114   ms/op
ClientGrpc.listUser                         avgt       3   3.980 ± 1.742   ms/op
ClientGrpc.createUser                     sample  309153   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  330577   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.134           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  317812   3.019 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.255           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.178           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.391           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.779           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  242170   3.962 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.909           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.591           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.512           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
