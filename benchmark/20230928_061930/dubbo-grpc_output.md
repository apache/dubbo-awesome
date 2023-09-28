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
# Warmup Iteration   1: 3.532 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 9.428 ops/ms
Iteration   1: 9.792 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 9.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.930 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (9.792, 9.930, 10.083), stdev = 0.146
  CI (99.9%): [7.270, 12.589] (assumes normal distribution)


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
# Warmup Iteration   1: 6.541 ops/ms
# Warmup Iteration   2: 10.109 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.810 ops/ms
Iteration   2: 10.675 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.645 ±(99.9%) 3.319 ops/ms [Average]
  (min, avg, max) = (10.450, 10.645, 10.810), stdev = 0.182
  CI (99.9%): [7.327, 13.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.540 ops/ms
# Warmup Iteration   2: 9.013 ops/ms
# Warmup Iteration   3: 9.778 ops/ms
Iteration   1: 9.747 ops/ms
Iteration   2: 9.899 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.852 ±(99.9%) 1.661 ops/ms [Average]
  (min, avg, max) = (9.747, 9.852, 9.910), stdev = 0.091
  CI (99.9%): [8.190, 11.513] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.129 ops/ms
# Warmup Iteration   2: 7.683 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 8.480 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.245 ±(99.9%) 3.711 ops/ms [Average]
  (min, avg, max) = (8.120, 8.245, 8.480), stdev = 0.203
  CI (99.9%): [4.534, 11.956] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.001 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.204 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.196 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.156, 3.196, 3.229), stdev = 0.037
  CI (99.9%): [2.517, 3.875] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.001 ms/op
Iteration   1: 3.052 ±(99.9%) 0.001 ms/op
Iteration   2: 3.063 ±(99.9%) 0.001 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.054 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (3.049, 3.054, 3.063), stdev = 0.007
  CI (99.9%): [2.925, 3.184] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.139 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
Iteration   3: 3.185 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.177 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.139, 3.177, 3.206), stdev = 0.035
  CI (99.9%): [2.543, 3.811] (assumes normal distribution)


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
# Warmup Iteration   1: 5.930 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.020 ms/op
Iteration   1: 3.918 ±(99.9%) 0.010 ms/op
Iteration   2: 3.926 ±(99.9%) 0.008 ms/op
Iteration   3: 3.944 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.929 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.918, 3.929, 3.944), stdev = 0.013
  CI (99.9%): [3.684, 4.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 23.360 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  9.416 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.650 ms/op
                 createUser·p0.9999: 37.224 ms/op
                 createUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301177
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7737 
    [ 2.500,  5.000) = 291819 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 17.050 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.695 ms/op
                 existUser·p0.9999: 19.148 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.029 ms/op
                 existUser·p0.9999: 20.624 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320357
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25266 
    [ 2.500,  5.000) = 293465 
    [ 5.000,  7.500) = 1281 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     20.925 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
Iteration   1: 3.158 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 15.116 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  11.733 ms/op
                 getUser·p0.9999: 14.742 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 17.461 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302959
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 8619 
    [ 2.500,  3.750) = 264985 
    [ 3.750,  5.000) = 27005 
    [ 5.000,  6.250) = 1192 
    [ 6.250,  7.500) = 341 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     18.311 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.604 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.009 ms/op
Iteration   1: 3.985 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 17.397 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.129 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 19.297 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242278
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2146 
    [ 2.500,  3.750) = 94546 
    [ 3.750,  5.000) = 128956 
    [ 5.000,  6.250) = 10478 
    [ 6.250,  7.500) = 4713 
    [ 7.500,  8.750) = 685 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 125 
    [15.000, 16.250) = 90 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     18.638 ms/op
     p(99.9990) =     19.868 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.930 ± 2.659  ops/ms
ClientGrpc.existUser                       thrpt       3  10.645 ± 3.319  ops/ms
ClientGrpc.getUser                         thrpt       3   9.852 ± 1.661  ops/ms
ClientGrpc.listUser                        thrpt       3   8.245 ± 3.711  ops/ms
ClientGrpc.createUser                       avgt       3   3.196 ± 0.679   ms/op
ClientGrpc.existUser                        avgt       3   3.054 ± 0.130   ms/op
ClientGrpc.getUser                          avgt       3   3.177 ± 0.634   ms/op
ClientGrpc.listUser                         avgt       3   3.929 ± 0.245   ms/op
ClientGrpc.createUser                     sample  301177   3.189 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.207           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.521           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.683           ms/op
ClientGrpc.existUser                      sample  320357   2.995 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.635           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.037           ms/op
ClientGrpc.getUser                        sample  302959   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.787           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.957           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.322           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  242278   3.962 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.849           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.680           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.638           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.956           ms/op
