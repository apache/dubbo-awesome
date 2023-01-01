# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.507 ops/ms
# Warmup Iteration   2: 7.572 ops/ms
# Warmup Iteration   3: 8.718 ops/ms
Iteration   1: 8.800 ops/ms
Iteration   2: 8.933 ops/ms
Iteration   3: 8.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.897 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (8.800, 8.897, 8.958), stdev = 0.085
  CI (99.9%): [7.344, 10.450] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.330 ops/ms
# Warmup Iteration   2: 8.621 ops/ms
# Warmup Iteration   3: 9.265 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.300 ops/ms
Iteration   3: 9.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.343 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (9.296, 9.343, 9.434), stdev = 0.079
  CI (99.9%): [7.908, 10.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.938 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 8.873 ops/ms
Iteration   1: 8.993 ops/ms
Iteration   2: 9.079 ops/ms
Iteration   3: 9.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.052 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (8.993, 9.052, 9.083), stdev = 0.051
  CI (99.9%): [8.121, 9.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ops/ms
# Warmup Iteration   2: 6.749 ops/ms
# Warmup Iteration   3: 7.167 ops/ms
Iteration   1: 7.167 ops/ms
Iteration   2: 7.301 ops/ms
Iteration   3: 7.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.271 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (7.167, 7.271, 7.346), stdev = 0.093
  CI (99.9%): [5.574, 8.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.002 ms/op
Iteration   1: 3.559 ±(99.9%) 0.002 ms/op
Iteration   2: 3.649 ±(99.9%) 0.003 ms/op
Iteration   3: 3.603 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.604 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.559, 3.604, 3.649), stdev = 0.045
  CI (99.9%): [2.786, 4.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.003 ms/op
Iteration   1: 3.383 ±(99.9%) 0.002 ms/op
Iteration   2: 3.473 ±(99.9%) 0.002 ms/op
Iteration   3: 3.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.445 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.383, 3.445, 3.481), stdev = 0.055
  CI (99.9%): [2.450, 4.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.883 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.003 ms/op
Iteration   1: 3.559 ±(99.9%) 0.004 ms/op
Iteration   2: 3.482 ±(99.9%) 0.007 ms/op
Iteration   3: 3.579 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.540 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.482, 3.540, 3.579), stdev = 0.051
  CI (99.9%): [2.611, 4.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.529 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.534 ±(99.9%) 0.009 ms/op
Iteration   1: 4.565 ±(99.9%) 0.010 ms/op
Iteration   2: 4.408 ±(99.9%) 0.011 ms/op
Iteration   3: 4.502 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.492 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (4.408, 4.492, 4.565), stdev = 0.079
  CI (99.9%): [3.048, 5.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.127 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.007 ms/op
Iteration   1: 3.479 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.652 ms/op
                 createUser·p0.9999: 12.252 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   2: 3.522 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 16.463 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.507 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  14.400 ms/op
                 createUser·p0.9999: 23.884 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274051
  mean =      3.503 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4589 
    [ 2.500,  5.000) = 266909 
    [ 5.000,  7.500) = 2084 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     23.370 ms/op
     p(99.9990) =     23.962 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.007 ms/op
Iteration   1: 3.603 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.257 ms/op
                 existUser·p0.9999: 13.246 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   2: 3.588 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.238 ms/op
                 existUser·p0.9999: 13.929 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 14.643 ms/op
                 existUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267362
  mean =      3.590 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 357 
    [ 1.250,  2.500) = 9277 
    [ 2.500,  3.750) = 159959 
    [ 3.750,  5.000) = 92350 
    [ 5.000,  6.250) = 3892 
    [ 6.250,  7.500) = 851 
    [ 7.500,  8.750) = 421 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.710 ms/op
     p(99.9900) =     14.082 ms/op
     p(99.9990) =     15.280 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.007 ms/op
Iteration   1: 3.575 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  8.307 ms/op
                 getUser·p0.9999: 14.715 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.462 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  8.888 ms/op
                 getUser·p0.9999: 18.178 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.604 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  7.678 ms/op
                 getUser·p0.9999: 17.175 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270725
  mean =      3.546 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 7880 
    [ 2.500,  3.750) = 175710 
    [ 3.750,  5.000) = 84499 
    [ 5.000,  6.250) = 1711 
    [ 6.250,  7.500) = 303 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     17.168 ms/op
     p(99.9990) =     18.685 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.419 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.014 ms/op
Iteration   1: 4.542 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.202 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.519 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 4.554 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.355 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  16.303 ms/op
                 listUser·p0.9999: 28.605 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211534
  mean =      4.538 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 485 
    [ 2.500,  5.000) = 163750 
    [ 5.000,  7.500) = 44157 
    [ 7.500, 10.000) = 2565 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     28.894 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.897 ± 1.553  ops/ms
ClientGrpc.existUser                       thrpt       3   9.343 ± 1.435  ops/ms
ClientGrpc.getUser                         thrpt       3   9.052 ± 0.930  ops/ms
ClientGrpc.listUser                        thrpt       3   7.271 ± 1.697  ops/ms
ClientGrpc.createUser                       avgt       3   3.604 ± 0.818   ms/op
ClientGrpc.existUser                        avgt       3   3.445 ± 0.996   ms/op
ClientGrpc.getUser                          avgt       3   3.540 ± 0.929   ms/op
ClientGrpc.listUser                         avgt       3   4.492 ± 1.444   ms/op
ClientGrpc.createUser                     sample  274051   3.503 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.370           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  267362   3.590 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.780           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.710           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.082           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.565           ms/op
ClientGrpc.getUser                        sample  270725   3.546 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.783           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.454           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.168           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  211534   4.538 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.355           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.702           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
