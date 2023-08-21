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
# Warmup Iteration   1: 4.381 ops/ms
# Warmup Iteration   2: 9.400 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.622 ±(99.9%) 2.477 ops/ms [Average]
  (min, avg, max) = (10.491, 10.622, 10.762), stdev = 0.136
  CI (99.9%): [8.145, 13.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.727 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 10.865 ops/ms
Iteration   1: 11.171 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.907 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (10.743, 10.907, 11.171), stdev = 0.231
  CI (99.9%): [6.686, 15.127] (assumes normal distribution)


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
# Warmup Iteration   1: 7.192 ops/ms
# Warmup Iteration   2: 10.063 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.643 ±(99.9%) 0.423 ops/ms [Average]
  (min, avg, max) = (10.616, 10.643, 10.657), stdev = 0.023
  CI (99.9%): [10.220, 11.066] (assumes normal distribution)


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
# Warmup Iteration   1: 5.159 ops/ms
# Warmup Iteration   2: 7.787 ops/ms
# Warmup Iteration   3: 8.119 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.138 ±(99.9%) 0.403 ops/ms [Average]
  (min, avg, max) = (8.117, 8.138, 8.161), stdev = 0.022
  CI (99.9%): [7.734, 8.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.512 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.004 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.012, 3.050, 3.108), stdev = 0.051
  CI (99.9%): [2.121, 3.979] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.003 ms/op
Iteration   1: 2.935 ±(99.9%) 0.001 ms/op
Iteration   2: 2.936 ±(99.9%) 0.002 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.911, 2.927, 2.936), stdev = 0.014
  CI (99.9%): [2.671, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.004 ms/op
Iteration   1: 2.997 ±(99.9%) 0.004 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.997, 3.009, 3.026), stdev = 0.015
  CI (99.9%): [2.736, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.014 ms/op
Iteration   1: 3.985 ±(99.9%) 0.019 ms/op
Iteration   2: 4.000 ±(99.9%) 0.024 ms/op
Iteration   3: 3.972 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.972, 3.986, 4.000), stdev = 0.014
  CI (99.9%): [3.722, 4.249] (assumes normal distribution)


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.180 ms/op
                 createUser·p0.9999: 13.384 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.743 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.430 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316855
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22777 
    [ 2.500,  5.000) = 292151 
    [ 5.000,  7.500) = 1369 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     23.788 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.832 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.571 ms/op
                 existUser·p0.9999: 18.406 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   2: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.969 ms/op
                 existUser·p0.9999: 20.027 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 2.909 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  10.078 ms/op
                 existUser·p0.9999: 21.267 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332160
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39335 
    [ 2.500,  5.000) = 291339 
    [ 5.000,  7.500) = 1050 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.963 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.977 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.307 ms/op
                 getUser·p0.9999: 12.730 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.032 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 16.571 ms/op
                 getUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315057
  mean =      3.049 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 485 
    [ 1.250,  2.500) = 22565 
    [ 2.500,  3.750) = 274633 
    [ 3.750,  5.000) = 15279 
    [ 5.000,  6.250) = 1132 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =     15.786 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 5.673 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.060 ms/op
                 listUser·p0.9999: 21.523 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.973 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 34.459 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 23.056 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243604
  mean =      3.941 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2665 
    [ 2.500,  5.000) = 219404 
    [ 5.000,  7.500) = 19727 
    [ 7.500, 10.000) = 1245 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     33.391 ms/op
     p(99.9990) =     35.107 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.622 ± 2.477  ops/ms
ClientGrpc.existUser                       thrpt       3  10.907 ± 4.220  ops/ms
ClientGrpc.getUser                         thrpt       3  10.643 ± 0.423  ops/ms
ClientGrpc.listUser                        thrpt       3   8.138 ± 0.403  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.929   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 0.256   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.273   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 0.263   ms/op
ClientGrpc.createUser                     sample  316855   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.788           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.395           ms/op
ClientGrpc.existUser                      sample  332160   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.741           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.447           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  315057   3.049 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.732           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.282           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.786           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.876           ms/op
ClientGrpc.listUser                       sample  243604   3.941 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.697           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.892           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.391           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.389           ms/op
