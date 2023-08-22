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
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 4.935 ops/ms
# Warmup Iteration   3: 6.584 ops/ms
Iteration   1: 6.910 ops/ms
Iteration   2: 7.090 ops/ms
Iteration   3: 7.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.024 ±(99.9%) 1.807 ops/ms [Average]
  (min, avg, max) = (6.910, 7.024, 7.090), stdev = 0.099
  CI (99.9%): [5.218, 8.831] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ops/ms
# Warmup Iteration   2: 7.014 ops/ms
# Warmup Iteration   3: 7.532 ops/ms
Iteration   1: 7.584 ops/ms
Iteration   2: 7.611 ops/ms
Iteration   3: 7.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.556 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (7.472, 7.556, 7.611), stdev = 0.074
  CI (99.9%): [6.208, 8.904] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 6.216 ops/ms
# Warmup Iteration   3: 7.102 ops/ms
Iteration   1: 7.296 ops/ms
Iteration   2: 7.213 ops/ms
Iteration   3: 7.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.271 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (7.213, 7.271, 7.302), stdev = 0.050
  CI (99.9%): [6.365, 8.176] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ops/ms
# Warmup Iteration   2: 5.064 ops/ms
# Warmup Iteration   3: 5.536 ops/ms
Iteration   1: 5.450 ops/ms
Iteration   2: 5.663 ops/ms
Iteration   3: 5.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.548 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (5.450, 5.548, 5.663), stdev = 0.108
  CI (99.9%): [3.583, 7.512] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.541 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.824 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.758 ±(99.9%) 0.005 ms/op
Iteration   1: 4.513 ±(99.9%) 0.004 ms/op
Iteration   2: 4.507 ±(99.9%) 0.004 ms/op
Iteration   3: 4.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.523 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (4.507, 4.523, 4.550), stdev = 0.023
  CI (99.9%): [4.097, 4.949] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.416 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.005 ms/op
Iteration   1: 3.987 ±(99.9%) 0.004 ms/op
Iteration   2: 4.122 ±(99.9%) 0.004 ms/op
Iteration   3: 3.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.028 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.976, 4.028, 4.122), stdev = 0.082
  CI (99.9%): [2.540, 5.517] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.004 ms/op
Iteration   1: 4.270 ±(99.9%) 0.004 ms/op
Iteration   2: 4.362 ±(99.9%) 0.004 ms/op
Iteration   3: 4.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.338 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (4.270, 4.338, 4.383), stdev = 0.060
  CI (99.9%): [3.244, 5.432] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.170 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.369 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.094 ±(99.9%) 0.035 ms/op
Iteration   1: 5.970 ±(99.9%) 0.029 ms/op
Iteration   2: 5.772 ±(99.9%) 0.024 ms/op
Iteration   3: 5.768 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.837 ±(99.9%) 2.106 ms/op [Average]
  (min, avg, max) = (5.768, 5.837, 5.970), stdev = 0.115
  CI (99.9%): [3.731, 7.942] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.361 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.539 ±(99.9%) 0.016 ms/op
Iteration   1: 4.571 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.890 ms/op
                 createUser·p0.95:   6.578 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  13.928 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 4.554 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  13.775 ms/op
                 createUser·p0.9999: 26.867 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 4.473 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211677
  mean =      4.532 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5016 
    [ 2.500,  5.000) = 150952 
    [ 5.000,  7.500) = 50846 
    [ 7.500, 10.000) = 3876 
    [10.000, 12.500) = 654 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     28.535 ms/op
     p(99.9990) =     29.094 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.443 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.330 ±(99.9%) 0.015 ms/op
Iteration   1: 4.096 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  12.762 ms/op
                 existUser·p0.9999: 26.620 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  10.901 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 4.096 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  15.573 ms/op
                 existUser·p0.9999: 42.926 ms/op
                 existUser·p1.00:   43.123 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237000
  mean =      4.050 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 209112 
    [ 5.000, 10.000) = 27119 
    [10.000, 15.000) = 595 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 22 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     41.963 ms/op
     p(99.9990) =     43.123 ms/op
     p(99.9999) =     43.123 ms/op
    p(100.0000) =     43.123 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.657 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.016 ms/op
Iteration   1: 4.459 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   8.355 ms/op
                 getUser·p0.999:  11.932 ms/op
                 getUser·p0.9999: 21.982 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   2: 4.277 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 28.427 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 4.366 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  11.582 ms/op
                 getUser·p0.9999: 27.023 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219888
  mean =      4.366 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5545 
    [ 2.500,  5.000) = 170278 
    [ 5.000,  7.500) = 40915 
    [ 7.500, 10.000) = 2583 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.302 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.048 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.724 ±(99.9%) 0.023 ms/op
Iteration   1: 5.653 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  20.302 ms/op
                 listUser·p0.9999: 26.652 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 5.680 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.372 ms/op
                 listUser·p0.999:  18.504 ms/op
                 listUser·p0.9999: 21.508 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 5.688 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 25.673 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169200
  mean =      5.673 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206 
    [ 2.500,  5.000) = 60136 
    [ 5.000,  7.500) = 90934 
    [ 7.500, 10.000) = 14064 
    [10.000, 12.500) = 2688 
    [12.500, 15.000) = 628 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     26.283 ms/op
     p(99.9990) =     28.816 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.024 ± 1.807  ops/ms
ClientGrpc.existUser                       thrpt       3   7.556 ± 1.348  ops/ms
ClientGrpc.getUser                         thrpt       3   7.271 ± 0.906  ops/ms
ClientGrpc.listUser                        thrpt       3   5.548 ± 1.965  ops/ms
ClientGrpc.createUser                       avgt       3   4.523 ± 0.426   ms/op
ClientGrpc.existUser                        avgt       3   4.028 ± 1.489   ms/op
ClientGrpc.getUser                          avgt       3   4.338 ± 1.094   ms/op
ClientGrpc.listUser                         avgt       3   5.837 ± 2.106   ms/op
ClientGrpc.createUser                     sample  211677   4.532 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.991           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.808           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.431           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.008           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.196           ms/op
ClientGrpc.existUser                      sample  237000   4.050 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.775           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.135           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.632           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          41.963           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          43.123           ms/op
ClientGrpc.getUser                        sample  219888   4.366 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.860           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.036           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.689           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  169200   5.673 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.649           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.283           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
