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
# Warmup Iteration   1: 3.217 ops/ms
# Warmup Iteration   2: 7.559 ops/ms
# Warmup Iteration   3: 8.521 ops/ms
Iteration   1: 9.021 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.165 ±(99.9%) 3.299 ops/ms [Average]
  (min, avg, max) = (9.021, 9.165, 9.368), stdev = 0.181
  CI (99.9%): [5.866, 12.465] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ops/ms
# Warmup Iteration   2: 9.019 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.471 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.869 ±(99.9%) 9.444 ops/ms [Average]
  (min, avg, max) = (9.471, 9.869, 10.454), stdev = 0.518
  CI (99.9%): [0.426, 19.313] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ops/ms
# Warmup Iteration   2: 8.412 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 9.091 ops/ms
Iteration   2: 8.984 ops/ms
Iteration   3: 9.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.070 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (8.984, 9.070, 9.137), stdev = 0.079
  CI (99.9%): [7.635, 10.506] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 6.863 ops/ms
Iteration   1: 6.913 ops/ms
Iteration   2: 7.000 ops/ms
Iteration   3: 6.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.966 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (6.913, 6.966, 7.000), stdev = 0.046
  CI (99.9%): [6.127, 7.804] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.004 ms/op
Iteration   1: 3.548 ±(99.9%) 0.003 ms/op
Iteration   2: 3.504 ±(99.9%) 0.003 ms/op
Iteration   3: 3.505 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.519 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.504, 3.519, 3.548), stdev = 0.025
  CI (99.9%): [3.058, 3.980] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.003 ms/op
Iteration   1: 3.391 ±(99.9%) 0.003 ms/op
Iteration   2: 3.384 ±(99.9%) 0.002 ms/op
Iteration   3: 3.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.395 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (3.384, 3.395, 3.410), stdev = 0.014
  CI (99.9%): [3.144, 3.646] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.207 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.003 ms/op
Iteration   1: 3.518 ±(99.9%) 0.004 ms/op
Iteration   2: 3.565 ±(99.9%) 0.006 ms/op
Iteration   3: 3.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.551 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.518, 3.551, 3.571), stdev = 0.029
  CI (99.9%): [3.014, 4.089] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.829 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.614 ±(99.9%) 0.012 ms/op
Iteration   1: 4.494 ±(99.9%) 0.015 ms/op
Iteration   2: 4.562 ±(99.9%) 0.014 ms/op
Iteration   3: 4.452 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.503 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (4.452, 4.503, 4.562), stdev = 0.056
  CI (99.9%): [3.488, 5.517] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.908 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.008 ms/op
Iteration   1: 3.489 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  9.140 ms/op
                 createUser·p0.9999: 24.243 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.457 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.273 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  9.363 ms/op
                 createUser·p0.9999: 18.112 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 3.455 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 22.470 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 276818
  mean =      3.467 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7396 
    [ 2.500,  5.000) = 265117 
    [ 5.000,  7.500) = 3739 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.325 ms/op
     p(99.9900) =     23.308 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.939 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.006 ms/op
Iteration   1: 3.368 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  10.487 ms/op
                 existUser·p0.9999: 15.762 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   2: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  10.028 ms/op
                 existUser·p0.9999: 26.388 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.345 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 20.134 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287457
  mean =      3.337 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8935 
    [ 2.500,  5.000) = 276007 
    [ 5.000,  7.500) = 1957 
    [ 7.500, 10.000) = 299 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     25.862 ms/op
     p(99.9990) =     26.817 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.143 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.008 ms/op
Iteration   1: 3.536 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  8.215 ms/op
                 getUser·p0.9999: 15.514 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 3.532 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  11.589 ms/op
                 getUser·p0.9999: 16.939 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.544 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 271215
  mean =      3.537 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10107 
    [ 2.500,  5.000) = 256384 
    [ 5.000,  7.500) = 4279 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     19.092 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.868 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.012 ms/op
Iteration   1: 4.722 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  14.181 ms/op
                 listUser·p0.9999: 16.394 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 4.607 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  15.589 ms/op
                 listUser·p0.9999: 21.074 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.596 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  20.045 ms/op
                 listUser·p0.9999: 31.065 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206892
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 446 
    [ 2.500,  5.000) = 165774 
    [ 5.000,  7.500) = 36426 
    [ 7.500, 10.000) = 3658 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     15.650 ms/op
     p(99.9900) =     28.953 ms/op
     p(99.9990) =     31.619 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.165 ± 3.299  ops/ms
ClientGrpc.existUser                       thrpt       3   9.869 ± 9.444  ops/ms
ClientGrpc.getUser                         thrpt       3   9.070 ± 1.435  ops/ms
ClientGrpc.listUser                        thrpt       3   6.966 ± 0.838  ops/ms
ClientGrpc.createUser                       avgt       3   3.519 ± 0.461   ms/op
ClientGrpc.existUser                        avgt       3   3.395 ± 0.251   ms/op
ClientGrpc.getUser                          avgt       3   3.551 ± 0.537   ms/op
ClientGrpc.listUser                         avgt       3   4.503 ± 1.014   ms/op
ClientGrpc.createUser                     sample  276818   3.467 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.818           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.420           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.325           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  287457   3.337 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.849           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.862           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  271215   3.537 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.880           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.092           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  206892   4.641 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.650           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.654           ms/op
