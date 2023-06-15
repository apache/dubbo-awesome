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
# Warmup Iteration   1: 3.786 ops/ms
# Warmup Iteration   2: 7.961 ops/ms
# Warmup Iteration   3: 9.511 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 9.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.972 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (9.904, 9.972, 10.064), stdev = 0.083
  CI (99.9%): [8.466, 11.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 9.708 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.709 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.680 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (10.637, 10.680, 10.709), stdev = 0.039
  CI (99.9%): [9.978, 11.383] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.586 ops/ms
# Warmup Iteration   2: 9.606 ops/ms
# Warmup Iteration   3: 9.914 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.999 ±(99.9%) 1.057 ops/ms [Average]
  (min, avg, max) = (9.958, 9.999, 10.066), stdev = 0.058
  CI (99.9%): [8.942, 11.056] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ops/ms
# Warmup Iteration   2: 7.140 ops/ms
# Warmup Iteration   3: 7.466 ops/ms
Iteration   1: 7.626 ops/ms
Iteration   2: 7.666 ops/ms
Iteration   3: 7.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.620 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (7.570, 7.620, 7.666), stdev = 0.048
  CI (99.9%): [6.744, 8.497] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.004 ms/op
Iteration   1: 3.246 ±(99.9%) 0.003 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.197 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.197 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.148, 3.197, 3.246), stdev = 0.049
  CI (99.9%): [2.299, 4.095] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.001 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.063 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.020, 3.063, 3.135), stdev = 0.063
  CI (99.9%): [1.912, 4.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.289 ±(99.9%) 0.003 ms/op
Iteration   2: 3.382 ±(99.9%) 0.004 ms/op
Iteration   3: 3.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.276 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (3.156, 3.276, 3.382), stdev = 0.114
  CI (99.9%): [1.203, 5.349] (assumes normal distribution)


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.021 ms/op
Iteration   1: 4.214 ±(99.9%) 0.010 ms/op
Iteration   2: 4.265 ±(99.9%) 0.028 ms/op
Iteration   3: 4.249 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.243 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (4.214, 4.243, 4.265), stdev = 0.026
  CI (99.9%): [3.770, 4.716] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  9.202 ms/op
                 createUser·p0.9999: 33.096 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.565 ms/op
                 createUser·p0.999:  8.074 ms/op
                 createUser·p0.9999: 25.592 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 3.336 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  11.336 ms/op
                 createUser·p0.9999: 24.261 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295200
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11721 
    [ 2.500,  5.000) = 280027 
    [ 5.000,  7.500) = 2940 
    [ 7.500, 10.000) = 205 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     10.299 ms/op
     p(99.9900) =     32.619 ms/op
     p(99.9990) =     33.199 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.484 ms/op
                 existUser·p0.999:  5.785 ms/op
                 existUser·p0.9999: 13.376 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.422 ms/op
                 existUser·p0.9999: 15.183 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 25.481 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310048
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16535 
    [ 2.500,  5.000) = 291724 
    [ 5.000,  7.500) = 1590 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.765 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.006 ms/op
Iteration   1: 3.210 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  7.128 ms/op
                 getUser·p0.9999: 12.519 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  7.474 ms/op
                 getUser·p0.9999: 23.791 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.000 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299254
  mean =      3.206 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9231 
    [ 2.500,  5.000) = 287657 
    [ 5.000,  7.500) = 2093 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.821 ms/op
     p(99.9000) =      7.248 ms/op
     p(99.9900) =     22.776 ms/op
     p(99.9990) =     24.708 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 5.982 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.239 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.159 ms/op
                 listUser·p0.9999: 25.806 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   3: 4.179 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.952 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229349
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2586 
    [ 2.500,  5.000) = 194853 
    [ 5.000,  7.500) = 29902 
    [ 7.500, 10.000) = 1504 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     29.401 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.972 ± 1.506  ops/ms
ClientGrpc.existUser                       thrpt       3  10.680 ± 0.703  ops/ms
ClientGrpc.getUser                         thrpt       3   9.999 ± 1.057  ops/ms
ClientGrpc.listUser                        thrpt       3   7.620 ± 0.876  ops/ms
ClientGrpc.createUser                       avgt       3   3.197 ± 0.898   ms/op
ClientGrpc.existUser                        avgt       3   3.063 ± 1.151   ms/op
ClientGrpc.getUser                          avgt       3   3.276 ± 2.073   ms/op
ClientGrpc.listUser                         avgt       3   4.243 ± 0.473   ms/op
ClientGrpc.createUser                     sample  295200   3.252 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.207           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.145           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.299           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.619           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.391           ms/op
ClientGrpc.existUser                      sample  310048   3.094 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.398           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.871           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.804           ms/op
ClientGrpc.getUser                        sample  299254   3.206 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.821           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.248           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.776           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.871           ms/op
ClientGrpc.listUser                       sample  229349   4.185 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.351           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.838           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.458           ms/op
