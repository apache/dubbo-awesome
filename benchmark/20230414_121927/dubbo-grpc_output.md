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
# Warmup Iteration   1: 4.715 ops/ms
# Warmup Iteration   2: 9.124 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.549 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (10.441, 10.549, 10.700), stdev = 0.135
  CI (99.9%): [8.092, 13.006] (assumes normal distribution)


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
# Warmup Iteration   1: 8.201 ops/ms
# Warmup Iteration   2: 10.850 ops/ms
# Warmup Iteration   3: 11.247 ops/ms
Iteration   1: 11.082 ops/ms
Iteration   2: 11.224 ops/ms
Iteration   3: 11.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.192 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (11.082, 11.192, 11.270), stdev = 0.098
  CI (99.9%): [9.404, 12.980] (assumes normal distribution)


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
# Warmup Iteration   1: 7.411 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 10.781 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.732 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (10.640, 10.732, 10.844), stdev = 0.103
  CI (99.9%): [8.844, 12.620] (assumes normal distribution)


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
# Warmup Iteration   1: 6.680 ops/ms
# Warmup Iteration   2: 7.920 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.572 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.365 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (8.234, 8.365, 8.572), stdev = 0.181
  CI (99.9%): [5.059, 11.670] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.990 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.998 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.990, 2.998, 3.004), stdev = 0.007
  CI (99.9%): [2.874, 3.121] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.004 ms/op
Iteration   1: 2.836 ±(99.9%) 0.003 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (2.836, 2.870, 2.922), stdev = 0.046
  CI (99.9%): [2.025, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.958, 2.964, 2.975), stdev = 0.009
  CI (99.9%): [2.801, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 5.199 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.029 ms/op
Iteration   1: 3.835 ±(99.9%) 0.021 ms/op
Iteration   2: 3.875 ±(99.9%) 0.020 ms/op
Iteration   3: 3.949 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.835, 3.886, 3.949), stdev = 0.058
  CI (99.9%): [2.835, 4.938] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.907 ms/op
                 createUser·p0.9999: 16.037 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.350 ms/op
                 createUser·p0.9999: 13.322 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  10.723 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318101
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22901 
    [ 2.500,  5.000) = 293855 
    [ 5.000,  7.500) = 924 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.059 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.050 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.006 ms/op
Iteration   1: 2.879 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.355 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   11.928 ms/op

Iteration   2: 2.844 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.261 ms/op
                 existUser·p0.999:  6.018 ms/op
                 existUser·p0.9999: 14.402 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.998 ms/op
                 existUser·p0.9999: 14.665 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333080
  mean =      2.880 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2540 
    [ 1.250,  2.500) = 41448 
    [ 2.500,  3.750) = 277397 
    [ 3.750,  5.000) = 10509 
    [ 5.000,  6.250) = 799 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.684 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     14.888 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.492 ms/op
                 getUser·p0.9999: 12.427 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.785 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.984 ms/op
                 getUser·p0.9999: 15.593 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317706
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33101 
    [ 2.500,  5.000) = 283389 
    [ 5.000,  7.500) = 885 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.382 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     21.544 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.780 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  16.334 ms/op
                 listUser·p0.9999: 26.471 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.583 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.907 ms/op
                 listUser·p0.9999: 19.852 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245500
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5214 
    [ 2.500,  5.000) = 218399 
    [ 5.000,  7.500) = 20740 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.574 ms/op
     p(99.9900) =     22.330 ms/op
     p(99.9990) =     26.923 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.549 ± 2.457  ops/ms
ClientGrpc.existUser                       thrpt       3  11.192 ± 1.788  ops/ms
ClientGrpc.getUser                         thrpt       3  10.732 ± 1.888  ops/ms
ClientGrpc.listUser                        thrpt       3   8.365 ± 3.306  ops/ms
ClientGrpc.createUser                       avgt       3   2.998 ± 0.124   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 0.845   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.163   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 1.051   ms/op
ClientGrpc.createUser                     sample  318101   3.022 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.383           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  333080   2.880 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.609           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.434           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.105           ms/op
ClientGrpc.getUser                        sample  317706   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.537           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.382           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.544           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.412           ms/op
ClientGrpc.listUser                       sample  245500   3.909 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.583           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.574           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.330           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
