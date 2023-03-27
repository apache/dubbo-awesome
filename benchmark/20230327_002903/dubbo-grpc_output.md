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
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 6.995 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.628 ops/ms
Iteration   2: 8.766 ops/ms
Iteration   3: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.617 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (8.457, 8.617, 8.766), stdev = 0.155
  CI (99.9%): [5.793, 11.442] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ops/ms
# Warmup Iteration   2: 8.673 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 8.993 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.043 ±(99.9%) 2.138 ops/ms [Average]
  (min, avg, max) = (8.958, 9.043, 9.177), stdev = 0.117
  CI (99.9%): [6.904, 11.181] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.203 ops/ms
# Warmup Iteration   2: 8.113 ops/ms
# Warmup Iteration   3: 8.682 ops/ms
Iteration   1: 8.645 ops/ms
Iteration   2: 8.567 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.617 ±(99.9%) 0.798 ops/ms [Average]
  (min, avg, max) = (8.567, 8.617, 8.645), stdev = 0.044
  CI (99.9%): [7.819, 9.416] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 6.499 ops/ms
Iteration   1: 6.421 ops/ms
Iteration   2: 6.641 ops/ms
Iteration   3: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.502 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (6.421, 6.502, 6.641), stdev = 0.121
  CI (99.9%): [4.287, 8.717] (assumes normal distribution)


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
# Warmup Iteration   1: 5.348 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.006 ms/op
Iteration   1: 3.707 ±(99.9%) 0.004 ms/op
Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
Iteration   3: 3.685 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.694 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.685, 3.694, 3.707), stdev = 0.012
  CI (99.9%): [3.472, 3.915] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.003 ms/op
Iteration   1: 3.504 ±(99.9%) 0.004 ms/op
Iteration   2: 3.451 ±(99.9%) 0.003 ms/op
Iteration   3: 3.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.488 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.451, 3.488, 3.509), stdev = 0.032
  CI (99.9%): [2.900, 4.076] (assumes normal distribution)


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
# Warmup Iteration   1: 5.586 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.003 ms/op
Iteration   1: 3.765 ±(99.9%) 0.005 ms/op
Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
Iteration   3: 3.675 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.704 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.671, 3.704, 3.765), stdev = 0.053
  CI (99.9%): [2.733, 4.674] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.022 ±(99.9%) 0.018 ms/op
Iteration   1: 4.890 ±(99.9%) 0.015 ms/op
Iteration   2: 4.920 ±(99.9%) 0.009 ms/op
Iteration   3: 4.792 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.867 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (4.792, 4.867, 4.920), stdev = 0.067
  CI (99.9%): [3.649, 6.085] (assumes normal distribution)


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
# Warmup Iteration   1: 5.412 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.012 ms/op
Iteration   1: 3.673 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 17.919 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 3.681 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 23.526 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.652 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.982 ms/op
                 createUser·p0.999:  12.916 ms/op
                 createUser·p0.9999: 39.846 ms/op
                 createUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261746
  mean =      3.669 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 250894 
    [ 5.000, 10.000) = 10376 
    [10.000, 15.000) = 274 
    [15.000, 20.000) = 104 
    [20.000, 25.000) = 66 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     39.245 ms/op
     p(99.9990) =     40.949 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.010 ms/op
Iteration   1: 3.642 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  10.651 ms/op
                 existUser·p0.9999: 15.191 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 3.540 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  9.746 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.521 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 23.056 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269304
  mean =      3.567 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9716 
    [ 2.500,  5.000) = 249581 
    [ 5.000,  7.500) = 8533 
    [ 7.500, 10.000) = 1105 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     27.008 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.011 ms/op
Iteration   1: 3.685 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  9.922 ms/op
                 getUser·p0.9999: 16.569 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.623 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.691 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 27.006 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.671 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 20.805 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260583
  mean =      3.683 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9610 
    [ 2.500,  5.000) = 239304 
    [ 5.000,  7.500) = 10139 
    [ 7.500, 10.000) = 1044 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     11.958 ms/op
     p(99.9900) =     26.538 ms/op
     p(99.9990) =     27.171 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 6.465 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.123 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.016 ms/op
Iteration   1: 4.898 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  14.692 ms/op
                 listUser·p0.9999: 18.464 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 5.035 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   9.746 ms/op
                 listUser·p0.999:  18.637 ms/op
                 listUser·p0.9999: 20.594 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.873 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  20.034 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194620
  mean =      4.934 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 887 
    [ 2.500,  5.000) = 129953 
    [ 5.000,  7.500) = 54643 
    [ 7.500, 10.000) = 7910 
    [10.000, 12.500) = 788 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     25.103 ms/op
     p(99.9990) =     27.334 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.617 ± 2.825  ops/ms
ClientGrpc.existUser                       thrpt       3   9.043 ± 2.138  ops/ms
ClientGrpc.getUser                         thrpt       3   8.617 ± 0.798  ops/ms
ClientGrpc.listUser                        thrpt       3   6.502 ± 2.215  ops/ms
ClientGrpc.createUser                       avgt       3   3.694 ± 0.222   ms/op
ClientGrpc.existUser                        avgt       3   3.488 ± 0.588   ms/op
ClientGrpc.getUser                          avgt       3   3.704 ± 0.970   ms/op
ClientGrpc.listUser                         avgt       3   4.867 ± 1.218   ms/op
ClientGrpc.createUser                     sample  261746   3.669 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.816           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.245           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          41.681           ms/op
ClientGrpc.existUser                      sample  269304   3.567 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.781           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.008           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  260583   3.683 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.958           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.538           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  194620   4.934 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.200           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.103           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
