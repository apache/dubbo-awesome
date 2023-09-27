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
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 6.604 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.392 ops/ms
Iteration   2: 8.557 ops/ms
Iteration   3: 8.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.524 ±(99.9%) 2.174 ops/ms [Average]
  (min, avg, max) = (8.392, 8.524, 8.624), stdev = 0.119
  CI (99.9%): [6.350, 10.698] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.110 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 8.919 ops/ms
Iteration   2: 9.144 ops/ms
Iteration   3: 9.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.028 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (8.919, 9.028, 9.144), stdev = 0.113
  CI (99.9%): [6.976, 11.081] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.005 ops/ms
# Warmup Iteration   2: 7.877 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.427 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.423 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (8.383, 8.423, 8.459), stdev = 0.038
  CI (99.9%): [7.730, 9.116] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.894 ops/ms
# Warmup Iteration   2: 6.359 ops/ms
# Warmup Iteration   3: 6.836 ops/ms
Iteration   1: 6.855 ops/ms
Iteration   2: 6.966 ops/ms
Iteration   3: 6.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.872 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (6.795, 6.872, 6.966), stdev = 0.086
  CI (99.9%): [5.295, 8.450] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
Iteration   1: 3.791 ±(99.9%) 0.002 ms/op
Iteration   2: 3.824 ±(99.9%) 0.003 ms/op
Iteration   3: 3.810 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.808 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.791, 3.808, 3.824), stdev = 0.017
  CI (99.9%): [3.498, 4.118] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.005 ms/op
Iteration   1: 3.636 ±(99.9%) 0.003 ms/op
Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
Iteration   3: 3.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.611 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.599, 3.611, 3.636), stdev = 0.021
  CI (99.9%): [3.231, 3.992] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.659 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
Iteration   1: 3.810 ±(99.9%) 0.004 ms/op
Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
Iteration   3: 3.780 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.790 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (3.779, 3.790, 3.810), stdev = 0.018
  CI (99.9%): [3.470, 4.109] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.695 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.359 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.787 ±(99.9%) 0.014 ms/op
Iteration   1: 4.759 ±(99.9%) 0.016 ms/op
Iteration   2: 4.847 ±(99.9%) 0.023 ms/op
Iteration   3: 4.759 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.788 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (4.759, 4.788, 4.847), stdev = 0.051
  CI (99.9%): [3.864, 5.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.010 ms/op
Iteration   1: 3.705 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  10.607 ms/op
                 createUser·p0.9999: 15.661 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 3.714 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 15.964 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   3: 3.709 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.678 ms/op
                 createUser·p0.999:  13.552 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258828
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4316 
    [ 2.500,  5.000) = 247854 
    [ 5.000,  7.500) = 5732 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     12.405 ms/op
     p(99.9900) =     18.616 ms/op
     p(99.9990) =     20.946 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.008 ms/op
Iteration   1: 3.535 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.592 ms/op
                 existUser·p0.999:  8.511 ms/op
                 existUser·p0.9999: 16.806 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 3.630 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  9.123 ms/op
                 existUser·p0.9999: 15.748 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   3: 3.643 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266421
  mean =      3.602 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8407 
    [ 2.500,  5.000) = 251651 
    [ 5.000,  7.500) = 5621 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     17.390 ms/op
     p(99.9990) =     20.207 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.525 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.011 ms/op
Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.616 ms/op
                 getUser·p0.999:  9.838 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 3.761 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.370 ms/op
                 getUser·p0.9999: 15.892 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.737 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255262
  mean =      3.760 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 4469 
    [ 2.500,  3.750) = 137561 
    [ 3.750,  5.000) = 104833 
    [ 5.000,  6.250) = 5866 
    [ 6.250,  7.500) = 1400 
    [ 7.500,  8.750) = 641 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     10.055 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     19.541 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 6.872 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.188 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.763 ±(99.9%) 0.013 ms/op
Iteration   1: 4.837 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  15.119 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 4.837 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  16.742 ms/op
                 listUser·p0.9999: 21.244 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.751 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  20.054 ms/op
                 listUser·p0.9999: 25.969 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199667
  mean =      4.808 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185 
    [ 2.500,  5.000) = 147104 
    [ 5.000,  7.500) = 46655 
    [ 7.500, 10.000) = 4820 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.544 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.524 ± 2.174  ops/ms
ClientGrpc.existUser                       thrpt       3   9.028 ± 2.053  ops/ms
ClientGrpc.getUser                         thrpt       3   8.423 ± 0.693  ops/ms
ClientGrpc.listUser                        thrpt       3   6.872 ± 1.578  ops/ms
ClientGrpc.createUser                       avgt       3   3.808 ± 0.310   ms/op
ClientGrpc.existUser                        avgt       3   3.611 ± 0.380   ms/op
ClientGrpc.getUser                          avgt       3   3.790 ± 0.320   ms/op
ClientGrpc.listUser                         avgt       3   4.788 ± 0.925   ms/op
ClientGrpc.createUser                     sample  258828   3.709 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.996           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.616           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.070           ms/op
ClientGrpc.existUser                      sample  266421   3.602 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.847           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.390           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  255262   3.760 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.986           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.226           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.055           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.595           ms/op
ClientGrpc.listUser                       sample  199667   4.808 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.378           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.078           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.314           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
