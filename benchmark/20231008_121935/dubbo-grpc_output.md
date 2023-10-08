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
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.235 ops/ms
# Warmup Iteration   3: 7.037 ops/ms
Iteration   1: 7.315 ops/ms
Iteration   2: 7.389 ops/ms
Iteration   3: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.409 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (7.315, 7.409, 7.522), stdev = 0.105
  CI (99.9%): [5.500, 9.318] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ops/ms
# Warmup Iteration   2: 7.385 ops/ms
# Warmup Iteration   3: 7.753 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.799 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.898 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (7.799, 7.898, 8.015), stdev = 0.109
  CI (99.9%): [5.912, 9.883] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.280 ops/ms
# Warmup Iteration   2: 6.847 ops/ms
# Warmup Iteration   3: 7.304 ops/ms
Iteration   1: 7.342 ops/ms
Iteration   2: 7.519 ops/ms
Iteration   3: 7.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.426 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (7.342, 7.426, 7.519), stdev = 0.089
  CI (99.9%): [5.802, 9.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.630 ops/ms
# Warmup Iteration   2: 5.253 ops/ms
# Warmup Iteration   3: 5.627 ops/ms
Iteration   1: 5.863 ops/ms
Iteration   2: 5.771 ops/ms
Iteration   3: 5.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.761 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (5.648, 5.761, 5.863), stdev = 0.108
  CI (99.9%): [3.795, 7.727] (assumes normal distribution)


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
# Warmup Iteration   1: 6.889 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.019 ms/op
Iteration   1: 4.309 ±(99.9%) 0.011 ms/op
Iteration   2: 4.194 ±(99.9%) 0.005 ms/op
Iteration   3: 4.331 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.278 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.194, 4.278, 4.331), stdev = 0.074
  CI (99.9%): [2.935, 5.620] (assumes normal distribution)


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
# Warmup Iteration   1: 6.253 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.006 ms/op
Iteration   1: 4.092 ±(99.9%) 0.011 ms/op
Iteration   2: 4.115 ±(99.9%) 0.005 ms/op
Iteration   3: 3.821 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.009 ±(99.9%) 2.985 ms/op [Average]
  (min, avg, max) = (3.821, 4.009, 4.115), stdev = 0.164
  CI (99.9%): [1.024, 6.995] (assumes normal distribution)


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
# Warmup Iteration   1: 6.735 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.009 ms/op
Iteration   1: 4.388 ±(99.9%) 0.004 ms/op
Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
Iteration   3: 4.427 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.477 ±(99.9%) 2.214 ms/op [Average]
  (min, avg, max) = (4.388, 4.477, 4.615), stdev = 0.121
  CI (99.9%): [2.263, 6.691] (assumes normal distribution)


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
# Warmup Iteration   1: 7.891 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.335 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.099 ±(99.9%) 0.018 ms/op
Iteration   1: 6.055 ±(99.9%) 0.020 ms/op
Iteration   2: 5.810 ±(99.9%) 0.020 ms/op
Iteration   3: 5.925 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.930 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (5.810, 5.930, 6.055), stdev = 0.123
  CI (99.9%): [3.694, 8.165] (assumes normal distribution)


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
# Warmup Iteration   1: 7.205 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.013 ms/op
Iteration   1: 4.143 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  14.631 ms/op
                 createUser·p0.9999: 19.524 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 4.221 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  11.488 ms/op
                 createUser·p0.9999: 19.314 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 4.178 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  18.070 ms/op
                 createUser·p0.9999: 20.426 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229592
  mean =      4.180 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6813 
    [ 2.500,  5.000) = 190104 
    [ 5.000,  7.500) = 30852 
    [ 7.500, 10.000) = 1333 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.765 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 6.031 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 22.052 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  14.117 ms/op
                 existUser·p0.9999: 23.186 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.577 ms/op
                 existUser·p0.999:  14.367 ms/op
                 existUser·p0.9999: 27.690 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242227
  mean =      3.963 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9410 
    [ 2.500,  5.000) = 211256 
    [ 5.000,  7.500) = 19714 
    [ 7.500, 10.000) = 1250 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     26.986 ms/op
     p(99.9990) =     27.994 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 6.686 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.014 ms/op
Iteration   1: 4.313 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.997 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  16.368 ms/op
                 getUser·p0.9999: 21.187 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   2: 4.449 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  16.531 ms/op
                 getUser·p0.9999: 18.803 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 4.542 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  12.933 ms/op
                 getUser·p0.9999: 22.475 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216441
  mean =      4.433 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3235 
    [ 2.500,  5.000) = 166303 
    [ 5.000,  7.500) = 44204 
    [ 7.500, 10.000) = 1823 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     15.738 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.758 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 7.877 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.153 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.747 ±(99.9%) 0.022 ms/op
Iteration   1: 5.615 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.261 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 24.467 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   2: 5.758 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   12.189 ms/op
                 listUser·p0.999:  23.593 ms/op
                 listUser·p0.9999: 43.647 ms/op
                 listUser·p1.00:   44.040 ms/op

Iteration   3: 5.627 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   11.248 ms/op
                 listUser·p0.999:  22.990 ms/op
                 listUser·p0.9999: 33.172 ms/op
                 listUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169425
  mean =      5.666 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 56850 
    [ 5.000, 10.000) = 109280 
    [10.000, 15.000) = 2490 
    [15.000, 20.000) = 536 
    [20.000, 25.000) = 181 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     21.613 ms/op
     p(99.9900) =     42.803 ms/op
     p(99.9990) =     43.995 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.409 ± 1.909  ops/ms
ClientGrpc.existUser                       thrpt       3   7.898 ± 1.985  ops/ms
ClientGrpc.getUser                         thrpt       3   7.426 ± 1.624  ops/ms
ClientGrpc.listUser                        thrpt       3   5.761 ± 1.966  ops/ms
ClientGrpc.createUser                       avgt       3   4.278 ± 1.342   ms/op
ClientGrpc.existUser                        avgt       3   4.009 ± 2.985   ms/op
ClientGrpc.getUser                          avgt       3   4.477 ± 2.214   ms/op
ClientGrpc.listUser                         avgt       3   5.930 ± 2.236   ms/op
ClientGrpc.createUser                     sample  229592   4.180 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.617           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.152           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.680           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.840           ms/op
ClientGrpc.existUser                      sample  242227   3.963 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.910           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.986           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.115           ms/op
ClientGrpc.getUser                        sample  216441   4.433 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.930           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.738           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.987           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  169425   5.666 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.147           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.266           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.682           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.613           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          42.803           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          44.040           ms/op
