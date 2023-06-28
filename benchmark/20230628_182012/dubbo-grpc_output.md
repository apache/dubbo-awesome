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
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 5.025 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.339 ops/ms
Iteration   3: 7.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.538 ±(99.9%) 3.341 ops/ms [Average]
  (min, avg, max) = (7.339, 7.538, 7.700), stdev = 0.183
  CI (99.9%): [4.197, 10.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 8.067 ops/ms
Iteration   1: 7.842 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.837 ±(99.9%) 1.098 ops/ms [Average]
  (min, avg, max) = (7.774, 7.837, 7.894), stdev = 0.060
  CI (99.9%): [6.738, 8.935] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 6.905 ops/ms
Iteration   1: 7.166 ops/ms
Iteration   2: 7.336 ops/ms
Iteration   3: 7.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.227 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (7.166, 7.227, 7.336), stdev = 0.094
  CI (99.9%): [5.510, 8.944] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
# Warmup Iteration   2: 4.890 ops/ms
# Warmup Iteration   3: 5.600 ops/ms
Iteration   1: 5.868 ops/ms
Iteration   2: 5.844 ops/ms
Iteration   3: 5.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.861 ±(99.9%) 0.273 ops/ms [Average]
  (min, avg, max) = (5.844, 5.861, 5.871), stdev = 0.015
  CI (99.9%): [5.588, 6.134] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.604 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.467 ±(99.9%) 0.027 ms/op
Iteration   1: 4.262 ±(99.9%) 0.002 ms/op
Iteration   2: 4.248 ±(99.9%) 0.004 ms/op
Iteration   3: 4.199 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.237 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (4.199, 4.237, 4.262), stdev = 0.033
  CI (99.9%): [3.635, 4.838] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.372 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.003 ms/op
Iteration   1: 3.918 ±(99.9%) 0.003 ms/op
Iteration   2: 3.921 ±(99.9%) 0.003 ms/op
Iteration   3: 3.876 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.905 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.876, 3.905, 3.921), stdev = 0.025
  CI (99.9%): [3.449, 4.361] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.672 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.007 ms/op
Iteration   1: 4.283 ±(99.9%) 0.003 ms/op
Iteration   2: 4.046 ±(99.9%) 0.003 ms/op
Iteration   3: 4.086 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.138 ±(99.9%) 2.316 ms/op [Average]
  (min, avg, max) = (4.046, 4.138, 4.283), stdev = 0.127
  CI (99.9%): [1.822, 6.454] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.975 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.550 ±(99.9%) 0.013 ms/op
Iteration   1: 5.719 ±(99.9%) 0.021 ms/op
Iteration   2: 5.638 ±(99.9%) 0.021 ms/op
Iteration   3: 5.707 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.688 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (5.638, 5.688, 5.719), stdev = 0.044
  CI (99.9%): [4.882, 6.495] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.014 ms/op
Iteration   1: 4.446 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.988 ms/op
                 createUser·p0.99:   7.686 ms/op
                 createUser·p0.999:  13.386 ms/op
                 createUser·p0.9999: 23.324 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 4.510 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  13.946 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 4.417 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.087 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  12.943 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215356
  mean =      4.458 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5354 
    [ 2.500,  5.000) = 160123 
    [ 5.000,  7.500) = 47103 
    [ 7.500, 10.000) = 1903 
    [10.000, 12.500) = 547 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     28.695 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.326 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.012 ms/op
Iteration   1: 4.330 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   7.653 ms/op
                 existUser·p0.999:  13.013 ms/op
                 existUser·p0.9999: 18.180 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 33.454 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  12.950 ms/op
                 existUser·p0.9999: 21.733 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233329
  mean =      4.115 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6456 
    [ 2.500,  5.000) = 198117 
    [ 5.000,  7.500) = 26793 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     12.365 ms/op
     p(99.9900) =     32.418 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.965 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.012 ms/op
Iteration   1: 4.307 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  10.498 ms/op
                 getUser·p0.9999: 30.367 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   2: 4.362 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  12.758 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 4.242 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   7.431 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223009
  mean =      4.303 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4947 
    [ 2.500,  5.000) = 177408 
    [ 5.000,  7.500) = 38859 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     29.298 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.507 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.095 ±(99.9%) 0.028 ms/op
Iteration   1: 5.989 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  21.186 ms/op
                 listUser·p0.9999: 29.458 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 5.623 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  17.274 ms/op
                 listUser·p0.9999: 20.556 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 5.740 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 32.305 ms/op
                 listUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165994
  mean =      5.780 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 57560 
    [ 5.000,  7.500) = 87564 
    [ 7.500, 10.000) = 17121 
    [10.000, 12.500) = 2669 
    [12.500, 15.000) = 502 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.832 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     30.874 ms/op
     p(99.9990) =     32.649 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.538 ± 3.341  ops/ms
ClientGrpc.existUser                       thrpt       3   7.837 ± 1.098  ops/ms
ClientGrpc.getUser                         thrpt       3   7.227 ± 1.717  ops/ms
ClientGrpc.listUser                        thrpt       3   5.861 ± 0.273  ops/ms
ClientGrpc.createUser                       avgt       3   4.237 ± 0.602   ms/op
ClientGrpc.existUser                        avgt       3   3.905 ± 0.456   ms/op
ClientGrpc.getUser                          avgt       3   4.138 ± 2.316   ms/op
ClientGrpc.listUser                         avgt       3   5.688 ± 0.807   ms/op
ClientGrpc.createUser                     sample  215356   4.458 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.963           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.337           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.886           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.705           ms/op
ClientGrpc.existUser                      sample  233329   4.115 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.861           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.365           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.418           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.406           ms/op
ClientGrpc.getUser                        sample  223009   4.303 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.029           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.407           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.731           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.298           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.736           ms/op
ClientGrpc.listUser                       sample  165994   5.780 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.495           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.847           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.354           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.447           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.874           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.735           ms/op
