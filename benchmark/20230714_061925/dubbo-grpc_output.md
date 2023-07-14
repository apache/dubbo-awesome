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
# Warmup Iteration   1: 4.125 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.267 ±(99.9%) 2.961 ops/ms [Average]
  (min, avg, max) = (10.152, 10.267, 10.452), stdev = 0.162
  CI (99.9%): [7.306, 13.228] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.677 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.687 ±(99.9%) 2.979 ops/ms [Average]
  (min, avg, max) = (10.529, 10.687, 10.856), stdev = 0.163
  CI (99.9%): [7.708, 13.667] (assumes normal distribution)


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
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 9.667 ops/ms
# Warmup Iteration   3: 10.139 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.219 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (10.116, 10.219, 10.312), stdev = 0.098
  CI (99.9%): [8.422, 12.016] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ops/ms
# Warmup Iteration   2: 7.340 ops/ms
# Warmup Iteration   3: 7.562 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 7.846 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.825 ±(99.9%) 0.390 ops/ms [Average]
  (min, avg, max) = (7.804, 7.825, 7.846), stdev = 0.021
  CI (99.9%): [7.435, 8.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.001 ms/op
Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.051, 3.082, 3.104), stdev = 0.028
  CI (99.9%): [2.573, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.003 ms/op
Iteration   1: 2.913 ±(99.9%) 0.003 ms/op
Iteration   2: 2.881 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (2.881, 2.918, 2.962), stdev = 0.041
  CI (99.9%): [2.171, 3.666] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.056 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.046, 3.056, 3.063), stdev = 0.009
  CI (99.9%): [2.899, 3.213] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.016 ms/op
Iteration   1: 3.972 ±(99.9%) 0.015 ms/op
Iteration   2: 3.955 ±(99.9%) 0.024 ms/op
Iteration   3: 3.911 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.911, 3.946, 3.972), stdev = 0.032
  CI (99.9%): [3.369, 4.523] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.768 ms/op
                 createUser·p0.9999: 14.544 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.393 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 15.698 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316652
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 502 
    [ 1.250,  2.500) = 20347 
    [ 2.500,  3.750) = 277563 
    [ 3.750,  5.000) = 16524 
    [ 5.000,  6.250) = 988 
    [ 6.250,  7.500) = 392 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.716 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 14.944 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  7.016 ms/op
                 existUser·p0.9999: 24.451 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326672
  mean =      2.937 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37634 
    [ 2.500,  5.000) = 288036 
    [ 5.000,  7.500) = 810 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     19.711 ms/op
     p(99.9990) =     24.738 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  12.321 ms/op
                 getUser·p0.9999: 13.714 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.201 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.153 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312618
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19057 
    [ 2.500,  5.000) = 292124 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     28.336 ms/op
     p(99.9990) =     30.364 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 5.159 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.877 ms/op
                 listUser·p0.9999: 23.040 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.752 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.742 ms/op
                 listUser·p0.9999: 17.887 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.700 ms/op
                 listUser·p0.9999: 19.737 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237312
  mean =      4.043 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2198 
    [ 2.500,  5.000) = 210173 
    [ 5.000,  7.500) = 23452 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.248 ms/op
     p(99.9900) =     22.172 ms/op
     p(99.9990) =     23.319 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.267 ± 2.961  ops/ms
ClientGrpc.existUser                       thrpt       3  10.687 ± 2.979  ops/ms
ClientGrpc.getUser                         thrpt       3  10.219 ± 1.797  ops/ms
ClientGrpc.listUser                        thrpt       3   7.825 ± 0.390  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.509   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.747   ms/op
ClientGrpc.getUser                          avgt       3   3.056 ± 0.157   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.577   ms/op
ClientGrpc.createUser                     sample  316652   3.034 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.393           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.700           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.793           ms/op
ClientGrpc.existUser                      sample  326672   2.937 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.564           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.756           ms/op
ClientGrpc.getUser                        sample  312618   3.072 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.708           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.336           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.392           ms/op
ClientGrpc.listUser                       sample  237312   4.043 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.022           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.248           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.172           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
