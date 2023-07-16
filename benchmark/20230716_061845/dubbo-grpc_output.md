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
# Warmup Iteration   1: 4.875 ops/ms
# Warmup Iteration   2: 9.315 ops/ms
# Warmup Iteration   3: 10.266 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.681 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (10.608, 10.681, 10.795), stdev = 0.100
  CI (99.9%): [8.855, 12.506] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 10.543 ops/ms
# Warmup Iteration   3: 11.192 ops/ms
Iteration   1: 11.271 ops/ms
Iteration   2: 11.241 ops/ms
Iteration   3: 11.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.210 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (11.119, 11.210, 11.271), stdev = 0.081
  CI (99.9%): [9.737, 12.683] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ops/ms
# Warmup Iteration   2: 10.391 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.667 ±(99.9%) 0.615 ops/ms [Average]
  (min, avg, max) = (10.638, 10.667, 10.704), stdev = 0.034
  CI (99.9%): [10.052, 11.282] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.477 ops/ms
# Warmup Iteration   2: 7.971 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 8.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.108 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (8.056, 8.108, 8.163), stdev = 0.053
  CI (99.9%): [7.132, 9.083] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.004 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.027, 3.043, 3.060), stdev = 0.017
  CI (99.9%): [2.737, 3.349] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.002 ms/op
Iteration   1: 2.905 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.916 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.905, 2.916, 2.932), stdev = 0.014
  CI (99.9%): [2.661, 3.170] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.004 ms/op
Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (2.992, 3.017, 3.041), stdev = 0.024
  CI (99.9%): [2.574, 3.460] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.009 ms/op
Iteration   1: 3.906 ±(99.9%) 0.031 ms/op
Iteration   2: 3.820 ±(99.9%) 0.009 ms/op
Iteration   3: 3.781 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.836 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.781, 3.836, 3.906), stdev = 0.064
  CI (99.9%): [2.665, 5.006] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.478 ms/op
                 createUser·p0.99:   4.431 ms/op
                 createUser·p0.999:  6.314 ms/op
                 createUser·p0.9999: 11.945 ms/op
                 createUser·p1.00:   12.222 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.935 ms/op
                 createUser·p0.9999: 12.386 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.677 ms/op
                 createUser·p0.9999: 20.571 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321401
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28052 
    [ 2.500,  5.000) = 291938 
    [ 5.000,  7.500) = 1066 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.382 ms/op
     p(99.9900) =     19.400 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
Iteration   1: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 20.421 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  6.756 ms/op
                 existUser·p0.9999: 14.727 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.789 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330541
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42511 
    [ 2.500,  5.000) = 287251 
    [ 5.000,  7.500) = 514 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.672 ms/op
     p(99.9900) =     15.300 ms/op
     p(99.9990) =     20.765 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.408 ms/op
                 getUser·p0.9999: 11.976 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 16.945 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 27.419 ms/op
                 getUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320214
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21311 
    [ 2.500,  5.000) = 297756 
    [ 5.000,  7.500) = 802 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     25.525 ms/op
     p(99.9990) =     28.016 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
Iteration   1: 3.806 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  11.873 ms/op
                 listUser·p0.9999: 16.275 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.482 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 19.298 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 3.894 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.102 ms/op
                 listUser·p0.9999: 16.704 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247066
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5952 
    [ 2.500,  5.000) = 217038 
    [ 5.000,  7.500) = 22965 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.467 ms/op
     p(99.9900) =     17.344 ms/op
     p(99.9990) =     20.237 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.681 ± 1.826  ops/ms
ClientGrpc.existUser                       thrpt       3  11.210 ± 1.473  ops/ms
ClientGrpc.getUser                         thrpt       3  10.667 ± 0.615  ops/ms
ClientGrpc.listUser                        thrpt       3   8.108 ± 0.975  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.306   ms/op
ClientGrpc.existUser                        avgt       3   2.916 ± 0.254   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.443   ms/op
ClientGrpc.listUser                         avgt       3   3.836 ± 1.170   ms/op
ClientGrpc.createUser                     sample  321401   2.986 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.382           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.400           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  330541   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.672           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  320214   2.997 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.709           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.525           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.213           ms/op
ClientGrpc.listUser                       sample  247066   3.888 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.482           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.344           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.053           ms/op
