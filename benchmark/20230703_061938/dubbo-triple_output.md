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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 6.032 ops/ms
# Warmup Iteration   3: 9.041 ops/ms
Iteration   1: 9.687 ops/ms
Iteration   2: 9.784 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.799 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (9.687, 9.799, 9.927), stdev = 0.121
  CI (99.9%): [7.595, 12.004] (assumes normal distribution)


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
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.968 ops/ms
# Warmup Iteration   3: 9.845 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.040 ±(99.9%) 4.235 ops/ms [Average]
  (min, avg, max) = (9.836, 10.040, 10.292), stdev = 0.232
  CI (99.9%): [5.805, 14.274] (assumes normal distribution)


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
# Warmup Iteration   1: 3.628 ops/ms
# Warmup Iteration   2: 8.954 ops/ms
# Warmup Iteration   3: 9.171 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.482 ops/ms
Iteration   3: 9.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.702 ±(99.9%) 3.532 ops/ms [Average]
  (min, avg, max) = (9.482, 9.702, 9.846), stdev = 0.194
  CI (99.9%): [6.170, 13.234] (assumes normal distribution)


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
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 7.478 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.485 ops/ms
Iteration   3: 8.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.478 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (8.440, 8.478, 8.509), stdev = 0.035
  CI (99.9%): [7.838, 9.118] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.044 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.005 ms/op
Iteration   1: 3.181 ±(99.9%) 0.006 ms/op
Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
Iteration   3: 3.226 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.154, 3.187, 3.226), stdev = 0.036
  CI (99.9%): [2.524, 3.849] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.133 ±(99.9%) 0.009 ms/op
Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.038, 3.098, 3.133), stdev = 0.052
  CI (99.9%): [2.150, 4.045] (assumes normal distribution)


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
# Warmup Iteration   1: 8.358 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.005 ms/op
Iteration   1: 3.357 ±(99.9%) 0.003 ms/op
Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
Iteration   3: 3.184 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (3.184, 3.255, 3.357), stdev = 0.091
  CI (99.9%): [1.601, 4.908] (assumes normal distribution)


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
# Warmup Iteration   1: 9.454 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.007 ms/op
Iteration   1: 3.748 ±(99.9%) 0.011 ms/op
Iteration   2: 3.672 ±(99.9%) 0.012 ms/op
Iteration   3: 3.810 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.744 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (3.672, 3.744, 3.810), stdev = 0.069
  CI (99.9%): [2.482, 5.005] (assumes normal distribution)


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
# Warmup Iteration   1: 8.943 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.280 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 24.777 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.486 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.010 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 23.915 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  15.739 ms/op
                 createUser·p0.9999: 20.032 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287228
  mean =      3.341 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14514 
    [ 2.500,  5.000) = 264181 
    [ 5.000,  7.500) = 7463 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.280 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.051 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.892 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  13.371 ms/op
                 existUser·p0.9999: 30.999 ms/op
                 existUser·p1.00:   31.785 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.476 ms/op
                 existUser·p0.999:  8.920 ms/op
                 existUser·p0.9999: 25.778 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  9.346 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305894
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15636 
    [ 2.500,  5.000) = 284928 
    [ 5.000,  7.500) = 4674 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 8.242 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
Iteration   1: 3.262 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 28.350 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  9.445 ms/op
                 getUser·p0.9999: 22.317 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297180
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6471 
    [ 2.500,  5.000) = 283545 
    [ 5.000,  7.500) = 6007 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     17.885 ms/op
     p(99.9900) =     27.371 ms/op
     p(99.9990) =     29.394 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 9.641 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  15.311 ms/op
                 listUser·p0.9999: 23.149 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 3.698 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.936 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.671 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   3.990 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  13.039 ms/op
                 listUser·p0.9999: 15.137 ms/op
                 listUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259022
  mean =      3.704 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 252873 
    [ 5.000,  7.500) = 4517 
    [ 7.500, 10.000) = 899 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     21.429 ms/op
     p(99.9990) =     23.764 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.799 ± 2.204  ops/ms
ClientPb.existUser                       thrpt       3  10.040 ± 4.235  ops/ms
ClientPb.getUser                         thrpt       3   9.702 ± 3.532  ops/ms
ClientPb.listUser                        thrpt       3   8.478 ± 0.640  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 0.663   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 0.948   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 1.653   ms/op
ClientPb.listUser                         avgt       3   3.744 ± 1.262   ms/op
ClientPb.createUser                     sample  287228   3.341 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.280           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.657           ms/op
ClientPb.existUser                      sample  305894   3.136 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.245           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.785           ms/op
ClientPb.getUser                        sample  297180   3.227 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.904           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.885           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.371           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.458           ms/op
ClientPb.listUser                       sample  259022   3.704 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
