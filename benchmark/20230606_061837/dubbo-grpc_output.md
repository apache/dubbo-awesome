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
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 9.498 ops/ms
# Warmup Iteration   3: 10.257 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.862 ops/ms
Iteration   3: 10.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.833 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (10.719, 10.833, 10.918), stdev = 0.103
  CI (99.9%): [8.961, 12.706] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.902 ops/ms
# Warmup Iteration   2: 10.804 ops/ms
# Warmup Iteration   3: 11.189 ops/ms
Iteration   1: 11.510 ops/ms
Iteration   2: 11.254 ops/ms
Iteration   3: 11.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.428 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (11.254, 11.428, 11.520), stdev = 0.151
  CI (99.9%): [8.678, 14.179] (assumes normal distribution)


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
# Warmup Iteration   1: 7.318 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.726 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (10.684, 10.726, 10.809), stdev = 0.071
  CI (99.9%): [9.425, 12.027] (assumes normal distribution)


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
# Warmup Iteration   1: 5.880 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.323 ±(99.9%) 3.225 ops/ms [Average]
  (min, avg, max) = (8.139, 8.323, 8.492), stdev = 0.177
  CI (99.9%): [5.098, 11.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.003 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.967, 2.982, 2.999), stdev = 0.016
  CI (99.9%): [2.693, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.002 ms/op
Iteration   1: 2.839 ±(99.9%) 0.002 ms/op
Iteration   2: 2.866 ±(99.9%) 0.003 ms/op
Iteration   3: 2.851 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.852 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.839, 2.852, 2.866), stdev = 0.013
  CI (99.9%): [2.610, 3.094] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.004 ms/op
Iteration   3: 2.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.954, 2.971, 2.998), stdev = 0.024
  CI (99.9%): [2.539, 3.402] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.014 ms/op
Iteration   1: 3.913 ±(99.9%) 0.017 ms/op
Iteration   2: 3.851 ±(99.9%) 0.009 ms/op
Iteration   3: 3.855 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.851, 3.873, 3.913), stdev = 0.035
  CI (99.9%): [3.242, 4.504] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.562 ms/op
                 createUser·p0.9999: 18.445 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.566 ms/op
                 createUser·p0.9999: 20.280 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.367 ms/op
                 createUser·p0.999:  12.265 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320471
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31066 
    [ 2.500,  5.000) = 287934 
    [ 5.000,  7.500) = 1062 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.364 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     22.146 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.005 ms/op
Iteration   1: 2.837 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  6.260 ms/op
                 existUser·p0.9999: 12.119 ms/op
                 existUser·p1.00:   12.485 ms/op

Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 15.647 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.340 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337119
  mean =      2.848 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47881 
    [ 2.500,  5.000) = 287997 
    [ 5.000,  7.500) = 860 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.852 ms/op
     p(99.9900) =     20.027 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.955 ms/op
                 getUser·p0.9999: 16.105 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.107 ms/op
                 getUser·p0.9999: 32.580 ms/op
                 getUser·p1.00:   32.899 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  5.423 ms/op
                 getUser·p0.9999: 23.318 ms/op
                 getUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320359
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27252 
    [ 2.500,  5.000) = 292184 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.764 ms/op
     p(99.9900) =     31.750 ms/op
     p(99.9990) =     32.787 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 5.641 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.602 ms/op
                 listUser·p0.9999: 14.486 ms/op
                 listUser·p1.00:   15.122 ms/op

Iteration   2: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 20.876 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 3.862 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 22.034 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248653
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4036 
    [ 2.500,  5.000) = 226132 
    [ 5.000,  7.500) = 17374 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.178 ms/op
     p(99.9900) =     21.074 ms/op
     p(99.9990) =     25.809 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.833 ± 1.872  ops/ms
ClientGrpc.existUser                       thrpt       3  11.428 ± 2.750  ops/ms
ClientGrpc.getUser                         thrpt       3  10.726 ± 1.301  ops/ms
ClientGrpc.listUser                        thrpt       3   8.323 ± 3.225  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.289   ms/op
ClientGrpc.existUser                        avgt       3   2.852 ± 0.242   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.431   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.631   ms/op
ClientGrpc.createUser                     sample  320471   2.993 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.364           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  337119   2.848 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.659           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.240           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.852           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.027           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.330           ms/op
ClientGrpc.getUser                        sample  320359   2.996 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.764           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.750           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.899           ms/op
ClientGrpc.listUser                       sample  248653   3.858 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.178           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.074           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
