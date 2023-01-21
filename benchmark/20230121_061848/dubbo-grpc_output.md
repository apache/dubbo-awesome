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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 5.980 ops/ms
# Warmup Iteration   3: 7.356 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 7.644 ops/ms
Iteration   3: 7.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.503 ±(99.9%) 4.457 ops/ms [Average]
  (min, avg, max) = (7.221, 7.503, 7.644), stdev = 0.244
  CI (99.9%): [3.045, 11.960] (assumes normal distribution)


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
# Warmup Iteration   1: 5.043 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.844 ops/ms
Iteration   1: 7.916 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.935 ±(99.9%) 0.319 ops/ms [Average]
  (min, avg, max) = (7.916, 7.935, 7.950), stdev = 0.017
  CI (99.9%): [7.617, 8.254] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ops/ms
# Warmup Iteration   2: 6.975 ops/ms
# Warmup Iteration   3: 7.677 ops/ms
Iteration   1: 7.585 ops/ms
Iteration   2: 7.438 ops/ms
Iteration   3: 7.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.525 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (7.438, 7.525, 7.585), stdev = 0.077
  CI (99.9%): [6.114, 8.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ops/ms
# Warmup Iteration   2: 5.135 ops/ms
# Warmup Iteration   3: 5.965 ops/ms
Iteration   1: 5.927 ops/ms
Iteration   2: 5.982 ops/ms
Iteration   3: 5.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.949 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (5.927, 5.949, 5.982), stdev = 0.029
  CI (99.9%): [5.424, 6.475] (assumes normal distribution)


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
# Warmup Iteration   1: 6.880 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.003 ms/op
Iteration   1: 4.267 ±(99.9%) 0.004 ms/op
Iteration   2: 4.500 ±(99.9%) 0.003 ms/op
Iteration   3: 4.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.429 ±(99.9%) 2.564 ms/op [Average]
  (min, avg, max) = (4.267, 4.429, 4.519), stdev = 0.141
  CI (99.9%): [1.865, 6.992] (assumes normal distribution)


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
# Warmup Iteration   1: 6.174 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.003 ms/op
Iteration   1: 4.041 ±(99.9%) 0.004 ms/op
Iteration   2: 4.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.998 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.029 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.998, 4.029, 4.047), stdev = 0.027
  CI (99.9%): [3.540, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 6.498 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.004 ms/op
Iteration   1: 4.287 ±(99.9%) 0.005 ms/op
Iteration   2: 4.325 ±(99.9%) 0.002 ms/op
Iteration   3: 4.183 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.265 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (4.183, 4.265, 4.325), stdev = 0.073
  CI (99.9%): [2.927, 5.603] (assumes normal distribution)


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
# Warmup Iteration   1: 7.326 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.457 ±(99.9%) 0.017 ms/op
Iteration   1: 5.288 ±(99.9%) 0.008 ms/op
Iteration   2: 5.152 ±(99.9%) 0.008 ms/op
Iteration   3: 5.280 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.240 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (5.152, 5.240, 5.288), stdev = 0.076
  CI (99.9%): [3.845, 6.635] (assumes normal distribution)


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
# Warmup Iteration   1: 6.608 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.013 ms/op
Iteration   1: 4.262 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.149 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  13.500 ms/op
                 createUser·p0.9999: 16.474 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   2: 4.380 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  12.646 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 4.323 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  13.281 ms/op
                 createUser·p0.9999: 19.443 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222140
  mean =      4.321 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4295 
    [ 2.500,  5.000) = 170518 
    [ 5.000,  7.500) = 45547 
    [ 7.500, 10.000) = 1285 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     13.301 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     31.377 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 6.066 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.012 ms/op
Iteration   1: 4.166 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  9.084 ms/op
                 existUser·p0.9999: 15.215 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   2: 4.035 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   7.319 ms/op
                 existUser·p0.999:  19.333 ms/op
                 existUser·p0.9999: 25.463 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 4.179 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  9.739 ms/op
                 existUser·p0.9999: 22.360 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232590
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7887 
    [ 2.500,  5.000) = 188470 
    [ 5.000,  7.500) = 34726 
    [ 7.500, 10.000) = 1233 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     10.224 ms/op
     p(99.9900) =     23.609 ms/op
     p(99.9990) =     25.679 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 6.989 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.428 ±(99.9%) 0.014 ms/op
Iteration   1: 4.251 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  14.476 ms/op
                 getUser·p0.9999: 22.232 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 4.341 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  10.820 ms/op
                 getUser·p0.9999: 21.516 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 4.250 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  11.637 ms/op
                 getUser·p0.9999: 26.787 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224254
  mean =      4.280 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4245 
    [ 2.500,  5.000) = 175980 
    [ 5.000,  7.500) = 42194 
    [ 7.500, 10.000) = 1439 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     26.037 ms/op
     p(99.9990) =     27.100 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.227 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.805 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.473 ±(99.9%) 0.019 ms/op
Iteration   1: 5.322 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  21.032 ms/op
                 listUser·p0.9999: 24.411 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 5.352 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  16.671 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 5.188 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  21.179 ms/op
                 listUser·p0.9999: 24.145 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181489
  mean =      5.286 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 335 
    [ 2.500,  5.000) = 91232 
    [ 5.000,  7.500) = 77563 
    [ 7.500, 10.000) = 10234 
    [10.000, 12.500) = 1302 
    [12.500, 15.000) = 393 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     19.563 ms/op
     p(99.9900) =     24.047 ms/op
     p(99.9990) =     24.764 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.503 ± 4.457  ops/ms
ClientGrpc.existUser                       thrpt       3   7.935 ± 0.319  ops/ms
ClientGrpc.getUser                         thrpt       3   7.525 ± 1.411  ops/ms
ClientGrpc.listUser                        thrpt       3   5.949 ± 0.526  ops/ms
ClientGrpc.createUser                       avgt       3   4.429 ± 2.564   ms/op
ClientGrpc.existUser                        avgt       3   4.029 ± 0.489   ms/op
ClientGrpc.getUser                          avgt       3   4.265 ± 1.338   ms/op
ClientGrpc.listUser                         avgt       3   5.240 ± 1.395   ms/op
ClientGrpc.createUser                     sample  222140   4.321 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.028           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.168           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.301           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.048           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.457           ms/op
ClientGrpc.existUser                      sample  232590   4.126 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.224           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.609           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  224254   4.280 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.763           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.037           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.263           ms/op
ClientGrpc.listUser                       sample  181489   5.286 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.417           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.930           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.563           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.047           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
