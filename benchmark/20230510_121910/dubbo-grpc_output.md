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
# Warmup Iteration   1: 3.782 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.669 ops/ms
Iteration   2: 8.482 ops/ms
Iteration   3: 8.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.631 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (8.482, 8.631, 8.741), stdev = 0.133
  CI (99.9%): [6.196, 11.066] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 8.893 ops/ms
# Warmup Iteration   3: 9.372 ops/ms
Iteration   1: 9.175 ops/ms
Iteration   2: 9.328 ops/ms
Iteration   3: 9.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.171 ±(99.9%) 2.903 ops/ms [Average]
  (min, avg, max) = (9.010, 9.171, 9.328), stdev = 0.159
  CI (99.9%): [6.268, 12.074] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.605 ops/ms
# Warmup Iteration   2: 8.328 ops/ms
# Warmup Iteration   3: 8.566 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.783 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.743 ±(99.9%) 2.500 ops/ms [Average]
  (min, avg, max) = (8.590, 8.743, 8.855), stdev = 0.137
  CI (99.9%): [6.242, 11.243] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 6.736 ops/ms
Iteration   1: 6.627 ops/ms
Iteration   2: 6.810 ops/ms
Iteration   3: 6.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.776 ±(99.9%) 2.468 ops/ms [Average]
  (min, avg, max) = (6.627, 6.776, 6.891), stdev = 0.135
  CI (99.9%): [4.308, 9.244] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.003 ms/op
Iteration   1: 3.666 ±(99.9%) 0.002 ms/op
Iteration   2: 3.564 ±(99.9%) 0.003 ms/op
Iteration   3: 3.474 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.568 ±(99.9%) 1.756 ms/op [Average]
  (min, avg, max) = (3.474, 3.568, 3.666), stdev = 0.096
  CI (99.9%): [1.811, 5.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.004 ms/op
Iteration   1: 3.442 ±(99.9%) 0.002 ms/op
Iteration   2: 3.372 ±(99.9%) 0.004 ms/op
Iteration   3: 3.365 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.393 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.365, 3.393, 3.442), stdev = 0.042
  CI (99.9%): [2.619, 4.167] (assumes normal distribution)


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.003 ms/op
Iteration   1: 3.505 ±(99.9%) 0.004 ms/op
Iteration   2: 3.548 ±(99.9%) 0.006 ms/op
Iteration   3: 3.410 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.488 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (3.410, 3.488, 3.548), stdev = 0.071
  CI (99.9%): [2.199, 4.776] (assumes normal distribution)


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
# Warmup Iteration   1: 6.095 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.881 ±(99.9%) 0.015 ms/op
Iteration   1: 4.617 ±(99.9%) 0.019 ms/op
Iteration   2: 4.583 ±(99.9%) 0.021 ms/op
Iteration   3: 4.655 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.618 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (4.583, 4.618, 4.655), stdev = 0.036
  CI (99.9%): [3.963, 5.273] (assumes normal distribution)


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
# Warmup Iteration   1: 5.112 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.012 ms/op
Iteration   1: 3.667 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  13.195 ms/op
                 createUser·p0.9999: 23.929 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.626 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  21.004 ms/op
                 createUser·p0.9999: 24.522 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.798 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 24.837 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265721
  mean =      3.612 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9981 
    [ 2.500,  5.000) = 244480 
    [ 5.000,  7.500) = 9290 
    [ 7.500, 10.000) = 1324 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.443 ms/op
     p(99.9900) =     24.590 ms/op
     p(99.9990) =     25.057 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.661 ms/op
                 existUser·p0.999:  12.704 ms/op
                 existUser·p0.9999: 14.664 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.609 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   3: 3.527 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  12.834 ms/op
                 existUser·p0.9999: 20.866 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270190
  mean =      3.553 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16216 
    [ 2.500,  5.000) = 244382 
    [ 5.000,  7.500) = 7961 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.292 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     12.350 ms/op
     p(99.9900) =     32.372 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 5.378 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
Iteration   1: 3.669 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  13.060 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  11.746 ms/op
                 getUser·p0.9999: 18.210 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.752 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  14.181 ms/op
                 getUser·p0.9999: 21.118 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255191
  mean =      3.762 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10597 
    [ 2.500,  5.000) = 231302 
    [ 5.000,  7.500) = 11165 
    [ 7.500, 10.000) = 1508 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     13.052 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     22.663 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 6.083 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.975 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.016 ms/op
Iteration   1: 4.557 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  15.216 ms/op
                 listUser·p0.9999: 18.536 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.626 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.841 ms/op
                 listUser·p0.99:   8.943 ms/op
                 listUser·p0.999:  16.724 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.571 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.427 ms/op
                 listUser·p0.999:  18.320 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209464
  mean =      4.584 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 731 
    [ 2.500,  5.000) = 165130 
    [ 5.000,  7.500) = 38664 
    [ 7.500, 10.000) = 3932 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     16.534 ms/op
     p(99.9900) =     22.351 ms/op
     p(99.9990) =     23.226 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.631 ± 2.435  ops/ms
ClientGrpc.existUser                       thrpt       3   9.171 ± 2.903  ops/ms
ClientGrpc.getUser                         thrpt       3   8.743 ± 2.500  ops/ms
ClientGrpc.listUser                        thrpt       3   6.776 ± 2.468  ops/ms
ClientGrpc.createUser                       avgt       3   3.568 ± 1.756   ms/op
ClientGrpc.existUser                        avgt       3   3.393 ± 0.774   ms/op
ClientGrpc.getUser                          avgt       3   3.488 ± 1.289   ms/op
ClientGrpc.listUser                         avgt       3   4.618 ± 0.655   ms/op
ClientGrpc.createUser                     sample  265721   3.612 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.894           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.037           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.443           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.590           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  270190   3.553 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.292           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.717           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.350           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.372           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.734           ms/op
ClientGrpc.getUser                        sample  255191   3.762 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.919           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.225           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.052           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.611           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  209464   4.584 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.534           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.351           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
