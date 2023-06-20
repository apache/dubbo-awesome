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
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 5.531 ops/ms
# Warmup Iteration   3: 7.163 ops/ms
Iteration   1: 7.158 ops/ms
Iteration   2: 7.241 ops/ms
Iteration   3: 7.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.172 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (7.115, 7.172, 7.241), stdev = 0.064
  CI (99.9%): [6.002, 8.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ops/ms
# Warmup Iteration   2: 7.127 ops/ms
# Warmup Iteration   3: 7.439 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.928 ±(99.9%) 0.401 ops/ms [Average]
  (min, avg, max) = (7.913, 7.928, 7.953), stdev = 0.022
  CI (99.9%): [7.527, 8.330] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ops/ms
# Warmup Iteration   2: 6.592 ops/ms
# Warmup Iteration   3: 7.038 ops/ms
Iteration   1: 7.202 ops/ms
Iteration   2: 7.276 ops/ms
Iteration   3: 7.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.343 ±(99.9%) 3.347 ops/ms [Average]
  (min, avg, max) = (7.202, 7.343, 7.550), stdev = 0.183
  CI (99.9%): [3.996, 10.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 5.317 ops/ms
# Warmup Iteration   3: 5.876 ops/ms
Iteration   1: 5.931 ops/ms
Iteration   2: 5.811 ops/ms
Iteration   3: 5.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.875 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (5.811, 5.875, 5.931), stdev = 0.060
  CI (99.9%): [4.779, 6.971] (assumes normal distribution)


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
# Warmup Iteration   1: 6.784 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.781 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.003 ms/op
Iteration   1: 4.418 ±(99.9%) 0.003 ms/op
Iteration   2: 4.174 ±(99.9%) 0.004 ms/op
Iteration   3: 4.261 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.284 ±(99.9%) 2.262 ms/op [Average]
  (min, avg, max) = (4.174, 4.284, 4.418), stdev = 0.124
  CI (99.9%): [2.022, 6.546] (assumes normal distribution)


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
# Warmup Iteration   1: 6.162 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.006 ms/op
Iteration   1: 3.910 ±(99.9%) 0.004 ms/op
Iteration   2: 3.926 ±(99.9%) 0.004 ms/op
Iteration   3: 3.915 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.917 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.910, 3.917, 3.926), stdev = 0.008
  CI (99.9%): [3.773, 4.061] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.739 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.005 ms/op
Iteration   1: 4.147 ±(99.9%) 0.005 ms/op
Iteration   2: 4.116 ±(99.9%) 0.006 ms/op
Iteration   3: 4.276 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.180 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (4.116, 4.180, 4.276), stdev = 0.085
  CI (99.9%): [2.628, 5.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.466 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.950 ±(99.9%) 0.014 ms/op
Iteration   1: 5.446 ±(99.9%) 0.014 ms/op
Iteration   2: 5.472 ±(99.9%) 0.020 ms/op
Iteration   3: 5.559 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.492 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (5.446, 5.492, 5.559), stdev = 0.059
  CI (99.9%): [4.413, 6.572] (assumes normal distribution)


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
# Warmup Iteration   1: 6.984 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.013 ms/op
Iteration   1: 4.145 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  12.380 ms/op
                 createUser·p0.9999: 30.811 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   2: 4.203 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  12.466 ms/op
                 createUser·p0.9999: 25.762 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 4.226 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   4.121 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 30.802 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229024
  mean =      4.191 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5414 
    [ 2.500,  5.000) = 193903 
    [ 5.000,  7.500) = 27743 
    [ 7.500, 10.000) = 1435 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     30.546 ms/op
     p(99.9990) =     31.373 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 6.042 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.012 ms/op
Iteration   1: 4.288 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  12.892 ms/op
                 existUser·p0.9999: 24.808 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  14.321 ms/op
                 existUser·p0.9999: 18.721 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  13.306 ms/op
                 existUser·p0.9999: 21.382 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230926
  mean =      4.156 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7075 
    [ 2.500,  5.000) = 191400 
    [ 5.000,  7.500) = 30350 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     13.519 ms/op
     p(99.9900) =     23.715 ms/op
     p(99.9990) =     25.146 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 6.206 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.013 ms/op
Iteration   1: 4.446 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.097 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  16.258 ms/op
                 getUser·p0.9999: 23.002 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 4.281 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.588 ms/op
                 getUser·p0.999:  11.489 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 4.324 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  12.355 ms/op
                 getUser·p0.9999: 25.907 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220807
  mean =      4.349 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4501 
    [ 2.500,  5.000) = 174987 
    [ 5.000,  7.500) = 38730 
    [ 7.500, 10.000) = 1986 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.175 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 7.296 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.992 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.020 ms/op
Iteration   1: 5.528 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  15.903 ms/op
                 listUser·p0.9999: 18.179 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 5.658 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 21.409 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 5.514 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.438 ms/op
                 listUser·p0.999:  21.727 ms/op
                 listUser·p0.9999: 33.817 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172329
  mean =      5.566 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 64602 
    [ 5.000,  7.500) = 92313 
    [ 7.500, 10.000) = 12513 
    [10.000, 12.500) = 2020 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     33.532 ms/op
     p(99.9990) =     34.031 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.172 ± 1.169  ops/ms
ClientGrpc.existUser                       thrpt       3   7.928 ± 0.401  ops/ms
ClientGrpc.getUser                         thrpt       3   7.343 ± 3.347  ops/ms
ClientGrpc.listUser                        thrpt       3   5.875 ± 1.096  ops/ms
ClientGrpc.createUser                       avgt       3   4.284 ± 2.262   ms/op
ClientGrpc.existUser                        avgt       3   3.917 ± 0.144   ms/op
ClientGrpc.getUser                          avgt       3   4.180 ± 1.552   ms/op
ClientGrpc.listUser                         avgt       3   5.492 ± 1.079   ms/op
ClientGrpc.createUser                     sample  229024   4.191 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.029           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.217           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.546           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.161           ms/op
ClientGrpc.existUser                      sample  230926   4.156 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.969           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.715           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.297           ms/op
ClientGrpc.getUser                        sample  220807   4.349 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.452           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.264           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  172329   5.566 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.614           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.682           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.079           ms/op
