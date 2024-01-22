# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ops/ms
# Warmup Iteration   2: 12.189 ops/ms
# Warmup Iteration   3: 12.366 ops/ms
Iteration   1: 12.775 ops/ms
Iteration   2: 12.777 ops/ms
Iteration   3: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.781 ±(99.9%) 0.155 ops/ms [Average]
  (min, avg, max) = (12.775, 12.781, 12.791), stdev = 0.009
  CI (99.9%): [12.626, 12.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.042 ops/ms
# Warmup Iteration   2: 12.901 ops/ms
# Warmup Iteration   3: 12.974 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 13.138 ops/ms
Iteration   3: 12.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.030 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (12.922, 13.030, 13.138), stdev = 0.108
  CI (99.9%): [11.059, 15.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.359 ops/ms
# Warmup Iteration   2: 12.772 ops/ms
# Warmup Iteration   3: 12.936 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 12.993 ops/ms
Iteration   3: 12.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.984 ±(99.9%) 0.188 ops/ms [Average]
  (min, avg, max) = (12.973, 12.984, 12.993), stdev = 0.010
  CI (99.9%): [12.796, 13.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ops/ms
# Warmup Iteration   2: 10.640 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.665 ops/ms
Iteration   3: 10.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.725 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (10.665, 10.725, 10.792), stdev = 0.064
  CI (99.9%): [9.559, 11.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.466 ±(99.9%) 0.003 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.492 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.466, 2.492, 2.523), stdev = 0.029
  CI (99.9%): [1.965, 3.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.440, 2.448, 2.463), stdev = 0.013
  CI (99.9%): [2.216, 2.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.480, 2.496, 2.512), stdev = 0.016
  CI (99.9%): [2.206, 2.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.972, 2.979, 2.988), stdev = 0.008
  CI (99.9%): [2.828, 3.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.328 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  8.191 ms/op
                 createUser·p0.9999: 13.519 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  9.047 ms/op
                 createUser·p0.9999: 11.534 ms/op
                 createUser·p1.00:   11.846 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.056 ms/op
                 createUser·p0.9999: 10.850 ms/op
                 createUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384948
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186432 
    [ 2.500,  3.750) = 194591 
    [ 3.750,  5.000) = 3108 
    [ 5.000,  6.250) = 290 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.054 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     13.896 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.014 ms/op
                 existUser·p0.9999: 13.351 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.164 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 11.485 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392960
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 197894 
    [ 2.500,  3.750) = 192282 
    [ 3.750,  5.000) = 2076 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 154 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.650 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.354 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.048 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  9.019 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  7.054 ms/op
                 getUser·p0.9999: 11.176 ms/op
                 getUser·p1.00:   11.878 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  6.296 ms/op
                 getUser·p0.9999: 10.911 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389525
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 196271 
    [ 2.500,  3.750) = 188624 
    [ 3.750,  5.000) = 3665 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      7.638 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.794 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.440 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.659 ms/op
                 listUser·p0.9999: 11.098 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   2: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.989 ms/op
                 listUser·p0.9999: 12.079 ms/op
                 listUser·p1.00:   13.386 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.104 ms/op
                 listUser·p0.9999: 10.307 ms/op
                 listUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321197
  mean =      2.986 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 98684 
    [ 2.500,  3.750) = 185017 
    [ 3.750,  5.000) = 30399 
    [ 5.000,  6.250) = 5714 
    [ 6.250,  7.500) = 638 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.847 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     11.287 ms/op
     p(99.9990) =     12.356 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.781 ± 0.155  ops/ms
ClientPb.existUser                       thrpt       3  13.030 ± 1.971  ops/ms
ClientPb.getUser                         thrpt       3  12.984 ± 0.188  ops/ms
ClientPb.listUser                        thrpt       3  10.725 ± 1.166  ops/ms
ClientPb.createUser                       avgt       3   2.492 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.232   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.290   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.151   ms/op
ClientPb.createUser                     sample  384948   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  392960   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.762           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.844           ms/op
ClientPb.getUser                        sample  389525   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.354           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.638           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  321197   2.986 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.847           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.287           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.386           ms/op
