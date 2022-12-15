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
# Warmup Iteration   1: 2.938 ops/ms
# Warmup Iteration   2: 6.783 ops/ms
# Warmup Iteration   3: 7.877 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.351 ±(99.9%) 2.270 ops/ms [Average]
  (min, avg, max) = (8.218, 8.351, 8.465), stdev = 0.124
  CI (99.9%): [6.080, 10.621] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.153 ops/ms
# Warmup Iteration   2: 8.681 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 9.283 ops/ms
Iteration   3: 8.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.995 ±(99.9%) 4.612 ops/ms [Average]
  (min, avg, max) = (8.808, 8.995, 9.283), stdev = 0.253
  CI (99.9%): [4.383, 13.607] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.633 ops/ms
# Warmup Iteration   2: 8.108 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.473 ops/ms
Iteration   3: 8.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.298 ±(99.9%) 2.907 ops/ms [Average]
  (min, avg, max) = (8.160, 8.298, 8.473), stdev = 0.159
  CI (99.9%): [5.392, 11.205] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.726 ops/ms
# Warmup Iteration   2: 6.420 ops/ms
# Warmup Iteration   3: 6.603 ops/ms
Iteration   1: 6.585 ops/ms
Iteration   2: 6.893 ops/ms
Iteration   3: 6.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.780 ±(99.9%) 3.085 ops/ms [Average]
  (min, avg, max) = (6.585, 6.780, 6.893), stdev = 0.169
  CI (99.9%): [3.695, 9.865] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.420 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.004 ms/op
Iteration   1: 3.747 ±(99.9%) 0.005 ms/op
Iteration   2: 3.860 ±(99.9%) 0.002 ms/op
Iteration   3: 3.736 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.781 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (3.736, 3.781, 3.860), stdev = 0.068
  CI (99.9%): [2.534, 5.029] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.003 ms/op
Iteration   1: 3.705 ±(99.9%) 0.004 ms/op
Iteration   2: 3.694 ±(99.9%) 0.003 ms/op
Iteration   3: 3.586 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.662 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.586, 3.662, 3.705), stdev = 0.066
  CI (99.9%): [2.460, 4.864] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.249 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.003 ms/op
Iteration   1: 3.850 ±(99.9%) 0.003 ms/op
Iteration   2: 3.859 ±(99.9%) 0.003 ms/op
Iteration   3: 3.874 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.861 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (3.850, 3.861, 3.874), stdev = 0.012
  CI (99.9%): [3.640, 4.081] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.916 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.964 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.020 ms/op
Iteration   1: 4.888 ±(99.9%) 0.010 ms/op
Iteration   2: 4.647 ±(99.9%) 0.025 ms/op
Iteration   3: 4.668 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.734 ±(99.9%) 2.433 ms/op [Average]
  (min, avg, max) = (4.647, 4.734, 4.888), stdev = 0.133
  CI (99.9%): [2.301, 7.167] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
Iteration   1: 3.844 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  9.742 ms/op
                 createUser·p0.9999: 15.090 ms/op
                 createUser·p1.00:   15.679 ms/op

Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  15.220 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.844 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246501
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8563 
    [ 2.500,  5.000) = 221481 
    [ 5.000,  7.500) = 15319 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     18.493 ms/op
     p(99.9990) =     20.137 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.159 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.009 ms/op
Iteration   1: 3.646 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  8.571 ms/op
                 existUser·p0.9999: 15.044 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 3.707 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 22.917 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.675 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 21.571 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261154
  mean =      3.676 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9445 
    [ 2.500,  5.000) = 243988 
    [ 5.000,  7.500) = 7025 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      8.747 ms/op
     p(99.9900) =     22.365 ms/op
     p(99.9990) =     23.081 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.082 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
Iteration   1: 3.727 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   5.837 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 29.046 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 3.825 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  9.310 ms/op
                 getUser·p0.9999: 18.518 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  9.076 ms/op
                 getUser·p0.9999: 19.978 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252763
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9383 
    [ 2.500,  5.000) = 231117 
    [ 5.000,  7.500) = 11397 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     28.457 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 6.544 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.949 ±(99.9%) 0.016 ms/op
Iteration   1: 4.795 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.811 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  17.746 ms/op
                 listUser·p0.9999: 21.475 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 4.718 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  22.418 ms/op
                 listUser·p0.9999: 31.053 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201039
  mean =      4.774 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 640 
    [ 2.500,  5.000) = 149043 
    [ 5.000,  7.500) = 45803 
    [ 7.500, 10.000) = 4773 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     16.383 ms/op
     p(99.9900) =     29.127 ms/op
     p(99.9990) =     31.553 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.351 ± 2.270  ops/ms
ClientGrpc.existUser                       thrpt       3   8.995 ± 4.612  ops/ms
ClientGrpc.getUser                         thrpt       3   8.298 ± 2.907  ops/ms
ClientGrpc.listUser                        thrpt       3   6.780 ± 3.085  ops/ms
ClientGrpc.createUser                       avgt       3   3.781 ± 1.247   ms/op
ClientGrpc.existUser                        avgt       3   3.662 ± 1.202   ms/op
ClientGrpc.getUser                          avgt       3   3.861 ± 0.220   ms/op
ClientGrpc.listUser                         avgt       3   4.734 ± 2.433   ms/op
ClientGrpc.createUser                     sample  246501   3.895 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.767           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.145           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  261154   3.676 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.808           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.747           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.365           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  252763   3.801 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.912           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.229           ms/op
ClientGrpc.listUser                       sample  201039   4.774 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.383           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.127           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.654           ms/op
