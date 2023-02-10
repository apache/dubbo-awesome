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
# Warmup Iteration   1: 3.403 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 8.360 ops/ms
Iteration   1: 8.765 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.676 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (8.555, 8.676, 8.765), stdev = 0.109
  CI (99.9%): [6.694, 10.659] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 9.124 ops/ms
Iteration   3: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.942 ±(99.9%) 3.900 ops/ms [Average]
  (min, avg, max) = (8.707, 8.942, 9.124), stdev = 0.214
  CI (99.9%): [5.042, 12.843] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.718 ops/ms
# Warmup Iteration   2: 8.263 ops/ms
# Warmup Iteration   3: 8.616 ops/ms
Iteration   1: 8.802 ops/ms
Iteration   2: 8.902 ops/ms
Iteration   3: 8.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.768 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (8.599, 8.768, 8.902), stdev = 0.155
  CI (99.9%): [5.948, 11.587] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ops/ms
# Warmup Iteration   2: 6.329 ops/ms
# Warmup Iteration   3: 6.730 ops/ms
Iteration   1: 6.847 ops/ms
Iteration   2: 6.760 ops/ms
Iteration   3: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.857 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (6.760, 6.857, 6.963), stdev = 0.102
  CI (99.9%): [4.999, 8.715] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.168 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.003 ms/op
Iteration   1: 3.798 ±(99.9%) 0.003 ms/op
Iteration   2: 3.790 ±(99.9%) 0.003 ms/op
Iteration   3: 3.661 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.749 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (3.661, 3.749, 3.798), stdev = 0.077
  CI (99.9%): [2.343, 5.156] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.688 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.003 ms/op
Iteration   1: 3.510 ±(99.9%) 0.003 ms/op
Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
Iteration   3: 3.516 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.524 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.510, 3.524, 3.547), stdev = 0.020
  CI (99.9%): [3.158, 3.891] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.003 ms/op
Iteration   1: 3.698 ±(99.9%) 0.003 ms/op
Iteration   2: 3.764 ±(99.9%) 0.002 ms/op
Iteration   3: 3.735 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.732 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.698, 3.732, 3.764), stdev = 0.033
  CI (99.9%): [3.129, 4.336] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.886 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.180 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.008 ms/op
Iteration   1: 4.710 ±(99.9%) 0.010 ms/op
Iteration   2: 4.656 ±(99.9%) 0.011 ms/op
Iteration   3: 4.603 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.656 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (4.603, 4.656, 4.710), stdev = 0.054
  CI (99.9%): [3.678, 5.635] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.414 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.012 ms/op
Iteration   1: 3.766 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  8.086 ms/op
                 createUser·p0.9999: 23.955 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.758 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  12.155 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.796 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 29.608 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254373
  mean =      3.773 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10291 
    [ 2.500,  5.000) = 234170 
    [ 5.000,  7.500) = 9162 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     28.756 ms/op
     p(99.9990) =     29.780 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
Iteration   1: 3.666 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  8.770 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 3.578 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  9.054 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 3.592 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  11.009 ms/op
                 existUser·p0.9999: 19.009 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265701
  mean =      3.611 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 9957 
    [ 2.500,  3.750) = 153294 
    [ 3.750,  5.000) = 96881 
    [ 5.000,  6.250) = 4178 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 314 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     18.261 ms/op
     p(99.9990) =     19.279 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 5.031 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.009 ms/op
Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.317 ms/op
                 getUser·p0.9999: 18.299 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  8.840 ms/op
                 getUser·p0.9999: 16.122 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   3: 3.685 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256451
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 6687 
    [ 2.500,  3.750) = 129938 
    [ 3.750,  5.000) = 112113 
    [ 5.000,  6.250) = 6617 
    [ 6.250,  7.500) = 519 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      8.774 ms/op
     p(99.9900) =     18.242 ms/op
     p(99.9990) =     19.052 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.563 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.795 ±(99.9%) 0.013 ms/op
Iteration   1: 4.774 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 30.424 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 4.696 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  16.234 ms/op
                 listUser·p0.9999: 23.401 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 4.694 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  20.825 ms/op
                 listUser·p0.9999: 31.621 ms/op
                 listUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203360
  mean =      4.721 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 252 
    [ 2.500,  5.000) = 155509 
    [ 5.000,  7.500) = 43483 
    [ 7.500, 10.000) = 3552 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     17.540 ms/op
     p(99.9900) =     30.977 ms/op
     p(99.9990) =     31.978 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.676 ± 1.983  ops/ms
ClientGrpc.existUser                       thrpt       3   8.942 ± 3.900  ops/ms
ClientGrpc.getUser                         thrpt       3   8.768 ± 2.819  ops/ms
ClientGrpc.listUser                        thrpt       3   6.857 ± 1.858  ops/ms
ClientGrpc.createUser                       avgt       3   3.749 ± 1.406   ms/op
ClientGrpc.existUser                        avgt       3   3.524 ± 0.367   ms/op
ClientGrpc.getUser                          avgt       3   3.732 ± 0.603   ms/op
ClientGrpc.listUser                         avgt       3   4.656 ± 0.978   ms/op
ClientGrpc.createUser                     sample  254373   3.773 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.878           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.141           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.756           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.983           ms/op
ClientGrpc.existUser                      sample  265701   3.611 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.322           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.261           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  256451   3.744 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.890           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.774           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.242           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.202           ms/op
ClientGrpc.listUser                       sample  203360   4.721 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.838           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.540           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.977           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.604           ms/op
