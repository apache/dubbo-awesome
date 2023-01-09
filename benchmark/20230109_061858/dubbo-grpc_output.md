# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.861 ops/ms
# Warmup Iteration   2: 9.645 ops/ms
# Warmup Iteration   3: 10.796 ops/ms
Iteration   1: 10.876 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.650 ±(99.9%) 3.625 ops/ms [Average]
  (min, avg, max) = (10.504, 10.650, 10.876), stdev = 0.199
  CI (99.9%): [7.024, 14.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.156 ops/ms
# Warmup Iteration   2: 10.753 ops/ms
# Warmup Iteration   3: 11.213 ops/ms
Iteration   1: 11.176 ops/ms
Iteration   2: 10.975 ops/ms
Iteration   3: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.084 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (10.975, 11.084, 11.176), stdev = 0.101
  CI (99.9%): [9.235, 12.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.619 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.686 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.645 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (10.509, 10.645, 10.763), stdev = 0.128
  CI (99.9%): [8.307, 12.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.995 ops/ms
# Warmup Iteration   2: 7.890 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.207 ±(99.9%) 4.225 ops/ms [Average]
  (min, avg, max) = (7.982, 8.207, 8.445), stdev = 0.232
  CI (99.9%): [3.982, 12.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.836 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.066 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.035, 3.066, 3.086), stdev = 0.027
  CI (99.9%): [2.565, 3.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.965, 2.967, 2.970), stdev = 0.003
  CI (99.9%): [2.914, 3.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (2.997, 3.030, 3.057), stdev = 0.030
  CI (99.9%): [2.474, 3.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.030 ms/op
Iteration   1: 4.015 ±(99.9%) 0.042 ms/op
Iteration   2: 3.925 ±(99.9%) 0.019 ms/op
Iteration   3: 3.809 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.916 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (3.809, 3.916, 4.015), stdev = 0.103
  CI (99.9%): [2.033, 5.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.725 ms/op
                 createUser·p0.9999: 11.780 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.872 ms/op
                 createUser·p0.9999: 12.840 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  11.033 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303808
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26370 
    [ 2.500,  5.000) = 276055 
    [ 5.000,  7.500) = 949 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.135 ms/op
     p(99.9900) =     18.600 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 11.456 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.036 ms/op
                 existUser·p0.9999: 12.756 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 16.336 ms/op
                 existUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325122
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2665 
    [ 1.250,  2.500) = 49199 
    [ 2.500,  3.750) = 253032 
    [ 3.750,  5.000) = 19478 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     14.734 ms/op
     p(99.9990) =     16.572 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.981 ms/op
                 getUser·p0.9999: 11.223 ms/op
                 getUser·p1.00:   11.452 ms/op

Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  7.259 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.873 ms/op
                 getUser·p0.9999: 14.390 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318750
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2184 
    [ 1.250,  2.500) = 26695 
    [ 2.500,  3.750) = 272108 
    [ 3.750,  5.000) = 16886 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     14.060 ms/op
     p(99.9990) =     14.890 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.957 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
Iteration   1: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  12.631 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 26.112 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 3.885 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.629 ms/op
                 listUser·p0.9999: 20.866 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244070
  mean =      3.931 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5029 
    [ 2.500,  5.000) = 213811 
    [ 5.000,  7.500) = 24214 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     25.251 ms/op
     p(99.9990) =     26.448 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.650 ± 3.625  ops/ms
ClientGrpc.existUser                       thrpt       3  11.084 ± 1.849  ops/ms
ClientGrpc.getUser                         thrpt       3  10.645 ± 2.338  ops/ms
ClientGrpc.listUser                        thrpt       3   8.207 ± 4.225  ops/ms
ClientGrpc.createUser                       avgt       3   3.066 ± 0.501   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 0.052   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.556   ms/op
ClientGrpc.listUser                         avgt       3   3.916 ± 1.883   ms/op
ClientGrpc.createUser                     sample  303808   3.159 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.135           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.600           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.266           ms/op
ClientGrpc.existUser                      sample  325122   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.734           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.679           ms/op
ClientGrpc.getUser                        sample  318750   3.011 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.060           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.926           ms/op
ClientGrpc.listUser                       sample  244070   3.931 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.902           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.189           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.251           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
