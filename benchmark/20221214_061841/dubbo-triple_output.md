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
# Warmup Iteration   1: 2.393 ops/ms
# Warmup Iteration   2: 5.226 ops/ms
# Warmup Iteration   3: 9.006 ops/ms
Iteration   1: 9.603 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 10.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.912 ±(99.9%) 6.488 ops/ms [Average]
  (min, avg, max) = (9.603, 9.912, 10.301), stdev = 0.356
  CI (99.9%): [3.424, 16.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.530 ops/ms
# Warmup Iteration   2: 8.956 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 4.396 ops/ms [Average]
  (min, avg, max) = (9.877, 10.128, 10.358), stdev = 0.241
  CI (99.9%): [5.733, 14.524] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ops/ms
# Warmup Iteration   2: 8.989 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.928 ±(99.9%) 4.101 ops/ms [Average]
  (min, avg, max) = (9.684, 9.928, 10.127), stdev = 0.225
  CI (99.9%): [5.827, 14.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 8.176 ops/ms
# Warmup Iteration   3: 8.541 ops/ms
Iteration   1: 8.594 ops/ms
Iteration   2: 8.485 ops/ms
Iteration   3: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.611 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (8.485, 8.611, 8.755), stdev = 0.136
  CI (99.9%): [6.135, 11.087] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.003 ms/op
Iteration   1: 3.213 ±(99.9%) 0.005 ms/op
Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
Iteration   3: 3.177 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.210 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.177, 3.210, 3.240), stdev = 0.032
  CI (99.9%): [2.634, 3.786] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.005 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.982, 3.005, 3.027), stdev = 0.022
  CI (99.9%): [2.596, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 8.083 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.006 ms/op
Iteration   1: 3.298 ±(99.9%) 0.003 ms/op
Iteration   2: 3.252 ±(99.9%) 0.005 ms/op
Iteration   3: 3.137 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.229 ±(99.9%) 1.518 ms/op [Average]
  (min, avg, max) = (3.137, 3.229, 3.298), stdev = 0.083
  CI (99.9%): [1.711, 4.747] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.835 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.007 ms/op
Iteration   1: 3.681 ±(99.9%) 0.010 ms/op
Iteration   2: 3.645 ±(99.9%) 0.009 ms/op
Iteration   3: 3.712 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.680 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.645, 3.680, 3.712), stdev = 0.033
  CI (99.9%): [3.069, 4.290] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.110 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.285 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.168 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  18.190 ms/op
                 createUser·p0.9999: 26.486 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  14.890 ms/op
                 createUser·p0.9999: 23.657 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298934
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23735 
    [ 2.500,  5.000) = 268213 
    [ 5.000,  7.500) = 5766 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     15.828 ms/op
     p(99.9900) =     26.290 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 6.701 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  12.878 ms/op
                 existUser·p0.9999: 21.816 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.807 ms/op
                 existUser·p0.9999: 22.486 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309568
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31420 
    [ 2.500,  5.000) = 273506 
    [ 5.000,  7.500) = 3889 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     12.852 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 8.178 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.010 ms/op
Iteration   1: 3.104 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   6.077 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 22.699 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  13.813 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  10.858 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305112
  mean =      3.145 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11492 
    [ 2.500,  5.000) = 288549 
    [ 5.000,  7.500) = 3980 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.760 ms/op
     p(99.9900) =     21.921 ms/op
     p(99.9990) =     22.903 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 8.344 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.967 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 19.526 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.740 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 14.942 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.732 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.534 ms/op
                 listUser·p0.9999: 17.316 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256675
  mean =      3.738 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 249519 
    [ 5.000,  7.500) = 5526 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     18.546 ms/op
     p(99.9990) =     19.896 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.912 ± 6.488  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 4.396  ops/ms
ClientPb.getUser                         thrpt       3   9.928 ± 4.101  ops/ms
ClientPb.listUser                        thrpt       3   8.611 ± 2.476  ops/ms
ClientPb.createUser                       avgt       3   3.210 ± 0.576   ms/op
ClientPb.existUser                        avgt       3   3.005 ± 0.409   ms/op
ClientPb.getUser                          avgt       3   3.229 ± 1.518   ms/op
ClientPb.listUser                         avgt       3   3.680 ± 0.610   ms/op
ClientPb.createUser                     sample  298934   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.976           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.828           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.290           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  309568   3.100 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.852           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.823           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.872           ms/op
ClientPb.getUser                        sample  305112   3.145 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.035           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.478           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.921           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.265           ms/op
ClientPb.listUser                       sample  256675   3.738 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.546           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.185           ms/op
