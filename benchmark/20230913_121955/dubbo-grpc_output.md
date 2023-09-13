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
# Warmup Iteration   1: 4.313 ops/ms
# Warmup Iteration   2: 8.930 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 10.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.181 ±(99.9%) 2.399 ops/ms [Average]
  (min, avg, max) = (10.090, 10.181, 10.332), stdev = 0.131
  CI (99.9%): [7.783, 12.580] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.027 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 11.089 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 10.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.927 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (10.842, 10.927, 11.089), stdev = 0.140
  CI (99.9%): [8.365, 13.488] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ops/ms
# Warmup Iteration   2: 10.047 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.323 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.258 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (10.198, 10.258, 10.323), stdev = 0.063
  CI (99.9%): [9.114, 11.402] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.551 ops/ms
# Warmup Iteration   2: 8.023 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.368 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.315 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (8.268, 8.315, 8.368), stdev = 0.050
  CI (99.9%): [7.395, 9.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.475 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.011 ms/op
Iteration   2: 3.155 ±(99.9%) 0.014 ms/op
Iteration   3: 3.078 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.078, 3.133, 3.166), stdev = 0.048
  CI (99.9%): [2.261, 4.006] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.953 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.969 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.953, 2.969, 2.983), stdev = 0.015
  CI (99.9%): [2.698, 3.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.003 ms/op
Iteration   1: 3.123 ±(99.9%) 0.001 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.035, 3.081, 3.123), stdev = 0.044
  CI (99.9%): [2.272, 3.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.019 ms/op
Iteration   1: 3.834 ±(99.9%) 0.013 ms/op
Iteration   2: 3.727 ±(99.9%) 0.017 ms/op
Iteration   3: 3.797 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.786 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.727, 3.786, 3.834), stdev = 0.054
  CI (99.9%): [2.794, 4.778] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.902 ms/op
                 createUser·p0.9999: 12.982 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.206 ms/op
                 createUser·p0.999:  6.906 ms/op
                 createUser·p0.9999: 13.929 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.203 ms/op
                 createUser·p0.9999: 17.358 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310259
  mean =      3.092 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 223 
    [ 1.250,  2.500) = 12458 
    [ 2.500,  3.750) = 279968 
    [ 3.750,  5.000) = 15922 
    [ 5.000,  6.250) = 963 
    [ 6.250,  7.500) = 361 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     15.973 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.174 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.119 ms/op
                 existUser·p0.9999: 12.918 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  9.610 ms/op
                 existUser·p0.9999: 16.174 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.689 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323814
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 679 
    [ 1.250,  2.500) = 29995 
    [ 2.500,  3.750) = 283616 
    [ 3.750,  5.000) = 7879 
    [ 5.000,  6.250) = 804 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.201 ms/op
                 getUser·p0.999:  6.827 ms/op
                 getUser·p0.9999: 13.508 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.921 ms/op
                 getUser·p0.9999: 13.521 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 14.262 ms/op
                 getUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310114
  mean =      3.097 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 9709 
    [ 2.500,  3.750) = 283090 
    [ 3.750,  5.000) = 15382 
    [ 5.000,  6.250) = 1030 
    [ 6.250,  7.500) = 423 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.488 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 5.530 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.010 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  16.458 ms/op
                 listUser·p0.9999: 18.539 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 3.878 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   6.590 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.101 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.867 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  14.275 ms/op
                 listUser·p0.9999: 16.576 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247681
  mean =      3.876 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 2454 
    [ 2.500,  3.750) = 112966 
    [ 3.750,  5.000) = 118471 
    [ 5.000,  6.250) = 9466 
    [ 6.250,  7.500) = 3331 
    [ 7.500,  8.750) = 333 
    [ 8.750, 10.000) = 154 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 100 
    [16.250, 17.500) = 84 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.521 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     19.452 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.181 ± 2.399  ops/ms
ClientGrpc.existUser                       thrpt       3  10.927 ± 2.561  ops/ms
ClientGrpc.getUser                         thrpt       3  10.258 ± 1.144  ops/ms
ClientGrpc.listUser                        thrpt       3   8.315 ± 0.920  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.873   ms/op
ClientGrpc.existUser                        avgt       3   2.969 ± 0.271   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.809   ms/op
ClientGrpc.listUser                         avgt       3   3.786 ± 0.992   ms/op
ClientGrpc.createUser                     sample  310259   3.092 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.871           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.823           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.433           ms/op
ClientGrpc.existUser                      sample  323814   2.964 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.536           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  310114   3.097 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.678           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.812           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.172           ms/op
ClientGrpc.listUser                       sample  247681   3.876 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.842           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.521           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.530           ms/op
