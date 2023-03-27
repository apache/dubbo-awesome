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
# Warmup Iteration   1: 2.193 ops/ms
# Warmup Iteration   2: 6.026 ops/ms
# Warmup Iteration   3: 7.569 ops/ms
Iteration   1: 8.107 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.267 ±(99.9%) 2.636 ops/ms [Average]
  (min, avg, max) = (8.107, 8.267, 8.387), stdev = 0.144
  CI (99.9%): [5.631, 10.902] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.235 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 8.631 ops/ms
Iteration   1: 8.626 ops/ms
Iteration   2: 8.679 ops/ms
Iteration   3: 8.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.670 ±(99.9%) 0.735 ops/ms [Average]
  (min, avg, max) = (8.626, 8.670, 8.705), stdev = 0.040
  CI (99.9%): [7.935, 9.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ops/ms
# Warmup Iteration   2: 7.249 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 8.065 ops/ms
Iteration   2: 8.338 ops/ms
Iteration   3: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.256 ±(99.9%) 3.032 ops/ms [Average]
  (min, avg, max) = (8.065, 8.256, 8.366), stdev = 0.166
  CI (99.9%): [5.225, 11.288] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ops/ms
# Warmup Iteration   2: 5.729 ops/ms
# Warmup Iteration   3: 6.146 ops/ms
Iteration   1: 6.306 ops/ms
Iteration   2: 6.231 ops/ms
Iteration   3: 6.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.272 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (6.231, 6.272, 6.306), stdev = 0.038
  CI (99.9%): [5.581, 6.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.052 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.008 ms/op
Iteration   1: 4.027 ±(99.9%) 0.007 ms/op
Iteration   2: 3.901 ±(99.9%) 0.003 ms/op
Iteration   3: 3.833 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.920 ±(99.9%) 1.793 ms/op [Average]
  (min, avg, max) = (3.833, 3.920, 4.027), stdev = 0.098
  CI (99.9%): [2.128, 5.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.003 ms/op
Iteration   1: 3.622 ±(99.9%) 0.003 ms/op
Iteration   2: 3.614 ±(99.9%) 0.002 ms/op
Iteration   3: 3.518 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.585 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.518, 3.585, 3.622), stdev = 0.058
  CI (99.9%): [2.527, 4.642] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.022 ms/op
Iteration   1: 3.962 ±(99.9%) 0.003 ms/op
Iteration   2: 3.821 ±(99.9%) 0.004 ms/op
Iteration   3: 3.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.916 ±(99.9%) 1.503 ms/op [Average]
  (min, avg, max) = (3.821, 3.916, 3.965), stdev = 0.082
  CI (99.9%): [2.413, 5.418] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.893 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.730 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.338 ±(99.9%) 0.028 ms/op
Iteration   1: 5.737 ±(99.9%) 0.013 ms/op
Iteration   2: 5.602 ±(99.9%) 0.011 ms/op
Iteration   3: 5.379 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.573 ±(99.9%) 3.294 ms/op [Average]
  (min, avg, max) = (5.379, 5.573, 5.737), stdev = 0.181
  CI (99.9%): [2.279, 8.867] (assumes normal distribution)


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
# Warmup Iteration   1: 6.063 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.145 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  11.121 ms/op
                 createUser·p0.9999: 15.094 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  15.801 ms/op
                 createUser·p0.9999: 19.826 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.433 ms/op
                 createUser·p0.999:  17.375 ms/op
                 createUser·p0.9999: 20.112 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237934
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5442 
    [ 2.500,  5.000) = 206816 
    [ 5.000,  7.500) = 24246 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.521 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.715 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.744 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.741 ms/op
                 existUser·p0.9999: 17.850 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 3.654 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 19.865 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  11.127 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263918
  mean =      3.638 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9772 
    [ 2.500,  5.000) = 242526 
    [ 5.000,  7.500) = 10560 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.545 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 6.041 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.010 ms/op
Iteration   1: 3.916 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.081 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.885 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 16.631 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 4.284 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   6.250 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  16.191 ms/op
                 getUser·p0.9999: 21.157 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 238725
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1982 
    [ 2.500,  5.000) = 213482 
    [ 5.000,  7.500) = 20711 
    [ 7.500, 10.000) = 1625 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     13.439 ms/op
     p(99.9900) =     19.243 ms/op
     p(99.9990) =     21.669 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 9.547 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 6.802 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.339 ±(99.9%) 0.019 ms/op
Iteration   1: 5.395 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 18.949 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 5.591 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.515 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 22.235 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 5.535 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  29.368 ms/op
                 listUser·p0.9999: 40.305 ms/op
                 listUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174249
  mean =      5.506 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 71718 
    [ 5.000, 10.000) = 99461 
    [10.000, 15.000) = 2550 
    [15.000, 20.000) = 303 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     22.094 ms/op
     p(99.9900) =     38.901 ms/op
     p(99.9990) =     40.501 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.267 ± 2.636  ops/ms
ClientGrpc.existUser                       thrpt       3   8.670 ± 0.735  ops/ms
ClientGrpc.getUser                         thrpt       3   8.256 ± 3.032  ops/ms
ClientGrpc.listUser                        thrpt       3   6.272 ± 0.692  ops/ms
ClientGrpc.createUser                       avgt       3   3.920 ± 1.793   ms/op
ClientGrpc.existUser                        avgt       3   3.585 ± 1.057   ms/op
ClientGrpc.getUser                          avgt       3   3.916 ± 1.503   ms/op
ClientGrpc.listUser                         avgt       3   5.573 ± 3.294   ms/op
ClientGrpc.createUser                     sample  237934   4.033 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  263918   3.638 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.792           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.152           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.650           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.298           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.871           ms/op
ClientGrpc.getUser                        sample  238725   4.021 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.940           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.439           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.243           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  174249   5.506 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.233           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.289           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.094           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.901           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.501           ms/op
