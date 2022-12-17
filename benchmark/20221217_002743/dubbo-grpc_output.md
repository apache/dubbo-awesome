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
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 9.573 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.377 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.444 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (10.377, 10.444, 10.578), stdev = 0.116
  CI (99.9%): [8.331, 12.557] (assumes normal distribution)


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
# Warmup Iteration   1: 7.871 ops/ms
# Warmup Iteration   2: 10.970 ops/ms
# Warmup Iteration   3: 11.113 ops/ms
Iteration   1: 11.244 ops/ms
Iteration   2: 11.097 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.100 ±(99.9%) 2.605 ops/ms [Average]
  (min, avg, max) = (10.958, 11.100, 11.244), stdev = 0.143
  CI (99.9%): [8.495, 13.705] (assumes normal distribution)


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
# Warmup Iteration   1: 7.565 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.554 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (10.461, 10.554, 10.602), stdev = 0.080
  CI (99.9%): [9.092, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 5.706 ops/ms
# Warmup Iteration   2: 7.654 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.245 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.153 ±(99.9%) 1.995 ops/ms [Average]
  (min, avg, max) = (8.032, 8.153, 8.245), stdev = 0.109
  CI (99.9%): [6.157, 10.148] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.004 ms/op
Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
Iteration   3: 3.011 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.031 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (3.011, 3.031, 3.047), stdev = 0.018
  CI (99.9%): [2.695, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.004 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (2.915, 2.949, 2.988), stdev = 0.037
  CI (99.9%): [2.283, 3.616] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.184 ±(99.9%) 0.001 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 1.852 ms/op [Average]
  (min, avg, max) = (2.995, 3.068, 3.184), stdev = 0.101
  CI (99.9%): [1.217, 4.920] (assumes normal distribution)


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.042 ms/op
Iteration   1: 3.968 ±(99.9%) 0.020 ms/op
Iteration   2: 3.984 ±(99.9%) 0.008 ms/op
Iteration   3: 3.929 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.929, 3.961, 3.984), stdev = 0.029
  CI (99.9%): [3.438, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.411 ms/op
                 createUser·p0.9999: 20.654 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  14.309 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311954
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29062 
    [ 2.500,  5.000) = 281810 
    [ 5.000,  7.500) = 691 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     11.814 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     21.586 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
Iteration   1: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.171 ms/op
                 existUser·p0.9999: 10.897 ms/op
                 existUser·p1.00:   11.158 ms/op

Iteration   2: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 11.176 ms/op
                 existUser·p1.00:   12.222 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  10.263 ms/op
                 existUser·p0.9999: 15.449 ms/op
                 existUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325026
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2228 
    [ 1.250,  2.500) = 41441 
    [ 2.500,  3.750) = 264110 
    [ 3.750,  5.000) = 16370 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     15.798 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.124 ms/op
                 getUser·p0.9999: 11.917 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.315 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 22.861 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.171 ms/op
                 getUser·p0.9999: 17.183 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313601
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24416 
    [ 2.500,  5.000) = 288220 
    [ 5.000,  7.500) = 575 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.919 ms/op
     p(99.9900) =     22.509 ms/op
     p(99.9990) =     23.031 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.609 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.189 ms/op
                 listUser·p0.9999: 24.114 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240386
  mean =      3.994 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3985 
    [ 2.500,  5.000) = 208955 
    [ 5.000,  7.500) = 25937 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     27.347 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.444 ± 2.113  ops/ms
ClientGrpc.existUser                       thrpt       3  11.100 ± 2.605  ops/ms
ClientGrpc.getUser                         thrpt       3  10.554 ± 1.462  ops/ms
ClientGrpc.listUser                        thrpt       3   8.153 ± 1.995  ops/ms
ClientGrpc.createUser                       avgt       3   3.031 ± 0.336   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.667   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 1.852   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.522   ms/op
ClientGrpc.createUser                     sample  311954   3.080 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.662           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.814           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.695           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  325026   2.953 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.365           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.729           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.909           ms/op
ClientGrpc.getUser                        sample  313601   3.059 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.606           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.919           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.509           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  240386   3.994 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.937           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
