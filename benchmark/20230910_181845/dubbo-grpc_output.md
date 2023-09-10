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
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 6.664 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.349 ops/ms
Iteration   2: 8.623 ops/ms
Iteration   3: 8.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.606 ±(99.9%) 4.550 ops/ms [Average]
  (min, avg, max) = (8.349, 8.606, 8.847), stdev = 0.249
  CI (99.9%): [4.056, 13.156] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.082 ops/ms
# Warmup Iteration   2: 8.665 ops/ms
# Warmup Iteration   3: 9.036 ops/ms
Iteration   1: 9.030 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.081 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (9.030, 9.081, 9.171), stdev = 0.078
  CI (99.9%): [7.654, 10.509] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.609 ops/ms
# Warmup Iteration   2: 8.180 ops/ms
# Warmup Iteration   3: 8.315 ops/ms
Iteration   1: 8.759 ops/ms
Iteration   2: 8.763 ops/ms
Iteration   3: 8.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.767 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (8.759, 8.767, 8.780), stdev = 0.011
  CI (99.9%): [8.558, 8.977] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ops/ms
# Warmup Iteration   2: 6.161 ops/ms
# Warmup Iteration   3: 6.689 ops/ms
Iteration   1: 6.687 ops/ms
Iteration   2: 6.672 ops/ms
Iteration   3: 6.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.689 ±(99.9%) 0.342 ops/ms [Average]
  (min, avg, max) = (6.672, 6.689, 6.709), stdev = 0.019
  CI (99.9%): [6.347, 7.031] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.455 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.013 ms/op
Iteration   1: 3.628 ±(99.9%) 0.005 ms/op
Iteration   2: 3.558 ±(99.9%) 0.003 ms/op
Iteration   3: 3.600 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.596 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (3.558, 3.596, 3.628), stdev = 0.035
  CI (99.9%): [2.954, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.774 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.003 ms/op
Iteration   1: 3.481 ±(99.9%) 0.003 ms/op
Iteration   2: 3.321 ±(99.9%) 0.003 ms/op
Iteration   3: 3.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.404 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (3.321, 3.404, 3.481), stdev = 0.080
  CI (99.9%): [1.948, 4.860] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.004 ms/op
Iteration   1: 3.650 ±(99.9%) 0.005 ms/op
Iteration   2: 3.552 ±(99.9%) 0.003 ms/op
Iteration   3: 3.548 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.583 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.548, 3.583, 3.650), stdev = 0.058
  CI (99.9%): [2.529, 4.637] (assumes normal distribution)


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
# Warmup Iteration   1: 6.633 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.014 ms/op
Iteration   1: 4.710 ±(99.9%) 0.011 ms/op
Iteration   2: 4.764 ±(99.9%) 0.014 ms/op
Iteration   3: 4.739 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.738 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (4.710, 4.738, 4.764), stdev = 0.027
  CI (99.9%): [4.241, 5.234] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.271 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.008 ms/op
Iteration   1: 3.579 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  10.036 ms/op
                 createUser·p0.9999: 14.305 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 3.599 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  10.423 ms/op
                 createUser·p0.9999: 16.550 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  15.473 ms/op
                 createUser·p0.9999: 33.227 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267958
  mean =      3.582 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7547 
    [ 2.500,  5.000) = 254419 
    [ 5.000,  7.500) = 5252 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     10.405 ms/op
     p(99.9900) =     32.840 ms/op
     p(99.9990) =     33.368 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.008 ms/op
Iteration   1: 3.483 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.751 ms/op
                 existUser·p0.9999: 14.153 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 3.474 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.630 ms/op
                 existUser·p0.999:  14.940 ms/op
                 existUser·p0.9999: 43.647 ms/op
                 existUser·p1.00:   44.827 ms/op

Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  11.461 ms/op
                 existUser·p0.9999: 30.679 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277616
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 272803 
    [ 5.000, 10.000) = 4447 
    [10.000, 15.000) = 247 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 22 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     43.662 ms/op
     p(99.9999) =     44.827 ms/op
    p(100.0000) =     44.827 ms/op


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
# Warmup Iteration   1: 5.247 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
Iteration   1: 3.687 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 17.968 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.606 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  7.761 ms/op
                 getUser·p0.9999: 35.521 ms/op
                 getUser·p1.00:   37.945 ms/op

Iteration   3: 3.671 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.334 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262639
  mean =      3.654 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7162 
    [ 2.500,  5.000) = 248364 
    [ 5.000,  7.500) = 6211 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     37.904 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 5.543 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.439 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.015 ms/op
Iteration   1: 4.753 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  15.262 ms/op
                 listUser·p0.9999: 16.783 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   2: 4.757 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.308 ms/op
                 listUser·p0.9999: 18.662 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.792 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  20.944 ms/op
                 listUser·p0.9999: 35.017 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201476
  mean =      4.767 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 361 
    [ 2.500,  5.000) = 151470 
    [ 5.000,  7.500) = 43974 
    [ 7.500, 10.000) = 4754 
    [10.000, 12.500) = 504 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     16.180 ms/op
     p(99.9900) =     33.938 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.606 ± 4.550  ops/ms
ClientGrpc.existUser                       thrpt       3   9.081 ± 1.427  ops/ms
ClientGrpc.getUser                         thrpt       3   8.767 ± 0.209  ops/ms
ClientGrpc.listUser                        thrpt       3   6.689 ± 0.342  ops/ms
ClientGrpc.createUser                       avgt       3   3.596 ± 0.642   ms/op
ClientGrpc.existUser                        avgt       3   3.404 ± 1.456   ms/op
ClientGrpc.getUser                          avgt       3   3.583 ± 1.054   ms/op
ClientGrpc.listUser                         avgt       3   4.738 ± 0.497   ms/op
ClientGrpc.createUser                     sample  267958   3.582 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.557           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.840           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.456           ms/op
ClientGrpc.existUser                      sample  277616   3.456 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.002           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.490           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          44.827           ms/op
ClientGrpc.getUser                        sample  262639   3.654 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.653           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.126           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.734           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.945           ms/op
ClientGrpc.listUser                       sample  201476   4.767 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.180           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.455           ms/op
