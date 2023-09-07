# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.356 ops/ms
# Warmup Iteration   2: 5.821 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.301 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.448 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (9.301, 9.448, 9.544), stdev = 0.130
  CI (99.9%): [7.085, 11.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.531 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.425 ±(99.9%) 3.472 ops/ms [Average]
  (min, avg, max) = (10.205, 10.425, 10.537), stdev = 0.190
  CI (99.9%): [6.953, 13.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.249 ops/ms
Iteration   1: 9.541 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 9.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.615 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (9.537, 9.615, 9.768), stdev = 0.132
  CI (99.9%): [7.201, 12.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.899 ops/ms
# Warmup Iteration   2: 7.565 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 8.551 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.316 ±(99.9%) 3.712 ops/ms [Average]
  (min, avg, max) = (8.196, 8.316, 8.551), stdev = 0.203
  CI (99.9%): [4.604, 12.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.189 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.007 ms/op
Iteration   1: 3.398 ±(99.9%) 0.008 ms/op
Iteration   2: 3.243 ±(99.9%) 0.006 ms/op
Iteration   3: 3.423 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.355 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.243, 3.355, 3.423), stdev = 0.097
  CI (99.9%): [1.579, 5.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.806 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.005 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
Iteration   3: 3.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (3.219, 3.226, 3.236), stdev = 0.009
  CI (99.9%): [3.064, 3.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.463 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.002 ms/op
Iteration   1: 3.337 ±(99.9%) 0.003 ms/op
Iteration   2: 3.207 ±(99.9%) 0.004 ms/op
Iteration   3: 3.270 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.207, 3.271, 3.337), stdev = 0.065
  CI (99.9%): [2.084, 4.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.052 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.006 ms/op
Iteration   1: 3.898 ±(99.9%) 0.006 ms/op
Iteration   2: 3.823 ±(99.9%) 0.005 ms/op
Iteration   3: 3.719 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.813 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (3.719, 3.813, 3.898), stdev = 0.090
  CI (99.9%): [2.178, 5.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.780 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.010 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  17.243 ms/op
                 createUser·p0.9999: 20.384 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.933 ms/op
                 createUser·p0.999:  15.398 ms/op
                 createUser·p0.9999: 21.364 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  13.004 ms/op
                 createUser·p0.9999: 21.661 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299346
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17282 
    [ 2.500,  5.000) = 275566 
    [ 5.000,  7.500) = 5190 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     22.022 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.309 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 21.154 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.930 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  12.383 ms/op
                 existUser·p0.9999: 21.573 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299901
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20765 
    [ 2.500,  5.000) = 272295 
    [ 5.000,  7.500) = 5651 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     11.774 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.150 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.823 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.010 ms/op
Iteration   1: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  17.400 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  12.869 ms/op
                 getUser·p0.9999: 19.988 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  13.295 ms/op
                 getUser·p0.9999: 20.965 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298465
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11504 
    [ 2.500,  5.000) = 278934 
    [ 5.000,  7.500) = 6519 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     16.393 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.944 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.015 ms/op
Iteration   1: 3.928 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  15.150 ms/op
                 listUser·p0.9999: 30.745 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   8.205 ms/op
                 listUser·p0.999:  13.449 ms/op
                 listUser·p0.9999: 15.286 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   3: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 17.778 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250212
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 237796 
    [ 5.000,  7.500) = 9583 
    [ 7.500, 10.000) = 1904 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.967 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.087 ms/op
     p(99.9900) =     29.276 ms/op
     p(99.9990) =     31.146 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.448 ± 2.363  ops/ms
ClientPb.existUser                       thrpt       3  10.425 ± 3.472  ops/ms
ClientPb.getUser                         thrpt       3   9.615 ± 2.414  ops/ms
ClientPb.listUser                        thrpt       3   8.316 ± 3.712  ops/ms
ClientPb.createUser                       avgt       3   3.355 ± 1.776   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 1.187   ms/op
ClientPb.listUser                         avgt       3   3.813 ± 1.636   ms/op
ClientPb.createUser                     sample  299346   3.204 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.729           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.544           ms/op
ClientPb.existUser                      sample  299901   3.200 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  298465   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.393           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.413           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.774           ms/op
ClientPb.listUser                       sample  250212   3.836 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.612           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.967           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.087           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.276           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.392           ms/op
