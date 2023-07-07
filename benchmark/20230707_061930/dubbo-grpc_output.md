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
# Warmup Iteration   1: 2.218 ops/ms
# Warmup Iteration   2: 5.427 ops/ms
# Warmup Iteration   3: 7.095 ops/ms
Iteration   1: 7.267 ops/ms
Iteration   2: 7.028 ops/ms
Iteration   3: 7.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.229 ±(99.9%) 3.368 ops/ms [Average]
  (min, avg, max) = (7.028, 7.229, 7.391), stdev = 0.185
  CI (99.9%): [3.861, 10.596] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.045 ops/ms
# Warmup Iteration   2: 7.622 ops/ms
# Warmup Iteration   3: 8.078 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.169 ±(99.9%) 2.481 ops/ms [Average]
  (min, avg, max) = (8.049, 8.169, 8.317), stdev = 0.136
  CI (99.9%): [5.688, 10.651] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ops/ms
# Warmup Iteration   2: 6.886 ops/ms
# Warmup Iteration   3: 7.572 ops/ms
Iteration   1: 7.406 ops/ms
Iteration   2: 7.547 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.528 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (7.406, 7.528, 7.630), stdev = 0.113
  CI (99.9%): [5.462, 9.593] (assumes normal distribution)


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
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 5.495 ops/ms
# Warmup Iteration   3: 5.881 ops/ms
Iteration   1: 5.700 ops/ms
Iteration   2: 5.983 ops/ms
Iteration   3: 5.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.875 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (5.700, 5.875, 5.983), stdev = 0.153
  CI (99.9%): [3.085, 8.665] (assumes normal distribution)


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
# Warmup Iteration   1: 6.617 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.004 ms/op
Iteration   1: 4.340 ±(99.9%) 0.003 ms/op
Iteration   2: 4.287 ±(99.9%) 0.002 ms/op
Iteration   3: 4.172 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.266 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (4.172, 4.266, 4.340), stdev = 0.086
  CI (99.9%): [2.694, 5.839] (assumes normal distribution)


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
# Warmup Iteration   1: 6.028 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.002 ms/op
Iteration   1: 3.866 ±(99.9%) 0.003 ms/op
Iteration   2: 4.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.904 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.941 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (3.866, 3.941, 4.053), stdev = 0.099
  CI (99.9%): [2.143, 5.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.075 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.003 ms/op
Iteration   1: 4.350 ±(99.9%) 0.003 ms/op
Iteration   2: 4.248 ±(99.9%) 0.003 ms/op
Iteration   3: 4.274 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.291 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (4.248, 4.291, 4.350), stdev = 0.053
  CI (99.9%): [3.325, 5.256] (assumes normal distribution)


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
# Warmup Iteration   1: 7.804 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 6.290 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.460 ±(99.9%) 0.020 ms/op
Iteration   1: 5.431 ±(99.9%) 0.018 ms/op
Iteration   2: 5.229 ±(99.9%) 0.016 ms/op
Iteration   3: 5.379 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.346 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (5.229, 5.346, 5.431), stdev = 0.105
  CI (99.9%): [3.432, 7.260] (assumes normal distribution)


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
# Warmup Iteration   1: 6.829 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.013 ms/op
Iteration   1: 4.300 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  11.115 ms/op
                 createUser·p0.9999: 20.470 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 4.160 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  13.248 ms/op
                 createUser·p0.9999: 18.239 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 4.211 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.271 ms/op
                 createUser·p0.999:  11.173 ms/op
                 createUser·p0.9999: 17.956 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227311
  mean =      4.223 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4888 
    [ 2.500,  5.000) = 188052 
    [ 5.000,  7.500) = 32646 
    [ 7.500, 10.000) = 1169 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     11.775 ms/op
     p(99.9900) =     19.506 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 6.567 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.011 ms/op
Iteration   1: 4.070 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  10.853 ms/op
                 existUser·p0.9999: 15.387 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 4.107 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.048 ms/op
                 existUser·p0.999:  11.586 ms/op
                 existUser·p0.9999: 16.453 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  11.243 ms/op
                 existUser·p0.9999: 19.271 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235323
  mean =      4.077 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3721 
    [ 2.500,  5.000) = 206737 
    [ 5.000,  7.500) = 23192 
    [ 7.500, 10.000) = 1201 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     20.279 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.072 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.012 ms/op
Iteration   1: 4.238 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 4.311 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  12.177 ms/op
                 getUser·p0.9999: 20.420 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 4.219 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   6.952 ms/op
                 getUser·p0.999:  9.967 ms/op
                 getUser·p0.9999: 19.997 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225485
  mean =      4.255 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3338 
    [ 2.500,  5.000) = 184546 
    [ 5.000,  7.500) = 35739 
    [ 7.500, 10.000) = 1600 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     19.887 ms/op
     p(99.9990) =     21.224 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 7.578 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.017 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.400 ±(99.9%) 0.017 ms/op
Iteration   1: 5.431 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  17.771 ms/op
                 listUser·p0.9999: 26.287 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 5.613 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  18.323 ms/op
                 listUser·p0.9999: 22.948 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 5.510 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.433 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  21.426 ms/op
                 listUser·p0.9999: 27.722 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173907
  mean =      5.517 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 147 
    [ 2.500,  5.000) = 65001 
    [ 5.000,  7.500) = 95971 
    [ 7.500, 10.000) = 10656 
    [10.000, 12.500) = 1529 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     19.434 ms/op
     p(99.9900) =     27.054 ms/op
     p(99.9990) =     27.897 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.229 ± 3.368  ops/ms
ClientGrpc.existUser                       thrpt       3   8.169 ± 2.481  ops/ms
ClientGrpc.getUser                         thrpt       3   7.528 ± 2.066  ops/ms
ClientGrpc.listUser                        thrpt       3   5.875 ± 2.790  ops/ms
ClientGrpc.createUser                       avgt       3   4.266 ± 1.572   ms/op
ClientGrpc.existUser                        avgt       3   3.941 ± 1.798   ms/op
ClientGrpc.getUser                          avgt       3   4.291 ± 0.966   ms/op
ClientGrpc.listUser                         avgt       3   5.346 ± 1.914   ms/op
ClientGrpc.createUser                     sample  227311   4.223 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.754           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.775           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.506           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.724           ms/op
ClientGrpc.existUser                      sample  235323   4.077 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.059           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.256           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.776           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  225485   4.255 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.926           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.137           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.767           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.240           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.887           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  173907   5.517 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.433           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.054           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.115           ms/op
