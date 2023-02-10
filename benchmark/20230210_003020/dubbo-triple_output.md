# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 5.758 ops/ms
# Warmup Iteration   3: 8.488 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 8.950 ops/ms
Iteration   3: 9.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.027 ±(99.9%) 4.226 ops/ms [Average]
  (min, avg, max) = (8.843, 9.027, 9.287), stdev = 0.232
  CI (99.9%): [4.801, 13.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 8.748 ops/ms
# Warmup Iteration   3: 9.166 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.861 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (9.810, 9.861, 9.907), stdev = 0.049
  CI (99.9%): [8.974, 10.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 8.134 ops/ms
# Warmup Iteration   3: 9.287 ops/ms
Iteration   1: 9.535 ops/ms
Iteration   2: 9.354 ops/ms
Iteration   3: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.442 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (9.354, 9.442, 9.535), stdev = 0.090
  CI (99.9%): [7.793, 11.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.700 ops/ms
# Warmup Iteration   2: 7.278 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 8.172 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.075 ±(99.9%) 4.745 ops/ms [Average]
  (min, avg, max) = (7.781, 8.075, 8.273), stdev = 0.260
  CI (99.9%): [3.331, 12.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.007 ms/op
Iteration   1: 3.554 ±(99.9%) 0.007 ms/op
Iteration   2: 3.517 ±(99.9%) 0.009 ms/op
Iteration   3: 3.405 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.492 ±(99.9%) 1.413 ms/op [Average]
  (min, avg, max) = (3.405, 3.492, 3.554), stdev = 0.077
  CI (99.9%): [2.079, 4.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.151 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.007 ms/op
Iteration   1: 3.281 ±(99.9%) 0.003 ms/op
Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
Iteration   3: 3.413 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.303 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (3.214, 3.303, 3.413), stdev = 0.101
  CI (99.9%): [1.457, 5.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.828 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.005 ms/op
Iteration   1: 3.347 ±(99.9%) 0.007 ms/op
Iteration   2: 3.527 ±(99.9%) 0.004 ms/op
Iteration   3: 3.403 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 1.675 ms/op [Average]
  (min, avg, max) = (3.347, 3.426, 3.527), stdev = 0.092
  CI (99.9%): [1.751, 5.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.279 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 3.983 ±(99.9%) 0.009 ms/op
Iteration   2: 4.056 ±(99.9%) 0.012 ms/op
Iteration   3: 3.924 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.988 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.924, 3.988, 4.056), stdev = 0.066
  CI (99.9%): [2.786, 5.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.173 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.698 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   6.341 ms/op
                 createUser·p0.99:   7.606 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.606 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.838 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  20.568 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267501
  mean =      3.589 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5579 
    [ 2.500,  5.000) = 248706 
    [ 5.000,  7.500) = 11452 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 119 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     27.238 ms/op
     p(99.9990) =     28.423 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.240 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.364 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  23.036 ms/op
                 existUser·p0.9999: 27.160 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 37.421 ms/op
                 existUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287064
  mean =      3.341 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17015 
    [ 2.500,  5.000) = 263649 
    [ 5.000,  7.500) = 5058 
    [ 7.500, 10.000) = 824 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     36.179 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.515 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.012 ms/op
Iteration   1: 3.594 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  19.397 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  22.586 ms/op
                 getUser·p0.9999: 24.177 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 3.635 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 28.882 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268784
  mean =      3.570 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9688 
    [ 2.500,  5.000) = 250198 
    [ 5.000,  7.500) = 7524 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     27.046 ms/op
     p(99.9990) =     29.348 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.793 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.015 ms/op
Iteration   1: 4.038 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  21.488 ms/op
                 listUser·p0.9999: 26.903 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   2: 3.990 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.936 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 3.965 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.620 ms/op
                 listUser·p0.9999: 19.454 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240046
  mean =      3.997 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 232414 
    [ 5.000,  7.500) = 5323 
    [ 7.500, 10.000) = 1389 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     27.309 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.027 ± 4.226  ops/ms
ClientPb.existUser                       thrpt       3   9.861 ± 0.888  ops/ms
ClientPb.getUser                         thrpt       3   9.442 ± 1.649  ops/ms
ClientPb.listUser                        thrpt       3   8.075 ± 4.745  ops/ms
ClientPb.createUser                       avgt       3   3.492 ± 1.413   ms/op
ClientPb.existUser                        avgt       3   3.303 ± 1.846   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 1.675   ms/op
ClientPb.listUser                         avgt       3   3.988 ± 1.202   ms/op
ClientPb.createUser                     sample  267501   3.589 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  287064   3.341 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.683           ms/op
ClientPb.getUser                        sample  268784   3.570 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.440           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.046           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  240046   3.997 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.744           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.166           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.427           ms/op
