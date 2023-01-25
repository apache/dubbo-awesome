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
# Warmup Iteration   1: 3.089 ops/ms
# Warmup Iteration   2: 7.248 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.274 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (8.170, 8.274, 8.350), stdev = 0.093
  CI (99.9%): [6.577, 9.972] (assumes normal distribution)


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
# Warmup Iteration   1: 5.916 ops/ms
# Warmup Iteration   2: 8.383 ops/ms
# Warmup Iteration   3: 8.740 ops/ms
Iteration   1: 8.907 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.713 ±(99.9%) 3.978 ops/ms [Average]
  (min, avg, max) = (8.477, 8.713, 8.907), stdev = 0.218
  CI (99.9%): [4.734, 12.691] (assumes normal distribution)


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
# Warmup Iteration   1: 5.361 ops/ms
# Warmup Iteration   2: 8.246 ops/ms
# Warmup Iteration   3: 8.712 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 7.849 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.924 ±(99.9%) 2.673 ops/ms [Average]
  (min, avg, max) = (7.831, 7.924, 8.093), stdev = 0.147
  CI (99.9%): [5.251, 10.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 6.557 ops/ms
Iteration   1: 6.496 ops/ms
Iteration   2: 6.854 ops/ms
Iteration   3: 7.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.815 ±(99.9%) 5.516 ops/ms [Average]
  (min, avg, max) = (6.496, 6.815, 7.097), stdev = 0.302
  CI (99.9%): [1.299, 12.332] (assumes normal distribution)


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
# Warmup Iteration   1: 5.342 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.033 ms/op
Iteration   1: 3.729 ±(99.9%) 0.004 ms/op
Iteration   2: 3.796 ±(99.9%) 0.002 ms/op
Iteration   3: 3.692 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.739 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.692, 3.739, 3.796), stdev = 0.053
  CI (99.9%): [2.768, 4.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.818 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.003 ms/op
Iteration   1: 3.747 ±(99.9%) 0.003 ms/op
Iteration   2: 3.657 ±(99.9%) 0.002 ms/op
Iteration   3: 3.641 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.682 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.641, 3.682, 3.747), stdev = 0.057
  CI (99.9%): [2.647, 4.716] (assumes normal distribution)


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.003 ms/op
Iteration   1: 3.847 ±(99.9%) 0.004 ms/op
Iteration   2: 3.826 ±(99.9%) 0.004 ms/op
Iteration   3: 3.807 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.827 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.807, 3.827, 3.847), stdev = 0.020
  CI (99.9%): [3.462, 4.191] (assumes normal distribution)


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
# Warmup Iteration   1: 6.901 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.021 ms/op
Iteration   1: 4.927 ±(99.9%) 0.022 ms/op
Iteration   2: 5.113 ±(99.9%) 0.023 ms/op
Iteration   3: 4.825 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.955 ±(99.9%) 2.670 ms/op [Average]
  (min, avg, max) = (4.825, 4.955, 5.113), stdev = 0.146
  CI (99.9%): [2.285, 7.625] (assumes normal distribution)


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
# Warmup Iteration   1: 5.138 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
Iteration   1: 3.647 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  12.722 ms/op
                 createUser·p0.9999: 14.551 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  12.616 ms/op
                 createUser·p0.9999: 17.870 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  10.093 ms/op
                 createUser·p0.9999: 18.533 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261307
  mean =      3.676 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8465 
    [ 2.500,  5.000) = 245451 
    [ 5.000,  7.500) = 6712 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     11.360 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     20.014 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.837 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.009 ms/op
Iteration   1: 3.669 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  8.550 ms/op
                 existUser·p0.9999: 15.757 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   2: 3.657 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   3: 3.659 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  12.007 ms/op
                 existUser·p0.9999: 36.241 ms/op
                 existUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262080
  mean =      3.662 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10414 
    [ 2.500,  5.000) = 245858 
    [ 5.000,  7.500) = 5298 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     35.414 ms/op
     p(99.9990) =     36.594 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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
# Warmup Iteration   1: 5.419 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.009 ms/op
Iteration   1: 3.828 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 18.196 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  9.289 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 3.816 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.930 ms/op
                 getUser·p0.9999: 21.916 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249545
  mean =      3.848 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5976 
    [ 2.500,  5.000) = 234097 
    [ 5.000,  7.500) = 8890 
    [ 7.500, 10.000) = 421 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.558 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 5.880 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.089 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.015 ms/op
Iteration   1: 4.488 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 17.428 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 4.646 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.986 ms/op
                 listUser·p0.999:  22.824 ms/op
                 listUser·p0.9999: 27.733 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   3: 4.709 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  23.068 ms/op
                 listUser·p0.9999: 27.951 ms/op
                 listUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208097
  mean =      4.613 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 422 
    [ 2.500,  5.000) = 168220 
    [ 5.000,  7.500) = 35697 
    [ 7.500, 10.000) = 3232 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     27.597 ms/op
     p(99.9990) =     28.634 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.274 ± 1.697  ops/ms
ClientGrpc.existUser                       thrpt       3   8.713 ± 3.978  ops/ms
ClientGrpc.getUser                         thrpt       3   7.924 ± 2.673  ops/ms
ClientGrpc.listUser                        thrpt       3   6.815 ± 5.516  ops/ms
ClientGrpc.createUser                       avgt       3   3.739 ± 0.971   ms/op
ClientGrpc.existUser                        avgt       3   3.682 ± 1.035   ms/op
ClientGrpc.getUser                          avgt       3   3.827 ± 0.364   ms/op
ClientGrpc.listUser                         avgt       3   4.955 ± 2.670   ms/op
ClientGrpc.createUser                     sample  261307   3.676 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.841           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.360           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.695           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.120           ms/op
ClientGrpc.existUser                      sample  262080   3.662 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.743           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.536           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.414           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          39.322           ms/op
ClientGrpc.getUser                        sample  249545   3.848 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.034           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.705           ms/op
ClientGrpc.listUser                       sample  208097   4.613 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.597           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.770           ms/op
