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
# Warmup Iteration   1: 1.908 ops/ms
# Warmup Iteration   2: 5.907 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.447 ops/ms
Iteration   2: 9.158 ops/ms
Iteration   3: 9.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.926 ±(99.9%) 7.580 ops/ms [Average]
  (min, avg, max) = (8.447, 8.926, 9.175), stdev = 0.416
  CI (99.9%): [1.346, 16.507] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.134 ops/ms
# Warmup Iteration   2: 8.483 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.275 ops/ms
Iteration   2: 9.478 ops/ms
Iteration   3: 9.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.522 ±(99.9%) 4.941 ops/ms [Average]
  (min, avg, max) = (9.275, 9.522, 9.811), stdev = 0.271
  CI (99.9%): [4.580, 14.463] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.750 ops/ms
# Warmup Iteration   2: 8.342 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.497 ops/ms
Iteration   3: 9.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.398 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (9.288, 9.398, 9.497), stdev = 0.105
  CI (99.9%): [7.486, 11.310] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 7.055 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 7.801 ops/ms
Iteration   3: 7.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.924 ±(99.9%) 1.935 ops/ms [Average]
  (min, avg, max) = (7.801, 7.924, 7.985), stdev = 0.106
  CI (99.9%): [5.989, 9.859] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.568 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.012 ms/op
Iteration   1: 3.484 ±(99.9%) 0.010 ms/op
Iteration   2: 3.413 ±(99.9%) 0.004 ms/op
Iteration   3: 3.453 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.413, 3.450, 3.484), stdev = 0.036
  CI (99.9%): [2.795, 4.105] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.455 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.004 ms/op
Iteration   1: 3.286 ±(99.9%) 0.007 ms/op
Iteration   2: 3.268 ±(99.9%) 0.006 ms/op
Iteration   3: 3.366 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.268, 3.307, 3.366), stdev = 0.052
  CI (99.9%): [2.357, 4.257] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.295 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.004 ms/op
Iteration   1: 3.448 ±(99.9%) 0.006 ms/op
Iteration   2: 3.405 ±(99.9%) 0.006 ms/op
Iteration   3: 3.424 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.405, 3.426, 3.448), stdev = 0.021
  CI (99.9%): [3.038, 3.813] (assumes normal distribution)


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
# Warmup Iteration   1: 12.242 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.007 ms/op
Iteration   1: 4.036 ±(99.9%) 0.010 ms/op
Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
Iteration   3: 3.908 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.978 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.908, 3.978, 4.036), stdev = 0.065
  CI (99.9%): [2.791, 5.164] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.534 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.011 ms/op
Iteration   1: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.832 ms/op
                 createUser·p0.9999: 22.929 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.537 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  23.088 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  20.542 ms/op
                 createUser·p0.9999: 26.007 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276543
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10824 
    [ 2.500,  5.000) = 259087 
    [ 5.000,  7.500) = 5602 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     20.263 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 9.097 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.008 ms/op
Iteration   1: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  15.040 ms/op
                 existUser·p0.9999: 21.277 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.425 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.895 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  17.765 ms/op
                 existUser·p0.9999: 26.267 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283923
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15870 
    [ 2.500,  5.000) = 262803 
    [ 5.000,  7.500) = 4402 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     17.869 ms/op
     p(99.9900) =     25.147 ms/op
     p(99.9990) =     26.600 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.595 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.012 ms/op
Iteration   1: 3.509 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   5.011 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  11.761 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 25.888 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.876 ms/op
                 getUser·p0.9999: 31.289 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272396
  mean =      3.522 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9346 
    [ 2.500,  5.000) = 252299 
    [ 5.000,  7.500) = 9097 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.290 ms/op
     p(99.9900) =     30.393 ms/op
     p(99.9990) =     31.765 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 10.779 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.014 ms/op
Iteration   1: 4.106 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  21.563 ms/op
                 listUser·p0.9999: 30.599 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 3.886 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.000 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.265 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240153
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 231578 
    [ 5.000,  7.500) = 6527 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.530 ms/op
     p(99.9900) =     29.622 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.926 ± 7.580  ops/ms
ClientPb.existUser                       thrpt       3   9.522 ± 4.941  ops/ms
ClientPb.getUser                         thrpt       3   9.398 ± 1.912  ops/ms
ClientPb.listUser                        thrpt       3   7.924 ± 1.935  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.655   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 0.950   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 0.388   ms/op
ClientPb.listUser                         avgt       3   3.978 ± 1.187   ms/op
ClientPb.createUser                     sample  276543   3.470 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.263           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  283923   3.380 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.869           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  272396   3.522 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.290           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.393           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  240153   3.995 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.530           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.622           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
