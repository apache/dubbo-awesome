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
# Warmup Iteration   1: 4.303 ops/ms
# Warmup Iteration   2: 9.105 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.494 ±(99.9%) 3.284 ops/ms [Average]
  (min, avg, max) = (10.288, 10.494, 10.615), stdev = 0.180
  CI (99.9%): [7.211, 13.778] (assumes normal distribution)


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
# Warmup Iteration   1: 7.596 ops/ms
# Warmup Iteration   2: 10.557 ops/ms
# Warmup Iteration   3: 10.860 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 10.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.905 ±(99.9%) 2.809 ops/ms [Average]
  (min, avg, max) = (10.771, 10.905, 11.073), stdev = 0.154
  CI (99.9%): [8.096, 13.714] (assumes normal distribution)


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
# Warmup Iteration   1: 7.448 ops/ms
# Warmup Iteration   2: 10.233 ops/ms
# Warmup Iteration   3: 10.575 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.364 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.479 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (10.364, 10.479, 10.644), stdev = 0.147
  CI (99.9%): [7.805, 13.153] (assumes normal distribution)


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
# Warmup Iteration   1: 5.960 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.039 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 8.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.188 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (8.117, 8.188, 8.293), stdev = 0.093
  CI (99.9%): [6.493, 9.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.066 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.023, 3.066, 3.117), stdev = 0.048
  CI (99.9%): [2.199, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.004 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.841 ±(99.9%) 0.004 ms/op
Iteration   3: 2.922 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (2.841, 2.901, 2.940), stdev = 0.053
  CI (99.9%): [1.939, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.010, 3.030, 3.055), stdev = 0.023
  CI (99.9%): [2.608, 3.452] (assumes normal distribution)


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
# Warmup Iteration   1: 5.146 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.015 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
Iteration   2: 3.914 ±(99.9%) 0.014 ms/op
Iteration   3: 3.931 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.914, 3.930, 3.945), stdev = 0.015
  CI (99.9%): [3.653, 4.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.850 ms/op
                 createUser·p0.9999: 11.715 ms/op
                 createUser·p1.00:   12.026 ms/op

Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.834 ms/op
                 createUser·p0.9999: 13.736 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.955 ms/op
                 createUser·p0.9999: 27.403 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320137
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28114 
    [ 2.500,  5.000) = 290986 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     26.454 ms/op
     p(99.9990) =     27.741 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.308 ms/op
                 existUser·p0.9999: 17.731 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.244 ms/op
                 existUser·p0.9999: 12.552 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.217 ms/op
                 existUser·p0.9999: 15.288 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326768
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1864 
    [ 1.250,  2.500) = 31013 
    [ 2.500,  3.750) = 282962 
    [ 3.750,  5.000) = 10007 
    [ 5.000,  6.250) = 621 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.128 ms/op
     p(99.9900) =     17.214 ms/op
     p(99.9990) =     18.038 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.691 ms/op
                 getUser·p0.999:  8.725 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.308 ms/op
                 getUser·p0.9999: 29.475 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 26.832 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315604
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24710 
    [ 2.500,  5.000) = 288735 
    [ 5.000,  7.500) = 1603 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.723 ms/op
     p(99.9900) =     28.850 ms/op
     p(99.9990) =     29.715 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 5.780 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.036 ms/op
                 listUser·p0.9999: 15.105 ms/op
                 listUser·p1.00:   15.450 ms/op

Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.331 ms/op
                 listUser·p0.9999: 17.327 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  17.518 ms/op
                 listUser·p0.9999: 23.197 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243701
  mean =      3.937 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4444 
    [ 2.500,  5.000) = 213657 
    [ 5.000,  7.500) = 24291 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.226 ms/op
     p(99.9900) =     21.177 ms/op
     p(99.9990) =     23.452 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.494 ± 3.284  ops/ms
ClientGrpc.existUser                       thrpt       3  10.905 ± 2.809  ops/ms
ClientGrpc.getUser                         thrpt       3  10.479 ± 2.674  ops/ms
ClientGrpc.listUser                        thrpt       3   8.188 ± 1.695  ops/ms
ClientGrpc.createUser                       avgt       3   3.066 ± 0.867   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.962   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.422   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.277   ms/op
ClientGrpc.createUser                     sample  320137   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.565           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.053           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.454           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.409           ms/op
ClientGrpc.existUser                      sample  326768   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.541           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.214           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  315604   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.723           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.850           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.950           ms/op
ClientGrpc.listUser                       sample  243701   3.937 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.771           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.226           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.177           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
