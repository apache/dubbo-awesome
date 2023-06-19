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
# Warmup Iteration   1: 4.641 ops/ms
# Warmup Iteration   2: 9.805 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.838 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.877 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (10.838, 10.877, 10.950), stdev = 0.064
  CI (99.9%): [9.713, 12.040] (assumes normal distribution)


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
# Warmup Iteration   1: 7.764 ops/ms
# Warmup Iteration   2: 10.889 ops/ms
# Warmup Iteration   3: 11.401 ops/ms
Iteration   1: 11.430 ops/ms
Iteration   2: 11.340 ops/ms
Iteration   3: 11.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.423 ±(99.9%) 1.456 ops/ms [Average]
  (min, avg, max) = (11.340, 11.423, 11.500), stdev = 0.080
  CI (99.9%): [9.967, 12.880] (assumes normal distribution)


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
# Warmup Iteration   1: 7.753 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.873 ops/ms
Iteration   1: 10.791 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.773 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (10.698, 10.773, 10.829), stdev = 0.068
  CI (99.9%): [9.539, 12.006] (assumes normal distribution)


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
# Warmup Iteration   1: 5.847 ops/ms
# Warmup Iteration   2: 8.379 ops/ms
# Warmup Iteration   3: 8.450 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.696 ops/ms
Iteration   3: 8.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.557 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (8.479, 8.557, 8.696), stdev = 0.120
  CI (99.9%): [6.359, 10.755] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.964 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.961, 2.964, 2.970), stdev = 0.005
  CI (99.9%): [2.879, 3.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.004 ms/op
Iteration   1: 2.726 ±(99.9%) 0.003 ms/op
Iteration   2: 2.771 ±(99.9%) 0.004 ms/op
Iteration   3: 2.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.773 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (2.726, 2.773, 2.822), stdev = 0.048
  CI (99.9%): [1.902, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.935 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (2.907, 2.935, 2.988), stdev = 0.046
  CI (99.9%): [2.098, 3.772] (assumes normal distribution)


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.030 ms/op
Iteration   1: 3.812 ±(99.9%) 0.023 ms/op
Iteration   2: 3.783 ±(99.9%) 0.007 ms/op
Iteration   3: 3.724 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.773 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.724, 3.773, 3.812), stdev = 0.045
  CI (99.9%): [2.952, 4.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.412 ms/op
                 createUser·p0.9999: 17.406 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  7.085 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.615 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321240
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22420 
    [ 2.500,  5.000) = 297509 
    [ 5.000,  7.500) = 1007 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     24.236 ms/op
     p(99.9990) =     26.044 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.006 ms/op
Iteration   1: 2.827 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  5.397 ms/op
                 existUser·p0.9999: 12.185 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.848 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.186 ms/op
                 existUser·p0.9999: 20.701 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 2.852 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.551 ms/op
                 existUser·p0.9999: 15.745 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337781
  mean =      2.842 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52130 
    [ 2.500,  5.000) = 284745 
    [ 5.000,  7.500) = 698 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.047 ms/op
     p(99.9900) =     17.833 ms/op
     p(99.9990) =     20.947 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 17.769 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 2.914 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.081 ms/op
                 getUser·p0.9999: 14.454 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  11.242 ms/op
                 getUser·p0.9999: 14.402 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324921
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1784 
    [ 1.250,  2.500) = 30533 
    [ 2.500,  3.750) = 278358 
    [ 3.750,  5.000) = 12979 
    [ 5.000,  6.250) = 746 
    [ 6.250,  7.500) = 266 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     18.039 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
Iteration   1: 3.789 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  12.170 ms/op
                 listUser·p0.9999: 18.081 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 19.831 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.838 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.695 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 19.683 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251742
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6564 
    [ 2.500,  5.000) = 223288 
    [ 5.000,  7.500) = 20637 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     19.557 ms/op
     p(99.9990) =     20.535 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.877 ± 1.163  ops/ms
ClientGrpc.existUser                       thrpt       3  11.423 ± 1.456  ops/ms
ClientGrpc.getUser                         thrpt       3  10.773 ± 1.234  ops/ms
ClientGrpc.listUser                        thrpt       3   8.557 ± 2.198  ops/ms
ClientGrpc.createUser                       avgt       3   2.964 ± 0.086   ms/op
ClientGrpc.existUser                        avgt       3   2.773 ± 0.871   ms/op
ClientGrpc.getUser                          avgt       3   2.935 ± 0.837   ms/op
ClientGrpc.listUser                         avgt       3   3.773 ± 0.821   ms/op
ClientGrpc.createUser                     sample  321240   2.990 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.673           ms/op
ClientGrpc.existUser                      sample  337781   2.842 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.585           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.047           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.833           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.037           ms/op
ClientGrpc.getUser                        sample  324921   2.953 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.121           ms/op
ClientGrpc.listUser                       sample  251742   3.811 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.695           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.557           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
