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
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 5.721 ops/ms
# Warmup Iteration   3: 7.206 ops/ms
Iteration   1: 7.504 ops/ms
Iteration   2: 7.415 ops/ms
Iteration   3: 7.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.442 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (7.407, 7.442, 7.504), stdev = 0.054
  CI (99.9%): [6.463, 8.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ops/ms
# Warmup Iteration   2: 7.278 ops/ms
# Warmup Iteration   3: 7.452 ops/ms
Iteration   1: 7.792 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.968 ±(99.9%) 3.006 ops/ms [Average]
  (min, avg, max) = (7.792, 7.968, 8.118), stdev = 0.165
  CI (99.9%): [4.962, 10.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 6.627 ops/ms
# Warmup Iteration   3: 6.946 ops/ms
Iteration   1: 7.223 ops/ms
Iteration   2: 7.435 ops/ms
Iteration   3: 7.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.301 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (7.223, 7.301, 7.435), stdev = 0.116
  CI (99.9%): [5.178, 9.425] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 5.002 ops/ms
# Warmup Iteration   3: 5.528 ops/ms
Iteration   1: 5.764 ops/ms
Iteration   2: 5.730 ops/ms
Iteration   3: 5.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.687 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (5.566, 5.687, 5.764), stdev = 0.106
  CI (99.9%): [3.755, 7.618] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.750 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.018 ms/op
Iteration   1: 4.370 ±(99.9%) 0.003 ms/op
Iteration   2: 4.344 ±(99.9%) 0.003 ms/op
Iteration   3: 4.271 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.328 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.271, 4.328, 4.370), stdev = 0.051
  CI (99.9%): [3.396, 5.260] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.534 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.004 ms/op
Iteration   1: 4.190 ±(99.9%) 0.003 ms/op
Iteration   2: 4.246 ±(99.9%) 0.003 ms/op
Iteration   3: 4.276 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.237 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (4.190, 4.237, 4.276), stdev = 0.043
  CI (99.9%): [3.447, 5.028] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.699 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.004 ms/op
Iteration   1: 4.481 ±(99.9%) 0.004 ms/op
Iteration   2: 4.331 ±(99.9%) 0.004 ms/op
Iteration   3: 4.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.440 ±(99.9%) 1.738 ms/op [Average]
  (min, avg, max) = (4.331, 4.440, 4.507), stdev = 0.095
  CI (99.9%): [2.702, 6.177] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.430 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.860 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.661 ±(99.9%) 0.027 ms/op
Iteration   1: 5.495 ±(99.9%) 0.025 ms/op
Iteration   2: 5.583 ±(99.9%) 0.018 ms/op
Iteration   3: 5.554 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.544 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (5.495, 5.544, 5.583), stdev = 0.045
  CI (99.9%): [4.725, 6.363] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.692 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.014 ms/op
Iteration   1: 4.313 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.369 ms/op
                 createUser·p0.999:  14.359 ms/op
                 createUser·p0.9999: 23.973 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 4.218 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  12.998 ms/op
                 createUser·p0.9999: 18.653 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 4.219 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  10.538 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225786
  mean =      4.249 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3454 
    [ 2.500,  5.000) = 187784 
    [ 5.000,  7.500) = 33017 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     12.685 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.074 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.011 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  11.422 ms/op
                 existUser·p0.9999: 15.660 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  11.750 ms/op
                 existUser·p0.9999: 17.099 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 30.335 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243026
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5659 
    [ 2.500,  5.000) = 218990 
    [ 5.000,  7.500) = 17146 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     11.419 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     30.727 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 6.502 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.467 ±(99.9%) 0.014 ms/op
Iteration   1: 4.346 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  10.488 ms/op
                 getUser·p0.9999: 16.896 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   2: 4.200 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.672 ms/op
                 getUser·p0.999:  10.523 ms/op
                 getUser·p0.9999: 21.225 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 4.090 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  11.381 ms/op
                 getUser·p0.9999: 21.213 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228048
  mean =      4.209 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4593 
    [ 2.500,  5.000) = 194515 
    [ 5.000,  7.500) = 27355 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     20.847 ms/op
     p(99.9990) =     21.665 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 8.174 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.714 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.350 ±(99.9%) 0.019 ms/op
Iteration   1: 5.289 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  16.214 ms/op
                 listUser·p0.9999: 19.102 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   2: 5.529 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  17.616 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 5.646 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  23.437 ms/op
                 listUser·p0.9999: 36.459 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175058
  mean =      5.484 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 73384 
    [ 5.000,  7.500) = 86361 
    [ 7.500, 10.000) = 12476 
    [10.000, 12.500) = 1879 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     36.864 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.442 ± 0.979  ops/ms
ClientGrpc.existUser                       thrpt       3   7.968 ± 3.006  ops/ms
ClientGrpc.getUser                         thrpt       3   7.301 ± 2.124  ops/ms
ClientGrpc.listUser                        thrpt       3   5.687 ± 1.932  ops/ms
ClientGrpc.createUser                       avgt       3   4.328 ± 0.932   ms/op
ClientGrpc.existUser                        avgt       3   4.237 ± 0.790   ms/op
ClientGrpc.getUser                          avgt       3   4.440 ± 1.738   ms/op
ClientGrpc.listUser                         avgt       3   5.544 ± 0.819   ms/op
ClientGrpc.createUser                     sample  225786   4.249 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.023           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.881           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.685           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.809           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  243026   3.951 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.970           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.463           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.419           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.900           ms/op
ClientGrpc.getUser                        sample  228048   4.209 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.893           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.873           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.863           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.847           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  175058   5.484 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.258           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.666           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.317           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.848           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.962           ms/op
