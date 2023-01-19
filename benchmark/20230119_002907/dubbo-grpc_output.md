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
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 5.445 ops/ms
# Warmup Iteration   3: 6.562 ops/ms
Iteration   1: 6.689 ops/ms
Iteration   2: 6.800 ops/ms
Iteration   3: 6.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.692 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (6.587, 6.692, 6.800), stdev = 0.106
  CI (99.9%): [4.753, 8.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ops/ms
# Warmup Iteration   2: 6.688 ops/ms
# Warmup Iteration   3: 7.170 ops/ms
Iteration   1: 7.133 ops/ms
Iteration   2: 7.261 ops/ms
Iteration   3: 7.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.219 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (7.133, 7.219, 7.264), stdev = 0.075
  CI (99.9%): [5.857, 8.582] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ops/ms
# Warmup Iteration   2: 6.337 ops/ms
# Warmup Iteration   3: 6.792 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 6.918 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.081 ±(99.9%) 6.513 ops/ms [Average]
  (min, avg, max) = (6.834, 7.081, 7.490), stdev = 0.357
  CI (99.9%): [0.568, 13.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ops/ms
# Warmup Iteration   2: 5.079 ops/ms
# Warmup Iteration   3: 5.228 ops/ms
Iteration   1: 5.299 ops/ms
Iteration   2: 5.359 ops/ms
Iteration   3: 5.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.368 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (5.299, 5.368, 5.444), stdev = 0.072
  CI (99.9%): [4.045, 6.690] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.973 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.008 ms/op
Iteration   1: 4.415 ±(99.9%) 0.003 ms/op
Iteration   2: 4.598 ±(99.9%) 0.002 ms/op
Iteration   3: 4.709 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.574 ±(99.9%) 2.710 ms/op [Average]
  (min, avg, max) = (4.415, 4.574, 4.709), stdev = 0.149
  CI (99.9%): [1.864, 7.284] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.002 ms/op
Iteration   1: 4.296 ±(99.9%) 0.004 ms/op
Iteration   2: 4.251 ±(99.9%) 0.004 ms/op
Iteration   3: 4.305 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.284 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (4.251, 4.284, 4.305), stdev = 0.029
  CI (99.9%): [3.760, 4.808] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.258 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.930 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.003 ms/op
Iteration   1: 4.783 ±(99.9%) 0.004 ms/op
Iteration   2: 4.598 ±(99.9%) 0.005 ms/op
Iteration   3: 4.549 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.644 ±(99.9%) 2.247 ms/op [Average]
  (min, avg, max) = (4.549, 4.644, 4.783), stdev = 0.123
  CI (99.9%): [2.397, 6.890] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.123 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.729 ±(99.9%) 0.020 ms/op
Iteration   1: 5.592 ±(99.9%) 0.013 ms/op
Iteration   2: 5.772 ±(99.9%) 0.019 ms/op
Iteration   3: 5.485 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.616 ±(99.9%) 2.646 ms/op [Average]
  (min, avg, max) = (5.485, 5.616, 5.772), stdev = 0.145
  CI (99.9%): [2.970, 8.262] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.531 ±(99.9%) 0.013 ms/op
Iteration   1: 4.524 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  13.468 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 4.474 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   7.503 ms/op
                 createUser·p0.999:  17.268 ms/op
                 createUser·p0.9999: 22.638 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 4.525 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 33.348 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212915
  mean =      4.508 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3715 
    [ 2.500,  5.000) = 148764 
    [ 5.000,  7.500) = 58454 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     32.599 ms/op
     p(99.9990) =     33.743 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.264 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.012 ms/op
Iteration   1: 4.165 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  11.485 ms/op
                 existUser·p0.9999: 15.378 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 4.165 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  9.128 ms/op
                 existUser·p0.9999: 19.583 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 4.282 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  13.633 ms/op
                 existUser·p0.9999: 20.286 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228444
  mean =      4.203 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10135 
    [ 2.500,  5.000) = 174166 
    [ 5.000,  7.500) = 43261 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.527 ms/op
     p(99.9900) =     19.769 ms/op
     p(99.9990) =     20.691 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.811 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.012 ms/op
Iteration   1: 4.479 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.075 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 14.802 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 4.370 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 17.313 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 4.359 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  10.594 ms/op
                 getUser·p0.9999: 21.484 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218035
  mean =      4.402 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5448 
    [ 2.500,  5.000) = 158936 
    [ 5.000,  7.500) = 52301 
    [ 7.500, 10.000) = 940 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     11.730 ms/op
     p(99.9900) =     17.839 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.095 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.695 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.017 ms/op
Iteration   1: 5.565 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  16.614 ms/op
                 listUser·p0.9999: 24.027 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 5.505 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  19.719 ms/op
                 listUser·p0.9999: 27.433 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 5.378 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   9.981 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 23.203 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175083
  mean =      5.482 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 64783 
    [ 5.000,  7.500) = 98924 
    [ 7.500, 10.000) = 9628 
    [10.000, 12.500) = 1029 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     25.739 ms/op
     p(99.9990) =     27.763 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.692 ± 1.939  ops/ms
ClientGrpc.existUser                       thrpt       3   7.219 ± 1.362  ops/ms
ClientGrpc.getUser                         thrpt       3   7.081 ± 6.513  ops/ms
ClientGrpc.listUser                        thrpt       3   5.368 ± 1.322  ops/ms
ClientGrpc.createUser                       avgt       3   4.574 ± 2.710   ms/op
ClientGrpc.existUser                        avgt       3   4.284 ± 0.524   ms/op
ClientGrpc.getUser                          avgt       3   4.644 ± 2.247   ms/op
ClientGrpc.listUser                         avgt       3   5.616 ± 2.646   ms/op
ClientGrpc.createUser                     sample  212915   4.508 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.886           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.499           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.599           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.882           ms/op
ClientGrpc.existUser                      sample  228444   4.203 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.969           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.718           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.527           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.769           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  218035   4.402 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.597           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.562           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.889           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.839           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.922           ms/op
ClientGrpc.listUser                       sample  175083   5.482 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.184           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.514           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
