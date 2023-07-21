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
# Warmup Iteration   1: 4.563 ops/ms
# Warmup Iteration   2: 9.383 ops/ms
# Warmup Iteration   3: 10.177 ops/ms
Iteration   1: 10.639 ops/ms
Iteration   2: 10.455 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.525 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (10.455, 10.525, 10.639), stdev = 0.100
  CI (99.9%): [8.707, 12.344] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ops/ms
# Warmup Iteration   2: 10.642 ops/ms
# Warmup Iteration   3: 10.996 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 11.038 ops/ms
Iteration   3: 11.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.998 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (10.944, 10.998, 11.038), stdev = 0.048
  CI (99.9%): [10.118, 11.878] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 10.264 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.805 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (10.719, 10.805, 10.864), stdev = 0.076
  CI (99.9%): [9.422, 12.189] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.791 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.203 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (8.191, 8.203, 8.222), stdev = 0.016
  CI (99.9%): [7.903, 8.502] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.028, 3.055, 3.098), stdev = 0.038
  CI (99.9%): [2.367, 3.744] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.922 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.002 ms/op
Iteration   1: 2.776 ±(99.9%) 0.003 ms/op
Iteration   2: 2.869 ±(99.9%) 0.003 ms/op
Iteration   3: 2.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.827 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (2.776, 2.827, 2.869), stdev = 0.047
  CI (99.9%): [1.969, 3.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.957, 2.978, 2.994), stdev = 0.019
  CI (99.9%): [2.627, 3.328] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.037 ms/op
Iteration   1: 3.893 ±(99.9%) 0.017 ms/op
Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
Iteration   3: 3.890 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.890, 3.904, 3.931), stdev = 0.023
  CI (99.9%): [3.489, 4.320] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 2.979 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.962 ms/op
                 createUser·p0.9999: 15.098 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.906 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.431 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.047 ms/op
                 createUser·p0.9999: 32.002 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324350
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37308 
    [ 2.500,  5.000) = 285652 
    [ 5.000,  7.500) = 881 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     26.468 ms/op
     p(99.9990) =     32.269 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.586 ms/op
                 existUser·p0.9999: 11.689 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.505 ms/op
                 existUser·p0.9999: 20.772 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  11.287 ms/op
                 existUser·p0.9999: 13.632 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329558
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35076 
    [ 2.500,  5.000) = 293447 
    [ 5.000,  7.500) = 622 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.707 ms/op
     p(99.9900) =     17.141 ms/op
     p(99.9990) =     21.050 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.186 ms/op
                 getUser·p0.9999: 15.055 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.635 ms/op
                 getUser·p0.9999: 13.113 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.758 ms/op
                 getUser·p0.9999: 19.015 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318818
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2278 
    [ 1.250,  2.500) = 20917 
    [ 2.500,  3.750) = 281162 
    [ 3.750,  5.000) = 13158 
    [ 5.000,  6.250) = 719 
    [ 6.250,  7.500) = 317 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     17.633 ms/op
     p(99.9990) =     19.360 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.009 ms/op
Iteration   1: 3.964 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  11.877 ms/op
                 listUser·p0.9999: 18.182 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.604 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.691 ms/op
                 listUser·p0.9999: 15.695 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 22.027 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242185
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4059 
    [ 2.500,  5.000) = 214754 
    [ 5.000,  7.500) = 22344 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.550 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.525 ± 1.819  ops/ms
ClientGrpc.existUser                       thrpt       3  10.998 ± 0.880  ops/ms
ClientGrpc.getUser                         thrpt       3  10.805 ± 1.384  ops/ms
ClientGrpc.listUser                        thrpt       3   8.203 ± 0.299  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 0.688   ms/op
ClientGrpc.existUser                        avgt       3   2.827 ± 0.858   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.350   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.415   ms/op
ClientGrpc.createUser                     sample  324350   2.961 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.431           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.468           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.440           ms/op
ClientGrpc.existUser                      sample  329558   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.707           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.141           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  318818   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.633           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  242185   3.961 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.604           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.664           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
