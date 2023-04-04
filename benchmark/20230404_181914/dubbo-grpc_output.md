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
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.665 ops/ms
# Warmup Iteration   3: 6.637 ops/ms
Iteration   1: 6.996 ops/ms
Iteration   2: 7.040 ops/ms
Iteration   3: 7.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.093 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (6.996, 7.093, 7.245), stdev = 0.133
  CI (99.9%): [4.672, 9.515] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 7.048 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.956 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.971 ±(99.9%) 1.189 ops/ms [Average]
  (min, avg, max) = (7.914, 7.971, 8.042), stdev = 0.065
  CI (99.9%): [6.782, 9.159] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 6.345 ops/ms
# Warmup Iteration   3: 6.835 ops/ms
Iteration   1: 6.987 ops/ms
Iteration   2: 7.373 ops/ms
Iteration   3: 7.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.143 ±(99.9%) 3.713 ops/ms [Average]
  (min, avg, max) = (6.987, 7.143, 7.373), stdev = 0.204
  CI (99.9%): [3.430, 10.856] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ops/ms
# Warmup Iteration   2: 4.994 ops/ms
# Warmup Iteration   3: 5.581 ops/ms
Iteration   1: 5.559 ops/ms
Iteration   2: 5.592 ops/ms
Iteration   3: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.615 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (5.559, 5.615, 5.694), stdev = 0.070
  CI (99.9%): [4.331, 6.899] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.971 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.869 ±(99.9%) 0.004 ms/op
Iteration   1: 4.465 ±(99.9%) 0.003 ms/op
Iteration   2: 4.552 ±(99.9%) 0.003 ms/op
Iteration   3: 4.560 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.526 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (4.465, 4.526, 4.560), stdev = 0.053
  CI (99.9%): [3.565, 5.486] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.266 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.003 ms/op
Iteration   1: 4.238 ±(99.9%) 0.005 ms/op
Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
Iteration   3: 4.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.156 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (4.097, 4.156, 4.238), stdev = 0.074
  CI (99.9%): [2.812, 5.500] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.529 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.012 ms/op
Iteration   1: 4.448 ±(99.9%) 0.031 ms/op
Iteration   2: 4.520 ±(99.9%) 0.003 ms/op
Iteration   3: 4.547 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.505 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.448, 4.505, 4.547), stdev = 0.051
  CI (99.9%): [3.577, 5.433] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 6.441 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.991 ±(99.9%) 0.024 ms/op
Iteration   1: 5.808 ±(99.9%) 0.021 ms/op
Iteration   2: 5.805 ±(99.9%) 0.023 ms/op
Iteration   3: 5.733 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.782 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (5.733, 5.782, 5.808), stdev = 0.042
  CI (99.9%): [5.008, 6.556] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.013 ms/op
Iteration   1: 4.327 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.241 ms/op
                 createUser·p0.999:  13.397 ms/op
                 createUser·p0.9999: 19.451 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 4.604 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  14.019 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 4.383 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  17.434 ms/op
                 createUser·p0.9999: 22.600 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216306
  mean =      4.435 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5859 
    [ 2.500,  5.000) = 157787 
    [ 5.000,  7.500) = 50795 
    [ 7.500, 10.000) = 1315 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.298 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     27.359 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.282 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.012 ms/op
Iteration   1: 4.135 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  10.973 ms/op
                 existUser·p0.9999: 17.810 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 4.156 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  13.563 ms/op
                 existUser·p0.9999: 20.172 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 4.188 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.420 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  9.644 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230827
  mean =      4.160 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5650 
    [ 2.500,  5.000) = 194518 
    [ 5.000,  7.500) = 29407 
    [ 7.500, 10.000) = 955 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     10.789 ms/op
     p(99.9900) =     23.293 ms/op
     p(99.9990) =     23.966 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.075 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.013 ms/op
Iteration   1: 4.539 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  9.266 ms/op
                 getUser·p0.9999: 15.301 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 4.472 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  15.423 ms/op
                 getUser·p0.9999: 20.874 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   3: 4.466 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  16.620 ms/op
                 getUser·p0.9999: 22.544 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213622
  mean =      4.492 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3595 
    [ 2.500,  5.000) = 161635 
    [ 5.000,  7.500) = 46519 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.266 ms/op
     p(99.9900) =     21.877 ms/op
     p(99.9990) =     24.156 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.040 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.323 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.763 ±(99.9%) 0.020 ms/op
Iteration   1: 5.722 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.930 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 20.900 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 5.905 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.625 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 19.765 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 5.792 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 27.032 ms/op
                 listUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165395
  mean =      5.805 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 39882 
    [ 5.000,  7.500) = 110738 
    [ 7.500, 10.000) = 12439 
    [10.000, 12.500) = 1674 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     17.977 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     29.051 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.093 ± 2.422  ops/ms
ClientGrpc.existUser                       thrpt       3   7.971 ± 1.189  ops/ms
ClientGrpc.getUser                         thrpt       3   7.143 ± 3.713  ops/ms
ClientGrpc.listUser                        thrpt       3   5.615 ± 1.284  ops/ms
ClientGrpc.createUser                       avgt       3   4.526 ± 0.961   ms/op
ClientGrpc.existUser                        avgt       3   4.156 ± 1.344   ms/op
ClientGrpc.getUser                          avgt       3   4.505 ± 0.928   ms/op
ClientGrpc.listUser                         avgt       3   5.782 ± 0.774   ms/op
ClientGrpc.createUser                     sample  216306   4.435 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.932           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.291           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.297           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.984           ms/op
ClientGrpc.existUser                      sample  230827   4.160 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.420           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.789           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.293           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  213622   4.492 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.885           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.324           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.266           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.877           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.674           ms/op
ClientGrpc.listUser                       sample  165395   5.805 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.356           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.502           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.977           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.244           ms/op
