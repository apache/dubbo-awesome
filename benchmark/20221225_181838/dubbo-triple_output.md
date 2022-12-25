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
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 9.470 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.018 ±(99.9%) 2.645 ops/ms [Average]
  (min, avg, max) = (9.852, 10.018, 10.114), stdev = 0.145
  CI (99.9%): [7.374, 12.663] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 9.695 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.748 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.558 ±(99.9%) 4.681 ops/ms [Average]
  (min, avg, max) = (10.266, 10.558, 10.748), stdev = 0.257
  CI (99.9%): [5.877, 15.239] (assumes normal distribution)


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
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 9.147 ops/ms
# Warmup Iteration   3: 9.775 ops/ms
Iteration   1: 10.198 ops/ms
Iteration   2: 10.226 ops/ms
Iteration   3: 10.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.180 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (10.116, 10.180, 10.226), stdev = 0.057
  CI (99.9%): [9.140, 11.220] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.663 ops/ms
Iteration   2: 8.466 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.464 ±(99.9%) 3.637 ops/ms [Average]
  (min, avg, max) = (8.264, 8.464, 8.663), stdev = 0.199
  CI (99.9%): [4.827, 12.101] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.349 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.005 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
Iteration   2: 3.143 ±(99.9%) 0.009 ms/op
Iteration   3: 3.193 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.125 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (3.038, 3.125, 3.193), stdev = 0.079
  CI (99.9%): [1.680, 4.569] (assumes normal distribution)


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
# Warmup Iteration   1: 6.627 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.004 ms/op
Iteration   1: 3.064 ±(99.9%) 0.005 ms/op
Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
Iteration   3: 2.953 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.023 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (2.953, 3.023, 3.064), stdev = 0.061
  CI (99.9%): [1.910, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 7.037 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
Iteration   3: 3.245 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.081, 3.175, 3.245), stdev = 0.085
  CI (99.9%): [1.627, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 9.253 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.002 ms/op
Iteration   1: 3.664 ±(99.9%) 0.009 ms/op
Iteration   2: 3.641 ±(99.9%) 0.012 ms/op
Iteration   3: 3.648 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.651 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.641, 3.651, 3.664), stdev = 0.012
  CI (99.9%): [3.435, 3.867] (assumes normal distribution)


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
# Warmup Iteration   1: 7.724 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
Iteration   1: 3.091 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  18.565 ms/op
                 createUser·p0.9999: 20.589 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 3.122 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  14.461 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  10.371 ms/op
                 createUser·p0.9999: 19.356 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308710
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15795 
    [ 2.500,  5.000) = 288872 
    [ 5.000,  7.500) = 3316 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     14.062 ms/op
     p(99.9900) =     20.648 ms/op
     p(99.9990) =     22.014 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 7.130 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 23.160 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.162 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 25.883 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  14.201 ms/op
                 existUser·p0.9999: 22.270 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305333
  mean =      3.141 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26586 
    [ 2.500,  5.000) = 271425 
    [ 5.000,  7.500) = 6411 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.970 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.790 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 7.357 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
Iteration   1: 3.098 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  15.905 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  19.477 ms/op
                 getUser·p0.9999: 25.365 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  13.320 ms/op
                 getUser·p0.9999: 18.027 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303285
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9710 
    [ 2.500,  5.000) = 287249 
    [ 5.000,  7.500) = 5284 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.282 ms/op
     p(99.9900) =     22.261 ms/op
     p(99.9990) =     26.410 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.016 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.834 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 16.133 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.530 ms/op
                 listUser·p0.999:  14.300 ms/op
                 listUser·p0.9999: 18.126 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250686
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 76 
    [ 2.500,  3.750) = 164845 
    [ 3.750,  5.000) = 71909 
    [ 5.000,  6.250) = 8488 
    [ 6.250,  7.500) = 3477 
    [ 7.500,  8.750) = 932 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 197 
    [13.750, 15.000) = 121 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     13.719 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     19.317 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.018 ± 2.645  ops/ms
ClientPb.existUser                       thrpt       3  10.558 ± 4.681  ops/ms
ClientPb.getUser                         thrpt       3  10.180 ± 1.040  ops/ms
ClientPb.listUser                        thrpt       3   8.464 ± 3.637  ops/ms
ClientPb.createUser                       avgt       3   3.125 ± 1.444   ms/op
ClientPb.existUser                        avgt       3   3.023 ± 1.112   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 1.548   ms/op
ClientPb.listUser                         avgt       3   3.651 ± 0.216   ms/op
ClientPb.createUser                     sample  308710   3.106 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.062           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.905           ms/op
ClientPb.existUser                      sample  305333   3.141 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.970           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.882           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  303285   3.163 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.648           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  250686   3.828 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.458           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.719           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.088           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.399           ms/op
