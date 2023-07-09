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
# Warmup Iteration   1: 2.499 ops/ms
# Warmup Iteration   2: 6.153 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.761 ops/ms
Iteration   2: 9.719 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.711 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (9.652, 9.711, 9.761), stdev = 0.055
  CI (99.9%): [8.712, 10.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ops/ms
# Warmup Iteration   2: 9.850 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.483 ±(99.9%) 2.298 ops/ms [Average]
  (min, avg, max) = (10.349, 10.483, 10.599), stdev = 0.126
  CI (99.9%): [8.185, 12.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 9.447 ops/ms
Iteration   1: 9.947 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.840 ±(99.9%) 6.789 ops/ms [Average]
  (min, avg, max) = (9.426, 9.840, 10.147), stdev = 0.372
  CI (99.9%): [3.051, 16.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 7.504 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 8.290 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.352 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (8.290, 8.352, 8.431), stdev = 0.072
  CI (99.9%): [7.039, 9.665] (assumes normal distribution)


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
# Warmup Iteration   1: 9.486 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.005 ms/op
Iteration   1: 3.165 ±(99.9%) 0.007 ms/op
Iteration   2: 3.190 ±(99.9%) 0.005 ms/op
Iteration   3: 3.253 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.203 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.165, 3.203, 3.253), stdev = 0.045
  CI (99.9%): [2.375, 4.031] (assumes normal distribution)


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
# Warmup Iteration   1: 7.914 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 2.980 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.015 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.980, 3.015, 3.041), stdev = 0.032
  CI (99.9%): [2.439, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.003 ms/op
Iteration   1: 3.162 ±(99.9%) 0.004 ms/op
Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.147 ±(99.9%) 1.302 ms/op [Average]
  (min, avg, max) = (3.069, 3.147, 3.210), stdev = 0.071
  CI (99.9%): [1.845, 4.449] (assumes normal distribution)


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
# Warmup Iteration   1: 9.333 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.007 ms/op
Iteration   1: 3.702 ±(99.9%) 0.011 ms/op
Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
Iteration   3: 3.775 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.703 ±(99.9%) 1.317 ms/op [Average]
  (min, avg, max) = (3.631, 3.703, 3.775), stdev = 0.072
  CI (99.9%): [2.386, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 7.848 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   6.418 ms/op
                 createUser·p0.999:  19.253 ms/op
                 createUser·p0.9999: 25.096 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  15.548 ms/op
                 createUser·p0.9999: 22.809 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  18.832 ms/op
                 createUser·p0.9999: 23.973 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295954
  mean =      3.239 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15337 
    [ 2.500,  5.000) = 274881 
    [ 5.000,  7.500) = 4762 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     24.393 ms/op
     p(99.9990) =     27.974 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 6.952 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 20.178 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.829 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.210 ms/op
                 existUser·p0.9999: 22.567 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308029
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19076 
    [ 2.500,  5.000) = 283712 
    [ 5.000,  7.500) = 4530 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     13.254 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 8.169 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  19.932 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  9.366 ms/op
                 getUser·p0.9999: 31.974 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 3.262 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.359 ms/op
                 getUser·p0.9999: 19.995 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297573
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19409 
    [ 2.500,  5.000) = 270857 
    [ 5.000,  7.500) = 6348 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     16.403 ms/op
     p(99.9900) =     30.301 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 8.267 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.010 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  13.946 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.747 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.882 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 19.643 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.673 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.071 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  12.500 ms/op
                 listUser·p0.9999: 13.931 ms/op
                 listUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256729
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 249710 
    [ 5.000,  7.500) = 4820 
    [ 7.500, 10.000) = 1448 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.736 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.711 ± 0.999  ops/ms
ClientPb.existUser                       thrpt       3  10.483 ± 2.298  ops/ms
ClientPb.getUser                         thrpt       3   9.840 ± 6.789  ops/ms
ClientPb.listUser                        thrpt       3   8.352 ± 1.313  ops/ms
ClientPb.createUser                       avgt       3   3.203 ± 0.828   ms/op
ClientPb.existUser                        avgt       3   3.015 ± 0.576   ms/op
ClientPb.getUser                          avgt       3   3.147 ± 1.302   ms/op
ClientPb.listUser                         avgt       3   3.703 ± 1.317   ms/op
ClientPb.createUser                     sample  295954   3.239 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.842           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.393           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  308029   3.114 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.941           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706           ms/op
ClientPb.getUser                        sample  297573   3.225 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.403           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.301           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  256729   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.283           ms/op
