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
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 4.592 ops/ms
# Warmup Iteration   3: 6.424 ops/ms
Iteration   1: 7.041 ops/ms
Iteration   2: 6.890 ops/ms
Iteration   3: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.951 ±(99.9%) 1.455 ops/ms [Average]
  (min, avg, max) = (6.890, 6.951, 7.041), stdev = 0.080
  CI (99.9%): [5.496, 8.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.477 ops/ms
# Warmup Iteration   2: 6.854 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.721 ops/ms
Iteration   2: 7.416 ops/ms
Iteration   3: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.581 ±(99.9%) 2.811 ops/ms [Average]
  (min, avg, max) = (7.416, 7.581, 7.721), stdev = 0.154
  CI (99.9%): [4.769, 10.392] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 6.610 ops/ms
Iteration   1: 7.014 ops/ms
Iteration   2: 6.958 ops/ms
Iteration   3: 7.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.032 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (6.958, 7.032, 7.124), stdev = 0.084
  CI (99.9%): [5.492, 8.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 5.093 ops/ms
# Warmup Iteration   3: 5.624 ops/ms
Iteration   1: 5.582 ops/ms
Iteration   2: 5.531 ops/ms
Iteration   3: 5.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.577 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (5.531, 5.577, 5.617), stdev = 0.043
  CI (99.9%): [4.786, 6.367] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.817 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.002 ms/op
Iteration   1: 4.544 ±(99.9%) 0.004 ms/op
Iteration   2: 4.661 ±(99.9%) 0.005 ms/op
Iteration   3: 4.601 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.602 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (4.544, 4.602, 4.661), stdev = 0.058
  CI (99.9%): [3.535, 5.669] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.531 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.003 ms/op
Iteration   1: 4.243 ±(99.9%) 0.003 ms/op
Iteration   2: 4.174 ±(99.9%) 0.005 ms/op
Iteration   3: 4.230 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.216 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (4.174, 4.216, 4.243), stdev = 0.037
  CI (99.9%): [3.549, 4.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.341 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.007 ms/op
Iteration   1: 4.515 ±(99.9%) 0.026 ms/op
Iteration   2: 4.592 ±(99.9%) 0.004 ms/op
Iteration   3: 4.611 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.573 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (4.515, 4.573, 4.611), stdev = 0.051
  CI (99.9%): [3.645, 5.500] (assumes normal distribution)


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
# Warmup Iteration   1: 8.022 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.203 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.022 ms/op
Iteration   1: 5.697 ±(99.9%) 0.010 ms/op
Iteration   2: 5.686 ±(99.9%) 0.023 ms/op
Iteration   3: 5.825 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.736 ±(99.9%) 1.413 ms/op [Average]
  (min, avg, max) = (5.686, 5.736, 5.825), stdev = 0.077
  CI (99.9%): [4.323, 7.149] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.262 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.823 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.012 ms/op
Iteration   1: 4.494 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  14.090 ms/op
                 createUser·p0.9999: 20.722 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 4.545 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.908 ms/op
                 createUser·p0.999:  14.935 ms/op
                 createUser·p0.9999: 24.935 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 4.546 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212045
  mean =      4.528 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3822 
    [ 2.500,  5.000) = 155578 
    [ 5.000,  7.500) = 50521 
    [ 7.500, 10.000) = 1573 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.508 ms/op
     p(99.9000) =     13.532 ms/op
     p(99.9900) =     25.152 ms/op
     p(99.9990) =     26.931 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 6.407 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.013 ms/op
Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  13.636 ms/op
                 existUser·p0.9999: 25.944 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 4.258 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  10.697 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  10.818 ms/op
                 existUser·p0.9999: 31.535 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230095
  mean =      4.169 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7389 
    [ 2.500,  5.000) = 192734 
    [ 5.000,  7.500) = 28300 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     31.962 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 6.230 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.764 ±(99.9%) 0.014 ms/op
Iteration   1: 4.529 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  11.656 ms/op
                 getUser·p0.9999: 16.364 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 4.543 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.067 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  15.286 ms/op
                 getUser·p0.9999: 18.610 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 4.602 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 22.186 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210504
  mean =      4.558 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2978 
    [ 2.500,  5.000) = 154147 
    [ 5.000,  7.500) = 50797 
    [ 7.500, 10.000) = 1868 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     20.313 ms/op
     p(99.9990) =     22.629 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 8.316 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.208 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.733 ±(99.9%) 0.021 ms/op
Iteration   1: 5.693 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 23.295 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 5.749 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  22.077 ms/op
                 listUser·p0.9999: 26.431 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 5.640 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  20.554 ms/op
                 listUser·p0.9999: 25.372 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168584
  mean =      5.694 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 48183 
    [ 5.000,  7.500) = 106109 
    [ 7.500, 10.000) = 12004 
    [10.000, 12.500) = 1563 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     19.904 ms/op
     p(99.9900) =     24.974 ms/op
     p(99.9990) =     28.123 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.951 ± 1.455  ops/ms
ClientGrpc.existUser                       thrpt       3   7.581 ± 2.811  ops/ms
ClientGrpc.getUser                         thrpt       3   7.032 ± 1.540  ops/ms
ClientGrpc.listUser                        thrpt       3   5.577 ± 0.790  ops/ms
ClientGrpc.createUser                       avgt       3   4.602 ± 1.067   ms/op
ClientGrpc.existUser                        avgt       3   4.216 ± 0.667   ms/op
ClientGrpc.getUser                          avgt       3   4.573 ± 0.927   ms/op
ClientGrpc.listUser                         avgt       3   5.736 ± 1.413   ms/op
ClientGrpc.createUser                     sample  212045   4.528 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.950           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.508           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.532           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.152           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  230095   4.169 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.792           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.212           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.080           ms/op
ClientGrpc.getUser                        sample  210504   4.558 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.071           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.832           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.353           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  168584   5.694 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.423           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.904           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
