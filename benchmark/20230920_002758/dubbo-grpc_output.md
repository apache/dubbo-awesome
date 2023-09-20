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
# Warmup Iteration   1: 2.062 ops/ms
# Warmup Iteration   2: 4.756 ops/ms
# Warmup Iteration   3: 6.597 ops/ms
Iteration   1: 7.075 ops/ms
Iteration   2: 7.518 ops/ms
Iteration   3: 7.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.264 ±(99.9%) 4.168 ops/ms [Average]
  (min, avg, max) = (7.075, 7.264, 7.518), stdev = 0.228
  CI (99.9%): [3.096, 11.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ops/ms
# Warmup Iteration   2: 7.105 ops/ms
# Warmup Iteration   3: 7.481 ops/ms
Iteration   1: 7.653 ops/ms
Iteration   2: 7.436 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.658 ±(99.9%) 4.077 ops/ms [Average]
  (min, avg, max) = (7.436, 7.658, 7.883), stdev = 0.223
  CI (99.9%): [3.581, 11.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ops/ms
# Warmup Iteration   2: 6.731 ops/ms
# Warmup Iteration   3: 7.040 ops/ms
Iteration   1: 7.087 ops/ms
Iteration   2: 7.131 ops/ms
Iteration   3: 7.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.232 ±(99.9%) 3.904 ops/ms [Average]
  (min, avg, max) = (7.087, 7.232, 7.478), stdev = 0.214
  CI (99.9%): [3.328, 11.137] (assumes normal distribution)


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
# Warmup Iteration   1: 3.447 ops/ms
# Warmup Iteration   2: 4.673 ops/ms
# Warmup Iteration   3: 5.143 ops/ms
Iteration   1: 5.173 ops/ms
Iteration   2: 5.305 ops/ms
Iteration   3: 5.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.334 ±(99.9%) 3.245 ops/ms [Average]
  (min, avg, max) = (5.173, 5.334, 5.525), stdev = 0.178
  CI (99.9%): [2.089, 8.579] (assumes normal distribution)


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
# Warmup Iteration   1: 7.103 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.825 ±(99.9%) 0.016 ms/op
Iteration   1: 4.627 ±(99.9%) 0.003 ms/op
Iteration   2: 4.598 ±(99.9%) 0.002 ms/op
Iteration   3: 4.603 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.609 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (4.598, 4.609, 4.627), stdev = 0.016
  CI (99.9%): [4.324, 4.894] (assumes normal distribution)


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
# Warmup Iteration   1: 5.984 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.012 ms/op
Iteration   1: 4.084 ±(99.9%) 0.003 ms/op
Iteration   2: 4.194 ±(99.9%) 0.004 ms/op
Iteration   3: 4.153 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.143 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (4.084, 4.143, 4.194), stdev = 0.055
  CI (99.9%): [3.131, 5.156] (assumes normal distribution)


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
# Warmup Iteration   1: 6.674 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.004 ms/op
Iteration   1: 4.481 ±(99.9%) 0.005 ms/op
Iteration   2: 4.411 ±(99.9%) 0.007 ms/op
Iteration   3: 4.314 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.402 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (4.314, 4.402, 4.481), stdev = 0.084
  CI (99.9%): [2.873, 5.930] (assumes normal distribution)


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
# Warmup Iteration   1: 7.613 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.349 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.808 ±(99.9%) 0.020 ms/op
Iteration   1: 5.872 ±(99.9%) 0.018 ms/op
Iteration   2: 5.806 ±(99.9%) 0.021 ms/op
Iteration   3: 5.861 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.846 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (5.806, 5.846, 5.872), stdev = 0.035
  CI (99.9%): [5.201, 6.491] (assumes normal distribution)


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
# Warmup Iteration   1: 7.895 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.017 ms/op
Iteration   1: 4.452 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.380 ms/op
                 createUser·p0.999:  11.338 ms/op
                 createUser·p0.9999: 15.073 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 4.388 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.416 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.794 ms/op
                 createUser·p0.999:  12.393 ms/op
                 createUser·p0.9999: 17.091 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 4.499 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  14.004 ms/op
                 createUser·p0.9999: 21.518 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215778
  mean =      4.446 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2074 
    [ 2.500,  5.000) = 163202 
    [ 5.000,  7.500) = 47310 
    [ 7.500, 10.000) = 2652 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     20.835 ms/op
     p(99.9990) =     21.720 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 6.597 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.013 ms/op
Iteration   1: 4.391 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.111 ms/op
                 existUser·p0.99:   8.648 ms/op
                 existUser·p0.999:  12.343 ms/op
                 existUser·p0.9999: 16.857 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 4.272 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   7.938 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 4.190 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   6.078 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  13.053 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224076
  mean =      4.283 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6618 
    [ 2.500,  5.000) = 176950 
    [ 5.000,  7.500) = 36672 
    [ 7.500, 10.000) = 2926 
    [10.000, 12.500) = 693 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     36.226 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 6.459 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.015 ms/op
Iteration   1: 4.329 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   8.641 ms/op
                 getUser·p0.999:  12.695 ms/op
                 getUser·p0.9999: 21.797 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 4.326 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  12.191 ms/op
                 getUser·p0.9999: 23.371 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 4.409 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  14.474 ms/op
                 getUser·p0.9999: 31.211 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220484
  mean =      4.354 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5863 
    [ 2.500,  5.000) = 173140 
    [ 5.000,  7.500) = 37635 
    [ 7.500, 10.000) = 2946 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     31.352 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 8.630 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.995 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.867 ±(99.9%) 0.024 ms/op
Iteration   1: 5.669 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 24.885 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 5.873 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  22.956 ms/op
                 listUser·p0.9999: 27.329 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 5.833 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 25.313 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165974
  mean =      5.790 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 59707 
    [ 5.000,  7.500) = 83856 
    [ 7.500, 10.000) = 17584 
    [10.000, 12.500) = 3243 
    [12.500, 15.000) = 729 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     11.944 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     27.974 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.264 ± 4.168  ops/ms
ClientGrpc.existUser                       thrpt       3   7.658 ± 4.077  ops/ms
ClientGrpc.getUser                         thrpt       3   7.232 ± 3.904  ops/ms
ClientGrpc.listUser                        thrpt       3   5.334 ± 3.245  ops/ms
ClientGrpc.createUser                       avgt       3   4.609 ± 0.285   ms/op
ClientGrpc.existUser                        avgt       3   4.143 ± 1.012   ms/op
ClientGrpc.getUser                          avgt       3   4.402 ± 1.528   ms/op
ClientGrpc.listUser                         avgt       3   5.846 ± 0.645   ms/op
ClientGrpc.createUser                     sample  215778   4.446 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.416           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.177           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.061           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.353           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.856           ms/op
ClientGrpc.existUser                      sample  224076   4.283 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.978           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.485           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.127           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.307           ms/op
ClientGrpc.getUser                        sample  220484   4.354 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.009           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.520           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.025           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.460           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.359           ms/op
ClientGrpc.listUser                       sample  165974   5.790 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.327           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.944           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.299           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
