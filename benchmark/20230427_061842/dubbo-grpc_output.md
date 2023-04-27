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
# Warmup Iteration   1: 2.636 ops/ms
# Warmup Iteration   2: 6.049 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 8.226 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.160 ±(99.9%) 3.477 ops/ms [Average]
  (min, avg, max) = (7.946, 8.160, 8.309), stdev = 0.191
  CI (99.9%): [4.683, 11.637] (assumes normal distribution)


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
# Warmup Iteration   1: 5.235 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 8.946 ops/ms
Iteration   3: 8.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.848 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (8.754, 8.848, 8.946), stdev = 0.096
  CI (99.9%): [7.094, 10.601] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ops/ms
# Warmup Iteration   2: 7.412 ops/ms
# Warmup Iteration   3: 8.101 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.208 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (8.057, 8.208, 8.292), stdev = 0.130
  CI (99.9%): [5.829, 10.586] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ops/ms
# Warmup Iteration   2: 5.543 ops/ms
# Warmup Iteration   3: 6.285 ops/ms
Iteration   1: 6.345 ops/ms
Iteration   2: 6.399 ops/ms
Iteration   3: 6.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.413 ±(99.9%) 1.396 ops/ms [Average]
  (min, avg, max) = (6.345, 6.413, 6.496), stdev = 0.076
  CI (99.9%): [5.018, 7.809] (assumes normal distribution)


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
# Warmup Iteration   1: 6.101 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.898 ±(99.9%) 0.004 ms/op
Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
Iteration   3: 3.861 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.869 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.847, 3.869, 3.898), stdev = 0.027
  CI (99.9%): [3.384, 4.353] (assumes normal distribution)


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
# Warmup Iteration   1: 5.887 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.011 ms/op
Iteration   1: 3.695 ±(99.9%) 0.003 ms/op
Iteration   2: 3.575 ±(99.9%) 0.003 ms/op
Iteration   3: 3.550 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.607 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (3.550, 3.607, 3.695), stdev = 0.077
  CI (99.9%): [2.196, 5.017] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.218 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.004 ms/op
Iteration   1: 3.854 ±(99.9%) 0.005 ms/op
Iteration   2: 3.893 ±(99.9%) 0.003 ms/op
Iteration   3: 3.863 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.870 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.854, 3.870, 3.893), stdev = 0.020
  CI (99.9%): [3.496, 4.244] (assumes normal distribution)


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
# Warmup Iteration   1: 7.681 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.504 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.185 ±(99.9%) 0.020 ms/op
Iteration   1: 5.137 ±(99.9%) 0.015 ms/op
Iteration   2: 5.237 ±(99.9%) 0.042 ms/op
Iteration   3: 5.270 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.215 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (5.137, 5.215, 5.270), stdev = 0.069
  CI (99.9%): [3.953, 6.477] (assumes normal distribution)


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
# Warmup Iteration   1: 6.007 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
Iteration   1: 3.837 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  10.453 ms/op
                 createUser·p0.9999: 15.674 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 3.859 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  12.437 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  9.849 ms/op
                 createUser·p0.9999: 19.013 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250284
  mean =      3.835 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11563 
    [ 2.500,  5.000) = 221078 
    [ 5.000,  7.500) = 16543 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 5.471 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.012 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  10.619 ms/op
                 existUser·p0.9999: 15.464 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.099 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 17.481 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.748 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  15.874 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256459
  mean =      3.740 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9246 
    [ 2.500,  5.000) = 232576 
    [ 5.000,  7.500) = 13124 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     11.297 ms/op
     p(99.9900) =     19.803 ms/op
     p(99.9990) =     20.283 ms/op
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
# Warmup Iteration   1: 6.012 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 20.708 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.904 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  11.075 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  12.963 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247415
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8413 
    [ 2.500,  5.000) = 221549 
    [ 5.000,  7.500) = 16324 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     23.105 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.685 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.122 ±(99.9%) 0.018 ms/op
Iteration   1: 5.079 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.528 ms/op
                 listUser·p0.99:   9.477 ms/op
                 listUser·p0.999:  17.631 ms/op
                 listUser·p0.9999: 21.218 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 5.073 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  16.578 ms/op
                 listUser·p0.9999: 20.198 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 5.068 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  18.642 ms/op
                 listUser·p0.9999: 32.768 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189124
  mean =      5.073 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 112284 
    [ 5.000,  7.500) = 66370 
    [ 7.500, 10.000) = 8646 
    [10.000, 12.500) = 936 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     30.947 ms/op
     p(99.9990) =     32.975 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.160 ± 3.477  ops/ms
ClientGrpc.existUser                       thrpt       3   8.848 ± 1.754  ops/ms
ClientGrpc.getUser                         thrpt       3   8.208 ± 2.378  ops/ms
ClientGrpc.listUser                        thrpt       3   6.413 ± 1.396  ops/ms
ClientGrpc.createUser                       avgt       3   3.869 ± 0.484   ms/op
ClientGrpc.existUser                        avgt       3   3.607 ± 1.411   ms/op
ClientGrpc.getUser                          avgt       3   3.870 ± 0.374   ms/op
ClientGrpc.listUser                         avgt       3   5.215 ± 1.262   ms/op
ClientGrpc.createUser                     sample  250284   3.835 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.688           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.699           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.735           ms/op
ClientGrpc.existUser                      sample  256459   3.740 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.866           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.586           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.297           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.803           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  247415   3.879 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.891           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.341           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.840           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  189124   5.073 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.249           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.947           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.063           ms/op
