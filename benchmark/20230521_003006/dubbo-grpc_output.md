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
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 6.190 ops/ms
# Warmup Iteration   3: 7.352 ops/ms
Iteration   1: 7.558 ops/ms
Iteration   2: 7.541 ops/ms
Iteration   3: 7.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.571 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (7.541, 7.571, 7.613), stdev = 0.038
  CI (99.9%): [6.882, 8.260] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.199 ops/ms
# Warmup Iteration   2: 7.555 ops/ms
# Warmup Iteration   3: 7.780 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 8.023 ops/ms
Iteration   3: 8.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.981 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (7.827, 7.981, 8.094), stdev = 0.139
  CI (99.9%): [5.452, 10.510] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.675 ops/ms
# Warmup Iteration   2: 7.366 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.734 ops/ms
Iteration   2: 7.716 ops/ms
Iteration   3: 7.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.751 ±(99.9%) 0.826 ops/ms [Average]
  (min, avg, max) = (7.716, 7.751, 7.802), stdev = 0.045
  CI (99.9%): [6.925, 8.576] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ops/ms
# Warmup Iteration   2: 5.481 ops/ms
# Warmup Iteration   3: 5.661 ops/ms
Iteration   1: 5.831 ops/ms
Iteration   2: 5.962 ops/ms
Iteration   3: 6.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.942 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (5.831, 5.942, 6.033), stdev = 0.103
  CI (99.9%): [4.069, 7.815] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.447 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.333 ±(99.9%) 0.007 ms/op
Iteration   1: 4.214 ±(99.9%) 0.003 ms/op
Iteration   2: 4.237 ±(99.9%) 0.002 ms/op
Iteration   3: 4.174 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.208 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (4.174, 4.208, 4.237), stdev = 0.032
  CI (99.9%): [3.621, 4.796] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.341 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.004 ms/op
Iteration   1: 4.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.945 ±(99.9%) 0.004 ms/op
Iteration   3: 4.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.997 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.945, 3.997, 4.035), stdev = 0.047
  CI (99.9%): [3.143, 4.851] (assumes normal distribution)


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
# Warmup Iteration   1: 6.671 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.004 ms/op
Iteration   1: 4.127 ±(99.9%) 0.005 ms/op
Iteration   2: 4.100 ±(99.9%) 0.005 ms/op
Iteration   3: 4.219 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.148 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (4.100, 4.148, 4.219), stdev = 0.062
  CI (99.9%): [3.010, 5.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.096 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.998 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.424 ±(99.9%) 0.018 ms/op
Iteration   1: 5.335 ±(99.9%) 0.020 ms/op
Iteration   2: 5.510 ±(99.9%) 0.017 ms/op
Iteration   3: 5.340 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.395 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (5.335, 5.395, 5.510), stdev = 0.100
  CI (99.9%): [3.578, 7.211] (assumes normal distribution)


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
# Warmup Iteration   1: 6.564 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.012 ms/op
Iteration   1: 4.236 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  12.322 ms/op
                 createUser·p0.9999: 16.985 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 4.238 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  15.634 ms/op
                 createUser·p0.9999: 18.413 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 4.325 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 27.866 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224928
  mean =      4.266 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2646 
    [ 2.500,  5.000) = 186724 
    [ 5.000,  7.500) = 33424 
    [ 7.500, 10.000) = 1541 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     13.059 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.582 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 6.177 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  9.865 ms/op
                 existUser·p0.9999: 16.801 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 4.011 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  8.915 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 3.834 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  10.136 ms/op
                 existUser·p0.9999: 33.258 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244181
  mean =      3.933 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7100 
    [ 2.500,  5.000) = 217955 
    [ 5.000,  7.500) = 18123 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     32.735 ms/op
     p(99.9990) =     34.836 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 6.509 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  10.792 ms/op
                 getUser·p0.9999: 17.245 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 4.198 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  11.253 ms/op
                 getUser·p0.9999: 19.514 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 4.263 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   7.380 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 35.619 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228305
  mean =      4.202 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4182 
    [ 2.500,  5.000) = 194528 
    [ 5.000,  7.500) = 27781 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     11.267 ms/op
     p(99.9900) =     34.811 ms/op
     p(99.9990) =     35.942 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.745 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.018 ms/op
Iteration   1: 5.273 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.832 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  15.882 ms/op
                 listUser·p0.9999: 18.941 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 5.385 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  15.706 ms/op
                 listUser·p0.9999: 27.101 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   3: 5.440 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  30.376 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178830
  mean =      5.365 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 76166 
    [ 5.000,  7.500) = 92482 
    [ 7.500, 10.000) = 8555 
    [10.000, 12.500) = 1073 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =      9.743 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     31.367 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.571 ± 0.689  ops/ms
ClientGrpc.existUser                       thrpt       3   7.981 ± 2.529  ops/ms
ClientGrpc.getUser                         thrpt       3   7.751 ± 0.826  ops/ms
ClientGrpc.listUser                        thrpt       3   5.942 ± 1.873  ops/ms
ClientGrpc.createUser                       avgt       3   4.208 ± 0.588   ms/op
ClientGrpc.existUser                        avgt       3   3.997 ± 0.854   ms/op
ClientGrpc.getUser                          avgt       3   4.148 ± 1.138   ms/op
ClientGrpc.listUser                         avgt       3   5.395 ± 1.817   ms/op
ClientGrpc.createUser                     sample  224928   4.266 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.030           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.444           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.672           ms/op
ClientGrpc.existUser                      sample  244181   3.933 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.797           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.683           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.735           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.996           ms/op
ClientGrpc.getUser                        sample  228305   4.202 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.979           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.153           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.062           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.267           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.811           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.110           ms/op
ClientGrpc.listUser                       sample  178830   5.365 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.513           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.743           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.367           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
