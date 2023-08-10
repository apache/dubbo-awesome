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
# Warmup Iteration   1: 4.222 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 10.082 ops/ms
Iteration   1: 10.479 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.554 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (10.479, 10.554, 10.606), stdev = 0.067
  CI (99.9%): [9.338, 11.771] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.918 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 11.332 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.148 ops/ms
Iteration   3: 11.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.204 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (11.148, 11.204, 11.289), stdev = 0.075
  CI (99.9%): [9.842, 12.567] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.870 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.480 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.476 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (10.373, 10.476, 10.543), stdev = 0.091
  CI (99.9%): [8.823, 12.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ops/ms
# Warmup Iteration   2: 7.936 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.270 ops/ms
Iteration   3: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.209 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (8.069, 8.209, 8.288), stdev = 0.121
  CI (99.9%): [5.993, 10.425] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.058 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.050, 3.058, 3.073), stdev = 0.012
  CI (99.9%): [2.833, 3.284] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.004 ms/op
Iteration   2: 2.911 ±(99.9%) 0.004 ms/op
Iteration   3: 2.864 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (2.864, 2.897, 2.916), stdev = 0.029
  CI (99.9%): [2.374, 3.421] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.994, 3.010, 3.039), stdev = 0.025
  CI (99.9%): [2.558, 3.462] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.047 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
Iteration   1: 3.894 ±(99.9%) 0.028 ms/op
Iteration   2: 3.909 ±(99.9%) 0.016 ms/op
Iteration   3: 3.904 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.894, 3.902, 3.909), stdev = 0.008
  CI (99.9%): [3.762, 4.043] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.276 ms/op
                 createUser·p0.9999: 12.220 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.118 ms/op
                 createUser·p0.9999: 20.427 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.972 ms/op
                 createUser·p0.9999: 25.147 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317809
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26567 
    [ 2.500,  5.000) = 289349 
    [ 5.000,  7.500) = 1498 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.025 ms/op
     p(99.9900) =     24.328 ms/op
     p(99.9990) =     25.455 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.906 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.798 ms/op
                 existUser·p0.9999: 15.090 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.461 ms/op
                 existUser·p0.9999: 14.011 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.204 ms/op
                 existUser·p0.9999: 15.726 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329124
  mean =      2.916 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3417 
    [ 1.250,  2.500) = 45063 
    [ 2.500,  3.750) = 264977 
    [ 3.750,  5.000) = 13993 
    [ 5.000,  6.250) = 861 
    [ 6.250,  7.500) = 466 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.552 ms/op
     p(99.9900) =     15.337 ms/op
     p(99.9990) =     16.369 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.114 ms/op
                 getUser·p0.9999: 24.325 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.265 ms/op
                 getUser·p0.999:  10.377 ms/op
                 getUser·p0.9999: 17.964 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309735
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19890 
    [ 2.500,  5.000) = 287375 
    [ 5.000,  7.500) = 2048 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      8.442 ms/op
     p(99.9900) =     23.988 ms/op
     p(99.9990) =     24.442 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 5.133 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
Iteration   1: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.833 ms/op
                 listUser·p0.9999: 26.186 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.173 ms/op
                 listUser·p0.9999: 23.067 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.229 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241230
  mean =      3.979 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4922 
    [ 2.500,  5.000) = 212329 
    [ 5.000,  7.500) = 22097 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.332 ms/op
     p(99.9900) =     25.457 ms/op
     p(99.9990) =     26.554 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.554 ± 1.216  ops/ms
ClientGrpc.existUser                       thrpt       3  11.204 ± 1.363  ops/ms
ClientGrpc.getUser                         thrpt       3  10.476 ± 1.653  ops/ms
ClientGrpc.listUser                        thrpt       3   8.209 ± 2.216  ops/ms
ClientGrpc.createUser                       avgt       3   3.058 ± 0.225   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.523   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.452   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 0.141   ms/op
ClientGrpc.createUser                     sample  317809   3.018 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.328           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  329124   2.916 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.504           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.552           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.337           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  309735   3.097 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.615           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.442           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.510           ms/op
ClientGrpc.listUser                       sample  241230   3.979 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.332           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.457           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
