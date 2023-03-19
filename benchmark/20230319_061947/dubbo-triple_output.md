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
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 6.398 ops/ms
# Warmup Iteration   3: 9.048 ops/ms
Iteration   1: 9.824 ops/ms
Iteration   2: 10.236 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.055 ±(99.9%) 3.836 ops/ms [Average]
  (min, avg, max) = (9.824, 10.055, 10.236), stdev = 0.210
  CI (99.9%): [6.218, 13.891] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ops/ms
# Warmup Iteration   2: 9.365 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.586 ±(99.9%) 4.052 ops/ms [Average]
  (min, avg, max) = (10.363, 10.586, 10.807), stdev = 0.222
  CI (99.9%): [6.535, 14.638] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ops/ms
# Warmup Iteration   2: 9.462 ops/ms
# Warmup Iteration   3: 9.761 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.655 ±(99.9%) 16.803 ops/ms [Average]
  (min, avg, max) = (8.592, 9.655, 10.213), stdev = 0.921
  CI (99.9%): [≈ 0, 26.458] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ops/ms
# Warmup Iteration   2: 6.752 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.429 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.253 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (8.163, 8.253, 8.429), stdev = 0.152
  CI (99.9%): [5.471, 11.034] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.983 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.005 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
Iteration   3: 3.297 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.346 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.297, 3.346, 3.389), stdev = 0.046
  CI (99.9%): [2.502, 4.189] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.261 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.004 ms/op
Iteration   1: 3.181 ±(99.9%) 0.006 ms/op
Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
Iteration   3: 3.109 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.126 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.088, 3.126, 3.181), stdev = 0.049
  CI (99.9%): [2.230, 4.022] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.682 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.004 ms/op
Iteration   1: 3.376 ±(99.9%) 0.002 ms/op
Iteration   2: 3.270 ±(99.9%) 0.003 ms/op
Iteration   3: 3.391 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.345 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.270, 3.345, 3.391), stdev = 0.066
  CI (99.9%): [2.144, 4.547] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.616 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.009 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
Iteration   2: 3.825 ±(99.9%) 0.008 ms/op
Iteration   3: 3.897 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.825, 3.887, 3.940), stdev = 0.058
  CI (99.9%): [2.830, 4.945] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.165 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
Iteration   1: 3.695 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   6.263 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  19.808 ms/op
                 createUser·p0.9999: 24.446 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  20.647 ms/op
                 createUser·p0.9999: 24.000 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  19.561 ms/op
                 createUser·p0.9999: 24.271 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277761
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12698 
    [ 2.500,  5.000) = 254540 
    [ 5.000,  7.500) = 7975 
    [ 7.500, 10.000) = 2016 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.075 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.877 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.283 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  12.549 ms/op
                 existUser·p0.9999: 22.665 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   6.858 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 23.870 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293632
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9940 
    [ 2.500,  5.000) = 277151 
    [ 5.000,  7.500) = 4864 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.687 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.105 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.997 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.010 ms/op
Iteration   1: 3.349 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  18.975 ms/op
                 getUser·p0.9999: 21.543 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  19.698 ms/op
                 getUser·p0.9999: 23.347 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.663 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 27.036 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277914
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12908 
    [ 2.500,  5.000) = 254915 
    [ 5.000,  7.500) = 8425 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     15.353 ms/op
     p(99.9900) =     25.474 ms/op
     p(99.9990) =     27.543 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 13.896 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.635 ±(99.9%) 0.016 ms/op
Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  19.322 ms/op
                 listUser·p0.9999: 21.990 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251178
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 243336 
    [ 5.000,  7.500) = 5718 
    [ 7.500, 10.000) = 1373 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     17.033 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     23.099 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3  10.055 ±  3.836  ops/ms
ClientPb.existUser                       thrpt       3  10.586 ±  4.052  ops/ms
ClientPb.getUser                         thrpt       3   9.655 ± 16.803  ops/ms
ClientPb.listUser                        thrpt       3   8.253 ±  2.782  ops/ms
ClientPb.createUser                       avgt       3   3.346 ±  0.843   ms/op
ClientPb.existUser                        avgt       3   3.126 ±  0.896   ms/op
ClientPb.getUser                          avgt       3   3.345 ±  1.202   ms/op
ClientPb.listUser                         avgt       3   3.887 ±  1.058   ms/op
ClientPb.createUser                     sample  277761   3.454 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.422            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.759            ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.150            ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428            ms/op
ClientPb.existUser                      sample  293632   3.269 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.636            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.687            ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.839            ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166            ms/op
ClientPb.getUser                        sample  277914   3.451 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.362            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685            ms/op
ClientPb.getUser:getUser·p0.999         sample          15.353            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.474            ms/op
ClientPb.getUser:getUser·p1.00          sample          27.918            ms/op
ClientPb.listUser                       sample  251178   3.821 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234            ms/op
ClientPb.listUser:listUser·p0.999       sample          17.033            ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.660            ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364            ms/op
