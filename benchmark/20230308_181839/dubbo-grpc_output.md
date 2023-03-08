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
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 5.761 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 8.106 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.141 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (8.063, 8.141, 8.255), stdev = 0.101
  CI (99.9%): [6.301, 9.982] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 8.732 ops/ms
Iteration   2: 8.561 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.513 ±(99.9%) 4.504 ops/ms [Average]
  (min, avg, max) = (8.245, 8.513, 8.732), stdev = 0.247
  CI (99.9%): [4.009, 13.017] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.772 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.182 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 7.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.079 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (7.938, 8.079, 8.182), stdev = 0.126
  CI (99.9%): [5.774, 10.385] (assumes normal distribution)


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
# Warmup Iteration   1: 3.934 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 5.887 ops/ms
Iteration   1: 5.910 ops/ms
Iteration   2: 6.068 ops/ms
Iteration   3: 6.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.049 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (5.910, 6.049, 6.168), stdev = 0.130
  CI (99.9%): [3.677, 8.421] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.500 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.013 ms/op
Iteration   1: 4.055 ±(99.9%) 0.003 ms/op
Iteration   2: 4.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.016 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.948, 4.016, 4.055), stdev = 0.060
  CI (99.9%): [2.927, 5.106] (assumes normal distribution)


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
# Warmup Iteration   1: 6.329 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
Iteration   1: 3.703 ±(99.9%) 0.005 ms/op
Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
Iteration   3: 3.799 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.800 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (3.703, 3.800, 3.898), stdev = 0.098
  CI (99.9%): [2.019, 5.582] (assumes normal distribution)


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
# Warmup Iteration   1: 6.586 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.006 ms/op
Iteration   1: 4.220 ±(99.9%) 0.004 ms/op
Iteration   2: 4.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.079 ±(99.9%) 2.281 ms/op [Average]
  (min, avg, max) = (3.979, 4.079, 4.220), stdev = 0.125
  CI (99.9%): [1.798, 6.361] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.706 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.310 ±(99.9%) 0.016 ms/op
Iteration   1: 5.173 ±(99.9%) 0.013 ms/op
Iteration   2: 5.480 ±(99.9%) 0.016 ms/op
Iteration   3: 5.361 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.338 ±(99.9%) 2.826 ms/op [Average]
  (min, avg, max) = (5.173, 5.338, 5.480), stdev = 0.155
  CI (99.9%): [2.513, 8.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.443 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
Iteration   1: 3.968 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   8.050 ms/op
                 createUser·p0.999:  13.535 ms/op
                 createUser·p0.9999: 21.690 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  10.429 ms/op
                 createUser·p0.9999: 19.629 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   3: 4.189 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   6.087 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  14.152 ms/op
                 createUser·p0.9999: 32.792 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236787
  mean =      4.053 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7540 
    [ 2.500,  5.000) = 200025 
    [ 5.000,  7.500) = 26134 
    [ 7.500, 10.000) = 2379 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     32.320 ms/op
     p(99.9990) =     33.191 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 5.905 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.810 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 16.584 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.873 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  13.196 ms/op
                 existUser·p0.9999: 17.588 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.852 ms/op
                 existUser·p0.999:  11.831 ms/op
                 existUser·p0.9999: 20.044 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 249484
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7770 
    [ 2.500,  5.000) = 223496 
    [ 5.000,  7.500) = 16310 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     12.116 ms/op
     p(99.9900) =     19.631 ms/op
     p(99.9990) =     21.140 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 6.636 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
Iteration   1: 4.243 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 4.260 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.226 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  13.925 ms/op
                 getUser·p0.9999: 28.442 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 4.097 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 28.067 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228773
  mean =      4.199 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8548 
    [ 2.500,  5.000) = 181825 
    [ 5.000,  7.500) = 35035 
    [ 7.500, 10.000) = 2559 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     13.389 ms/op
     p(99.9900) =     27.922 ms/op
     p(99.9990) =     28.962 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 8.216 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.695 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.288 ±(99.9%) 0.021 ms/op
Iteration   1: 5.326 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 5.367 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.681 ms/op
                 listUser·p0.999:  19.634 ms/op
                 listUser·p0.9999: 25.396 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 5.285 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.258 ms/op
                 listUser·p0.99:   10.534 ms/op
                 listUser·p0.999:  21.398 ms/op
                 listUser·p0.9999: 36.484 ms/op
                 listUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180242
  mean =      5.326 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 689 
    [ 2.500,  5.000) = 92913 
    [ 5.000,  7.500) = 70975 
    [ 7.500, 10.000) = 13216 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     20.825 ms/op
     p(99.9900) =     33.193 ms/op
     p(99.9990) =     37.447 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.141 ± 1.841  ops/ms
ClientGrpc.existUser                       thrpt       3   8.513 ± 4.504  ops/ms
ClientGrpc.getUser                         thrpt       3   8.079 ± 2.306  ops/ms
ClientGrpc.listUser                        thrpt       3   6.049 ± 2.372  ops/ms
ClientGrpc.createUser                       avgt       3   4.016 ± 1.089   ms/op
ClientGrpc.existUser                        avgt       3   3.800 ± 1.782   ms/op
ClientGrpc.getUser                          avgt       3   4.079 ± 2.281   ms/op
ClientGrpc.listUser                         avgt       3   5.338 ± 2.826   ms/op
ClientGrpc.createUser                     sample  236787   4.053 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.447           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.930           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.320           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.358           ms/op
ClientGrpc.existUser                      sample  249484   3.847 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.883           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.116           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.631           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  228773   4.199 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.846           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.922           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.098           ms/op
ClientGrpc.listUser                       sample  180242   5.326 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.825           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.193           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.552           ms/op
