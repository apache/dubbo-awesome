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
# Warmup Iteration   1: 3.811 ops/ms
# Warmup Iteration   2: 8.164 ops/ms
# Warmup Iteration   3: 9.587 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 10.107 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.981 ±(99.9%) 3.760 ops/ms [Average]
  (min, avg, max) = (9.743, 9.981, 10.107), stdev = 0.206
  CI (99.9%): [6.222, 13.741] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.235 ops/ms
# Warmup Iteration   3: 10.427 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.449 ±(99.9%) 2.907 ops/ms [Average]
  (min, avg, max) = (10.265, 10.449, 10.547), stdev = 0.159
  CI (99.9%): [7.542, 13.356] (assumes normal distribution)


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
# Warmup Iteration   1: 6.671 ops/ms
# Warmup Iteration   2: 9.569 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 9.933 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.965 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (9.933, 9.965, 10.000), stdev = 0.034
  CI (99.9%): [9.348, 10.583] (assumes normal distribution)


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
# Warmup Iteration   1: 5.228 ops/ms
# Warmup Iteration   2: 7.734 ops/ms
# Warmup Iteration   3: 7.980 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (7.952, 8.010, 8.088), stdev = 0.070
  CI (99.9%): [6.734, 9.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.002 ms/op
Iteration   1: 3.198 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.003 ms/op
Iteration   3: 3.191 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.173 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.128, 3.173, 3.198), stdev = 0.038
  CI (99.9%): [2.471, 3.874] (assumes normal distribution)


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.002 ms/op
Iteration   1: 3.045 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.013, 3.028, 3.045), stdev = 0.016
  CI (99.9%): [2.734, 3.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
Iteration   1: 3.185 ±(99.9%) 0.006 ms/op
Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.197 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.182, 3.197, 3.222), stdev = 0.022
  CI (99.9%): [2.787, 3.606] (assumes normal distribution)


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
# Warmup Iteration   1: 5.588 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.033 ms/op
Iteration   1: 4.012 ±(99.9%) 0.025 ms/op
Iteration   2: 4.014 ±(99.9%) 0.032 ms/op
Iteration   3: 3.975 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.000 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.975, 4.000, 4.014), stdev = 0.022
  CI (99.9%): [3.604, 4.396] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
Iteration   1: 3.228 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.443 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  11.058 ms/op
                 createUser·p0.9999: 16.911 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.233 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.306 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 22.116 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298696
  mean =      3.212 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6821 
    [ 2.500,  5.000) = 290061 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     21.336 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.147 ms/op
                 existUser·p0.9999: 25.765 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.627 ms/op
                 existUser·p0.999:  9.409 ms/op
                 existUser·p0.9999: 19.510 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313133
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16623 
    [ 2.500,  5.000) = 294799 
    [ 5.000,  7.500) = 1369 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.765 ms/op
     p(99.9900) =     20.066 ms/op
     p(99.9990) =     26.079 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
Iteration   1: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.778 ms/op
                 getUser·p0.999:  10.404 ms/op
                 getUser·p0.9999: 27.160 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.480 ms/op
                 getUser·p0.999:  12.825 ms/op
                 getUser·p0.9999: 14.957 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.234 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 20.684 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300171
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7746 
    [ 2.500,  5.000) = 290467 
    [ 5.000,  7.500) = 1432 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      9.221 ms/op
     p(99.9900) =     20.671 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.010 ms/op
Iteration   1: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.427 ms/op
                 listUser·p0.9999: 22.246 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 20.063 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240379
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1911 
    [ 2.500,  5.000) = 222044 
    [ 5.000,  7.500) = 14769 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.607 ms/op
     p(99.9900) =     21.822 ms/op
     p(99.9990) =     22.498 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.981 ± 3.760  ops/ms
ClientGrpc.existUser                       thrpt       3  10.449 ± 2.907  ops/ms
ClientGrpc.getUser                         thrpt       3   9.965 ± 0.617  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 1.276  ops/ms
ClientGrpc.createUser                       avgt       3   3.173 ± 0.701   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.294   ms/op
ClientGrpc.getUser                          avgt       3   3.197 ± 0.409   ms/op
ClientGrpc.listUser                         avgt       3   4.000 ± 0.396   ms/op
ClientGrpc.createUser                     sample  298696   3.212 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.306           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.336           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.233           ms/op
ClientGrpc.existUser                      sample  313133   3.066 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.686           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.765           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.066           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  300171   3.198 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.221           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.671           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.754           ms/op
ClientGrpc.listUser                       sample  240379   3.995 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.657           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.607           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.822           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
