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
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 5.610 ops/ms
# Warmup Iteration   3: 7.302 ops/ms
Iteration   1: 7.703 ops/ms
Iteration   2: 7.488 ops/ms
Iteration   3: 7.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.543 ±(99.9%) 2.557 ops/ms [Average]
  (min, avg, max) = (7.439, 7.543, 7.703), stdev = 0.140
  CI (99.9%): [4.986, 10.100] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ops/ms
# Warmup Iteration   2: 7.650 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 7.998 ops/ms
Iteration   3: 8.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.117 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (7.998, 8.117, 8.250), stdev = 0.126
  CI (99.9%): [5.809, 10.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.730 ops/ms
# Warmup Iteration   2: 7.310 ops/ms
# Warmup Iteration   3: 7.610 ops/ms
Iteration   1: 7.565 ops/ms
Iteration   2: 7.645 ops/ms
Iteration   3: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.647 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (7.565, 7.647, 7.730), stdev = 0.083
  CI (99.9%): [6.135, 9.158] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 5.398 ops/ms
# Warmup Iteration   3: 5.488 ops/ms
Iteration   1: 5.760 ops/ms
Iteration   2: 5.835 ops/ms
Iteration   3: 5.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.844 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (5.760, 5.844, 5.938), stdev = 0.090
  CI (99.9%): [4.210, 7.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.004 ms/op
Iteration   1: 4.249 ±(99.9%) 0.003 ms/op
Iteration   2: 4.182 ±(99.9%) 0.002 ms/op
Iteration   3: 4.142 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.191 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (4.142, 4.191, 4.249), stdev = 0.054
  CI (99.9%): [3.205, 5.176] (assumes normal distribution)


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
# Warmup Iteration   1: 5.735 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.003 ms/op
Iteration   1: 3.951 ±(99.9%) 0.002 ms/op
Iteration   2: 3.815 ±(99.9%) 0.003 ms/op
Iteration   3: 3.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.894 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.815, 3.894, 3.951), stdev = 0.071
  CI (99.9%): [2.603, 5.186] (assumes normal distribution)


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
# Warmup Iteration   1: 6.774 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.003 ms/op
Iteration   1: 4.409 ±(99.9%) 0.002 ms/op
Iteration   2: 4.264 ±(99.9%) 0.003 ms/op
Iteration   3: 4.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.261 ±(99.9%) 2.733 ms/op [Average]
  (min, avg, max) = (4.109, 4.261, 4.409), stdev = 0.150
  CI (99.9%): [1.527, 6.994] (assumes normal distribution)


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
# Warmup Iteration   1: 7.316 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.980 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.026 ms/op
Iteration   1: 5.544 ±(99.9%) 0.016 ms/op
Iteration   2: 5.487 ±(99.9%) 0.014 ms/op
Iteration   3: 5.534 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.522 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (5.487, 5.522, 5.544), stdev = 0.030
  CI (99.9%): [4.970, 6.074] (assumes normal distribution)


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
# Warmup Iteration   1: 6.208 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.013 ms/op
Iteration   1: 4.335 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.216 ms/op
                 createUser·p0.999:  12.947 ms/op
                 createUser·p0.9999: 22.258 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 4.233 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  12.804 ms/op
                 createUser·p0.9999: 23.182 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 4.779 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.172 ms/op
                 createUser·p0.999:  23.264 ms/op
                 createUser·p0.9999: 26.060 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216293
  mean =      4.437 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3317 
    [ 2.500,  5.000) = 165348 
    [ 5.000,  7.500) = 42923 
    [ 7.500, 10.000) = 3654 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     14.974 ms/op
     p(99.9900) =     25.768 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 6.023 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.012 ms/op
Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 17.954 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.994 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  12.448 ms/op
                 existUser·p0.9999: 18.284 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  13.191 ms/op
                 existUser·p0.9999: 29.721 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241247
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7265 
    [ 2.500,  5.000) = 213233 
    [ 5.000,  7.500) = 18576 
    [ 7.500, 10.000) = 1564 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     29.923 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 6.421 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.012 ms/op
Iteration   1: 4.273 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   8.159 ms/op
                 getUser·p0.999:  13.473 ms/op
                 getUser·p0.9999: 16.450 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 4.372 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.124 ms/op
                 getUser·p0.999:  12.013 ms/op
                 getUser·p0.9999: 19.280 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 4.373 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  11.795 ms/op
                 getUser·p0.9999: 21.314 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221084
  mean =      4.339 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4743 
    [ 2.500,  5.000) = 173676 
    [ 5.000,  7.500) = 39918 
    [ 7.500, 10.000) = 2056 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     12.762 ms/op
     p(99.9900) =     19.912 ms/op
     p(99.9990) =     21.901 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 7.827 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.227 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.019 ms/op
Iteration   1: 5.616 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.488 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 19.734 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 5.467 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 27.137 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 5.396 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174781
  mean =      5.491 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 151 
    [ 2.500,  5.000) = 71247 
    [ 5.000,  7.500) = 89825 
    [ 7.500, 10.000) = 10663 
    [10.000, 12.500) = 1973 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     23.510 ms/op
     p(99.9990) =     27.845 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.543 ± 2.557  ops/ms
ClientGrpc.existUser                       thrpt       3   8.117 ± 2.308  ops/ms
ClientGrpc.getUser                         thrpt       3   7.647 ± 1.512  ops/ms
ClientGrpc.listUser                        thrpt       3   5.844 ± 1.634  ops/ms
ClientGrpc.createUser                       avgt       3   4.191 ± 0.986   ms/op
ClientGrpc.existUser                        avgt       3   3.894 ± 1.292   ms/op
ClientGrpc.getUser                          avgt       3   4.261 ± 2.733   ms/op
ClientGrpc.listUser                         avgt       3   5.522 ± 0.552   ms/op
ClientGrpc.createUser                     sample  216293   4.437 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.935           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.974           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.768           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.149           ms/op
ClientGrpc.existUser                      sample  241247   3.980 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.291           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.403           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.228           ms/op
ClientGrpc.getUser                        sample  221084   4.339 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.897           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.762           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.912           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  174781   5.491 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.488           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.961           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.579           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
