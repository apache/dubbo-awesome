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
# Warmup Iteration   1: 2.192 ops/ms
# Warmup Iteration   2: 4.874 ops/ms
# Warmup Iteration   3: 6.916 ops/ms
Iteration   1: 7.039 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.279 ±(99.9%) 4.082 ops/ms [Average]
  (min, avg, max) = (7.039, 7.279, 7.482), stdev = 0.224
  CI (99.9%): [3.197, 11.361] (assumes normal distribution)


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
# Warmup Iteration   1: 4.637 ops/ms
# Warmup Iteration   2: 7.084 ops/ms
# Warmup Iteration   3: 7.605 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.815 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.759 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (7.627, 7.759, 7.836), stdev = 0.115
  CI (99.9%): [5.662, 9.857] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ops/ms
# Warmup Iteration   2: 6.748 ops/ms
# Warmup Iteration   3: 6.896 ops/ms
Iteration   1: 7.234 ops/ms
Iteration   2: 7.161 ops/ms
Iteration   3: 7.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.219 ±(99.9%) 0.961 ops/ms [Average]
  (min, avg, max) = (7.161, 7.219, 7.263), stdev = 0.053
  CI (99.9%): [6.259, 8.180] (assumes normal distribution)


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
# Warmup Iteration   1: 3.405 ops/ms
# Warmup Iteration   2: 5.059 ops/ms
# Warmup Iteration   3: 5.552 ops/ms
Iteration   1: 5.589 ops/ms
Iteration   2: 5.499 ops/ms
Iteration   3: 5.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.601 ±(99.9%) 1.977 ops/ms [Average]
  (min, avg, max) = (5.499, 5.601, 5.714), stdev = 0.108
  CI (99.9%): [3.623, 7.578] (assumes normal distribution)


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
# Warmup Iteration   1: 6.783 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.443 ±(99.9%) 0.003 ms/op
Iteration   1: 4.494 ±(99.9%) 0.004 ms/op
Iteration   2: 4.413 ±(99.9%) 0.004 ms/op
Iteration   3: 4.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.437 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (4.403, 4.437, 4.494), stdev = 0.050
  CI (99.9%): [3.527, 5.346] (assumes normal distribution)


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
# Warmup Iteration   1: 6.523 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.005 ms/op
Iteration   1: 4.299 ±(99.9%) 0.002 ms/op
Iteration   2: 4.123 ±(99.9%) 0.003 ms/op
Iteration   3: 4.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.167 ±(99.9%) 2.126 ms/op [Average]
  (min, avg, max) = (4.078, 4.167, 4.299), stdev = 0.117
  CI (99.9%): [2.041, 6.293] (assumes normal distribution)


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
# Warmup Iteration   1: 6.549 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.009 ms/op
Iteration   1: 4.506 ±(99.9%) 0.003 ms/op
Iteration   2: 4.377 ±(99.9%) 0.004 ms/op
Iteration   3: 4.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.435 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (4.377, 4.435, 4.506), stdev = 0.065
  CI (99.9%): [3.244, 5.625] (assumes normal distribution)


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
# Warmup Iteration   1: 8.786 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.829 ±(99.9%) 0.021 ms/op
Iteration   1: 5.659 ±(99.9%) 0.042 ms/op
Iteration   2: 5.518 ±(99.9%) 0.013 ms/op
Iteration   3: 5.551 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.576 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (5.518, 5.576, 5.659), stdev = 0.074
  CI (99.9%): [4.233, 6.919] (assumes normal distribution)


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
# Warmup Iteration   1: 6.997 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.013 ms/op
Iteration   1: 4.424 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  13.393 ms/op
                 createUser·p0.9999: 34.704 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   2: 4.434 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  11.842 ms/op
                 createUser·p0.9999: 37.603 ms/op
                 createUser·p1.00:   38.142 ms/op

Iteration   3: 4.390 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.848 ms/op
                 createUser·p0.999:  13.946 ms/op
                 createUser·p0.9999: 24.445 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217298
  mean =      4.416 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5359 
    [ 2.500,  5.000) = 170192 
    [ 5.000,  7.500) = 39705 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     12.873 ms/op
     p(99.9900) =     36.652 ms/op
     p(99.9990) =     38.054 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 6.589 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.544 ±(99.9%) 0.014 ms/op
Iteration   1: 4.313 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  13.176 ms/op
                 existUser·p0.9999: 15.722 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   2: 4.338 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  15.417 ms/op
                 existUser·p0.9999: 33.161 ms/op
                 existUser·p1.00:   36.504 ms/op

Iteration   3: 4.205 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224054
  mean =      4.285 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4655 
    [ 2.500,  5.000) = 184202 
    [ 5.000,  7.500) = 33175 
    [ 7.500, 10.000) = 1300 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     35.456 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 7.080 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.801 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.011 ms/op
Iteration   1: 4.422 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  10.747 ms/op
                 getUser·p0.9999: 16.032 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 4.480 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  15.344 ms/op
                 getUser·p0.9999: 19.521 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 4.469 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  10.805 ms/op
                 getUser·p0.9999: 34.527 ms/op
                 getUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215190
  mean =      4.457 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3500 
    [ 2.500,  5.000) = 167469 
    [ 5.000,  7.500) = 42658 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     11.269 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     35.967 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 8.097 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.009 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.634 ±(99.9%) 0.020 ms/op
Iteration   1: 5.618 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.042 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 5.627 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  19.338 ms/op
                 listUser·p0.9999: 21.285 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   3: 5.524 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  20.855 ms/op
                 listUser·p0.9999: 24.664 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171648
  mean =      5.589 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 58051 
    [ 5.000,  7.500) = 100222 
    [ 7.500, 10.000) = 10851 
    [10.000, 12.500) = 1756 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     23.997 ms/op
     p(99.9990) =     30.034 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.279 ± 4.082  ops/ms
ClientGrpc.existUser                       thrpt       3   7.759 ± 2.097  ops/ms
ClientGrpc.getUser                         thrpt       3   7.219 ± 0.961  ops/ms
ClientGrpc.listUser                        thrpt       3   5.601 ± 1.977  ops/ms
ClientGrpc.createUser                       avgt       3   4.437 ± 0.909   ms/op
ClientGrpc.existUser                        avgt       3   4.167 ± 2.126   ms/op
ClientGrpc.getUser                          avgt       3   4.435 ± 1.190   ms/op
ClientGrpc.listUser                         avgt       3   5.576 ± 1.343   ms/op
ClientGrpc.createUser                     sample  217298   4.416 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.043           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.873           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.652           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.142           ms/op
ClientGrpc.existUser                      sample  224054   4.285 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.063           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.340           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.779           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.869           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.504           ms/op
ClientGrpc.getUser                        sample  215190   4.457 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.857           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.269           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.948           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.700           ms/op
ClientGrpc.listUser                       sample  171648   5.589 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.239           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.081           ms/op
