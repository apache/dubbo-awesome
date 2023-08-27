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
# Warmup Iteration   1: 3.195 ops/ms
# Warmup Iteration   2: 7.339 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.723 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.759 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (8.711, 8.759, 8.844), stdev = 0.074
  CI (99.9%): [7.412, 10.106] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.594 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.491 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.490 ±(99.9%) 0.420 ops/ms [Average]
  (min, avg, max) = (9.466, 9.490, 9.512), stdev = 0.023
  CI (99.9%): [9.070, 9.910] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.770 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 8.915 ops/ms
Iteration   1: 8.818 ops/ms
Iteration   2: 8.794 ops/ms
Iteration   3: 8.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.830 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (8.794, 8.830, 8.878), stdev = 0.043
  CI (99.9%): [8.039, 9.622] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.103 ops/ms
# Warmup Iteration   2: 6.271 ops/ms
# Warmup Iteration   3: 6.688 ops/ms
Iteration   1: 6.735 ops/ms
Iteration   2: 6.713 ops/ms
Iteration   3: 6.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.730 ±(99.9%) 0.279 ops/ms [Average]
  (min, avg, max) = (6.713, 6.730, 6.742), stdev = 0.015
  CI (99.9%): [6.451, 7.009] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.003 ms/op
Iteration   1: 3.631 ±(99.9%) 0.003 ms/op
Iteration   2: 3.624 ±(99.9%) 0.003 ms/op
Iteration   3: 3.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.580 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (3.484, 3.580, 3.631), stdev = 0.083
  CI (99.9%): [2.069, 5.090] (assumes normal distribution)


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.003 ms/op
Iteration   1: 3.404 ±(99.9%) 0.003 ms/op
Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
Iteration   3: 3.249 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.347 ±(99.9%) 1.561 ms/op [Average]
  (min, avg, max) = (3.249, 3.347, 3.404), stdev = 0.086
  CI (99.9%): [1.786, 4.908] (assumes normal distribution)


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.005 ms/op
Iteration   1: 3.662 ±(99.9%) 0.005 ms/op
Iteration   2: 3.580 ±(99.9%) 0.006 ms/op
Iteration   3: 3.549 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.597 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (3.549, 3.597, 3.662), stdev = 0.058
  CI (99.9%): [2.533, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 6.573 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.016 ms/op
Iteration   1: 4.756 ±(99.9%) 0.022 ms/op
Iteration   2: 4.714 ±(99.9%) 0.011 ms/op
Iteration   3: 4.637 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.702 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (4.637, 4.702, 4.756), stdev = 0.060
  CI (99.9%): [3.603, 5.802] (assumes normal distribution)


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.008 ms/op
Iteration   1: 3.635 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 25.120 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.503 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 15.825 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.603 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.517 ms/op
                 createUser·p0.999:  9.654 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268032
  mean =      3.580 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6485 
    [ 2.500,  5.000) = 256646 
    [ 5.000,  7.500) = 3981 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     10.518 ms/op
     p(99.9900) =     24.097 ms/op
     p(99.9990) =     25.832 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
Iteration   1: 3.359 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.295 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.328 ms/op
                 existUser·p0.9999: 17.103 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 3.426 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  17.465 ms/op
                 existUser·p0.9999: 68.551 ms/op
                 existUser·p1.00:   71.827 ms/op

Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  7.676 ms/op
                 existUser·p0.9999: 21.865 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283984
  mean =      3.378 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 280555 
    [ 5.000, 10.000) = 3263 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 94 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 31 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     67.633 ms/op
     p(99.9990) =     68.813 ms/op
     p(99.9999) =     71.827 ms/op
    p(100.0000) =     71.827 ms/op


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.007 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  13.474 ms/op
                 getUser·p0.9999: 16.449 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.570 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  8.276 ms/op
                 getUser·p0.9999: 16.205 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   3: 3.534 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 21.461 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266891
  mean =      3.596 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7365 
    [ 2.500,  5.000) = 253639 
    [ 5.000,  7.500) = 5135 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     20.130 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 6.561 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.667 ±(99.9%) 0.014 ms/op
Iteration   1: 4.692 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  13.858 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 4.728 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  18.917 ms/op
                 listUser·p0.9999: 25.025 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.732 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203500
  mean =      4.717 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 162377 
    [ 5.000,  7.500) = 36442 
    [ 7.500, 10.000) = 3844 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     24.630 ms/op
     p(99.9990) =     26.342 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.759 ± 1.347  ops/ms
ClientGrpc.existUser                       thrpt       3   9.490 ± 0.420  ops/ms
ClientGrpc.getUser                         thrpt       3   8.830 ± 0.791  ops/ms
ClientGrpc.listUser                        thrpt       3   6.730 ± 0.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.580 ± 1.510   ms/op
ClientGrpc.existUser                        avgt       3   3.347 ± 1.561   ms/op
ClientGrpc.getUser                          avgt       3   3.597 ± 1.064   ms/op
ClientGrpc.listUser                         avgt       3   4.702 ± 1.099   ms/op
ClientGrpc.createUser                     sample  268032   3.580 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.518           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.097           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.887           ms/op
ClientGrpc.existUser                      sample  283984   3.378 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.295           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          67.633           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          71.827           ms/op
ClientGrpc.getUser                        sample  266891   3.596 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.796           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.486           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.130           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  203500   4.717 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.163           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.630           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
