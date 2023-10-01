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
# Warmup Iteration   1: 4.108 ops/ms
# Warmup Iteration   2: 8.896 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.178 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (10.079, 10.178, 10.249), stdev = 0.088
  CI (99.9%): [8.574, 11.781] (assumes normal distribution)


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
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.812 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.775 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (10.702, 10.775, 10.812), stdev = 0.063
  CI (99.9%): [9.619, 11.930] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 10.224 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.288 ops/ms
Iteration   2: 10.466 ops/ms
Iteration   3: 10.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.355 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (10.288, 10.355, 10.466), stdev = 0.097
  CI (99.9%): [8.593, 12.118] (assumes normal distribution)


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
# Warmup Iteration   1: 6.164 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 8.206 ops/ms
Iteration   1: 8.150 ops/ms
Iteration   2: 8.442 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.264 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (8.150, 8.264, 8.442), stdev = 0.156
  CI (99.9%): [5.415, 11.113] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.114 ±(99.9%) 0.002 ms/op
Iteration   2: 3.131 ±(99.9%) 0.001 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.114, 3.139, 3.172), stdev = 0.030
  CI (99.9%): [2.598, 3.681] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.001 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (2.974, 2.993, 3.030), stdev = 0.032
  CI (99.9%): [2.411, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.120 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.094, 3.120, 3.156), stdev = 0.032
  CI (99.9%): [2.537, 3.704] (assumes normal distribution)


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
# Warmup Iteration   1: 5.596 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.020 ms/op
Iteration   1: 3.869 ±(99.9%) 0.009 ms/op
Iteration   2: 3.864 ±(99.9%) 0.024 ms/op
Iteration   3: 3.854 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.854, 3.863, 3.869), stdev = 0.008
  CI (99.9%): [3.720, 4.005] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.677 ms/op
                 createUser·p0.9999: 17.902 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 14.643 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   3: 3.151 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.611 ms/op
                 createUser·p0.9999: 17.292 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307411
  mean =      3.121 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 13456 
    [ 2.500,  3.750) = 268854 
    [ 3.750,  5.000) = 23296 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 393 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.529 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     18.151 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 12.419 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 14.551 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  8.019 ms/op
                 existUser·p0.9999: 20.817 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325123
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28363 
    [ 2.500,  5.000) = 295221 
    [ 5.000,  7.500) = 1173 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     17.950 ms/op
     p(99.9990) =     21.152 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 16.994 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.316 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.208 ms/op
                 getUser·p0.9999: 18.473 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.017 ms/op
                 getUser·p0.9999: 21.059 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309578
  mean =      3.103 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13265 
    [ 2.500,  5.000) = 294488 
    [ 5.000,  7.500) = 1641 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.532 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     21.388 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 5.367 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.009 ms/op
Iteration   1: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 15.991 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   2: 3.894 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.704 ms/op
                 listUser·p0.9999: 21.385 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244523
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2226 
    [ 2.500,  5.000) = 228621 
    [ 5.000,  7.500) = 12494 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.598 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.178 ± 1.603  ops/ms
ClientGrpc.existUser                       thrpt       3  10.775 ± 1.156  ops/ms
ClientGrpc.getUser                         thrpt       3  10.355 ± 1.763  ops/ms
ClientGrpc.listUser                        thrpt       3   8.264 ± 2.849  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 0.541   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.582   ms/op
ClientGrpc.getUser                          avgt       3   3.120 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.142   ms/op
ClientGrpc.createUser                     sample  307411   3.121 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.529           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.400           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.448           ms/op
ClientGrpc.existUser                      sample  325123   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.511           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.950           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.299           ms/op
ClientGrpc.getUser                        sample  309578   3.103 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.316           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.532           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.169           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  244523   3.926 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.856           ms/op
