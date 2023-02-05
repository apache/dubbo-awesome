# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.420 ops/ms
# Warmup Iteration   2: 6.128 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 9.536 ops/ms
Iteration   2: 9.874 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.668 ±(99.9%) 3.300 ops/ms [Average]
  (min, avg, max) = (9.536, 9.668, 9.874), stdev = 0.181
  CI (99.9%): [6.368, 12.967] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ops/ms
# Warmup Iteration   2: 9.359 ops/ms
# Warmup Iteration   3: 9.797 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 9.699 ops/ms
Iteration   3: 10.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.104 ±(99.9%) 6.448 ops/ms [Average]
  (min, avg, max) = (9.699, 10.104, 10.350), stdev = 0.353
  CI (99.9%): [3.656, 16.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ops/ms
# Warmup Iteration   2: 9.338 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.265 ops/ms
Iteration   2: 9.933 ops/ms
Iteration   3: 9.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 4.769 ops/ms [Average]
  (min, avg, max) = (9.749, 9.983, 10.265), stdev = 0.261
  CI (99.9%): [5.214, 14.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ops/ms
# Warmup Iteration   2: 7.721 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.475 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.502 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (8.475, 8.502, 8.540), stdev = 0.034
  CI (99.9%): [7.886, 9.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.193 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.005 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.077 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.152 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.077, 3.152, 3.222), stdev = 0.073
  CI (99.9%): [1.822, 4.481] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.260 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.004 ms/op
Iteration   1: 3.140 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.001 ms/op
Iteration   3: 3.130 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.089 ±(99.9%) 1.458 ms/op [Average]
  (min, avg, max) = (2.997, 3.089, 3.140), stdev = 0.080
  CI (99.9%): [1.631, 4.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.194 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.003 ms/op
Iteration   1: 3.230 ±(99.9%) 0.006 ms/op
Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.175, 3.208, 3.230), stdev = 0.029
  CI (99.9%): [2.676, 3.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.692 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.005 ms/op
Iteration   1: 3.871 ±(99.9%) 0.005 ms/op
Iteration   2: 3.644 ±(99.9%) 0.010 ms/op
Iteration   3: 3.643 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 2.392 ms/op [Average]
  (min, avg, max) = (3.643, 3.719, 3.871), stdev = 0.131
  CI (99.9%): [1.327, 6.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.049 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.009 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  17.189 ms/op
                 createUser·p0.9999: 23.430 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  8.347 ms/op
                 createUser·p0.9999: 24.776 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.271 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.912 ms/op
                 createUser·p0.999:  15.057 ms/op
                 createUser·p0.9999: 18.489 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296332
  mean =      3.239 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14457 
    [ 2.500,  5.000) = 276957 
    [ 5.000,  7.500) = 4106 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     15.477 ms/op
     p(99.9900) =     23.671 ms/op
     p(99.9990) =     25.531 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.008 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  12.920 ms/op
                 existUser·p0.9999: 21.196 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  7.944 ms/op
                 existUser·p0.9999: 23.116 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.294 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  10.065 ms/op
                 existUser·p0.9999: 29.909 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309266
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22060 
    [ 2.500,  5.000) = 280099 
    [ 5.000,  7.500) = 6321 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.038 ms/op
     p(99.9900) =     28.576 ms/op
     p(99.9990) =     30.361 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.388 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  14.337 ms/op
                 getUser·p0.9999: 26.261 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.645 ms/op
                 getUser·p0.999:  10.596 ms/op
                 getUser·p0.9999: 23.654 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.561 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 26.639 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299651
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11011 
    [ 2.500,  5.000) = 281280 
    [ 5.000,  7.500) = 6285 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     13.463 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.393 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.011 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.054 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 21.417 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 3.788 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 16.262 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   7.098 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 14.932 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254280
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 244674 
    [ 5.000,  7.500) = 7433 
    [ 7.500, 10.000) = 1467 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.233 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.668 ± 3.300  ops/ms
ClientPb.existUser                       thrpt       3  10.104 ± 6.448  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 4.769  ops/ms
ClientPb.listUser                        thrpt       3   8.502 ± 0.617  ops/ms
ClientPb.createUser                       avgt       3   3.152 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   3.089 ± 1.458   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 0.532   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 2.392   ms/op
ClientPb.createUser                     sample  296332   3.239 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.477           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.671           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  309266   3.103 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.038           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  299651   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.463           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.492           ms/op
ClientPb.listUser                       sample  254280   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.364           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.233           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
