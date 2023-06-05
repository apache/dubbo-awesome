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
# Warmup Iteration   1: 4.142 ops/ms
# Warmup Iteration   2: 8.855 ops/ms
# Warmup Iteration   3: 9.907 ops/ms
Iteration   1: 10.139 ops/ms
Iteration   2: 10.513 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.383 ±(99.9%) 3.856 ops/ms [Average]
  (min, avg, max) = (10.139, 10.383, 10.513), stdev = 0.211
  CI (99.9%): [6.528, 14.239] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.881 ops/ms
Iteration   2: 11.030 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.916 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (10.836, 10.916, 11.030), stdev = 0.101
  CI (99.9%): [9.067, 12.764] (assumes normal distribution)


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
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 10.115 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.488 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (10.410, 10.488, 10.572), stdev = 0.081
  CI (99.9%): [9.005, 11.970] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 8.121 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.105 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (8.001, 8.105, 8.194), stdev = 0.098
  CI (99.9%): [6.322, 9.889] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (2.977, 3.030, 3.071), stdev = 0.048
  CI (99.9%): [2.155, 3.904] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.002 ms/op
Iteration   1: 2.893 ±(99.9%) 0.003 ms/op
Iteration   2: 2.863 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.863, 2.891, 2.918), stdev = 0.028
  CI (99.9%): [2.390, 3.393] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.004 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.004 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (3.024, 3.046, 3.057), stdev = 0.019
  CI (99.9%): [2.707, 3.385] (assumes normal distribution)


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.012 ms/op
Iteration   1: 3.927 ±(99.9%) 0.007 ms/op
Iteration   2: 3.905 ±(99.9%) 0.022 ms/op
Iteration   3: 3.927 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.905, 3.920, 3.927), stdev = 0.012
  CI (99.9%): [3.692, 4.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.415 ms/op
                 createUser·p0.9999: 24.041 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.350 ms/op
                 createUser·p0.9999: 20.125 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 23.254 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310673
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17791 
    [ 2.500,  5.000) = 291011 
    [ 5.000,  7.500) = 1427 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.129 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.402 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.005 ms/op
Iteration   1: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.379 ms/op
                 existUser·p0.9999: 18.542 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 23.098 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 2.959 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  7.346 ms/op
                 existUser·p0.9999: 28.612 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330629
  mean =      2.905 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39274 
    [ 2.500,  5.000) = 290253 
    [ 5.000,  7.500) = 740 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.936 ms/op
     p(99.9900) =     27.621 ms/op
     p(99.9990) =     28.826 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.826 ms/op
                 getUser·p0.9999: 19.285 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.240 ms/op
                 getUser·p0.9999: 15.243 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.659 ms/op
                 getUser·p0.999:  6.845 ms/op
                 getUser·p0.9999: 21.821 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316323
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23553 
    [ 2.500,  5.000) = 291484 
    [ 5.000,  7.500) = 1071 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.002 ms/op
     p(99.9900) =     21.139 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 5.320 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.834 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.739 ms/op
                 listUser·p0.999:  22.489 ms/op
                 listUser·p0.9999: 26.164 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.220 ms/op
                 listUser·p0.9999: 17.864 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244026
  mean =      3.934 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3025 
    [ 2.500,  5.000) = 220453 
    [ 5.000,  7.500) = 19302 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     15.203 ms/op
     p(99.9900) =     25.467 ms/op
     p(99.9990) =     27.019 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.383 ± 3.856  ops/ms
ClientGrpc.existUser                       thrpt       3  10.916 ± 1.848  ops/ms
ClientGrpc.getUser                         thrpt       3  10.488 ± 1.482  ops/ms
ClientGrpc.listUser                        thrpt       3   8.105 ± 1.783  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.874   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.502   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.339   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 0.227   ms/op
ClientGrpc.createUser                     sample  310673   3.088 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.129           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.233           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  330629   2.905 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.833           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.936           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.621           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.901           ms/op
ClientGrpc.getUser                        sample  316323   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.836           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.002           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.139           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  244026   3.934 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.203           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.467           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
