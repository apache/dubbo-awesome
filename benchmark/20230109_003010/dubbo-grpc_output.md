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
# Warmup Iteration   1: 4.886 ops/ms
# Warmup Iteration   2: 9.387 ops/ms
# Warmup Iteration   3: 10.464 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.423 ±(99.9%) 4.900 ops/ms [Average]
  (min, avg, max) = (10.118, 10.423, 10.623), stdev = 0.269
  CI (99.9%): [5.523, 15.323] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.768 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 10.896 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 11.121 ops/ms
Iteration   3: 10.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.932 ±(99.9%) 4.130 ops/ms [Average]
  (min, avg, max) = (10.681, 10.932, 11.121), stdev = 0.226
  CI (99.9%): [6.802, 15.061] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.162 ops/ms
# Warmup Iteration   2: 10.256 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.382 ±(99.9%) 4.528 ops/ms [Average]
  (min, avg, max) = (10.099, 10.382, 10.565), stdev = 0.248
  CI (99.9%): [5.854, 14.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ops/ms
# Warmup Iteration   2: 7.927 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 7.910 ops/ms
Iteration   3: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.005 ±(99.9%) 1.531 ops/ms [Average]
  (min, avg, max) = (7.910, 8.005, 8.069), stdev = 0.084
  CI (99.9%): [6.474, 9.536] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.002 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.092, 3.104, 3.123), stdev = 0.017
  CI (99.9%): [2.798, 3.410] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.915 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (2.915, 2.936, 2.955), stdev = 0.020
  CI (99.9%): [2.573, 3.298] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 3.112 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.057, 3.080, 3.112), stdev = 0.028
  CI (99.9%): [2.560, 3.600] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.608 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.034 ms/op
Iteration   1: 3.923 ±(99.9%) 0.022 ms/op
Iteration   2: 3.964 ±(99.9%) 0.032 ms/op
Iteration   3: 3.992 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.960 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.923, 3.960, 3.992), stdev = 0.035
  CI (99.9%): [3.325, 4.594] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.122 ms/op
                 createUser·p0.999:  7.242 ms/op
                 createUser·p0.9999: 13.105 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  11.519 ms/op
                 createUser·p0.9999: 16.982 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.926 ms/op
                 createUser·p0.9999: 23.651 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316910
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25765 
    [ 2.500,  5.000) = 290181 
    [ 5.000,  7.500) = 599 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.708 ms/op
     p(99.9900) =     22.980 ms/op
     p(99.9990) =     26.093 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.428 ms/op
                 existUser·p0.9999: 11.534 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  7.184 ms/op
                 existUser·p0.9999: 19.239 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.235 ms/op
                 existUser·p0.9999: 17.571 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326475
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1696 
    [ 1.250,  2.500) = 46566 
    [ 2.500,  3.750) = 260570 
    [ 3.750,  5.000) = 16863 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.599 ms/op
     p(99.9900) =     18.211 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.102 ms/op
                 getUser·p0.9999: 15.671 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.388 ms/op
                 getUser·p0.9999: 16.095 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 19.258 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311293
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1361 
    [ 1.250,  2.500) = 26075 
    [ 2.500,  3.750) = 256324 
    [ 3.750,  5.000) = 26504 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 85 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.326 ms/op
     p(99.9900) =     18.571 ms/op
     p(99.9990) =     19.493 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.978 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.672 ms/op
                 listUser·p0.9999: 21.929 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.552 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240044
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4101 
    [ 2.500,  5.000) = 203757 
    [ 5.000,  7.500) = 31024 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     24.582 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.423 ± 4.900  ops/ms
ClientGrpc.existUser                       thrpt       3  10.932 ± 4.130  ops/ms
ClientGrpc.getUser                         thrpt       3  10.382 ± 4.528  ops/ms
ClientGrpc.listUser                        thrpt       3   8.005 ± 1.531  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.306   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.363   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.960 ± 0.634   ms/op
ClientGrpc.createUser                     sample  316910   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.567           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.708           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.980           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  326475   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.599           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.211           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  311293   3.083 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.675           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.326           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.571           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  240044   3.999 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.023           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
