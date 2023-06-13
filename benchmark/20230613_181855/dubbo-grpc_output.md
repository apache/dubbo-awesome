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
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 6.609 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.196 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (7.988, 8.196, 8.336), stdev = 0.184
  CI (99.9%): [4.843, 11.550] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.349 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 8.867 ops/ms
Iteration   3: 8.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.631 ±(99.9%) 9.133 ops/ms [Average]
  (min, avg, max) = (8.056, 8.631, 8.969), stdev = 0.501
  CI (99.9%): [≈ 0, 17.763] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.619 ops/ms
# Warmup Iteration   2: 8.041 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.584 ops/ms
Iteration   2: 8.202 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.313 ±(99.9%) 4.297 ops/ms [Average]
  (min, avg, max) = (8.154, 8.313, 8.584), stdev = 0.236
  CI (99.9%): [4.016, 12.610] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ops/ms
# Warmup Iteration   2: 6.143 ops/ms
# Warmup Iteration   3: 6.371 ops/ms
Iteration   1: 6.404 ops/ms
Iteration   2: 6.304 ops/ms
Iteration   3: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.296 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (6.180, 6.296, 6.404), stdev = 0.112
  CI (99.9%): [4.250, 8.343] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.661 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.410 ±(99.9%) 0.004 ms/op
Iteration   1: 4.018 ±(99.9%) 0.003 ms/op
Iteration   2: 3.886 ±(99.9%) 0.003 ms/op
Iteration   3: 3.770 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.891 ±(99.9%) 2.262 ms/op [Average]
  (min, avg, max) = (3.770, 3.891, 4.018), stdev = 0.124
  CI (99.9%): [1.629, 6.153] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.012 ms/op
Iteration   1: 3.557 ±(99.9%) 0.004 ms/op
Iteration   2: 3.498 ±(99.9%) 0.004 ms/op
Iteration   3: 3.470 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.508 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.470, 3.508, 3.557), stdev = 0.045
  CI (99.9%): [2.694, 4.322] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.689 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.006 ms/op
Iteration   1: 3.894 ±(99.9%) 0.005 ms/op
Iteration   2: 3.648 ±(99.9%) 0.003 ms/op
Iteration   3: 3.763 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.768 ±(99.9%) 2.244 ms/op [Average]
  (min, avg, max) = (3.648, 3.768, 3.894), stdev = 0.123
  CI (99.9%): [1.524, 6.012] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.515 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.581 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.437 ±(99.9%) 0.017 ms/op
Iteration   1: 5.397 ±(99.9%) 0.019 ms/op
Iteration   2: 5.059 ±(99.9%) 0.027 ms/op
Iteration   3: 5.069 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.175 ±(99.9%) 3.505 ms/op [Average]
  (min, avg, max) = (5.059, 5.175, 5.397), stdev = 0.192
  CI (99.9%): [1.670, 8.679] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  12.674 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 18.880 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 19.225 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249023
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6820 
    [ 2.500,  5.000) = 220280 
    [ 5.000,  7.500) = 20626 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     11.237 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
Iteration   1: 3.638 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.356 ms/op
                 existUser·p0.9999: 20.395 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.653 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  10.778 ms/op
                 existUser·p0.9999: 19.243 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 3.691 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.142 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 22.576 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262236
  mean =      3.661 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8766 
    [ 2.500,  5.000) = 238955 
    [ 5.000,  7.500) = 13581 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.084 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.010 ms/op
Iteration   1: 3.775 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.354 ms/op
                 getUser·p0.999:  9.507 ms/op
                 getUser·p0.9999: 15.173 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.878 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 31.006 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   3: 3.835 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 21.035 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250816
  mean =      3.829 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4003 
    [ 2.500,  5.000) = 227909 
    [ 5.000,  7.500) = 17914 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =      9.506 ms/op
     p(99.9900) =     30.144 ms/op
     p(99.9990) =     31.981 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 7.820 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.375 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.939 ±(99.9%) 0.018 ms/op
Iteration   1: 5.034 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.385 ms/op
                 listUser·p0.999:  18.333 ms/op
                 listUser·p0.9999: 23.132 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 5.250 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.651 ms/op
                 listUser·p0.99:   9.533 ms/op
                 listUser·p0.999:  22.109 ms/op
                 listUser·p0.9999: 31.675 ms/op
                 listUser·p1.00:   39.256 ms/op

Iteration   3: 5.138 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  18.007 ms/op
                 listUser·p0.9999: 24.015 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186663
  mean =      5.139 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 635 
    [ 2.500,  5.000) = 99969 
    [ 5.000,  7.500) = 76567 
    [ 7.500, 10.000) = 8146 
    [10.000, 12.500) = 900 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.657 ms/op
     p(95.0000) =      7.520 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     19.246 ms/op
     p(99.9900) =     30.387 ms/op
     p(99.9990) =     38.063 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.196 ± 3.353  ops/ms
ClientGrpc.existUser                       thrpt       3   8.631 ± 9.133  ops/ms
ClientGrpc.getUser                         thrpt       3   8.313 ± 4.297  ops/ms
ClientGrpc.listUser                        thrpt       3   6.296 ± 2.047  ops/ms
ClientGrpc.createUser                       avgt       3   3.891 ± 2.262   ms/op
ClientGrpc.existUser                        avgt       3   3.508 ± 0.814   ms/op
ClientGrpc.getUser                          avgt       3   3.768 ± 2.244   ms/op
ClientGrpc.listUser                         avgt       3   5.175 ± 3.505   ms/op
ClientGrpc.createUser                     sample  249023   3.852 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.838           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.237           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.907           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.987           ms/op
ClientGrpc.existUser                      sample  262236   3.661 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.916           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.275           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.970           ms/op
ClientGrpc.getUser                        sample  250816   3.829 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.506           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.144           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.047           ms/op
ClientGrpc.listUser                       sample  186663   5.139 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.657           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.246           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.387           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.256           ms/op
