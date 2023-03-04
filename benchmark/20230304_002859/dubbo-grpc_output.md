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
# Warmup Iteration   1: 2.380 ops/ms
# Warmup Iteration   2: 5.516 ops/ms
# Warmup Iteration   3: 7.049 ops/ms
Iteration   1: 7.325 ops/ms
Iteration   2: 7.362 ops/ms
Iteration   3: 7.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.293 ±(99.9%) 1.637 ops/ms [Average]
  (min, avg, max) = (7.192, 7.293, 7.362), stdev = 0.090
  CI (99.9%): [5.656, 8.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ops/ms
# Warmup Iteration   2: 7.189 ops/ms
# Warmup Iteration   3: 7.447 ops/ms
Iteration   1: 7.599 ops/ms
Iteration   2: 7.387 ops/ms
Iteration   3: 7.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.436 ±(99.9%) 2.644 ops/ms [Average]
  (min, avg, max) = (7.322, 7.436, 7.599), stdev = 0.145
  CI (99.9%): [4.792, 10.080] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 6.498 ops/ms
# Warmup Iteration   3: 6.938 ops/ms
Iteration   1: 6.964 ops/ms
Iteration   2: 6.883 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.884 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (6.803, 6.884, 6.964), stdev = 0.080
  CI (99.9%): [5.422, 8.345] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 5.362 ops/ms
# Warmup Iteration   3: 5.634 ops/ms
Iteration   1: 5.778 ops/ms
Iteration   2: 5.612 ops/ms
Iteration   3: 5.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.634 ±(99.9%) 2.458 ops/ms [Average]
  (min, avg, max) = (5.511, 5.634, 5.778), stdev = 0.135
  CI (99.9%): [3.176, 8.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.517 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.769 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.004 ms/op
Iteration   1: 4.474 ±(99.9%) 0.003 ms/op
Iteration   2: 4.470 ±(99.9%) 0.002 ms/op
Iteration   3: 4.409 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.451 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (4.409, 4.451, 4.474), stdev = 0.036
  CI (99.9%): [3.788, 5.114] (assumes normal distribution)


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
# Warmup Iteration   1: 6.588 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.012 ms/op
Iteration   1: 4.413 ±(99.9%) 0.006 ms/op
Iteration   2: 4.384 ±(99.9%) 0.003 ms/op
Iteration   3: 4.274 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.357 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (4.274, 4.357, 4.413), stdev = 0.074
  CI (99.9%): [3.014, 5.700] (assumes normal distribution)


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
# Warmup Iteration   1: 7.175 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.008 ms/op
Iteration   1: 4.598 ±(99.9%) 0.002 ms/op
Iteration   2: 4.826 ±(99.9%) 0.002 ms/op
Iteration   3: 4.652 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.692 ±(99.9%) 2.170 ms/op [Average]
  (min, avg, max) = (4.598, 4.692, 4.826), stdev = 0.119
  CI (99.9%): [2.522, 6.862] (assumes normal distribution)


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
# Warmup Iteration   1: 8.046 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 6.173 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.741 ±(99.9%) 0.018 ms/op
Iteration   1: 5.586 ±(99.9%) 0.009 ms/op
Iteration   2: 5.516 ±(99.9%) 0.006 ms/op
Iteration   3: 5.522 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.541 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (5.516, 5.541, 5.586), stdev = 0.039
  CI (99.9%): [4.828, 6.255] (assumes normal distribution)


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
# Warmup Iteration   1: 6.814 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.014 ms/op
Iteration   1: 4.437 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.514 ms/op
                 createUser·p0.999:  12.938 ms/op
                 createUser·p0.9999: 20.319 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 4.473 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  12.121 ms/op
                 createUser·p0.9999: 24.517 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 4.330 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   6.936 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 26.234 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217610
  mean =      4.413 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3936 
    [ 2.500,  5.000) = 165407 
    [ 5.000,  7.500) = 46562 
    [ 7.500, 10.000) = 1253 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.216 ms/op
     p(99.9000) =     12.481 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 6.377 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.358 ±(99.9%) 0.012 ms/op
Iteration   1: 4.493 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.603 ms/op
                 existUser·p0.95:   5.972 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  13.743 ms/op
                 existUser·p0.9999: 19.915 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 4.325 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   4.243 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  12.619 ms/op
                 existUser·p0.9999: 18.279 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 4.138 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  16.236 ms/op
                 existUser·p0.9999: 19.670 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222413
  mean =      4.314 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6694 
    [ 2.500,  5.000) = 169301 
    [ 5.000,  7.500) = 44701 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     13.657 ms/op
     p(99.9900) =     19.448 ms/op
     p(99.9990) =     20.320 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 6.831 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.718 ±(99.9%) 0.013 ms/op
Iteration   1: 4.697 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  13.891 ms/op
                 getUser·p0.9999: 20.185 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 4.553 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  14.553 ms/op
                 getUser·p0.9999: 18.218 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   3: 4.677 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  10.878 ms/op
                 getUser·p0.9999: 21.905 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206689
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2403 
    [ 2.500,  5.000) = 137735 
    [ 5.000,  7.500) = 64823 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     19.945 ms/op
     p(99.9990) =     22.684 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 8.597 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.009 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.549 ±(99.9%) 0.018 ms/op
Iteration   1: 5.393 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 21.760 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 5.603 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   10.033 ms/op
                 listUser·p0.999:  16.711 ms/op
                 listUser·p0.9999: 24.794 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 5.804 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  19.493 ms/op
                 listUser·p0.9999: 25.243 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171607
  mean =      5.595 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 58073 
    [ 5.000,  7.500) = 99461 
    [ 7.500, 10.000) = 12185 
    [10.000, 12.500) = 1242 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     24.402 ms/op
     p(99.9990) =     26.045 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.293 ± 1.637  ops/ms
ClientGrpc.existUser                       thrpt       3   7.436 ± 2.644  ops/ms
ClientGrpc.getUser                         thrpt       3   6.884 ± 1.461  ops/ms
ClientGrpc.listUser                        thrpt       3   5.634 ± 2.458  ops/ms
ClientGrpc.createUser                       avgt       3   4.451 ± 0.663   ms/op
ClientGrpc.existUser                        avgt       3   4.357 ± 1.343   ms/op
ClientGrpc.getUser                          avgt       3   4.692 ± 2.170   ms/op
ClientGrpc.listUser                         avgt       3   5.541 ± 0.714   ms/op
ClientGrpc.createUser                     sample  217610   4.413 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.853           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.216           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.481           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.985           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  222413   4.314 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.833           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.119           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.657           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.448           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.480           ms/op
ClientGrpc.getUser                        sample  206689   4.641 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.163           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.201           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.042           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.945           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  171607   5.595 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.579           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.402           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
