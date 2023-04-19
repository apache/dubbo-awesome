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
# Warmup Iteration   1: 4.795 ops/ms
# Warmup Iteration   2: 9.838 ops/ms
# Warmup Iteration   3: 10.214 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.822 ±(99.9%) 1.260 ops/ms [Average]
  (min, avg, max) = (10.777, 10.822, 10.902), stdev = 0.069
  CI (99.9%): [9.562, 12.082] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 10.820 ops/ms
# Warmup Iteration   3: 11.027 ops/ms
Iteration   1: 11.472 ops/ms
Iteration   2: 11.216 ops/ms
Iteration   3: 11.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.247 ±(99.9%) 3.843 ops/ms [Average]
  (min, avg, max) = (11.054, 11.247, 11.472), stdev = 0.211
  CI (99.9%): [7.405, 15.090] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ops/ms
# Warmup Iteration   2: 10.364 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.995 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.942 ±(99.9%) 1.061 ops/ms [Average]
  (min, avg, max) = (10.879, 10.942, 10.995), stdev = 0.058
  CI (99.9%): [9.880, 12.003] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 8.236 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.301 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (8.230, 8.301, 8.379), stdev = 0.075
  CI (99.9%): [6.938, 9.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.930 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (2.892, 2.930, 2.957), stdev = 0.033
  CI (99.9%): [2.322, 3.537] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.003 ms/op
Iteration   1: 2.840 ±(99.9%) 0.002 ms/op
Iteration   2: 2.784 ±(99.9%) 0.003 ms/op
Iteration   3: 2.798 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.808 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (2.784, 2.808, 2.840), stdev = 0.029
  CI (99.9%): [2.275, 3.341] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.002 ms/op
Iteration   1: 2.917 ±(99.9%) 0.002 ms/op
Iteration   2: 2.917 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.916 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (2.913, 2.916, 2.917), stdev = 0.002
  CI (99.9%): [2.874, 2.957] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.031 ms/op
Iteration   1: 3.757 ±(99.9%) 0.070 ms/op
Iteration   2: 3.816 ±(99.9%) 0.008 ms/op
Iteration   3: 3.770 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.781 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.757, 3.781, 3.816), stdev = 0.031
  CI (99.9%): [3.213, 4.348] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.209 ms/op
                 createUser·p0.9999: 20.009 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 2.907 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  7.161 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.554 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.568 ms/op
                 createUser·p0.9999: 15.951 ms/op
                 createUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324995
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33066 
    [ 2.500,  5.000) = 290883 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     17.745 ms/op
     p(99.9990) =     20.505 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.879 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.692 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.687 ms/op
                 existUser·p0.9999: 11.506 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.873 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  10.514 ms/op
                 existUser·p0.9999: 24.015 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 21.518 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341721
  mean =      2.807 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65859 
    [ 2.500,  5.000) = 274828 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.299 ms/op
     p(99.9900) =     21.883 ms/op
     p(99.9990) =     24.366 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  6.107 ms/op
                 getUser·p0.9999: 14.569 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  7.507 ms/op
                 getUser·p0.9999: 22.159 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323385
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27359 
    [ 2.500,  5.000) = 295180 
    [ 5.000,  7.500) = 579 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.632 ms/op
     p(99.9900) =     21.211 ms/op
     p(99.9990) =     22.365 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.009 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.307 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.545 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 19.814 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.876 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.703 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  14.800 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249702
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4654 
    [ 2.500,  5.000) = 225094 
    [ 5.000,  7.500) = 18760 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     15.127 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     20.483 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.822 ± 1.260  ops/ms
ClientGrpc.existUser                       thrpt       3  11.247 ± 3.843  ops/ms
ClientGrpc.getUser                         thrpt       3  10.942 ± 1.061  ops/ms
ClientGrpc.listUser                        thrpt       3   8.301 ± 1.363  ops/ms
ClientGrpc.createUser                       avgt       3   2.930 ± 0.607   ms/op
ClientGrpc.existUser                        avgt       3   2.808 ± 0.533   ms/op
ClientGrpc.getUser                          avgt       3   2.916 ± 0.041   ms/op
ClientGrpc.listUser                         avgt       3   3.781 ± 0.567   ms/op
ClientGrpc.createUser                     sample  324995   2.952 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.516           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.745           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  341721   2.807 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.299           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.883           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.445           ms/op
ClientGrpc.getUser                        sample  323385   2.968 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.647           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.632           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.211           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  249702   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.127           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.037           ms/op
