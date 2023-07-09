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
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.929 ops/ms
# Warmup Iteration   3: 8.636 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.153 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.289 ±(99.9%) 3.152 ops/ms [Average]
  (min, avg, max) = (9.153, 9.289, 9.483), stdev = 0.173
  CI (99.9%): [6.137, 12.441] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 8.737 ops/ms
# Warmup Iteration   3: 9.650 ops/ms
Iteration   1: 9.645 ops/ms
Iteration   2: 9.903 ops/ms
Iteration   3: 9.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.734 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (9.645, 9.734, 9.903), stdev = 0.146
  CI (99.9%): [7.070, 12.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.069 ops/ms
Iteration   2: 9.558 ops/ms
Iteration   3: 9.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.377 ±(99.9%) 4.889 ops/ms [Average]
  (min, avg, max) = (9.069, 9.377, 9.558), stdev = 0.268
  CI (99.9%): [4.488, 14.267] (assumes normal distribution)


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
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 7.503 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 8.106 ops/ms
Iteration   3: 7.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.900 ±(99.9%) 3.450 ops/ms [Average]
  (min, avg, max) = (7.734, 7.900, 8.106), stdev = 0.189
  CI (99.9%): [4.451, 11.350] (assumes normal distribution)


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
# Warmup Iteration   1: 9.447 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.008 ms/op
Iteration   1: 3.532 ±(99.9%) 0.006 ms/op
Iteration   2: 3.344 ±(99.9%) 0.011 ms/op
Iteration   3: 3.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.424 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (3.344, 3.424, 3.532), stdev = 0.097
  CI (99.9%): [1.651, 5.196] (assumes normal distribution)


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
# Warmup Iteration   1: 9.125 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.003 ms/op
Iteration   1: 3.387 ±(99.9%) 0.004 ms/op
Iteration   2: 3.262 ±(99.9%) 0.012 ms/op
Iteration   3: 3.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.356 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.262, 3.356, 3.420), stdev = 0.083
  CI (99.9%): [1.836, 4.877] (assumes normal distribution)


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
# Warmup Iteration   1: 8.740 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.004 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
Iteration   2: 3.568 ±(99.9%) 0.003 ms/op
Iteration   3: 3.357 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 2.168 ms/op [Average]
  (min, avg, max) = (3.357, 3.431, 3.568), stdev = 0.119
  CI (99.9%): [1.263, 5.600] (assumes normal distribution)


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
# Warmup Iteration   1: 11.867 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.007 ms/op
Iteration   1: 4.079 ±(99.9%) 0.007 ms/op
Iteration   2: 4.077 ±(99.9%) 0.009 ms/op
Iteration   3: 3.972 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.043 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (3.972, 4.043, 4.079), stdev = 0.062
  CI (99.9%): [2.916, 5.169] (assumes normal distribution)


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
# Warmup Iteration   1: 9.256 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.010 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.247 ms/op
                 createUser·p0.999:  20.409 ms/op
                 createUser·p0.9999: 25.017 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  20.831 ms/op
                 createUser·p0.9999: 23.877 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  18.417 ms/op
                 createUser·p0.9999: 23.738 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282784
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9079 
    [ 2.500,  5.000) = 267753 
    [ 5.000,  7.500) = 4758 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     24.647 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 8.420 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
Iteration   1: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.193 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  18.662 ms/op
                 existUser·p0.9999: 26.036 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  9.662 ms/op
                 existUser·p0.9999: 24.811 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.442 ms/op
                 existUser·p0.999:  17.525 ms/op
                 existUser·p0.9999: 26.981 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290481
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3800 
    [ 2.500,  5.000) = 281561 
    [ 5.000,  7.500) = 4430 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     14.058 ms/op
     p(99.9900) =     26.278 ms/op
     p(99.9990) =     27.592 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 8.691 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.010 ms/op
Iteration   1: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  14.691 ms/op
                 getUser·p0.9999: 23.877 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  16.642 ms/op
                 getUser·p0.9999: 24.939 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  18.914 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283273
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6432 
    [ 2.500,  5.000) = 269947 
    [ 5.000,  7.500) = 6070 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     14.753 ms/op
     p(99.9900) =     23.943 ms/op
     p(99.9990) =     25.570 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 9.844 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.013 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  19.513 ms/op
                 listUser·p0.9999: 24.440 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 16.278 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.983 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.770 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242109
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 234903 
    [ 5.000,  7.500) = 5100 
    [ 7.500, 10.000) = 1238 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.241 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     23.226 ms/op
     p(99.9990) =     24.923 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.289 ± 3.152  ops/ms
ClientPb.existUser                       thrpt       3   9.734 ± 2.664  ops/ms
ClientPb.getUser                         thrpt       3   9.377 ± 4.889  ops/ms
ClientPb.listUser                        thrpt       3   7.900 ± 3.450  ops/ms
ClientPb.createUser                       avgt       3   3.424 ± 1.772   ms/op
ClientPb.existUser                        avgt       3   3.356 ± 1.521   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 2.168   ms/op
ClientPb.listUser                         avgt       3   4.043 ± 1.127   ms/op
ClientPb.createUser                     sample  282784   3.394 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.448           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.647           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  290481   3.305 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.278           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  283273   3.387 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.753           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.985           ms/op
ClientPb.listUser                       sample  242109   3.961 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.226           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
