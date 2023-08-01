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
# Warmup Iteration   1: 2.202 ops/ms
# Warmup Iteration   2: 5.595 ops/ms
# Warmup Iteration   3: 6.727 ops/ms
Iteration   1: 7.126 ops/ms
Iteration   2: 7.175 ops/ms
Iteration   3: 7.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.141 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (7.122, 7.141, 7.175), stdev = 0.029
  CI (99.9%): [6.607, 7.675] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 6.628 ops/ms
# Warmup Iteration   3: 6.756 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.503 ops/ms
Iteration   3: 7.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.509 ±(99.9%) 2.544 ops/ms [Average]
  (min, avg, max) = (7.372, 7.509, 7.651), stdev = 0.139
  CI (99.9%): [4.965, 10.053] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ops/ms
# Warmup Iteration   2: 6.433 ops/ms
# Warmup Iteration   3: 6.657 ops/ms
Iteration   1: 6.578 ops/ms
Iteration   2: 6.923 ops/ms
Iteration   3: 6.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.831 ±(99.9%) 4.040 ops/ms [Average]
  (min, avg, max) = (6.578, 6.831, 6.991), stdev = 0.221
  CI (99.9%): [2.791, 10.870] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ops/ms
# Warmup Iteration   2: 4.848 ops/ms
# Warmup Iteration   3: 5.430 ops/ms
Iteration   1: 5.710 ops/ms
Iteration   2: 5.717 ops/ms
Iteration   3: 5.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.668 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (5.577, 5.668, 5.717), stdev = 0.079
  CI (99.9%): [4.233, 7.103] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.966 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.019 ms/op
Iteration   1: 4.470 ±(99.9%) 0.004 ms/op
Iteration   2: 4.466 ±(99.9%) 0.003 ms/op
Iteration   3: 4.561 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.499 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (4.466, 4.499, 4.561), stdev = 0.054
  CI (99.9%): [3.519, 5.479] (assumes normal distribution)


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
# Warmup Iteration   1: 7.170 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.004 ms/op
Iteration   1: 4.055 ±(99.9%) 0.003 ms/op
Iteration   2: 4.033 ±(99.9%) 0.003 ms/op
Iteration   3: 4.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.043 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (4.033, 4.043, 4.055), stdev = 0.012
  CI (99.9%): [3.832, 4.253] (assumes normal distribution)


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
# Warmup Iteration   1: 6.706 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.012 ms/op
Iteration   1: 4.286 ±(99.9%) 0.006 ms/op
Iteration   2: 4.408 ±(99.9%) 0.004 ms/op
Iteration   3: 4.329 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.341 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (4.286, 4.341, 4.408), stdev = 0.062
  CI (99.9%): [3.214, 5.468] (assumes normal distribution)


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
# Warmup Iteration   1: 8.337 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.161 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.639 ±(99.9%) 0.018 ms/op
Iteration   1: 5.753 ±(99.9%) 0.014 ms/op
Iteration   2: 5.718 ±(99.9%) 0.014 ms/op
Iteration   3: 5.645 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.705 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (5.645, 5.705, 5.753), stdev = 0.055
  CI (99.9%): [4.696, 6.715] (assumes normal distribution)


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
# Warmup Iteration   1: 7.565 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.014 ms/op
Iteration   1: 4.507 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.326 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 17.626 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 4.411 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.057 ms/op
                 createUser·p0.999:  13.530 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 4.523 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.484 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   8.402 ms/op
                 createUser·p0.999:  11.770 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214231
  mean =      4.480 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4049 
    [ 2.500,  5.000) = 158300 
    [ 5.000,  7.500) = 48582 
    [ 7.500, 10.000) = 2626 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     13.407 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.934 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 6.072 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.013 ms/op
Iteration   1: 4.107 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.165 ms/op
                 existUser·p0.999:  11.345 ms/op
                 existUser·p0.9999: 17.840 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 4.226 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  10.725 ms/op
                 existUser·p0.9999: 20.246 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 4.124 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  10.205 ms/op
                 existUser·p0.9999: 21.668 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231097
  mean =      4.151 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4910 
    [ 2.500,  5.000) = 198057 
    [ 5.000,  7.500) = 26394 
    [ 7.500, 10.000) = 1392 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     10.763 ms/op
     p(99.9900) =     21.026 ms/op
     p(99.9990) =     21.891 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 7.506 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.013 ms/op
Iteration   1: 4.475 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  13.005 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   2: 4.464 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.975 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  12.796 ms/op
                 getUser·p0.9999: 17.192 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 4.440 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.741 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215310
  mean =      4.460 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2726 
    [ 2.500,  5.000) = 169660 
    [ 5.000,  7.500) = 40435 
    [ 7.500, 10.000) = 1937 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     23.934 ms/op
     p(99.9990) =     24.889 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 8.800 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.327 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.626 ±(99.9%) 0.022 ms/op
Iteration   1: 5.441 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 23.703 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 5.526 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   7.938 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  20.979 ms/op
                 listUser·p0.9999: 22.460 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 5.599 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 29.928 ms/op
                 listUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173800
  mean =      5.521 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 122 
    [ 2.500,  5.000) = 64115 
    [ 5.000,  7.500) = 96259 
    [ 7.500, 10.000) = 11343 
    [10.000, 12.500) = 1365 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     19.798 ms/op
     p(99.9900) =     29.217 ms/op
     p(99.9990) =     31.260 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.141 ± 0.534  ops/ms
ClientGrpc.existUser                       thrpt       3   7.509 ± 2.544  ops/ms
ClientGrpc.getUser                         thrpt       3   6.831 ± 4.040  ops/ms
ClientGrpc.listUser                        thrpt       3   5.668 ± 1.435  ops/ms
ClientGrpc.createUser                       avgt       3   4.499 ± 0.980   ms/op
ClientGrpc.existUser                        avgt       3   4.043 ± 0.211   ms/op
ClientGrpc.getUser                          avgt       3   4.341 ± 1.127   ms/op
ClientGrpc.listUser                         avgt       3   5.705 ± 1.009   ms/op
ClientGrpc.createUser                     sample  214231   4.480 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.484           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.407           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.480           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  231097   4.151 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.763           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.026           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  215310   4.460 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.717           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.934           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.068           ms/op
ClientGrpc.listUser                       sample  173800   5.521 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.483           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.798           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.719           ms/op
