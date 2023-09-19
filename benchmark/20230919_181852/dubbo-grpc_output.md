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
# Warmup Iteration   1: 4.003 ops/ms
# Warmup Iteration   2: 8.334 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 9.999 ops/ms
Iteration   3: 10.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.035 ±(99.9%) 1.907 ops/ms [Average]
  (min, avg, max) = (9.953, 10.035, 10.152), stdev = 0.105
  CI (99.9%): [8.128, 11.941] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.742 ops/ms
# Warmup Iteration   2: 9.952 ops/ms
# Warmup Iteration   3: 10.480 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.589 ±(99.9%) 2.950 ops/ms [Average]
  (min, avg, max) = (10.436, 10.589, 10.758), stdev = 0.162
  CI (99.9%): [7.639, 13.539] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 9.855 ops/ms
# Warmup Iteration   3: 10.120 ops/ms
Iteration   1: 9.934 ops/ms
Iteration   2: 9.842 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.968 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (9.842, 9.968, 10.128), stdev = 0.146
  CI (99.9%): [7.309, 12.627] (assumes normal distribution)


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
# Warmup Iteration   1: 5.849 ops/ms
# Warmup Iteration   2: 7.952 ops/ms
# Warmup Iteration   3: 8.206 ops/ms
Iteration   1: 8.243 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.290 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (8.243, 8.290, 8.371), stdev = 0.071
  CI (99.9%): [6.996, 9.584] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.003 ms/op
Iteration   2: 3.169 ±(99.9%) 0.001 ms/op
Iteration   3: 3.258 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.185 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.129, 3.185, 3.258), stdev = 0.066
  CI (99.9%): [1.980, 4.391] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.001 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.044 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (2.997, 3.044, 3.087), stdev = 0.045
  CI (99.9%): [2.224, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.002 ms/op
Iteration   1: 3.144 ±(99.9%) 0.005 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.284 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.195 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (3.144, 3.195, 3.284), stdev = 0.078
  CI (99.9%): [1.781, 4.609] (assumes normal distribution)


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.037 ms/op
Iteration   2: 3.823 ±(99.9%) 0.022 ms/op
Iteration   3: 3.898 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.823, 3.851, 3.898), stdev = 0.040
  CI (99.9%): [3.118, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.006 ms/op
Iteration   1: 3.221 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.783 ms/op
                 createUser·p0.9999: 12.552 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  9.059 ms/op
                 createUser·p0.9999: 13.088 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  12.899 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300194
  mean =      3.197 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8746 
    [ 2.500,  5.000) = 289301 
    [ 5.000,  7.500) = 1476 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.418 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.710 ms/op
                 existUser·p0.999:  8.660 ms/op
                 existUser·p0.9999: 11.927 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.463 ms/op
                 existUser·p0.9999: 20.163 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 20.605 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313702
  mean =      3.059 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18666 
    [ 2.500,  5.000) = 293241 
    [ 5.000,  7.500) = 1411 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     20.075 ms/op
     p(99.9990) =     20.901 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  9.099 ms/op
                 getUser·p0.9999: 12.778 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.529 ms/op
                 getUser·p0.9999: 12.993 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  6.767 ms/op
                 getUser·p0.9999: 15.944 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298513
  mean =      3.214 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 479 
    [ 1.250,  2.500) = 8175 
    [ 2.500,  3.750) = 250899 
    [ 3.750,  5.000) = 36989 
    [ 5.000,  6.250) = 1104 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     15.312 ms/op
     p(99.9990) =     16.375 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 5.728 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.009 ms/op
Iteration   1: 3.770 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 15.033 ms/op
                 listUser·p1.00:   15.761 ms/op

Iteration   2: 3.872 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.853 ms/op
                 listUser·p0.9999: 18.095 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 3.896 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249551
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2519 
    [ 2.500,  3.750) = 121602 
    [ 3.750,  5.000) = 110919 
    [ 5.000,  6.250) = 9399 
    [ 6.250,  7.500) = 3844 
    [ 7.500,  8.750) = 538 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 144 
    [13.750, 15.000) = 115 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.721 ms/op
     p(99.9900) =     17.248 ms/op
     p(99.9990) =     18.548 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.035 ± 1.907  ops/ms
ClientGrpc.existUser                       thrpt       3  10.589 ± 2.950  ops/ms
ClientGrpc.getUser                         thrpt       3   9.968 ± 2.659  ops/ms
ClientGrpc.listUser                        thrpt       3   8.290 ± 1.294  ops/ms
ClientGrpc.createUser                       avgt       3   3.185 ± 1.206   ms/op
ClientGrpc.existUser                        avgt       3   3.044 ± 0.819   ms/op
ClientGrpc.getUser                          avgt       3   3.195 ± 1.414   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 0.733   ms/op
ClientGrpc.createUser                     sample  300194   3.197 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.791           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.418           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.724           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.609           ms/op
ClientGrpc.existUser                      sample  313702   3.059 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.075           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  298513   3.214 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.312           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.039           ms/op
ClientGrpc.listUser                       sample  249551   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.893           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.721           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.711           ms/op
