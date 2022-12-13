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
# Warmup Iteration   1: 2.390 ops/ms
# Warmup Iteration   2: 5.675 ops/ms
# Warmup Iteration   3: 6.958 ops/ms
Iteration   1: 7.069 ops/ms
Iteration   2: 7.191 ops/ms
Iteration   3: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.020 ±(99.9%) 3.657 ops/ms [Average]
  (min, avg, max) = (6.799, 7.020, 7.191), stdev = 0.200
  CI (99.9%): [3.363, 10.676] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
# Warmup Iteration   2: 7.269 ops/ms
# Warmup Iteration   3: 7.580 ops/ms
Iteration   1: 7.447 ops/ms
Iteration   2: 7.457 ops/ms
Iteration   3: 7.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.463 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (7.447, 7.463, 7.483), stdev = 0.019
  CI (99.9%): [7.123, 7.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ops/ms
# Warmup Iteration   2: 6.846 ops/ms
# Warmup Iteration   3: 6.757 ops/ms
Iteration   1: 7.200 ops/ms
Iteration   2: 6.857 ops/ms
Iteration   3: 7.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.028 ±(99.9%) 3.132 ops/ms [Average]
  (min, avg, max) = (6.857, 7.028, 7.200), stdev = 0.172
  CI (99.9%): [3.896, 10.159] (assumes normal distribution)


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
# Warmup Iteration   1: 3.705 ops/ms
# Warmup Iteration   2: 5.325 ops/ms
# Warmup Iteration   3: 5.695 ops/ms
Iteration   1: 5.463 ops/ms
Iteration   2: 5.864 ops/ms
Iteration   3: 5.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.689 ±(99.9%) 3.743 ops/ms [Average]
  (min, avg, max) = (5.463, 5.689, 5.864), stdev = 0.205
  CI (99.9%): [1.945, 9.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.314 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.757 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.012 ms/op
Iteration   1: 4.457 ±(99.9%) 0.004 ms/op
Iteration   2: 4.546 ±(99.9%) 0.002 ms/op
Iteration   3: 4.525 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.509 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (4.457, 4.509, 4.546), stdev = 0.047
  CI (99.9%): [3.658, 5.361] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.083 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.004 ms/op
Iteration   1: 4.217 ±(99.9%) 0.002 ms/op
Iteration   2: 4.214 ±(99.9%) 0.004 ms/op
Iteration   3: 4.160 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.197 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (4.160, 4.197, 4.217), stdev = 0.032
  CI (99.9%): [3.612, 4.782] (assumes normal distribution)


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
# Warmup Iteration   1: 6.979 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.004 ms/op
Iteration   1: 4.489 ±(99.9%) 0.003 ms/op
Iteration   2: 4.730 ±(99.9%) 0.004 ms/op
Iteration   3: 4.561 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.593 ±(99.9%) 2.261 ms/op [Average]
  (min, avg, max) = (4.489, 4.593, 4.730), stdev = 0.124
  CI (99.9%): [2.332, 6.855] (assumes normal distribution)


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
# Warmup Iteration   1: 8.354 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 6.330 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.612 ±(99.9%) 0.017 ms/op
Iteration   1: 5.662 ±(99.9%) 0.008 ms/op
Iteration   2: 5.674 ±(99.9%) 0.016 ms/op
Iteration   3: 5.828 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.721 ±(99.9%) 1.688 ms/op [Average]
  (min, avg, max) = (5.662, 5.721, 5.828), stdev = 0.092
  CI (99.9%): [4.034, 7.409] (assumes normal distribution)


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
# Warmup Iteration   1: 6.984 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.645 ±(99.9%) 0.015 ms/op
Iteration   1: 4.454 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 4.585 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.009 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 4.579 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.492 ms/op
                 createUser·p0.999:  12.479 ms/op
                 createUser·p0.9999: 25.102 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211498
  mean =      4.539 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2966 
    [ 2.500,  5.000) = 149137 
    [ 5.000,  7.500) = 56125 
    [ 7.500, 10.000) = 2714 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     25.388 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 6.411 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.572 ±(99.9%) 0.014 ms/op
Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  11.506 ms/op
                 existUser·p0.9999: 31.478 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   2: 4.308 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  11.721 ms/op
                 existUser·p0.9999: 16.046 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   4.059 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  12.816 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224532
  mean =      4.272 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4453 
    [ 2.500,  5.000) = 178635 
    [ 5.000,  7.500) = 39300 
    [ 7.500, 10.000) = 1667 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     12.165 ms/op
     p(99.9900) =     30.739 ms/op
     p(99.9990) =     31.826 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 6.230 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.502 ±(99.9%) 0.015 ms/op
Iteration   1: 4.426 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.119 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  14.782 ms/op
                 getUser·p0.9999: 23.381 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 4.480 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.832 ms/op
                 getUser·p0.999:  13.957 ms/op
                 getUser·p0.9999: 30.718 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   3: 4.506 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.249 ms/op
                 getUser·p0.999:  12.580 ms/op
                 getUser·p0.9999: 21.132 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214811
  mean =      4.470 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3727 
    [ 2.500,  5.000) = 160696 
    [ 5.000,  7.500) = 47322 
    [ 7.500, 10.000) = 2322 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     30.049 ms/op
     p(99.9990) =     31.054 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 8.164 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.024 ms/op
Iteration   1: 5.560 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  23.281 ms/op
                 listUser·p0.9999: 27.992 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 5.874 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  26.134 ms/op
                 listUser·p0.9999: 33.737 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 5.663 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.493 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.131 ms/op
                 listUser·p0.999:  27.310 ms/op
                 listUser·p0.9999: 37.313 ms/op
                 listUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168515
  mean =      5.696 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 171 
    [ 2.500,  5.000) = 58984 
    [ 5.000,  7.500) = 91340 
    [ 7.500, 10.000) = 14692 
    [10.000, 12.500) = 2403 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     24.559 ms/op
     p(99.9900) =     34.691 ms/op
     p(99.9990) =     38.089 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.020 ± 3.657  ops/ms
ClientGrpc.existUser                       thrpt       3   7.463 ± 0.340  ops/ms
ClientGrpc.getUser                         thrpt       3   7.028 ± 3.132  ops/ms
ClientGrpc.listUser                        thrpt       3   5.689 ± 3.743  ops/ms
ClientGrpc.createUser                       avgt       3   4.509 ± 0.851   ms/op
ClientGrpc.existUser                        avgt       3   4.197 ± 0.585   ms/op
ClientGrpc.getUser                          avgt       3   4.593 ± 2.261   ms/op
ClientGrpc.listUser                         avgt       3   5.721 ± 1.688   ms/op
ClientGrpc.createUser                     sample  211498   4.539 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.882           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.316           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.314           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.428           ms/op
ClientGrpc.existUser                      sample  224532   4.272 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.854           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.438           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.165           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.949           ms/op
ClientGrpc.getUser                        sample  214811   4.470 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.167           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.090           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.049           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.768           ms/op
ClientGrpc.listUser                       sample  168515   5.696 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.493           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.559           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.256           ms/op
