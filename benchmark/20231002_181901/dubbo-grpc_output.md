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
# Warmup Iteration   1: 3.855 ops/ms
# Warmup Iteration   2: 8.423 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 10.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.930 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (9.848, 9.930, 10.028), stdev = 0.091
  CI (99.9%): [8.274, 11.587] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.071 ops/ms
# Warmup Iteration   2: 9.987 ops/ms
# Warmup Iteration   3: 10.276 ops/ms
Iteration   1: 10.246 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.425 ±(99.9%) 4.793 ops/ms [Average]
  (min, avg, max) = (10.246, 10.425, 10.726), stdev = 0.263
  CI (99.9%): [5.632, 15.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.151 ops/ms
# Warmup Iteration   2: 9.339 ops/ms
# Warmup Iteration   3: 9.681 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.833 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (9.772, 9.833, 9.875), stdev = 0.054
  CI (99.9%): [8.847, 10.820] (assumes normal distribution)


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
# Warmup Iteration   1: 5.183 ops/ms
# Warmup Iteration   2: 7.881 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 8.056 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.067 ±(99.9%) 1.595 ops/ms [Average]
  (min, avg, max) = (7.986, 8.067, 8.160), stdev = 0.087
  CI (99.9%): [6.472, 9.662] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.003 ms/op
Iteration   1: 3.296 ±(99.9%) 0.002 ms/op
Iteration   2: 3.256 ±(99.9%) 0.002 ms/op
Iteration   3: 3.212 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.255 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.212, 3.255, 3.296), stdev = 0.042
  CI (99.9%): [2.493, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.123 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.089, 3.123, 3.146), stdev = 0.030
  CI (99.9%): [2.578, 3.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.001 ms/op
Iteration   1: 3.335 ±(99.9%) 0.002 ms/op
Iteration   2: 3.251 ±(99.9%) 0.001 ms/op
Iteration   3: 3.265 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.284 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.251, 3.284, 3.335), stdev = 0.045
  CI (99.9%): [2.468, 4.099] (assumes normal distribution)


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
# Warmup Iteration   1: 5.688 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.025 ms/op
Iteration   1: 4.032 ±(99.9%) 0.020 ms/op
Iteration   2: 3.908 ±(99.9%) 0.040 ms/op
Iteration   3: 3.977 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.908, 3.972, 4.032), stdev = 0.062
  CI (99.9%): [2.839, 5.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.007 ms/op
Iteration   1: 3.261 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 15.882 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 3.208 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.646 ms/op
                 createUser·p0.9999: 17.007 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.290 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.380 ms/op
                 createUser·p0.9999: 18.719 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295029
  mean =      3.253 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 551 
    [ 1.250,  2.500) = 6025 
    [ 2.500,  3.750) = 250915 
    [ 3.750,  5.000) = 35565 
    [ 5.000,  6.250) = 1133 
    [ 6.250,  7.500) = 541 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.536 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     18.876 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.095 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 12.299 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 13.965 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 3.124 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.300 ms/op
                 existUser·p0.9999: 14.734 ms/op
                 existUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309009
  mean =      3.107 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1134 
    [ 1.250,  2.500) = 8340 
    [ 2.500,  3.750) = 279774 
    [ 3.750,  5.000) = 18432 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     14.157 ms/op
     p(99.9990) =     14.953 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.912 ms/op
                 getUser·p0.9999: 17.011 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 3.237 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.446 ms/op
                 getUser·p0.999:  7.353 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 3.201 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.628 ms/op
                 getUser·p0.9999: 17.434 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297140
  mean =      3.230 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6333 
    [ 2.500,  5.000) = 289111 
    [ 5.000,  7.500) = 1311 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.288 ms/op
     p(99.9900) =     20.162 ms/op
     p(99.9990) =     21.432 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.568 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.009 ms/op
Iteration   1: 3.993 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.335 ms/op
                 listUser·p0.9999: 15.532 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.148 ms/op
                 listUser·p0.9999: 16.473 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 18.636 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241281
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2211 
    [ 2.500,  3.750) = 87396 
    [ 3.750,  5.000) = 135510 
    [ 5.000,  6.250) = 10149 
    [ 6.250,  7.500) = 5038 
    [ 7.500,  8.750) = 366 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 104 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     17.686 ms/op
     p(99.9990) =     18.911 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.930 ± 1.656  ops/ms
ClientGrpc.existUser                       thrpt       3  10.425 ± 4.793  ops/ms
ClientGrpc.getUser                         thrpt       3   9.833 ± 0.987  ops/ms
ClientGrpc.listUser                        thrpt       3   8.067 ± 1.595  ops/ms
ClientGrpc.createUser                       avgt       3   3.255 ± 0.761   ms/op
ClientGrpc.existUser                        avgt       3   3.123 ± 0.545   ms/op
ClientGrpc.getUser                          avgt       3   3.284 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 1.134   ms/op
ClientGrpc.createUser                     sample  295029   3.253 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.207           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.153           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  309009   3.107 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.157           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.024           ms/op
ClientGrpc.getUser                        sample  297140   3.230 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.288           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.162           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.561           ms/op
ClientGrpc.listUser                       sample  241281   3.976 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.009           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.686           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.005           ms/op
