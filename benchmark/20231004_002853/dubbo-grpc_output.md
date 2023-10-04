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
# Warmup Iteration   1: 1.400 ops/ms
# Warmup Iteration   2: 4.220 ops/ms
# Warmup Iteration   3: 6.387 ops/ms
Iteration   1: 6.272 ops/ms
Iteration   2: 6.475 ops/ms
Iteration   3: 6.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.308 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (6.177, 6.308, 6.475), stdev = 0.152
  CI (99.9%): [3.533, 9.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 6.462 ops/ms
# Warmup Iteration   3: 5.867 ops/ms
Iteration   1: 7.193 ops/ms
Iteration   2: 7.120 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.870 ±(99.9%) 9.066 ops/ms [Average]
  (min, avg, max) = (6.298, 6.870, 7.193), stdev = 0.497
  CI (99.9%): [≈ 0, 15.936] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ops/ms
# Warmup Iteration   2: 5.801 ops/ms
# Warmup Iteration   3: 6.175 ops/ms
Iteration   1: 6.753 ops/ms
Iteration   2: 6.975 ops/ms
Iteration   3: 6.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.897 ±(99.9%) 2.279 ops/ms [Average]
  (min, avg, max) = (6.753, 6.897, 6.975), stdev = 0.125
  CI (99.9%): [4.618, 9.176] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.137 ops/ms
# Warmup Iteration   2: 4.926 ops/ms
# Warmup Iteration   3: 5.219 ops/ms
Iteration   1: 5.409 ops/ms
Iteration   2: 5.302 ops/ms
Iteration   3: 5.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.311 ±(99.9%) 1.719 ops/ms [Average]
  (min, avg, max) = (5.221, 5.311, 5.409), stdev = 0.094
  CI (99.9%): [3.592, 7.029] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.552 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.359 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.805 ±(99.9%) 0.005 ms/op
Iteration   1: 4.827 ±(99.9%) 0.004 ms/op
Iteration   2: 4.782 ±(99.9%) 0.004 ms/op
Iteration   3: 4.715 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.775 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (4.715, 4.775, 4.827), stdev = 0.056
  CI (99.9%): [3.745, 5.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.003 ms/op
Iteration   1: 4.254 ±(99.9%) 0.004 ms/op
Iteration   2: 4.418 ±(99.9%) 0.004 ms/op
Iteration   3: 4.419 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.364 ±(99.9%) 1.732 ms/op [Average]
  (min, avg, max) = (4.254, 4.364, 4.419), stdev = 0.095
  CI (99.9%): [2.632, 6.096] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.669 ±(99.9%) 0.005 ms/op
Iteration   1: 4.501 ±(99.9%) 0.004 ms/op
Iteration   2: 4.508 ±(99.9%) 0.005 ms/op
Iteration   3: 4.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.504 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (4.501, 4.504, 4.508), stdev = 0.003
  CI (99.9%): [4.442, 4.567] (assumes normal distribution)


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
# Warmup Iteration   1: 8.735 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.315 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.033 ±(99.9%) 0.020 ms/op
Iteration   1: 5.934 ±(99.9%) 0.013 ms/op
Iteration   2: 5.806 ±(99.9%) 0.015 ms/op
Iteration   3: 5.857 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.866 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (5.806, 5.866, 5.934), stdev = 0.065
  CI (99.9%): [4.687, 7.045] (assumes normal distribution)


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
# Warmup Iteration   1: 7.304 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.118 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.015 ms/op
Iteration   1: 4.523 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 27.124 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   2: 4.681 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.890 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  15.356 ms/op
                 createUser·p0.9999: 26.056 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 4.716 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   9.346 ms/op
                 createUser·p0.999:  18.876 ms/op
                 createUser·p0.9999: 27.486 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207119
  mean =      4.639 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4220 
    [ 2.500,  5.000) = 143878 
    [ 5.000,  7.500) = 54868 
    [ 7.500, 10.000) = 3062 
    [10.000, 12.500) = 712 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     14.891 ms/op
     p(99.9900) =     26.964 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 6.607 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.015 ms/op
Iteration   1: 4.396 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.128 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  13.869 ms/op
                 existUser·p0.9999: 17.587 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   2: 4.304 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   4.186 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.643 ms/op
                 existUser·p0.999:  13.530 ms/op
                 existUser·p0.9999: 19.698 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 4.362 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  14.560 ms/op
                 existUser·p0.9999: 23.812 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220440
  mean =      4.354 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4918 
    [ 2.500,  5.000) = 179573 
    [ 5.000,  7.500) = 32592 
    [ 7.500, 10.000) = 2374 
    [10.000, 12.500) = 632 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     23.066 ms/op
     p(99.9990) =     24.097 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 6.681 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.821 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.014 ms/op
Iteration   1: 4.627 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.247 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  13.465 ms/op
                 getUser·p0.9999: 16.473 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 4.614 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  15.244 ms/op
                 getUser·p0.9999: 21.730 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 4.599 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  12.853 ms/op
                 getUser·p0.9999: 23.237 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208003
  mean =      4.614 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2792 
    [ 2.500,  5.000) = 147559 
    [ 5.000,  7.500) = 53889 
    [ 7.500, 10.000) = 2916 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     21.797 ms/op
     p(99.9990) =     23.653 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 8.540 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.381 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.695 ±(99.9%) 0.021 ms/op
Iteration   1: 5.705 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 19.811 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 5.812 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.659 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 25.477 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 5.949 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  23.927 ms/op
                 listUser·p0.9999: 32.559 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164861
  mean =      5.820 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 46068 
    [ 5.000,  7.500) = 100440 
    [ 7.500, 10.000) = 14441 
    [10.000, 12.500) = 2786 
    [12.500, 15.000) = 556 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     19.043 ms/op
     p(99.9900) =     31.573 ms/op
     p(99.9990) =     32.981 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.308 ± 2.775  ops/ms
ClientGrpc.existUser                       thrpt       3   6.870 ± 9.066  ops/ms
ClientGrpc.getUser                         thrpt       3   6.897 ± 2.279  ops/ms
ClientGrpc.listUser                        thrpt       3   5.311 ± 1.719  ops/ms
ClientGrpc.createUser                       avgt       3   4.775 ± 1.029   ms/op
ClientGrpc.existUser                        avgt       3   4.364 ± 1.732   ms/op
ClientGrpc.getUser                          avgt       3   4.504 ± 0.063   ms/op
ClientGrpc.listUser                         avgt       3   5.866 ± 1.179   ms/op
ClientGrpc.createUser                     sample  207119   4.639 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.437           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.891           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.964           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  220440   4.354 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.818           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.339           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.123           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.066           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.248           ms/op
ClientGrpc.getUser                        sample  208003   4.614 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.617           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.500           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.797           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.822           ms/op
ClientGrpc.listUser                       sample  164861   5.820 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.141           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.469           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.043           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
