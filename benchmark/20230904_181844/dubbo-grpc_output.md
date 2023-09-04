# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ops/ms
# Warmup Iteration   2: 6.396 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.543 ops/ms
Iteration   2: 8.779 ops/ms
Iteration   3: 8.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.677 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (8.543, 8.677, 8.779), stdev = 0.121
  CI (99.9%): [6.473, 10.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.786 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 9.080 ops/ms
Iteration   1: 9.266 ops/ms
Iteration   2: 9.169 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.298 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (9.169, 9.298, 9.458), stdev = 0.147
  CI (99.9%): [6.612, 11.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ops/ms
# Warmup Iteration   2: 8.110 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.724 ops/ms
Iteration   2: 8.681 ops/ms
Iteration   3: 8.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.670 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (8.604, 8.670, 8.724), stdev = 0.061
  CI (99.9%): [7.553, 9.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ops/ms
# Warmup Iteration   2: 5.789 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.421 ops/ms
Iteration   2: 6.524 ops/ms
Iteration   3: 6.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.492 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (6.421, 6.492, 6.530), stdev = 0.061
  CI (99.9%): [5.378, 7.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.710 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.029 ms/op
Iteration   1: 3.623 ±(99.9%) 0.003 ms/op
Iteration   2: 3.593 ±(99.9%) 0.004 ms/op
Iteration   3: 3.727 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.648 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.593, 3.648, 3.727), stdev = 0.070
  CI (99.9%): [2.365, 4.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.003 ms/op
Iteration   1: 3.508 ±(99.9%) 0.003 ms/op
Iteration   2: 3.528 ±(99.9%) 0.002 ms/op
Iteration   3: 3.700 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.579 ±(99.9%) 1.924 ms/op [Average]
  (min, avg, max) = (3.508, 3.579, 3.700), stdev = 0.105
  CI (99.9%): [1.655, 5.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.584 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.009 ms/op
Iteration   1: 4.028 ±(99.9%) 0.004 ms/op
Iteration   2: 3.967 ±(99.9%) 0.005 ms/op
Iteration   3: 3.847 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.947 ±(99.9%) 1.675 ms/op [Average]
  (min, avg, max) = (3.847, 3.947, 4.028), stdev = 0.092
  CI (99.9%): [2.272, 5.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.447 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.013 ms/op
Iteration   1: 4.624 ±(99.9%) 0.009 ms/op
Iteration   2: 4.748 ±(99.9%) 0.009 ms/op
Iteration   3: 4.733 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.702 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (4.624, 4.702, 4.748), stdev = 0.067
  CI (99.9%): [3.471, 5.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.816 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.011 ms/op
Iteration   1: 3.732 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  11.495 ms/op
                 createUser·p0.9999: 14.446 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  14.090 ms/op
                 createUser·p0.9999: 24.715 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.704 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  17.746 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254794
  mean =      3.769 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6750 
    [ 2.500,  5.000) = 238186 
    [ 5.000,  7.500) = 8487 
    [ 7.500, 10.000) = 853 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     12.619 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     26.700 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.279 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.009 ms/op
Iteration   1: 3.473 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.812 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.508 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.509 ms/op
                 existUser·p0.999:  12.708 ms/op
                 existUser·p0.9999: 27.517 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.500 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.927 ms/op
                 existUser·p0.9999: 20.017 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274640
  mean =      3.494 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16973 
    [ 2.500,  5.000) = 252230 
    [ 5.000,  7.500) = 4422 
    [ 7.500, 10.000) = 676 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     27.730 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.826 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.009 ms/op
Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  12.599 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 4.026 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  11.308 ms/op
                 getUser·p0.9999: 21.762 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  11.770 ms/op
                 getUser·p0.9999: 20.474 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240792
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5641 
    [ 2.500,  5.000) = 216194 
    [ 5.000,  7.500) = 17436 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     12.226 ms/op
     p(99.9900) =     20.278 ms/op
     p(99.9990) =     22.419 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.165 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.024 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.998 ±(99.9%) 0.015 ms/op
Iteration   1: 4.994 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  16.071 ms/op
                 listUser·p0.9999: 20.762 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 4.940 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.567 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  17.025 ms/op
                 listUser·p0.9999: 28.564 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   3: 5.020 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  26.094 ms/op
                 listUser·p0.9999: 28.832 ms/op
                 listUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192477
  mean =      4.984 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 248 
    [ 2.500,  5.000) = 127264 
    [ 5.000,  7.500) = 57665 
    [ 7.500, 10.000) = 6169 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.677 ± 2.204  ops/ms
ClientGrpc.existUser                       thrpt       3   9.298 ± 2.686  ops/ms
ClientGrpc.getUser                         thrpt       3   8.670 ± 1.117  ops/ms
ClientGrpc.listUser                        thrpt       3   6.492 ± 1.114  ops/ms
ClientGrpc.createUser                       avgt       3   3.648 ± 1.283   ms/op
ClientGrpc.existUser                        avgt       3   3.579 ± 1.924   ms/op
ClientGrpc.getUser                          avgt       3   3.947 ± 1.675   ms/op
ClientGrpc.listUser                         avgt       3   4.702 ± 1.231   ms/op
ClientGrpc.createUser                     sample  254794   3.769 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.283           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.116           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.460           ms/op
ClientGrpc.existUser                      sample  274640   3.494 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.706           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.617           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.919           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.820           ms/op
ClientGrpc.getUser                        sample  240792   3.984 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.821           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.734           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.226           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.278           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.512           ms/op
ClientGrpc.listUser                       sample  192477   4.984 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.030           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.367           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.410           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.491           ms/op
