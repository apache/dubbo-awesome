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
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 9.952 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.541 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (10.417, 10.541, 10.708), stdev = 0.150
  CI (99.9%): [7.801, 13.281] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.272 ops/ms
# Warmup Iteration   2: 10.799 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.263 ops/ms
Iteration   2: 11.312 ops/ms
Iteration   3: 11.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.206 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (11.044, 11.206, 11.312), stdev = 0.143
  CI (99.9%): [8.602, 13.810] (assumes normal distribution)


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
# Warmup Iteration   1: 6.374 ops/ms
# Warmup Iteration   2: 9.919 ops/ms
# Warmup Iteration   3: 10.330 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.449 ±(99.9%) 3.182 ops/ms [Average]
  (min, avg, max) = (10.280, 10.449, 10.629), stdev = 0.174
  CI (99.9%): [7.267, 13.631] (assumes normal distribution)


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
# Warmup Iteration   1: 5.203 ops/ms
# Warmup Iteration   2: 8.101 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 8.198 ops/ms
Iteration   2: 8.256 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.205 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (8.162, 8.205, 8.256), stdev = 0.047
  CI (99.9%): [7.341, 9.069] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.004 ms/op
Iteration   2: 3.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.046, 3.059, 3.077), stdev = 0.016
  CI (99.9%): [2.763, 3.355] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.002 ms/op
Iteration   1: 2.876 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.003 ms/op
Iteration   3: 2.857 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.857, 2.885, 2.922), stdev = 0.033
  CI (99.9%): [2.274, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (3.042, 3.045, 3.049), stdev = 0.004
  CI (99.9%): [2.978, 3.111] (assumes normal distribution)


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
# Warmup Iteration   1: 5.272 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.019 ms/op
Iteration   1: 3.925 ±(99.9%) 0.014 ms/op
Iteration   2: 3.963 ±(99.9%) 0.018 ms/op
Iteration   3: 3.902 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.902, 3.930, 3.963), stdev = 0.031
  CI (99.9%): [3.368, 4.492] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.127 ms/op
                 createUser·p0.9999: 13.019 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.682 ms/op
                 createUser·p0.9999: 18.947 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.088 ms/op
                 createUser·p0.9999: 17.579 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311893
  mean =      3.078 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 566 
    [ 1.250,  2.500) = 20312 
    [ 2.500,  3.750) = 272322 
    [ 3.750,  5.000) = 17271 
    [ 5.000,  6.250) = 735 
    [ 6.250,  7.500) = 344 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.841 ms/op
     p(99.9900) =     17.983 ms/op
     p(99.9990) =     19.260 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.134 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 20.145 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  7.852 ms/op
                 existUser·p0.9999: 16.538 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.179 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330403
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39055 
    [ 2.500,  5.000) = 290328 
    [ 5.000,  7.500) = 718 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      7.248 ms/op
     p(99.9900) =     17.577 ms/op
     p(99.9990) =     20.634 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.936 ms/op
                 getUser·p0.9999: 14.159 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  8.877 ms/op
                 getUser·p0.9999: 21.710 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.032 ms/op
                 getUser·p0.9999: 17.291 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313048
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17690 
    [ 2.500,  5.000) = 293778 
    [ 5.000,  7.500) = 1261 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =     20.962 ms/op
     p(99.9990) =     21.913 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.620 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.011 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  12.609 ms/op
                 listUser·p0.9999: 15.433 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.608 ms/op
                 listUser·p0.9999: 22.367 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.780 ms/op
                 listUser·p0.9999: 23.365 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240667
  mean =      3.988 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3621 
    [ 2.500,  5.000) = 213469 
    [ 5.000,  7.500) = 22414 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.849 ms/op
     p(99.9900) =     22.704 ms/op
     p(99.9990) =     24.497 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.541 ± 2.740  ops/ms
ClientGrpc.existUser                       thrpt       3  11.206 ± 2.604  ops/ms
ClientGrpc.getUser                         thrpt       3  10.449 ± 3.182  ops/ms
ClientGrpc.listUser                        thrpt       3   8.205 ± 0.864  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.296   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.611   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.066   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.562   ms/op
ClientGrpc.createUser                     sample  311893   3.078 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.841           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.983           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.399           ms/op
ClientGrpc.existUser                      sample  330403   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.248           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  313048   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.962           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  240667   3.988 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.019           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.849           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.704           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
