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
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 6.963 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.826 ops/ms
Iteration   2: 8.861 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.804 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (8.726, 8.804, 8.861), stdev = 0.070
  CI (99.9%): [7.528, 10.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.562 ops/ms
# Warmup Iteration   2: 8.437 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.150 ops/ms
Iteration   2: 9.329 ops/ms
Iteration   3: 9.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.251 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (9.150, 9.251, 9.329), stdev = 0.092
  CI (99.9%): [7.577, 10.924] (assumes normal distribution)


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
# Warmup Iteration   1: 5.599 ops/ms
# Warmup Iteration   2: 8.348 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 8.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.856 ±(99.9%) 0.559 ops/ms [Average]
  (min, avg, max) = (8.826, 8.856, 8.888), stdev = 0.031
  CI (99.9%): [8.296, 9.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.770 ops/ms
# Warmup Iteration   2: 6.167 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 6.879 ops/ms
Iteration   2: 6.750 ops/ms
Iteration   3: 6.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.788 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (6.735, 6.788, 6.879), stdev = 0.079
  CI (99.9%): [5.342, 8.234] (assumes normal distribution)


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
# Warmup Iteration   1: 5.539 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.010 ms/op
Iteration   1: 3.618 ±(99.9%) 0.008 ms/op
Iteration   2: 3.494 ±(99.9%) 0.003 ms/op
Iteration   3: 3.638 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.583 ±(99.9%) 1.427 ms/op [Average]
  (min, avg, max) = (3.494, 3.583, 3.638), stdev = 0.078
  CI (99.9%): [2.156, 5.011] (assumes normal distribution)


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.002 ms/op
Iteration   1: 3.384 ±(99.9%) 0.003 ms/op
Iteration   2: 3.443 ±(99.9%) 0.004 ms/op
Iteration   3: 3.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.413 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.384, 3.413, 3.443), stdev = 0.029
  CI (99.9%): [2.877, 3.949] (assumes normal distribution)


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.004 ms/op
Iteration   1: 3.631 ±(99.9%) 0.004 ms/op
Iteration   2: 3.667 ±(99.9%) 0.005 ms/op
Iteration   3: 3.610 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.636 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.610, 3.636, 3.667), stdev = 0.029
  CI (99.9%): [3.113, 4.158] (assumes normal distribution)


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
# Warmup Iteration   1: 7.199 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.010 ms/op
Iteration   1: 4.785 ±(99.9%) 0.027 ms/op
Iteration   2: 4.721 ±(99.9%) 0.014 ms/op
Iteration   3: 4.746 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.751 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (4.721, 4.751, 4.785), stdev = 0.032
  CI (99.9%): [4.169, 5.333] (assumes normal distribution)


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
# Warmup Iteration   1: 5.382 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.009 ms/op
Iteration   1: 3.483 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  11.028 ms/op
                 createUser·p0.9999: 14.139 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 3.547 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  7.946 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.596 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  16.776 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271186
  mean =      3.541 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9129 
    [ 2.500,  5.000) = 258496 
    [ 5.000,  7.500) = 3119 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
Iteration   1: 3.311 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  7.617 ms/op
                 existUser·p0.9999: 14.533 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 3.456 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 16.797 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.537 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 19.297 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279810
  mean =      3.432 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 13409 
    [ 2.500,  3.750) = 206556 
    [ 3.750,  5.000) = 55715 
    [ 5.000,  6.250) = 2211 
    [ 6.250,  7.500) = 754 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     19.766 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 5.213 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.010 ms/op
Iteration   1: 3.628 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 13.277 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   2: 3.589 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  9.547 ms/op
                 getUser·p0.9999: 21.237 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   3: 3.598 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  8.604 ms/op
                 getUser·p0.9999: 18.602 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266157
  mean =      3.605 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7524 
    [ 2.500,  5.000) = 252922 
    [ 5.000,  7.500) = 4931 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.238 ms/op
     p(99.9900) =     20.788 ms/op
     p(99.9990) =     21.902 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 5.726 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.775 ±(99.9%) 0.014 ms/op
Iteration   1: 4.792 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  15.077 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 4.800 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.609 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.943 ms/op
                 listUser·p0.9999: 30.659 ms/op
                 listUser·p1.00:   31.130 ms/op

Iteration   3: 4.775 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  19.761 ms/op
                 listUser·p0.9999: 33.771 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200462
  mean =      4.789 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 339 
    [ 2.500,  5.000) = 152757 
    [ 5.000,  7.500) = 42688 
    [ 7.500, 10.000) = 3932 
    [10.000, 12.500) = 377 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.893 ms/op
     p(99.9900) =     32.565 ms/op
     p(99.9990) =     34.078 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.804 ± 1.276  ops/ms
ClientGrpc.existUser                       thrpt       3   9.251 ± 1.674  ops/ms
ClientGrpc.getUser                         thrpt       3   8.856 ± 0.559  ops/ms
ClientGrpc.listUser                        thrpt       3   6.788 ± 1.446  ops/ms
ClientGrpc.createUser                       avgt       3   3.583 ± 1.427   ms/op
ClientGrpc.existUser                        avgt       3   3.413 ± 0.536   ms/op
ClientGrpc.getUser                          avgt       3   3.636 ± 0.523   ms/op
ClientGrpc.listUser                         avgt       3   4.751 ± 0.582   ms/op
ClientGrpc.createUser                     sample  271186   3.541 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.452           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.857           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  279810   3.432 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.853           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.842           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.792           ms/op
ClientGrpc.getUser                        sample  266157   3.605 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.691           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.238           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.788           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  200462   4.789 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.044           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.565           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
