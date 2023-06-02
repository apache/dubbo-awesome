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
# Warmup Iteration   1: 3.602 ops/ms
# Warmup Iteration   2: 8.134 ops/ms
# Warmup Iteration   3: 9.501 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.041 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (9.915, 10.041, 10.133), stdev = 0.113
  CI (99.9%): [7.984, 12.098] (assumes normal distribution)


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
# Warmup Iteration   1: 7.908 ops/ms
# Warmup Iteration   2: 10.654 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.114 ±(99.9%) 2.665 ops/ms [Average]
  (min, avg, max) = (9.953, 10.114, 10.239), stdev = 0.146
  CI (99.9%): [7.449, 12.779] (assumes normal distribution)


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
# Warmup Iteration   1: 6.755 ops/ms
# Warmup Iteration   2: 9.862 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.274 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.456 ±(99.9%) 3.059 ops/ms [Average]
  (min, avg, max) = (10.274, 10.456, 10.603), stdev = 0.168
  CI (99.9%): [7.397, 13.516] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.495 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 7.734 ops/ms
Iteration   2: 7.449 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.603 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (7.449, 7.603, 7.734), stdev = 0.144
  CI (99.9%): [4.977, 10.230] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.005 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.095 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.067, 3.095, 3.115), stdev = 0.025
  CI (99.9%): [2.640, 3.550] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.926 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.017 ±(99.9%) 1.999 ms/op [Average]
  (min, avg, max) = (2.926, 3.017, 3.138), stdev = 0.110
  CI (99.9%): [1.017, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 3.228 ±(99.9%) 0.003 ms/op
Iteration   3: 3.337 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.196 ±(99.9%) 2.930 ms/op [Average]
  (min, avg, max) = (3.021, 3.196, 3.337), stdev = 0.161
  CI (99.9%): [0.265, 6.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.022 ms/op
Iteration   1: 4.046 ±(99.9%) 0.013 ms/op
Iteration   2: 4.402 ±(99.9%) 0.006 ms/op
Iteration   3: 4.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.331 ±(99.9%) 4.699 ms/op [Average]
  (min, avg, max) = (4.046, 4.331, 4.546), stdev = 0.258
  CI (99.9%): [≈ 0, 9.030] (assumes normal distribution)


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
# Warmup Iteration   1: 5.336 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.007 ms/op
Iteration   1: 3.301 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  8.604 ms/op
                 createUser·p0.9999: 15.978 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  6.936 ms/op
                 createUser·p0.9999: 21.780 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.548 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302517
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20481 
    [ 2.500,  5.000) = 280006 
    [ 5.000,  7.500) = 1747 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      7.335 ms/op
     p(99.9900) =     21.651 ms/op
     p(99.9990) =     24.441 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.151 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  7.004 ms/op
                 existUser·p0.9999: 12.286 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.866 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.927 ms/op
                 existUser·p0.9999: 19.285 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317108
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27345 
    [ 2.500,  5.000) = 287777 
    [ 5.000,  7.500) = 1680 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     19.983 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.005 ms/op
Iteration   1: 3.384 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 13.534 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 14.928 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.478 ms/op
                 getUser·p0.9999: 15.525 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297141
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 739 
    [ 1.250,  2.500) = 12311 
    [ 2.500,  3.750) = 245918 
    [ 3.750,  5.000) = 35431 
    [ 5.000,  6.250) = 1983 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =      8.485 ms/op
     p(99.9900) =     15.111 ms/op
     p(99.9990) =     15.746 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 5.330 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.011 ms/op
Iteration   1: 4.176 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.600 ms/op
                 listUser·p0.9999: 17.247 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.134 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.407 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 24.879 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 30.191 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232138
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2416 
    [ 2.500,  5.000) = 201428 
    [ 5.000,  7.500) = 26354 
    [ 7.500, 10.000) = 1405 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.209 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     30.498 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.041 ± 2.057  ops/ms
ClientGrpc.existUser                       thrpt       3  10.114 ± 2.665  ops/ms
ClientGrpc.getUser                         thrpt       3  10.456 ± 3.059  ops/ms
ClientGrpc.listUser                        thrpt       3   7.603 ± 2.627  ops/ms
ClientGrpc.createUser                       avgt       3   3.095 ± 0.455   ms/op
ClientGrpc.existUser                        avgt       3   3.017 ± 1.999   ms/op
ClientGrpc.getUser                          avgt       3   3.196 ± 2.930   ms/op
ClientGrpc.listUser                         avgt       3   4.331 ± 4.699   ms/op
ClientGrpc.createUser                     sample  302517   3.172 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.335           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.651           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  317108   3.026 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.695           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  297141   3.229 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.183           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.153           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.485           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.111           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.860           ms/op
ClientGrpc.listUser                       sample  232138   4.134 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.209           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.164           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.736           ms/op
