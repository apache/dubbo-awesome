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
# Warmup Iteration   1: 3.139 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 10.011 ops/ms
Iteration   3: 10.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.001 ±(99.9%) 1.375 ops/ms [Average]
  (min, avg, max) = (9.921, 10.001, 10.071), stdev = 0.075
  CI (99.9%): [8.626, 11.376] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.793 ops/ms
# Warmup Iteration   2: 9.723 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.606 ±(99.9%) 3.467 ops/ms [Average]
  (min, avg, max) = (10.403, 10.606, 10.780), stdev = 0.190
  CI (99.9%): [7.139, 14.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.828 ops/ms
# Warmup Iteration   2: 9.615 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.046 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (9.924, 10.046, 10.157), stdev = 0.117
  CI (99.9%): [7.910, 12.181] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.279 ops/ms
# Warmup Iteration   2: 7.445 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.737 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (7.686, 7.737, 7.812), stdev = 0.066
  CI (99.9%): [6.535, 8.940] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.635 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.002 ms/op
Iteration   1: 3.240 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.193 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.158, 3.193, 3.240), stdev = 0.043
  CI (99.9%): [2.417, 3.969] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.388 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.001 ms/op
Iteration   3: 3.103 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.061 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.030, 3.061, 3.103), stdev = 0.038
  CI (99.9%): [2.367, 3.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.002 ms/op
Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
Iteration   3: 3.183 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.199 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.183, 3.199, 3.212), stdev = 0.015
  CI (99.9%): [2.932, 3.467] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.023 ms/op
Iteration   1: 3.905 ±(99.9%) 0.014 ms/op
Iteration   2: 3.969 ±(99.9%) 0.040 ms/op
Iteration   3: 3.964 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.905, 3.946, 3.969), stdev = 0.036
  CI (99.9%): [3.297, 4.595] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 3.225 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 37.754 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   3: 3.172 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  12.011 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300407
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10329 
    [ 2.500,  5.000) = 287725 
    [ 5.000,  7.500) = 1521 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     10.577 ms/op
     p(99.9900) =     37.222 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  9.959 ms/op
                 existUser·p0.9999: 14.829 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  9.997 ms/op
                 existUser·p0.9999: 15.658 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  13.288 ms/op
                 existUser·p0.9999: 22.665 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314137
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21009 
    [ 2.500,  5.000) = 290869 
    [ 5.000,  7.500) = 1313 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     10.874 ms/op
     p(99.9900) =     22.190 ms/op
     p(99.9990) =     23.869 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  9.745 ms/op
                 getUser·p0.9999: 21.724 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  9.120 ms/op
                 getUser·p0.9999: 16.458 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 19.726 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298310
  mean =      3.218 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11349 
    [ 2.500,  5.000) = 283867 
    [ 5.000,  7.500) = 2119 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      9.268 ms/op
     p(99.9900) =     21.174 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 6.879 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.011 ms/op
Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  15.125 ms/op
                 listUser·p0.9999: 22.764 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.774 ms/op
                 listUser·p0.9999: 16.772 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  20.251 ms/op
                 listUser·p0.9999: 22.599 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239701
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1758 
    [ 2.500,  5.000) = 218857 
    [ 5.000,  7.500) = 17219 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.941 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.001 ± 1.375  ops/ms
ClientGrpc.existUser                       thrpt       3  10.606 ± 3.467  ops/ms
ClientGrpc.getUser                         thrpt       3  10.046 ± 2.135  ops/ms
ClientGrpc.listUser                        thrpt       3   7.737 ± 1.203  ops/ms
ClientGrpc.createUser                       avgt       3   3.193 ± 0.776   ms/op
ClientGrpc.existUser                        avgt       3   3.061 ± 0.694   ms/op
ClientGrpc.getUser                          avgt       3   3.199 ± 0.267   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.649   ms/op
ClientGrpc.createUser                     sample  300407   3.196 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.577           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.222           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.076           ms/op
ClientGrpc.existUser                      sample  314137   3.053 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.874           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.190           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.838           ms/op
ClientGrpc.getUser                        sample  298310   3.218 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.716           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.268           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.174           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.315           ms/op
ClientGrpc.listUser                       sample  239701   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.112           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
