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
# Warmup Iteration   1: 2.154 ops/ms
# Warmup Iteration   2: 5.703 ops/ms
# Warmup Iteration   3: 7.333 ops/ms
Iteration   1: 6.963 ops/ms
Iteration   2: 7.148 ops/ms
Iteration   3: 7.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.054 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (6.963, 7.054, 7.148), stdev = 0.092
  CI (99.9%): [5.370, 8.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.810 ops/ms
Iteration   2: 7.490 ops/ms
Iteration   3: 7.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.697 ±(99.9%) 3.263 ops/ms [Average]
  (min, avg, max) = (7.490, 7.697, 7.810), stdev = 0.179
  CI (99.9%): [4.433, 10.960] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 6.615 ops/ms
# Warmup Iteration   3: 7.129 ops/ms
Iteration   1: 7.359 ops/ms
Iteration   2: 7.577 ops/ms
Iteration   3: 7.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.492 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (7.359, 7.492, 7.577), stdev = 0.117
  CI (99.9%): [5.364, 9.620] (assumes normal distribution)


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
# Warmup Iteration   1: 3.425 ops/ms
# Warmup Iteration   2: 5.008 ops/ms
# Warmup Iteration   3: 5.563 ops/ms
Iteration   1: 5.216 ops/ms
Iteration   2: 5.251 ops/ms
Iteration   3: 5.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.240 ±(99.9%) 0.375 ops/ms [Average]
  (min, avg, max) = (5.216, 5.240, 5.253), stdev = 0.021
  CI (99.9%): [4.865, 5.615] (assumes normal distribution)


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
# Warmup Iteration   1: 7.242 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.649 ±(99.9%) 0.007 ms/op
Iteration   1: 4.636 ±(99.9%) 0.003 ms/op
Iteration   2: 4.572 ±(99.9%) 0.004 ms/op
Iteration   3: 4.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.580 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (4.532, 4.580, 4.636), stdev = 0.052
  CI (99.9%): [3.627, 5.533] (assumes normal distribution)


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
# Warmup Iteration   1: 6.400 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.012 ms/op
Iteration   1: 4.312 ±(99.9%) 0.003 ms/op
Iteration   2: 4.280 ±(99.9%) 0.005 ms/op
Iteration   3: 4.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.210 ±(99.9%) 2.751 ms/op [Average]
  (min, avg, max) = (4.037, 4.210, 4.312), stdev = 0.151
  CI (99.9%): [1.458, 6.961] (assumes normal distribution)


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
# Warmup Iteration   1: 6.635 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.845 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.012 ms/op
Iteration   1: 4.349 ±(99.9%) 0.003 ms/op
Iteration   2: 4.340 ±(99.9%) 0.014 ms/op
Iteration   3: 4.325 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.338 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (4.325, 4.338, 4.349), stdev = 0.012
  CI (99.9%): [4.122, 4.554] (assumes normal distribution)


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
# Warmup Iteration   1: 9.129 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.801 ±(99.9%) 0.022 ms/op
Iteration   1: 5.935 ±(99.9%) 0.024 ms/op
Iteration   2: 5.583 ±(99.9%) 0.020 ms/op
Iteration   3: 5.669 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.729 ±(99.9%) 3.351 ms/op [Average]
  (min, avg, max) = (5.583, 5.729, 5.935), stdev = 0.184
  CI (99.9%): [2.378, 9.081] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.101 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.014 ms/op
Iteration   1: 4.334 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  15.368 ms/op
                 createUser·p0.9999: 18.882 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 4.457 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   7.782 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 4.311 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  15.122 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219884
  mean =      4.366 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6398 
    [ 2.500,  5.000) = 169725 
    [ 5.000,  7.500) = 41445 
    [ 7.500, 10.000) = 1814 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     14.322 ms/op
     p(99.9900) =     23.529 ms/op
     p(99.9990) =     26.562 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 6.794 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.012 ms/op
Iteration   1: 4.244 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  12.166 ms/op
                 existUser·p0.9999: 17.331 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 4.214 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.652 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  16.651 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   4.035 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.782 ms/op
                 existUser·p0.999:  14.192 ms/op
                 existUser·p0.9999: 20.293 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228087
  mean =      4.207 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4530 
    [ 2.500,  5.000) = 193444 
    [ 5.000,  7.500) = 27789 
    [ 7.500, 10.000) = 1700 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     14.120 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.635 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 7.096 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.575 ±(99.9%) 0.014 ms/op
Iteration   1: 4.534 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.226 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  15.620 ms/op
                 getUser·p0.9999: 22.801 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 4.405 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.053 ms/op
                 getUser·p0.999:  12.972 ms/op
                 getUser·p0.9999: 20.013 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 4.437 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.431 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  11.868 ms/op
                 getUser·p0.9999: 20.834 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215252
  mean =      4.458 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3980 
    [ 2.500,  5.000) = 165949 
    [ 5.000,  7.500) = 42002 
    [ 7.500, 10.000) = 2574 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     13.808 ms/op
     p(99.9900) =     21.429 ms/op
     p(99.9990) =     23.452 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 9.359 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.046 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.753 ±(99.9%) 0.019 ms/op
Iteration   1: 5.810 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  16.578 ms/op
                 listUser·p0.9999: 18.906 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 5.862 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  18.937 ms/op
                 listUser·p0.9999: 27.987 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   3: 5.716 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  23.757 ms/op
                 listUser·p0.9999: 30.946 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165625
  mean =      5.796 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 47683 
    [ 5.000,  7.500) = 99774 
    [ 7.500, 10.000) = 14931 
    [10.000, 12.500) = 2432 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     28.074 ms/op
     p(99.9990) =     31.176 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.054 ± 1.685  ops/ms
ClientGrpc.existUser                       thrpt       3   7.697 ± 3.263  ops/ms
ClientGrpc.getUser                         thrpt       3   7.492 ± 2.128  ops/ms
ClientGrpc.listUser                        thrpt       3   5.240 ± 0.375  ops/ms
ClientGrpc.createUser                       avgt       3   4.580 ± 0.953   ms/op
ClientGrpc.existUser                        avgt       3   4.210 ± 2.751   ms/op
ClientGrpc.getUser                          avgt       3   4.338 ± 0.216   ms/op
ClientGrpc.listUser                         avgt       3   5.729 ± 3.351   ms/op
ClientGrpc.createUser                     sample  219884   4.366 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.561           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  228087   4.207 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.838           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.677           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.537           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.120           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  215252   4.458 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.431           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.808           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.429           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  165625   5.796 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.595           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.977           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.874           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.074           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.326           ms/op
