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
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 5.211 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.546 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (9.465, 9.546, 9.595), stdev = 0.071
  CI (99.9%): [8.253, 10.840] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ops/ms
# Warmup Iteration   2: 9.643 ops/ms
# Warmup Iteration   3: 10.096 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.479 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (10.333, 10.479, 10.567), stdev = 0.127
  CI (99.9%): [8.158, 12.800] (assumes normal distribution)


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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 9.347 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 10.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.066 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (9.993, 10.066, 10.117), stdev = 0.065
  CI (99.9%): [8.876, 11.257] (assumes normal distribution)


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
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 8.043 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.537 ops/ms
Iteration   3: 8.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.463 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (8.348, 8.463, 8.537), stdev = 0.102
  CI (99.9%): [6.610, 10.317] (assumes normal distribution)


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
# Warmup Iteration   1: 8.013 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.003 ms/op
Iteration   1: 3.248 ±(99.9%) 0.007 ms/op
Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.143 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (3.040, 3.143, 3.248), stdev = 0.104
  CI (99.9%): [1.244, 5.043] (assumes normal distribution)


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
# Warmup Iteration   1: 7.472 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
Iteration   3: 3.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.062 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.021, 3.062, 3.086), stdev = 0.036
  CI (99.9%): [2.402, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 7.148 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.237 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.125, 3.181, 3.237), stdev = 0.056
  CI (99.9%): [2.157, 4.206] (assumes normal distribution)


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
# Warmup Iteration   1: 9.074 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.006 ms/op
Iteration   1: 3.779 ±(99.9%) 0.006 ms/op
Iteration   2: 3.722 ±(99.9%) 0.008 ms/op
Iteration   3: 3.688 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.729 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.688, 3.729, 3.779), stdev = 0.046
  CI (99.9%): [2.890, 4.568] (assumes normal distribution)


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
# Warmup Iteration   1: 8.426 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  17.627 ms/op
                 createUser·p0.9999: 25.218 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  9.952 ms/op
                 createUser·p0.9999: 19.796 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298421
  mean =      3.214 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23646 
    [ 2.500,  5.000) = 270284 
    [ 5.000,  7.500) = 3758 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     17.484 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.527 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 8.769 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.084 ms/op
                 existUser·p0.9999: 20.668 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  11.505 ms/op
                 existUser·p0.9999: 22.528 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  13.829 ms/op
                 existUser·p0.9999: 20.082 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311406
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22444 
    [ 2.500,  5.000) = 284197 
    [ 5.000,  7.500) = 3981 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.657 ms/op
     p(99.9900) =     21.688 ms/op
     p(99.9990) =     22.934 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 8.229 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 20.357 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.252 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  23.367 ms/op
                 getUser·p0.9999: 27.465 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  14.052 ms/op
                 getUser·p0.9999: 21.871 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291201
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19473 
    [ 2.500,  5.000) = 261836 
    [ 5.000,  7.500) = 8842 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     15.837 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.700 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 9.229 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.011 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 19.972 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.709 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 18.657 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.747 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 15.671 ms/op
                 listUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256565
  mean =      3.738 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 247949 
    [ 5.000,  7.500) = 6620 
    [ 7.500, 10.000) = 1246 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     19.126 ms/op
     p(99.9990) =     21.739 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.546 ± 1.294  ops/ms
ClientPb.existUser                       thrpt       3  10.479 ± 2.321  ops/ms
ClientPb.getUser                         thrpt       3  10.066 ± 1.190  ops/ms
ClientPb.listUser                        thrpt       3   8.463 ± 1.854  ops/ms
ClientPb.createUser                       avgt       3   3.143 ± 1.900   ms/op
ClientPb.existUser                        avgt       3   3.062 ± 0.660   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 1.025   ms/op
ClientPb.listUser                         avgt       3   3.729 ± 0.839   ms/op
ClientPb.createUser                     sample  298421   3.214 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.779           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.484           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.625           ms/op
ClientPb.existUser                      sample  311406   3.081 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.997           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.657           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.688           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.970           ms/op
ClientPb.getUser                        sample  291201   3.297 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.837           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.099           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.951           ms/op
ClientPb.listUser                       sample  256565   3.738 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.769           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.126           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
