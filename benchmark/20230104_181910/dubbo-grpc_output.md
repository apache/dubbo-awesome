# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 4.970 ops/ms
# Warmup Iteration   3: 6.429 ops/ms
Iteration   1: 6.676 ops/ms
Iteration   2: 6.838 ops/ms
Iteration   3: 6.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.737 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (6.676, 6.737, 6.838), stdev = 0.088
  CI (99.9%): [5.136, 8.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ops/ms
# Warmup Iteration   2: 6.663 ops/ms
# Warmup Iteration   3: 6.933 ops/ms
Iteration   1: 7.050 ops/ms
Iteration   2: 7.000 ops/ms
Iteration   3: 7.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.065 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (7.000, 7.065, 7.143), stdev = 0.073
  CI (99.9%): [5.734, 8.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 5.897 ops/ms
# Warmup Iteration   3: 6.326 ops/ms
Iteration   1: 6.507 ops/ms
Iteration   2: 6.318 ops/ms
Iteration   3: 6.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.521 ±(99.9%) 3.827 ops/ms [Average]
  (min, avg, max) = (6.318, 6.521, 6.737), stdev = 0.210
  CI (99.9%): [2.694, 10.347] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 4.980 ops/ms
# Warmup Iteration   3: 5.310 ops/ms
Iteration   1: 5.357 ops/ms
Iteration   2: 5.449 ops/ms
Iteration   3: 5.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.412 ±(99.9%) 0.887 ops/ms [Average]
  (min, avg, max) = (5.357, 5.412, 5.449), stdev = 0.049
  CI (99.9%): [4.525, 6.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.074 ±(99.9%) 0.004 ms/op
Iteration   1: 4.683 ±(99.9%) 0.006 ms/op
Iteration   2: 4.624 ±(99.9%) 0.003 ms/op
Iteration   3: 4.527 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.611 ±(99.9%) 1.439 ms/op [Average]
  (min, avg, max) = (4.527, 4.611, 4.683), stdev = 0.079
  CI (99.9%): [3.172, 6.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.924 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.570 ±(99.9%) 0.004 ms/op
Iteration   1: 4.474 ±(99.9%) 0.002 ms/op
Iteration   2: 4.512 ±(99.9%) 0.005 ms/op
Iteration   3: 4.349 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.445 ±(99.9%) 1.558 ms/op [Average]
  (min, avg, max) = (4.349, 4.445, 4.512), stdev = 0.085
  CI (99.9%): [2.887, 6.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.586 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.780 ±(99.9%) 0.005 ms/op
Iteration   1: 4.677 ±(99.9%) 0.004 ms/op
Iteration   2: 4.568 ±(99.9%) 0.004 ms/op
Iteration   3: 4.816 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.687 ±(99.9%) 2.264 ms/op [Average]
  (min, avg, max) = (4.568, 4.687, 4.816), stdev = 0.124
  CI (99.9%): [2.423, 6.951] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.424 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.566 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.949 ±(99.9%) 0.012 ms/op
Iteration   1: 5.865 ±(99.9%) 0.018 ms/op
Iteration   2: 5.841 ±(99.9%) 0.017 ms/op
Iteration   3: 5.990 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.899 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (5.841, 5.899, 5.990), stdev = 0.080
  CI (99.9%): [4.436, 7.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.967 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.017 ms/op
Iteration   1: 4.785 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  12.558 ms/op
                 createUser·p0.9999: 32.330 ms/op
                 createUser·p1.00:   33.358 ms/op

Iteration   2: 4.737 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.578 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  17.019 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   3: 4.757 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.598 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  14.611 ms/op
                 createUser·p0.9999: 23.850 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201603
  mean =      4.760 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3149 
    [ 2.500,  5.000) = 125323 
    [ 5.000,  7.500) = 68576 
    [ 7.500, 10.000) = 3535 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     15.148 ms/op
     p(99.9900) =     31.043 ms/op
     p(99.9990) =     32.570 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.544 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.016 ms/op
Iteration   1: 4.703 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  14.187 ms/op
                 existUser·p0.9999: 23.894 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 4.546 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.775 ms/op
                 existUser·p0.99:   9.407 ms/op
                 existUser·p0.999:  14.190 ms/op
                 existUser·p0.9999: 19.230 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 4.539 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.791 ms/op
                 existUser·p0.99:   9.840 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 26.834 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 208841
  mean =      4.595 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6133 
    [ 2.500,  5.000) = 146081 
    [ 5.000,  7.500) = 49084 
    [ 7.500, 10.000) = 5785 
    [10.000, 12.500) = 1127 
    [12.500, 15.000) = 482 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.415 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.308 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.016 ms/op
Iteration   1: 4.678 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  12.609 ms/op
                 getUser·p0.9999: 21.919 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 4.727 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  14.933 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 4.544 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 39.059 ms/op
                 getUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206629
  mean =      4.649 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4867 
    [ 2.500,  5.000) = 135684 
    [ 5.000,  7.500) = 62138 
    [ 7.500, 10.000) = 3077 
    [10.000, 12.500) = 614 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     12.874 ms/op
     p(99.9900) =     37.115 ms/op
     p(99.9990) =     39.383 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.986 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.534 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.999 ±(99.9%) 0.025 ms/op
Iteration   1: 6.047 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.569 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 25.759 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   2: 6.305 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   3: 6.269 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  22.643 ms/op
                 listUser·p0.9999: 32.329 ms/op
                 listUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154729
  mean =      6.205 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 37785 
    [ 5.000,  7.500) = 86985 
    [ 7.500, 10.000) = 24695 
    [10.000, 12.500) = 4097 
    [12.500, 15.000) = 630 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      8.454 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     21.057 ms/op
     p(99.9900) =     30.150 ms/op
     p(99.9990) =     32.857 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.737 ± 1.601  ops/ms
ClientGrpc.existUser                       thrpt       3   7.065 ± 1.331  ops/ms
ClientGrpc.getUser                         thrpt       3   6.521 ± 3.827  ops/ms
ClientGrpc.listUser                        thrpt       3   5.412 ± 0.887  ops/ms
ClientGrpc.createUser                       avgt       3   4.611 ± 1.439   ms/op
ClientGrpc.existUser                        avgt       3   4.445 ± 1.558   ms/op
ClientGrpc.getUser                          avgt       3   4.687 ± 2.264   ms/op
ClientGrpc.listUser                         avgt       3   5.899 ± 1.462   ms/op
ClientGrpc.createUser                     sample  201603   4.760 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.077           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.595           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.148           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.043           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.358           ms/op
ClientGrpc.existUser                      sample  208841   4.595 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.013           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.939           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.699           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.483           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.280           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  206629   4.649 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.161           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.874           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          37.115           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          39.453           ms/op
ClientGrpc.listUser                       sample  154729   6.205 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.335           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.829           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.150           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.965           ms/op
