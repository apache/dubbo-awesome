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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 4.777 ops/ms
# Warmup Iteration   3: 6.623 ops/ms
Iteration   1: 7.005 ops/ms
Iteration   2: 7.028 ops/ms
Iteration   3: 7.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.031 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (7.005, 7.031, 7.061), stdev = 0.028
  CI (99.9%): [6.519, 7.543] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 7.038 ops/ms
Iteration   1: 7.604 ops/ms
Iteration   2: 7.234 ops/ms
Iteration   3: 7.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.384 ±(99.9%) 3.550 ops/ms [Average]
  (min, avg, max) = (7.234, 7.384, 7.604), stdev = 0.195
  CI (99.9%): [3.834, 10.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ops/ms
# Warmup Iteration   2: 6.624 ops/ms
# Warmup Iteration   3: 7.001 ops/ms
Iteration   1: 7.120 ops/ms
Iteration   2: 7.281 ops/ms
Iteration   3: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.150 ±(99.9%) 2.185 ops/ms [Average]
  (min, avg, max) = (7.047, 7.150, 7.281), stdev = 0.120
  CI (99.9%): [4.965, 9.334] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 4.886 ops/ms
# Warmup Iteration   3: 5.697 ops/ms
Iteration   1: 5.674 ops/ms
Iteration   2: 5.647 ops/ms
Iteration   3: 5.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.614 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (5.522, 5.614, 5.674), stdev = 0.081
  CI (99.9%): [4.134, 7.094] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.093 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.704 ±(99.9%) 0.009 ms/op
Iteration   1: 4.649 ±(99.9%) 0.004 ms/op
Iteration   2: 4.551 ±(99.9%) 0.004 ms/op
Iteration   3: 4.416 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.539 ±(99.9%) 2.138 ms/op [Average]
  (min, avg, max) = (4.416, 4.539, 4.649), stdev = 0.117
  CI (99.9%): [2.400, 6.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.844 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.003 ms/op
Iteration   1: 4.194 ±(99.9%) 0.005 ms/op
Iteration   2: 4.373 ±(99.9%) 0.004 ms/op
Iteration   3: 4.184 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.250 ±(99.9%) 1.940 ms/op [Average]
  (min, avg, max) = (4.184, 4.250, 4.373), stdev = 0.106
  CI (99.9%): [2.310, 6.190] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.669 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.642 ±(99.9%) 0.007 ms/op
Iteration   1: 4.473 ±(99.9%) 0.003 ms/op
Iteration   2: 4.649 ±(99.9%) 0.003 ms/op
Iteration   3: 4.587 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.570 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (4.473, 4.570, 4.649), stdev = 0.089
  CI (99.9%): [2.940, 6.199] (assumes normal distribution)


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
# Warmup Iteration   1: 9.130 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.777 ±(99.9%) 0.016 ms/op
Iteration   1: 5.638 ±(99.9%) 0.019 ms/op
Iteration   2: 5.857 ±(99.9%) 0.025 ms/op
Iteration   3: 5.756 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.750 ±(99.9%) 2.005 ms/op [Average]
  (min, avg, max) = (5.638, 5.750, 5.857), stdev = 0.110
  CI (99.9%): [3.745, 7.755] (assumes normal distribution)


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
# Warmup Iteration   1: 6.619 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.014 ms/op
Iteration   1: 4.477 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.969 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  12.576 ms/op
                 createUser·p0.9999: 15.326 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 4.577 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   7.715 ms/op
                 createUser·p0.999:  15.205 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 4.398 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.074 ms/op
                 createUser·p0.999:  12.854 ms/op
                 createUser·p0.9999: 27.114 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214121
  mean =      4.483 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2975 
    [ 2.500,  5.000) = 162521 
    [ 5.000,  7.500) = 46073 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 535 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     26.193 ms/op
     p(99.9990) =     27.450 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 6.693 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.015 ms/op
Iteration   1: 4.447 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  14.854 ms/op
                 existUser·p0.9999: 19.032 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 4.395 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 20.598 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 4.386 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   8.069 ms/op
                 existUser·p0.999:  15.008 ms/op
                 existUser·p0.9999: 21.336 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 217672
  mean =      4.409 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5682 
    [ 2.500,  5.000) = 167511 
    [ 5.000,  7.500) = 40423 
    [ 7.500, 10.000) = 2844 
    [10.000, 12.500) = 770 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     14.145 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.931 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 6.835 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.825 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.014 ms/op
Iteration   1: 4.677 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   7.957 ms/op
                 getUser·p0.999:  13.926 ms/op
                 getUser·p0.9999: 20.785 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 4.398 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  13.056 ms/op
                 getUser·p0.9999: 23.387 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 4.475 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  12.697 ms/op
                 getUser·p0.9999: 24.510 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212794
  mean =      4.514 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 154922 
    [ 5.000,  7.500) = 51186 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     24.174 ms/op
     p(99.9990) =     25.706 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 8.707 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.410 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.985 ±(99.9%) 0.021 ms/op
Iteration   1: 5.876 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  18.218 ms/op
                 listUser·p0.9999: 19.482 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 5.769 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 25.341 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   3: 5.962 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  21.409 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163621
  mean =      5.868 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 41470 
    [ 5.000,  7.500) = 105164 
    [ 7.500, 10.000) = 13856 
    [10.000, 12.500) = 2288 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.553 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     18.887 ms/op
     p(99.9900) =     23.925 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.031 ± 0.512  ops/ms
ClientGrpc.existUser                       thrpt       3   7.384 ± 3.550  ops/ms
ClientGrpc.getUser                         thrpt       3   7.150 ± 2.185  ops/ms
ClientGrpc.listUser                        thrpt       3   5.614 ± 1.480  ops/ms
ClientGrpc.createUser                       avgt       3   4.539 ± 2.138   ms/op
ClientGrpc.existUser                        avgt       3   4.250 ± 1.940   ms/op
ClientGrpc.getUser                          avgt       3   4.570 ± 1.629   ms/op
ClientGrpc.listUser                         avgt       3   5.750 ± 2.005   ms/op
ClientGrpc.createUser                     sample  214121   4.483 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.823           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.648           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.193           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  217672   4.409 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.962           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.145           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.447           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.479           ms/op
ClientGrpc.getUser                        sample  212794   4.514 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.139           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.160           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.651           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.140           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.174           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  163621   5.868 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.945           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.887           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.925           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.196           ms/op
