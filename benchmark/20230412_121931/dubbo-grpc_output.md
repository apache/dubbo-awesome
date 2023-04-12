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
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 7.294 ops/ms
Iteration   1: 6.985 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.563 ±(99.9%) 9.174 ops/ms [Average]
  (min, avg, max) = (6.985, 7.563, 7.900), stdev = 0.503
  CI (99.9%): [≈ 0, 16.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ops/ms
# Warmup Iteration   2: 7.410 ops/ms
# Warmup Iteration   3: 8.357 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.151 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.266 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (8.151, 8.266, 8.416), stdev = 0.136
  CI (99.9%): [5.783, 10.750] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ops/ms
# Warmup Iteration   2: 7.236 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 7.772 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.816 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (7.772, 7.816, 7.843), stdev = 0.038
  CI (99.9%): [7.114, 8.518] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ops/ms
# Warmup Iteration   2: 5.452 ops/ms
# Warmup Iteration   3: 5.916 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 5.874 ops/ms
Iteration   3: 6.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.942 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (5.874, 5.942, 6.008), stdev = 0.067
  CI (99.9%): [4.723, 7.161] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.004 ms/op
Iteration   1: 4.192 ±(99.9%) 0.004 ms/op
Iteration   2: 4.063 ±(99.9%) 0.003 ms/op
Iteration   3: 4.160 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.138 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (4.063, 4.138, 4.192), stdev = 0.068
  CI (99.9%): [2.906, 5.371] (assumes normal distribution)


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
# Warmup Iteration   1: 6.111 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.003 ms/op
Iteration   1: 3.921 ±(99.9%) 0.006 ms/op
Iteration   2: 3.808 ±(99.9%) 0.002 ms/op
Iteration   3: 3.938 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.889 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.808, 3.889, 3.938), stdev = 0.071
  CI (99.9%): [2.602, 5.176] (assumes normal distribution)


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
# Warmup Iteration   1: 6.325 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.014 ms/op
Iteration   1: 4.228 ±(99.9%) 0.002 ms/op
Iteration   2: 4.279 ±(99.9%) 0.002 ms/op
Iteration   3: 4.119 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.209 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (4.119, 4.209, 4.279), stdev = 0.082
  CI (99.9%): [2.712, 5.705] (assumes normal distribution)


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
# Warmup Iteration   1: 7.906 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.681 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.513 ±(99.9%) 0.015 ms/op
Iteration   1: 5.480 ±(99.9%) 0.030 ms/op
Iteration   2: 5.331 ±(99.9%) 0.015 ms/op
Iteration   3: 5.194 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.335 ±(99.9%) 2.613 ms/op [Average]
  (min, avg, max) = (5.194, 5.335, 5.480), stdev = 0.143
  CI (99.9%): [2.722, 7.948] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.013 ms/op
Iteration   1: 4.277 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  13.122 ms/op
                 createUser·p0.9999: 17.482 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 4.225 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   6.975 ms/op
                 createUser·p0.999:  16.010 ms/op
                 createUser·p0.9999: 23.994 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 4.344 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 23.745 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224239
  mean =      4.281 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2750 
    [ 2.500,  5.000) = 182889 
    [ 5.000,  7.500) = 36392 
    [ 7.500, 10.000) = 1753 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     23.448 ms/op
     p(99.9990) =     24.669 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 6.147 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   4.035 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.412 ms/op
                 existUser·p0.999:  10.809 ms/op
                 existUser·p0.9999: 17.611 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 3.845 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 20.338 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 3.903 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 18.901 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242330
  mean =      3.960 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5686 
    [ 2.500,  5.000) = 214672 
    [ 5.000,  7.500) = 20493 
    [ 7.500, 10.000) = 1211 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     18.957 ms/op
     p(99.9990) =     20.832 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.303 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   2: 4.079 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  14.878 ms/op
                 getUser·p0.9999: 21.173 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 4.037 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  11.514 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237691
  mean =      4.038 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3270 
    [ 2.500,  5.000) = 210427 
    [ 5.000,  7.500) = 22845 
    [ 7.500, 10.000) = 791 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     20.273 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 7.634 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.777 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.428 ±(99.9%) 0.021 ms/op
Iteration   1: 5.362 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 5.353 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.651 ms/op
                 listUser·p0.99:   9.794 ms/op
                 listUser·p0.999:  17.143 ms/op
                 listUser·p0.9999: 19.007 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 5.346 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  19.171 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179479
  mean =      5.353 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 79714 
    [ 5.000,  7.500) = 88994 
    [ 7.500, 10.000) = 9091 
    [10.000, 12.500) = 1133 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.194 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.563 ± 9.174  ops/ms
ClientGrpc.existUser                       thrpt       3   8.266 ± 2.484  ops/ms
ClientGrpc.getUser                         thrpt       3   7.816 ± 0.702  ops/ms
ClientGrpc.listUser                        thrpt       3   5.942 ± 1.219  ops/ms
ClientGrpc.createUser                       avgt       3   4.138 ± 1.232   ms/op
ClientGrpc.existUser                        avgt       3   3.889 ± 1.287   ms/op
ClientGrpc.getUser                          avgt       3   4.209 ± 1.496   ms/op
ClientGrpc.listUser                         avgt       3   5.335 ± 2.613   ms/op
ClientGrpc.createUser                     sample  224239   4.281 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.898           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.479           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.696           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.805           ms/op
ClientGrpc.existUser                      sample  242330   3.960 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.822           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.382           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.889           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  237691   4.038 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.894           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.488           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.273           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  179479   5.353 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.427           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.733           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.298           ms/op
