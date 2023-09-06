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
# Warmup Iteration   1: 3.314 ops/ms
# Warmup Iteration   2: 7.252 ops/ms
# Warmup Iteration   3: 8.614 ops/ms
Iteration   1: 9.092 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.160 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (9.092, 9.160, 9.218), stdev = 0.063
  CI (99.9%): [8.004, 10.316] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.146 ops/ms
# Warmup Iteration   2: 9.271 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 9.445 ops/ms
Iteration   2: 9.474 ops/ms
Iteration   3: 9.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.464 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (9.445, 9.464, 9.474), stdev = 0.016
  CI (99.9%): [9.168, 9.760] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.832 ops/ms
# Warmup Iteration   2: 8.762 ops/ms
# Warmup Iteration   3: 9.175 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 9.347 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.287 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (9.142, 9.287, 9.373), stdev = 0.127
  CI (99.9%): [6.978, 11.596] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ops/ms
# Warmup Iteration   2: 6.508 ops/ms
# Warmup Iteration   3: 6.942 ops/ms
Iteration   1: 6.959 ops/ms
Iteration   2: 6.817 ops/ms
Iteration   3: 6.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.884 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (6.817, 6.884, 6.959), stdev = 0.071
  CI (99.9%): [5.581, 8.187] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.019 ms/op
Iteration   1: 3.567 ±(99.9%) 0.003 ms/op
Iteration   2: 3.489 ±(99.9%) 0.003 ms/op
Iteration   3: 3.401 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.485 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (3.401, 3.485, 3.567), stdev = 0.083
  CI (99.9%): [1.969, 5.001] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.002 ms/op
Iteration   1: 3.346 ±(99.9%) 0.004 ms/op
Iteration   2: 3.227 ±(99.9%) 0.004 ms/op
Iteration   3: 3.272 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.282 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (3.227, 3.282, 3.346), stdev = 0.060
  CI (99.9%): [2.189, 4.374] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.878 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.007 ms/op
Iteration   1: 3.423 ±(99.9%) 0.007 ms/op
Iteration   2: 3.415 ±(99.9%) 0.003 ms/op
Iteration   3: 3.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.446 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (3.415, 3.446, 3.502), stdev = 0.048
  CI (99.9%): [2.569, 4.323] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.913 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.639 ±(99.9%) 0.012 ms/op
Iteration   1: 4.547 ±(99.9%) 0.009 ms/op
Iteration   2: 4.607 ±(99.9%) 0.010 ms/op
Iteration   3: 4.502 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.552 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (4.502, 4.552, 4.607), stdev = 0.052
  CI (99.9%): [3.595, 5.509] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.178 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.010 ms/op
Iteration   1: 3.481 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  9.505 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  12.799 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 24.861 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278667
  mean =      3.443 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10756 
    [ 2.500,  5.000) = 261912 
    [ 5.000,  7.500) = 5013 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     25.613 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
Iteration   1: 3.262 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  7.967 ms/op
                 existUser·p0.9999: 22.124 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 15.574 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.135 ms/op
                 existUser·p0.9999: 21.517 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292727
  mean =      3.280 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12859 
    [ 2.500,  5.000) = 276275 
    [ 5.000,  7.500) = 2974 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     21.618 ms/op
     p(99.9990) =     22.811 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.009 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  9.773 ms/op
                 getUser·p0.9999: 18.383 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.450 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  9.136 ms/op
                 getUser·p0.9999: 19.071 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.308 ms/op
                 getUser·p0.9999: 25.338 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 276526
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10666 
    [ 2.500,  5.000) = 260650 
    [ 5.000,  7.500) = 4367 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.421 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.838 ms/op
     p(99.9900) =     24.469 ms/op
     p(99.9990) =     25.534 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 6.118 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.588 ±(99.9%) 0.015 ms/op
Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  14.759 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 4.569 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  16.901 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   3: 4.570 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.783 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 26.149 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209304
  mean =      4.587 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 171688 
    [ 5.000,  7.500) = 32928 
    [ 7.500, 10.000) = 3491 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.685 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     26.678 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.160 ± 1.156  ops/ms
ClientGrpc.existUser                       thrpt       3   9.464 ± 0.296  ops/ms
ClientGrpc.getUser                         thrpt       3   9.287 ± 2.309  ops/ms
ClientGrpc.listUser                        thrpt       3   6.884 ± 1.303  ops/ms
ClientGrpc.createUser                       avgt       3   3.485 ± 1.516   ms/op
ClientGrpc.existUser                        avgt       3   3.282 ± 1.093   ms/op
ClientGrpc.getUser                          avgt       3   3.446 ± 0.877   ms/op
ClientGrpc.listUser                         avgt       3   4.552 ± 0.957   ms/op
ClientGrpc.createUser                     sample  278667   3.443 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.731           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.400           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.808           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.248           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  292727   3.280 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.622           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.618           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  276526   3.470 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.121           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.421           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.838           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.469           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.788           ms/op
ClientGrpc.listUser                       sample  209304   4.587 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.401           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.022           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.262           ms/op
