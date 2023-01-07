# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 7.114 ops/ms
# Warmup Iteration   3: 8.264 ops/ms
Iteration   1: 8.607 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.455 ±(99.9%) 3.264 ops/ms [Average]
  (min, avg, max) = (8.258, 8.455, 8.607), stdev = 0.179
  CI (99.9%): [5.192, 11.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.265 ops/ms
# Warmup Iteration   2: 8.480 ops/ms
# Warmup Iteration   3: 8.698 ops/ms
Iteration   1: 8.699 ops/ms
Iteration   2: 8.999 ops/ms
Iteration   3: 8.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.805 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (8.699, 8.805, 8.999), stdev = 0.169
  CI (99.9%): [5.725, 11.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 8.113 ops/ms
# Warmup Iteration   3: 8.798 ops/ms
Iteration   1: 8.814 ops/ms
Iteration   2: 8.296 ops/ms
Iteration   3: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.650 ±(99.9%) 5.600 ops/ms [Average]
  (min, avg, max) = (8.296, 8.650, 8.841), stdev = 0.307
  CI (99.9%): [3.051, 14.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ops/ms
# Warmup Iteration   2: 6.318 ops/ms
# Warmup Iteration   3: 6.396 ops/ms
Iteration   1: 6.332 ops/ms
Iteration   2: 6.470 ops/ms
Iteration   3: 6.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.398 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (6.332, 6.398, 6.470), stdev = 0.070
  CI (99.9%): [5.130, 7.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.200 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.004 ms/op
Iteration   1: 3.775 ±(99.9%) 0.003 ms/op
Iteration   2: 3.795 ±(99.9%) 0.003 ms/op
Iteration   3: 3.608 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.726 ±(99.9%) 1.871 ms/op [Average]
  (min, avg, max) = (3.608, 3.726, 3.795), stdev = 0.103
  CI (99.9%): [1.856, 5.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.009 ms/op
Iteration   1: 3.535 ±(99.9%) 0.003 ms/op
Iteration   2: 3.550 ±(99.9%) 0.005 ms/op
Iteration   3: 3.622 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.569 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.535, 3.569, 3.622), stdev = 0.046
  CI (99.9%): [2.727, 4.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.003 ms/op
Iteration   1: 3.843 ±(99.9%) 0.002 ms/op
Iteration   2: 3.826 ±(99.9%) 0.002 ms/op
Iteration   3: 3.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.820 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.792, 3.820, 3.843), stdev = 0.026
  CI (99.9%): [3.343, 4.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.769 ±(99.9%) 0.013 ms/op
Iteration   1: 4.834 ±(99.9%) 0.019 ms/op
Iteration   2: 4.676 ±(99.9%) 0.010 ms/op
Iteration   3: 4.686 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.732 ±(99.9%) 1.608 ms/op [Average]
  (min, avg, max) = (4.676, 4.732, 4.834), stdev = 0.088
  CI (99.9%): [3.124, 6.340] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.010 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  11.510 ms/op
                 createUser·p0.9999: 17.945 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.806 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  12.959 ms/op
                 createUser·p0.9999: 21.666 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  12.812 ms/op
                 createUser·p0.9999: 20.117 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253873
  mean =      3.779 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7514 
    [ 2.500,  5.000) = 236200 
    [ 5.000,  7.500) = 9302 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     22.065 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.534 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  7.881 ms/op
                 existUser·p0.9999: 16.498 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 3.653 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  12.081 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  7.610 ms/op
                 existUser·p0.9999: 19.539 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266630
  mean =      3.599 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11745 
    [ 2.500,  5.000) = 249425 
    [ 5.000,  7.500) = 4969 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     20.535 ms/op
     p(99.9990) =     21.769 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.074 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.010 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  10.132 ms/op
                 getUser·p0.9999: 18.141 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.076 ms/op
                 getUser·p0.999:  10.623 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 23.305 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253232
  mean =      3.792 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6854 
    [ 2.500,  5.000) = 236185 
    [ 5.000,  7.500) = 9358 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     10.613 ms/op
     p(99.9900) =     22.599 ms/op
     p(99.9990) =     23.772 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.887 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.075 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.015 ms/op
Iteration   1: 4.766 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 18.008 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 4.715 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  15.322 ms/op
                 listUser·p0.9999: 24.073 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 4.765 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.392 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 26.029 ms/op
                 listUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202058
  mean =      4.748 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 148234 
    [ 5.000,  7.500) = 49120 
    [ 7.500, 10.000) = 3800 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     25.211 ms/op
     p(99.9990) =     29.751 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.455 ± 3.264  ops/ms
ClientGrpc.existUser                       thrpt       3   8.805 ± 3.079  ops/ms
ClientGrpc.getUser                         thrpt       3   8.650 ± 5.600  ops/ms
ClientGrpc.listUser                        thrpt       3   6.398 ± 1.268  ops/ms
ClientGrpc.createUser                       avgt       3   3.726 ± 1.871   ms/op
ClientGrpc.existUser                        avgt       3   3.569 ± 0.842   ms/op
ClientGrpc.getUser                          avgt       3   3.820 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   4.732 ± 1.608   ms/op
ClientGrpc.createUser                     sample  253873   3.779 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.871           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.796           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.546           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  266630   3.599 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.810           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.423           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.535           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.118           ms/op
ClientGrpc.getUser                        sample  253232   3.792 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.780           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.800           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.613           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.599           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.822           ms/op
ClientGrpc.listUser                       sample  202058   4.748 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.211           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.819           ms/op
