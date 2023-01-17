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
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 6.505 ops/ms
# Warmup Iteration   3: 9.343 ops/ms
Iteration   1: 9.729 ops/ms
Iteration   2: 9.685 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.808 ±(99.9%) 3.219 ops/ms [Average]
  (min, avg, max) = (9.685, 9.808, 10.010), stdev = 0.176
  CI (99.9%): [6.589, 13.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ops/ms
# Warmup Iteration   2: 9.625 ops/ms
# Warmup Iteration   3: 10.617 ops/ms
Iteration   1: 10.627 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.631 ±(99.9%) 4.226 ops/ms [Average]
  (min, avg, max) = (10.401, 10.631, 10.864), stdev = 0.232
  CI (99.9%): [6.405, 14.857] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ops/ms
# Warmup Iteration   2: 9.419 ops/ms
# Warmup Iteration   3: 9.965 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.475 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.177 ±(99.9%) 8.906 ops/ms [Average]
  (min, avg, max) = (9.614, 10.177, 10.475), stdev = 0.488
  CI (99.9%): [1.271, 19.084] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 7.859 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.754 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.625 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (8.527, 8.625, 8.754), stdev = 0.117
  CI (99.9%): [6.489, 10.760] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.087 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.003 ms/op
Iteration   1: 3.223 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.004 ms/op
Iteration   3: 3.051 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.155 ±(99.9%) 1.670 ms/op [Average]
  (min, avg, max) = (3.051, 3.155, 3.223), stdev = 0.092
  CI (99.9%): [1.485, 4.825] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.916 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.106 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.148 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.106, 3.148, 3.182), stdev = 0.038
  CI (99.9%): [2.446, 3.850] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.541 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.004 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.090 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.065, 3.090, 3.123), stdev = 0.030
  CI (99.9%): [2.545, 3.634] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.371 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.007 ms/op
Iteration   1: 3.752 ±(99.9%) 0.007 ms/op
Iteration   2: 3.712 ±(99.9%) 0.010 ms/op
Iteration   3: 3.654 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.706 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.654, 3.706, 3.752), stdev = 0.049
  CI (99.9%): [2.807, 4.606] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.801 ms/op
                 createUser·p0.999:  11.356 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.164 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  17.884 ms/op
                 createUser·p0.9999: 33.092 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  13.470 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298282
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25971 
    [ 2.500,  5.000) = 264655 
    [ 5.000,  7.500) = 6888 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     14.299 ms/op
     p(99.9900) =     31.529 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  7.880 ms/op
                 existUser·p0.9999: 25.767 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 21.581 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  10.987 ms/op
                 existUser·p0.9999: 20.099 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316315
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31157 
    [ 2.500,  5.000) = 280803 
    [ 5.000,  7.500) = 3875 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.203 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     10.245 ms/op
     p(99.9900) =     21.892 ms/op
     p(99.9990) =     26.466 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 7.516 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.010 ms/op
Iteration   1: 3.140 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  14.254 ms/op
                 getUser·p0.9999: 30.212 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  13.462 ms/op
                 getUser·p0.9999: 24.015 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.814 ms/op
                 getUser·p0.999:  10.757 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302606
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13046 
    [ 2.500,  5.000) = 282009 
    [ 5.000,  7.500) = 6606 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 8.593 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.011 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.632 ms/op
                 listUser·p0.9999: 21.984 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.683 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.518 ms/op
                 listUser·p0.999:  13.651 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.639 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255354
  mean =      3.758 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 246222 
    [ 5.000,  7.500) = 7338 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.829 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.892 ms/op
     p(99.9900) =     21.020 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.808 ± 3.219  ops/ms
ClientPb.existUser                       thrpt       3  10.631 ± 4.226  ops/ms
ClientPb.getUser                         thrpt       3  10.177 ± 8.906  ops/ms
ClientPb.listUser                        thrpt       3   8.625 ± 2.136  ops/ms
ClientPb.createUser                       avgt       3   3.155 ± 1.670   ms/op
ClientPb.existUser                        avgt       3   3.148 ± 0.702   ms/op
ClientPb.getUser                          avgt       3   3.090 ± 0.545   ms/op
ClientPb.listUser                         avgt       3   3.706 ± 0.900   ms/op
ClientPb.createUser                     sample  298282   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.529           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  316315   3.035 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.945           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.245           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.892           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197           ms/op
ClientPb.getUser                        sample  302606   3.172 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.599           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.443           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  255354   3.758 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.020           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
