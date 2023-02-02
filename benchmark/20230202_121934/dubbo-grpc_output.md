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
# Warmup Iteration   1: 3.390 ops/ms
# Warmup Iteration   2: 6.844 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.294 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (8.264, 8.294, 8.310), stdev = 0.026
  CI (99.9%): [7.819, 8.769] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.829 ops/ms
# Warmup Iteration   2: 8.073 ops/ms
# Warmup Iteration   3: 8.089 ops/ms
Iteration   1: 8.555 ops/ms
Iteration   2: 8.613 ops/ms
Iteration   3: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.544 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (8.463, 8.544, 8.613), stdev = 0.076
  CI (99.9%): [7.165, 9.922] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.790 ops/ms
# Warmup Iteration   2: 7.825 ops/ms
# Warmup Iteration   3: 8.214 ops/ms
Iteration   1: 8.169 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.182 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (8.104, 8.182, 8.272), stdev = 0.085
  CI (99.9%): [6.632, 9.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 6.306 ops/ms
# Warmup Iteration   3: 6.701 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 6.760 ops/ms
Iteration   3: 6.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.758 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (6.686, 6.758, 6.829), stdev = 0.072
  CI (99.9%): [5.453, 8.064] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.477 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.005 ms/op
Iteration   1: 3.882 ±(99.9%) 0.003 ms/op
Iteration   2: 3.908 ±(99.9%) 0.003 ms/op
Iteration   3: 3.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.909 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.882, 3.909, 3.937), stdev = 0.028
  CI (99.9%): [3.406, 4.411] (assumes normal distribution)


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.003 ms/op
Iteration   1: 3.799 ±(99.9%) 0.002 ms/op
Iteration   2: 3.881 ±(99.9%) 0.003 ms/op
Iteration   3: 3.844 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.841 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.799, 3.841, 3.881), stdev = 0.041
  CI (99.9%): [3.085, 4.597] (assumes normal distribution)


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.003 ms/op
Iteration   1: 3.969 ±(99.9%) 0.002 ms/op
Iteration   2: 3.914 ±(99.9%) 0.004 ms/op
Iteration   3: 4.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.967 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.914, 3.967, 4.019), stdev = 0.053
  CI (99.9%): [3.005, 4.930] (assumes normal distribution)


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
# Warmup Iteration   1: 5.944 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.119 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.009 ms/op
Iteration   1: 4.601 ±(99.9%) 0.008 ms/op
Iteration   2: 4.829 ±(99.9%) 0.014 ms/op
Iteration   3: 4.719 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.716 ±(99.9%) 2.085 ms/op [Average]
  (min, avg, max) = (4.601, 4.716, 4.829), stdev = 0.114
  CI (99.9%): [2.631, 6.801] (assumes normal distribution)


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.767 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 16.558 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 3.907 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.017 ms/op
                 createUser·p0.999:  13.500 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  14.310 ms/op
                 createUser·p0.9999: 32.600 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245119
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5332 
    [ 2.500,  5.000) = 224638 
    [ 5.000,  7.500) = 13938 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     31.703 ms/op
     p(99.9990) =     32.938 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.010 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  10.591 ms/op
                 existUser·p0.9999: 16.644 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.720 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  12.516 ms/op
                 existUser·p0.9999: 16.099 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  13.196 ms/op
                 existUser·p0.9999: 19.446 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254892
  mean =      3.767 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8832 
    [ 2.500,  5.000) = 234023 
    [ 5.000,  7.500) = 10962 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     20.659 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.607 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.010 ms/op
Iteration   1: 4.012 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  13.440 ms/op
                 getUser·p0.9999: 15.702 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 3.826 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  12.503 ms/op
                 getUser·p0.9999: 16.831 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  11.090 ms/op
                 getUser·p0.9999: 19.608 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246395
  mean =      3.893 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6004 
    [ 2.500,  5.000) = 224995 
    [ 5.000,  7.500) = 14251 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     12.429 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     19.976 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 7.877 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.250 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.017 ms/op
Iteration   1: 4.849 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.806 ms/op
                 listUser·p0.9999: 23.835 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 4.850 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  16.855 ms/op
                 listUser·p0.9999: 23.620 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 4.471 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.436 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  21.344 ms/op
                 listUser·p0.9999: 32.779 ms/op
                 listUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203576
  mean =      4.716 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 149843 
    [ 5.000,  7.500) = 47879 
    [ 7.500, 10.000) = 4712 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     18.130 ms/op
     p(99.9900) =     31.839 ms/op
     p(99.9990) =     33.256 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.294 ± 0.475  ops/ms
ClientGrpc.existUser                       thrpt       3   8.544 ± 1.378  ops/ms
ClientGrpc.getUser                         thrpt       3   8.182 ± 1.550  ops/ms
ClientGrpc.listUser                        thrpt       3   6.758 ± 1.305  ops/ms
ClientGrpc.createUser                       avgt       3   3.909 ± 0.503   ms/op
ClientGrpc.existUser                        avgt       3   3.841 ± 0.756   ms/op
ClientGrpc.getUser                          avgt       3   3.967 ± 0.962   ms/op
ClientGrpc.listUser                         avgt       3   4.716 ± 2.085   ms/op
ClientGrpc.createUser                     sample  245119   3.916 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.007           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.095           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.892           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.703           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.996           ms/op
ClientGrpc.existUser                      sample  254892   3.767 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.892           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.291           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.632           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  246395   3.893 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.506           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.429           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.219           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  203576   4.716 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.436           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.130           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.839           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.358           ms/op
