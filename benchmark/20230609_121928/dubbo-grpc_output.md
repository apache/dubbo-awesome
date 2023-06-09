# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 10.068 ops/ms
Iteration   1: 10.460 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.402 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (10.355, 10.402, 10.460), stdev = 0.053
  CI (99.9%): [9.431, 11.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.581 ops/ms
# Warmup Iteration   2: 10.661 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 11.290 ops/ms
Iteration   2: 11.117 ops/ms
Iteration   3: 11.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.182 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (11.117, 11.182, 11.290), stdev = 0.094
  CI (99.9%): [9.471, 12.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.933 ops/ms
# Warmup Iteration   2: 9.864 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.554 ±(99.9%) 1.221 ops/ms [Average]
  (min, avg, max) = (10.479, 10.554, 10.608), stdev = 0.067
  CI (99.9%): [9.333, 11.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.380 ops/ms
# Warmup Iteration   2: 7.389 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 8.132 ops/ms
Iteration   3: 7.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (7.914, 8.010, 8.132), stdev = 0.111
  CI (99.9%): [5.984, 10.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.451 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.014, 3.059, 3.100), stdev = 0.043
  CI (99.9%): [2.276, 3.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.002 ms/op
Iteration   1: 2.906 ±(99.9%) 0.003 ms/op
Iteration   2: 2.906 ±(99.9%) 0.003 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.906, 2.917, 2.937), stdev = 0.018
  CI (99.9%): [2.596, 3.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.166 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.020, 3.043, 3.065), stdev = 0.023
  CI (99.9%): [2.629, 3.457] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.809 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.013 ms/op
Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
Iteration   2: 4.035 ±(99.9%) 0.009 ms/op
Iteration   3: 4.030 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.012 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.971, 4.012, 4.035), stdev = 0.036
  CI (99.9%): [3.362, 4.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 19.182 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  7.735 ms/op
                 createUser·p0.9999: 15.588 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.504 ms/op
                 createUser·p0.9999: 23.884 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315751
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15281 
    [ 2.500,  5.000) = 299161 
    [ 5.000,  7.500) = 987 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.533 ms/op
     p(99.9900) =     22.755 ms/op
     p(99.9990) =     24.298 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.906 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 12.697 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   2: 2.844 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.509 ms/op
                 existUser·p0.9999: 13.005 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.813 ms/op
                 existUser·p0.9999: 28.566 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330740
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41297 
    [ 2.500,  5.000) = 288485 
    [ 5.000,  7.500) = 744 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     17.135 ms/op
     p(99.9990) =     29.078 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.752 ms/op
                 getUser·p0.9999: 18.925 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.787 ms/op
                 getUser·p0.9999: 14.518 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.806 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.956 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314017
  mean =      3.058 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 15802 
    [ 2.500,  3.750) = 281977 
    [ 3.750,  5.000) = 14434 
    [ 5.000,  6.250) = 933 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     19.324 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.191 ms/op
                 listUser·p0.9999: 23.201 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.472 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.832 ms/op
                 listUser·p0.9999: 26.512 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240492
  mean =      3.989 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1751 
    [ 2.500,  5.000) = 217936 
    [ 5.000,  7.500) = 19481 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.443 ms/op
     p(99.9900) =     24.442 ms/op
     p(99.9990) =     27.577 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.402 ± 0.971  ops/ms
ClientGrpc.existUser                       thrpt       3  11.182 ± 1.711  ops/ms
ClientGrpc.getUser                         thrpt       3  10.554 ± 1.221  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 2.026  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.784   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.321   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   4.012 ± 0.650   ms/op
ClientGrpc.createUser                     sample  315751   3.041 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.780           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.533           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.755           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.445           ms/op
ClientGrpc.existUser                      sample  330740   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.135           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.229           ms/op
ClientGrpc.getUser                        sample  314017   3.058 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.086           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.973           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  240492   3.989 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.443           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.442           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623           ms/op
