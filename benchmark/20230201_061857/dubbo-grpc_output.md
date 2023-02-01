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
# Warmup Iteration   1: 3.187 ops/ms
# Warmup Iteration   2: 6.630 ops/ms
# Warmup Iteration   3: 8.111 ops/ms
Iteration   1: 8.742 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.533 ±(99.9%) 3.638 ops/ms [Average]
  (min, avg, max) = (8.345, 8.533, 8.742), stdev = 0.199
  CI (99.9%): [4.895, 12.171] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.050 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 8.605 ops/ms
Iteration   1: 8.865 ops/ms
Iteration   2: 8.676 ops/ms
Iteration   3: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.802 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (8.676, 8.802, 8.865), stdev = 0.109
  CI (99.9%): [6.812, 10.791] (assumes normal distribution)


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
# Warmup Iteration   1: 5.843 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.501 ops/ms
Iteration   2: 8.145 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.300 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (8.145, 8.300, 8.501), stdev = 0.182
  CI (99.9%): [4.973, 11.627] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ops/ms
# Warmup Iteration   2: 6.198 ops/ms
# Warmup Iteration   3: 6.423 ops/ms
Iteration   1: 6.675 ops/ms
Iteration   2: 6.499 ops/ms
Iteration   3: 6.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.637 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (6.499, 6.637, 6.737), stdev = 0.124
  CI (99.9%): [4.384, 8.890] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.227 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.003 ms/op
Iteration   1: 3.850 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.003 ms/op
Iteration   3: 3.853 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.875 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.850, 3.875, 3.923), stdev = 0.041
  CI (99.9%): [3.124, 4.627] (assumes normal distribution)


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.004 ms/op
Iteration   1: 3.609 ±(99.9%) 0.002 ms/op
Iteration   2: 3.657 ±(99.9%) 0.003 ms/op
Iteration   3: 3.661 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.642 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.609, 3.642, 3.661), stdev = 0.029
  CI (99.9%): [3.121, 4.164] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.223 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.003 ms/op
Iteration   1: 3.828 ±(99.9%) 0.006 ms/op
Iteration   2: 3.786 ±(99.9%) 0.003 ms/op
Iteration   3: 3.648 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.754 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (3.648, 3.754, 3.828), stdev = 0.094
  CI (99.9%): [2.034, 5.474] (assumes normal distribution)


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
# Warmup Iteration   1: 5.968 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.120 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.723 ±(99.9%) 0.007 ms/op
Iteration   1: 4.710 ±(99.9%) 0.014 ms/op
Iteration   2: 4.667 ±(99.9%) 0.009 ms/op
Iteration   3: 4.654 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.677 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (4.654, 4.677, 4.710), stdev = 0.029
  CI (99.9%): [4.141, 5.212] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.333 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  13.373 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 3.836 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 14.696 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   3: 3.872 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.415 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250359
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7466 
    [ 2.500,  5.000) = 231269 
    [ 5.000,  7.500) = 10518 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     18.478 ms/op
     p(99.9990) =     19.710 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.961 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.009 ms/op
Iteration   1: 3.659 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  8.192 ms/op
                 existUser·p0.9999: 14.791 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 3.647 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 17.604 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.617 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.349 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  13.681 ms/op
                 existUser·p0.9999: 21.567 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263581
  mean =      3.641 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15250 
    [ 2.500,  5.000) = 240359 
    [ 5.000,  7.500) = 7208 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.841 ms/op
     p(99.9900) =     20.993 ms/op
     p(99.9990) =     21.916 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.009 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  10.771 ms/op
                 getUser·p0.9999: 19.810 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   2: 3.860 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 22.150 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.728 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.101 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253316
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5366 
    [ 2.500,  5.000) = 238221 
    [ 5.000,  7.500) = 8797 
    [ 7.500, 10.000) = 676 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     10.061 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 6.851 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.072 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.787 ±(99.9%) 0.014 ms/op
Iteration   1: 4.705 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  15.941 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 4.528 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  15.603 ms/op
                 listUser·p0.9999: 20.244 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 4.728 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 21.190 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206444
  mean =      4.652 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 622 
    [ 2.500,  5.000) = 159922 
    [ 5.000,  7.500) = 41665 
    [ 7.500, 10.000) = 3583 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     16.320 ms/op
     p(99.9900) =     20.602 ms/op
     p(99.9990) =     21.489 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.533 ± 3.638  ops/ms
ClientGrpc.existUser                       thrpt       3   8.802 ± 1.990  ops/ms
ClientGrpc.getUser                         thrpt       3   8.300 ± 3.327  ops/ms
ClientGrpc.listUser                        thrpt       3   6.637 ± 2.253  ops/ms
ClientGrpc.createUser                       avgt       3   3.875 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3   3.642 ± 0.522   ms/op
ClientGrpc.getUser                          avgt       3   3.754 ± 1.720   ms/op
ClientGrpc.listUser                         avgt       3   4.677 ± 0.536   ms/op
ClientGrpc.createUser                     sample  250359   3.832 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.961           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.353           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.218           ms/op
ClientGrpc.existUser                      sample  263581   3.641 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.349           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.841           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.993           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  253316   3.790 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.770           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.462           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  206444   4.652 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.110           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.320           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.602           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.561           ms/op
