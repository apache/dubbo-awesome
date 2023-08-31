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
# Warmup Iteration   1: 3.951 ops/ms
# Warmup Iteration   2: 9.125 ops/ms
# Warmup Iteration   3: 9.798 ops/ms
Iteration   1: 10.383 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 0.824 ops/ms [Average]
  (min, avg, max) = (10.383, 10.435, 10.466), stdev = 0.045
  CI (99.9%): [9.611, 11.258] (assumes normal distribution)


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
# Warmup Iteration   1: 7.077 ops/ms
# Warmup Iteration   2: 10.502 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 11.132 ops/ms
Iteration   2: 10.709 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.864 ±(99.9%) 4.253 ops/ms [Average]
  (min, avg, max) = (10.709, 10.864, 11.132), stdev = 0.233
  CI (99.9%): [6.612, 15.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.276 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.318 ±(99.9%) 2.109 ops/ms [Average]
  (min, avg, max) = (10.229, 10.318, 10.449), stdev = 0.116
  CI (99.9%): [8.209, 12.427] (assumes normal distribution)


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
# Warmup Iteration   1: 5.254 ops/ms
# Warmup Iteration   2: 7.524 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 7.704 ops/ms
Iteration   3: 7.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.748 ±(99.9%) 2.168 ops/ms [Average]
  (min, avg, max) = (7.657, 7.748, 7.882), stdev = 0.119
  CI (99.9%): [5.580, 9.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.099, 3.116, 3.133), stdev = 0.017
  CI (99.9%): [2.811, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.002 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (2.923, 2.944, 2.983), stdev = 0.034
  CI (99.9%): [2.323, 3.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.042, 3.069, 3.097), stdev = 0.028
  CI (99.9%): [2.563, 3.574] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.430 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.032 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
Iteration   2: 4.119 ±(99.9%) 0.011 ms/op
Iteration   3: 3.963 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (3.963, 4.054, 4.119), stdev = 0.081
  CI (99.9%): [2.581, 5.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  7.911 ms/op
                 createUser·p0.9999: 17.864 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 21.817 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307477
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17782 
    [ 2.500,  5.000) = 287258 
    [ 5.000,  7.500) = 1963 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.179 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.464 ms/op
                 existUser·p0.9999: 15.390 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.070 ms/op
                 existUser·p0.9999: 14.160 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  10.388 ms/op
                 existUser·p0.9999: 27.109 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324443
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30710 
    [ 2.500,  5.000) = 291711 
    [ 5.000,  7.500) = 1666 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.759 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     27.353 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.699 ms/op
                 getUser·p0.9999: 13.617 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.769 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 13.993 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  7.741 ms/op
                 getUser·p0.9999: 14.919 ms/op
                 getUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310451
  mean =      3.090 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 238 
    [ 1.250,  2.500) = 14002 
    [ 2.500,  3.750) = 276964 
    [ 3.750,  5.000) = 16803 
    [ 5.000,  6.250) = 1297 
    [ 6.250,  7.500) = 633 
    [ 7.500,  8.750) = 276 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      8.115 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     15.430 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 6.055 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.011 ms/op
Iteration   1: 4.149 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  13.742 ms/op
                 listUser·p0.9999: 20.260 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.580 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 18.553 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.326 ms/op
                 listUser·p0.9999: 31.036 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233758
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2193 
    [ 2.500,  5.000) = 203155 
    [ 5.000,  7.500) = 26633 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     15.298 ms/op
     p(99.9900) =     30.396 ms/op
     p(99.9990) =     31.162 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 0.824  ops/ms
ClientGrpc.existUser                       thrpt       3  10.864 ± 4.253  ops/ms
ClientGrpc.getUser                         thrpt       3  10.318 ± 2.109  ops/ms
ClientGrpc.listUser                        thrpt       3   7.748 ± 2.168  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 0.305   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.621   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 1.473   ms/op
ClientGrpc.createUser                     sample  307477   3.122 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.591           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.939           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  324443   2.960 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.759           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.706           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  310451   3.090 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.115           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.500           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.203           ms/op
ClientGrpc.listUser                       sample  233758   4.109 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.580           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.298           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.396           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.195           ms/op
