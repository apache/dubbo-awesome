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
# Warmup Iteration   1: 2.315 ops/ms
# Warmup Iteration   2: 5.140 ops/ms
# Warmup Iteration   3: 6.997 ops/ms
Iteration   1: 7.233 ops/ms
Iteration   2: 7.137 ops/ms
Iteration   3: 7.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.250 ±(99.9%) 2.244 ops/ms [Average]
  (min, avg, max) = (7.137, 7.250, 7.381), stdev = 0.123
  CI (99.9%): [5.006, 9.494] (assumes normal distribution)


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
# Warmup Iteration   1: 5.054 ops/ms
# Warmup Iteration   2: 7.504 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 7.940 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.976 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (7.902, 7.976, 8.086), stdev = 0.097
  CI (99.9%): [6.202, 9.750] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ops/ms
# Warmup Iteration   2: 6.529 ops/ms
# Warmup Iteration   3: 7.243 ops/ms
Iteration   1: 7.271 ops/ms
Iteration   2: 7.255 ops/ms
Iteration   3: 7.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.236 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (7.181, 7.236, 7.271), stdev = 0.048
  CI (99.9%): [6.363, 8.108] (assumes normal distribution)


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
# Warmup Iteration   1: 3.523 ops/ms
# Warmup Iteration   2: 5.127 ops/ms
# Warmup Iteration   3: 5.748 ops/ms
Iteration   1: 5.834 ops/ms
Iteration   2: 6.026 ops/ms
Iteration   3: 5.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.839 ±(99.9%) 3.384 ops/ms [Average]
  (min, avg, max) = (5.655, 5.839, 6.026), stdev = 0.185
  CI (99.9%): [2.455, 9.223] (assumes normal distribution)


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
# Warmup Iteration   1: 6.779 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.005 ms/op
Iteration   1: 4.422 ±(99.9%) 0.031 ms/op
Iteration   2: 4.308 ±(99.9%) 0.005 ms/op
Iteration   3: 4.359 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.363 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (4.308, 4.363, 4.422), stdev = 0.057
  CI (99.9%): [3.316, 5.409] (assumes normal distribution)


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
# Warmup Iteration   1: 6.169 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.003 ms/op
Iteration   1: 3.980 ±(99.9%) 0.003 ms/op
Iteration   2: 4.075 ±(99.9%) 0.004 ms/op
Iteration   3: 4.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.020 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.980, 4.020, 4.075), stdev = 0.049
  CI (99.9%): [3.124, 4.917] (assumes normal distribution)


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
# Warmup Iteration   1: 6.514 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.003 ms/op
Iteration   1: 4.322 ±(99.9%) 0.004 ms/op
Iteration   2: 4.415 ±(99.9%) 0.004 ms/op
Iteration   3: 4.254 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.330 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (4.254, 4.330, 4.415), stdev = 0.081
  CI (99.9%): [2.850, 5.811] (assumes normal distribution)


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
# Warmup Iteration   1: 8.334 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.960 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.020 ms/op
Iteration   1: 5.663 ±(99.9%) 0.021 ms/op
Iteration   2: 5.343 ±(99.9%) 0.022 ms/op
Iteration   3: 5.490 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.499 ±(99.9%) 2.921 ms/op [Average]
  (min, avg, max) = (5.343, 5.499, 5.663), stdev = 0.160
  CI (99.9%): [2.578, 8.420] (assumes normal distribution)


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
# Warmup Iteration   1: 6.827 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.014 ms/op
Iteration   1: 4.359 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 26.331 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 4.314 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.380 ms/op
                 createUser·p0.999:  14.081 ms/op
                 createUser·p0.9999: 23.979 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 4.253 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222779
  mean =      4.308 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4306 
    [ 2.500,  5.000) = 179458 
    [ 5.000,  7.500) = 36858 
    [ 7.500, 10.000) = 1524 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.440 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     29.584 ms/op
     p(99.9990) =     31.639 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 5.509 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  12.860 ms/op
                 existUser·p0.9999: 16.340 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 4.125 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.561 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  10.991 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 4.180 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  12.966 ms/op
                 existUser·p0.9999: 20.327 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231302
  mean =      4.151 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2621 
    [ 2.500,  5.000) = 201194 
    [ 5.000,  7.500) = 25670 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     12.496 ms/op
     p(99.9900) =     19.263 ms/op
     p(99.9990) =     20.779 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 6.559 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.012 ms/op
Iteration   1: 4.179 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  14.469 ms/op
                 getUser·p0.9999: 22.349 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 4.280 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   6.879 ms/op
                 getUser·p0.999:  10.703 ms/op
                 getUser·p0.9999: 23.610 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  13.572 ms/op
                 getUser·p0.9999: 40.791 ms/op
                 getUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227110
  mean =      4.225 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 197482 
    [ 5.000, 10.000) = 29120 
    [10.000, 15.000) = 342 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     39.668 ms/op
     p(99.9990) =     41.073 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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
# Warmup Iteration   1: 8.507 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.031 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.021 ms/op
Iteration   1: 5.293 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 24.307 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 5.370 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  24.962 ms/op
                 listUser·p0.9999: 27.627 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   3: 5.280 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  21.079 ms/op
                 listUser·p0.9999: 26.307 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180715
  mean =      5.314 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 165 
    [ 2.500,  5.000) = 82224 
    [ 5.000,  7.500) = 87603 
    [ 7.500, 10.000) = 8632 
    [10.000, 12.500) = 1432 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     27.130 ms/op
     p(99.9990) =     28.546 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.250 ± 2.244  ops/ms
ClientGrpc.existUser                       thrpt       3   7.976 ± 1.774  ops/ms
ClientGrpc.getUser                         thrpt       3   7.236 ± 0.873  ops/ms
ClientGrpc.listUser                        thrpt       3   5.839 ± 3.384  ops/ms
ClientGrpc.createUser                       avgt       3   4.363 ± 1.047   ms/op
ClientGrpc.existUser                        avgt       3   4.020 ± 0.896   ms/op
ClientGrpc.getUser                          avgt       3   4.330 ± 1.480   ms/op
ClientGrpc.listUser                         avgt       3   5.499 ± 2.921   ms/op
ClientGrpc.createUser                     sample  222779   4.308 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.856           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.584           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.654           ms/op
ClientGrpc.existUser                      sample  231302   4.151 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.100           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.496           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.263           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  227110   4.225 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.838           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.104           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.562           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.074           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          39.668           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          41.157           ms/op
ClientGrpc.listUser                       sample  180715   5.314 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.436           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.782           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.955           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.130           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
