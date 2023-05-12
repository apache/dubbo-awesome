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
# Warmup Iteration   1: 4.491 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 10.447 ops/ms
Iteration   1: 10.700 ops/ms
Iteration   2: 10.773 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 0.672 ops/ms [Average]
  (min, avg, max) = (10.700, 10.735, 10.773), stdev = 0.037
  CI (99.9%): [10.064, 11.407] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 11.225 ops/ms
# Warmup Iteration   3: 11.309 ops/ms
Iteration   1: 11.646 ops/ms
Iteration   2: 11.471 ops/ms
Iteration   3: 11.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.482 ±(99.9%) 2.903 ops/ms [Average]
  (min, avg, max) = (11.328, 11.482, 11.646), stdev = 0.159
  CI (99.9%): [8.579, 14.385] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 10.612 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 10.899 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.850 ±(99.9%) 0.776 ops/ms [Average]
  (min, avg, max) = (10.823, 10.850, 10.899), stdev = 0.043
  CI (99.9%): [10.074, 11.625] (assumes normal distribution)


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
# Warmup Iteration   1: 6.153 ops/ms
# Warmup Iteration   2: 8.157 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.550 ops/ms
Iteration   2: 8.488 ops/ms
Iteration   3: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.512 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (8.488, 8.512, 8.550), stdev = 0.033
  CI (99.9%): [7.906, 9.118] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (2.958, 2.990, 3.020), stdev = 0.031
  CI (99.9%): [2.431, 3.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
Iteration   1: 2.806 ±(99.9%) 0.004 ms/op
Iteration   2: 2.859 ±(99.9%) 0.003 ms/op
Iteration   3: 2.862 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (2.806, 2.842, 2.862), stdev = 0.032
  CI (99.9%): [2.265, 3.420] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.004 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.941, 2.958, 2.979), stdev = 0.019
  CI (99.9%): [2.607, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.015 ms/op
Iteration   1: 3.828 ±(99.9%) 0.014 ms/op
Iteration   2: 3.724 ±(99.9%) 0.043 ms/op
Iteration   3: 3.690 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.747 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.690, 3.747, 3.828), stdev = 0.072
  CI (99.9%): [2.434, 5.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.105 ms/op
                 createUser·p0.9999: 16.309 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 16.015 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  16.661 ms/op
                 createUser·p0.9999: 28.213 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317904
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21219 
    [ 2.500,  5.000) = 294935 
    [ 5.000,  7.500) = 1230 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     27.015 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.873 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.006 ms/op
Iteration   1: 2.867 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.139 ms/op
                 existUser·p0.9999: 16.048 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 22.534 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336446
  mean =      2.852 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47585 
    [ 2.500,  5.000) = 287916 
    [ 5.000,  7.500) = 716 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =     21.966 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 12.669 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   2: 2.921 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.123 ms/op
                 getUser·p0.9999: 13.796 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.929 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  5.839 ms/op
                 getUser·p0.9999: 27.921 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327519
  mean =      2.930 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40030 
    [ 2.500,  5.000) = 286607 
    [ 5.000,  7.500) = 665 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.340 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     18.976 ms/op
     p(99.9990) =     28.228 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.010 ms/op
Iteration   1: 3.776 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  11.927 ms/op
                 listUser·p0.9999: 14.608 ms/op
                 listUser·p1.00:   15.401 ms/op

Iteration   2: 3.800 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 17.083 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.748 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.413 ms/op
                 listUser·p0.9999: 15.212 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 254169
  mean =      3.775 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 6615 
    [ 2.500,  3.750) = 144332 
    [ 3.750,  5.000) = 84571 
    [ 5.000,  6.250) = 15141 
    [ 6.250,  7.500) = 2657 
    [ 7.500,  8.750) = 296 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 155 
    [13.750, 15.000) = 112 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     15.338 ms/op
     p(99.9990) =     17.472 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 0.672  ops/ms
ClientGrpc.existUser                       thrpt       3  11.482 ± 2.903  ops/ms
ClientGrpc.getUser                         thrpt       3  10.850 ± 0.776  ops/ms
ClientGrpc.listUser                        thrpt       3   8.512 ± 0.606  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.560   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.578   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.352   ms/op
ClientGrpc.listUser                         avgt       3   3.747 ± 1.313   ms/op
ClientGrpc.createUser                     sample  317904   3.019 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.372           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.015           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  336446   2.852 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.966           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  327519   2.930 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.707           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.340           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.144           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.976           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.344           ms/op
ClientGrpc.listUser                       sample  254169   3.775 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.851           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.338           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.596           ms/op
