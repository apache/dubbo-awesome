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
# Warmup Iteration   1: 1.637 ops/ms
# Warmup Iteration   2: 4.705 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 8.451 ops/ms
Iteration   2: 8.376 ops/ms
Iteration   3: 8.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.436 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (8.376, 8.436, 8.481), stdev = 0.054
  CI (99.9%): [7.456, 9.415] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 7.975 ops/ms
# Warmup Iteration   3: 8.815 ops/ms
Iteration   1: 9.219 ops/ms
Iteration   2: 9.197 ops/ms
Iteration   3: 9.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.253 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (9.197, 9.253, 9.343), stdev = 0.079
  CI (99.9%): [7.811, 10.695] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 7.282 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 8.971 ops/ms
Iteration   2: 8.868 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.029 ±(99.9%) 3.590 ops/ms [Average]
  (min, avg, max) = (8.868, 9.029, 9.249), stdev = 0.197
  CI (99.9%): [5.440, 12.619] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 7.541 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.696 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (7.615, 7.696, 7.780), stdev = 0.083
  CI (99.9%): [6.185, 9.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.404 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.010 ms/op
Iteration   1: 3.430 ±(99.9%) 0.003 ms/op
Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
Iteration   3: 3.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.461 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.430, 3.461, 3.512), stdev = 0.044
  CI (99.9%): [2.651, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 10.765 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.287 ±(99.9%) 0.006 ms/op
Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
Iteration   3: 3.239 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.239, 3.304, 3.384), stdev = 0.074
  CI (99.9%): [1.959, 4.649] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.470 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.006 ms/op
Iteration   1: 3.475 ±(99.9%) 0.006 ms/op
Iteration   2: 3.451 ±(99.9%) 0.005 ms/op
Iteration   3: 3.581 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.451, 3.502, 3.581), stdev = 0.069
  CI (99.9%): [2.244, 4.760] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.312 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.010 ms/op
Iteration   1: 4.236 ±(99.9%) 0.009 ms/op
Iteration   2: 4.179 ±(99.9%) 0.009 ms/op
Iteration   3: 4.276 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.230 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (4.179, 4.230, 4.276), stdev = 0.049
  CI (99.9%): [3.340, 5.121] (assumes normal distribution)


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
# Warmup Iteration   1: 10.978 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.014 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  19.535 ms/op
                 createUser·p0.9999: 22.921 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.379 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  20.988 ms/op
                 createUser·p0.9999: 32.313 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 31.918 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281481
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11601 
    [ 2.500,  5.000) = 264052 
    [ 5.000,  7.500) = 4817 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     20.202 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     32.979 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.789 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.613 ms/op
                 existUser·p0.999:  16.339 ms/op
                 existUser·p0.9999: 25.079 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   6.179 ms/op
                 existUser·p0.999:  10.418 ms/op
                 existUser·p0.9999: 29.989 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294746
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9951 
    [ 2.500,  5.000) = 279736 
    [ 5.000,  7.500) = 4309 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.392 ms/op
     p(99.9900) =     28.349 ms/op
     p(99.9990) =     32.973 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.450 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  17.870 ms/op
                 getUser·p0.9999: 22.595 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.796 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  21.820 ms/op
                 getUser·p0.9999: 26.921 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.490 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.690 ms/op
                 getUser·p0.999:  20.439 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278566
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9128 
    [ 2.500,  5.000) = 261786 
    [ 5.000,  7.500) = 6254 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     26.383 ms/op
     p(99.9990) =     27.783 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.076 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.016 ms/op
Iteration   1: 4.108 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  20.452 ms/op
                 listUser·p0.9999: 25.875 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 4.210 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.080 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.247 ms/op
                 listUser·p0.999:  17.493 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233071
  mean =      4.117 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 226318 
    [ 5.000,  7.500) = 4314 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     27.143 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.436 ± 0.979  ops/ms
ClientPb.existUser                       thrpt       3   9.253 ± 1.442  ops/ms
ClientPb.getUser                         thrpt       3   9.029 ± 3.590  ops/ms
ClientPb.listUser                        thrpt       3   7.696 ± 1.511  ops/ms
ClientPb.createUser                       avgt       3   3.461 ± 0.810   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 1.345   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 1.258   ms/op
ClientPb.listUser                         avgt       3   4.230 ± 0.890   ms/op
ClientPb.createUser                     sample  281481   3.410 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.122           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.883           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  294746   3.255 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.392           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.349           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  278566   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.466           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.383           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.279           ms/op
ClientPb.listUser                       sample  233071   4.117 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.445           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
