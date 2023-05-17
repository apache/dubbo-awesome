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
# Warmup Iteration   1: 3.781 ops/ms
# Warmup Iteration   2: 8.371 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.389 ops/ms
Iteration   3: 10.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.280 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (10.209, 10.280, 10.389), stdev = 0.096
  CI (99.9%): [8.532, 12.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ops/ms
# Warmup Iteration   2: 10.170 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.940 ops/ms
Iteration   2: 10.868 ops/ms
Iteration   3: 10.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.884 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (10.845, 10.884, 10.940), stdev = 0.050
  CI (99.9%): [9.980, 11.789] (assumes normal distribution)


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
# Warmup Iteration   1: 6.631 ops/ms
# Warmup Iteration   2: 10.032 ops/ms
# Warmup Iteration   3: 10.313 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.317 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (10.232, 10.317, 10.371), stdev = 0.075
  CI (99.9%): [8.954, 11.680] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 7.950 ops/ms
Iteration   1: 8.187 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.109 ±(99.9%) 1.593 ops/ms [Average]
  (min, avg, max) = (8.015, 8.109, 8.187), stdev = 0.087
  CI (99.9%): [6.516, 9.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.059 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.044, 3.059, 3.084), stdev = 0.021
  CI (99.9%): [2.672, 3.446] (assumes normal distribution)


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.002 ms/op
Iteration   1: 2.924 ±(99.9%) 0.001 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (2.915, 2.949, 3.009), stdev = 0.052
  CI (99.9%): [2.004, 3.894] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (2.994, 3.030, 3.065), stdev = 0.036
  CI (99.9%): [2.377, 3.683] (assumes normal distribution)


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
Iteration   1: 4.034 ±(99.9%) 0.021 ms/op
Iteration   2: 3.979 ±(99.9%) 0.009 ms/op
Iteration   3: 3.849 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.849, 3.954, 4.034), stdev = 0.095
  CI (99.9%): [2.219, 5.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.975 ms/op
                 createUser·p0.9999: 20.957 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.942 ms/op
                 createUser·p0.9999: 23.551 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.412 ms/op
                 createUser·p0.9999: 23.841 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312918
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17144 
    [ 2.500,  5.000) = 294204 
    [ 5.000,  7.500) = 1223 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.644 ms/op
     p(99.9900) =     23.649 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.986 ms/op
                 existUser·p0.9999: 13.393 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.269 ms/op
                 existUser·p0.9999: 14.467 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.936 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325717
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 626 
    [ 1.250,  2.500) = 29546 
    [ 2.500,  3.750) = 285981 
    [ 3.750,  5.000) = 8262 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     15.300 ms/op
     p(99.9990) =     17.186 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.799 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 24.464 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.657 ms/op
                 getUser·p0.999:  6.896 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311381
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15466 
    [ 2.500,  5.000) = 293906 
    [ 5.000,  7.500) = 1608 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.297 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     24.703 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 5.454 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.099 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.256 ms/op
                 listUser·p0.999:  16.333 ms/op
                 listUser·p0.9999: 18.684 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238543
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2702 
    [ 2.500,  5.000) = 208693 
    [ 5.000,  7.500) = 25205 
    [ 7.500, 10.000) = 1374 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     20.601 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.280 ± 1.748  ops/ms
ClientGrpc.existUser                       thrpt       3  10.884 ± 0.905  ops/ms
ClientGrpc.getUser                         thrpt       3  10.317 ± 1.363  ops/ms
ClientGrpc.listUser                        thrpt       3   8.109 ± 1.593  ops/ms
ClientGrpc.createUser                       avgt       3   3.059 ± 0.387   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.945   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.653   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.735   ms/op
ClientGrpc.createUser                     sample  312918   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.370           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.644           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.649           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.559           ms/op
ClientGrpc.existUser                      sample  325717   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.323           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  311381   3.082 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.297           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.097           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.773           ms/op
ClientGrpc.listUser                       sample  238543   4.024 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.776           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.103           ms/op
