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
# Warmup Iteration   1: 1.781 ops/ms
# Warmup Iteration   2: 4.049 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.191 ±(99.9%) 6.065 ops/ms [Average]
  (min, avg, max) = (7.808, 8.191, 8.395), stdev = 0.332
  CI (99.9%): [2.126, 14.257] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 6.901 ops/ms
# Warmup Iteration   3: 8.314 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.504 ±(99.9%) 6.668 ops/ms [Average]
  (min, avg, max) = (8.118, 8.504, 8.844), stdev = 0.365
  CI (99.9%): [1.836, 15.171] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.250 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.134 ±(99.9%) 3.390 ops/ms [Average]
  (min, avg, max) = (7.922, 8.134, 8.269), stdev = 0.186
  CI (99.9%): [4.744, 11.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.838 ops/ms
# Warmup Iteration   2: 5.531 ops/ms
# Warmup Iteration   3: 6.328 ops/ms
Iteration   1: 6.842 ops/ms
Iteration   2: 6.796 ops/ms
Iteration   3: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.877 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (6.796, 6.877, 6.992), stdev = 0.102
  CI (99.9%): [5.008, 8.745] (assumes normal distribution)


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
# Warmup Iteration   1: 11.256 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.005 ms/op
Iteration   1: 4.049 ±(99.9%) 0.005 ms/op
Iteration   2: 3.947 ±(99.9%) 0.007 ms/op
Iteration   3: 3.907 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.968 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (3.907, 3.968, 4.049), stdev = 0.073
  CI (99.9%): [2.628, 5.307] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.334 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.003 ms/op
Iteration   1: 3.650 ±(99.9%) 0.007 ms/op
Iteration   2: 3.638 ±(99.9%) 0.009 ms/op
Iteration   3: 3.687 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.658 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.638, 3.658, 3.687), stdev = 0.026
  CI (99.9%): [3.188, 4.128] (assumes normal distribution)


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
# Warmup Iteration   1: 11.252 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.774 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.007 ms/op
Iteration   1: 3.921 ±(99.9%) 0.008 ms/op
Iteration   2: 4.002 ±(99.9%) 0.008 ms/op
Iteration   3: 3.842 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.922 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (3.842, 3.922, 4.002), stdev = 0.080
  CI (99.9%): [2.460, 5.383] (assumes normal distribution)


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
# Warmup Iteration   1: 12.780 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.403 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.009 ms/op
Iteration   1: 4.393 ±(99.9%) 0.013 ms/op
Iteration   2: 4.626 ±(99.9%) 0.011 ms/op
Iteration   3: 4.635 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.551 ±(99.9%) 2.507 ms/op [Average]
  (min, avg, max) = (4.393, 4.551, 4.635), stdev = 0.137
  CI (99.9%): [2.044, 7.059] (assumes normal distribution)


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
# Warmup Iteration   1: 11.827 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.017 ms/op
Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.425 ms/op
                 createUser·p0.999:  22.577 ms/op
                 createUser·p0.9999: 25.072 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 3.658 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  22.465 ms/op
                 createUser·p0.9999: 25.928 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.750 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  24.632 ms/op
                 createUser·p0.9999: 29.802 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 261476
  mean =      3.669 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4787 
    [ 2.500,  5.000) = 249363 
    [ 5.000,  7.500) = 5653 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     30.260 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 10.223 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.010 ms/op
Iteration   1: 3.630 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.826 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  25.185 ms/op
                 existUser·p0.9999: 28.703 ms/op
                 existUser·p1.00:   29.458 ms/op

Iteration   3: 3.675 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.062 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.586 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  17.957 ms/op
                 existUser·p0.9999: 31.785 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265591
  mean =      3.615 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3912 
    [ 2.500,  5.000) = 253528 
    [ 5.000,  7.500) = 6832 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     30.864 ms/op
     p(99.9990) =     31.983 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 12.897 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.015 ms/op
Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.879 ms/op
                 getUser·p0.999:  12.166 ms/op
                 getUser·p0.9999: 27.769 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.651 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.390 ms/op
                 getUser·p0.99:   6.321 ms/op
                 getUser·p0.999:  25.898 ms/op
                 getUser·p0.9999: 28.105 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.834 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.606 ms/op
                 getUser·p0.999:  25.884 ms/op
                 getUser·p0.9999: 34.974 ms/op
                 getUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 256428
  mean =      3.742 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2713 
    [ 2.500,  5.000) = 241205 
    [ 5.000,  7.500) = 11141 
    [ 7.500, 10.000) = 948 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     18.202 ms/op
     p(99.9900) =     33.161 ms/op
     p(99.9990) =     35.578 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 13.056 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.016 ms/op
Iteration   1: 4.219 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  24.674 ms/op
                 listUser·p0.9999: 27.107 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 18.811 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 4.308 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.182 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229478
  mean =      4.183 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 214068 
    [ 5.000,  7.500) = 12443 
    [ 7.500, 10.000) = 2012 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     16.327 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     27.332 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.191 ± 6.065  ops/ms
ClientPb.existUser                       thrpt       3   8.504 ± 6.668  ops/ms
ClientPb.getUser                         thrpt       3   8.134 ± 3.390  ops/ms
ClientPb.listUser                        thrpt       3   6.877 ± 1.868  ops/ms
ClientPb.createUser                       avgt       3   3.968 ± 1.340   ms/op
ClientPb.existUser                        avgt       3   3.658 ± 0.470   ms/op
ClientPb.getUser                          avgt       3   3.922 ± 1.462   ms/op
ClientPb.listUser                         avgt       3   4.551 ± 2.507   ms/op
ClientPb.createUser                     sample  261476   3.669 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.938           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.541           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.064           ms/op
ClientPb.existUser                      sample  265591   3.615 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.581           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.864           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  256428   3.742 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.202           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.161           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.717           ms/op
ClientPb.listUser                       sample  229478   4.183 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.227           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.905           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.327           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.575           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
