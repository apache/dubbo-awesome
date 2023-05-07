# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.141 ops/ms
# Warmup Iteration   2: 2.383 ops/ms
# Warmup Iteration   3: 5.226 ops/ms
Iteration   1: 5.515 ops/ms
Iteration   2: 5.711 ops/ms
Iteration   3: 6.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.823 ±(99.9%) 6.871 ops/ms [Average]
  (min, avg, max) = (5.515, 5.823, 6.243), stdev = 0.377
  CI (99.9%): [≈ 0, 12.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.718 ops/ms
# Warmup Iteration   2: 4.957 ops/ms
# Warmup Iteration   3: 6.243 ops/ms
Iteration   1: 6.137 ops/ms
Iteration   2: 6.458 ops/ms
Iteration   3: 6.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.348 ±(99.9%) 3.330 ops/ms [Average]
  (min, avg, max) = (6.137, 6.348, 6.458), stdev = 0.183
  CI (99.9%): [3.018, 9.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.468 ops/ms
# Warmup Iteration   2: 4.534 ops/ms
# Warmup Iteration   3: 5.760 ops/ms
Iteration   1: 5.417 ops/ms
Iteration   2: 5.747 ops/ms
Iteration   3: 6.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.737 ±(99.9%) 5.762 ops/ms [Average]
  (min, avg, max) = (5.417, 5.737, 6.048), stdev = 0.316
  CI (99.9%): [≈ 0, 11.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.611 ops/ms
# Warmup Iteration   2: 4.021 ops/ms
# Warmup Iteration   3: 5.063 ops/ms
Iteration   1: 4.737 ops/ms
Iteration   2: 5.064 ops/ms
Iteration   3: 5.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.042 ±(99.9%) 5.377 ops/ms [Average]
  (min, avg, max) = (4.737, 5.042, 5.325), stdev = 0.295
  CI (99.9%): [≈ 0, 10.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.462 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.833 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.010 ms/op
Iteration   1: 5.361 ±(99.9%) 0.024 ms/op
Iteration   2: 5.181 ±(99.9%) 0.018 ms/op
Iteration   3: 5.384 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.309 ±(99.9%) 2.029 ms/op [Average]
  (min, avg, max) = (5.181, 5.309, 5.384), stdev = 0.111
  CI (99.9%): [3.280, 7.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.174 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.409 ±(99.9%) 0.008 ms/op
Iteration   1: 5.291 ±(99.9%) 0.012 ms/op
Iteration   2: 5.145 ±(99.9%) 0.012 ms/op
Iteration   3: 5.157 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.198 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (5.145, 5.198, 5.291), stdev = 0.081
  CI (99.9%): [3.720, 6.676] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.448 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.420 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.635 ±(99.9%) 0.011 ms/op
Iteration   1: 5.678 ±(99.9%) 0.010 ms/op
Iteration   2: 5.266 ±(99.9%) 0.015 ms/op
Iteration   3: 5.293 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.413 ±(99.9%) 4.207 ms/op [Average]
  (min, avg, max) = (5.266, 5.413, 5.678), stdev = 0.231
  CI (99.9%): [1.206, 9.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.996 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.891 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.316 ±(99.9%) 0.016 ms/op
Iteration   1: 6.169 ±(99.9%) 0.014 ms/op
Iteration   2: 6.291 ±(99.9%) 0.014 ms/op
Iteration   3: 6.092 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.184 ±(99.9%) 1.830 ms/op [Average]
  (min, avg, max) = (6.092, 6.184, 6.291), stdev = 0.100
  CI (99.9%): [4.353, 8.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.825 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.116 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.875 ±(99.9%) 0.026 ms/op
Iteration   1: 5.584 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  15.661 ms/op
                 createUser·p0.9999: 29.616 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 5.379 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  26.183 ms/op
                 createUser·p0.9999: 29.631 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 5.329 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  26.873 ms/op
                 createUser·p0.9999: 30.606 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176551
  mean =      5.429 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 78602 
    [ 5.000,  7.500) = 87837 
    [ 7.500, 10.000) = 7888 
    [10.000, 12.500) = 1595 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     31.128 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.752 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.019 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.329 ±(99.9%) 0.019 ms/op
Iteration   1: 5.184 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   9.519 ms/op
                 existUser·p0.999:  22.512 ms/op
                 existUser·p0.9999: 26.733 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   2: 5.031 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   9.044 ms/op
                 existUser·p0.999:  15.466 ms/op
                 existUser·p0.9999: 28.103 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 5.464 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   8.208 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  28.312 ms/op
                 existUser·p0.9999: 38.341 ms/op
                 existUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183768
  mean =      5.220 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 97137 
    [ 5.000, 10.000) = 84748 
    [10.000, 15.000) = 1502 
    [15.000, 20.000) = 164 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 130 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     23.621 ms/op
     p(99.9900) =     33.726 ms/op
     p(99.9990) =     40.670 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.635 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.760 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.627 ±(99.9%) 0.019 ms/op
Iteration   1: 5.664 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.045 ms/op
                 getUser·p0.95:   8.200 ms/op
                 getUser·p0.99:   12.519 ms/op
                 getUser·p0.999:  20.923 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 5.503 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.748 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   8.187 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  25.023 ms/op
                 getUser·p0.9999: 29.995 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 5.502 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.744 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  17.880 ms/op
                 getUser·p0.9999: 26.351 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172752
  mean =      5.555 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 63687 
    [ 5.000,  7.500) = 96824 
    [ 7.500, 10.000) = 9158 
    [10.000, 12.500) = 1873 
    [12.500, 15.000) = 597 
    [15.000, 17.500) = 332 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     19.611 ms/op
     p(99.9900) =     29.523 ms/op
     p(99.9990) =     30.310 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.499 ±(99.9%) 0.414 ms/op
# Warmup Iteration   2: 7.577 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.387 ±(99.9%) 0.025 ms/op
Iteration   1: 5.951 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.600 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 22.323 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 6.117 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   3.322 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   10.524 ms/op
                 listUser·p0.999:  24.417 ms/op
                 listUser·p0.9999: 28.887 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   3: 6.256 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   12.414 ms/op
                 listUser·p0.999:  21.389 ms/op
                 listUser·p0.9999: 28.297 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157131
  mean =      6.105 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 10713 
    [ 5.000,  7.500) = 132431 
    [ 7.500, 10.000) = 10469 
    [10.000, 12.500) = 2401 
    [12.500, 15.000) = 518 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     21.459 ms/op
     p(99.9900) =     28.354 ms/op
     p(99.9990) =     30.044 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.823 ± 6.871  ops/ms
ClientPb.existUser                       thrpt       3   6.348 ± 3.330  ops/ms
ClientPb.getUser                         thrpt       3   5.737 ± 5.762  ops/ms
ClientPb.listUser                        thrpt       3   5.042 ± 5.377  ops/ms
ClientPb.createUser                       avgt       3   5.309 ± 2.029   ms/op
ClientPb.existUser                        avgt       3   5.198 ± 1.478   ms/op
ClientPb.getUser                          avgt       3   5.413 ± 4.207   ms/op
ClientPb.listUser                         avgt       3   6.184 ± 1.830   ms/op
ClientPb.createUser                     sample  176551   5.429 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.302           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.692           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.371           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.087           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  183768   5.220 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.953           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.348           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.726           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.878           ms/op
ClientPb.getUser                        sample  172752   5.555 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.009           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.110           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.321           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  157131   6.105 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.400           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.459           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
