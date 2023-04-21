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
# Warmup Iteration   1: 3.196 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 8.897 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.560 ±(99.9%) 5.395 ops/ms [Average]
  (min, avg, max) = (8.345, 8.560, 8.897), stdev = 0.296
  CI (99.9%): [3.165, 13.955] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.661 ops/ms
# Warmup Iteration   2: 9.584 ops/ms
# Warmup Iteration   3: 9.908 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 10.250 ops/ms
Iteration   3: 10.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.200 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (10.129, 10.200, 10.250), stdev = 0.063
  CI (99.9%): [9.044, 11.355] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.682 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 9.142 ops/ms
Iteration   1: 9.203 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 8.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.132 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (8.892, 9.132, 9.299), stdev = 0.213
  CI (99.9%): [5.249, 13.014] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 6.324 ops/ms
# Warmup Iteration   3: 6.413 ops/ms
Iteration   1: 6.461 ops/ms
Iteration   2: 6.592 ops/ms
Iteration   3: 6.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.485 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (6.401, 6.485, 6.592), stdev = 0.098
  CI (99.9%): [4.701, 8.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.802 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.003 ms/op
Iteration   1: 3.665 ±(99.9%) 0.002 ms/op
Iteration   2: 3.670 ±(99.9%) 0.003 ms/op
Iteration   3: 3.602 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.646 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.602, 3.646, 3.670), stdev = 0.038
  CI (99.9%): [2.957, 4.335] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 5.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.004 ms/op
Iteration   1: 3.380 ±(99.9%) 0.003 ms/op
Iteration   2: 3.449 ±(99.9%) 0.002 ms/op
Iteration   3: 3.406 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.411 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.380, 3.411, 3.449), stdev = 0.035
  CI (99.9%): [2.779, 4.044] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.004 ms/op
Iteration   1: 3.567 ±(99.9%) 0.003 ms/op
Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
Iteration   3: 3.544 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.571 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.544, 3.571, 3.601), stdev = 0.029
  CI (99.9%): [3.048, 4.094] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 7.224 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.823 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.027 ms/op
Iteration   1: 4.597 ±(99.9%) 0.012 ms/op
Iteration   2: 4.552 ±(99.9%) 0.010 ms/op
Iteration   3: 4.582 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.577 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (4.552, 4.577, 4.597), stdev = 0.023
  CI (99.9%): [4.155, 4.998] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.010 ms/op
Iteration   1: 3.674 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 18.402 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.665 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  9.906 ms/op
                 createUser·p0.9999: 14.565 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 3.753 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.417 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.109 ms/op
                 createUser·p0.99:   7.497 ms/op
                 createUser·p0.999:  15.100 ms/op
                 createUser·p0.9999: 20.299 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259842
  mean =      3.697 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6209 
    [ 2.500,  5.000) = 241711 
    [ 5.000,  7.500) = 10100 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.677 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.437 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  11.055 ms/op
                 existUser·p0.9999: 16.987 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.793 ms/op
                 existUser·p0.999:  12.879 ms/op
                 existUser·p0.9999: 16.297 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   3: 3.416 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  9.636 ms/op
                 existUser·p0.9999: 18.740 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277646
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9593 
    [ 2.500,  5.000) = 261174 
    [ 5.000,  7.500) = 5522 
    [ 7.500, 10.000) = 960 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     20.083 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.840 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.011 ms/op
Iteration   1: 3.787 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  12.045 ms/op
                 getUser·p0.9999: 17.600 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.793 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  15.672 ms/op
                 getUser·p0.9999: 20.647 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.718 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.123 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  11.320 ms/op
                 getUser·p0.9999: 18.822 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254991
  mean =      3.766 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16325 
    [ 2.500,  5.000) = 218466 
    [ 5.000,  7.500) = 17793 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.219 ms/op
     p(99.9990) =     20.888 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.484 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.016 ms/op
Iteration   1: 4.569 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 4.434 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.676 ms/op
                 listUser·p0.9999: 20.623 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.498 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.321 ms/op
                 listUser·p0.9999: 26.659 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213152
  mean =      4.500 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1577 
    [ 2.500,  5.000) = 163984 
    [ 5.000,  7.500) = 41867 
    [ 7.500, 10.000) = 4531 
    [10.000, 12.500) = 627 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     15.792 ms/op
     p(99.9900) =     23.509 ms/op
     p(99.9990) =     27.021 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.560 ± 5.395  ops/ms
ClientGrpc.existUser                       thrpt       3  10.200 ± 1.156  ops/ms
ClientGrpc.getUser                         thrpt       3   9.132 ± 3.883  ops/ms
ClientGrpc.listUser                        thrpt       3   6.485 ± 1.783  ops/ms
ClientGrpc.createUser                       avgt       3   3.646 ± 0.689   ms/op
ClientGrpc.existUser                        avgt       3   3.411 ± 0.633   ms/op
ClientGrpc.getUser                          avgt       3   3.571 ± 0.523   ms/op
ClientGrpc.listUser                         avgt       3   4.577 ± 0.421   ms/op
ClientGrpc.createUser                     sample  259842   3.697 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.417           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.783           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.713           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.268           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.808           ms/op
ClientGrpc.existUser                      sample  277646   3.455 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.169           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  254991   3.766 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.692           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.414           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.058           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.219           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.972           ms/op
ClientGrpc.listUser                       sample  213152   4.500 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.700           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.792           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
