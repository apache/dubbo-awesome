# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 5.826 ops/ms
# Warmup Iteration   3: 7.411 ops/ms
Iteration   1: 7.665 ops/ms
Iteration   2: 7.734 ops/ms
Iteration   3: 7.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.661 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (7.584, 7.661, 7.734), stdev = 0.075
  CI (99.9%): [6.291, 9.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ops/ms
# Warmup Iteration   2: 7.344 ops/ms
# Warmup Iteration   3: 7.965 ops/ms
Iteration   1: 8.181 ops/ms
Iteration   2: 8.216 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.221 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (8.181, 8.221, 8.266), stdev = 0.043
  CI (99.9%): [7.440, 9.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ops/ms
# Warmup Iteration   2: 6.895 ops/ms
# Warmup Iteration   3: 7.366 ops/ms
Iteration   1: 7.471 ops/ms
Iteration   2: 7.447 ops/ms
Iteration   3: 7.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.461 ±(99.9%) 0.222 ops/ms [Average]
  (min, avg, max) = (7.447, 7.461, 7.471), stdev = 0.012
  CI (99.9%): [7.239, 7.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ops/ms
# Warmup Iteration   2: 5.370 ops/ms
# Warmup Iteration   3: 5.810 ops/ms
Iteration   1: 5.906 ops/ms
Iteration   2: 5.961 ops/ms
Iteration   3: 5.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.924 ±(99.9%) 0.580 ops/ms [Average]
  (min, avg, max) = (5.905, 5.924, 5.961), stdev = 0.032
  CI (99.9%): [5.344, 6.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.010 ms/op
Iteration   1: 4.193 ±(99.9%) 0.003 ms/op
Iteration   2: 4.262 ±(99.9%) 0.006 ms/op
Iteration   3: 4.074 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.177 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (4.074, 4.177, 4.262), stdev = 0.095
  CI (99.9%): [2.443, 5.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.986 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.003 ms/op
Iteration   1: 3.843 ±(99.9%) 0.005 ms/op
Iteration   2: 3.802 ±(99.9%) 0.004 ms/op
Iteration   3: 3.876 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.840 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.802, 3.840, 3.876), stdev = 0.037
  CI (99.9%): [3.161, 4.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.170 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.005 ms/op
Iteration   1: 4.152 ±(99.9%) 0.005 ms/op
Iteration   2: 4.154 ±(99.9%) 0.006 ms/op
Iteration   3: 4.095 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.133 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (4.095, 4.133, 4.154), stdev = 0.034
  CI (99.9%): [3.520, 4.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.749 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.810 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.411 ±(99.9%) 0.020 ms/op
Iteration   1: 5.459 ±(99.9%) 0.014 ms/op
Iteration   2: 5.321 ±(99.9%) 0.019 ms/op
Iteration   3: 5.346 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.376 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (5.321, 5.376, 5.459), stdev = 0.074
  CI (99.9%): [4.033, 6.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.322 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.014 ms/op
Iteration   1: 4.236 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   4.121 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.398 ms/op
                 createUser·p0.999:  18.137 ms/op
                 createUser·p0.9999: 26.491 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 4.321 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  12.369 ms/op
                 createUser·p0.9999: 27.053 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  15.589 ms/op
                 createUser·p0.9999: 34.562 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225798
  mean =      4.249 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6002 
    [ 2.500,  5.000) = 183556 
    [ 5.000,  7.500) = 34008 
    [ 7.500, 10.000) = 1624 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     13.946 ms/op
     p(99.9900) =     32.244 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.012 ms/op
Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 16.048 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 3.830 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 16.564 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  12.230 ms/op
                 existUser·p0.9999: 31.395 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241040
  mean =      3.981 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8159 
    [ 2.500,  5.000) = 210433 
    [ 5.000,  7.500) = 20278 
    [ 7.500, 10.000) = 1507 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     30.562 ms/op
     p(99.9990) =     31.594 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.475 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.014 ms/op
Iteration   1: 4.416 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  10.741 ms/op
                 getUser·p0.9999: 19.129 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   2: 4.193 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   8.126 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 22.589 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 4.263 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.400 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223760
  mean =      4.289 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4278 
    [ 2.500,  5.000) = 180738 
    [ 5.000,  7.500) = 36355 
    [ 7.500, 10.000) = 1597 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     14.291 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     25.503 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.922 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.833 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.019 ms/op
Iteration   1: 5.308 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.688 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   10.094 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 17.388 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 5.294 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.619 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 5.422 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  21.857 ms/op
                 listUser·p0.9999: 38.011 ms/op
                 listUser·p1.00:   43.385 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179779
  mean =      5.341 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 82569 
    [ 5.000, 10.000) = 95012 
    [10.000, 15.000) = 1753 
    [15.000, 20.000) = 325 
    [20.000, 25.000) = 84 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     36.308 ms/op
     p(99.9990) =     43.228 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.661 ± 1.370  ops/ms
ClientGrpc.existUser                       thrpt       3   8.221 ± 0.781  ops/ms
ClientGrpc.getUser                         thrpt       3   7.461 ± 0.222  ops/ms
ClientGrpc.listUser                        thrpt       3   5.924 ± 0.580  ops/ms
ClientGrpc.createUser                       avgt       3   4.177 ± 1.734   ms/op
ClientGrpc.existUser                        avgt       3   3.840 ± 0.679   ms/op
ClientGrpc.getUser                          avgt       3   4.133 ± 0.614   ms/op
ClientGrpc.listUser                         avgt       3   5.376 ± 1.342   ms/op
ClientGrpc.createUser                     sample  225798   4.249 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.826           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.487           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.244           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.865           ms/op
ClientGrpc.existUser                      sample  241040   3.981 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.042           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.211           ms/op
ClientGrpc.getUser                        sample  223760   4.289 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.400           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.800           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.291           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.512           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.034           ms/op
ClientGrpc.listUser                       sample  179779   5.341 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.688           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.355           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.907           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.308           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          43.385           ms/op
