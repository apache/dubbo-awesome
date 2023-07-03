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
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 6.483 ops/ms
# Warmup Iteration   3: 7.834 ops/ms
Iteration   1: 8.335 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.395 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (8.321, 8.395, 8.529), stdev = 0.116
  CI (99.9%): [6.273, 10.517] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.933 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 8.905 ops/ms
Iteration   1: 8.868 ops/ms
Iteration   2: 8.926 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.980 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (8.868, 8.980, 9.147), stdev = 0.147
  CI (99.9%): [6.301, 11.659] (assumes normal distribution)


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
# Warmup Iteration   1: 5.650 ops/ms
# Warmup Iteration   2: 7.950 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.351 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.582 ±(99.9%) 3.663 ops/ms [Average]
  (min, avg, max) = (8.351, 8.582, 8.709), stdev = 0.201
  CI (99.9%): [4.920, 12.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.334 ops/ms
# Warmup Iteration   2: 6.162 ops/ms
# Warmup Iteration   3: 6.665 ops/ms
Iteration   1: 6.677 ops/ms
Iteration   2: 6.605 ops/ms
Iteration   3: 6.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.667 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (6.605, 6.667, 6.718), stdev = 0.057
  CI (99.9%): [5.620, 7.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.677 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.003 ms/op
Iteration   1: 3.789 ±(99.9%) 0.006 ms/op
Iteration   2: 3.691 ±(99.9%) 0.004 ms/op
Iteration   3: 3.719 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.691, 3.733, 3.789), stdev = 0.050
  CI (99.9%): [2.818, 4.648] (assumes normal distribution)


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.003 ms/op
Iteration   1: 3.549 ±(99.9%) 0.003 ms/op
Iteration   2: 3.592 ±(99.9%) 0.003 ms/op
Iteration   3: 3.574 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.572 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (3.549, 3.572, 3.592), stdev = 0.022
  CI (99.9%): [3.175, 3.968] (assumes normal distribution)


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
# Warmup Iteration   1: 5.289 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.004 ms/op
Iteration   1: 3.728 ±(99.9%) 0.004 ms/op
Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
Iteration   3: 3.687 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.728 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.687, 3.728, 3.770), stdev = 0.041
  CI (99.9%): [2.972, 4.485] (assumes normal distribution)


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
# Warmup Iteration   1: 6.680 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.425 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.839 ±(99.9%) 0.010 ms/op
Iteration   1: 4.848 ±(99.9%) 0.014 ms/op
Iteration   2: 4.641 ±(99.9%) 0.013 ms/op
Iteration   3: 4.851 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.780 ±(99.9%) 2.196 ms/op [Average]
  (min, avg, max) = (4.641, 4.780, 4.851), stdev = 0.120
  CI (99.9%): [2.584, 6.976] (assumes normal distribution)


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
# Warmup Iteration   1: 5.683 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  11.339 ms/op
                 createUser·p0.9999: 15.237 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  13.047 ms/op
                 createUser·p0.9999: 17.412 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  10.851 ms/op
                 createUser·p0.9999: 34.767 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257050
  mean =      3.736 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6794 
    [ 2.500,  5.000) = 240243 
    [ 5.000,  7.500) = 8621 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     11.336 ms/op
     p(99.9900) =     34.229 ms/op
     p(99.9990) =     35.053 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 5.199 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.008 ms/op
Iteration   1: 3.572 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.453 ms/op
                 existUser·p0.999:  12.172 ms/op
                 existUser·p0.9999: 19.057 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.580 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.277 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 22.156 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.506 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 26.964 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270305
  mean =      3.552 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10597 
    [ 2.500,  5.000) = 252386 
    [ 5.000,  7.500) = 6117 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     26.213 ms/op
     p(99.9990) =     32.385 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 5.463 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.010 ms/op
Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.536 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  13.759 ms/op
                 getUser·p0.9999: 17.726 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.698 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  14.039 ms/op
                 getUser·p0.9999: 16.062 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.457 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257403
  mean =      3.729 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 9234 
    [ 2.500,  3.750) = 141451 
    [ 3.750,  5.000) = 94960 
    [ 5.000,  6.250) = 8573 
    [ 6.250,  7.500) = 1620 
    [ 7.500,  8.750) = 696 
    [ 8.750, 10.000) = 343 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.183 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     19.042 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 6.966 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.152 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.019 ms/op
Iteration   1: 5.028 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.700 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  15.325 ms/op
                 listUser·p0.9999: 18.413 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.905 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  20.986 ms/op
                 listUser·p0.9999: 31.752 ms/op
                 listUser·p1.00:   32.113 ms/op

Iteration   3: 4.844 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.227 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  24.377 ms/op
                 listUser·p0.9999: 36.399 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194934
  mean =      4.924 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1016 
    [ 2.500,  5.000) = 131345 
    [ 5.000,  7.500) = 53844 
    [ 7.500, 10.000) = 7190 
    [10.000, 12.500) = 923 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     18.848 ms/op
     p(99.9900) =     34.767 ms/op
     p(99.9990) =     36.776 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.395 ± 2.122  ops/ms
ClientGrpc.existUser                       thrpt       3   8.980 ± 2.679  ops/ms
ClientGrpc.getUser                         thrpt       3   8.582 ± 3.663  ops/ms
ClientGrpc.listUser                        thrpt       3   6.667 ± 1.047  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 0.915   ms/op
ClientGrpc.existUser                        avgt       3   3.572 ± 0.397   ms/op
ClientGrpc.getUser                          avgt       3   3.728 ± 0.757   ms/op
ClientGrpc.listUser                         avgt       3   4.780 ± 2.196   ms/op
ClientGrpc.createUser                     sample  257050   3.736 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.447           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.365           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.336           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.229           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.127           ms/op
ClientGrpc.existUser                      sample  270305   3.552 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.840           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.223           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.213           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.440           ms/op
ClientGrpc.getUser                        sample  257403   3.729 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.496           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  194934   4.924 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.848           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.767           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.962           ms/op
