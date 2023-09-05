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
# Warmup Iteration   1: 2.260 ops/ms
# Warmup Iteration   2: 5.644 ops/ms
# Warmup Iteration   3: 7.140 ops/ms
Iteration   1: 7.334 ops/ms
Iteration   2: 7.375 ops/ms
Iteration   3: 7.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.378 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (7.334, 7.378, 7.424), stdev = 0.045
  CI (99.9%): [6.559, 8.197] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.990 ops/ms
# Warmup Iteration   2: 7.686 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.239 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (8.124, 8.239, 8.350), stdev = 0.113
  CI (99.9%): [6.182, 10.296] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 7.111 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 7.451 ops/ms
Iteration   2: 7.448 ops/ms
Iteration   3: 7.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.450 ±(99.9%) 0.033 ops/ms [Average]
  (min, avg, max) = (7.448, 7.450, 7.452), stdev = 0.002
  CI (99.9%): [7.417, 7.483] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 5.340 ops/ms
# Warmup Iteration   3: 5.645 ops/ms
Iteration   1: 5.652 ops/ms
Iteration   2: 5.854 ops/ms
Iteration   3: 5.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.726 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (5.652, 5.726, 5.854), stdev = 0.112
  CI (99.9%): [3.685, 7.766] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.569 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.011 ms/op
Iteration   1: 4.273 ±(99.9%) 0.003 ms/op
Iteration   2: 4.253 ±(99.9%) 0.003 ms/op
Iteration   3: 4.189 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.238 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (4.189, 4.238, 4.273), stdev = 0.044
  CI (99.9%): [3.437, 5.039] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.659 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.007 ms/op
Iteration   1: 4.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.861 ±(99.9%) 0.003 ms/op
Iteration   3: 3.880 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.916 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.861, 3.916, 4.009), stdev = 0.081
  CI (99.9%): [2.445, 5.387] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.004 ms/op
Iteration   1: 4.167 ±(99.9%) 0.003 ms/op
Iteration   2: 4.207 ±(99.9%) 0.003 ms/op
Iteration   3: 4.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.164 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (4.119, 4.164, 4.207), stdev = 0.044
  CI (99.9%): [3.358, 4.971] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.150 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.097 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.013 ms/op
Iteration   1: 5.446 ±(99.9%) 0.012 ms/op
Iteration   2: 5.517 ±(99.9%) 0.015 ms/op
Iteration   3: 5.552 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.505 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (5.446, 5.505, 5.552), stdev = 0.054
  CI (99.9%): [4.518, 6.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.726 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.012 ms/op
Iteration   1: 4.227 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 18.280 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 4.289 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 17.698 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.136 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 21.691 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227055
  mean =      4.227 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5958 
    [ 2.500,  5.000) = 185769 
    [ 5.000,  7.500) = 33352 
    [ 7.500, 10.000) = 1345 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     20.879 ms/op
     p(99.9990) =     22.387 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.001 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.011 ms/op
Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 15.811 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   2: 4.017 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  13.203 ms/op
                 existUser·p0.9999: 25.134 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  9.111 ms/op
                 existUser·p0.9999: 22.351 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238518
  mean =      4.024 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6942 
    [ 2.500,  5.000) = 208737 
    [ 5.000,  7.500) = 21413 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     11.746 ms/op
     p(99.9900) =     23.041 ms/op
     p(99.9990) =     25.456 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 6.518 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.013 ms/op
Iteration   1: 4.315 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  11.059 ms/op
                 getUser·p0.9999: 16.324 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 4.227 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 18.771 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 4.315 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 31.392 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224160
  mean =      4.285 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5981 
    [ 2.500,  5.000) = 181182 
    [ 5.000,  7.500) = 34875 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     29.614 ms/op
     p(99.9990) =     31.541 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 7.675 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.864 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.021 ms/op
Iteration   1: 5.550 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  18.277 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 5.525 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  17.281 ms/op
                 listUser·p0.9999: 25.523 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 5.576 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.231 ms/op
                 listUser·p0.99:   10.380 ms/op
                 listUser·p0.999:  19.112 ms/op
                 listUser·p0.9999: 22.533 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172778
  mean =      5.551 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 250 
    [ 2.500,  5.000) = 66508 
    [ 5.000,  7.500) = 90773 
    [ 7.500, 10.000) = 12873 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.929 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.378 ± 0.819  ops/ms
ClientGrpc.existUser                       thrpt       3   8.239 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3   7.450 ± 0.033  ops/ms
ClientGrpc.listUser                        thrpt       3   5.726 ± 2.041  ops/ms
ClientGrpc.createUser                       avgt       3   4.238 ± 0.801   ms/op
ClientGrpc.existUser                        avgt       3   3.916 ± 1.471   ms/op
ClientGrpc.getUser                          avgt       3   4.164 ± 0.807   ms/op
ClientGrpc.listUser                         avgt       3   5.505 ± 0.987   ms/op
ClientGrpc.createUser                     sample  227055   4.227 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.159           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.258           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.139           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.879           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.774           ms/op
ClientGrpc.existUser                      sample  238518   4.024 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.932           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.783           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.746           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.592           ms/op
ClientGrpc.getUser                        sample  224160   4.285 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.705           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.292           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.397           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.614           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.588           ms/op
ClientGrpc.listUser                       sample  172778   5.551 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.354           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.274           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.502           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
