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
# Warmup Iteration   1: 2.163 ops/ms
# Warmup Iteration   2: 6.107 ops/ms
# Warmup Iteration   3: 7.340 ops/ms
Iteration   1: 7.729 ops/ms
Iteration   2: 7.764 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.927 ±(99.9%) 5.714 ops/ms [Average]
  (min, avg, max) = (7.729, 7.927, 8.288), stdev = 0.313
  CI (99.9%): [2.213, 13.641] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.847 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.407 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.169 ±(99.9%) 4.740 ops/ms [Average]
  (min, avg, max) = (7.892, 8.169, 8.407), stdev = 0.260
  CI (99.9%): [3.429, 12.909] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ops/ms
# Warmup Iteration   2: 6.727 ops/ms
# Warmup Iteration   3: 7.424 ops/ms
Iteration   1: 7.427 ops/ms
Iteration   2: 7.396 ops/ms
Iteration   3: 7.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.395 ±(99.9%) 0.609 ops/ms [Average]
  (min, avg, max) = (7.361, 7.395, 7.427), stdev = 0.033
  CI (99.9%): [6.786, 8.004] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ops/ms
# Warmup Iteration   2: 5.534 ops/ms
# Warmup Iteration   3: 5.856 ops/ms
Iteration   1: 6.149 ops/ms
Iteration   2: 6.064 ops/ms
Iteration   3: 5.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.027 ±(99.9%) 2.631 ops/ms [Average]
  (min, avg, max) = (5.868, 6.027, 6.149), stdev = 0.144
  CI (99.9%): [3.396, 8.658] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.053 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.014 ms/op
Iteration   1: 4.282 ±(99.9%) 0.003 ms/op
Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
Iteration   3: 4.235 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.204 ±(99.9%) 1.758 ms/op [Average]
  (min, avg, max) = (4.097, 4.204, 4.282), stdev = 0.096
  CI (99.9%): [2.446, 5.963] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.956 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.003 ms/op
Iteration   1: 3.751 ±(99.9%) 0.002 ms/op
Iteration   2: 3.660 ±(99.9%) 0.003 ms/op
Iteration   3: 3.859 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.757 ±(99.9%) 1.814 ms/op [Average]
  (min, avg, max) = (3.660, 3.757, 3.859), stdev = 0.099
  CI (99.9%): [1.943, 5.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.998 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.004 ms/op
Iteration   1: 4.209 ±(99.9%) 0.005 ms/op
Iteration   2: 4.126 ±(99.9%) 0.004 ms/op
Iteration   3: 4.402 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.246 ±(99.9%) 2.587 ms/op [Average]
  (min, avg, max) = (4.126, 4.246, 4.402), stdev = 0.142
  CI (99.9%): [1.659, 6.833] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.712 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.015 ms/op
Iteration   1: 5.352 ±(99.9%) 0.015 ms/op
Iteration   2: 5.174 ±(99.9%) 0.017 ms/op
Iteration   3: 5.272 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.266 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (5.174, 5.266, 5.352), stdev = 0.090
  CI (99.9%): [3.631, 6.901] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  13.109 ms/op
                 createUser·p0.9999: 18.482 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  13.435 ms/op
                 createUser·p0.9999: 18.285 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.500 ms/op
                 createUser·p0.999:  12.194 ms/op
                 createUser·p0.9999: 18.229 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242098
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5589 
    [ 2.500,  5.000) = 210321 
    [ 5.000,  7.500) = 24596 
    [ 7.500, 10.000) = 1132 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     19.007 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 5.836 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.012 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  11.516 ms/op
                 existUser·p0.9999: 14.616 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 3.953 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  10.321 ms/op
                 existUser·p0.9999: 18.828 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 4.210 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   7.376 ms/op
                 existUser·p0.999:  10.357 ms/op
                 existUser·p0.9999: 27.172 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236032
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7371 
    [ 2.500,  5.000) = 199537 
    [ 5.000,  7.500) = 27089 
    [ 7.500, 10.000) = 1723 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     25.867 ms/op
     p(99.9990) =     28.660 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.670 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.014 ms/op
Iteration   1: 4.325 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  13.748 ms/op
                 getUser·p0.9999: 20.978 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  12.463 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 4.308 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.328 ms/op
                 getUser·p0.95:   5.888 ms/op
                 getUser·p0.99:   8.305 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 83.624 ms/op
                 getUser·p1.00:   86.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227428
  mean =      4.219 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 193099 
    [ 5.000, 10.000) = 33748 
    [10.000, 15.000) = 351 
    [15.000, 20.000) = 124 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     83.100 ms/op
     p(99.9990) =     86.376 ms/op
     p(99.9999) =     86.508 ms/op
    p(100.0000) =     86.508 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.350 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.448 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.484 ±(99.9%) 0.021 ms/op
Iteration   1: 5.189 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.412 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  18.067 ms/op
                 listUser·p0.9999: 26.007 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   2: 5.249 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  17.172 ms/op
                 listUser·p0.9999: 19.998 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 5.323 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 24.837 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182650
  mean =      5.253 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170 
    [ 2.500,  5.000) = 91467 
    [ 5.000,  7.500) = 80604 
    [ 7.500, 10.000) = 8725 
    [10.000, 12.500) = 1151 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     18.099 ms/op
     p(99.9900) =     24.934 ms/op
     p(99.9990) =     26.986 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.927 ± 5.714  ops/ms
ClientGrpc.existUser                       thrpt       3   8.169 ± 4.740  ops/ms
ClientGrpc.getUser                         thrpt       3   7.395 ± 0.609  ops/ms
ClientGrpc.listUser                        thrpt       3   6.027 ± 2.631  ops/ms
ClientGrpc.createUser                       avgt       3   4.204 ± 1.758   ms/op
ClientGrpc.existUser                        avgt       3   3.757 ± 1.814   ms/op
ClientGrpc.getUser                          avgt       3   4.246 ± 2.587   ms/op
ClientGrpc.listUser                         avgt       3   5.266 ± 1.635   ms/op
ClientGrpc.createUser                     sample  242098   3.965 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.815           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.963           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.317           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  236032   4.066 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.915           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.867           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.672           ms/op
ClientGrpc.getUser                        sample  227428   4.219 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.418           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          83.100           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          86.508           ms/op
ClientGrpc.listUser                       sample  182650   5.253 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.303           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.099           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.934           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
