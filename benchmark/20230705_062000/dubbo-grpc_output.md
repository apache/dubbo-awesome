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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 5.950 ops/ms
# Warmup Iteration   3: 7.267 ops/ms
Iteration   1: 7.737 ops/ms
Iteration   2: 7.611 ops/ms
Iteration   3: 7.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.725 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (7.611, 7.725, 7.827), stdev = 0.108
  CI (99.9%): [5.747, 9.703] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.931 ops/ms
# Warmup Iteration   2: 7.756 ops/ms
# Warmup Iteration   3: 8.358 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.292 ±(99.9%) 3.352 ops/ms [Average]
  (min, avg, max) = (8.115, 8.292, 8.482), stdev = 0.184
  CI (99.9%): [4.940, 11.645] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ops/ms
# Warmup Iteration   2: 7.229 ops/ms
# Warmup Iteration   3: 7.423 ops/ms
Iteration   1: 7.454 ops/ms
Iteration   2: 7.589 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.625 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (7.454, 7.625, 7.833), stdev = 0.192
  CI (99.9%): [4.118, 11.133] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 5.484 ops/ms
# Warmup Iteration   3: 5.845 ops/ms
Iteration   1: 5.924 ops/ms
Iteration   2: 6.014 ops/ms
Iteration   3: 6.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.002 ±(99.9%) 1.336 ops/ms [Average]
  (min, avg, max) = (5.924, 6.002, 6.069), stdev = 0.073
  CI (99.9%): [4.666, 7.339] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.280 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.006 ms/op
Iteration   1: 4.133 ±(99.9%) 0.003 ms/op
Iteration   2: 4.132 ±(99.9%) 0.003 ms/op
Iteration   3: 4.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.142 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (4.132, 4.142, 4.161), stdev = 0.016
  CI (99.9%): [3.842, 4.442] (assumes normal distribution)


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
# Warmup Iteration   1: 5.638 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.005 ms/op
Iteration   1: 3.790 ±(99.9%) 0.004 ms/op
Iteration   2: 3.751 ±(99.9%) 0.003 ms/op
Iteration   3: 3.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.760 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.740, 3.760, 3.790), stdev = 0.026
  CI (99.9%): [3.284, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 6.381 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.005 ms/op
Iteration   1: 4.060 ±(99.9%) 0.003 ms/op
Iteration   2: 4.019 ±(99.9%) 0.005 ms/op
Iteration   3: 4.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.067 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (4.019, 4.067, 4.121), stdev = 0.052
  CI (99.9%): [3.126, 5.007] (assumes normal distribution)


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
# Warmup Iteration   1: 7.773 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.842 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.016 ms/op
Iteration   1: 5.352 ±(99.9%) 0.013 ms/op
Iteration   2: 5.203 ±(99.9%) 0.014 ms/op
Iteration   3: 5.265 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.274 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (5.203, 5.274, 5.352), stdev = 0.075
  CI (99.9%): [3.905, 6.642] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.203 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.013 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  11.429 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  16.147 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 4.036 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.166 ms/op
                 createUser·p0.999:  10.846 ms/op
                 createUser·p0.9999: 19.833 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234965
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5689 
    [ 2.500,  5.000) = 198692 
    [ 5.000,  7.500) = 28451 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.895 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 5.829 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  9.434 ms/op
                 existUser·p0.9999: 15.489 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   2: 3.700 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 15.986 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   3: 3.774 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  11.727 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254331
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7741 
    [ 2.500,  5.000) = 229340 
    [ 5.000,  7.500) = 15945 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     21.514 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 6.101 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.012 ms/op
Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.753 ms/op
                 getUser·p0.999:  14.888 ms/op
                 getUser·p0.9999: 26.154 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  11.442 ms/op
                 getUser·p0.9999: 19.598 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  9.957 ms/op
                 getUser·p0.9999: 19.731 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236203
  mean =      4.061 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6074 
    [ 2.500,  5.000) = 204120 
    [ 5.000,  7.500) = 24212 
    [ 7.500, 10.000) = 1310 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     25.584 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 8.227 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.606 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.222 ±(99.9%) 0.019 ms/op
Iteration   1: 5.312 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  16.711 ms/op
                 listUser·p0.9999: 20.804 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 5.363 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.482 ms/op
                 listUser·p0.999:  22.950 ms/op
                 listUser·p0.9999: 29.066 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   3: 5.365 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.331 ms/op
                 listUser·p0.999:  20.176 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179529
  mean =      5.347 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 148 
    [ 2.500,  5.000) = 86379 
    [ 5.000,  7.500) = 79928 
    [ 7.500, 10.000) = 10859 
    [10.000, 12.500) = 1526 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     19.495 ms/op
     p(99.9900) =     28.706 ms/op
     p(99.9990) =     29.784 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.725 ± 1.978  ops/ms
ClientGrpc.existUser                       thrpt       3   8.292 ± 3.352  ops/ms
ClientGrpc.getUser                         thrpt       3   7.625 ± 3.507  ops/ms
ClientGrpc.listUser                        thrpt       3   6.002 ± 1.336  ops/ms
ClientGrpc.createUser                       avgt       3   4.142 ± 0.300   ms/op
ClientGrpc.existUser                        avgt       3   3.760 ± 0.476   ms/op
ClientGrpc.getUser                          avgt       3   4.067 ± 0.941   ms/op
ClientGrpc.listUser                         avgt       3   5.274 ± 1.369   ms/op
ClientGrpc.createUser                     sample  234965   4.087 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.679           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.194           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.038           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.939           ms/op
ClientGrpc.existUser                      sample  254331   3.772 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.600           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.514           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  236203   4.061 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.090           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.071           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.086           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.468           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.584           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.345           ms/op
ClientGrpc.listUser                       sample  179529   5.347 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.355           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.495           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.706           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
