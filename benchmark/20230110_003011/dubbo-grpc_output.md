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
# Warmup Iteration   1: 3.186 ops/ms
# Warmup Iteration   2: 7.085 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.271 ±(99.9%) 4.261 ops/ms [Average]
  (min, avg, max) = (8.046, 8.271, 8.512), stdev = 0.234
  CI (99.9%): [4.011, 12.532] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.094 ops/ms
# Warmup Iteration   2: 8.474 ops/ms
# Warmup Iteration   3: 8.986 ops/ms
Iteration   1: 8.917 ops/ms
Iteration   2: 8.728 ops/ms
Iteration   3: 8.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.760 ±(99.9%) 2.625 ops/ms [Average]
  (min, avg, max) = (8.635, 8.760, 8.917), stdev = 0.144
  CI (99.9%): [6.135, 11.385] (assumes normal distribution)


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
# Warmup Iteration   1: 5.825 ops/ms
# Warmup Iteration   2: 8.371 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 8.065 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.200 ±(99.9%) 2.143 ops/ms [Average]
  (min, avg, max) = (8.065, 8.200, 8.282), stdev = 0.117
  CI (99.9%): [6.057, 10.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ops/ms
# Warmup Iteration   2: 6.008 ops/ms
# Warmup Iteration   3: 6.627 ops/ms
Iteration   1: 6.749 ops/ms
Iteration   2: 6.872 ops/ms
Iteration   3: 6.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.735 ±(99.9%) 2.630 ops/ms [Average]
  (min, avg, max) = (6.585, 6.735, 6.872), stdev = 0.144
  CI (99.9%): [4.105, 9.365] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.455 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.004 ms/op
Iteration   1: 3.945 ±(99.9%) 0.003 ms/op
Iteration   2: 3.816 ±(99.9%) 0.008 ms/op
Iteration   3: 3.803 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.854 ±(99.9%) 1.434 ms/op [Average]
  (min, avg, max) = (3.803, 3.854, 3.945), stdev = 0.079
  CI (99.9%): [2.420, 5.289] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.823 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.006 ms/op
Iteration   1: 3.653 ±(99.9%) 0.002 ms/op
Iteration   2: 3.542 ±(99.9%) 0.005 ms/op
Iteration   3: 3.633 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.609 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.542, 3.609, 3.653), stdev = 0.059
  CI (99.9%): [2.533, 4.685] (assumes normal distribution)


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
# Warmup Iteration   1: 5.229 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.004 ms/op
Iteration   1: 3.842 ±(99.9%) 0.003 ms/op
Iteration   2: 3.792 ±(99.9%) 0.002 ms/op
Iteration   3: 3.819 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.818 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.792, 3.818, 3.842), stdev = 0.025
  CI (99.9%): [3.364, 4.272] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.845 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.079 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.908 ±(99.9%) 0.021 ms/op
Iteration   1: 4.745 ±(99.9%) 0.007 ms/op
Iteration   2: 4.566 ±(99.9%) 0.010 ms/op
Iteration   3: 4.718 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.676 ±(99.9%) 1.761 ms/op [Average]
  (min, avg, max) = (4.566, 4.676, 4.745), stdev = 0.097
  CI (99.9%): [2.915, 6.437] (assumes normal distribution)


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
# Warmup Iteration   1: 5.771 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 14.639 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.924 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  15.620 ms/op
                 createUser·p0.9999: 19.749 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247100
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7060 
    [ 2.500,  5.000) = 224795 
    [ 5.000,  7.500) = 14035 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     19.244 ms/op
     p(99.9990) =     20.154 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.009 ms/op
Iteration   1: 3.590 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  7.978 ms/op
                 existUser·p0.9999: 20.325 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.705 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 18.198 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   3: 3.626 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  8.779 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263602
  mean =      3.640 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15439 
    [ 2.500,  5.000) = 240125 
    [ 5.000,  7.500) = 7095 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     18.863 ms/op
     p(99.9990) =     20.623 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.514 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.010 ms/op
Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  8.748 ms/op
                 getUser·p0.9999: 23.917 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.721 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  9.780 ms/op
                 getUser·p0.9999: 25.605 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.709 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.632 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 28.356 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259499
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8519 
    [ 2.500,  5.000) = 243425 
    [ 5.000,  7.500) = 6799 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     27.627 ms/op
     p(99.9990) =     28.535 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 6.534 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.161 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.112 ±(99.9%) 0.018 ms/op
Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 17.291 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 4.999 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  17.008 ms/op
                 listUser·p0.9999: 25.677 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   3: 4.969 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  25.023 ms/op
                 listUser·p0.9999: 32.047 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196091
  mean =      4.893 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 135489 
    [ 5.000,  7.500) = 53692 
    [ 7.500, 10.000) = 5900 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     16.971 ms/op
     p(99.9900) =     31.896 ms/op
     p(99.9990) =     33.400 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.271 ± 4.261  ops/ms
ClientGrpc.existUser                       thrpt       3   8.760 ± 2.625  ops/ms
ClientGrpc.getUser                         thrpt       3   8.200 ± 2.143  ops/ms
ClientGrpc.listUser                        thrpt       3   6.735 ± 2.630  ops/ms
ClientGrpc.createUser                       avgt       3   3.854 ± 1.434   ms/op
ClientGrpc.existUser                        avgt       3   3.609 ± 1.076   ms/op
ClientGrpc.getUser                          avgt       3   3.818 ± 0.454   ms/op
ClientGrpc.listUser                         avgt       3   4.676 ± 1.761   ms/op
ClientGrpc.createUser                     sample  247100   3.888 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.920           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.104           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.649           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.244           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  263602   3.640 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.690           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.093           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.863           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  259499   3.701 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.812           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.032           ms/op
ClientGrpc.listUser                       sample  196091   4.893 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.971           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.896           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.620           ms/op
