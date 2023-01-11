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
# Warmup Iteration   1: 4.086 ops/ms
# Warmup Iteration   2: 8.360 ops/ms
# Warmup Iteration   3: 9.693 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.859 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (9.803, 9.859, 9.963), stdev = 0.090
  CI (99.9%): [8.212, 11.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.619 ops/ms
# Warmup Iteration   2: 10.034 ops/ms
# Warmup Iteration   3: 10.209 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.638 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (10.521, 10.638, 10.714), stdev = 0.103
  CI (99.9%): [8.766, 12.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.147 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.308 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 10.125 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.067 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (9.969, 10.067, 10.125), stdev = 0.086
  CI (99.9%): [8.504, 11.630] (assumes normal distribution)


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
# Warmup Iteration   1: 6.168 ops/ms
# Warmup Iteration   2: 7.531 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.221 ±(99.9%) 6.473 ops/ms [Average]
  (min, avg, max) = (7.928, 8.221, 8.616), stdev = 0.355
  CI (99.9%): [1.748, 14.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.164 ±(99.9%) 0.002 ms/op
Iteration   2: 3.216 ±(99.9%) 0.002 ms/op
Iteration   3: 3.149 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.149, 3.176, 3.216), stdev = 0.035
  CI (99.9%): [2.538, 3.815] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 3.024 ±(99.9%) 0.004 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.988 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (2.946, 2.988, 3.024), stdev = 0.039
  CI (99.9%): [2.271, 3.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.002 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.112, 3.142, 3.181), stdev = 0.036
  CI (99.9%): [2.493, 3.791] (assumes normal distribution)


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.008 ms/op
Iteration   1: 4.005 ±(99.9%) 0.020 ms/op
Iteration   2: 4.006 ±(99.9%) 0.008 ms/op
Iteration   3: 4.003 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.005 ±(99.9%) 0.027 ms/op [Average]
  (min, avg, max) = (4.003, 4.005, 4.006), stdev = 0.001
  CI (99.9%): [3.978, 4.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.732 ms/op
                 createUser·p0.9999: 12.609 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  11.291 ms/op
                 createUser·p0.9999: 14.158 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  12.085 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300846
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26129 
    [ 2.500,  5.000) = 272990 
    [ 5.000,  7.500) = 1147 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     10.493 ms/op
     p(99.9900) =     25.643 ms/op
     p(99.9990) =     27.420 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.818 ms/op
                 existUser·p0.9999: 12.683 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.834 ms/op
                 existUser·p0.9999: 20.138 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.009 ms/op
                 existUser·p0.9999: 18.694 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318182
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40687 
    [ 2.500,  5.000) = 276811 
    [ 5.000,  7.500) = 532 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      5.898 ms/op
     p(99.9900) =     19.339 ms/op
     p(99.9990) =     20.277 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 13.988 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.482 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.218 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.063 ms/op
                 getUser·p0.9999: 18.780 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302987
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22463 
    [ 2.500,  5.000) = 279097 
    [ 5.000,  7.500) = 1091 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     23.911 ms/op
     p(99.9990) =     24.968 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 5.626 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.014 ms/op
Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  20.081 ms/op
                 listUser·p0.9999: 22.739 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  19.107 ms/op
                 listUser·p0.9999: 23.493 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   3.770 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242041
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2408 
    [ 2.500,  5.000) = 215333 
    [ 5.000,  7.500) = 22989 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.404 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.859 ± 1.647  ops/ms
ClientGrpc.existUser                       thrpt       3  10.638 ± 1.872  ops/ms
ClientGrpc.getUser                         thrpt       3  10.067 ± 1.563  ops/ms
ClientGrpc.listUser                        thrpt       3   8.221 ± 6.473  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.638   ms/op
ClientGrpc.existUser                        avgt       3   2.988 ± 0.717   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.649   ms/op
ClientGrpc.listUser                         avgt       3   4.005 ± 0.027   ms/op
ClientGrpc.createUser                     sample  300846   3.188 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.493           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.643           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.886           ms/op
ClientGrpc.existUser                      sample  318182   3.016 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.795           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.898           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.339           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.578           ms/op
ClientGrpc.getUser                        sample  302987   3.167 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.758           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.911           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.068           ms/op
ClientGrpc.listUser                       sample  242041   3.964 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.632           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.462           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.478           ms/op
