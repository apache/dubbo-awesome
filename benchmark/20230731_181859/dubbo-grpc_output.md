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
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 4.959 ops/ms
# Warmup Iteration   3: 6.816 ops/ms
Iteration   1: 7.339 ops/ms
Iteration   2: 7.347 ops/ms
Iteration   3: 7.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.367 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (7.339, 7.367, 7.415), stdev = 0.042
  CI (99.9%): [6.606, 8.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.620 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 8.132 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 7.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.922 ±(99.9%) 3.984 ops/ms [Average]
  (min, avg, max) = (7.696, 7.922, 8.132), stdev = 0.218
  CI (99.9%): [3.938, 11.907] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ops/ms
# Warmup Iteration   2: 6.894 ops/ms
# Warmup Iteration   3: 7.242 ops/ms
Iteration   1: 7.446 ops/ms
Iteration   2: 7.496 ops/ms
Iteration   3: 7.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.426 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (7.335, 7.426, 7.496), stdev = 0.083
  CI (99.9%): [5.917, 8.934] (assumes normal distribution)


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
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 5.207 ops/ms
# Warmup Iteration   3: 5.524 ops/ms
Iteration   1: 5.473 ops/ms
Iteration   2: 5.685 ops/ms
Iteration   3: 5.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.595 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (5.473, 5.595, 5.685), stdev = 0.109
  CI (99.9%): [3.601, 7.588] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.017 ms/op
Iteration   1: 4.424 ±(99.9%) 0.003 ms/op
Iteration   2: 4.434 ±(99.9%) 0.002 ms/op
Iteration   3: 4.315 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.391 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (4.315, 4.391, 4.434), stdev = 0.066
  CI (99.9%): [3.188, 5.593] (assumes normal distribution)


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
# Warmup Iteration   1: 6.413 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.003 ms/op
Iteration   1: 4.056 ±(99.9%) 0.003 ms/op
Iteration   2: 4.139 ±(99.9%) 0.003 ms/op
Iteration   3: 4.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.086 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (4.056, 4.086, 4.139), stdev = 0.046
  CI (99.9%): [3.250, 4.922] (assumes normal distribution)


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
# Warmup Iteration   1: 7.003 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.894 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.005 ms/op
Iteration   1: 4.471 ±(99.9%) 0.004 ms/op
Iteration   2: 4.317 ±(99.9%) 0.005 ms/op
Iteration   3: 4.249 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.345 ±(99.9%) 2.079 ms/op [Average]
  (min, avg, max) = (4.249, 4.345, 4.471), stdev = 0.114
  CI (99.9%): [2.266, 6.425] (assumes normal distribution)


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
# Warmup Iteration   1: 8.465 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.409 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.021 ms/op
Iteration   1: 5.524 ±(99.9%) 0.033 ms/op
Iteration   2: 5.522 ±(99.9%) 0.021 ms/op
Iteration   3: 5.676 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.574 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (5.522, 5.574, 5.676), stdev = 0.088
  CI (99.9%): [3.964, 7.183] (assumes normal distribution)


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
# Warmup Iteration   1: 6.593 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.014 ms/op
Iteration   1: 4.369 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  11.557 ms/op
                 createUser·p0.9999: 27.678 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   2: 4.363 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.661 ms/op
                 createUser·p0.999:  12.157 ms/op
                 createUser·p0.9999: 39.059 ms/op
                 createUser·p1.00:   39.649 ms/op

Iteration   3: 4.408 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  15.137 ms/op
                 createUser·p0.9999: 28.407 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219144
  mean =      4.380 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4172 
    [ 2.500,  5.000) = 175316 
    [ 5.000,  7.500) = 37385 
    [ 7.500, 10.000) = 1479 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     38.350 ms/op
     p(99.9990) =     39.624 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 6.431 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.010 ms/op
Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   4.043 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  10.307 ms/op
                 existUser·p0.9999: 15.767 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 4.191 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  14.392 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 4.165 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.059 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  10.148 ms/op
                 existUser·p0.9999: 18.961 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231837
  mean =      4.140 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7504 
    [ 2.500,  5.000) = 196732 
    [ 5.000,  7.500) = 26341 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.624 ms/op
     p(99.9000) =     12.454 ms/op
     p(99.9900) =     20.298 ms/op
     p(99.9990) =     24.359 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 6.410 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.011 ms/op
Iteration   1: 4.454 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   8.226 ms/op
                 getUser·p0.999:  15.949 ms/op
                 getUser·p0.9999: 18.279 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   2: 4.436 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  10.698 ms/op
                 getUser·p0.9999: 18.435 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 4.280 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.508 ms/op
                 getUser·p0.999:  13.029 ms/op
                 getUser·p0.9999: 21.218 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218594
  mean =      4.389 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2039 
    [ 2.500,  5.000) = 178256 
    [ 5.000,  7.500) = 35664 
    [ 7.500, 10.000) = 2027 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     20.522 ms/op
     p(99.9990) =     21.492 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 8.543 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.354 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.019 ms/op
Iteration   1: 5.513 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 24.969 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 5.666 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.758 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 23.015 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   3: 5.618 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.417 ms/op
                 listUser·p0.999:  20.905 ms/op
                 listUser·p0.9999: 34.203 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171452
  mean =      5.598 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 51949 
    [ 5.000,  7.500) = 107379 
    [ 7.500, 10.000) = 10087 
    [10.000, 12.500) = 1443 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.012 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     18.696 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     34.706 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.367 ± 0.761  ops/ms
ClientGrpc.existUser                       thrpt       3   7.922 ± 3.984  ops/ms
ClientGrpc.getUser                         thrpt       3   7.426 ± 1.509  ops/ms
ClientGrpc.listUser                        thrpt       3   5.595 ± 1.993  ops/ms
ClientGrpc.createUser                       avgt       3   4.391 ± 1.203   ms/op
ClientGrpc.existUser                        avgt       3   4.086 ± 0.836   ms/op
ClientGrpc.getUser                          avgt       3   4.345 ± 2.079   ms/op
ClientGrpc.listUser                         avgt       3   5.574 ± 1.609   ms/op
ClientGrpc.createUser                     sample  219144   4.380 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.759           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.746           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.350           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.649           ms/op
ClientGrpc.existUser                      sample  231837   4.140 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.974           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.624           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.454           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.298           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.445           ms/op
ClientGrpc.getUser                        sample  218594   4.389 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.522           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  171452   5.598 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.313           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.256           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.128           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
