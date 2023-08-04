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
# Warmup Iteration   1: 2.147 ops/ms
# Warmup Iteration   2: 5.115 ops/ms
# Warmup Iteration   3: 6.887 ops/ms
Iteration   1: 7.375 ops/ms
Iteration   2: 7.368 ops/ms
Iteration   3: 7.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.367 ±(99.9%) 0.138 ops/ms [Average]
  (min, avg, max) = (7.360, 7.367, 7.375), stdev = 0.008
  CI (99.9%): [7.229, 7.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 7.088 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 7.921 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.883 ±(99.9%) 2.848 ops/ms [Average]
  (min, avg, max) = (7.711, 7.883, 8.016), stdev = 0.156
  CI (99.9%): [5.034, 10.731] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ops/ms
# Warmup Iteration   2: 6.658 ops/ms
# Warmup Iteration   3: 7.261 ops/ms
Iteration   1: 7.294 ops/ms
Iteration   2: 7.386 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.390 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (7.294, 7.390, 7.490), stdev = 0.098
  CI (99.9%): [5.602, 9.178] (assumes normal distribution)


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
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 5.005 ops/ms
# Warmup Iteration   3: 5.551 ops/ms
Iteration   1: 5.571 ops/ms
Iteration   2: 5.716 ops/ms
Iteration   3: 5.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.717 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (5.571, 5.717, 5.865), stdev = 0.147
  CI (99.9%): [3.039, 8.396] (assumes normal distribution)


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
# Warmup Iteration   1: 6.962 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.720 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.697 ±(99.9%) 0.023 ms/op
Iteration   1: 4.547 ±(99.9%) 0.003 ms/op
Iteration   2: 4.475 ±(99.9%) 0.004 ms/op
Iteration   3: 4.544 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.522 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (4.475, 4.522, 4.547), stdev = 0.041
  CI (99.9%): [3.779, 5.266] (assumes normal distribution)


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
# Warmup Iteration   1: 6.616 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.003 ms/op
Iteration   1: 4.058 ±(99.9%) 0.004 ms/op
Iteration   2: 4.190 ±(99.9%) 0.005 ms/op
Iteration   3: 4.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.107 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (4.058, 4.107, 4.190), stdev = 0.073
  CI (99.9%): [2.782, 5.431] (assumes normal distribution)


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
# Warmup Iteration   1: 6.907 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.330 ±(99.9%) 0.008 ms/op
Iteration   1: 4.490 ±(99.9%) 0.004 ms/op
Iteration   2: 4.385 ±(99.9%) 0.003 ms/op
Iteration   3: 4.263 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.379 ±(99.9%) 2.079 ms/op [Average]
  (min, avg, max) = (4.263, 4.379, 4.490), stdev = 0.114
  CI (99.9%): [2.301, 6.458] (assumes normal distribution)


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
# Warmup Iteration   1: 8.242 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.227 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.676 ±(99.9%) 0.030 ms/op
Iteration   1: 5.791 ±(99.9%) 0.013 ms/op
Iteration   2: 5.843 ±(99.9%) 0.022 ms/op
Iteration   3: 5.729 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.788 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (5.729, 5.788, 5.843), stdev = 0.057
  CI (99.9%): [4.748, 6.827] (assumes normal distribution)


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
# Warmup Iteration   1: 6.900 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.796 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.016 ms/op
Iteration   1: 4.589 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.488 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  12.719 ms/op
                 createUser·p0.9999: 25.169 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 4.428 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  13.124 ms/op
                 createUser·p0.9999: 25.004 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 4.437 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   7.894 ms/op
                 createUser·p0.999:  16.078 ms/op
                 createUser·p0.9999: 20.440 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214137
  mean =      4.483 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4376 
    [ 2.500,  5.000) = 159522 
    [ 5.000,  7.500) = 46349 
    [ 7.500, 10.000) = 2897 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     13.653 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.763 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 6.316 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.014 ms/op
Iteration   1: 4.297 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   6.177 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  13.034 ms/op
                 existUser·p0.9999: 16.526 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 4.164 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   7.578 ms/op
                 existUser·p0.999:  11.406 ms/op
                 existUser·p0.9999: 18.514 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   3: 4.146 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  12.153 ms/op
                 existUser·p0.9999: 23.293 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228485
  mean =      4.202 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7975 
    [ 2.500,  5.000) = 184982 
    [ 5.000,  7.500) = 32038 
    [ 7.500, 10.000) = 2709 
    [10.000, 12.500) = 593 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     20.850 ms/op
     p(99.9990) =     23.902 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 6.710 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.789 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.014 ms/op
Iteration   1: 4.517 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.455 ms/op
                 getUser·p0.99:   9.093 ms/op
                 getUser·p0.999:  14.355 ms/op
                 getUser·p0.9999: 17.121 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 4.508 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  13.550 ms/op
                 getUser·p0.9999: 19.720 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 4.404 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  13.753 ms/op
                 getUser·p0.9999: 22.372 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214366
  mean =      4.475 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3928 
    [ 2.500,  5.000) = 161994 
    [ 5.000,  7.500) = 44081 
    [ 7.500, 10.000) = 3344 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     21.249 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 8.784 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.025 ms/op
Iteration   1: 5.736 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   11.600 ms/op
                 listUser·p0.999:  20.703 ms/op
                 listUser·p0.9999: 26.439 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 5.585 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 25.292 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 5.615 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  28.901 ms/op
                 listUser·p0.9999: 31.271 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170058
  mean =      5.644 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 70634 
    [ 5.000,  7.500) = 77813 
    [ 7.500, 10.000) = 17077 
    [10.000, 12.500) = 3231 
    [12.500, 15.000) = 483 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.848 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     30.834 ms/op
     p(99.9990) =     32.352 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.367 ± 0.138  ops/ms
ClientGrpc.existUser                       thrpt       3   7.883 ± 2.848  ops/ms
ClientGrpc.getUser                         thrpt       3   7.390 ± 1.788  ops/ms
ClientGrpc.listUser                        thrpt       3   5.717 ± 2.679  ops/ms
ClientGrpc.createUser                       avgt       3   4.522 ± 0.744   ms/op
ClientGrpc.existUser                        avgt       3   4.107 ± 1.325   ms/op
ClientGrpc.getUser                          avgt       3   4.379 ± 2.079   ms/op
ClientGrpc.listUser                         avgt       3   5.788 ± 1.039   ms/op
ClientGrpc.createUser                     sample  214137   4.483 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.036           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.283           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.602           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.653           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.576           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.870           ms/op
ClientGrpc.existUser                      sample  228485   4.202 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.826           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.915           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.258           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.850           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  214366   4.475 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.873           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.324           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.634           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.812           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.249           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  170058   5.644 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.848           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.321           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.495           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.834           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.375           ms/op
