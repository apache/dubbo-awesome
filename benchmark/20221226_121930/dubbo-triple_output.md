# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.171 ops/ms
# Warmup Iteration   2: 6.202 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 9.301 ops/ms
Iteration   2: 9.272 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.328 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (9.272, 9.328, 9.413), stdev = 0.074
  CI (99.9%): [7.971, 10.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 9.612 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.774 ±(99.9%) 4.359 ops/ms [Average]
  (min, avg, max) = (9.584, 9.774, 10.042), stdev = 0.239
  CI (99.9%): [5.415, 14.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 8.412 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.503 ops/ms
Iteration   3: 9.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.351 ±(99.9%) 3.710 ops/ms [Average]
  (min, avg, max) = (9.120, 9.351, 9.503), stdev = 0.203
  CI (99.9%): [5.641, 13.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.945 ops/ms
# Warmup Iteration   2: 7.704 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 7.924 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.082 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (7.924, 8.082, 8.249), stdev = 0.163
  CI (99.9%): [5.114, 11.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.155 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.006 ms/op
Iteration   1: 3.286 ±(99.9%) 0.011 ms/op
Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
Iteration   3: 3.318 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.286, 3.316, 3.345), stdev = 0.030
  CI (99.9%): [2.777, 3.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.220 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.005 ms/op
Iteration   1: 3.440 ±(99.9%) 0.007 ms/op
Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
Iteration   3: 3.269 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.321 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (3.253, 3.321, 3.440), stdev = 0.104
  CI (99.9%): [1.424, 5.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.799 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.004 ms/op
Iteration   1: 3.488 ±(99.9%) 0.007 ms/op
Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
Iteration   3: 3.455 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.449 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.402, 3.449, 3.488), stdev = 0.043
  CI (99.9%): [2.656, 4.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.037 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.009 ms/op
Iteration   1: 3.960 ±(99.9%) 0.016 ms/op
Iteration   2: 3.866 ±(99.9%) 0.014 ms/op
Iteration   3: 3.826 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.884 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.826, 3.884, 3.960), stdev = 0.069
  CI (99.9%): [2.627, 5.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.145 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.010 ms/op
Iteration   1: 3.607 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 24.056 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.414 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  20.983 ms/op
                 createUser·p0.9999: 24.367 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.374 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  22.421 ms/op
                 createUser·p0.9999: 26.920 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277072
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6903 
    [ 2.500,  5.000) = 259052 
    [ 5.000,  7.500) = 9819 
    [ 7.500, 10.000) = 828 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 168 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     18.592 ms/op
     p(99.9900) =     25.536 ms/op
     p(99.9990) =     27.631 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.747 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.087 ms/op
                 existUser·p0.9999: 20.674 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.378 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 23.596 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  21.068 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290531
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3616 
    [ 2.500,  5.000) = 282189 
    [ 5.000,  7.500) = 3963 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     27.622 ms/op
     p(99.9990) =     29.429 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.031 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.008 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  20.719 ms/op
                 getUser·p0.9999: 27.385 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 3.445 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  21.799 ms/op
                 getUser·p0.9999: 25.358 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  10.803 ms/op
                 getUser·p0.9999: 24.016 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284377
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9360 
    [ 2.500,  5.000) = 268203 
    [ 5.000,  7.500) = 5953 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.151 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.476 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.013 ms/op
Iteration   1: 4.036 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.050 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  17.764 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 4.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.235 ms/op
                 listUser·p0.999:  14.677 ms/op
                 listUser·p0.9999: 16.566 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238229
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 229908 
    [ 5.000,  7.500) = 6227 
    [ 7.500, 10.000) = 1173 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.050 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     22.059 ms/op
     p(99.9990) =     24.396 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.328 ± 1.357  ops/ms
ClientPb.existUser                       thrpt       3   9.774 ± 4.359  ops/ms
ClientPb.getUser                         thrpt       3   9.351 ± 3.710  ops/ms
ClientPb.listUser                        thrpt       3   8.082 ± 2.968  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   3.321 ± 1.897   ms/op
ClientPb.getUser                          avgt       3   3.449 ± 0.793   ms/op
ClientPb.listUser                         avgt       3   3.884 ± 1.257   ms/op
ClientPb.createUser                     sample  277072   3.462 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.030           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.592           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.536           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  290531   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.622           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  284377   3.375 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.973           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.444           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.639           ms/op
ClientPb.listUser                       sample  238229   4.028 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.050           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
