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
# Warmup Iteration   1: 2.171 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 6.520 ops/ms
Iteration   1: 6.339 ops/ms
Iteration   2: 6.706 ops/ms
Iteration   3: 6.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.466 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (6.339, 6.466, 6.706), stdev = 0.208
  CI (99.9%): [2.668, 10.264] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ops/ms
# Warmup Iteration   2: 6.610 ops/ms
# Warmup Iteration   3: 6.975 ops/ms
Iteration   1: 7.093 ops/ms
Iteration   2: 7.243 ops/ms
Iteration   3: 7.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.163 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (7.093, 7.163, 7.243), stdev = 0.075
  CI (99.9%): [5.793, 8.533] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 6.111 ops/ms
# Warmup Iteration   3: 6.563 ops/ms
Iteration   1: 6.648 ops/ms
Iteration   2: 6.576 ops/ms
Iteration   3: 6.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.654 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (6.576, 6.654, 6.739), stdev = 0.081
  CI (99.9%): [5.168, 8.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 4.666 ops/ms
# Warmup Iteration   3: 5.317 ops/ms
Iteration   1: 5.164 ops/ms
Iteration   2: 5.424 ops/ms
Iteration   3: 5.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.316 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (5.164, 5.316, 5.424), stdev = 0.136
  CI (99.9%): [2.841, 7.791] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.447 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.946 ±(99.9%) 0.013 ms/op
Iteration   1: 4.958 ±(99.9%) 0.004 ms/op
Iteration   2: 4.797 ±(99.9%) 0.005 ms/op
Iteration   3: 4.842 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.866 ±(99.9%) 1.513 ms/op [Average]
  (min, avg, max) = (4.797, 4.866, 4.958), stdev = 0.083
  CI (99.9%): [3.353, 6.378] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.315 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.645 ±(99.9%) 0.004 ms/op
Iteration   1: 4.556 ±(99.9%) 0.005 ms/op
Iteration   2: 4.697 ±(99.9%) 0.006 ms/op
Iteration   3: 4.692 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.648 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (4.556, 4.648, 4.697), stdev = 0.080
  CI (99.9%): [3.187, 6.109] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.412 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.956 ±(99.9%) 0.004 ms/op
Iteration   1: 4.939 ±(99.9%) 0.004 ms/op
Iteration   2: 4.707 ±(99.9%) 0.004 ms/op
Iteration   3: 4.793 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.813 ±(99.9%) 2.135 ms/op [Average]
  (min, avg, max) = (4.707, 4.813, 4.939), stdev = 0.117
  CI (99.9%): [2.678, 6.948] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.485 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 6.644 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.066 ±(99.9%) 0.012 ms/op
Iteration   1: 6.169 ±(99.9%) 0.019 ms/op
Iteration   2: 6.174 ±(99.9%) 0.012 ms/op
Iteration   3: 5.985 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.109 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (5.985, 6.109, 6.174), stdev = 0.108
  CI (99.9%): [4.142, 8.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.297 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.060 ±(99.9%) 0.017 ms/op
Iteration   1: 4.993 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.062 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 21.273 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 4.922 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   6.767 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  13.125 ms/op
                 createUser·p0.9999: 25.920 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 5.010 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  25.991 ms/op
                 createUser·p0.9999: 43.229 ms/op
                 createUser·p1.00:   43.647 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 192846
  mean =      4.975 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 109903 
    [ 5.000, 10.000) = 82105 
    [10.000, 15.000) = 709 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 52 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     13.061 ms/op
     p(99.9900) =     42.926 ms/op
     p(99.9990) =     43.464 ms/op
     p(99.9999) =     43.647 ms/op
    p(100.0000) =     43.647 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.455 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.017 ms/op
Iteration   1: 4.733 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  12.430 ms/op
                 existUser·p0.9999: 25.891 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 4.610 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  14.404 ms/op
                 existUser·p0.9999: 23.531 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 4.648 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  14.067 ms/op
                 existUser·p0.9999: 26.057 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 205842
  mean =      4.663 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4935 
    [ 2.500,  5.000) = 132471 
    [ 5.000,  7.500) = 64528 
    [ 7.500, 10.000) = 3145 
    [10.000, 12.500) = 500 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     13.519 ms/op
     p(99.9900) =     25.704 ms/op
     p(99.9990) =     26.833 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.222 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.262 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.016 ms/op
Iteration   1: 4.809 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.121 ms/op
                 getUser·p0.95:   6.717 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  14.569 ms/op
                 getUser·p0.9999: 18.788 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 4.814 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.160 ms/op
                 getUser·p0.999:  14.197 ms/op
                 getUser·p0.9999: 25.767 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 4.880 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.660 ms/op
                 getUser·p0.99:   8.304 ms/op
                 getUser·p0.999:  12.054 ms/op
                 getUser·p0.9999: 24.586 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 198597
  mean =      4.834 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3118 
    [ 2.500,  5.000) = 118487 
    [ 5.000,  7.500) = 72278 
    [ 7.500, 10.000) = 3780 
    [10.000, 12.500) = 675 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.694 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     25.888 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.755 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 6.803 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.090 ±(99.9%) 0.024 ms/op
Iteration   1: 5.876 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  20.105 ms/op
                 listUser·p0.9999: 31.213 ms/op
                 listUser·p1.00:   32.113 ms/op

Iteration   2: 5.884 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.478 ms/op
                 listUser·p0.999:  19.093 ms/op
                 listUser·p0.9999: 27.294 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   3: 6.099 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  20.823 ms/op
                 listUser·p0.9999: 23.675 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161309
  mean =      5.951 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 42440 
    [ 5.000,  7.500) = 97024 
    [ 7.500, 10.000) = 17812 
    [10.000, 12.500) = 3090 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     20.318 ms/op
     p(99.9900) =     28.495 ms/op
     p(99.9990) =     32.072 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.466 ± 3.798  ops/ms
ClientGrpc.existUser                       thrpt       3   7.163 ± 1.370  ops/ms
ClientGrpc.getUser                         thrpt       3   6.654 ± 1.486  ops/ms
ClientGrpc.listUser                        thrpt       3   5.316 ± 2.475  ops/ms
ClientGrpc.createUser                       avgt       3   4.866 ± 1.513   ms/op
ClientGrpc.existUser                        avgt       3   4.648 ± 1.461   ms/op
ClientGrpc.getUser                          avgt       3   4.813 ± 2.135   ms/op
ClientGrpc.listUser                         avgt       3   6.109 ± 1.967   ms/op
ClientGrpc.createUser                     sample  192846   4.975 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.171           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.332           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.873           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.061           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          42.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          43.647           ms/op
ClientGrpc.existUser                      sample  205842   4.663 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.044           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.704           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  198597   4.834 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.153           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.177           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.717           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.749           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.694           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  161309   5.951 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.979           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.946           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.370           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.495           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.113           ms/op
