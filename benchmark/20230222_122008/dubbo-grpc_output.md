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
# Warmup Iteration   1: 2.417 ops/ms
# Warmup Iteration   2: 5.738 ops/ms
# Warmup Iteration   3: 6.951 ops/ms
Iteration   1: 7.191 ops/ms
Iteration   2: 7.164 ops/ms
Iteration   3: 7.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.165 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (7.140, 7.165, 7.191), stdev = 0.025
  CI (99.9%): [6.704, 7.626] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.200 ops/ms
# Warmup Iteration   2: 7.096 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.294 ops/ms
Iteration   2: 7.607 ops/ms
Iteration   3: 7.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.485 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (7.294, 7.485, 7.607), stdev = 0.167
  CI (99.9%): [4.430, 10.539] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 6.849 ops/ms
Iteration   1: 6.647 ops/ms
Iteration   2: 6.762 ops/ms
Iteration   3: 6.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.759 ±(99.9%) 2.003 ops/ms [Average]
  (min, avg, max) = (6.647, 6.759, 6.867), stdev = 0.110
  CI (99.9%): [4.756, 8.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ops/ms
# Warmup Iteration   2: 4.935 ops/ms
# Warmup Iteration   3: 5.387 ops/ms
Iteration   1: 5.389 ops/ms
Iteration   2: 5.506 ops/ms
Iteration   3: 5.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.471 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (5.389, 5.471, 5.519), stdev = 0.072
  CI (99.9%): [4.161, 6.781] (assumes normal distribution)


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
# Warmup Iteration   1: 6.283 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.003 ms/op
Iteration   1: 4.720 ±(99.9%) 0.004 ms/op
Iteration   2: 4.877 ±(99.9%) 0.003 ms/op
Iteration   3: 4.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.795 ±(99.9%) 1.433 ms/op [Average]
  (min, avg, max) = (4.720, 4.795, 4.877), stdev = 0.079
  CI (99.9%): [3.362, 6.228] (assumes normal distribution)


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
# Warmup Iteration   1: 6.289 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.003 ms/op
Iteration   1: 4.481 ±(99.9%) 0.003 ms/op
Iteration   2: 4.485 ±(99.9%) 0.003 ms/op
Iteration   3: 4.444 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.470 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (4.444, 4.470, 4.485), stdev = 0.023
  CI (99.9%): [4.054, 4.885] (assumes normal distribution)


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
# Warmup Iteration   1: 6.553 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.003 ms/op
Iteration   1: 4.663 ±(99.9%) 0.004 ms/op
Iteration   2: 4.639 ±(99.9%) 0.003 ms/op
Iteration   3: 4.722 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.675 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (4.639, 4.675, 4.722), stdev = 0.043
  CI (99.9%): [3.891, 5.458] (assumes normal distribution)


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.829 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.015 ms/op
Iteration   1: 5.655 ±(99.9%) 0.025 ms/op
Iteration   2: 5.510 ±(99.9%) 0.022 ms/op
Iteration   3: 5.377 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.514 ±(99.9%) 2.537 ms/op [Average]
  (min, avg, max) = (5.377, 5.514, 5.655), stdev = 0.139
  CI (99.9%): [2.977, 8.051] (assumes normal distribution)


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
# Warmup Iteration   1: 6.265 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.013 ms/op
Iteration   1: 4.697 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.021 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  10.776 ms/op
                 createUser·p0.9999: 16.605 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 4.685 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.398 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  11.661 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   3: 4.521 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  19.083 ms/op
                 createUser·p0.9999: 23.063 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207224
  mean =      4.633 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3245 
    [ 2.500,  5.000) = 137823 
    [ 5.000,  7.500) = 64160 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     13.366 ms/op
     p(99.9900) =     21.013 ms/op
     p(99.9990) =     24.671 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.916 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.012 ms/op
Iteration   1: 4.440 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  11.202 ms/op
                 existUser·p0.9999: 22.273 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 4.480 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  12.292 ms/op
                 existUser·p0.9999: 15.626 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   3: 4.416 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  9.768 ms/op
                 existUser·p0.9999: 17.409 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 215942
  mean =      4.445 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3545 
    [ 2.500,  5.000) = 157911 
    [ 5.000,  7.500) = 52891 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     10.962 ms/op
     p(99.9900) =     17.669 ms/op
     p(99.9990) =     22.792 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 6.545 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.013 ms/op
Iteration   1: 4.578 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  14.345 ms/op
                 getUser·p0.9999: 18.875 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 4.590 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  11.646 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 4.467 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.411 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.119 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  11.467 ms/op
                 getUser·p0.9999: 21.223 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211277
  mean =      4.544 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4297 
    [ 2.500,  5.000) = 146201 
    [ 5.000,  7.500) = 58625 
    [ 7.500, 10.000) = 1738 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     12.422 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     21.579 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 8.244 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.079 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.878 ±(99.9%) 0.020 ms/op
Iteration   1: 5.775 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  16.977 ms/op
                 listUser·p0.9999: 22.494 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 5.812 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  15.478 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 5.749 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 25.571 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166119
  mean =      5.778 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 126 
    [ 2.500,  5.000) = 44224 
    [ 5.000,  7.500) = 105423 
    [ 7.500, 10.000) = 13936 
    [10.000, 12.500) = 1817 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.471 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     17.363 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     26.368 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.165 ± 0.461  ops/ms
ClientGrpc.existUser                       thrpt       3   7.485 ± 3.054  ops/ms
ClientGrpc.getUser                         thrpt       3   6.759 ± 2.003  ops/ms
ClientGrpc.listUser                        thrpt       3   5.471 ± 1.310  ops/ms
ClientGrpc.createUser                       avgt       3   4.795 ± 1.433   ms/op
ClientGrpc.existUser                        avgt       3   4.470 ± 0.416   ms/op
ClientGrpc.getUser                          avgt       3   4.675 ± 0.783   ms/op
ClientGrpc.listUser                         avgt       3   5.514 ± 2.537   ms/op
ClientGrpc.createUser                     sample  207224   4.633 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.887           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.890           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.291           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.455           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.366           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.013           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.936           ms/op
ClientGrpc.existUser                      sample  215942   4.445 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.463           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.962           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.669           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.938           ms/op
ClientGrpc.getUser                        sample  211277   4.544 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.411           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.767           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.422           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.694           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.725           ms/op
ClientGrpc.listUser                       sample  166119   5.778 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.440           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.471           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.363           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
