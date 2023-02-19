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
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.761 ops/ms
Iteration   1: 8.765 ops/ms
Iteration   2: 8.797 ops/ms
Iteration   3: 8.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.725 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (8.613, 8.725, 8.797), stdev = 0.099
  CI (99.9%): [6.927, 10.523] (assumes normal distribution)


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
# Warmup Iteration   1: 6.191 ops/ms
# Warmup Iteration   2: 8.631 ops/ms
# Warmup Iteration   3: 9.092 ops/ms
Iteration   1: 8.979 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.146 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (8.979, 9.146, 9.264), stdev = 0.149
  CI (99.9%): [6.426, 11.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.726 ops/ms
# Warmup Iteration   2: 8.955 ops/ms
# Warmup Iteration   3: 8.829 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.876 ops/ms
Iteration   3: 8.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.807 ±(99.9%) 2.109 ops/ms [Average]
  (min, avg, max) = (8.674, 8.807, 8.876), stdev = 0.116
  CI (99.9%): [6.698, 10.917] (assumes normal distribution)


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
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 6.158 ops/ms
# Warmup Iteration   3: 6.636 ops/ms
Iteration   1: 6.828 ops/ms
Iteration   2: 6.901 ops/ms
Iteration   3: 6.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.886 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (6.828, 6.886, 6.928), stdev = 0.052
  CI (99.9%): [5.940, 7.831] (assumes normal distribution)


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
# Warmup Iteration   1: 5.409 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.009 ms/op
Iteration   1: 3.831 ±(99.9%) 0.004 ms/op
Iteration   2: 3.723 ±(99.9%) 0.004 ms/op
Iteration   3: 3.645 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (3.645, 3.733, 3.831), stdev = 0.094
  CI (99.9%): [2.025, 5.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.002 ms/op
Iteration   1: 3.665 ±(99.9%) 0.002 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.569 ±(99.9%) 2.298 ms/op [Average]
  (min, avg, max) = (3.427, 3.569, 3.665), stdev = 0.126
  CI (99.9%): [1.272, 5.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.005 ms/op
Iteration   1: 3.696 ±(99.9%) 0.003 ms/op
Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
Iteration   3: 3.709 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.728 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.696, 3.728, 3.779), stdev = 0.045
  CI (99.9%): [2.911, 4.546] (assumes normal distribution)


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
# Warmup Iteration   2: 4.824 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.016 ms/op
Iteration   1: 4.665 ±(99.9%) 0.009 ms/op
Iteration   2: 4.594 ±(99.9%) 0.011 ms/op
Iteration   3: 4.619 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.626 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (4.594, 4.626, 4.665), stdev = 0.036
  CI (99.9%): [3.974, 5.278] (assumes normal distribution)


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
# Warmup Iteration   1: 5.396 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.157 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 31.466 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   2: 3.784 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  9.050 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.773 ms/op
                 createUser·p0.9999: 23.509 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249712
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4398 
    [ 2.500,  5.000) = 233934 
    [ 5.000,  7.500) = 10454 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     30.410 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.008 ms/op
Iteration   1: 3.676 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 18.101 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 3.725 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.620 ms/op
                 existUser·p0.9999: 16.791 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  7.728 ms/op
                 existUser·p0.9999: 19.027 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259495
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 9865 
    [ 2.500,  3.750) = 132748 
    [ 3.750,  5.000) = 109223 
    [ 5.000,  6.250) = 6520 
    [ 6.250,  7.500) = 557 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     18.517 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.008 ms/op
Iteration   1: 3.639 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   2: 3.728 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  7.409 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.715 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  7.879 ms/op
                 getUser·p0.9999: 20.591 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259913
  mean =      3.694 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7572 
    [ 2.500,  5.000) = 245675 
    [ 5.000,  7.500) = 6144 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.012 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 5.778 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.788 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.536 ±(99.9%) 0.013 ms/op
Iteration   1: 4.320 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  15.564 ms/op
                 listUser·p0.9999: 17.780 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 4.489 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  15.690 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.428 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  25.834 ms/op
                 listUser·p0.9999: 31.133 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217607
  mean =      4.411 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 759 
    [ 2.500,  5.000) = 182292 
    [ 5.000,  7.500) = 31366 
    [ 7.500, 10.000) = 2597 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     29.270 ms/op
     p(99.9990) =     31.386 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.725 ± 1.798  ops/ms
ClientGrpc.existUser                       thrpt       3   9.146 ± 2.720  ops/ms
ClientGrpc.getUser                         thrpt       3   8.807 ± 2.109  ops/ms
ClientGrpc.listUser                        thrpt       3   6.886 ± 0.945  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 1.708   ms/op
ClientGrpc.existUser                        avgt       3   3.569 ± 2.298   ms/op
ClientGrpc.getUser                          avgt       3   3.728 ± 0.818   ms/op
ClientGrpc.listUser                         avgt       3   4.626 ± 0.652   ms/op
ClientGrpc.createUser                     sample  249712   3.846 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.075           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.410           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.883           ms/op
ClientGrpc.existUser                      sample  259495   3.698 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.909           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.517           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  259913   3.694 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.527           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.585           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.150           ms/op
ClientGrpc.listUser                       sample  217607   4.411 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.876           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.243           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.283           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.270           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
