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
# Warmup Iteration   1: 2.054 ops/ms
# Warmup Iteration   2: 5.049 ops/ms
# Warmup Iteration   3: 6.401 ops/ms
Iteration   1: 6.421 ops/ms
Iteration   2: 6.826 ops/ms
Iteration   3: 6.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.699 ±(99.9%) 4.398 ops/ms [Average]
  (min, avg, max) = (6.421, 6.699, 6.850), stdev = 0.241
  CI (99.9%): [2.301, 11.097] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ops/ms
# Warmup Iteration   2: 6.773 ops/ms
# Warmup Iteration   3: 7.242 ops/ms
Iteration   1: 7.447 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.298 ±(99.9%) 2.914 ops/ms [Average]
  (min, avg, max) = (7.130, 7.298, 7.447), stdev = 0.160
  CI (99.9%): [4.384, 10.212] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 6.451 ops/ms
# Warmup Iteration   3: 6.891 ops/ms
Iteration   1: 7.000 ops/ms
Iteration   2: 7.033 ops/ms
Iteration   3: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.008 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (6.992, 7.008, 7.033), stdev = 0.022
  CI (99.9%): [6.608, 7.409] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.191 ops/ms
# Warmup Iteration   2: 4.895 ops/ms
# Warmup Iteration   3: 5.196 ops/ms
Iteration   1: 5.058 ops/ms
Iteration   2: 5.150 ops/ms
Iteration   3: 5.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.127 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (5.058, 5.127, 5.172), stdev = 0.061
  CI (99.9%): [4.020, 6.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.001 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.837 ±(99.9%) 0.008 ms/op
Iteration   1: 4.609 ±(99.9%) 0.003 ms/op
Iteration   2: 4.745 ±(99.9%) 0.004 ms/op
Iteration   3: 4.666 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.673 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (4.609, 4.673, 4.745), stdev = 0.068
  CI (99.9%): [3.426, 5.920] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.827 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.006 ms/op
Iteration   1: 4.381 ±(99.9%) 0.004 ms/op
Iteration   2: 4.489 ±(99.9%) 0.003 ms/op
Iteration   3: 4.370 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.414 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (4.370, 4.414, 4.489), stdev = 0.066
  CI (99.9%): [3.212, 5.615] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.082 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.161 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.893 ±(99.9%) 0.020 ms/op
Iteration   1: 4.870 ±(99.9%) 0.006 ms/op
Iteration   2: 4.763 ±(99.9%) 0.005 ms/op
Iteration   3: 4.652 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.762 ±(99.9%) 1.992 ms/op [Average]
  (min, avg, max) = (4.652, 4.762, 4.870), stdev = 0.109
  CI (99.9%): [2.770, 6.753] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.225 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.873 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.333 ±(99.9%) 0.019 ms/op
Iteration   1: 6.233 ±(99.9%) 0.020 ms/op
Iteration   2: 6.140 ±(99.9%) 0.022 ms/op
Iteration   3: 5.984 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.119 ±(99.9%) 2.296 ms/op [Average]
  (min, avg, max) = (5.984, 6.119, 6.233), stdev = 0.126
  CI (99.9%): [3.823, 8.415] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.017 ms/op
Iteration   1: 4.738 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   6.554 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  12.483 ms/op
                 createUser·p0.9999: 33.268 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   2: 4.707 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  16.576 ms/op
                 createUser·p0.9999: 30.872 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   3: 4.593 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  11.502 ms/op
                 createUser·p0.9999: 31.850 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205194
  mean =      4.678 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2092 
    [ 2.500,  5.000) = 141893 
    [ 5.000,  7.500) = 57534 
    [ 7.500, 10.000) = 2824 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     12.629 ms/op
     p(99.9900) =     32.224 ms/op
     p(99.9990) =     34.469 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.707 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.816 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.454 ±(99.9%) 0.015 ms/op
Iteration   1: 4.491 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.636 ms/op
                 existUser·p0.95:   6.210 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  12.186 ms/op
                 existUser·p0.9999: 17.068 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 4.366 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  12.594 ms/op
                 existUser·p0.9999: 17.356 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 4.422 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  14.003 ms/op
                 existUser·p0.9999: 19.981 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216889
  mean =      4.425 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4294 
    [ 2.500,  5.000) = 166874 
    [ 5.000,  7.500) = 42952 
    [ 7.500, 10.000) = 2208 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     19.245 ms/op
     p(99.9990) =     20.114 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.615 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.014 ms/op
Iteration   1: 4.751 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  14.149 ms/op
                 getUser·p0.9999: 24.413 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 4.612 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  11.216 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 4.628 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  12.139 ms/op
                 getUser·p0.9999: 26.381 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 205977
  mean =      4.663 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5057 
    [ 2.500,  5.000) = 138353 
    [ 5.000,  7.500) = 58506 
    [ 7.500, 10.000) = 3493 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     12.437 ms/op
     p(99.9900) =     26.359 ms/op
     p(99.9990) =     27.093 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.919 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 7.091 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.258 ±(99.9%) 0.024 ms/op
Iteration   1: 6.097 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  18.103 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 6.118 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  19.259 ms/op
                 listUser·p0.9999: 22.343 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 6.331 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   9.929 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 30.702 ms/op
                 listUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155376
  mean =      6.180 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 29579 
    [ 5.000,  7.500) = 101595 
    [ 7.500, 10.000) = 19023 
    [10.000, 12.500) = 4040 
    [12.500, 15.000) = 696 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      5.808 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     20.664 ms/op
     p(99.9900) =     28.798 ms/op
     p(99.9990) =     30.977 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.699 ± 4.398  ops/ms
ClientGrpc.existUser                       thrpt       3   7.298 ± 2.914  ops/ms
ClientGrpc.getUser                         thrpt       3   7.008 ± 0.400  ops/ms
ClientGrpc.listUser                        thrpt       3   5.127 ± 1.107  ops/ms
ClientGrpc.createUser                       avgt       3   4.673 ± 1.247   ms/op
ClientGrpc.existUser                        avgt       3   4.414 ± 1.201   ms/op
ClientGrpc.getUser                          avgt       3   4.762 ± 1.992   ms/op
ClientGrpc.listUser                         avgt       3   6.119 ± 2.296   ms/op
ClientGrpc.createUser                     sample  205194   4.678 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.112           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.454           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.629           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.224           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.603           ms/op
ClientGrpc.existUser                      sample  216889   4.425 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.538           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.062           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.889           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.698           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.245           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  205977   4.663 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.858           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.923           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.496           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.364           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.437           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.359           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.197           ms/op
ClientGrpc.listUser                       sample  155376   6.180 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.796           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.829           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.664           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.798           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.031           ms/op
