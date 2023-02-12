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
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 5.620 ops/ms
# Warmup Iteration   3: 7.192 ops/ms
Iteration   1: 7.389 ops/ms
Iteration   2: 7.626 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.574 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (7.389, 7.574, 7.706), stdev = 0.165
  CI (99.9%): [4.559, 10.588] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ops/ms
# Warmup Iteration   2: 6.881 ops/ms
# Warmup Iteration   3: 7.595 ops/ms
Iteration   1: 7.376 ops/ms
Iteration   2: 7.398 ops/ms
Iteration   3: 7.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.418 ±(99.9%) 1.001 ops/ms [Average]
  (min, avg, max) = (7.376, 7.418, 7.480), stdev = 0.055
  CI (99.9%): [6.417, 8.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 6.981 ops/ms
Iteration   1: 6.959 ops/ms
Iteration   2: 7.109 ops/ms
Iteration   3: 7.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.058 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (6.959, 7.058, 7.109), stdev = 0.086
  CI (99.9%): [5.488, 8.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 5.137 ops/ms
# Warmup Iteration   3: 5.528 ops/ms
Iteration   1: 5.644 ops/ms
Iteration   2: 5.740 ops/ms
Iteration   3: 5.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.670 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (5.626, 5.670, 5.740), stdev = 0.061
  CI (99.9%): [4.552, 6.788] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.768 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.748 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.634 ±(99.9%) 0.006 ms/op
Iteration   1: 4.670 ±(99.9%) 0.003 ms/op
Iteration   2: 4.568 ±(99.9%) 0.004 ms/op
Iteration   3: 4.666 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.635 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (4.568, 4.635, 4.670), stdev = 0.058
  CI (99.9%): [3.581, 5.688] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.446 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.004 ms/op
Iteration   1: 4.279 ±(99.9%) 0.003 ms/op
Iteration   2: 4.320 ±(99.9%) 0.003 ms/op
Iteration   3: 4.213 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.270 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (4.213, 4.270, 4.320), stdev = 0.054
  CI (99.9%): [3.286, 5.255] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.721 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.004 ms/op
Iteration   1: 4.711 ±(99.9%) 0.004 ms/op
Iteration   2: 4.726 ±(99.9%) 0.005 ms/op
Iteration   3: 4.444 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.627 ±(99.9%) 2.894 ms/op [Average]
  (min, avg, max) = (4.444, 4.627, 4.726), stdev = 0.159
  CI (99.9%): [1.733, 7.521] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.777 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.858 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.731 ±(99.9%) 0.021 ms/op
Iteration   1: 5.597 ±(99.9%) 0.021 ms/op
Iteration   2: 5.477 ±(99.9%) 0.023 ms/op
Iteration   3: 5.944 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.673 ±(99.9%) 4.420 ms/op [Average]
  (min, avg, max) = (5.477, 5.673, 5.944), stdev = 0.242
  CI (99.9%): [1.253, 10.093] (assumes normal distribution)


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
# Warmup Iteration   1: 7.533 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.687 ±(99.9%) 0.017 ms/op
Iteration   1: 4.561 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.881 ms/op
                 createUser·p0.99:   9.912 ms/op
                 createUser·p0.999:  16.415 ms/op
                 createUser·p0.9999: 26.966 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 4.421 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.436 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 40.406 ms/op
                 createUser·p1.00:   46.989 ms/op

Iteration   3: 4.342 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   4.166 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.694 ms/op
                 createUser·p0.999:  14.260 ms/op
                 createUser·p0.9999: 24.302 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216057
  mean =      4.439 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 171172 
    [ 5.000, 10.000) = 43292 
    [10.000, 15.000) = 1280 
    [15.000, 20.000) = 137 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      9.395 ms/op
     p(99.9000) =     18.020 ms/op
     p(99.9900) =     39.649 ms/op
     p(99.9990) =     46.575 ms/op
     p(99.9999) =     46.989 ms/op
    p(100.0000) =     46.989 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.808 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.014 ms/op
Iteration   1: 4.214 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   4.076 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   7.940 ms/op
                 existUser·p0.999:  12.454 ms/op
                 existUser·p0.9999: 27.716 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   8.135 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 17.279 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   3: 4.202 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 23.769 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228904
  mean =      4.193 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8832 
    [ 2.500,  5.000) = 181401 
    [ 5.000,  7.500) = 35232 
    [ 7.500, 10.000) = 2487 
    [10.000, 12.500) = 628 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     12.961 ms/op
     p(99.9900) =     23.931 ms/op
     p(99.9990) =     31.396 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.320 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.019 ms/op
Iteration   1: 4.636 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  15.122 ms/op
                 getUser·p0.9999: 18.688 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 4.604 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.767 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  13.846 ms/op
                 getUser·p0.9999: 34.813 ms/op
                 getUser·p1.00:   35.586 ms/op

Iteration   3: 4.520 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.434 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  14.720 ms/op
                 getUser·p0.9999: 39.900 ms/op
                 getUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209473
  mean =      4.586 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 150962 
    [ 5.000, 10.000) = 56572 
    [10.000, 15.000) = 1750 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     38.556 ms/op
     p(99.9990) =     41.865 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.986 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.455 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.964 ±(99.9%) 0.030 ms/op
Iteration   1: 6.245 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  25.526 ms/op
                 listUser·p0.9999: 33.178 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 5.882 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  26.863 ms/op
                 listUser·p0.9999: 35.070 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.105 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  31.682 ms/op
                 listUser·p0.9999: 37.112 ms/op
                 listUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 157991
  mean =      6.073 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 262 
    [ 2.500,  5.000) = 51078 
    [ 5.000,  7.500) = 76994 
    [ 7.500, 10.000) = 23239 
    [10.000, 12.500) = 5020 
    [12.500, 15.000) = 860 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      8.552 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     26.411 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     37.542 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.574 ± 3.015  ops/ms
ClientGrpc.existUser                       thrpt       3   7.418 ± 1.001  ops/ms
ClientGrpc.getUser                         thrpt       3   7.058 ± 1.570  ops/ms
ClientGrpc.listUser                        thrpt       3   5.670 ± 1.118  ops/ms
ClientGrpc.createUser                       avgt       3   4.635 ± 1.054   ms/op
ClientGrpc.existUser                        avgt       3   4.270 ± 0.984   ms/op
ClientGrpc.getUser                          avgt       3   4.627 ± 2.894   ms/op
ClientGrpc.listUser                         avgt       3   5.673 ± 4.420   ms/op
ClientGrpc.createUser                     sample  216057   4.439 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.436           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.395           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.020           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.649           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          46.989           ms/op
ClientGrpc.existUser                      sample  228904   4.193 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.938           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.217           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.931           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.161           ms/op
ClientGrpc.getUser                        sample  209473   4.586 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.434           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.964           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.824           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.814           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.647           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          38.556           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          42.402           ms/op
ClientGrpc.listUser                       sample  157991   6.073 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.774           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.206           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          26.411           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.586           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.618           ms/op
