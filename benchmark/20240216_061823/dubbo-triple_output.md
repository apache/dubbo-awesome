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
# Warmup Iteration   1: 5.118 ops/ms
# Warmup Iteration   2: 12.202 ops/ms
# Warmup Iteration   3: 12.362 ops/ms
Iteration   1: 12.649 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 0.195 ops/ms [Average]
  (min, avg, max) = (12.637, 12.648, 12.659), stdev = 0.011
  CI (99.9%): [12.453, 12.843] (assumes normal distribution)


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
# Warmup Iteration   1: 8.426 ops/ms
# Warmup Iteration   2: 12.612 ops/ms
# Warmup Iteration   3: 13.004 ops/ms
Iteration   1: 12.839 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 13.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.957 ±(99.9%) 2.052 ops/ms [Average]
  (min, avg, max) = (12.839, 12.957, 13.063), stdev = 0.112
  CI (99.9%): [10.905, 15.009] (assumes normal distribution)


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
# Warmup Iteration   1: 7.503 ops/ms
# Warmup Iteration   2: 12.616 ops/ms
# Warmup Iteration   3: 12.814 ops/ms
Iteration   1: 12.972 ops/ms
Iteration   2: 12.854 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.844 ±(99.9%) 2.439 ops/ms [Average]
  (min, avg, max) = (12.706, 12.844, 12.972), stdev = 0.134
  CI (99.9%): [10.405, 15.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.682 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.700 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.667 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (10.581, 10.667, 10.719), stdev = 0.075
  CI (99.9%): [9.298, 12.036] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (2.514, 2.520, 2.524), stdev = 0.005
  CI (99.9%): [2.425, 2.615] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.003 ms/op
Iteration   1: 2.474 ±(99.9%) 0.003 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (2.464, 2.470, 2.474), stdev = 0.005
  CI (99.9%): [2.377, 2.563] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.485, 2.494, 2.498), stdev = 0.008
  CI (99.9%): [2.353, 2.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.776 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 3.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (3.002, 3.007, 3.011), stdev = 0.005
  CI (99.9%): [2.923, 3.091] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  12.052 ms/op
                 createUser·p0.9999: 14.113 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 12.159 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.012 ms/op
                 createUser·p0.9999: 13.291 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381364
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184378 
    [ 2.500,  5.000) = 196241 
    [ 5.000,  7.500) = 293 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      9.906 ms/op
     p(99.9900) =     13.447 ms/op
     p(99.9990) =     14.575 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  5.419 ms/op
                 existUser·p0.9999: 14.070 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  6.285 ms/op
                 existUser·p0.9999: 13.227 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.669 ms/op
                 existUser·p0.999:  6.022 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390465
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 194765 
    [ 2.500,  3.750) = 192328 
    [ 3.750,  5.000) = 2599 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.247 ms/op
     p(99.9900) =     13.221 ms/op
     p(99.9990) =     14.536 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  11.554 ms/op
                 getUser·p0.9999: 14.505 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  9.980 ms/op
                 getUser·p0.9999: 12.373 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  8.674 ms/op
                 getUser·p0.9999: 16.057 ms/op
                 getUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378538
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 185025 
    [ 2.500,  3.750) = 188223 
    [ 3.750,  5.000) = 4087 
    [ 5.000,  6.250) = 697 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.016 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     16.817 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.870 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.289 ms/op
                 listUser·p0.9999: 12.043 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.287 ms/op
                 listUser·p0.9999: 12.861 ms/op
                 listUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317041
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 90331 
    [ 2.500,  3.750) = 186043 
    [ 3.750,  5.000) = 32977 
    [ 5.000,  6.250) = 6139 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 207 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     12.440 ms/op
     p(99.9990) =     12.987 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 0.195  ops/ms
ClientPb.existUser                       thrpt       3  12.957 ± 2.052  ops/ms
ClientPb.getUser                         thrpt       3  12.844 ± 2.439  ops/ms
ClientPb.listUser                        thrpt       3  10.667 ± 1.369  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.095   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.093   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.141   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.084   ms/op
ClientPb.createUser                     sample  381364   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.931           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.906           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.447           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.251           ms/op
ClientPb.existUser                      sample  390465   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.850           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.247           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.221           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.057           ms/op
ClientPb.getUser                        sample  378538   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.016           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.138           ms/op
ClientPb.listUser                       sample  317041   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.854           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.440           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.189           ms/op
