# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ops/ms
# Warmup Iteration   2: 7.330 ops/ms
# Warmup Iteration   3: 8.353 ops/ms
Iteration   1: 8.709 ops/ms
Iteration   2: 8.931 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.980 ±(99.9%) 5.430 ops/ms [Average]
  (min, avg, max) = (8.709, 8.980, 9.299), stdev = 0.298
  CI (99.9%): [3.549, 14.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.949 ops/ms
# Warmup Iteration   2: 8.876 ops/ms
# Warmup Iteration   3: 9.485 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.505 ops/ms
Iteration   3: 9.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.331 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (9.236, 9.331, 9.505), stdev = 0.151
  CI (99.9%): [6.579, 12.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ops/ms
# Warmup Iteration   2: 8.582 ops/ms
# Warmup Iteration   3: 8.780 ops/ms
Iteration   1: 8.998 ops/ms
Iteration   2: 8.938 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.914 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (8.807, 8.914, 8.998), stdev = 0.098
  CI (99.9%): [7.128, 10.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ops/ms
# Warmup Iteration   2: 6.534 ops/ms
# Warmup Iteration   3: 6.571 ops/ms
Iteration   1: 6.823 ops/ms
Iteration   2: 6.878 ops/ms
Iteration   3: 6.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.803 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (6.708, 6.803, 6.878), stdev = 0.087
  CI (99.9%): [5.219, 8.386] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.360 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.005 ms/op
Iteration   1: 3.637 ±(99.9%) 0.004 ms/op
Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
Iteration   3: 3.594 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.640 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.594, 3.640, 3.688), stdev = 0.047
  CI (99.9%): [2.785, 4.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.887 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.004 ms/op
Iteration   1: 3.434 ±(99.9%) 0.003 ms/op
Iteration   2: 3.441 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.437 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (3.434, 3.437, 3.441), stdev = 0.004
  CI (99.9%): [3.373, 3.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.054 ms/op
Iteration   1: 3.673 ±(99.9%) 0.003 ms/op
Iteration   2: 3.681 ±(99.9%) 0.004 ms/op
Iteration   3: 3.651 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.668 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.651, 3.668, 3.681), stdev = 0.015
  CI (99.9%): [3.391, 3.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.649 ±(99.9%) 0.046 ms/op
Iteration   1: 4.678 ±(99.9%) 0.008 ms/op
Iteration   2: 4.732 ±(99.9%) 0.013 ms/op
Iteration   3: 4.854 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.755 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (4.678, 4.755, 4.854), stdev = 0.090
  CI (99.9%): [3.108, 6.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.499 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.009 ms/op
Iteration   1: 3.554 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   2: 3.603 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.368 ms/op
                 createUser·p0.999:  15.621 ms/op
                 createUser·p0.9999: 21.172 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.587 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  11.431 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268072
  mean =      3.581 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9965 
    [ 2.500,  5.000) = 252673 
    [ 5.000,  7.500) = 4376 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     11.812 ms/op
     p(99.9900) =     26.745 ms/op
     p(99.9990) =     29.359 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.008 ms/op
Iteration   1: 3.483 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  10.751 ms/op
                 existUser·p0.9999: 14.262 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 3.608 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.076 ms/op
                 existUser·p0.999:  13.018 ms/op
                 existUser·p0.9999: 16.601 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   3: 3.520 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.374 ms/op
                 existUser·p0.9999: 19.026 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271484
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9524 
    [ 2.500,  5.000) = 256010 
    [ 5.000,  7.500) = 4942 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     16.969 ms/op
     p(99.9990) =     19.843 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.008 ms/op
Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  13.321 ms/op
                 getUser·p0.9999: 22.725 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.673 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.063 ms/op
                 getUser·p0.999:  10.316 ms/op
                 getUser·p0.9999: 30.862 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 3.697 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  12.005 ms/op
                 getUser·p0.9999: 26.531 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258814
  mean =      3.711 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4945 
    [ 2.500,  5.000) = 246940 
    [ 5.000,  7.500) = 5748 
    [ 7.500, 10.000) = 692 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.931 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.241 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.971 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.362 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.863 ±(99.9%) 0.015 ms/op
Iteration   1: 4.836 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  15.969 ms/op
                 listUser·p0.9999: 17.524 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 4.867 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 29.140 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   3: 4.737 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.275 ms/op
                 listUser·p0.999:  18.724 ms/op
                 listUser·p0.9999: 26.140 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199397
  mean =      4.813 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 148619 
    [ 5.000,  7.500) = 45113 
    [ 7.500, 10.000) = 4488 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     26.122 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.980 ± 5.430  ops/ms
ClientGrpc.existUser                       thrpt       3   9.331 ± 2.753  ops/ms
ClientGrpc.getUser                         thrpt       3   8.914 ± 1.786  ops/ms
ClientGrpc.listUser                        thrpt       3   6.803 ± 1.583  ops/ms
ClientGrpc.createUser                       avgt       3   3.640 ± 0.854   ms/op
ClientGrpc.existUser                        avgt       3   3.437 ± 0.065   ms/op
ClientGrpc.getUser                          avgt       3   3.668 ± 0.278   ms/op
ClientGrpc.listUser                         avgt       3   4.755 ± 1.647   ms/op
ClientGrpc.createUser                     sample  268072   3.581 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.745           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.491           ms/op
ClientGrpc.existUser                      sample  271484   3.536 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.802           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.775           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.747           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.969           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  258814   3.711 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.741           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.931           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.310           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.473           ms/op
ClientGrpc.listUser                       sample  199397   4.813 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.382           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.122           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.590           ms/op
