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
# Warmup Iteration   1: 4.887 ops/ms
# Warmup Iteration   2: 9.491 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 10.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.627 ±(99.9%) 0.879 ops/ms [Average]
  (min, avg, max) = (10.574, 10.627, 10.668), stdev = 0.048
  CI (99.9%): [9.747, 11.506] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ops/ms
# Warmup Iteration   2: 10.924 ops/ms
# Warmup Iteration   3: 11.061 ops/ms
Iteration   1: 11.094 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.266 ±(99.9%) 4.413 ops/ms [Average]
  (min, avg, max) = (11.094, 11.266, 11.542), stdev = 0.242
  CI (99.9%): [6.852, 15.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.327 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.692 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (10.606, 10.692, 10.745), stdev = 0.076
  CI (99.9%): [9.314, 12.070] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.187 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.285 ops/ms
Iteration   1: 8.269 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.261 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (8.194, 8.261, 8.322), stdev = 0.064
  CI (99.9%): [7.089, 9.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.004 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.004 ms/op
Iteration   3: 2.977 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.967, 2.973, 2.977), stdev = 0.005
  CI (99.9%): [2.875, 3.071] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.900 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.934 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.909, 2.934, 2.966), stdev = 0.029
  CI (99.9%): [2.404, 3.465] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
Iteration   3: 3.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.988, 3.000, 3.018), stdev = 0.016
  CI (99.9%): [2.700, 3.300] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.007 ms/op
Iteration   1: 3.816 ±(99.9%) 0.018 ms/op
Iteration   2: 3.833 ±(99.9%) 0.015 ms/op
Iteration   3: 3.877 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.842 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.816, 3.842, 3.877), stdev = 0.032
  CI (99.9%): [3.264, 4.420] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.936 ms/op
                 createUser·p0.9999: 13.873 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.795 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 21.931 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318854
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31317 
    [ 2.500,  5.000) = 285367 
    [ 5.000,  7.500) = 1523 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     21.434 ms/op
     p(99.9990) =     22.178 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.124 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.093 ms/op
                 existUser·p0.9999: 14.560 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.963 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327958
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2030 
    [ 1.250,  2.500) = 40003 
    [ 2.500,  3.750) = 272827 
    [ 3.750,  5.000) = 11694 
    [ 5.000,  6.250) = 700 
    [ 6.250,  7.500) = 356 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     15.071 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  9.368 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.101 ms/op
                 getUser·p0.9999: 23.314 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.251 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 21.114 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320299
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27442 
    [ 2.500,  5.000) = 291005 
    [ 5.000,  7.500) = 1189 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     23.586 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 5.071 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.040 ms/op
                 listUser·p0.999:  12.794 ms/op
                 listUser·p0.9999: 16.300 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.561 ms/op
                 listUser·p0.9999: 25.883 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.878 ms/op
                 listUser·p0.999:  13.870 ms/op
                 listUser·p0.9999: 22.799 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245193
  mean =      3.915 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4761 
    [ 2.500,  5.000) = 218733 
    [ 5.000,  7.500) = 20220 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     24.493 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.627 ± 0.879  ops/ms
ClientGrpc.existUser                       thrpt       3  11.266 ± 4.413  ops/ms
ClientGrpc.getUser                         thrpt       3  10.692 ± 1.378  ops/ms
ClientGrpc.listUser                        thrpt       3   8.261 ± 1.173  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.098   ms/op
ClientGrpc.existUser                        avgt       3   2.934 ± 0.531   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 0.300   ms/op
ClientGrpc.listUser                         avgt       3   3.842 ± 0.578   ms/op
ClientGrpc.createUser                     sample  318854   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.434           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  327958   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.287           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.139           ms/op
ClientGrpc.getUser                        sample  320299   2.998 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.251           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.093           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.808           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.822           ms/op
ClientGrpc.listUser                       sample  245193   3.915 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.493           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
