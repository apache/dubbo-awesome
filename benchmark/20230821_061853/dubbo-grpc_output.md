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
# Warmup Iteration   1: 2.282 ops/ms
# Warmup Iteration   2: 5.214 ops/ms
# Warmup Iteration   3: 6.603 ops/ms
Iteration   1: 6.899 ops/ms
Iteration   2: 7.007 ops/ms
Iteration   3: 7.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.086 ±(99.9%) 4.302 ops/ms [Average]
  (min, avg, max) = (6.899, 7.086, 7.351), stdev = 0.236
  CI (99.9%): [2.784, 11.387] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ops/ms
# Warmup Iteration   2: 6.940 ops/ms
# Warmup Iteration   3: 7.353 ops/ms
Iteration   1: 7.410 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 7.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.724 ±(99.9%) 6.328 ops/ms [Average]
  (min, avg, max) = (7.410, 7.724, 8.096), stdev = 0.347
  CI (99.9%): [1.396, 14.052] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.795 ops/ms
# Warmup Iteration   2: 7.158 ops/ms
# Warmup Iteration   3: 7.308 ops/ms
Iteration   1: 7.414 ops/ms
Iteration   2: 6.947 ops/ms
Iteration   3: 7.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.301 ±(99.9%) 5.724 ops/ms [Average]
  (min, avg, max) = (6.947, 7.301, 7.543), stdev = 0.314
  CI (99.9%): [1.577, 13.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.504 ops/ms
# Warmup Iteration   2: 5.236 ops/ms
# Warmup Iteration   3: 5.787 ops/ms
Iteration   1: 5.741 ops/ms
Iteration   2: 5.412 ops/ms
Iteration   3: 5.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.529 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (5.412, 5.529, 5.741), stdev = 0.184
  CI (99.9%): [2.176, 8.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.012 ms/op
Iteration   1: 4.414 ±(99.9%) 0.002 ms/op
Iteration   2: 4.364 ±(99.9%) 0.003 ms/op
Iteration   3: 4.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.392 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (4.364, 4.392, 4.414), stdev = 0.026
  CI (99.9%): [3.924, 4.861] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.196 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.006 ms/op
Iteration   1: 4.194 ±(99.9%) 0.005 ms/op
Iteration   2: 4.044 ±(99.9%) 0.002 ms/op
Iteration   3: 4.217 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.151 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (4.044, 4.151, 4.217), stdev = 0.094
  CI (99.9%): [2.438, 5.865] (assumes normal distribution)


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
# Warmup Iteration   1: 6.889 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.061 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.689 ±(99.9%) 0.007 ms/op
Iteration   1: 4.614 ±(99.9%) 0.004 ms/op
Iteration   2: 4.466 ±(99.9%) 0.003 ms/op
Iteration   3: 4.362 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.481 ±(99.9%) 2.311 ms/op [Average]
  (min, avg, max) = (4.362, 4.481, 4.614), stdev = 0.127
  CI (99.9%): [2.169, 6.792] (assumes normal distribution)


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
# Warmup Iteration   1: 7.552 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 6.018 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.021 ms/op
Iteration   1: 5.439 ±(99.9%) 0.010 ms/op
Iteration   2: 5.549 ±(99.9%) 0.017 ms/op
Iteration   3: 5.534 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.508 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (5.439, 5.508, 5.549), stdev = 0.060
  CI (99.9%): [4.422, 6.594] (assumes normal distribution)


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
# Warmup Iteration   1: 6.730 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.969 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.016 ms/op
Iteration   1: 4.445 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  13.133 ms/op
                 createUser·p0.9999: 25.290 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 4.662 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  15.541 ms/op
                 createUser·p0.9999: 31.724 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 4.626 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   8.196 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 30.289 ms/op
                 createUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209793
  mean =      4.575 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3286 
    [ 2.500,  5.000) = 150653 
    [ 5.000,  7.500) = 52527 
    [ 7.500, 10.000) = 2420 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.341 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     16.388 ms/op
     p(99.9900) =     31.065 ms/op
     p(99.9990) =     31.811 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 6.122 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.340 ±(99.9%) 0.013 ms/op
Iteration   1: 4.336 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  11.717 ms/op
                 existUser·p0.9999: 18.005 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   2: 4.219 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  12.599 ms/op
                 existUser·p0.9999: 17.685 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  18.285 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226665
  mean =      4.234 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3930 
    [ 2.500,  5.000) = 188824 
    [ 5.000,  7.500) = 31464 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     12.523 ms/op
     p(99.9900) =     22.097 ms/op
     p(99.9990) =     23.669 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.989 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.016 ms/op
Iteration   1: 4.528 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  11.818 ms/op
                 getUser·p0.9999: 26.755 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 4.444 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 23.436 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 4.652 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  13.357 ms/op
                 getUser·p0.9999: 28.942 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211432
  mean =      4.540 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3783 
    [ 2.500,  5.000) = 152057 
    [ 5.000,  7.500) = 53166 
    [ 7.500, 10.000) = 1723 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     12.674 ms/op
     p(99.9900) =     27.319 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.349 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.805 ±(99.9%) 0.021 ms/op
Iteration   1: 5.774 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  18.272 ms/op
                 listUser·p0.9999: 21.408 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 5.703 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.324 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.556 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 19.395 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 5.868 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  22.723 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166112
  mean =      5.781 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 45980 
    [ 5.000,  7.500) = 104398 
    [ 7.500, 10.000) = 12724 
    [10.000, 12.500) = 2269 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     18.051 ms/op
     p(99.9900) =     25.353 ms/op
     p(99.9990) =     26.284 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.086 ± 4.302  ops/ms
ClientGrpc.existUser                       thrpt       3   7.724 ± 6.328  ops/ms
ClientGrpc.getUser                         thrpt       3   7.301 ± 5.724  ops/ms
ClientGrpc.listUser                        thrpt       3   5.529 ± 3.353  ops/ms
ClientGrpc.createUser                       avgt       3   4.392 ± 0.469   ms/op
ClientGrpc.existUser                        avgt       3   4.151 ± 1.713   ms/op
ClientGrpc.getUser                          avgt       3   4.481 ± 2.311   ms/op
ClientGrpc.listUser                         avgt       3   5.508 ± 1.086   ms/op
ClientGrpc.createUser                     sample  209793   4.575 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.036           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.341           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.274           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.388           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.065           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.014           ms/op
ClientGrpc.existUser                      sample  226665   4.234 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.698           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.668           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.523           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.097           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.953           ms/op
ClientGrpc.getUser                        sample  211432   4.540 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.865           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.725           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.674           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.319           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.245           ms/op
ClientGrpc.listUser                       sample  166112   5.781 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.782           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.051           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.353           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
