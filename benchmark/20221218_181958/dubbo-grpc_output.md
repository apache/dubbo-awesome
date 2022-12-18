# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.234 ops/ms
# Warmup Iteration   2: 6.846 ops/ms
# Warmup Iteration   3: 8.035 ops/ms
Iteration   1: 8.247 ops/ms
Iteration   2: 8.335 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.234 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (8.119, 8.234, 8.335), stdev = 0.109
  CI (99.9%): [6.254, 10.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.894 ops/ms
# Warmup Iteration   2: 8.223 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.703 ±(99.9%) 3.429 ops/ms [Average]
  (min, avg, max) = (8.500, 8.703, 8.872), stdev = 0.188
  CI (99.9%): [5.274, 12.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.786 ops/ms
# Warmup Iteration   2: 7.981 ops/ms
# Warmup Iteration   3: 8.078 ops/ms
Iteration   1: 8.257 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.295 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (8.257, 8.295, 8.352), stdev = 0.050
  CI (99.9%): [7.375, 9.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 6.044 ops/ms
# Warmup Iteration   3: 6.515 ops/ms
Iteration   1: 6.607 ops/ms
Iteration   2: 6.482 ops/ms
Iteration   3: 6.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.614 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (6.482, 6.614, 6.752), stdev = 0.135
  CI (99.9%): [4.151, 9.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.247 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.013 ms/op
Iteration   1: 3.835 ±(99.9%) 0.002 ms/op
Iteration   2: 3.911 ±(99.9%) 0.003 ms/op
Iteration   3: 3.840 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.862 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.835, 3.862, 3.911), stdev = 0.043
  CI (99.9%): [3.085, 4.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.003 ms/op
Iteration   1: 3.772 ±(99.9%) 0.003 ms/op
Iteration   2: 3.657 ±(99.9%) 0.004 ms/op
Iteration   3: 3.671 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.700 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.657, 3.700, 3.772), stdev = 0.063
  CI (99.9%): [2.555, 4.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.005 ms/op
Iteration   1: 3.815 ±(99.9%) 0.003 ms/op
Iteration   2: 3.907 ±(99.9%) 0.003 ms/op
Iteration   3: 3.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.848 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.815, 3.848, 3.907), stdev = 0.051
  CI (99.9%): [2.918, 4.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.700 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.925 ±(99.9%) 0.023 ms/op
Iteration   1: 5.021 ±(99.9%) 0.017 ms/op
Iteration   2: 4.912 ±(99.9%) 0.011 ms/op
Iteration   3: 4.796 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.910 ±(99.9%) 2.050 ms/op [Average]
  (min, avg, max) = (4.796, 4.910, 5.021), stdev = 0.112
  CI (99.9%): [2.860, 6.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.455 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.265 ms/op
                 createUser·p0.999:  10.403 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.196 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 22.519 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.023 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  19.940 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246703
  mean =      3.893 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6223 
    [ 2.500,  5.000) = 222607 
    [ 5.000,  7.500) = 16029 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     11.387 ms/op
     p(99.9900) =     25.089 ms/op
     p(99.9990) =     26.874 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.910 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.010 ms/op
Iteration   1: 3.665 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 23.208 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.602 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  11.554 ms/op
                 existUser·p0.9999: 23.011 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   3: 3.643 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 26.695 ms/op
                 existUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263996
  mean =      3.636 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9593 
    [ 2.500,  5.000) = 245035 
    [ 5.000,  7.500) = 8030 
    [ 7.500, 10.000) = 888 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     24.419 ms/op
     p(99.9990) =     27.057 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.376 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.819 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  14.473 ms/op
                 getUser·p0.9999: 29.905 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  11.051 ms/op
                 getUser·p0.9999: 24.660 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  12.886 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247809
  mean =      3.873 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7618 
    [ 2.500,  5.000) = 222252 
    [ 5.000,  7.500) = 16078 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     30.823 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.370 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.167 ±(99.9%) 0.021 ms/op
Iteration   1: 5.210 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.605 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  18.403 ms/op
                 listUser·p0.9999: 26.575 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 5.177 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  19.664 ms/op
                 listUser·p0.9999: 24.387 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 5.209 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.746 ms/op
                 listUser·p0.999:  28.279 ms/op
                 listUser·p0.9999: 31.682 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184591
  mean =      5.198 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1225 
    [ 2.500,  5.000) = 98363 
    [ 5.000,  7.500) = 72741 
    [ 7.500, 10.000) = 10646 
    [10.000, 12.500) = 1121 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     30.885 ms/op
     p(99.9990) =     32.867 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.234 ± 1.980  ops/ms
ClientGrpc.existUser                       thrpt       3   8.703 ± 3.429  ops/ms
ClientGrpc.getUser                         thrpt       3   8.295 ± 0.920  ops/ms
ClientGrpc.listUser                        thrpt       3   6.614 ± 2.463  ops/ms
ClientGrpc.createUser                       avgt       3   3.862 ± 0.777   ms/op
ClientGrpc.existUser                        avgt       3   3.700 ± 1.145   ms/op
ClientGrpc.getUser                          avgt       3   3.848 ± 0.930   ms/op
ClientGrpc.listUser                         avgt       3   4.910 ± 2.050   ms/op
ClientGrpc.createUser                     sample  246703   3.893 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.866           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.062           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.089           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.001           ms/op
ClientGrpc.existUser                      sample  263996   3.636 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.329           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.234           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.190           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.419           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.132           ms/op
ClientGrpc.getUser                        sample  247809   3.873 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.776           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.738           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.620           ms/op
ClientGrpc.listUser                       sample  184591   5.198 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.605           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.848           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.814           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.332           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.885           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.669           ms/op
