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
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 9.547 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.841 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.789 ±(99.9%) 1.530 ops/ms [Average]
  (min, avg, max) = (10.692, 10.789, 10.841), stdev = 0.084
  CI (99.9%): [9.259, 12.319] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.570 ops/ms
# Warmup Iteration   2: 10.995 ops/ms
# Warmup Iteration   3: 11.345 ops/ms
Iteration   1: 11.439 ops/ms
Iteration   2: 11.578 ops/ms
Iteration   3: 11.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.528 ±(99.9%) 1.412 ops/ms [Average]
  (min, avg, max) = (11.439, 11.528, 11.578), stdev = 0.077
  CI (99.9%): [10.116, 12.940] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.592 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 10.790 ops/ms
Iteration   1: 11.014 ops/ms
Iteration   2: 10.848 ops/ms
Iteration   3: 11.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.968 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (10.848, 10.968, 11.043), stdev = 0.105
  CI (99.9%): [9.051, 12.885] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.364 ops/ms
# Warmup Iteration   2: 8.205 ops/ms
# Warmup Iteration   3: 8.494 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.483 ±(99.9%) 0.807 ops/ms [Average]
  (min, avg, max) = (8.445, 8.483, 8.531), stdev = 0.044
  CI (99.9%): [7.676, 9.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.939 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.934 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.928, 2.934, 2.939), stdev = 0.006
  CI (99.9%): [2.824, 3.044] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.891 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.003 ms/op
Iteration   1: 2.863 ±(99.9%) 0.002 ms/op
Iteration   2: 2.800 ±(99.9%) 0.003 ms/op
Iteration   3: 2.745 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.803 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (2.745, 2.803, 2.863), stdev = 0.059
  CI (99.9%): [1.728, 3.878] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.928 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.902, 2.928, 2.942), stdev = 0.022
  CI (99.9%): [2.519, 3.336] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.022 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.026 ms/op
Iteration   1: 3.837 ±(99.9%) 0.018 ms/op
Iteration   2: 3.821 ±(99.9%) 0.031 ms/op
Iteration   3: 3.808 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.822 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.808, 3.822, 3.837), stdev = 0.015
  CI (99.9%): [3.553, 4.091] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.921 ms/op
                 createUser·p0.9999: 15.810 ms/op
                 createUser·p1.00:   16.630 ms/op

Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.883 ms/op
                 createUser·p0.9999: 12.763 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.923 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.762 ms/op
                 createUser·p0.9999: 21.862 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 328481
  mean =      2.923 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42686 
    [ 2.500,  5.000) = 284434 
    [ 5.000,  7.500) = 1007 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     17.274 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.006 ms/op
Iteration   1: 2.789 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.203 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.363 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 11.847 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.784 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   2.777 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.338 ms/op
                 existUser·p0.999:  5.835 ms/op
                 existUser·p0.9999: 24.725 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 2.717 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   2.781 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  9.540 ms/op
                 existUser·p0.9999: 25.500 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 347362
  mean =      2.763 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74878 
    [ 2.500,  5.000) = 271421 
    [ 5.000,  7.500) = 748 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.203 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.214 ms/op
     p(99.9900) =     25.174 ms/op
     p(99.9990) =     25.725 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.014 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 2.918 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.559 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.119 ms/op
                 getUser·p0.9999: 11.223 ms/op
                 getUser·p1.00:   11.518 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.589 ms/op
                 getUser·p0.9999: 18.419 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.281 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.935 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328549
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32249 
    [ 2.500,  5.000) = 295400 
    [ 5.000,  7.500) = 638 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.939 ms/op
     p(99.9900) =     24.925 ms/op
     p(99.9990) =     26.729 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 4.983 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
Iteration   1: 3.783 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  11.900 ms/op
                 listUser·p0.9999: 18.258 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  14.490 ms/op
                 listUser·p0.9999: 18.762 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.559 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  17.541 ms/op
                 listUser·p0.9999: 24.563 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252790
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6325 
    [ 2.500,  5.000) = 228706 
    [ 5.000,  7.500) = 16836 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.538 ms/op
     p(99.9000) =     15.280 ms/op
     p(99.9900) =     23.935 ms/op
     p(99.9990) =     24.640 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.789 ± 1.530  ops/ms
ClientGrpc.existUser                       thrpt       3  11.528 ± 1.412  ops/ms
ClientGrpc.getUser                         thrpt       3  10.968 ± 1.917  ops/ms
ClientGrpc.listUser                        thrpt       3   8.483 ± 0.807  ops/ms
ClientGrpc.createUser                       avgt       3   2.934 ± 0.110   ms/op
ClientGrpc.existUser                        avgt       3   2.803 ± 1.075   ms/op
ClientGrpc.getUser                          avgt       3   2.928 ± 0.409   ms/op
ClientGrpc.listUser                         avgt       3   3.822 ± 0.269   ms/op
ClientGrpc.createUser                     sample  328481   2.923 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.635           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.274           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  347362   2.763 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.203           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.785           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.214           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.174           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  328549   2.921 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.559           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.925           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.771           ms/op
ClientGrpc.listUser                       sample  252790   3.797 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.559           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.538           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.280           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.935           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
