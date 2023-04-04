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
# Warmup Iteration   1: 2.373 ops/ms
# Warmup Iteration   2: 6.085 ops/ms
# Warmup Iteration   3: 6.957 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.386 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.546 ±(99.9%) 4.788 ops/ms [Average]
  (min, avg, max) = (7.386, 7.546, 7.849), stdev = 0.262
  CI (99.9%): [2.758, 12.334] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ops/ms
# Warmup Iteration   2: 7.374 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 8.343 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.367 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (8.295, 8.367, 8.464), stdev = 0.087
  CI (99.9%): [6.776, 9.959] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 7.124 ops/ms
# Warmup Iteration   3: 7.502 ops/ms
Iteration   1: 7.701 ops/ms
Iteration   2: 7.776 ops/ms
Iteration   3: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.742 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (7.701, 7.742, 7.776), stdev = 0.038
  CI (99.9%): [7.054, 8.430] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ops/ms
# Warmup Iteration   2: 5.202 ops/ms
# Warmup Iteration   3: 5.879 ops/ms
Iteration   1: 5.715 ops/ms
Iteration   2: 5.997 ops/ms
Iteration   3: 5.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.874 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (5.715, 5.874, 5.997), stdev = 0.144
  CI (99.9%): [3.241, 8.507] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.104 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.010 ms/op
Iteration   1: 4.062 ±(99.9%) 0.003 ms/op
Iteration   2: 4.149 ±(99.9%) 0.003 ms/op
Iteration   3: 4.186 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.132 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (4.062, 4.132, 4.186), stdev = 0.064
  CI (99.9%): [2.972, 5.293] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.793 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.002 ms/op
Iteration   1: 4.006 ±(99.9%) 0.003 ms/op
Iteration   2: 3.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.780 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.926 ±(99.9%) 2.311 ms/op [Average]
  (min, avg, max) = (3.780, 3.926, 4.006), stdev = 0.127
  CI (99.9%): [1.615, 6.237] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.176 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.012 ms/op
Iteration   1: 4.329 ±(99.9%) 0.003 ms/op
Iteration   2: 4.242 ±(99.9%) 0.004 ms/op
Iteration   3: 4.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.229 ±(99.9%) 1.976 ms/op [Average]
  (min, avg, max) = (4.114, 4.229, 4.329), stdev = 0.108
  CI (99.9%): [2.253, 6.204] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.263 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.644 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.018 ms/op
Iteration   1: 5.070 ±(99.9%) 0.011 ms/op
Iteration   2: 5.377 ±(99.9%) 0.021 ms/op
Iteration   3: 5.262 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.236 ±(99.9%) 2.825 ms/op [Average]
  (min, avg, max) = (5.070, 5.236, 5.377), stdev = 0.155
  CI (99.9%): [2.411, 8.062] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.014 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.296 ms/op
                 createUser·p0.999:  12.175 ms/op
                 createUser·p0.9999: 21.479 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.476 ms/op
                 createUser·p0.999:  16.110 ms/op
                 createUser·p0.9999: 19.977 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   3: 4.157 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  11.713 ms/op
                 createUser·p0.9999: 21.440 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231716
  mean =      4.142 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6403 
    [ 2.500,  5.000) = 194125 
    [ 5.000,  7.500) = 28925 
    [ 7.500, 10.000) = 1826 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     23.933 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.851 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  11.310 ms/op
                 existUser·p0.9999: 27.081 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 3.829 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.499 ms/op
                 existUser·p0.999:  13.875 ms/op
                 existUser·p0.9999: 38.797 ms/op
                 existUser·p1.00:   39.518 ms/op

Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  9.634 ms/op
                 existUser·p0.9999: 23.280 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251854
  mean =      3.812 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10717 
    [ 2.500,  5.000) = 225377 
    [ 5.000,  7.500) = 13702 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     36.426 ms/op
     p(99.9990) =     39.348 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.267 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.992 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  11.793 ms/op
                 getUser·p0.9999: 16.445 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  13.216 ms/op
                 getUser·p0.9999: 24.775 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   6.819 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 29.452 ms/op
                 getUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235406
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8012 
    [ 2.500,  5.000) = 200195 
    [ 5.000,  7.500) = 25495 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     12.003 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.192 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.793 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.413 ±(99.9%) 0.023 ms/op
Iteration   1: 5.359 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 28.968 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   2: 5.393 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 33.821 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 5.342 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  20.154 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179004
  mean =      5.365 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 434 
    [ 2.500,  5.000) = 84368 
    [ 5.000,  7.500) = 79974 
    [ 7.500, 10.000) = 11953 
    [10.000, 12.500) = 1514 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.094 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     31.559 ms/op
     p(99.9990) =     34.106 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.546 ± 4.788  ops/ms
ClientGrpc.existUser                       thrpt       3   8.367 ± 1.591  ops/ms
ClientGrpc.getUser                         thrpt       3   7.742 ± 0.688  ops/ms
ClientGrpc.listUser                        thrpt       3   5.874 ± 2.633  ops/ms
ClientGrpc.createUser                       avgt       3   4.132 ± 1.160   ms/op
ClientGrpc.existUser                        avgt       3   3.926 ± 2.311   ms/op
ClientGrpc.getUser                          avgt       3   4.229 ± 1.976   ms/op
ClientGrpc.listUser                         avgt       3   5.236 ± 2.825   ms/op
ClientGrpc.createUser                     sample  231716   4.142 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.707           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.463           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  251854   3.812 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.960           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.426           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          39.518           ms/op
ClientGrpc.getUser                        sample  235406   4.075 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.901           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.971           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.003           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.131           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.605           ms/op
ClientGrpc.listUser                       sample  179004   5.365 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.217           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.087           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
