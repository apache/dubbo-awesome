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
# Warmup Iteration   1: 3.195 ops/ms
# Warmup Iteration   2: 6.550 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 8.550 ops/ms
Iteration   2: 8.859 ops/ms
Iteration   3: 8.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.650 ±(99.9%) 3.316 ops/ms [Average]
  (min, avg, max) = (8.540, 8.650, 8.859), stdev = 0.182
  CI (99.9%): [5.334, 11.966] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.824 ops/ms
# Warmup Iteration   2: 8.032 ops/ms
# Warmup Iteration   3: 8.862 ops/ms
Iteration   1: 9.133 ops/ms
Iteration   2: 8.955 ops/ms
Iteration   3: 8.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.994 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (8.893, 8.994, 9.133), stdev = 0.125
  CI (99.9%): [6.721, 11.267] (assumes normal distribution)


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
# Warmup Iteration   1: 5.577 ops/ms
# Warmup Iteration   2: 8.219 ops/ms
# Warmup Iteration   3: 8.502 ops/ms
Iteration   1: 8.627 ops/ms
Iteration   2: 8.622 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.601 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (8.554, 8.601, 8.627), stdev = 0.041
  CI (99.9%): [7.852, 9.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.352 ops/ms
# Warmup Iteration   2: 6.290 ops/ms
# Warmup Iteration   3: 6.544 ops/ms
Iteration   1: 6.423 ops/ms
Iteration   2: 6.495 ops/ms
Iteration   3: 6.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.489 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (6.423, 6.489, 6.549), stdev = 0.064
  CI (99.9%): [5.328, 7.649] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.521 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.006 ms/op
Iteration   1: 3.831 ±(99.9%) 0.005 ms/op
Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
Iteration   3: 3.760 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.790 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.760, 3.790, 3.831), stdev = 0.037
  CI (99.9%): [3.119, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.004 ms/op
Iteration   1: 3.595 ±(99.9%) 0.004 ms/op
Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
Iteration   3: 3.516 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.582 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.516, 3.582, 3.635), stdev = 0.061
  CI (99.9%): [2.475, 4.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.842 ±(99.9%) 0.004 ms/op
Iteration   2: 3.805 ±(99.9%) 0.004 ms/op
Iteration   3: 3.736 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.794 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.736, 3.794, 3.842), stdev = 0.054
  CI (99.9%): [2.815, 4.774] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.092 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.900 ±(99.9%) 0.022 ms/op
Iteration   1: 5.010 ±(99.9%) 0.013 ms/op
Iteration   2: 4.716 ±(99.9%) 0.017 ms/op
Iteration   3: 4.741 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.822 ±(99.9%) 2.979 ms/op [Average]
  (min, avg, max) = (4.716, 4.822, 5.010), stdev = 0.163
  CI (99.9%): [1.844, 7.801] (assumes normal distribution)


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
# Warmup Iteration   1: 5.557 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.012 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  12.976 ms/op
                 createUser·p0.9999: 19.890 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.820 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  14.137 ms/op
                 createUser·p0.9999: 19.976 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.717 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.793 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251843
  mean =      3.810 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13057 
    [ 2.500,  5.000) = 220451 
    [ 5.000,  7.500) = 16076 
    [ 7.500, 10.000) = 1794 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.353 ms/op
     p(99.9000) =     12.785 ms/op
     p(99.9900) =     25.645 ms/op
     p(99.9990) =     27.540 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.758 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
Iteration   1: 3.592 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  11.452 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 16.073 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  9.274 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273986
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18607 
    [ 2.500,  5.000) = 245610 
    [ 5.000,  7.500) = 8349 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     12.223 ms/op
     p(99.9900) =     18.403 ms/op
     p(99.9990) =     20.259 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.518 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 15.192 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   2: 3.777 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  13.659 ms/op
                 getUser·p0.9999: 16.573 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.727 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  10.915 ms/op
                 getUser·p0.9999: 20.508 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254266
  mean =      3.773 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10429 
    [ 2.500,  5.000) = 228620 
    [ 5.000,  7.500) = 13646 
    [ 7.500, 10.000) = 1078 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     12.263 ms/op
     p(99.9900) =     17.798 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 7.341 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.207 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.019 ms/op
Iteration   1: 4.786 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.127 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.787 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  16.421 ms/op
                 listUser·p0.9999: 21.288 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.975 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 40.145 ms/op
                 listUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197937
  mean =      4.848 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 139804 
    [ 5.000, 10.000) = 57021 
    [10.000, 15.000) = 811 
    [15.000, 20.000) = 144 
    [20.000, 25.000) = 125 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     40.568 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.650 ± 3.316  ops/ms
ClientGrpc.existUser                       thrpt       3   8.994 ± 2.273  ops/ms
ClientGrpc.getUser                         thrpt       3   8.601 ± 0.749  ops/ms
ClientGrpc.listUser                        thrpt       3   6.489 ± 1.160  ops/ms
ClientGrpc.createUser                       avgt       3   3.790 ± 0.671   ms/op
ClientGrpc.existUser                        avgt       3   3.582 ± 1.107   ms/op
ClientGrpc.getUser                          avgt       3   3.794 ± 0.979   ms/op
ClientGrpc.listUser                         avgt       3   4.822 ± 2.979   ms/op
ClientGrpc.createUser                     sample  251843   3.810 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.353           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.785           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.645           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  273986   3.506 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.676           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.223           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.403           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  254266   3.773 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.263           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.798           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  197937   4.848 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.175           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.973           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.142           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.632           ms/op
