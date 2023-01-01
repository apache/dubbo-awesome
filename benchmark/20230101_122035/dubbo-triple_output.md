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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 5.469 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 10.023 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.909 ±(99.9%) 5.263 ops/ms [Average]
  (min, avg, max) = (9.581, 9.909, 10.123), stdev = 0.288
  CI (99.9%): [4.646, 15.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 9.409 ops/ms
# Warmup Iteration   3: 10.016 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.564 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (10.512, 10.564, 10.602), stdev = 0.046
  CI (99.9%): [9.717, 11.412] (assumes normal distribution)


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
# Warmup Iteration   1: 3.515 ops/ms
# Warmup Iteration   2: 8.937 ops/ms
# Warmup Iteration   3: 9.516 ops/ms
Iteration   1: 10.353 ops/ms
Iteration   2: 10.329 ops/ms
Iteration   3: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.187 ±(99.9%) 4.873 ops/ms [Average]
  (min, avg, max) = (9.879, 10.187, 10.353), stdev = 0.267
  CI (99.9%): [5.314, 15.061] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 7.778 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.354 ±(99.9%) 9.513 ops/ms [Average]
  (min, avg, max) = (7.778, 8.354, 8.794), stdev = 0.521
  CI (99.9%): [≈ 0, 17.867] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.005 ms/op
Iteration   1: 3.223 ±(99.9%) 0.005 ms/op
Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
Iteration   3: 3.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.216 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (3.211, 3.216, 3.223), stdev = 0.007
  CI (99.9%): [3.092, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.004 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.998 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.979, 2.998, 3.020), stdev = 0.020
  CI (99.9%): [2.627, 3.369] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.949 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.006 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
Iteration   3: 3.233 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.181, 3.204, 3.233), stdev = 0.027
  CI (99.9%): [2.716, 3.692] (assumes normal distribution)


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
# Warmup Iteration   1: 8.673 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.006 ms/op
Iteration   1: 3.749 ±(99.9%) 0.007 ms/op
Iteration   2: 3.760 ±(99.9%) 0.007 ms/op
Iteration   3: 3.616 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.709 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.616, 3.709, 3.760), stdev = 0.080
  CI (99.9%): [2.245, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 8.485 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  8.832 ms/op
                 createUser·p0.9999: 19.564 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.142 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  20.062 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 21.388 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304548
  mean =      3.152 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18103 
    [ 2.500,  5.000) = 280579 
    [ 5.000,  7.500) = 4985 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 195 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.689 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 7.712 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.008 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  11.913 ms/op
                 existUser·p0.9999: 23.944 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 23.159 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.143 ms/op
                 existUser·p0.9999: 17.823 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315129
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17407 
    [ 2.500,  5.000) = 292254 
    [ 5.000,  7.500) = 4824 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =      9.564 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 6.963 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.009 ms/op
Iteration   1: 3.103 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 22.885 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  8.781 ms/op
                 getUser·p0.9999: 24.756 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  9.205 ms/op
                 getUser·p0.9999: 22.118 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300845
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15126 
    [ 2.500,  5.000) = 278019 
    [ 5.000,  7.500) = 6885 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     17.546 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 8.759 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.013 ms/op
Iteration   1: 3.724 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.967 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 14.894 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.482 ms/op
                 listUser·p0.9999: 16.302 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257832
  mean =      3.720 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 249978 
    [ 5.000,  7.500) = 5532 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     19.649 ms/op
     p(99.9990) =     21.996 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.909 ± 5.263  ops/ms
ClientPb.existUser                       thrpt       3  10.564 ± 0.847  ops/ms
ClientPb.getUser                         thrpt       3  10.187 ± 4.873  ops/ms
ClientPb.listUser                        thrpt       3   8.354 ± 9.513  ops/ms
ClientPb.createUser                       avgt       3   3.216 ± 0.123   ms/op
ClientPb.existUser                        avgt       3   2.998 ± 0.371   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 0.488   ms/op
ClientPb.listUser                         avgt       3   3.709 ± 1.463   ms/op
ClientPb.createUser                     sample  304548   3.152 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  315129   3.045 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.642           ms/op
ClientPb.getUser                        sample  300845   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.957           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.546           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.658           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  257832   3.720 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.053           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.649           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
