# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.313 ops/ms
# Warmup Iteration   2: 5.767 ops/ms
# Warmup Iteration   3: 8.912 ops/ms
Iteration   1: 9.336 ops/ms
Iteration   2: 9.338 ops/ms
Iteration   3: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.280 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (9.165, 9.280, 9.338), stdev = 0.099
  CI (99.9%): [7.465, 11.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.411 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 9.672 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 10.071 ops/ms
Iteration   3: 9.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.854 ±(99.9%) 3.547 ops/ms [Average]
  (min, avg, max) = (9.695, 9.854, 10.071), stdev = 0.194
  CI (99.9%): [6.308, 13.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.376 ops/ms
# Warmup Iteration   2: 8.604 ops/ms
# Warmup Iteration   3: 9.409 ops/ms
Iteration   1: 9.141 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 9.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.391 ±(99.9%) 4.587 ops/ms [Average]
  (min, avg, max) = (9.141, 9.391, 9.644), stdev = 0.251
  CI (99.9%): [4.804, 13.978] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.878 ops/ms
# Warmup Iteration   2: 7.193 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 8.125 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.236 ±(99.9%) 1.758 ops/ms [Average]
  (min, avg, max) = (8.125, 8.236, 8.299), stdev = 0.096
  CI (99.9%): [6.478, 9.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.383 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.006 ms/op
Iteration   1: 3.506 ±(99.9%) 0.008 ms/op
Iteration   2: 3.249 ±(99.9%) 0.012 ms/op
Iteration   3: 3.283 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.346 ±(99.9%) 2.545 ms/op [Average]
  (min, avg, max) = (3.249, 3.346, 3.506), stdev = 0.139
  CI (99.9%): [0.801, 5.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.718 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.004 ms/op
Iteration   1: 3.193 ±(99.9%) 0.009 ms/op
Iteration   2: 3.228 ±(99.9%) 0.006 ms/op
Iteration   3: 3.344 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.255 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.193, 3.255, 3.344), stdev = 0.079
  CI (99.9%): [1.809, 4.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.090 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.007 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
Iteration   2: 3.525 ±(99.9%) 0.005 ms/op
Iteration   3: 3.391 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (3.391, 3.441, 3.525), stdev = 0.073
  CI (99.9%): [2.116, 4.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.436 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
Iteration   2: 3.930 ±(99.9%) 0.015 ms/op
Iteration   3: 4.085 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.992 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.930, 3.992, 4.085), stdev = 0.082
  CI (99.9%): [2.493, 5.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.011 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 23.154 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.295 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.311 ms/op
                 createUser·p0.9999: 25.372 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  18.979 ms/op
                 createUser·p0.9999: 27.555 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281996
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9216 
    [ 2.500,  5.000) = 266352 
    [ 5.000,  7.500) = 5392 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.957 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.048 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.142 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 22.430 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.369 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  20.574 ms/op
                 existUser·p0.9999: 25.969 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  17.393 ms/op
                 existUser·p0.9999: 26.086 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285485
  mean =      3.361 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16846 
    [ 2.500,  5.000) = 261600 
    [ 5.000,  7.500) = 6117 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     25.738 ms/op
     p(99.9990) =     26.566 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  19.021 ms/op
                 getUser·p0.9999: 26.393 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 3.356 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 26.272 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284914
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7034 
    [ 2.500,  5.000) = 270540 
    [ 5.000,  7.500) = 6405 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     19.514 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.497 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.104 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.013 ms/op
Iteration   1: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 23.292 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.915 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.465 ms/op
                 listUser·p0.999:  14.068 ms/op
                 listUser·p0.9999: 15.202 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   3: 3.870 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.048 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245268
  mean =      3.911 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 237896 
    [ 5.000,  7.500) = 5457 
    [ 7.500, 10.000) = 1248 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     14.479 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.811 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.280 ± 1.815  ops/ms
ClientPb.existUser                       thrpt       3   9.854 ± 3.547  ops/ms
ClientPb.getUser                         thrpt       3   9.391 ± 4.587  ops/ms
ClientPb.listUser                        thrpt       3   8.236 ± 1.758  ops/ms
ClientPb.createUser                       avgt       3   3.346 ± 2.545   ms/op
ClientPb.existUser                        avgt       3   3.255 ± 1.446   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 1.325   ms/op
ClientPb.listUser                         avgt       3   3.992 ± 1.499   ms/op
ClientPb.createUser                     sample  281996   3.404 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.182           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  285485   3.361 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.063           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.859           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  284914   3.367 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.514           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  245268   3.911 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.195           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.479           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
