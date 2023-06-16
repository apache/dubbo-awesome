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
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 4.732 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.898 ops/ms
Iteration   2: 6.870 ops/ms
Iteration   3: 6.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.877 ±(99.9%) 0.339 ops/ms [Average]
  (min, avg, max) = (6.864, 6.877, 6.898), stdev = 0.019
  CI (99.9%): [6.539, 7.216] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ops/ms
# Warmup Iteration   2: 7.143 ops/ms
# Warmup Iteration   3: 7.301 ops/ms
Iteration   1: 7.552 ops/ms
Iteration   2: 7.648 ops/ms
Iteration   3: 7.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.577 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (7.532, 7.577, 7.648), stdev = 0.062
  CI (99.9%): [6.446, 8.708] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ops/ms
# Warmup Iteration   2: 6.667 ops/ms
# Warmup Iteration   3: 6.836 ops/ms
Iteration   1: 6.937 ops/ms
Iteration   2: 6.793 ops/ms
Iteration   3: 7.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.978 ±(99.9%) 3.823 ops/ms [Average]
  (min, avg, max) = (6.793, 6.978, 7.206), stdev = 0.210
  CI (99.9%): [3.156, 10.801] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.181 ops/ms
# Warmup Iteration   2: 4.736 ops/ms
# Warmup Iteration   3: 5.277 ops/ms
Iteration   1: 5.202 ops/ms
Iteration   2: 5.436 ops/ms
Iteration   3: 5.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.364 ±(99.9%) 2.565 ops/ms [Average]
  (min, avg, max) = (5.202, 5.364, 5.453), stdev = 0.141
  CI (99.9%): [2.799, 7.929] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.055 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.013 ms/op
Iteration   1: 4.695 ±(99.9%) 0.005 ms/op
Iteration   2: 4.438 ±(99.9%) 0.003 ms/op
Iteration   3: 4.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.544 ±(99.9%) 2.451 ms/op [Average]
  (min, avg, max) = (4.438, 4.544, 4.695), stdev = 0.134
  CI (99.9%): [2.093, 6.996] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.003 ms/op
Iteration   1: 4.405 ±(99.9%) 0.004 ms/op
Iteration   2: 4.623 ±(99.9%) 0.007 ms/op
Iteration   3: 4.515 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.515 ±(99.9%) 1.988 ms/op [Average]
  (min, avg, max) = (4.405, 4.515, 4.623), stdev = 0.109
  CI (99.9%): [2.526, 6.503] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.009 ms/op
Iteration   1: 4.570 ±(99.9%) 0.005 ms/op
Iteration   2: 4.512 ±(99.9%) 0.005 ms/op
Iteration   3: 4.615 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.566 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (4.512, 4.566, 4.615), stdev = 0.051
  CI (99.9%): [3.630, 5.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.241 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 6.515 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.138 ±(99.9%) 0.015 ms/op
Iteration   1: 6.073 ±(99.9%) 0.020 ms/op
Iteration   2: 5.977 ±(99.9%) 0.014 ms/op
Iteration   3: 6.110 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.053 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (5.977, 6.053, 6.110), stdev = 0.068
  CI (99.9%): [4.808, 7.299] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.015 ms/op
Iteration   1: 4.572 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  14.631 ms/op
                 createUser·p0.9999: 23.266 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 4.535 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   8.746 ms/op
                 createUser·p0.999:  13.859 ms/op
                 createUser·p0.9999: 21.101 ms/op
                 createUser·p1.00:   44.958 ms/op

Iteration   3: 4.601 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  22.774 ms/op
                 createUser·p0.9999: 24.286 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210136
  mean =      4.569 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 154415 
    [ 5.000, 10.000) = 54924 
    [10.000, 15.000) = 586 
    [15.000, 20.000) = 25 
    [20.000, 25.000) = 180 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     15.055 ms/op
     p(99.9900) =     23.559 ms/op
     p(99.9990) =     26.899 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.953 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.014 ms/op
Iteration   1: 4.323 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.210 ms/op
                 existUser·p0.99:   8.028 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 17.210 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 4.234 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   6.111 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  13.435 ms/op
                 existUser·p0.9999: 20.293 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 4.426 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.710 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   8.454 ms/op
                 existUser·p0.999:  13.412 ms/op
                 existUser·p0.9999: 36.950 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221969
  mean =      4.326 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8407 
    [ 2.500,  5.000) = 174193 
    [ 5.000,  7.500) = 35536 
    [ 7.500, 10.000) = 3042 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      8.194 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     33.712 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.127 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.974 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.016 ms/op
Iteration   1: 4.850 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   6.988 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  15.940 ms/op
                 getUser·p0.9999: 23.911 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 4.692 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 18.258 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 4.864 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   7.029 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  14.405 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 199940
  mean =      4.801 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3476 
    [ 2.500,  5.000) = 128079 
    [ 5.000,  7.500) = 62196 
    [ 7.500, 10.000) = 4964 
    [10.000, 12.500) = 780 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     32.441 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 6.741 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.275 ±(99.9%) 0.029 ms/op
Iteration   1: 6.155 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  18.263 ms/op
                 listUser·p0.9999: 24.957 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 6.259 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   12.501 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 6.031 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  23.886 ms/op
                 listUser·p0.9999: 40.023 ms/op
                 listUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 156139
  mean =      6.147 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 38184 
    [ 5.000, 10.000) = 112076 
    [10.000, 15.000) = 5365 
    [15.000, 20.000) = 326 
    [20.000, 25.000) = 139 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     20.733 ms/op
     p(99.9900) =     39.281 ms/op
     p(99.9990) =     40.071 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.877 ± 0.339  ops/ms
ClientGrpc.existUser                       thrpt       3   7.577 ± 1.131  ops/ms
ClientGrpc.getUser                         thrpt       3   6.978 ± 3.823  ops/ms
ClientGrpc.listUser                        thrpt       3   5.364 ± 2.565  ops/ms
ClientGrpc.createUser                       avgt       3   4.544 ± 2.451   ms/op
ClientGrpc.existUser                        avgt       3   4.515 ± 1.988   ms/op
ClientGrpc.getUser                          avgt       3   4.566 ± 0.936   ms/op
ClientGrpc.listUser                         avgt       3   6.053 ± 1.245   ms/op
ClientGrpc.createUser                     sample  210136   4.569 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.455           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.055           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.559           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          44.958           ms/op
ClientGrpc.existUser                      sample  221969   4.326 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.911           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.107           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.712           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.618           ms/op
ClientGrpc.getUser                        sample  199940   4.801 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.002           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.175           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.549           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.441           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.110           ms/op
ClientGrpc.listUser                       sample  156139   6.147 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.661           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.337           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.733           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.281           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.108           ms/op
