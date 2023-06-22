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
# Warmup Iteration   1: 2.290 ops/ms
# Warmup Iteration   2: 5.556 ops/ms
# Warmup Iteration   3: 7.372 ops/ms
Iteration   1: 7.234 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.284 ±(99.9%) 0.798 ops/ms [Average]
  (min, avg, max) = (7.234, 7.284, 7.317), stdev = 0.044
  CI (99.9%): [6.485, 8.082] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ops/ms
# Warmup Iteration   2: 7.452 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.082 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.137 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (8.082, 8.137, 8.185), stdev = 0.052
  CI (99.9%): [7.191, 9.084] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ops/ms
# Warmup Iteration   2: 6.869 ops/ms
# Warmup Iteration   3: 7.187 ops/ms
Iteration   1: 7.455 ops/ms
Iteration   2: 7.680 ops/ms
Iteration   3: 7.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.433 ±(99.9%) 4.734 ops/ms [Average]
  (min, avg, max) = (7.163, 7.433, 7.680), stdev = 0.259
  CI (99.9%): [2.699, 12.167] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 5.287 ops/ms
# Warmup Iteration   3: 5.848 ops/ms
Iteration   1: 5.815 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 5.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.864 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (5.787, 5.864, 5.989), stdev = 0.110
  CI (99.9%): [3.865, 7.863] (assumes normal distribution)


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
# Warmup Iteration   1: 6.608 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.019 ms/op
Iteration   1: 4.514 ±(99.9%) 0.003 ms/op
Iteration   2: 4.274 ±(99.9%) 0.004 ms/op
Iteration   3: 4.365 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.384 ±(99.9%) 2.212 ms/op [Average]
  (min, avg, max) = (4.274, 4.384, 4.514), stdev = 0.121
  CI (99.9%): [2.173, 6.596] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.757 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.003 ms/op
Iteration   1: 4.265 ±(99.9%) 0.003 ms/op
Iteration   2: 4.271 ±(99.9%) 0.002 ms/op
Iteration   3: 4.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.200 ±(99.9%) 2.130 ms/op [Average]
  (min, avg, max) = (4.065, 4.200, 4.271), stdev = 0.117
  CI (99.9%): [2.070, 6.331] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.391 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.003 ms/op
Iteration   1: 4.308 ±(99.9%) 0.002 ms/op
Iteration   2: 4.307 ±(99.9%) 0.005 ms/op
Iteration   3: 4.303 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.306 ±(99.9%) 0.045 ms/op [Average]
  (min, avg, max) = (4.303, 4.306, 4.308), stdev = 0.002
  CI (99.9%): [4.261, 4.351] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.908 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.618 ±(99.9%) 0.028 ms/op
Iteration   1: 5.527 ±(99.9%) 0.011 ms/op
Iteration   2: 5.514 ±(99.9%) 0.014 ms/op
Iteration   3: 5.408 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.483 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (5.408, 5.483, 5.527), stdev = 0.065
  CI (99.9%): [4.296, 6.670] (assumes normal distribution)


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
# Warmup Iteration   1: 6.719 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.014 ms/op
Iteration   1: 4.376 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  15.851 ms/op
                 createUser·p0.9999: 25.760 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.407 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.882 ms/op
                 createUser·p0.999:  14.080 ms/op
                 createUser·p0.9999: 28.434 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 4.255 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.153 ms/op
                 createUser·p0.90:   5.218 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220913
  mean =      4.345 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2321 
    [ 2.500,  5.000) = 179377 
    [ 5.000,  7.500) = 37161 
    [ 7.500, 10.000) = 1445 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.684 ms/op
     p(99.9900) =     28.407 ms/op
     p(99.9990) =     28.855 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 6.044 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.011 ms/op
Iteration   1: 4.073 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.961 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   6.770 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 18.790 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.956 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  12.600 ms/op
                 existUser·p0.9999: 17.332 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.997 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.100 ms/op
                 existUser·p0.999:  10.570 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239475
  mean =      4.008 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4075 
    [ 2.500,  5.000) = 213697 
    [ 5.000,  7.500) = 20461 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     11.839 ms/op
     p(99.9900) =     20.713 ms/op
     p(99.9990) =     21.654 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.773 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.012 ms/op
Iteration   1: 4.280 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.358 ms/op
                 getUser·p0.999:  12.352 ms/op
                 getUser·p0.9999: 16.827 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 4.301 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  11.561 ms/op
                 getUser·p0.9999: 18.027 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 4.308 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  12.501 ms/op
                 getUser·p0.9999: 20.401 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223268
  mean =      4.296 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4216 
    [ 2.500,  5.000) = 181277 
    [ 5.000,  7.500) = 35974 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     11.825 ms/op
     p(99.9900) =     19.191 ms/op
     p(99.9990) =     20.860 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.867 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.882 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.020 ms/op
Iteration   1: 5.507 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  15.318 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 5.551 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  18.533 ms/op
                 listUser·p0.9999: 28.679 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 5.464 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  19.218 ms/op
                 listUser·p0.9999: 23.762 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174308
  mean =      5.507 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 62989 
    [ 5.000,  7.500) = 99228 
    [ 7.500, 10.000) = 10145 
    [10.000, 12.500) = 1377 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      5.288 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     17.881 ms/op
     p(99.9900) =     27.688 ms/op
     p(99.9990) =     29.156 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.284 ± 0.798  ops/ms
ClientGrpc.existUser                       thrpt       3   8.137 ± 0.946  ops/ms
ClientGrpc.getUser                         thrpt       3   7.433 ± 4.734  ops/ms
ClientGrpc.listUser                        thrpt       3   5.864 ± 1.999  ops/ms
ClientGrpc.createUser                       avgt       3   4.384 ± 2.212   ms/op
ClientGrpc.existUser                        avgt       3   4.200 ± 2.130   ms/op
ClientGrpc.getUser                          avgt       3   4.306 ± 0.045   ms/op
ClientGrpc.listUser                         avgt       3   5.483 ± 1.187   ms/op
ClientGrpc.createUser                     sample  220913   4.345 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.895           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.000           ms/op
ClientGrpc.existUser                      sample  239475   4.008 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.937           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.839           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.713           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.823           ms/op
ClientGrpc.getUser                        sample  223268   4.296 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.094           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.201           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.825           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.191           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  174308   5.507 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.288           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.881           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.688           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.229           ms/op
