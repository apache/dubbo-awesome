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
# Warmup Iteration   1: 4.096 ops/ms
# Warmup Iteration   2: 9.217 ops/ms
# Warmup Iteration   3: 10.091 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.596 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (10.528, 10.596, 10.665), stdev = 0.069
  CI (99.9%): [9.346, 11.847] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.185 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 10.991 ops/ms
Iteration   1: 11.162 ops/ms
Iteration   2: 11.072 ops/ms
Iteration   3: 11.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.150 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (11.072, 11.150, 11.214), stdev = 0.072
  CI (99.9%): [9.832, 12.467] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.876 ops/ms
# Warmup Iteration   2: 10.175 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.736 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.593 ±(99.9%) 2.645 ops/ms [Average]
  (min, avg, max) = (10.446, 10.593, 10.736), stdev = 0.145
  CI (99.9%): [7.948, 13.238] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.061 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.336 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.240 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (8.131, 8.240, 8.336), stdev = 0.103
  CI (99.9%): [6.357, 10.122] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.031, 3.050, 3.068), stdev = 0.019
  CI (99.9%): [2.706, 3.393] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 2.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.897, 2.930, 2.951), stdev = 0.029
  CI (99.9%): [2.407, 3.452] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.977, 2.994, 3.004), stdev = 0.015
  CI (99.9%): [2.719, 3.269] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.035 ms/op
Iteration   1: 3.960 ±(99.9%) 0.026 ms/op
Iteration   2: 3.925 ±(99.9%) 0.019 ms/op
Iteration   3: 3.882 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.882, 3.922, 3.960), stdev = 0.039
  CI (99.9%): [3.212, 4.633] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.633 ms/op
                 createUser·p0.999:  9.127 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.660 ms/op
                 createUser·p0.9999: 15.565 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.865 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318890
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25844 
    [ 2.500,  5.000) = 291455 
    [ 5.000,  7.500) = 1213 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.923 ms/op
     p(99.9900) =     27.565 ms/op
     p(99.9990) =     28.666 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.005 ms/op
Iteration   1: 2.902 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 12.500 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.735 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.448 ms/op
                 existUser·p0.9999: 12.892 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.441 ms/op
                 existUser·p0.9999: 15.809 ms/op
                 existUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337962
  mean =      2.837 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2018 
    [ 1.250,  2.500) = 42816 
    [ 2.500,  3.750) = 285952 
    [ 3.750,  5.000) = 6431 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     15.548 ms/op
     p(99.9990) =     16.011 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.506 ms/op
                 getUser·p0.9999: 13.360 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.902 ms/op
                 getUser·p0.9999: 21.252 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.646 ms/op
                 getUser·p0.9999: 18.984 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316573
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24507 
    [ 2.500,  5.000) = 290479 
    [ 5.000,  7.500) = 1287 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     20.765 ms/op
     p(99.9990) =     21.425 ms/op
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
# Warmup Iteration   1: 4.725 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  12.645 ms/op
                 listUser·p0.9999: 15.967 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.929 ms/op
                 listUser·p0.999:  15.200 ms/op
                 listUser·p0.9999: 22.934 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 25.356 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244140
  mean =      3.932 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3031 
    [ 2.500,  5.000) = 217397 
    [ 5.000,  7.500) = 22382 
    [ 7.500, 10.000) = 911 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     23.973 ms/op
     p(99.9990) =     26.185 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.596 ± 1.250  ops/ms
ClientGrpc.existUser                       thrpt       3  11.150 ± 1.317  ops/ms
ClientGrpc.getUser                         thrpt       3  10.593 ± 2.645  ops/ms
ClientGrpc.listUser                        thrpt       3   8.240 ± 1.882  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.343   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.522   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.275   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.711   ms/op
ClientGrpc.createUser                     sample  318890   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.623           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.923           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.565           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.738           ms/op
ClientGrpc.existUser                      sample  337962   2.837 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.548           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.138           ms/op
ClientGrpc.getUser                        sample  316573   3.031 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.765           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  244140   3.932 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.871           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.762           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.973           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
