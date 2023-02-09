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
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 5.552 ops/ms
# Warmup Iteration   3: 6.707 ops/ms
Iteration   1: 6.815 ops/ms
Iteration   2: 6.888 ops/ms
Iteration   3: 6.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.857 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (6.815, 6.857, 6.888), stdev = 0.038
  CI (99.9%): [6.168, 7.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 6.976 ops/ms
Iteration   1: 7.106 ops/ms
Iteration   2: 7.134 ops/ms
Iteration   3: 7.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.157 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (7.106, 7.157, 7.231), stdev = 0.066
  CI (99.9%): [5.958, 8.357] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ops/ms
# Warmup Iteration   2: 6.504 ops/ms
# Warmup Iteration   3: 6.653 ops/ms
Iteration   1: 6.936 ops/ms
Iteration   2: 6.905 ops/ms
Iteration   3: 7.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.977 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (6.905, 6.977, 7.089), stdev = 0.098
  CI (99.9%): [5.183, 8.770] (assumes normal distribution)


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
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 5.419 ops/ms
Iteration   1: 5.494 ops/ms
Iteration   2: 5.512 ops/ms
Iteration   3: 5.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.441 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (5.318, 5.441, 5.512), stdev = 0.107
  CI (99.9%): [3.481, 7.402] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.969 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.752 ±(99.9%) 0.006 ms/op
Iteration   1: 4.677 ±(99.9%) 0.004 ms/op
Iteration   2: 4.676 ±(99.9%) 0.004 ms/op
Iteration   3: 4.549 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.634 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (4.549, 4.634, 4.677), stdev = 0.074
  CI (99.9%): [3.291, 5.977] (assumes normal distribution)


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
# Warmup Iteration   1: 6.276 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.005 ms/op
Iteration   1: 4.465 ±(99.9%) 0.003 ms/op
Iteration   2: 4.246 ±(99.9%) 0.004 ms/op
Iteration   3: 4.239 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.317 ±(99.9%) 2.342 ms/op [Average]
  (min, avg, max) = (4.239, 4.317, 4.465), stdev = 0.128
  CI (99.9%): [1.975, 6.658] (assumes normal distribution)


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
# Warmup Iteration   1: 7.013 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.757 ±(99.9%) 0.005 ms/op
Iteration   1: 4.762 ±(99.9%) 0.005 ms/op
Iteration   2: 4.723 ±(99.9%) 0.003 ms/op
Iteration   3: 4.713 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.733 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (4.713, 4.733, 4.762), stdev = 0.026
  CI (99.9%): [4.260, 5.206] (assumes normal distribution)


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
# Warmup Iteration   1: 7.608 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.976 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.787 ±(99.9%) 0.015 ms/op
Iteration   1: 5.960 ±(99.9%) 0.010 ms/op
Iteration   2: 5.751 ±(99.9%) 0.012 ms/op
Iteration   3: 5.680 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.797 ±(99.9%) 2.647 ms/op [Average]
  (min, avg, max) = (5.680, 5.797, 5.960), stdev = 0.145
  CI (99.9%): [3.150, 8.444] (assumes normal distribution)


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
# Warmup Iteration   1: 7.531 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.017 ms/op
Iteration   1: 4.839 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   6.758 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  12.989 ms/op
                 createUser·p0.9999: 25.028 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 4.597 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  14.760 ms/op
                 createUser·p0.9999: 28.477 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 4.567 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  13.350 ms/op
                 createUser·p0.9999: 29.589 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205815
  mean =      4.665 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2683 
    [ 2.500,  5.000) = 138527 
    [ 5.000,  7.500) = 61238 
    [ 7.500, 10.000) = 2773 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     13.471 ms/op
     p(99.9900) =     28.587 ms/op
     p(99.9990) =     30.108 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.015 ms/op
Iteration   1: 4.633 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.308 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 34.013 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 4.454 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.792 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   7.709 ms/op
                 existUser·p0.999:  11.079 ms/op
                 existUser·p0.9999: 19.229 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   3: 4.442 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.710 ms/op
                 existUser·p0.95:   6.169 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  11.307 ms/op
                 existUser·p0.9999: 41.629 ms/op
                 existUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 212829
  mean =      4.508 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 153068 
    [ 5.000, 10.000) = 59314 
    [10.000, 15.000) = 351 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     11.390 ms/op
     p(99.9900) =     40.960 ms/op
     p(99.9990) =     42.188 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


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
# Warmup Iteration   1: 6.929 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.107 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.015 ms/op
Iteration   1: 4.732 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  11.034 ms/op
                 getUser·p0.9999: 18.727 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 4.668 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 20.850 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 4.809 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   6.111 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 202764
  mean =      4.736 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4882 
    [ 2.500,  5.000) = 122881 
    [ 5.000,  7.500) = 71360 
    [ 7.500, 10.000) = 3095 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.522 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.682 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.420 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.022 ms/op
Iteration   1: 5.818 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 19.546 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 5.953 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   3: 5.847 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  20.522 ms/op
                 listUser·p0.9999: 23.352 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163454
  mean =      5.872 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 44963 
    [ 5.000,  7.500) = 98862 
    [ 7.500, 10.000) = 16456 
    [10.000, 12.500) = 2295 
    [12.500, 15.000) = 402 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      7.750 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.908 ms/op
     p(99.9990) =     27.847 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.857 ± 0.689  ops/ms
ClientGrpc.existUser                       thrpt       3   7.157 ± 1.200  ops/ms
ClientGrpc.getUser                         thrpt       3   6.977 ± 1.793  ops/ms
ClientGrpc.listUser                        thrpt       3   5.441 ± 1.961  ops/ms
ClientGrpc.createUser                       avgt       3   4.634 ± 1.343   ms/op
ClientGrpc.existUser                        avgt       3   4.317 ± 2.342   ms/op
ClientGrpc.getUser                          avgt       3   4.733 ± 0.473   ms/op
ClientGrpc.listUser                         avgt       3   5.797 ± 2.647   ms/op
ClientGrpc.createUser                     sample  205815   4.665 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.077           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.587           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.343           ms/op
ClientGrpc.existUser                      sample  212829   4.508 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.100           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.390           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          40.960           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.336           ms/op
ClientGrpc.getUser                        sample  202764   4.736 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.083           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.054           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.289           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.234           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.724           ms/op
ClientGrpc.listUser                       sample  163454   5.872 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.010           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.908           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
