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
# Warmup Iteration   1: 1.902 ops/ms
# Warmup Iteration   2: 5.061 ops/ms
# Warmup Iteration   3: 8.318 ops/ms
Iteration   1: 9.517 ops/ms
Iteration   2: 9.186 ops/ms
Iteration   3: 9.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.416 ±(99.9%) 3.638 ops/ms [Average]
  (min, avg, max) = (9.186, 9.416, 9.544), stdev = 0.199
  CI (99.9%): [5.778, 13.054] (assumes normal distribution)


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
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 8.842 ops/ms
# Warmup Iteration   3: 9.504 ops/ms
Iteration   1: 9.522 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 9.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.834 ±(99.9%) 5.741 ops/ms [Average]
  (min, avg, max) = (9.522, 9.834, 10.151), stdev = 0.315
  CI (99.9%): [4.093, 15.575] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 7.979 ops/ms
# Warmup Iteration   3: 9.240 ops/ms
Iteration   1: 9.242 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.328 ±(99.9%) 3.052 ops/ms [Average]
  (min, avg, max) = (9.221, 9.328, 9.521), stdev = 0.167
  CI (99.9%): [6.276, 12.379] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ops/ms
# Warmup Iteration   2: 7.165 ops/ms
# Warmup Iteration   3: 7.544 ops/ms
Iteration   1: 7.839 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 7.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.893 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (7.839, 7.893, 7.938), stdev = 0.050
  CI (99.9%): [6.979, 8.806] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.127 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.008 ms/op
Iteration   1: 3.560 ±(99.9%) 0.009 ms/op
Iteration   2: 3.447 ±(99.9%) 0.004 ms/op
Iteration   3: 3.428 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.428, 3.478, 3.560), stdev = 0.072
  CI (99.9%): [2.174, 4.783] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.902 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.007 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
Iteration   2: 3.357 ±(99.9%) 0.012 ms/op
Iteration   3: 3.244 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.244, 3.283, 3.357), stdev = 0.064
  CI (99.9%): [2.114, 4.452] (assumes normal distribution)


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
# Warmup Iteration   1: 10.848 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.006 ms/op
Iteration   1: 3.404 ±(99.9%) 0.008 ms/op
Iteration   2: 3.502 ±(99.9%) 0.006 ms/op
Iteration   3: 3.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.464 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.404, 3.464, 3.502), stdev = 0.052
  CI (99.9%): [2.513, 4.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.494 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.009 ms/op
Iteration   1: 4.221 ±(99.9%) 0.006 ms/op
Iteration   2: 3.886 ±(99.9%) 0.014 ms/op
Iteration   3: 4.002 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.036 ±(99.9%) 3.110 ms/op [Average]
  (min, avg, max) = (3.886, 4.036, 4.221), stdev = 0.170
  CI (99.9%): [0.926, 7.147] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.948 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
Iteration   1: 3.394 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.536 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  22.528 ms/op
                 createUser·p0.9999: 32.003 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281856
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2091 
    [ 2.500,  5.000) = 275075 
    [ 5.000,  7.500) = 3904 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     19.839 ms/op
     p(99.9900) =     30.784 ms/op
     p(99.9990) =     32.455 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 8.457 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.345 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  20.009 ms/op
                 existUser·p0.9999: 23.490 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  20.686 ms/op
                 existUser·p0.9999: 30.187 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  17.759 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287689
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7809 
    [ 2.500,  5.000) = 273253 
    [ 5.000,  7.500) = 5919 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     18.491 ms/op
     p(99.9900) =     28.155 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.741 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.013 ms/op
Iteration   1: 3.500 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.396 ms/op
                 getUser·p0.999:  22.292 ms/op
                 getUser·p0.9999: 27.769 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  23.176 ms/op
                 getUser·p0.9999: 30.856 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   3: 3.611 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273452
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8409 
    [ 2.500,  5.000) = 255419 
    [ 5.000,  7.500) = 8487 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     15.391 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.793 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
Iteration   1: 4.143 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.654 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 4.074 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.650 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 3.992 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 23.329 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235860
  mean =      4.069 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 227023 
    [ 5.000,  7.500) = 5971 
    [ 7.500, 10.000) = 2104 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     17.568 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.438 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.416 ± 3.638  ops/ms
ClientPb.existUser                       thrpt       3   9.834 ± 5.741  ops/ms
ClientPb.getUser                         thrpt       3   9.328 ± 3.052  ops/ms
ClientPb.listUser                        thrpt       3   7.893 ± 0.913  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 1.305   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 1.169   ms/op
ClientPb.getUser                          avgt       3   3.464 ± 0.951   ms/op
ClientPb.listUser                         avgt       3   4.036 ± 3.110   ms/op
ClientPb.createUser                     sample  281856   3.404 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.526           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.784           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  287689   3.339 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.491           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.155           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  273452   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.367           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.391           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  235860   4.069 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.661           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.512           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.462           ms/op
