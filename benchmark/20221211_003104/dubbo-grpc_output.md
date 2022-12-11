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
# Warmup Iteration   1: 4.673 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 10.122 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 10.326 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.127 ±(99.9%) 3.527 ops/ms [Average]
  (min, avg, max) = (9.940, 10.127, 10.326), stdev = 0.193
  CI (99.9%): [6.600, 13.654] (assumes normal distribution)


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
# Warmup Iteration   1: 7.361 ops/ms
# Warmup Iteration   2: 10.262 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.865 ops/ms
Iteration   3: 11.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.894 ±(99.9%) 6.572 ops/ms [Average]
  (min, avg, max) = (10.549, 10.894, 11.268), stdev = 0.360
  CI (99.9%): [4.322, 17.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.514 ops/ms
# Warmup Iteration   2: 9.764 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.116 ±(99.9%) 3.177 ops/ms [Average]
  (min, avg, max) = (9.978, 10.116, 10.311), stdev = 0.174
  CI (99.9%): [6.938, 13.293] (assumes normal distribution)


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
# Warmup Iteration   1: 5.547 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.977 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (7.861, 7.977, 8.157), stdev = 0.158
  CI (99.9%): [5.089, 10.865] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.003 ms/op
Iteration   1: 3.183 ±(99.9%) 0.010 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.183 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.174, 3.183, 3.193), stdev = 0.010
  CI (99.9%): [3.008, 3.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.004 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.034 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (2.969, 3.034, 3.098), stdev = 0.064
  CI (99.9%): [1.863, 4.204] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.189 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.271 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.221 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.189, 3.221, 3.271), stdev = 0.044
  CI (99.9%): [2.422, 4.019] (assumes normal distribution)


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
# Warmup Iteration   1: 5.488 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.011 ms/op
Iteration   1: 4.138 ±(99.9%) 0.042 ms/op
Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
Iteration   3: 4.037 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.067 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (4.026, 4.067, 4.138), stdev = 0.062
  CI (99.9%): [2.940, 5.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.203 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.940 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.085 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  12.080 ms/op
                 createUser·p0.9999: 30.298 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301100
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18694 
    [ 2.500,  5.000) = 281158 
    [ 5.000,  7.500) = 828 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.953 ms/op
     p(99.9900) =     29.054 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.945 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.129 ms/op
                 existUser·p0.9999: 16.070 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.332 ms/op
                 existUser·p0.9999: 16.247 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308763
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 920 
    [ 1.250,  2.500) = 31036 
    [ 2.500,  3.750) = 239548 
    [ 3.750,  5.000) = 36305 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.063 ms/op
     p(99.9900) =     16.013 ms/op
     p(99.9990) =     17.525 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.571 ms/op
                 getUser·p0.9999: 20.578 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.187 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.231 ms/op
                 getUser·p0.9999: 15.220 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.551 ms/op
                 getUser·p0.9999: 17.755 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307030
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21677 
    [ 2.500,  5.000) = 284335 
    [ 5.000,  7.500) = 781 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     19.779 ms/op
     p(99.9990) =     20.805 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
Iteration   1: 4.118 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.123 ms/op
                 listUser·p0.9999: 20.692 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.508 ms/op
                 listUser·p0.9999: 25.693 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.983 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.970 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235517
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2515 
    [ 2.500,  5.000) = 204486 
    [ 5.000,  7.500) = 26738 
    [ 7.500, 10.000) = 1288 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     24.984 ms/op
     p(99.9990) =     27.355 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.127 ± 3.527  ops/ms
ClientGrpc.existUser                       thrpt       3  10.894 ± 6.572  ops/ms
ClientGrpc.getUser                         thrpt       3  10.116 ± 3.177  ops/ms
ClientGrpc.listUser                        thrpt       3   7.977 ± 2.888  ops/ms
ClientGrpc.createUser                       avgt       3   3.183 ± 0.175   ms/op
ClientGrpc.existUser                        avgt       3   3.034 ± 1.171   ms/op
ClientGrpc.getUser                          avgt       3   3.221 ± 0.799   ms/op
ClientGrpc.listUser                         avgt       3   4.067 ± 1.127   ms/op
ClientGrpc.createUser                     sample  301100   3.187 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.584           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.953           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.359           ms/op
ClientGrpc.existUser                      sample  308763   3.108 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.626           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.080           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.063           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.013           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  307030   3.126 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.569           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.779           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  235517   4.075 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.981           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.984           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
