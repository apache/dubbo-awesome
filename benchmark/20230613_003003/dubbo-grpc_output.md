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
# Warmup Iteration   1: 4.694 ops/ms
# Warmup Iteration   2: 8.792 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.445 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (10.393, 10.445, 10.526), stdev = 0.071
  CI (99.9%): [9.146, 11.744] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 11.079 ops/ms
Iteration   1: 11.195 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.006 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (10.903, 11.006, 11.195), stdev = 0.164
  CI (99.9%): [8.020, 13.993] (assumes normal distribution)


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
# Warmup Iteration   1: 7.074 ops/ms
# Warmup Iteration   2: 10.100 ops/ms
# Warmup Iteration   3: 10.318 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.397 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (10.315, 10.397, 10.443), stdev = 0.071
  CI (99.9%): [9.101, 11.693] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.089 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 8.023 ops/ms
Iteration   3: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.969 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (7.915, 7.969, 8.023), stdev = 0.054
  CI (99.9%): [6.978, 8.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.002 ms/op
Iteration   1: 3.142 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.164 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.142, 3.164, 3.188), stdev = 0.023
  CI (99.9%): [2.740, 3.589] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.873 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (2.873, 2.942, 2.977), stdev = 0.060
  CI (99.9%): [1.854, 4.030] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.114 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.041, 3.086, 3.114), stdev = 0.039
  CI (99.9%): [2.374, 3.797] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.479 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.010 ms/op
Iteration   1: 3.982 ±(99.9%) 0.008 ms/op
Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
Iteration   3: 3.908 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.908, 3.968, 4.013), stdev = 0.054
  CI (99.9%): [2.980, 4.956] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.262 ms/op
                 createUser·p0.9999: 13.493 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.232 ms/op
                 createUser·p0.9999: 17.094 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  7.944 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312431
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1683 
    [ 1.250,  2.500) = 18321 
    [ 2.500,  3.750) = 269926 
    [ 3.750,  5.000) = 19684 
    [ 5.000,  6.250) = 1824 
    [ 6.250,  7.500) = 535 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 67 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      8.098 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.934 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  7.874 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 23.177 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323449
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34979 
    [ 2.500,  5.000) = 285155 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 227 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =      8.856 ms/op
     p(99.9900) =     21.253 ms/op
     p(99.9990) =     23.497 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.274 ms/op
                 getUser·p0.9999: 15.826 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  8.825 ms/op
                 getUser·p0.9999: 14.467 ms/op
                 getUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311384
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1308 
    [ 1.250,  2.500) = 18921 
    [ 2.500,  3.750) = 269425 
    [ 3.750,  5.000) = 18248 
    [ 5.000,  6.250) = 2279 
    [ 6.250,  7.500) = 794 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     16.630 ms/op
     p(99.9990) =     17.622 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.011 ms/op
Iteration   1: 3.962 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.013 ms/op
                 listUser·p0.9999: 14.956 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   2: 3.852 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 19.061 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.029 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.303 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 27.564 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243291
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3517 
    [ 2.500,  5.000) = 215329 
    [ 5.000,  7.500) = 22579 
    [ 7.500, 10.000) = 1269 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 278 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.593 ms/op
     p(99.9900) =     26.957 ms/op
     p(99.9990) =     27.923 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.445 ± 1.299  ops/ms
ClientGrpc.existUser                       thrpt       3  11.006 ± 2.987  ops/ms
ClientGrpc.getUser                         thrpt       3  10.397 ± 1.296  ops/ms
ClientGrpc.listUser                        thrpt       3   7.969 ± 0.992  ops/ms
ClientGrpc.createUser                       avgt       3   3.164 ± 0.424   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 1.088   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.711   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 0.988   ms/op
ClientGrpc.createUser                     sample  312431   3.073 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.450           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.098           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.302           ms/op
ClientGrpc.existUser                      sample  323449   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.543           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.856           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.253           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.871           ms/op
ClientGrpc.getUser                        sample  311384   3.083 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.630           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.760           ms/op
ClientGrpc.listUser                       sample  243291   3.946 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.766           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.593           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.957           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
