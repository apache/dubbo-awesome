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
# Warmup Iteration   1: 2.446 ops/ms
# Warmup Iteration   2: 6.269 ops/ms
# Warmup Iteration   3: 9.351 ops/ms
Iteration   1: 9.838 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.705 ±(99.9%) 8.314 ops/ms [Average]
  (min, avg, max) = (9.197, 9.705, 10.079), stdev = 0.456
  CI (99.9%): [1.391, 18.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
# Warmup Iteration   2: 9.143 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.359 ±(99.9%) 6.324 ops/ms [Average]
  (min, avg, max) = (10.062, 10.359, 10.740), stdev = 0.347
  CI (99.9%): [4.035, 16.682] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 8.909 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 9.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.926 ±(99.9%) 2.358 ops/ms [Average]
  (min, avg, max) = (9.822, 9.926, 10.071), stdev = 0.129
  CI (99.9%): [7.568, 12.284] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 7.303 ops/ms
# Warmup Iteration   3: 8.284 ops/ms
Iteration   1: 8.656 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.521 ±(99.9%) 2.505 ops/ms [Average]
  (min, avg, max) = (8.382, 8.521, 8.656), stdev = 0.137
  CI (99.9%): [6.016, 11.026] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.519 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.005 ms/op
Iteration   1: 3.403 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.006 ms/op
Iteration   3: 3.306 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.322 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.258, 3.322, 3.403), stdev = 0.074
  CI (99.9%): [1.977, 4.668] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.404 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.271 ±(99.9%) 0.005 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.156 ±(99.9%) 2.165 ms/op [Average]
  (min, avg, max) = (3.034, 3.156, 3.271), stdev = 0.119
  CI (99.9%): [0.991, 5.322] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.534 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.007 ms/op
Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
Iteration   3: 3.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.141 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.100, 3.141, 3.199), stdev = 0.052
  CI (99.9%): [2.197, 4.085] (assumes normal distribution)


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
# Warmup Iteration   1: 8.600 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.004 ms/op
Iteration   1: 3.677 ±(99.9%) 0.009 ms/op
Iteration   2: 3.835 ±(99.9%) 0.006 ms/op
Iteration   3: 3.827 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.779 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (3.677, 3.779, 3.835), stdev = 0.089
  CI (99.9%): [2.155, 5.404] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.764 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
Iteration   1: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 20.863 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  13.551 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  14.844 ms/op
                 createUser·p0.9999: 19.268 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300589
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23039 
    [ 2.500,  5.000) = 271722 
    [ 5.000,  7.500) = 4884 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     21.659 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 7.792 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.279 ms/op
                 existUser·p0.999:  7.488 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  14.519 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.109 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  8.967 ms/op
                 existUser·p0.9999: 24.042 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304650
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19920 
    [ 2.500,  5.000) = 279614 
    [ 5.000,  7.500) = 4514 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.867 ms/op
     p(99.9900) =     23.399 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 7.305 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.010 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.266 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 20.562 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.820 ms/op
                 getUser·p0.999:  16.405 ms/op
                 getUser·p0.9999: 23.834 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  18.453 ms/op
                 getUser·p0.9999: 30.913 ms/op
                 getUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287635
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17819 
    [ 2.500,  5.000) = 262762 
    [ 5.000,  7.500) = 5955 
    [ 7.500, 10.000) = 726 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     18.124 ms/op
     p(99.9900) =     29.368 ms/op
     p(99.9990) =     31.166 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 8.772 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.013 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.992 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 15.599 ms/op
                 listUser·p1.00:   16.548 ms/op

Iteration   3: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.339 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253669
  mean =      3.782 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 245500 
    [ 5.000,  7.500) = 6096 
    [ 7.500, 10.000) = 1206 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.132 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.705 ± 8.314  ops/ms
ClientPb.existUser                       thrpt       3  10.359 ± 6.324  ops/ms
ClientPb.getUser                         thrpt       3   9.926 ± 2.358  ops/ms
ClientPb.listUser                        thrpt       3   8.521 ± 2.505  ops/ms
ClientPb.createUser                       avgt       3   3.322 ± 1.346   ms/op
ClientPb.existUser                        avgt       3   3.156 ± 2.165   ms/op
ClientPb.getUser                          avgt       3   3.141 ± 0.944   ms/op
ClientPb.listUser                         avgt       3   3.779 ± 1.624   ms/op
ClientPb.createUser                     sample  300589   3.191 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.795           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.987           ms/op
ClientPb.existUser                      sample  304650   3.149 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.867           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.399           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  287635   3.334 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.031           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.124           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.368           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.621           ms/op
ClientPb.listUser                       sample  253669   3.782 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
