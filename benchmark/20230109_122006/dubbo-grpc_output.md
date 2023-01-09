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
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 5.755 ops/ms
# Warmup Iteration   3: 7.011 ops/ms
Iteration   1: 7.455 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.381 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (7.317, 7.381, 7.455), stdev = 0.069
  CI (99.9%): [6.118, 8.645] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 7.738 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.972 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (7.923, 7.972, 8.029), stdev = 0.054
  CI (99.9%): [6.993, 8.950] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ops/ms
# Warmup Iteration   2: 7.578 ops/ms
# Warmup Iteration   3: 8.069 ops/ms
Iteration   1: 7.929 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.928 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (7.849, 7.928, 8.006), stdev = 0.078
  CI (99.9%): [6.503, 9.353] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.599 ops/ms
# Warmup Iteration   2: 5.260 ops/ms
# Warmup Iteration   3: 6.009 ops/ms
Iteration   1: 5.909 ops/ms
Iteration   2: 5.748 ops/ms
Iteration   3: 6.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.916 ±(99.9%) 3.138 ops/ms [Average]
  (min, avg, max) = (5.748, 5.916, 6.092), stdev = 0.172
  CI (99.9%): [2.778, 9.054] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.344 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.003 ms/op
Iteration   1: 4.307 ±(99.9%) 0.003 ms/op
Iteration   2: 4.416 ±(99.9%) 0.005 ms/op
Iteration   3: 4.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.403 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (4.307, 4.403, 4.485), stdev = 0.090
  CI (99.9%): [2.767, 6.038] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.943 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.007 ms/op
Iteration   1: 4.151 ±(99.9%) 0.004 ms/op
Iteration   2: 4.246 ±(99.9%) 0.003 ms/op
Iteration   3: 4.182 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.193 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (4.151, 4.193, 4.246), stdev = 0.049
  CI (99.9%): [3.303, 5.083] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.593 ±(99.9%) 0.005 ms/op
Iteration   1: 4.347 ±(99.9%) 0.003 ms/op
Iteration   2: 4.416 ±(99.9%) 0.004 ms/op
Iteration   3: 4.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.405 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (4.347, 4.405, 4.450), stdev = 0.053
  CI (99.9%): [3.439, 5.371] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.336 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.944 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.552 ±(99.9%) 0.013 ms/op
Iteration   1: 5.388 ±(99.9%) 0.016 ms/op
Iteration   2: 5.391 ±(99.9%) 0.011 ms/op
Iteration   3: 5.401 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.393 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (5.388, 5.393, 5.401), stdev = 0.007
  CI (99.9%): [5.268, 5.518] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.412 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.015 ms/op
Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  13.089 ms/op
                 createUser·p0.9999: 15.612 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 4.253 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  12.498 ms/op
                 createUser·p0.9999: 20.838 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 4.186 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  12.152 ms/op
                 createUser·p0.9999: 22.167 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228646
  mean =      4.194 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5811 
    [ 2.500,  5.000) = 192010 
    [ 5.000,  7.500) = 27760 
    [ 7.500, 10.000) = 2193 
    [10.000, 12.500) = 651 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     21.238 ms/op
     p(99.9990) =     22.647 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.668 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
Iteration   1: 4.059 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   8.505 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 16.448 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.095 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  11.560 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 4.233 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.889 ms/op
                 existUser·p0.999:  14.222 ms/op
                 existUser·p0.9999: 21.051 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233013
  mean =      4.121 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8726 
    [ 2.500,  5.000) = 190939 
    [ 5.000,  7.500) = 30418 
    [ 7.500, 10.000) = 2083 
    [10.000, 12.500) = 654 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     21.368 ms/op
     p(99.9990) =     23.670 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.015 ms/op
Iteration   1: 4.484 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.718 ms/op
                 getUser·p0.95:   6.226 ms/op
                 getUser·p0.99:   8.845 ms/op
                 getUser·p0.999:  13.463 ms/op
                 getUser·p0.9999: 28.725 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   2: 4.415 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.114 ms/op
                 getUser·p0.999:  13.149 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 4.346 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  12.767 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217362
  mean =      4.414 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5871 
    [ 2.500,  5.000) = 157268 
    [ 5.000,  7.500) = 51058 
    [ 7.500, 10.000) = 2285 
    [10.000, 12.500) = 559 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     13.200 ms/op
     p(99.9900) =     27.837 ms/op
     p(99.9990) =     29.146 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 7.553 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.022 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.486 ±(99.9%) 0.021 ms/op
Iteration   1: 5.421 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   5.087 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  16.168 ms/op
                 listUser·p0.9999: 19.900 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 5.495 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  19.040 ms/op
                 listUser·p0.9999: 33.128 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 4.964 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  22.058 ms/op
                 listUser·p0.9999: 27.060 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181724
  mean =      5.283 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 567 
    [ 2.500,  5.000) = 93980 
    [ 5.000,  7.500) = 72086 
    [ 7.500, 10.000) = 12087 
    [10.000, 12.500) = 2184 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     31.936 ms/op
     p(99.9990) =     33.447 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.381 ± 1.263  ops/ms
ClientGrpc.existUser                       thrpt       3   7.972 ± 0.979  ops/ms
ClientGrpc.getUser                         thrpt       3   7.928 ± 1.425  ops/ms
ClientGrpc.listUser                        thrpt       3   5.916 ± 3.138  ops/ms
ClientGrpc.createUser                       avgt       3   4.403 ± 1.635   ms/op
ClientGrpc.existUser                        avgt       3   4.193 ± 0.890   ms/op
ClientGrpc.getUser                          avgt       3   4.405 ± 0.966   ms/op
ClientGrpc.listUser                         avgt       3   5.393 ± 0.125   ms/op
ClientGrpc.createUser                     sample  228646   4.194 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.419           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.238           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.774           ms/op
ClientGrpc.existUser                      sample  233013   4.121 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.579           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.829           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.368           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.757           ms/op
ClientGrpc.getUser                        sample  217362   4.414 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.816           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.200           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.262           ms/op
ClientGrpc.listUser                       sample  181724   5.283 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.221           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.022           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.936           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
