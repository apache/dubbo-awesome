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
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 12.004 ops/ms
# Warmup Iteration   3: 12.515 ops/ms
Iteration   1: 12.877 ops/ms
Iteration   2: 12.717 ops/ms
Iteration   3: 12.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.787 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (12.717, 12.787, 12.877), stdev = 0.082
  CI (99.9%): [11.292, 14.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.333 ops/ms
# Warmup Iteration   2: 13.421 ops/ms
# Warmup Iteration   3: 13.436 ops/ms
Iteration   1: 13.451 ops/ms
Iteration   2: 13.423 ops/ms
Iteration   3: 13.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.423 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (13.394, 13.423, 13.451), stdev = 0.028
  CI (99.9%): [12.906, 13.940] (assumes normal distribution)


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
# Warmup Iteration   1: 8.025 ops/ms
# Warmup Iteration   2: 12.847 ops/ms
# Warmup Iteration   3: 13.174 ops/ms
Iteration   1: 13.079 ops/ms
Iteration   2: 13.174 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.174 ±(99.9%) 1.746 ops/ms [Average]
  (min, avg, max) = (13.079, 13.174, 13.270), stdev = 0.096
  CI (99.9%): [11.429, 14.920] (assumes normal distribution)


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
# Warmup Iteration   1: 6.663 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 10.805 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.771 ±(99.9%) 0.650 ops/ms [Average]
  (min, avg, max) = (10.734, 10.771, 10.805), stdev = 0.036
  CI (99.9%): [10.121, 11.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.472, 2.488, 2.511), stdev = 0.021
  CI (99.9%): [2.111, 2.865] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.003 ms/op
Iteration   1: 2.378 ±(99.9%) 0.003 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.401 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.378, 2.401, 2.423), stdev = 0.022
  CI (99.9%): [1.996, 2.807] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.427 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.411, 2.427, 2.437), stdev = 0.015
  CI (99.9%): [2.162, 2.693] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 2.968 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.968, 2.980, 3.000), stdev = 0.017
  CI (99.9%): [2.662, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.826 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  8.931 ms/op
                 createUser·p0.9999: 12.541 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  8.434 ms/op
                 createUser·p0.9999: 11.170 ms/op
                 createUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381346
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 183118 
    [ 2.500,  3.750) = 193745 
    [ 3.750,  5.000) = 3642 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.448 ms/op
     p(99.9900) =     13.412 ms/op
     p(99.9990) =     18.913 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.748 ms/op
                 existUser·p0.9999: 13.732 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.480 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   3: 2.386 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.026 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.632 ms/op
                 existUser·p0.9999: 11.446 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401325
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 207559 
    [ 2.500,  3.750) = 190812 
    [ 3.750,  5.000) = 2169 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     14.237 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  6.800 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  7.880 ms/op
                 getUser·p0.9999: 13.244 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  6.506 ms/op
                 getUser·p0.9999: 11.683 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387573
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 193290 
    [ 2.500,  3.750) = 190002 
    [ 3.750,  5.000) = 3068 
    [ 5.000,  6.250) = 729 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.708 ms/op
     p(99.9900) =     13.275 ms/op
     p(99.9990) =     14.291 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.100 ms/op
                 listUser·p0.9999: 10.890 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.891 ms/op
                 listUser·p0.9999: 11.523 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.757 ms/op
                 listUser·p0.9999: 11.383 ms/op
                 listUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320727
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 94103 
    [ 2.500,  3.750) = 187995 
    [ 3.750,  5.000) = 31850 
    [ 5.000,  6.250) = 5310 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     12.406 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.787 ± 1.495  ops/ms
ClientPb.existUser                       thrpt       3  13.423 ± 0.517  ops/ms
ClientPb.getUser                         thrpt       3  13.174 ± 1.746  ops/ms
ClientPb.listUser                        thrpt       3  10.771 ± 0.650  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.377   ms/op
ClientPb.existUser                        avgt       3   2.401 ± 0.405   ms/op
ClientPb.getUser                          avgt       3   2.427 ± 0.265   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.318   ms/op
ClientPb.createUser                     sample  381346   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.821           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.448           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.890           ms/op
ClientPb.existUser                      sample  401325   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.636           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.714           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  387573   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.865           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.708           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.254           ms/op
ClientPb.listUser                       sample  320727   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.747           ms/op
