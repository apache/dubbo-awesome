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
# Warmup Iteration   1: 4.489 ops/ms
# Warmup Iteration   2: 11.948 ops/ms
# Warmup Iteration   3: 12.485 ops/ms
Iteration   1: 12.681 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.677 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (12.645, 12.677, 12.706), stdev = 0.030
  CI (99.9%): [12.125, 13.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.523 ops/ms
# Warmup Iteration   2: 12.961 ops/ms
# Warmup Iteration   3: 13.243 ops/ms
Iteration   1: 13.175 ops/ms
Iteration   2: 13.271 ops/ms
Iteration   3: 13.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.166 ±(99.9%) 2.003 ops/ms [Average]
  (min, avg, max) = (13.052, 13.166, 13.271), stdev = 0.110
  CI (99.9%): [11.164, 15.169] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.261 ops/ms
# Warmup Iteration   2: 12.711 ops/ms
# Warmup Iteration   3: 12.900 ops/ms
Iteration   1: 12.907 ops/ms
Iteration   2: 12.805 ops/ms
Iteration   3: 12.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.868 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (12.805, 12.868, 12.907), stdev = 0.055
  CI (99.9%): [11.861, 13.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.122 ops/ms
# Warmup Iteration   2: 10.724 ops/ms
# Warmup Iteration   3: 10.797 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.827 ops/ms
Iteration   3: 10.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.881 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (10.827, 10.881, 10.911), stdev = 0.046
  CI (99.9%): [10.037, 11.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.003 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (2.494, 2.527, 2.566), stdev = 0.036
  CI (99.9%): [1.869, 3.185] (assumes normal distribution)


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.444, 2.454, 2.465), stdev = 0.011
  CI (99.9%): [2.258, 2.649] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.484, 2.496, 2.505), stdev = 0.011
  CI (99.9%): [2.298, 2.695] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.959, 2.979, 2.992), stdev = 0.018
  CI (99.9%): [2.652, 3.307] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.321 ms/op
                 createUser·p0.9999: 13.320 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 11.341 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  7.455 ms/op
                 createUser·p0.9999: 10.484 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381287
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 184398 
    [ 2.500,  3.750) = 193214 
    [ 3.750,  5.000) = 2934 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.070 ms/op
     p(99.9900) =     12.941 ms/op
     p(99.9990) =     13.821 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.861 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.456 ms/op
                 existUser·p0.9999: 10.525 ms/op
                 existUser·p1.00:   10.846 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.728 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 12.026 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395599
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 199991 
    [ 2.500,  3.750) = 192606 
    [ 3.750,  5.000) = 2281 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      7.117 ms/op
     p(99.9900) =     13.147 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  6.349 ms/op
                 getUser·p0.9999: 13.470 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.841 ms/op
                 getUser·p0.999:  7.349 ms/op
                 getUser·p0.9999: 13.792 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.679 ms/op
                 getUser·p0.999:  6.165 ms/op
                 getUser·p0.9999: 10.369 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393614
  mean =      2.437 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 200184 
    [ 2.500,  3.750) = 189350 
    [ 3.750,  5.000) = 2807 
    [ 5.000,  6.250) = 757 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.215 ms/op
     p(99.9900) =     13.297 ms/op
     p(99.9990) =     14.125 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.009 ms/op
Iteration   1: 2.943 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.987 ms/op
                 listUser·p0.9999: 11.667 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324296
  mean =      2.958 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 102115 
    [ 2.500,  3.750) = 186282 
    [ 3.750,  5.000) = 28640 
    [ 5.000,  6.250) = 5733 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 303 
    [ 8.750, 10.000) = 189 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      8.957 ms/op
     p(99.9900) =     11.200 ms/op
     p(99.9990) =     13.263 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.677 ± 0.552  ops/ms
ClientPb.existUser                       thrpt       3  13.166 ± 2.003  ops/ms
ClientPb.getUser                         thrpt       3  12.868 ± 1.007  ops/ms
ClientPb.listUser                        thrpt       3  10.881 ± 0.844  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.658   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.196   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.328   ms/op
ClientPb.createUser                     sample  381287   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.016           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.070           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.941           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  395599   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.792           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.117           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  393614   2.437 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.684           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  324296   2.958 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.957           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
