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
# Warmup Iteration   1: 4.163 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.746 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.366 ±(99.9%) 3.606 ops/ms [Average]
  (min, avg, max) = (10.216, 10.366, 10.590), stdev = 0.198
  CI (99.9%): [6.760, 13.973] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.345 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 11.043 ops/ms
Iteration   1: 10.853 ops/ms
Iteration   2: 11.122 ops/ms
Iteration   3: 10.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.940 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (10.846, 10.940, 11.122), stdev = 0.157
  CI (99.9%): [8.067, 13.813] (assumes normal distribution)


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
# Warmup Iteration   1: 6.993 ops/ms
# Warmup Iteration   2: 10.017 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (10.310, 10.455, 10.561), stdev = 0.130
  CI (99.9%): [8.081, 12.830] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 7.685 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.807 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (7.708, 7.807, 7.922), stdev = 0.108
  CI (99.9%): [5.841, 9.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.123 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.069, 3.096, 3.123), stdev = 0.027
  CI (99.9%): [2.599, 3.592] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.002 ms/op
Iteration   2: 2.901 ±(99.9%) 0.003 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.924 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.901, 2.924, 2.938), stdev = 0.020
  CI (99.9%): [2.551, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.058, 3.084, 3.099), stdev = 0.022
  CI (99.9%): [2.677, 3.491] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.019 ms/op
Iteration   1: 4.147 ±(99.9%) 0.014 ms/op
Iteration   2: 4.158 ±(99.9%) 0.014 ms/op
Iteration   3: 4.085 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.130 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (4.085, 4.130, 4.158), stdev = 0.040
  CI (99.9%): [3.408, 4.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.958 ms/op
                 createUser·p0.999:  9.152 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  7.995 ms/op
                 createUser·p0.9999: 15.322 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  11.920 ms/op
                 createUser·p0.9999: 32.021 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311585
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22281 
    [ 2.500,  5.000) = 286702 
    [ 5.000,  7.500) = 1928 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      9.720 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 24.716 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 2.904 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.852 ms/op
                 existUser·p0.9999: 23.329 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 2.945 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 26.739 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327553
  mean =      2.932 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35649 
    [ 2.500,  5.000) = 290082 
    [ 5.000,  7.500) = 1430 
    [ 7.500, 10.000) = 190 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     25.764 ms/op
     p(99.9990) =     27.096 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.789 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 16.361 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.511 ms/op
                 getUser·p0.9999: 22.420 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.698 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 17.960 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310198
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15310 
    [ 2.500,  5.000) = 292544 
    [ 5.000,  7.500) = 1763 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     21.888 ms/op
     p(99.9990) =     22.705 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 5.653 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.012 ms/op
Iteration   1: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.200 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.289 ms/op
                 listUser·p0.999:  14.939 ms/op
                 listUser·p0.9999: 17.996 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 4.161 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.730 ms/op
                 listUser·p0.9999: 31.992 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233548
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1876 
    [ 2.500,  5.000) = 205419 
    [ 5.000,  7.500) = 24146 
    [ 7.500, 10.000) = 1544 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.195 ms/op
     p(99.9900) =     31.118 ms/op
     p(99.9990) =     32.167 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.366 ± 3.606  ops/ms
ClientGrpc.existUser                       thrpt       3  10.940 ± 2.873  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 2.374  ops/ms
ClientGrpc.listUser                        thrpt       3   7.807 ± 1.966  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.496   ms/op
ClientGrpc.existUser                        avgt       3   2.924 ± 0.374   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 0.407   ms/op
ClientGrpc.listUser                         avgt       3   4.130 ± 0.723   ms/op
ClientGrpc.createUser                     sample  311585   3.079 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.523           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.720           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.162           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.800           ms/op
ClientGrpc.existUser                      sample  327553   2.932 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.646           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.764           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.197           ms/op
ClientGrpc.getUser                        sample  310198   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.888           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  233548   4.109 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.047           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.381           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.195           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.118           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.834           ms/op
