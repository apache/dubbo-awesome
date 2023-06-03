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
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 4.668 ops/ms
# Warmup Iteration   3: 8.337 ops/ms
Iteration   1: 8.904 ops/ms
Iteration   2: 8.870 ops/ms
Iteration   3: 8.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.888 ±(99.9%) 0.308 ops/ms [Average]
  (min, avg, max) = (8.870, 8.888, 8.904), stdev = 0.017
  CI (99.9%): [8.579, 9.196] (assumes normal distribution)


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
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 8.671 ops/ms
# Warmup Iteration   3: 9.265 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 9.807 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.768 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (9.678, 9.768, 9.819), stdev = 0.078
  CI (99.9%): [8.341, 11.195] (assumes normal distribution)


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
# Warmup Iteration   1: 2.932 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 8.568 ops/ms
Iteration   1: 9.316 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.284 ±(99.9%) 2.520 ops/ms [Average]
  (min, avg, max) = (9.133, 9.284, 9.403), stdev = 0.138
  CI (99.9%): [6.765, 11.804] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.013 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (7.928, 8.013, 8.075), stdev = 0.076
  CI (99.9%): [6.628, 9.398] (assumes normal distribution)


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
# Warmup Iteration   1: 9.403 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.006 ms/op
Iteration   1: 3.365 ±(99.9%) 0.015 ms/op
Iteration   2: 3.447 ±(99.9%) 0.003 ms/op
Iteration   3: 3.442 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.365, 3.418, 3.447), stdev = 0.046
  CI (99.9%): [2.574, 4.261] (assumes normal distribution)


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
# Warmup Iteration   1: 9.413 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.005 ms/op
Iteration   1: 3.294 ±(99.9%) 0.007 ms/op
Iteration   2: 3.202 ±(99.9%) 0.010 ms/op
Iteration   3: 3.323 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.273 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.202, 3.273, 3.323), stdev = 0.063
  CI (99.9%): [2.116, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 9.363 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.004 ms/op
Iteration   1: 3.406 ±(99.9%) 0.011 ms/op
Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
Iteration   3: 3.465 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.406, 3.436, 3.465), stdev = 0.030
  CI (99.9%): [2.894, 3.977] (assumes normal distribution)


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
# Warmup Iteration   1: 11.224 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.006 ms/op
Iteration   1: 4.070 ±(99.9%) 0.006 ms/op
Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
Iteration   3: 4.053 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.031 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.972, 4.031, 4.070), stdev = 0.052
  CI (99.9%): [3.075, 4.988] (assumes normal distribution)


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
# Warmup Iteration   1: 8.881 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  20.705 ms/op
                 createUser·p0.9999: 23.060 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  23.398 ms/op
                 createUser·p0.9999: 26.168 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.432 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  20.278 ms/op
                 createUser·p0.9999: 28.849 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279930
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3368 
    [ 2.500,  5.000) = 271945 
    [ 5.000,  7.500) = 3517 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     20.491 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     29.406 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.251 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.008 ms/op
Iteration   1: 3.263 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 19.149 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  19.201 ms/op
                 existUser·p0.9999: 20.539 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 21.771 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285044
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9848 
    [ 2.500,  5.000) = 267773 
    [ 5.000,  7.500) = 6403 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     21.086 ms/op
     p(99.9990) =     22.428 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 9.176 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  22.104 ms/op
                 getUser·p0.9999: 29.067 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.222 ms/op
                 getUser·p0.999:  22.285 ms/op
                 getUser·p0.9999: 26.268 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.130 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  17.769 ms/op
                 getUser·p0.9999: 27.546 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278905
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5232 
    [ 2.500,  5.000) = 267091 
    [ 5.000,  7.500) = 5351 
    [ 7.500, 10.000) = 699 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     27.365 ms/op
     p(99.9990) =     31.737 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 10.298 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.015 ms/op
Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.100 ms/op
                 listUser·p0.99:   8.144 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 25.733 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235706
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 224980 
    [ 5.000,  7.500) = 8069 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     17.999 ms/op
     p(99.9900) =     23.247 ms/op
     p(99.9990) =     26.039 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.888 ± 0.308  ops/ms
ClientPb.existUser                       thrpt       3   9.768 ± 1.427  ops/ms
ClientPb.getUser                         thrpt       3   9.284 ± 2.520  ops/ms
ClientPb.listUser                        thrpt       3   8.013 ± 1.385  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 0.843   ms/op
ClientPb.existUser                        avgt       3   3.273 ± 1.157   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 0.542   ms/op
ClientPb.listUser                         avgt       3   4.031 ± 0.957   ms/op
ClientPb.createUser                     sample  279930   3.427 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.444           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.491           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  285044   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.086           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.610           ms/op
ClientPb.getUser                        sample  278905   3.439 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.365           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  235706   4.072 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.003           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.999           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.247           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
