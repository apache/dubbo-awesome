# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 6.421 ops/ms
# Warmup Iteration   3: 9.395 ops/ms
Iteration   1: 9.511 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 9.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.710 ±(99.9%) 3.276 ops/ms [Average]
  (min, avg, max) = (9.511, 9.710, 9.860), stdev = 0.180
  CI (99.9%): [6.434, 12.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ops/ms
# Warmup Iteration   2: 9.125 ops/ms
# Warmup Iteration   3: 10.316 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.326 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.414 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (10.282, 10.414, 10.635), stdev = 0.193
  CI (99.9%): [6.902, 13.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 8.390 ops/ms
# Warmup Iteration   3: 9.893 ops/ms
Iteration   1: 10.236 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 9.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.110 ±(99.9%) 3.485 ops/ms [Average]
  (min, avg, max) = (9.890, 10.110, 10.236), stdev = 0.191
  CI (99.9%): [6.625, 13.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ops/ms
# Warmup Iteration   2: 7.489 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.629 ops/ms
Iteration   2: 8.610 ops/ms
Iteration   3: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.576 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (8.488, 8.576, 8.629), stdev = 0.077
  CI (99.9%): [7.175, 9.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.005 ms/op
Iteration   1: 3.223 ±(99.9%) 0.003 ms/op
Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
Iteration   3: 3.129 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.129, 3.197, 3.238), stdev = 0.059
  CI (99.9%): [2.123, 4.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.604 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.007 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
Iteration   3: 3.039 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.032 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (2.970, 3.032, 3.089), stdev = 0.060
  CI (99.9%): [1.939, 4.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.186 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.005 ms/op
Iteration   1: 3.274 ±(99.9%) 0.004 ms/op
Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.151 ±(99.9%) 2.081 ms/op [Average]
  (min, avg, max) = (3.049, 3.151, 3.274), stdev = 0.114
  CI (99.9%): [1.070, 5.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.005 ms/op
Iteration   1: 3.696 ±(99.9%) 0.010 ms/op
Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
Iteration   3: 3.803 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.797 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.696, 3.797, 3.893), stdev = 0.099
  CI (99.9%): [1.993, 5.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.755 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  17.661 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.185 ms/op
                 createUser·p0.9999: 26.466 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 20.146 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305970
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15417 
    [ 2.500,  5.000) = 286563 
    [ 5.000,  7.500) = 3201 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     17.893 ms/op
     p(99.9900) =     24.635 ms/op
     p(99.9990) =     26.999 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.869 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 27.368 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 21.624 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308918
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17955 
    [ 2.500,  5.000) = 286537 
    [ 5.000,  7.500) = 3705 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     10.798 ms/op
     p(99.9900) =     25.570 ms/op
     p(99.9990) =     28.178 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.769 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  16.639 ms/op
                 getUser·p0.9999: 20.189 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  10.629 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  13.500 ms/op
                 getUser·p0.9999: 18.700 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303418
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13210 
    [ 2.500,  5.000) = 283041 
    [ 5.000,  7.500) = 6346 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     15.345 ms/op
     p(99.9900) =     20.698 ms/op
     p(99.9990) =     22.248 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.657 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.010 ms/op
Iteration   1: 3.727 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  16.189 ms/op
                 listUser·p0.9999: 21.411 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.013 ms/op
                 listUser·p0.9999: 14.823 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.680 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 14.418 ms/op
                 listUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259287
  mean =      3.703 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 251140 
    [ 5.000,  7.500) = 6176 
    [ 7.500, 10.000) = 1149 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.233 ms/op
     p(99.9900) =     18.467 ms/op
     p(99.9990) =     21.798 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.710 ± 3.276  ops/ms
ClientPb.existUser                       thrpt       3  10.414 ± 3.512  ops/ms
ClientPb.getUser                         thrpt       3  10.110 ± 3.485  ops/ms
ClientPb.listUser                        thrpt       3   8.576 ± 1.401  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 1.074   ms/op
ClientPb.existUser                        avgt       3   3.032 ± 1.093   ms/op
ClientPb.getUser                          avgt       3   3.151 ± 2.081   ms/op
ClientPb.listUser                         avgt       3   3.797 ± 1.805   ms/op
ClientPb.createUser                     sample  305970   3.135 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.893           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.635           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.197           ms/op
ClientPb.existUser                      sample  308918   3.105 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.798           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.570           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  303418   3.163 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.176           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.345           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.698           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.134           ms/op
ClientPb.listUser                       sample  259287   3.703 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.233           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.467           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.889           ms/op
