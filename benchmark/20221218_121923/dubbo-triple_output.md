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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.579 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 9.145 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.205 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (9.145, 9.205, 9.290), stdev = 0.076
  CI (99.9%): [7.823, 10.587] (assumes normal distribution)


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
# Warmup Iteration   1: 2.880 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.616 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.771 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (9.616, 9.771, 9.910), stdev = 0.147
  CI (99.9%): [7.082, 12.460] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.422 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.340 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (9.237, 9.340, 9.422), stdev = 0.094
  CI (99.9%): [7.620, 11.060] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.802 ops/ms
# Warmup Iteration   2: 6.859 ops/ms
# Warmup Iteration   3: 7.744 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.928 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (7.732, 7.928, 8.042), stdev = 0.170
  CI (99.9%): [4.820, 11.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.938 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.007 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
Iteration   2: 3.370 ±(99.9%) 0.006 ms/op
Iteration   3: 3.528 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.370, 3.453, 3.528), stdev = 0.079
  CI (99.9%): [2.003, 4.902] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.590 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
Iteration   2: 3.323 ±(99.9%) 0.006 ms/op
Iteration   3: 3.457 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.327 ±(99.9%) 2.352 ms/op [Average]
  (min, avg, max) = (3.200, 3.327, 3.457), stdev = 0.129
  CI (99.9%): [0.975, 5.679] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.098 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
Iteration   3: 3.268 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.307 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.268, 3.307, 3.342), stdev = 0.037
  CI (99.9%): [2.623, 3.991] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.685 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.986 ±(99.9%) 0.013 ms/op
Iteration   2: 3.849 ±(99.9%) 0.015 ms/op
Iteration   3: 3.880 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.905 ±(99.9%) 1.311 ms/op [Average]
  (min, avg, max) = (3.849, 3.905, 3.986), stdev = 0.072
  CI (99.9%): [2.594, 5.216] (assumes normal distribution)


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
# Warmup Iteration   1: 9.463 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  23.492 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  24.316 ms/op
                 createUser·p0.9999: 26.582 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 3.401 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  21.666 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280653
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9545 
    [ 2.500,  5.000) = 265507 
    [ 5.000,  7.500) = 4545 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.771 ms/op
     p(99.9000) =     22.097 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.882 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.008 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  21.852 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.277 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 28.164 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.334 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  20.318 ms/op
                 existUser·p0.9999: 28.371 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287538
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18419 
    [ 2.500,  5.000) = 264027 
    [ 5.000,  7.500) = 4141 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     20.331 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     29.598 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.519 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.013 ms/op
Iteration   1: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  21.725 ms/op
                 getUser·p0.9999: 25.282 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.367 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 29.721 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   3: 3.674 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.096 ms/op
                 getUser·p0.999:  14.240 ms/op
                 getUser·p0.9999: 35.930 ms/op
                 getUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274956
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4105 
    [ 2.500,  5.000) = 260825 
    [ 5.000,  7.500) = 8723 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.271 ms/op
     p(99.9900) =     34.374 ms/op
     p(99.9990) =     37.241 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.808 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.012 ms/op
Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  23.652 ms/op
                 listUser·p0.9999: 30.015 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 18.865 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.539 ms/op
                 listUser·p0.999:  16.100 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240641
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 232511 
    [ 5.000,  7.500) = 5806 
    [ 7.500, 10.000) = 1466 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     28.340 ms/op
     p(99.9990) =     30.100 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.205 ± 1.382  ops/ms
ClientPb.existUser                       thrpt       3   9.771 ± 2.689  ops/ms
ClientPb.getUser                         thrpt       3   9.340 ± 1.720  ops/ms
ClientPb.listUser                        thrpt       3   7.928 ± 3.108  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 1.450   ms/op
ClientPb.existUser                        avgt       3   3.327 ± 2.352   ms/op
ClientPb.getUser                          avgt       3   3.307 ± 0.684   ms/op
ClientPb.listUser                         avgt       3   3.905 ± 1.311   ms/op
ClientPb.createUser                     sample  280653   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.771           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.097           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.082           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  287538   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.115           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015           ms/op
ClientPb.getUser                        sample  274956   3.488 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.374           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.814           ms/op
ClientPb.listUser                       sample  240641   3.986 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.212           ms/op
