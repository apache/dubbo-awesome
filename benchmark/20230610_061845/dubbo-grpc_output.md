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
# Warmup Iteration   1: 4.449 ops/ms
# Warmup Iteration   2: 9.333 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.882 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.883 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (10.794, 10.883, 10.972), stdev = 0.089
  CI (99.9%): [9.255, 12.511] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 9.073 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 11.190 ops/ms
Iteration   1: 11.097 ops/ms
Iteration   2: 11.702 ops/ms
Iteration   3: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.341 ±(99.9%) 5.825 ops/ms [Average]
  (min, avg, max) = (11.097, 11.341, 11.702), stdev = 0.319
  CI (99.9%): [5.516, 17.166] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.606 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.659 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (10.481, 10.659, 10.816), stdev = 0.169
  CI (99.9%): [7.585, 13.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.273 ops/ms
# Warmup Iteration   2: 7.912 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.150 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (8.084, 8.150, 8.213), stdev = 0.065
  CI (99.9%): [6.973, 9.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.056, 3.078, 3.101), stdev = 0.022
  CI (99.9%): [2.669, 3.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.003 ms/op
Iteration   1: 2.880 ±(99.9%) 0.003 ms/op
Iteration   2: 2.839 ±(99.9%) 0.002 ms/op
Iteration   3: 2.829 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.849 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.829, 2.849, 2.880), stdev = 0.027
  CI (99.9%): [2.358, 3.340] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.004 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.004 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.011 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.996, 3.011, 3.027), stdev = 0.015
  CI (99.9%): [2.730, 3.292] (assumes normal distribution)


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.008 ms/op
Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
Iteration   2: 3.786 ±(99.9%) 0.008 ms/op
Iteration   3: 3.865 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.786, 3.851, 3.900), stdev = 0.059
  CI (99.9%): [2.783, 4.918] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  6.652 ms/op
                 createUser·p0.9999: 12.386 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 14.232 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.574 ms/op
                 createUser·p0.999:  10.799 ms/op
                 createUser·p0.9999: 31.399 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322226
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29312 
    [ 2.500,  5.000) = 291673 
    [ 5.000,  7.500) = 861 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.397 ms/op
     p(99.9000) =     10.642 ms/op
     p(99.9900) =     28.208 ms/op
     p(99.9990) =     31.614 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.852 ±(99.9%) 0.005 ms/op
Iteration   1: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.699 ms/op
                 existUser·p0.9999: 21.952 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  8.954 ms/op
                 existUser·p0.9999: 16.158 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 2.827 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.782 ms/op
                 existUser·p0.9999: 26.007 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332996
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48636 
    [ 2.500,  5.000) = 283291 
    [ 5.000,  7.500) = 784 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     23.672 ms/op
     p(99.9990) =     26.400 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  6.757 ms/op
                 getUser·p0.9999: 20.296 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.651 ms/op
                 getUser·p0.9999: 19.054 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.327 ms/op
                 getUser·p0.9999: 26.553 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318171
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26487 
    [ 2.500,  5.000) = 290131 
    [ 5.000,  7.500) = 1263 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.085 ms/op
     p(99.9900) =     25.598 ms/op
     p(99.9990) =     26.864 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 5.600 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.669 ms/op
                 listUser·p0.999:  13.651 ms/op
                 listUser·p0.9999: 16.738 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.567 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.181 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245189
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4904 
    [ 2.500,  5.000) = 215704 
    [ 5.000,  7.500) = 23477 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     23.155 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.883 ± 1.628  ops/ms
ClientGrpc.existUser                       thrpt       3  11.341 ± 5.825  ops/ms
ClientGrpc.getUser                         thrpt       3  10.659 ± 3.074  ops/ms
ClientGrpc.listUser                        thrpt       3   8.150 ± 1.177  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 0.409   ms/op
ClientGrpc.existUser                        avgt       3   2.849 ± 0.491   ms/op
ClientGrpc.getUser                          avgt       3   3.011 ± 0.281   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 1.068   ms/op
ClientGrpc.createUser                     sample  322226   2.978 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.770           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.397           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.642           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.208           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.687           ms/op
ClientGrpc.existUser                      sample  332996   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.119           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.672           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.542           ms/op
ClientGrpc.getUser                        sample  318171   3.019 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.797           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.085           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.598           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.968           ms/op
ClientGrpc.listUser                       sample  245189   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.790           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.155           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.904           ms/op
