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
# Warmup Iteration   1: 2.039 ops/ms
# Warmup Iteration   2: 5.450 ops/ms
# Warmup Iteration   3: 6.743 ops/ms
Iteration   1: 7.272 ops/ms
Iteration   2: 7.097 ops/ms
Iteration   3: 7.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.148 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (7.074, 7.148, 7.272), stdev = 0.108
  CI (99.9%): [5.175, 9.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ops/ms
# Warmup Iteration   2: 7.059 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.566 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 7.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.662 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (7.561, 7.662, 7.859), stdev = 0.171
  CI (99.9%): [4.547, 10.777] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 7.254 ops/ms
Iteration   1: 7.153 ops/ms
Iteration   2: 7.333 ops/ms
Iteration   3: 7.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.308 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (7.153, 7.308, 7.437), stdev = 0.143
  CI (99.9%): [4.691, 9.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.661 ops/ms
# Warmup Iteration   2: 5.052 ops/ms
# Warmup Iteration   3: 5.378 ops/ms
Iteration   1: 5.491 ops/ms
Iteration   2: 5.680 ops/ms
Iteration   3: 5.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.626 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (5.491, 5.626, 5.708), stdev = 0.118
  CI (99.9%): [3.475, 7.778] (assumes normal distribution)


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
# Warmup Iteration   1: 6.964 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.004 ms/op
Iteration   1: 4.513 ±(99.9%) 0.006 ms/op
Iteration   2: 4.438 ±(99.9%) 0.004 ms/op
Iteration   3: 4.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.474 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (4.438, 4.474, 4.513), stdev = 0.037
  CI (99.9%): [3.792, 5.157] (assumes normal distribution)


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
# Warmup Iteration   1: 6.523 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.005 ms/op
Iteration   1: 4.167 ±(99.9%) 0.005 ms/op
Iteration   2: 4.168 ±(99.9%) 0.004 ms/op
Iteration   3: 4.110 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.148 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (4.110, 4.148, 4.168), stdev = 0.034
  CI (99.9%): [3.536, 4.761] (assumes normal distribution)


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
# Warmup Iteration   1: 6.563 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.005 ms/op
Iteration   1: 4.337 ±(99.9%) 0.003 ms/op
Iteration   2: 4.318 ±(99.9%) 0.004 ms/op
Iteration   3: 4.291 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.315 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (4.291, 4.315, 4.337), stdev = 0.023
  CI (99.9%): [3.895, 4.736] (assumes normal distribution)


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
# Warmup Iteration   1: 8.413 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.763 ±(99.9%) 0.019 ms/op
Iteration   1: 5.802 ±(99.9%) 0.020 ms/op
Iteration   2: 5.563 ±(99.9%) 0.021 ms/op
Iteration   3: 5.683 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.683 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (5.563, 5.683, 5.802), stdev = 0.120
  CI (99.9%): [3.500, 7.865] (assumes normal distribution)


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
# Warmup Iteration   1: 7.245 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.499 ±(99.9%) 0.016 ms/op
Iteration   1: 4.323 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  12.972 ms/op
                 createUser·p0.9999: 15.820 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   2: 4.425 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  12.381 ms/op
                 createUser·p0.9999: 29.345 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 4.367 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  15.734 ms/op
                 createUser·p0.9999: 22.927 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219760
  mean =      4.371 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2512 
    [ 2.500,  5.000) = 177037 
    [ 5.000,  7.500) = 36747 
    [ 7.500, 10.000) = 2655 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     28.345 ms/op
     p(99.9990) =     30.527 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 5.987 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.450 ms/op
                 existUser·p0.999:  10.583 ms/op
                 existUser·p0.9999: 18.746 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 22.692 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 4.127 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  14.312 ms/op
                 existUser·p0.9999: 24.650 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238647
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7500 
    [ 2.500,  5.000) = 207492 
    [ 5.000,  7.500) = 20901 
    [ 7.500, 10.000) = 2180 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     12.114 ms/op
     p(99.9900) =     24.056 ms/op
     p(99.9990) =     26.146 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 6.941 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.014 ms/op
Iteration   1: 4.459 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  12.802 ms/op
                 getUser·p0.9999: 18.169 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 4.374 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.682 ms/op
                 getUser·p0.999:  14.299 ms/op
                 getUser·p0.9999: 18.887 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   3: 4.485 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  14.834 ms/op
                 getUser·p0.9999: 22.147 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216256
  mean =      4.439 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2649 
    [ 2.500,  5.000) = 167472 
    [ 5.000,  7.500) = 42206 
    [ 7.500, 10.000) = 2831 
    [10.000, 12.500) = 696 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      8.609 ms/op
     p(99.9000) =     14.213 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     22.633 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 8.273 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.847 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.976 ±(99.9%) 0.027 ms/op
Iteration   1: 5.864 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  22.360 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 5.955 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  23.285 ms/op
                 listUser·p0.9999: 27.985 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   3: 5.764 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  22.153 ms/op
                 listUser·p0.9999: 27.900 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163809
  mean =      5.860 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 54238 
    [ 5.000,  7.500) = 86605 
    [ 7.500, 10.000) = 18097 
    [10.000, 12.500) = 3454 
    [12.500, 15.000) = 747 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      8.045 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     22.459 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     31.296 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.148 ± 1.972  ops/ms
ClientGrpc.existUser                       thrpt       3   7.662 ± 3.115  ops/ms
ClientGrpc.getUser                         thrpt       3   7.308 ± 2.616  ops/ms
ClientGrpc.listUser                        thrpt       3   5.626 ± 2.151  ops/ms
ClientGrpc.createUser                       avgt       3   4.474 ± 0.682   ms/op
ClientGrpc.existUser                        avgt       3   4.148 ± 0.612   ms/op
ClientGrpc.getUser                          avgt       3   4.315 ± 0.421   ms/op
ClientGrpc.listUser                         avgt       3   5.683 ± 2.183   ms/op
ClientGrpc.createUser                     sample  219760   4.371 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.061           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.331           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.877           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.638           ms/op
ClientGrpc.existUser                      sample  238647   4.022 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.897           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.114           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.056           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.444           ms/op
ClientGrpc.getUser                        sample  216256   4.439 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.163           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.609           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.213           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  163809   5.860 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.042           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.459           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
