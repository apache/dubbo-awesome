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
# Warmup Iteration   1: 4.143 ops/ms
# Warmup Iteration   2: 8.978 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.174 ±(99.9%) 3.481 ops/ms [Average]
  (min, avg, max) = (9.976, 10.174, 10.356), stdev = 0.191
  CI (99.9%): [6.694, 13.655] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.288 ops/ms
# Warmup Iteration   2: 10.318 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.825 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.670 ±(99.9%) 2.706 ops/ms [Average]
  (min, avg, max) = (10.530, 10.670, 10.825), stdev = 0.148
  CI (99.9%): [7.964, 13.376] (assumes normal distribution)


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
# Warmup Iteration   1: 6.757 ops/ms
# Warmup Iteration   2: 9.786 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 9.901 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 10.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.020 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (9.901, 10.020, 10.085), stdev = 0.103
  CI (99.9%): [8.138, 11.902] (assumes normal distribution)


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
# Warmup Iteration   1: 4.988 ops/ms
# Warmup Iteration   2: 7.619 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 7.705 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.924 ±(99.9%) 4.176 ops/ms [Average]
  (min, avg, max) = (7.705, 7.924, 8.162), stdev = 0.229
  CI (99.9%): [3.748, 12.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.012 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.160, 3.170, 3.183), stdev = 0.011
  CI (99.9%): [2.961, 3.379] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.025 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.012, 3.025, 3.040), stdev = 0.014
  CI (99.9%): [2.768, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.002 ms/op
Iteration   1: 3.206 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.188 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.157, 3.188, 3.206), stdev = 0.027
  CI (99.9%): [2.695, 3.681] (assumes normal distribution)


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
# Warmup Iteration   1: 5.046 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
Iteration   2: 3.953 ±(99.9%) 0.016 ms/op
Iteration   3: 4.091 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.057 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (3.953, 4.057, 4.127), stdev = 0.092
  CI (99.9%): [2.375, 5.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.943 ms/op
                 createUser·p0.9999: 13.433 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 3.249 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  12.970 ms/op
                 createUser·p0.9999: 23.047 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  12.743 ms/op
                 createUser·p0.9999: 19.625 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300349
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24910 
    [ 2.500,  5.000) = 272521 
    [ 5.000,  7.500) = 2243 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     12.331 ms/op
     p(99.9900) =     22.116 ms/op
     p(99.9990) =     23.494 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  7.991 ms/op
                 existUser·p0.9999: 13.315 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  8.195 ms/op
                 existUser·p0.9999: 16.900 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  7.651 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308529
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1104 
    [ 1.250,  2.500) = 36206 
    [ 2.500,  3.750) = 232263 
    [ 3.750,  5.000) = 36426 
    [ 5.000,  6.250) = 1634 
    [ 6.250,  7.500) = 453 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     18.869 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.121 ms/op
                 getUser·p0.9999: 13.155 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 14.694 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.112 ms/op
                 getUser·p0.9999: 20.673 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302401
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24556 
    [ 2.500,  5.000) = 275506 
    [ 5.000,  7.500) = 1853 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.546 ms/op
     p(99.9900) =     19.686 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 5.608 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.012 ms/op
Iteration   1: 4.120 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.980 ms/op
                 listUser·p0.9999: 18.554 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 23.108 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234013
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2617 
    [ 2.500,  5.000) = 202516 
    [ 5.000,  7.500) = 27009 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     23.516 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.174 ± 3.481  ops/ms
ClientGrpc.existUser                       thrpt       3  10.670 ± 2.706  ops/ms
ClientGrpc.getUser                         thrpt       3  10.020 ± 1.882  ops/ms
ClientGrpc.listUser                        thrpt       3   7.924 ± 4.176  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.209   ms/op
ClientGrpc.existUser                        avgt       3   3.025 ± 0.257   ms/op
ClientGrpc.getUser                          avgt       3   3.188 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   4.057 ± 1.682   ms/op
ClientGrpc.createUser                     sample  300349   3.196 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.956           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.331           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.116           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  308529   3.110 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.743           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.080           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.825           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.269           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  302401   3.172 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.812           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.546           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.686           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  234013   4.102 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.040           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
