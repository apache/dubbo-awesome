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
# Warmup Iteration   1: 2.966 ops/ms
# Warmup Iteration   2: 6.240 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.033 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (7.837, 8.033, 8.170), stdev = 0.174
  CI (99.9%): [4.857, 11.208] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.901 ops/ms
# Warmup Iteration   2: 8.148 ops/ms
# Warmup Iteration   3: 8.498 ops/ms
Iteration   1: 8.747 ops/ms
Iteration   2: 9.270 ops/ms
Iteration   3: 8.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.962 ±(99.9%) 4.993 ops/ms [Average]
  (min, avg, max) = (8.747, 8.962, 9.270), stdev = 0.274
  CI (99.9%): [3.969, 13.955] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.201 ops/ms
# Warmup Iteration   2: 8.090 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.348 ops/ms
Iteration   3: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.394 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (8.348, 8.394, 8.433), stdev = 0.043
  CI (99.9%): [7.613, 9.174] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ops/ms
# Warmup Iteration   2: 6.082 ops/ms
# Warmup Iteration   3: 6.513 ops/ms
Iteration   1: 6.500 ops/ms
Iteration   2: 6.686 ops/ms
Iteration   3: 6.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.649 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (6.500, 6.649, 6.760), stdev = 0.134
  CI (99.9%): [4.211, 9.086] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.778 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.902 ±(99.9%) 0.004 ms/op
Iteration   2: 3.830 ±(99.9%) 0.003 ms/op
Iteration   3: 3.800 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.844 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.800, 3.844, 3.902), stdev = 0.052
  CI (99.9%): [2.887, 4.801] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.003 ms/op
Iteration   1: 3.661 ±(99.9%) 0.003 ms/op
Iteration   2: 3.586 ±(99.9%) 0.005 ms/op
Iteration   3: 3.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.599 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.549, 3.599, 3.661), stdev = 0.057
  CI (99.9%): [2.554, 4.643] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.486 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.004 ms/op
Iteration   1: 3.821 ±(99.9%) 0.004 ms/op
Iteration   2: 3.766 ±(99.9%) 0.003 ms/op
Iteration   3: 3.786 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.791 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.766, 3.791, 3.821), stdev = 0.028
  CI (99.9%): [3.284, 4.299] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.973 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.254 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.969 ±(99.9%) 0.015 ms/op
Iteration   1: 4.982 ±(99.9%) 0.013 ms/op
Iteration   2: 4.901 ±(99.9%) 0.015 ms/op
Iteration   3: 5.221 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.035 ±(99.9%) 3.033 ms/op [Average]
  (min, avg, max) = (4.901, 5.035, 5.221), stdev = 0.166
  CI (99.9%): [2.002, 8.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  12.819 ms/op
                 createUser·p0.9999: 15.412 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  13.129 ms/op
                 createUser·p0.9999: 17.822 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.873 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  12.868 ms/op
                 createUser·p0.9999: 21.372 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245981
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6843 
    [ 2.500,  5.000) = 223284 
    [ 5.000,  7.500) = 13541 
    [ 7.500, 10.000) = 1587 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     21.534 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.167 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.009 ms/op
Iteration   1: 3.659 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.289 ms/op
                 existUser·p0.9999: 14.803 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 3.574 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  13.773 ms/op
                 existUser·p0.9999: 27.625 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.690 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  11.294 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263679
  mean =      3.641 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8678 
    [ 2.500,  5.000) = 246683 
    [ 5.000,  7.500) = 7166 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     26.887 ms/op
     p(99.9990) =     28.156 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.568 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
Iteration   1: 3.865 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  10.510 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.738 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  9.888 ms/op
                 getUser·p0.9999: 18.085 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  11.623 ms/op
                 getUser·p0.9999: 24.196 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253569
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4598 
    [ 2.500,  5.000) = 239663 
    [ 5.000,  7.500) = 7894 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     21.582 ms/op
     p(99.9990) =     24.574 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 6.923 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.014 ms/op
Iteration   1: 4.690 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  15.365 ms/op
                 listUser·p0.9999: 21.715 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 4.767 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  17.062 ms/op
                 listUser·p0.9999: 23.406 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 4.768 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  23.966 ms/op
                 listUser·p0.9999: 30.910 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202515
  mean =      4.741 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 200 
    [ 2.500,  5.000) = 155274 
    [ 5.000,  7.500) = 42486 
    [ 7.500, 10.000) = 3700 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     16.686 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.033 ± 3.176  ops/ms
ClientGrpc.existUser                       thrpt       3   8.962 ± 4.993  ops/ms
ClientGrpc.getUser                         thrpt       3   8.394 ± 0.781  ops/ms
ClientGrpc.listUser                        thrpt       3   6.649 ± 2.437  ops/ms
ClientGrpc.createUser                       avgt       3   3.844 ± 0.957   ms/op
ClientGrpc.existUser                        avgt       3   3.599 ± 1.045   ms/op
ClientGrpc.getUser                          avgt       3   3.791 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   5.035 ± 3.033   ms/op
ClientGrpc.createUser                     sample  245981   3.901 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.863           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.177           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.911           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.873           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.627           ms/op
ClientGrpc.existUser                      sample  263679   3.641 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.887           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.606           ms/op
ClientGrpc.getUser                        sample  253569   3.783 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.925           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.207           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.582           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  202515   4.741 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.405           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.803           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.097           ms/op
