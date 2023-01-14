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
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.527 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (10.435, 10.527, 10.604), stdev = 0.085
  CI (99.9%): [8.968, 12.086] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ops/ms
# Warmup Iteration   2: 10.694 ops/ms
# Warmup Iteration   3: 10.747 ops/ms
Iteration   1: 10.830 ops/ms
Iteration   2: 11.068 ops/ms
Iteration   3: 11.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.031 ±(99.9%) 3.380 ops/ms [Average]
  (min, avg, max) = (10.830, 11.031, 11.195), stdev = 0.185
  CI (99.9%): [7.651, 14.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.518 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (10.385, 10.518, 10.611), stdev = 0.118
  CI (99.9%): [8.363, 12.674] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.425 ops/ms
# Warmup Iteration   2: 7.571 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.067 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (7.976, 8.067, 8.145), stdev = 0.085
  CI (99.9%): [6.511, 9.622] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.114 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.107, 3.114, 3.121), stdev = 0.007
  CI (99.9%): [2.984, 3.243] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.003 ms/op
Iteration   1: 2.949 ±(99.9%) 0.007 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.929, 2.944, 2.956), stdev = 0.014
  CI (99.9%): [2.687, 3.202] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
Iteration   3: 3.133 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.072 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.030, 3.072, 3.133), stdev = 0.054
  CI (99.9%): [2.090, 4.054] (assumes normal distribution)


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
Iteration   1: 3.921 ±(99.9%) 0.008 ms/op
Iteration   2: 3.803 ±(99.9%) 0.024 ms/op
Iteration   3: 3.916 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.880 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.803, 3.880, 3.921), stdev = 0.067
  CI (99.9%): [2.656, 5.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.840 ms/op
                 createUser·p0.9999: 13.365 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.068 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  12.887 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312787
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27331 
    [ 2.500,  5.000) = 284233 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     17.948 ms/op
     p(99.9990) =     20.542 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 10.867 ms/op
                 existUser·p1.00:   11.600 ms/op

Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  7.411 ms/op
                 existUser·p0.9999: 12.893 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.920 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 14.877 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328741
  mean =      2.922 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5089 
    [ 1.250,  2.500) = 42138 
    [ 2.500,  3.750) = 266173 
    [ 3.750,  5.000) = 14314 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      7.314 ms/op
     p(99.9900) =     14.453 ms/op
     p(99.9990) =     15.092 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.209 ms/op
                 getUser·p0.9999: 18.011 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.494 ms/op
                 getUser·p0.9999: 15.786 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.880 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.483 ms/op
                 getUser·p0.9999: 20.626 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314092
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28332 
    [ 2.500,  5.000) = 285003 
    [ 5.000,  7.500) = 528 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.382 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     20.925 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 5.305 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.569 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.075 ms/op
                 listUser·p0.999:  13.537 ms/op
                 listUser·p0.9999: 14.801 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.736 ms/op
                 listUser·p0.9999: 30.217 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239086
  mean =      4.015 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4046 
    [ 2.500,  5.000) = 203885 
    [ 5.000,  7.500) = 29973 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     30.396 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.527 ± 1.559  ops/ms
ClientGrpc.existUser                       thrpt       3  11.031 ± 3.380  ops/ms
ClientGrpc.getUser                         thrpt       3  10.518 ± 2.156  ops/ms
ClientGrpc.listUser                        thrpt       3   8.067 ± 1.556  ops/ms
ClientGrpc.createUser                       avgt       3   3.114 ± 0.129   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.257   ms/op
ClientGrpc.getUser                          avgt       3   3.072 ± 0.982   ms/op
ClientGrpc.listUser                         avgt       3   3.880 ± 1.224   ms/op
ClientGrpc.createUser                     sample  312787   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.526           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.948           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  328741   2.922 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.585           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.314           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.453           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.122           ms/op
ClientGrpc.getUser                        sample  314092   3.055 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.382           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.809           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  239086   4.015 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.866           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.697           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.231           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
