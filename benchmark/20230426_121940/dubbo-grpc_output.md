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
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 6.872 ops/ms
# Warmup Iteration   3: 8.389 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.488 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (8.356, 8.488, 8.569), stdev = 0.115
  CI (99.9%): [6.392, 10.583] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 8.898 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 8.897 ops/ms
Iteration   3: 9.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.126 ±(99.9%) 4.883 ops/ms [Average]
  (min, avg, max) = (8.897, 9.126, 9.420), stdev = 0.268
  CI (99.9%): [4.242, 14.009] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.322 ops/ms
# Warmup Iteration   2: 8.290 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.601 ops/ms
Iteration   3: 8.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.581 ±(99.9%) 0.316 ops/ms [Average]
  (min, avg, max) = (8.569, 8.581, 8.601), stdev = 0.017
  CI (99.9%): [8.265, 8.897] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.355 ops/ms
# Warmup Iteration   2: 6.063 ops/ms
# Warmup Iteration   3: 6.631 ops/ms
Iteration   1: 6.524 ops/ms
Iteration   2: 6.623 ops/ms
Iteration   3: 6.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.559 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (6.524, 6.559, 6.623), stdev = 0.056
  CI (99.9%): [5.543, 7.575] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.309 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.004 ms/op
Iteration   1: 3.717 ±(99.9%) 0.003 ms/op
Iteration   2: 3.740 ±(99.9%) 0.006 ms/op
Iteration   3: 3.674 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.711 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.674, 3.711, 3.740), stdev = 0.034
  CI (99.9%): [3.099, 4.322] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.003 ms/op
Iteration   1: 3.601 ±(99.9%) 0.004 ms/op
Iteration   2: 3.582 ±(99.9%) 0.003 ms/op
Iteration   3: 3.581 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.588 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.581, 3.588, 3.601), stdev = 0.012
  CI (99.9%): [3.375, 3.801] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.598 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.005 ms/op
Iteration   1: 3.735 ±(99.9%) 0.004 ms/op
Iteration   2: 3.730 ±(99.9%) 0.005 ms/op
Iteration   3: 3.608 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.691 ±(99.9%) 1.312 ms/op [Average]
  (min, avg, max) = (3.608, 3.691, 3.735), stdev = 0.072
  CI (99.9%): [2.379, 5.003] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.639 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.009 ms/op
Iteration   1: 4.668 ±(99.9%) 0.011 ms/op
Iteration   2: 4.728 ±(99.9%) 0.015 ms/op
Iteration   3: 4.594 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.663 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (4.594, 4.663, 4.728), stdev = 0.067
  CI (99.9%): [3.446, 5.881] (assumes normal distribution)


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  12.503 ms/op
                 createUser·p0.9999: 19.560 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.621 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.553 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  9.279 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.715 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 22.819 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259865
  mean =      3.692 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7740 
    [ 2.500,  5.000) = 243797 
    [ 5.000,  7.500) = 7095 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     10.455 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.266 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.059 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.007 ms/op
Iteration   1: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  8.511 ms/op
                 existUser·p0.9999: 19.942 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.481 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.519 ms/op
                 existUser·p0.9999: 26.758 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 3.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  11.906 ms/op
                 existUser·p0.9999: 18.579 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277976
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15258 
    [ 2.500,  5.000) = 257037 
    [ 5.000,  7.500) = 4982 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     25.481 ms/op
     p(99.9990) =     27.245 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.011 ms/op
Iteration   1: 3.686 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  9.745 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   2: 3.705 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 30.335 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 3.694 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  8.247 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259665
  mean =      3.695 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5074 
    [ 2.500,  5.000) = 247204 
    [ 5.000,  7.500) = 6525 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     10.032 ms/op
     p(99.9900) =     29.722 ms/op
     p(99.9990) =     30.520 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 7.074 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.015 ms/op
Iteration   1: 4.757 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.930 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 4.540 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  15.885 ms/op
                 listUser·p0.9999: 20.573 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.723 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.616 ms/op
                 listUser·p0.999:  19.179 ms/op
                 listUser·p0.9999: 30.900 ms/op
                 listUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205494
  mean =      4.671 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 569 
    [ 2.500,  5.000) = 156876 
    [ 5.000,  7.500) = 42351 
    [ 7.500, 10.000) = 4856 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     16.294 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     31.152 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.488 ± 2.095  ops/ms
ClientGrpc.existUser                       thrpt       3   9.126 ± 4.883  ops/ms
ClientGrpc.getUser                         thrpt       3   8.581 ± 0.316  ops/ms
ClientGrpc.listUser                        thrpt       3   6.559 ± 1.016  ops/ms
ClientGrpc.createUser                       avgt       3   3.711 ± 0.611   ms/op
ClientGrpc.existUser                        avgt       3   3.588 ± 0.213   ms/op
ClientGrpc.getUser                          avgt       3   3.691 ± 1.312   ms/op
ClientGrpc.listUser                         avgt       3   4.663 ± 1.218   ms/op
ClientGrpc.createUser                     sample  259865   3.692 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.792           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.308           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.455           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.512           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  277976   3.455 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.795           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.481           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.361           ms/op
ClientGrpc.getUser                        sample  259665   3.695 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.032           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.722           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.573           ms/op
ClientGrpc.listUser                       sample  205494   4.671 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.294           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.967           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.293           ms/op
