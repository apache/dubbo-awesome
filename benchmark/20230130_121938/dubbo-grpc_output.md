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
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 6.970 ops/ms
# Warmup Iteration   3: 8.516 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.492 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (8.316, 8.492, 8.585), stdev = 0.153
  CI (99.9%): [5.702, 11.282] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.094 ops/ms
# Warmup Iteration   2: 8.625 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 8.993 ops/ms
Iteration   2: 9.160 ops/ms
Iteration   3: 8.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.997 ±(99.9%) 2.929 ops/ms [Average]
  (min, avg, max) = (8.839, 8.997, 9.160), stdev = 0.161
  CI (99.9%): [6.069, 11.926] (assumes normal distribution)


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
# Warmup Iteration   1: 5.854 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.220 ±(99.9%) 2.961 ops/ms [Average]
  (min, avg, max) = (8.080, 8.220, 8.398), stdev = 0.162
  CI (99.9%): [5.259, 11.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ops/ms
# Warmup Iteration   2: 5.892 ops/ms
# Warmup Iteration   3: 6.429 ops/ms
Iteration   1: 6.588 ops/ms
Iteration   2: 6.564 ops/ms
Iteration   3: 6.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.655 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (6.564, 6.655, 6.812), stdev = 0.137
  CI (99.9%): [4.152, 9.157] (assumes normal distribution)


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
# Warmup Iteration   1: 5.614 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.003 ms/op
Iteration   1: 3.812 ±(99.9%) 0.004 ms/op
Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
Iteration   3: 3.868 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.820 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.780, 3.820, 3.868), stdev = 0.045
  CI (99.9%): [3.007, 4.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.836 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.004 ms/op
Iteration   1: 3.583 ±(99.9%) 0.004 ms/op
Iteration   2: 3.665 ±(99.9%) 0.005 ms/op
Iteration   3: 3.754 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.667 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.583, 3.667, 3.754), stdev = 0.085
  CI (99.9%): [2.112, 5.223] (assumes normal distribution)


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.008 ms/op
Iteration   1: 3.966 ±(99.9%) 0.003 ms/op
Iteration   2: 3.800 ±(99.9%) 0.003 ms/op
Iteration   3: 3.877 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.881 ±(99.9%) 1.515 ms/op [Average]
  (min, avg, max) = (3.800, 3.881, 3.966), stdev = 0.083
  CI (99.9%): [2.366, 5.395] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.800 ±(99.9%) 0.029 ms/op
Iteration   1: 4.907 ±(99.9%) 0.014 ms/op
Iteration   2: 4.728 ±(99.9%) 0.006 ms/op
Iteration   3: 4.782 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.806 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (4.728, 4.806, 4.907), stdev = 0.092
  CI (99.9%): [3.133, 6.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.774 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.487 ms/op
                 createUser·p0.999:  13.210 ms/op
                 createUser·p0.9999: 14.905 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.840 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  10.223 ms/op
                 createUser·p0.9999: 16.576 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 3.825 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  10.974 ms/op
                 createUser·p0.9999: 19.244 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246501
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6853 
    [ 2.500,  5.000) = 223676 
    [ 5.000,  7.500) = 14724 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     21.389 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.218 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
Iteration   1: 3.837 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.527 ms/op
                 existUser·p0.999:  11.983 ms/op
                 existUser·p0.9999: 23.964 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.715 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.237 ms/op
                 existUser·p0.999:  9.757 ms/op
                 existUser·p0.9999: 23.638 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.371 ms/op
                 existUser·p0.9999: 24.938 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259361
  mean =      3.700 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16901 
    [ 2.500,  5.000) = 230813 
    [ 5.000,  7.500) = 10230 
    [ 7.500, 10.000) = 1065 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     11.217 ms/op
     p(99.9900) =     24.021 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 5.442 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.623 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 17.787 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 27.675 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249489
  mean =      3.849 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9075 
    [ 2.500,  5.000) = 225635 
    [ 5.000,  7.500) = 13215 
    [ 7.500, 10.000) = 1240 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     27.232 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 6.430 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.192 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.017 ms/op
Iteration   1: 4.857 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.927 ms/op
                 listUser·p0.99:   8.925 ms/op
                 listUser·p0.999:  18.090 ms/op
                 listUser·p0.9999: 24.333 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.847 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.763 ms/op
                 listUser·p0.999:  15.072 ms/op
                 listUser·p0.9999: 19.543 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.832 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  20.000 ms/op
                 listUser·p0.9999: 32.735 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198148
  mean =      4.845 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 533 
    [ 2.500,  5.000) = 139210 
    [ 5.000,  7.500) = 52005 
    [ 7.500, 10.000) = 5298 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     18.083 ms/op
     p(99.9900) =     32.059 ms/op
     p(99.9990) =     34.347 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.492 ± 2.790  ops/ms
ClientGrpc.existUser                       thrpt       3   8.997 ± 2.929  ops/ms
ClientGrpc.getUser                         thrpt       3   8.220 ± 2.961  ops/ms
ClientGrpc.listUser                        thrpt       3   6.655 ± 2.502  ops/ms
ClientGrpc.createUser                       avgt       3   3.820 ± 0.814   ms/op
ClientGrpc.existUser                        avgt       3   3.667 ± 1.556   ms/op
ClientGrpc.getUser                          avgt       3   3.881 ± 1.515   ms/op
ClientGrpc.listUser                         avgt       3   4.806 ± 1.672   ms/op
ClientGrpc.createUser                     sample  246501   3.890 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.834           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.862           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.940           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  259361   3.700 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.846           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.217           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.133           ms/op
ClientGrpc.getUser                        sample  249489   3.849 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.717           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.232           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.918           ms/op
ClientGrpc.listUser                       sample  198148   4.845 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.950           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.962           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.083           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.059           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.669           ms/op
