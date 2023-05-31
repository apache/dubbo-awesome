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
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 5.343 ops/ms
# Warmup Iteration   3: 7.101 ops/ms
Iteration   1: 7.134 ops/ms
Iteration   2: 7.053 ops/ms
Iteration   3: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.112 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (7.053, 7.112, 7.148), stdev = 0.051
  CI (99.9%): [6.173, 8.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ops/ms
# Warmup Iteration   2: 6.600 ops/ms
# Warmup Iteration   3: 7.238 ops/ms
Iteration   1: 7.484 ops/ms
Iteration   2: 7.562 ops/ms
Iteration   3: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.550 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (7.484, 7.550, 7.605), stdev = 0.061
  CI (99.9%): [6.435, 8.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ops/ms
# Warmup Iteration   2: 6.617 ops/ms
# Warmup Iteration   3: 6.961 ops/ms
Iteration   1: 6.961 ops/ms
Iteration   2: 7.294 ops/ms
Iteration   3: 7.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.171 ±(99.9%) 3.341 ops/ms [Average]
  (min, avg, max) = (6.961, 7.171, 7.294), stdev = 0.183
  CI (99.9%): [3.830, 10.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.509 ops/ms
# Warmup Iteration   2: 5.335 ops/ms
# Warmup Iteration   3: 5.525 ops/ms
Iteration   1: 5.547 ops/ms
Iteration   2: 5.801 ops/ms
Iteration   3: 5.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.743 ±(99.9%) 3.193 ops/ms [Average]
  (min, avg, max) = (5.547, 5.743, 5.882), stdev = 0.175
  CI (99.9%): [2.551, 8.936] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.529 ±(99.9%) 0.006 ms/op
Iteration   1: 4.410 ±(99.9%) 0.003 ms/op
Iteration   2: 4.344 ±(99.9%) 0.002 ms/op
Iteration   3: 4.276 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.344 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (4.276, 4.344, 4.410), stdev = 0.067
  CI (99.9%): [3.127, 5.560] (assumes normal distribution)


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
# Warmup Iteration   1: 6.379 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.002 ms/op
Iteration   1: 4.006 ±(99.9%) 0.003 ms/op
Iteration   2: 4.015 ±(99.9%) 0.004 ms/op
Iteration   3: 4.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.035 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (4.006, 4.035, 4.083), stdev = 0.042
  CI (99.9%): [3.266, 4.804] (assumes normal distribution)


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
# Warmup Iteration   1: 7.194 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.006 ms/op
Iteration   1: 4.397 ±(99.9%) 0.004 ms/op
Iteration   2: 4.511 ±(99.9%) 0.003 ms/op
Iteration   3: 4.322 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.410 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (4.322, 4.410, 4.511), stdev = 0.095
  CI (99.9%): [2.676, 6.144] (assumes normal distribution)


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
# Warmup Iteration   1: 8.319 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.477 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.148 ±(99.9%) 0.027 ms/op
Iteration   1: 5.857 ±(99.9%) 0.027 ms/op
Iteration   2: 6.123 ±(99.9%) 0.012 ms/op
Iteration   3: 6.147 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.043 ±(99.9%) 2.936 ms/op [Average]
  (min, avg, max) = (5.857, 6.043, 6.147), stdev = 0.161
  CI (99.9%): [3.107, 8.978] (assumes normal distribution)


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
# Warmup Iteration   1: 7.007 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.013 ms/op
Iteration   1: 4.436 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  10.792 ms/op
                 createUser·p0.9999: 23.881 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 4.368 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  13.136 ms/op
                 createUser·p0.9999: 18.001 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 4.394 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  20.352 ms/op
                 createUser·p0.9999: 26.720 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218188
  mean =      4.399 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2337 
    [ 2.500,  5.000) = 175975 
    [ 5.000,  7.500) = 37623 
    [ 7.500, 10.000) = 1669 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     13.950 ms/op
     p(99.9900) =     26.286 ms/op
     p(99.9990) =     26.858 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 6.188 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.011 ms/op
Iteration   1: 4.286 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   7.648 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 16.180 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 4.285 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  10.721 ms/op
                 existUser·p0.9999: 16.607 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 4.192 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  10.091 ms/op
                 existUser·p0.9999: 21.717 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225546
  mean =      4.254 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2791 
    [ 2.500,  5.000) = 189256 
    [ 5.000,  7.500) = 31818 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.240 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 6.772 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.015 ms/op
Iteration   1: 4.451 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.152 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  16.178 ms/op
                 getUser·p0.9999: 32.532 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   2: 4.327 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.672 ms/op
                 getUser·p0.99:   7.914 ms/op
                 getUser·p0.999:  13.108 ms/op
                 getUser·p0.9999: 27.597 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 4.627 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   8.282 ms/op
                 getUser·p0.999:  12.827 ms/op
                 getUser·p0.9999: 28.189 ms/op
                 getUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214994
  mean =      4.465 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3430 
    [ 2.500,  5.000) = 167867 
    [ 5.000,  7.500) = 40386 
    [ 7.500, 10.000) = 2594 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     31.441 ms/op
     p(99.9990) =     33.545 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 8.077 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.718 ±(99.9%) 0.019 ms/op
Iteration   1: 5.648 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  17.522 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 5.487 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  18.301 ms/op
                 listUser·p0.9999: 25.318 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 5.553 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.171 ms/op
                 listUser·p0.99:   10.726 ms/op
                 listUser·p0.999:  19.357 ms/op
                 listUser·p0.9999: 25.532 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172641
  mean =      5.562 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 57879 
    [ 5.000,  7.500) = 101417 
    [ 7.500, 10.000) = 10997 
    [10.000, 12.500) = 1629 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.086 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     18.100 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.128 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.112 ± 0.939  ops/ms
ClientGrpc.existUser                       thrpt       3   7.550 ± 1.115  ops/ms
ClientGrpc.getUser                         thrpt       3   7.171 ± 3.341  ops/ms
ClientGrpc.listUser                        thrpt       3   5.743 ± 3.193  ops/ms
ClientGrpc.createUser                       avgt       3   4.344 ± 1.217   ms/op
ClientGrpc.existUser                        avgt       3   4.035 ± 0.769   ms/op
ClientGrpc.getUser                          avgt       3   4.410 ± 1.734   ms/op
ClientGrpc.listUser                         avgt       3   6.043 ± 2.936   ms/op
ClientGrpc.createUser                     sample  218188   4.399 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.235           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.950           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.903           ms/op
ClientGrpc.existUser                      sample  225546   4.254 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.955           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.616           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  214994   4.465 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.133           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.144           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.402           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.441           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.686           ms/op
ClientGrpc.listUser                       sample  172641   5.562 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.977           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.404           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.100           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.002           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
