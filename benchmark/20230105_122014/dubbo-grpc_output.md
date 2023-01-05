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
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 6.746 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.101 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.056 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (7.985, 8.056, 8.101), stdev = 0.063
  CI (99.9%): [6.911, 9.202] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.673 ops/ms
# Warmup Iteration   2: 8.138 ops/ms
# Warmup Iteration   3: 8.593 ops/ms
Iteration   1: 8.665 ops/ms
Iteration   2: 8.486 ops/ms
Iteration   3: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.561 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (8.486, 8.561, 8.665), stdev = 0.093
  CI (99.9%): [6.861, 10.261] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 8.067 ops/ms
Iteration   1: 8.236 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.276 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (8.217, 8.276, 8.376), stdev = 0.087
  CI (99.9%): [6.694, 9.858] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ops/ms
# Warmup Iteration   2: 6.132 ops/ms
# Warmup Iteration   3: 6.411 ops/ms
Iteration   1: 6.419 ops/ms
Iteration   2: 6.484 ops/ms
Iteration   3: 6.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.488 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (6.419, 6.488, 6.561), stdev = 0.071
  CI (99.9%): [5.189, 7.786] (assumes normal distribution)


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
# Warmup Iteration   1: 5.291 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.006 ms/op
Iteration   1: 3.827 ±(99.9%) 0.003 ms/op
Iteration   2: 3.918 ±(99.9%) 0.002 ms/op
Iteration   3: 3.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.865 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.827, 3.865, 3.918), stdev = 0.047
  CI (99.9%): [2.999, 4.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.004 ms/op
Iteration   1: 3.699 ±(99.9%) 0.003 ms/op
Iteration   2: 3.688 ±(99.9%) 0.002 ms/op
Iteration   3: 3.724 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.704 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (3.688, 3.704, 3.724), stdev = 0.018
  CI (99.9%): [3.368, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 5.481 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.004 ms/op
Iteration   1: 3.863 ±(99.9%) 0.002 ms/op
Iteration   2: 3.841 ±(99.9%) 0.004 ms/op
Iteration   3: 3.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.866 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.841, 3.866, 3.894), stdev = 0.027
  CI (99.9%): [3.380, 4.351] (assumes normal distribution)


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
# Warmup Iteration   1: 6.646 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.881 ±(99.9%) 0.011 ms/op
Iteration   1: 4.855 ±(99.9%) 0.011 ms/op
Iteration   2: 4.728 ±(99.9%) 0.014 ms/op
Iteration   3: 4.895 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.826 ±(99.9%) 1.590 ms/op [Average]
  (min, avg, max) = (4.728, 4.826, 4.895), stdev = 0.087
  CI (99.9%): [3.236, 6.417] (assumes normal distribution)


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
# Warmup Iteration   1: 5.660 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.010 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  9.065 ms/op
                 createUser·p0.9999: 23.054 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  7.982 ms/op
                 createUser·p0.9999: 35.848 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  21.336 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250563
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7505 
    [ 2.500,  5.000) = 232730 
    [ 5.000,  7.500) = 9845 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.862 ms/op
     p(99.9900) =     34.337 ms/op
     p(99.9990) =     36.304 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.009 ms/op
Iteration   1: 3.685 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  7.883 ms/op
                 existUser·p0.9999: 18.708 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.926 ms/op
                 existUser·p0.9999: 17.019 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.669 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.415 ms/op
                 existUser·p0.9999: 21.392 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260218
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12706 
    [ 2.500,  5.000) = 241423 
    [ 5.000,  7.500) = 5606 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      9.554 ms/op
     p(99.9900) =     20.315 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 5.382 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.009 ms/op
Iteration   1: 3.874 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   5.665 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 20.422 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.787 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  9.793 ms/op
                 getUser·p0.9999: 21.423 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.798 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 23.729 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249038
  mean =      3.854 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7395 
    [ 2.500,  5.000) = 230821 
    [ 5.000,  7.500) = 10127 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     21.547 ms/op
     p(99.9990) =     24.284 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 6.952 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.500 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.918 ±(99.9%) 0.015 ms/op
Iteration   1: 4.918 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.146 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  15.462 ms/op
                 listUser·p0.9999: 18.563 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.841 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 32.347 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   3: 4.940 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  19.857 ms/op
                 listUser·p0.9999: 23.020 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196064
  mean =      4.899 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 337 
    [ 2.500,  5.000) = 132576 
    [ 5.000,  7.500) = 58195 
    [ 7.500, 10.000) = 4379 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     16.902 ms/op
     p(99.9900) =     31.102 ms/op
     p(99.9990) =     32.773 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.056 ± 1.145  ops/ms
ClientGrpc.existUser                       thrpt       3   8.561 ± 1.700  ops/ms
ClientGrpc.getUser                         thrpt       3   8.276 ± 1.582  ops/ms
ClientGrpc.listUser                        thrpt       3   6.488 ± 1.299  ops/ms
ClientGrpc.createUser                       avgt       3   3.865 ± 0.865   ms/op
ClientGrpc.existUser                        avgt       3   3.704 ± 0.336   ms/op
ClientGrpc.getUser                          avgt       3   3.866 ± 0.485   ms/op
ClientGrpc.listUser                         avgt       3   4.826 ± 1.590   ms/op
ClientGrpc.createUser                     sample  250563   3.830 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.862           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.337           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.635           ms/op
ClientGrpc.existUser                      sample  260218   3.688 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.784           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.554           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.315           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  249038   3.854 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.813           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.535           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.547           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.412           ms/op
ClientGrpc.listUser                       sample  196064   4.899 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.971           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.405           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.902           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.102           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.899           ms/op
