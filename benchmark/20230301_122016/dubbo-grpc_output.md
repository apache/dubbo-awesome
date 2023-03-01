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
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.103 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.724 ops/ms
Iteration   2: 6.845 ops/ms
Iteration   3: 6.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.746 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (6.668, 6.746, 6.845), stdev = 0.090
  CI (99.9%): [5.095, 8.397] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ops/ms
# Warmup Iteration   2: 7.040 ops/ms
# Warmup Iteration   3: 7.162 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 7.174 ops/ms
Iteration   3: 7.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.142 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (7.030, 7.142, 7.223), stdev = 0.100
  CI (99.9%): [5.311, 8.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 6.286 ops/ms
# Warmup Iteration   3: 6.642 ops/ms
Iteration   1: 6.814 ops/ms
Iteration   2: 6.585 ops/ms
Iteration   3: 6.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.678 ±(99.9%) 2.197 ops/ms [Average]
  (min, avg, max) = (6.585, 6.678, 6.814), stdev = 0.120
  CI (99.9%): [4.481, 8.875] (assumes normal distribution)


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
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 4.959 ops/ms
# Warmup Iteration   3: 5.439 ops/ms
Iteration   1: 5.504 ops/ms
Iteration   2: 5.597 ops/ms
Iteration   3: 5.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.543 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (5.504, 5.543, 5.597), stdev = 0.048
  CI (99.9%): [4.665, 6.420] (assumes normal distribution)


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
# Warmup Iteration   1: 7.054 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.653 ±(99.9%) 0.004 ms/op
Iteration   1: 4.662 ±(99.9%) 0.003 ms/op
Iteration   2: 4.712 ±(99.9%) 0.004 ms/op
Iteration   3: 4.787 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.720 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (4.662, 4.720, 4.787), stdev = 0.063
  CI (99.9%): [3.572, 5.869] (assumes normal distribution)


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
# Warmup Iteration   1: 6.372 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.535 ±(99.9%) 0.007 ms/op
Iteration   1: 4.480 ±(99.9%) 0.004 ms/op
Iteration   2: 4.494 ±(99.9%) 0.003 ms/op
Iteration   3: 4.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.485 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (4.480, 4.485, 4.494), stdev = 0.007
  CI (99.9%): [4.349, 4.621] (assumes normal distribution)


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
# Warmup Iteration   1: 7.069 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.904 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.008 ms/op
Iteration   1: 4.672 ±(99.9%) 0.003 ms/op
Iteration   2: 4.647 ±(99.9%) 0.003 ms/op
Iteration   3: 4.675 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.665 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (4.647, 4.665, 4.675), stdev = 0.015
  CI (99.9%): [4.387, 4.942] (assumes normal distribution)


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
# Warmup Iteration   1: 8.698 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.459 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.015 ms/op
Iteration   1: 5.560 ±(99.9%) 0.018 ms/op
Iteration   2: 5.748 ±(99.9%) 0.025 ms/op
Iteration   3: 5.910 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.739 ±(99.9%) 3.193 ms/op [Average]
  (min, avg, max) = (5.560, 5.739, 5.910), stdev = 0.175
  CI (99.9%): [2.546, 8.933] (assumes normal distribution)


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
# Warmup Iteration   1: 7.491 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.014 ms/op
Iteration   1: 4.620 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.242 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  13.108 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.899 ms/op

Iteration   2: 4.761 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  12.364 ms/op
                 createUser·p0.9999: 23.939 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 4.742 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   7.857 ms/op
                 createUser·p0.999:  13.300 ms/op
                 createUser·p0.9999: 31.425 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 203826
  mean =      4.707 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2936 
    [ 2.500,  5.000) = 131207 
    [ 5.000,  7.500) = 66747 
    [ 7.500, 10.000) = 2326 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     12.487 ms/op
     p(99.9900) =     31.543 ms/op
     p(99.9990) =     32.820 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.175 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.014 ms/op
Iteration   1: 4.494 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.359 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  13.759 ms/op
                 existUser·p0.9999: 17.482 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 4.612 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.091 ms/op
                 existUser·p0.999:  12.971 ms/op
                 existUser·p0.9999: 21.400 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 4.607 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.414 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.792 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  12.834 ms/op
                 existUser·p0.9999: 24.250 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 210042
  mean =      4.570 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5511 
    [ 2.500,  5.000) = 140840 
    [ 5.000,  7.500) = 60381 
    [ 7.500, 10.000) = 2550 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      8.311 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     21.659 ms/op
     p(99.9990) =     24.376 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 7.101 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.048 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.016 ms/op
Iteration   1: 4.862 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.743 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   6.717 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  15.247 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   2: 4.738 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  14.262 ms/op
                 getUser·p0.9999: 21.226 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 4.645 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.324 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  11.605 ms/op
                 getUser·p0.9999: 22.339 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 202212
  mean =      4.746 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3639 
    [ 2.500,  5.000) = 125103 
    [ 5.000,  7.500) = 69699 
    [ 7.500, 10.000) = 2933 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     23.492 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 8.383 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.523 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.865 ±(99.9%) 0.022 ms/op
Iteration   1: 5.765 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.891 ms/op
                 listUser·p0.999:  19.086 ms/op
                 listUser·p0.9999: 24.918 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 5.778 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 22.563 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 5.761 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 32.710 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166374
  mean =      5.768 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 51131 
    [ 5.000,  7.500) = 97134 
    [ 7.500, 10.000) = 14908 
    [10.000, 12.500) = 2381 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     33.404 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.746 ± 1.651  ops/ms
ClientGrpc.existUser                       thrpt       3   7.142 ± 1.831  ops/ms
ClientGrpc.getUser                         thrpt       3   6.678 ± 2.197  ops/ms
ClientGrpc.listUser                        thrpt       3   5.543 ± 0.877  ops/ms
ClientGrpc.createUser                       avgt       3   4.720 ± 1.149   ms/op
ClientGrpc.existUser                        avgt       3   4.485 ± 0.136   ms/op
ClientGrpc.getUser                          avgt       3   4.665 ± 0.278   ms/op
ClientGrpc.listUser                         avgt       3   5.739 ± 3.193   ms/op
ClientGrpc.createUser                     sample  203826   4.707 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.035           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.110           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.543           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.899           ms/op
ClientGrpc.existUser                      sample  210042   4.570 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.414           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.808           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.311           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.582           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.659           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.330           ms/op
ClientGrpc.getUser                        sample  202212   4.746 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.094           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.238           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.299           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  166374   5.768 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.325           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.977           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.021           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.079           ms/op
