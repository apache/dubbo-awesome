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
# Warmup Iteration   1: 4.161 ops/ms
# Warmup Iteration   2: 8.975 ops/ms
# Warmup Iteration   3: 10.086 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.455 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.601 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (10.455, 10.601, 10.703), stdev = 0.130
  CI (99.9%): [8.230, 12.972] (assumes normal distribution)


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
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 10.746 ops/ms
# Warmup Iteration   3: 11.203 ops/ms
Iteration   1: 11.110 ops/ms
Iteration   2: 11.011 ops/ms
Iteration   3: 11.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.068 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (11.011, 11.068, 11.110), stdev = 0.051
  CI (99.9%): [10.129, 12.006] (assumes normal distribution)


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
# Warmup Iteration   1: 7.430 ops/ms
# Warmup Iteration   2: 10.167 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.686 ±(99.9%) 0.684 ops/ms [Average]
  (min, avg, max) = (10.644, 10.686, 10.716), stdev = 0.037
  CI (99.9%): [10.002, 11.369] (assumes normal distribution)


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
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.115 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (7.984, 8.115, 8.268), stdev = 0.143
  CI (99.9%): [5.499, 10.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.010, 3.030, 3.041), stdev = 0.017
  CI (99.9%): [2.719, 3.341] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 2.797 ±(99.9%) 0.004 ms/op
Iteration   2: 2.907 ±(99.9%) 0.004 ms/op
Iteration   3: 2.918 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.874 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (2.797, 2.874, 2.918), stdev = 0.067
  CI (99.9%): [1.652, 4.096] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (2.921, 2.996, 3.042), stdev = 0.066
  CI (99.9%): [1.799, 4.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.980 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.013 ms/op
Iteration   1: 3.885 ±(99.9%) 0.005 ms/op
Iteration   2: 3.952 ±(99.9%) 0.016 ms/op
Iteration   3: 3.928 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.885, 3.921, 3.952), stdev = 0.034
  CI (99.9%): [3.304, 4.539] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  8.186 ms/op
                 createUser·p0.9999: 12.360 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.832 ms/op
                 createUser·p0.9999: 13.278 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 21.641 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317402
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19964 
    [ 2.500,  5.000) = 295440 
    [ 5.000,  7.500) = 1494 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     21.185 ms/op
     p(99.9990) =     21.959 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.007 ms/op
Iteration   1: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  7.414 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.567 ms/op
                 existUser·p0.999:  7.866 ms/op
                 existUser·p0.9999: 18.452 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.868 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  6.860 ms/op
                 existUser·p0.9999: 16.534 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330442
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3800 
    [ 1.250,  2.500) = 39413 
    [ 2.500,  3.750) = 274184 
    [ 3.750,  5.000) = 11214 
    [ 5.000,  6.250) = 1144 
    [ 6.250,  7.500) = 378 
    [ 7.500,  8.750) = 144 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     17.202 ms/op
     p(99.9990) =     18.635 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.741 ms/op
                 getUser·p0.999:  10.191 ms/op
                 getUser·p0.9999: 13.606 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.500 ms/op
                 getUser·p0.9999: 21.275 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.798 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320051
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27452 
    [ 2.500,  5.000) = 290610 
    [ 5.000,  7.500) = 1418 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.781 ms/op
     p(99.9900) =     20.971 ms/op
     p(99.9990) =     21.784 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 5.493 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  13.639 ms/op
                 listUser·p0.9999: 16.153 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.957 ms/op
                 listUser·p0.9999: 15.686 ms/op
                 listUser·p1.00:   16.286 ms/op

Iteration   3: 3.996 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  21.068 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242775
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5179 
    [ 2.500,  5.000) = 213537 
    [ 5.000,  7.500) = 22389 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     23.944 ms/op
     p(99.9990) =     24.955 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.601 ± 2.371  ops/ms
ClientGrpc.existUser                       thrpt       3  11.068 ± 0.938  ops/ms
ClientGrpc.getUser                         thrpt       3  10.686 ± 0.684  ops/ms
ClientGrpc.listUser                        thrpt       3   8.115 ± 2.616  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.311   ms/op
ClientGrpc.existUser                        avgt       3   2.874 ± 1.222   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 1.197   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 0.618   ms/op
ClientGrpc.createUser                     sample  317402   3.025 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.185           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  330442   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.414           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  320051   2.998 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.613           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.971           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.987           ms/op
ClientGrpc.listUser                       sample  242775   3.953 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.944           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
