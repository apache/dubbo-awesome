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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.011 ops/ms
# Warmup Iteration   3: 6.747 ops/ms
Iteration   1: 7.323 ops/ms
Iteration   2: 7.328 ops/ms
Iteration   3: 7.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.331 ±(99.9%) 0.195 ops/ms [Average]
  (min, avg, max) = (7.323, 7.331, 7.343), stdev = 0.011
  CI (99.9%): [7.136, 7.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 7.100 ops/ms
# Warmup Iteration   3: 7.509 ops/ms
Iteration   1: 7.465 ops/ms
Iteration   2: 7.594 ops/ms
Iteration   3: 7.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.607 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (7.465, 7.607, 7.763), stdev = 0.149
  CI (99.9%): [4.887, 10.328] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ops/ms
# Warmup Iteration   2: 6.580 ops/ms
# Warmup Iteration   3: 6.798 ops/ms
Iteration   1: 7.095 ops/ms
Iteration   2: 7.027 ops/ms
Iteration   3: 7.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.115 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (7.027, 7.115, 7.222), stdev = 0.099
  CI (99.9%): [5.314, 8.916] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 4.923 ops/ms
# Warmup Iteration   3: 5.557 ops/ms
Iteration   1: 5.643 ops/ms
Iteration   2: 5.771 ops/ms
Iteration   3: 5.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.644 ±(99.9%) 2.301 ops/ms [Average]
  (min, avg, max) = (5.518, 5.644, 5.771), stdev = 0.126
  CI (99.9%): [3.343, 7.945] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.146 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.806 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.588 ±(99.9%) 0.030 ms/op
Iteration   1: 4.383 ±(99.9%) 0.003 ms/op
Iteration   2: 4.456 ±(99.9%) 0.002 ms/op
Iteration   3: 4.368 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.402 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (4.368, 4.402, 4.456), stdev = 0.047
  CI (99.9%): [3.546, 5.259] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.270 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.003 ms/op
Iteration   1: 4.286 ±(99.9%) 0.002 ms/op
Iteration   2: 4.265 ±(99.9%) 0.002 ms/op
Iteration   3: 4.062 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.204 ±(99.9%) 2.260 ms/op [Average]
  (min, avg, max) = (4.062, 4.204, 4.286), stdev = 0.124
  CI (99.9%): [1.945, 6.464] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.159 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.003 ms/op
Iteration   1: 4.505 ±(99.9%) 0.003 ms/op
Iteration   2: 4.488 ±(99.9%) 0.003 ms/op
Iteration   3: 4.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.466 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (4.404, 4.466, 4.505), stdev = 0.054
  CI (99.9%): [3.476, 5.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.276 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.885 ±(99.9%) 0.021 ms/op
Iteration   1: 5.718 ±(99.9%) 0.016 ms/op
Iteration   2: 5.883 ±(99.9%) 0.020 ms/op
Iteration   3: 5.799 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.800 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (5.718, 5.800, 5.883), stdev = 0.083
  CI (99.9%): [4.293, 7.307] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.014 ms/op
Iteration   1: 4.431 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  10.286 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   2: 4.398 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 21.815 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 4.541 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  11.806 ms/op
                 createUser·p0.9999: 26.541 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215344
  mean =      4.456 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2825 
    [ 2.500,  5.000) = 168176 
    [ 5.000,  7.500) = 43010 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     11.725 ms/op
     p(99.9900) =     24.226 ms/op
     p(99.9990) =     26.897 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 6.107 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.444 ±(99.9%) 0.012 ms/op
Iteration   1: 4.298 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  12.937 ms/op
                 existUser·p0.9999: 17.109 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 4.174 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  9.690 ms/op
                 existUser·p0.9999: 18.918 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 4.459 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   7.789 ms/op
                 existUser·p0.999:  14.567 ms/op
                 existUser·p0.9999: 20.278 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222770
  mean =      4.307 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2813 
    [ 2.500,  5.000) = 183233 
    [ 5.000,  7.500) = 34858 
    [ 7.500, 10.000) = 1391 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     13.168 ms/op
     p(99.9900) =     18.833 ms/op
     p(99.9990) =     21.456 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 6.936 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.706 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.012 ms/op
Iteration   1: 4.467 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  10.883 ms/op
                 getUser·p0.9999: 21.447 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 4.421 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  11.379 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 4.522 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  11.155 ms/op
                 getUser·p0.9999: 21.131 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214668
  mean =      4.470 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2511 
    [ 2.500,  5.000) = 164512 
    [ 5.000,  7.500) = 45752 
    [ 7.500, 10.000) = 1523 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.059 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 7.831 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.225 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.778 ±(99.9%) 0.021 ms/op
Iteration   1: 5.686 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  16.511 ms/op
                 listUser·p0.9999: 19.898 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 5.706 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  18.633 ms/op
                 listUser·p0.9999: 22.517 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 5.663 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  23.036 ms/op
                 listUser·p0.9999: 30.432 ms/op
                 listUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168863
  mean =      5.685 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 51260 
    [ 5.000,  7.500) = 102548 
    [ 7.500, 10.000) = 12118 
    [10.000, 12.500) = 2183 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     18.781 ms/op
     p(99.9900) =     29.572 ms/op
     p(99.9990) =     31.140 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.331 ± 0.195  ops/ms
ClientGrpc.existUser                       thrpt       3   7.607 ± 2.720  ops/ms
ClientGrpc.getUser                         thrpt       3   7.115 ± 1.801  ops/ms
ClientGrpc.listUser                        thrpt       3   5.644 ± 2.301  ops/ms
ClientGrpc.createUser                       avgt       3   4.402 ± 0.857   ms/op
ClientGrpc.existUser                        avgt       3   4.204 ± 2.260   ms/op
ClientGrpc.getUser                          avgt       3   4.466 ± 0.990   ms/op
ClientGrpc.listUser                         avgt       3   5.800 ± 1.507   ms/op
ClientGrpc.createUser                     sample  215344   4.456 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.975           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.988           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.725           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.226           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.001           ms/op
ClientGrpc.existUser                      sample  222770   4.307 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.930           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.242           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.168           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.833           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.561           ms/op
ClientGrpc.getUser                        sample  214668   4.470 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.043           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.134           ms/op
ClientGrpc.listUser                       sample  168863   5.685 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.395           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.781           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.572           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.162           ms/op
