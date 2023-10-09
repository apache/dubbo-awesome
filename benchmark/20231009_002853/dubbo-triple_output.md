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
# Warmup Iteration   1: 2.117 ops/ms
# Warmup Iteration   2: 5.881 ops/ms
# Warmup Iteration   3: 9.234 ops/ms
Iteration   1: 9.890 ops/ms
Iteration   2: 9.849 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.924 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (9.849, 9.924, 10.034), stdev = 0.097
  CI (99.9%): [8.149, 11.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.426 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (10.397, 10.426, 10.466), stdev = 0.036
  CI (99.9%): [9.778, 11.074] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
# Warmup Iteration   2: 9.493 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 9.932 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (9.932, 9.997, 10.043), stdev = 0.058
  CI (99.9%): [8.947, 11.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 7.660 ops/ms
# Warmup Iteration   3: 8.316 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.371 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (8.294, 8.371, 8.503), stdev = 0.115
  CI (99.9%): [6.273, 10.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.563 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.002 ms/op
Iteration   1: 3.238 ±(99.9%) 0.003 ms/op
Iteration   2: 3.166 ±(99.9%) 0.003 ms/op
Iteration   3: 3.263 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.166, 3.222, 3.263), stdev = 0.051
  CI (99.9%): [2.297, 4.148] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.254 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.150 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.127, 3.150, 3.176), stdev = 0.025
  CI (99.9%): [2.697, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 7.985 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.003 ms/op
Iteration   1: 3.248 ±(99.9%) 0.003 ms/op
Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
Iteration   3: 3.284 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.184, 3.239, 3.284), stdev = 0.050
  CI (99.9%): [2.322, 4.155] (assumes normal distribution)


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
# Warmup Iteration   1: 9.057 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.002 ms/op
Iteration   1: 3.773 ±(99.9%) 0.004 ms/op
Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
Iteration   3: 3.747 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.747, 3.773, 3.801), stdev = 0.027
  CI (99.9%): [3.276, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 7.945 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  13.873 ms/op
                 createUser·p0.9999: 23.742 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  14.559 ms/op
                 createUser·p0.9999: 23.201 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298770
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18096 
    [ 2.500,  5.000) = 276653 
    [ 5.000,  7.500) = 3283 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     17.735 ms/op
     p(99.9900) =     23.957 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 6.954 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  16.086 ms/op
                 existUser·p0.9999: 22.089 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 22.883 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299868
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14347 
    [ 2.500,  5.000) = 279322 
    [ 5.000,  7.500) = 5100 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     14.204 ms/op
     p(99.9900) =     21.825 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 9.023 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  17.518 ms/op
                 getUser·p0.9999: 19.109 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  14.493 ms/op
                 getUser·p0.9999: 21.990 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  10.802 ms/op
                 getUser·p0.9999: 20.974 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297155
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5497 
    [ 2.500,  5.000) = 286716 
    [ 5.000,  7.500) = 4240 
    [ 7.500, 10.000) = 299 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     21.440 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 8.478 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
Iteration   1: 3.818 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  15.419 ms/op
                 listUser·p0.9999: 21.145 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 14.205 ms/op
                 listUser·p1.00:   14.598 ms/op

Iteration   3: 3.729 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.206 ms/op
                 listUser·p0.9999: 14.762 ms/op
                 listUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254352
  mean =      3.773 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 248561 
    [ 5.000,  7.500) = 4558 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     19.941 ms/op
     p(99.9990) =     21.457 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.924 ± 1.775  ops/ms
ClientPb.existUser                       thrpt       3  10.426 ± 0.648  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 1.049  ops/ms
ClientPb.listUser                        thrpt       3   8.371 ± 2.098  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 0.926   ms/op
ClientPb.existUser                        avgt       3   3.150 ± 0.453   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.917   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.498   ms/op
ClientPb.createUser                     sample  298770   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.735           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.957           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.180           ms/op
ClientPb.existUser                      sample  299868   3.200 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.061           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.825           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.790           ms/op
ClientPb.getUser                        sample  297155   3.229 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.440           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  254352   3.773 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.187           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.009           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.941           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.823           ms/op
