# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.169 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 9.653 ops/ms
Iteration   1: 10.152 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 10.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.213 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (10.139, 10.213, 10.347), stdev = 0.117
  CI (99.9%): [8.086, 12.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.476 ops/ms
# Warmup Iteration   2: 10.368 ops/ms
# Warmup Iteration   3: 10.947 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.805 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.785 ±(99.9%) 0.446 ops/ms [Average]
  (min, avg, max) = (10.758, 10.785, 10.805), stdev = 0.024
  CI (99.9%): [10.340, 11.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.044 ops/ms
# Warmup Iteration   2: 9.855 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.284 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (10.266, 10.284, 10.313), stdev = 0.025
  CI (99.9%): [9.820, 10.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.922 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 7.864 ops/ms
Iteration   2: 7.921 ops/ms
Iteration   3: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.875 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (7.841, 7.875, 7.921), stdev = 0.041
  CI (99.9%): [7.128, 8.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.118 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.143 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.118, 3.143, 3.173), stdev = 0.028
  CI (99.9%): [2.633, 3.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.972 ±(99.9%) 0.004 ms/op
Iteration   2: 2.920 ±(99.9%) 0.004 ms/op
Iteration   3: 2.834 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (2.834, 2.908, 2.972), stdev = 0.070
  CI (99.9%): [1.635, 4.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.148 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.056, 3.088, 3.148), stdev = 0.052
  CI (99.9%): [2.142, 4.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.658 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.024 ms/op
Iteration   1: 3.978 ±(99.9%) 0.009 ms/op
Iteration   2: 3.987 ±(99.9%) 0.024 ms/op
Iteration   3: 3.926 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.964 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (3.926, 3.964, 3.987), stdev = 0.033
  CI (99.9%): [3.363, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  6.976 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.466 ms/op
                 createUser·p0.9999: 21.384 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.642 ms/op
                 createUser·p0.999:  9.135 ms/op
                 createUser·p0.9999: 15.245 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311783
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20604 
    [ 2.500,  5.000) = 289528 
    [ 5.000,  7.500) = 1244 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     20.495 ms/op
     p(99.9990) =     21.557 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.543 ms/op
                 existUser·p0.9999: 12.278 ms/op
                 existUser·p1.00:   12.534 ms/op

Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.447 ms/op
                 existUser·p0.999:  7.573 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.459 ms/op
                 existUser·p0.9999: 15.927 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316720
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2172 
    [ 1.250,  2.500) = 21924 
    [ 2.500,  3.750) = 274586 
    [ 3.750,  5.000) = 16645 
    [ 5.000,  6.250) = 936 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     15.334 ms/op
     p(99.9990) =     16.179 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.771 ms/op
                 getUser·p0.9999: 16.259 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.776 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 16.296 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.381 ms/op
                 getUser·p0.9999: 29.124 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313514
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19009 
    [ 2.500,  5.000) = 292896 
    [ 5.000,  7.500) = 1264 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     28.560 ms/op
     p(99.9990) =     29.421 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.010 ms/op
Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  12.419 ms/op
                 listUser·p0.9999: 19.004 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 3.994 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  18.756 ms/op
                 listUser·p0.9999: 22.815 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239243
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4152 
    [ 2.500,  5.000) = 207600 
    [ 5.000,  7.500) = 26017 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.131 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.529 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.213 ± 2.127  ops/ms
ClientGrpc.existUser                       thrpt       3  10.785 ± 0.446  ops/ms
ClientGrpc.getUser                         thrpt       3  10.284 ± 0.465  ops/ms
ClientGrpc.listUser                        thrpt       3   7.875 ± 0.747  ops/ms
ClientGrpc.createUser                       avgt       3   3.143 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 1.274   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 0.946   ms/op
ClientGrpc.listUser                         avgt       3   3.964 ± 0.600   ms/op
ClientGrpc.createUser                     sample  311783   3.081 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.495           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  316720   3.032 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.677           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.334           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.269           ms/op
ClientGrpc.getUser                        sample  313514   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.610           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.560           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.524           ms/op
ClientGrpc.listUser                       sample  239243   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.131           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.640           ms/op
