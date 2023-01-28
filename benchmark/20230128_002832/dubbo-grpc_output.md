# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.372 ops/ms
# Warmup Iteration   2: 5.513 ops/ms
# Warmup Iteration   3: 7.023 ops/ms
Iteration   1: 7.213 ops/ms
Iteration   2: 7.215 ops/ms
Iteration   3: 7.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.191 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (7.144, 7.191, 7.215), stdev = 0.040
  CI (99.9%): [6.453, 7.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ops/ms
# Warmup Iteration   2: 7.402 ops/ms
# Warmup Iteration   3: 7.621 ops/ms
Iteration   1: 7.618 ops/ms
Iteration   2: 7.506 ops/ms
Iteration   3: 7.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.458 ±(99.9%) 3.420 ops/ms [Average]
  (min, avg, max) = (7.252, 7.458, 7.618), stdev = 0.187
  CI (99.9%): [4.039, 10.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.361 ops/ms
# Warmup Iteration   2: 7.105 ops/ms
# Warmup Iteration   3: 7.558 ops/ms
Iteration   1: 7.785 ops/ms
Iteration   2: 7.708 ops/ms
Iteration   3: 7.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.694 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (7.589, 7.694, 7.785), stdev = 0.099
  CI (99.9%): [5.896, 9.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ops/ms
# Warmup Iteration   2: 5.418 ops/ms
# Warmup Iteration   3: 5.951 ops/ms
Iteration   1: 5.849 ops/ms
Iteration   2: 5.829 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.830 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (5.812, 5.830, 5.849), stdev = 0.019
  CI (99.9%): [5.485, 6.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.462 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.621 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.020 ms/op
Iteration   1: 4.496 ±(99.9%) 0.003 ms/op
Iteration   2: 4.397 ±(99.9%) 0.003 ms/op
Iteration   3: 4.511 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.468 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (4.397, 4.468, 4.511), stdev = 0.062
  CI (99.9%): [3.337, 5.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.120 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.003 ms/op
Iteration   1: 4.265 ±(99.9%) 0.004 ms/op
Iteration   2: 4.357 ±(99.9%) 0.003 ms/op
Iteration   3: 4.330 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.317 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (4.265, 4.317, 4.357), stdev = 0.047
  CI (99.9%): [3.458, 5.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.560 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.671 ±(99.9%) 0.004 ms/op
Iteration   1: 4.533 ±(99.9%) 0.005 ms/op
Iteration   2: 4.590 ±(99.9%) 0.003 ms/op
Iteration   3: 4.690 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.604 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (4.533, 4.604, 4.690), stdev = 0.079
  CI (99.9%): [3.157, 6.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.146 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.829 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.554 ±(99.9%) 0.026 ms/op
Iteration   1: 5.466 ±(99.9%) 0.014 ms/op
Iteration   2: 5.322 ±(99.9%) 0.028 ms/op
Iteration   3: 5.471 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.419 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (5.322, 5.419, 5.471), stdev = 0.085
  CI (99.9%): [3.873, 6.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.724 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.656 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.013 ms/op
Iteration   1: 4.383 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.670 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  12.976 ms/op
                 createUser·p0.9999: 20.882 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 4.144 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 22.586 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 4.426 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 25.912 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222503
  mean =      4.314 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3614 
    [ 2.500,  5.000) = 171901 
    [ 5.000,  7.500) = 45266 
    [ 7.500, 10.000) = 1312 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     24.977 ms/op
     p(99.9990) =     26.407 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.012 ms/op
Iteration   1: 4.353 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   5.921 ms/op
                 existUser·p0.99:   7.433 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 15.444 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   2: 4.360 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  10.802 ms/op
                 existUser·p0.9999: 18.099 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 4.204 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 23.491 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223053
  mean =      4.305 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5026 
    [ 2.500,  5.000) = 170028 
    [ 5.000,  7.500) = 45773 
    [ 7.500, 10.000) = 1808 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     11.337 ms/op
     p(99.9900) =     22.209 ms/op
     p(99.9990) =     24.044 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.751 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.014 ms/op
Iteration   1: 4.475 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 16.414 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   2: 4.477 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  10.805 ms/op
                 getUser·p0.9999: 17.193 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 4.384 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  9.766 ms/op
                 getUser·p0.9999: 18.963 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215919
  mean =      4.445 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 3849 
    [ 2.500,  3.750) = 49507 
    [ 3.750,  5.000) = 105826 
    [ 5.000,  6.250) = 49783 
    [ 6.250,  7.500) = 5052 
    [ 7.500,  8.750) = 1129 
    [ 8.750, 10.000) = 401 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     17.808 ms/op
     p(99.9990) =     19.361 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.557 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.798 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.213 ±(99.9%) 0.018 ms/op
Iteration   1: 5.148 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  16.725 ms/op
                 listUser·p0.9999: 19.581 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 5.188 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.788 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  18.449 ms/op
                 listUser·p0.9999: 22.554 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 5.405 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.377 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  20.181 ms/op
                 listUser·p0.9999: 39.279 ms/op
                 listUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183060
  mean =      5.245 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 95265 
    [ 5.000, 10.000) = 85819 
    [10.000, 15.000) = 1643 
    [15.000, 20.000) = 234 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     17.791 ms/op
     p(99.9900) =     35.697 ms/op
     p(99.9990) =     39.999 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.191 ± 0.738  ops/ms
ClientGrpc.existUser                       thrpt       3   7.458 ± 3.420  ops/ms
ClientGrpc.getUser                         thrpt       3   7.694 ± 1.799  ops/ms
ClientGrpc.listUser                        thrpt       3   5.830 ± 0.345  ops/ms
ClientGrpc.createUser                       avgt       3   4.468 ± 1.132   ms/op
ClientGrpc.existUser                        avgt       3   4.317 ± 0.860   ms/op
ClientGrpc.getUser                          avgt       3   4.604 ± 1.447   ms/op
ClientGrpc.listUser                         avgt       3   5.419 ± 1.546   ms/op
ClientGrpc.createUser                     sample  222503   4.314 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.184           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.944           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.977           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  223053   4.305 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.953           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.337           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.209           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.494           ms/op
ClientGrpc.getUser                        sample  215919   4.445 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.307           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.518           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.808           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.399           ms/op
ClientGrpc.listUser                       sample  183060   5.245 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.608           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.979           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.109           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.791           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.697           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.108           ms/op
