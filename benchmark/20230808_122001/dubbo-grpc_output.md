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
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.420 ops/ms
# Warmup Iteration   3: 6.996 ops/ms
Iteration   1: 7.156 ops/ms
Iteration   2: 7.302 ops/ms
Iteration   3: 7.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.278 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (7.156, 7.278, 7.376), stdev = 0.112
  CI (99.9%): [5.235, 9.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 7.581 ops/ms
Iteration   1: 7.904 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.853 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (7.780, 7.853, 7.904), stdev = 0.065
  CI (99.9%): [6.675, 9.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ops/ms
# Warmup Iteration   2: 6.929 ops/ms
# Warmup Iteration   3: 7.331 ops/ms
Iteration   1: 7.560 ops/ms
Iteration   2: 7.468 ops/ms
Iteration   3: 7.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.502 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (7.468, 7.502, 7.560), stdev = 0.050
  CI (99.9%): [6.589, 8.416] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ops/ms
# Warmup Iteration   2: 5.300 ops/ms
# Warmup Iteration   3: 5.612 ops/ms
Iteration   1: 5.741 ops/ms
Iteration   2: 5.760 ops/ms
Iteration   3: 5.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.603 ±(99.9%) 4.649 ops/ms [Average]
  (min, avg, max) = (5.309, 5.603, 5.760), stdev = 0.255
  CI (99.9%): [0.954, 10.252] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.479 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.003 ms/op
Iteration   1: 4.228 ±(99.9%) 0.003 ms/op
Iteration   2: 4.279 ±(99.9%) 0.003 ms/op
Iteration   3: 4.231 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.246 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (4.228, 4.246, 4.279), stdev = 0.028
  CI (99.9%): [3.727, 4.765] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.961 ±(99.9%) 0.004 ms/op
Iteration   2: 3.928 ±(99.9%) 0.004 ms/op
Iteration   3: 4.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.980 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.928, 3.980, 4.052), stdev = 0.064
  CI (99.9%): [2.811, 5.150] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.767 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.007 ms/op
Iteration   1: 4.262 ±(99.9%) 0.004 ms/op
Iteration   2: 4.182 ±(99.9%) 0.005 ms/op
Iteration   3: 4.205 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.216 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (4.182, 4.216, 4.262), stdev = 0.041
  CI (99.9%): [3.462, 4.971] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.405 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 6.208 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.015 ms/op
Iteration   1: 5.563 ±(99.9%) 0.016 ms/op
Iteration   2: 5.524 ±(99.9%) 0.020 ms/op
Iteration   3: 5.573 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.553 ±(99.9%) 0.474 ms/op [Average]
  (min, avg, max) = (5.524, 5.553, 5.573), stdev = 0.026
  CI (99.9%): [5.080, 6.027] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.451 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.779 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.435 ±(99.9%) 0.014 ms/op
Iteration   1: 4.300 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  14.215 ms/op
                 createUser·p0.9999: 18.827 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 4.572 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.988 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   10.785 ms/op
                 createUser·p0.999:  16.091 ms/op
                 createUser·p0.9999: 26.149 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 4.291 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.133 ms/op
                 createUser·p0.999:  13.539 ms/op
                 createUser·p0.9999: 20.465 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218959
  mean =      4.384 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7963 
    [ 2.500,  5.000) = 163593 
    [ 5.000,  7.500) = 42659 
    [ 7.500, 10.000) = 3151 
    [10.000, 12.500) = 916 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     14.812 ms/op
     p(99.9900) =     24.714 ms/op
     p(99.9990) =     27.655 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 6.731 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.015 ms/op
Iteration   1: 4.074 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  17.347 ms/op
                 existUser·p0.9999: 19.286 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  12.164 ms/op
                 existUser·p0.9999: 24.867 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.984 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  13.092 ms/op
                 existUser·p0.9999: 28.833 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239101
  mean =      4.017 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11481 
    [ 2.500,  5.000) = 198888 
    [ 5.000,  7.500) = 26056 
    [ 7.500, 10.000) = 1889 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     13.284 ms/op
     p(99.9900) =     26.021 ms/op
     p(99.9990) =     29.269 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 6.569 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.572 ±(99.9%) 0.018 ms/op
Iteration   1: 4.340 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  13.095 ms/op
                 getUser·p0.9999: 19.702 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 4.491 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.586 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 20.472 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   3: 4.577 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.873 ms/op
                 getUser·p0.99:   9.593 ms/op
                 getUser·p0.999:  17.993 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214881
  mean =      4.467 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6468 
    [ 2.500,  5.000) = 157579 
    [ 5.000,  7.500) = 44725 
    [ 7.500, 10.000) = 4790 
    [10.000, 12.500) = 951 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      9.260 ms/op
     p(99.9000) =     14.420 ms/op
     p(99.9900) =     25.248 ms/op
     p(99.9990) =     26.537 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 8.243 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.186 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.025 ms/op
Iteration   1: 5.515 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  16.497 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 5.549 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.170 ms/op
                 listUser·p0.999:  17.675 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 5.684 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  23.198 ms/op
                 listUser·p0.9999: 27.931 ms/op
                 listUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172074
  mean =      5.582 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 72929 
    [ 5.000,  7.500) = 80335 
    [ 7.500, 10.000) = 14591 
    [10.000, 12.500) = 2913 
    [12.500, 15.000) = 588 
    [15.000, 17.500) = 260 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     11.522 ms/op
     p(99.9000) =     19.069 ms/op
     p(99.9900) =     27.341 ms/op
     p(99.9990) =     30.676 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.278 ± 2.043  ops/ms
ClientGrpc.existUser                       thrpt       3   7.853 ± 1.178  ops/ms
ClientGrpc.getUser                         thrpt       3   7.502 ± 0.914  ops/ms
ClientGrpc.listUser                        thrpt       3   5.603 ± 4.649  ops/ms
ClientGrpc.createUser                       avgt       3   4.246 ± 0.519   ms/op
ClientGrpc.existUser                        avgt       3   3.980 ± 1.170   ms/op
ClientGrpc.getUser                          avgt       3   4.216 ± 0.755   ms/op
ClientGrpc.listUser                         avgt       3   5.553 ± 0.474   ms/op
ClientGrpc.createUser                     sample  218959   4.384 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.093           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.714           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.377           ms/op
ClientGrpc.existUser                      sample  239101   4.017 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.856           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.676           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.284           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.360           ms/op
ClientGrpc.getUser                        sample  214881   4.467 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.749           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.608           ms/op
ClientGrpc.listUser                       sample  172074   5.582 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.589           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.522           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.069           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.341           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.227           ms/op
