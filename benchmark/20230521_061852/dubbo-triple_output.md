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
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 5.356 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 9.422 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.352 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (9.217, 9.352, 9.422), stdev = 0.118
  CI (99.9%): [7.209, 11.496] (assumes normal distribution)


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
# Warmup Iteration   1: 3.207 ops/ms
# Warmup Iteration   2: 8.286 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.934 ops/ms
Iteration   3: 10.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.993 ±(99.9%) 3.672 ops/ms [Average]
  (min, avg, max) = (9.828, 9.993, 10.218), stdev = 0.201
  CI (99.9%): [6.321, 13.666] (assumes normal distribution)


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
# Warmup Iteration   1: 3.187 ops/ms
# Warmup Iteration   2: 8.492 ops/ms
# Warmup Iteration   3: 9.160 ops/ms
Iteration   1: 9.437 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.596 ±(99.9%) 2.598 ops/ms [Average]
  (min, avg, max) = (9.437, 9.596, 9.711), stdev = 0.142
  CI (99.9%): [6.998, 12.194] (assumes normal distribution)


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
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 7.262 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.218 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (8.167, 8.218, 8.251), stdev = 0.045
  CI (99.9%): [7.402, 9.033] (assumes normal distribution)


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
# Warmup Iteration   1: 9.748 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.007 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
Iteration   2: 3.339 ±(99.9%) 0.005 ms/op
Iteration   3: 3.292 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.307 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.290, 3.307, 3.339), stdev = 0.028
  CI (99.9%): [2.795, 3.819] (assumes normal distribution)


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
# Warmup Iteration   1: 9.050 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.007 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
Iteration   2: 3.263 ±(99.9%) 0.010 ms/op
Iteration   3: 3.297 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.240, 3.267, 3.297), stdev = 0.029
  CI (99.9%): [2.740, 3.793] (assumes normal distribution)


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
# Warmup Iteration   1: 9.322 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
Iteration   2: 3.317 ±(99.9%) 0.006 ms/op
Iteration   3: 3.431 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.358 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.317, 3.358, 3.431), stdev = 0.063
  CI (99.9%): [2.206, 4.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.094 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 3.891 ±(99.9%) 0.014 ms/op
Iteration   2: 3.953 ±(99.9%) 0.010 ms/op
Iteration   3: 4.132 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.992 ±(99.9%) 2.285 ms/op [Average]
  (min, avg, max) = (3.891, 3.992, 4.132), stdev = 0.125
  CI (99.9%): [1.707, 6.277] (assumes normal distribution)


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
# Warmup Iteration   1: 10.699 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.013 ms/op
Iteration   1: 3.478 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.082 ms/op
                 createUser·p0.999:  20.388 ms/op
                 createUser·p0.9999: 23.521 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.405 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.302 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  17.305 ms/op
                 createUser·p0.9999: 24.837 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278768
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18513 
    [ 2.500,  5.000) = 253803 
    [ 5.000,  7.500) = 5292 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.753 ms/op
     p(99.9000) =     17.571 ms/op
     p(99.9900) =     24.486 ms/op
     p(99.9990) =     25.685 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.833 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.010 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  13.724 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 3.289 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  29.622 ms/op
                 existUser·p0.9999: 96.516 ms/op
                 existUser·p1.00:   103.023 ms/op

Iteration   3: 3.866 ±(99.9%) 0.063 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   21.758 ms/op
                 existUser·p0.999:  80.125 ms/op
                 existUser·p0.9999: 98.793 ms/op
                 existUser·p1.00:   108.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278133
  mean =      3.449 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 276767 
    [ 12.500,  25.000) = 480 
    [ 25.000,  37.500) = 179 
    [ 37.500,  50.000) = 174 
    [ 50.000,  62.500) = 175 
    [ 62.500,  75.000) = 189 
    [ 75.000,  87.500) = 125 
    [ 87.500, 100.000) = 33 
    [100.000, 112.500) = 11 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     66.847 ms/op
     p(99.9900) =     96.411 ms/op
     p(99.9990) =    106.955 ms/op
     p(99.9999) =    108.003 ms/op
    p(100.0000) =    108.003 ms/op


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
# Warmup Iteration   1: 12.753 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.096 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.072 ms/op
Iteration   1: 4.073 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   22.676 ms/op
                 getUser·p0.999:  91.226 ms/op
                 getUser·p0.9999: 110.126 ms/op
                 getUser·p1.00:   125.305 ms/op

Iteration   2: 4.109 ±(99.9%) 0.074 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   26.806 ms/op
                 getUser·p0.999:  89.915 ms/op
                 getUser·p0.9999: 103.524 ms/op
                 getUser·p1.00:   122.552 ms/op

Iteration   3: 4.053 ±(99.9%) 0.069 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   29.426 ms/op
                 getUser·p0.999:  86.114 ms/op
                 getUser·p0.9999: 98.740 ms/op
                 getUser·p1.00:   112.067 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235395
  mean =      4.078 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 232293 
    [ 12.500,  25.000) = 676 
    [ 25.000,  37.500) = 452 
    [ 37.500,  50.000) = 481 
    [ 50.000,  62.500) = 455 
    [ 62.500,  75.000) = 401 
    [ 75.000,  87.500) = 358 
    [ 87.500, 100.000) = 225 
    [100.000, 112.500) = 45 
    [112.500, 125.000) = 8 
    [125.000, 137.500) = 1 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =     26.903 ms/op
     p(99.9000) =     89.260 ms/op
     p(99.9900) =    102.760 ms/op
     p(99.9990) =    122.552 ms/op
     p(99.9999) =    125.305 ms/op
    p(100.0000) =    125.305 ms/op


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
# Warmup Iteration   1: 14.185 ±(99.9%) 0.368 ms/op
# Warmup Iteration   2: 5.769 ±(99.9%) 0.117 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.022 ms/op
Iteration   1: 4.045 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  21.053 ms/op
                 listUser·p0.9999: 73.269 ms/op
                 listUser·p1.00:   74.318 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.518 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 3.918 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 16.040 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240533
  mean =      3.990 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 231680 
    [ 5.000, 10.000) = 7995 
    [10.000, 15.000) = 502 
    [15.000, 20.000) = 264 
    [20.000, 25.000) = 38 
    [25.000, 30.000) = 13 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 5 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     17.284 ms/op
     p(99.9900) =     56.056 ms/op
     p(99.9990) =     74.187 ms/op
     p(99.9999) =     74.318 ms/op
    p(100.0000) =     74.318 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3    9.352 ± 2.144  ops/ms
ClientPb.existUser                       thrpt       3    9.993 ± 3.672  ops/ms
ClientPb.getUser                         thrpt       3    9.596 ± 2.598  ops/ms
ClientPb.listUser                        thrpt       3    8.218 ± 0.816  ops/ms
ClientPb.createUser                       avgt       3    3.307 ± 0.512   ms/op
ClientPb.existUser                        avgt       3    3.267 ± 0.527   ms/op
ClientPb.getUser                          avgt       3    3.358 ± 1.152   ms/op
ClientPb.listUser                         avgt       3    3.992 ± 2.285   ms/op
ClientPb.createUser                     sample  278768    3.442 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample            1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample            3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample            3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample            4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample            5.753           ms/op
ClientPb.createUser:createUser·p0.999   sample           17.571           ms/op
ClientPb.createUser:createUser·p0.9999  sample           24.486           ms/op
ClientPb.createUser:createUser·p1.00    sample           26.182           ms/op
ClientPb.existUser                      sample  278133    3.449 ± 0.021   ms/op
ClientPb.existUser:existUser·p0.00      sample            1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample            3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample            3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample            3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample            6.308           ms/op
ClientPb.existUser:existUser·p0.999     sample           66.847           ms/op
ClientPb.existUser:existUser·p0.9999    sample           96.411           ms/op
ClientPb.existUser:existUser·p1.00      sample          108.003           ms/op
ClientPb.getUser                        sample  235395    4.078 ± 0.042   ms/op
ClientPb.getUser:getUser·p0.00          sample            1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample            3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample            4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample            4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           26.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           89.260           ms/op
ClientPb.getUser:getUser·p0.9999        sample          102.760           ms/op
ClientPb.getUser:getUser·p1.00          sample          125.305           ms/op
ClientPb.listUser                       sample  240533    3.990 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample            1.450           ms/op
ClientPb.listUser:listUser·p0.50        sample            3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample            4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample            4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample            7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample           17.284           ms/op
ClientPb.listUser:listUser·p0.9999      sample           56.056           ms/op
ClientPb.listUser:listUser·p1.00        sample           74.318           ms/op
