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
# Warmup Iteration   1: 1.461 ops/ms
# Warmup Iteration   2: 3.035 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.471 ops/ms
Iteration   2: 7.509 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.642 ±(99.9%) 4.799 ops/ms [Average]
  (min, avg, max) = (7.471, 7.642, 7.945), stdev = 0.263
  CI (99.9%): [2.843, 12.440] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 7.693 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.826 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (7.693, 7.826, 8.009), stdev = 0.164
  CI (99.9%): [4.840, 10.812] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 6.747 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.510 ops/ms
Iteration   2: 7.567 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.803 ±(99.9%) 8.367 ops/ms [Average]
  (min, avg, max) = (7.510, 7.803, 8.331), stdev = 0.459
  CI (99.9%): [≈ 0, 16.169] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 6.485 ops/ms
Iteration   1: 6.420 ops/ms
Iteration   2: 6.348 ops/ms
Iteration   3: 6.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.402 ±(99.9%) 0.867 ops/ms [Average]
  (min, avg, max) = (6.348, 6.402, 6.438), stdev = 0.048
  CI (99.9%): [5.535, 7.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.469 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.008 ms/op
Iteration   1: 4.231 ±(99.9%) 0.004 ms/op
Iteration   2: 4.041 ±(99.9%) 0.008 ms/op
Iteration   3: 4.176 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.149 ±(99.9%) 1.790 ms/op [Average]
  (min, avg, max) = (4.041, 4.149, 4.231), stdev = 0.098
  CI (99.9%): [2.360, 5.939] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.255 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.008 ms/op
Iteration   1: 3.901 ±(99.9%) 0.004 ms/op
Iteration   2: 3.853 ±(99.9%) 0.006 ms/op
Iteration   3: 3.970 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.908 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.853, 3.908, 3.970), stdev = 0.059
  CI (99.9%): [2.835, 4.981] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.321 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.894 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.005 ms/op
Iteration   1: 4.265 ±(99.9%) 0.005 ms/op
Iteration   2: 3.891 ±(99.9%) 0.006 ms/op
Iteration   3: 3.959 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.038 ±(99.9%) 3.638 ms/op [Average]
  (min, avg, max) = (3.891, 4.038, 4.265), stdev = 0.199
  CI (99.9%): [0.401, 7.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.387 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.833 ±(99.9%) 0.013 ms/op
Iteration   1: 4.799 ±(99.9%) 0.008 ms/op
Iteration   2: 4.684 ±(99.9%) 0.012 ms/op
Iteration   3: 4.763 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.749 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (4.684, 4.749, 4.799), stdev = 0.059
  CI (99.9%): [3.675, 5.822] (assumes normal distribution)


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
# Warmup Iteration   1: 12.539 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.456 ±(99.9%) 0.019 ms/op
Iteration   1: 4.212 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  27.030 ms/op
                 createUser·p0.9999: 44.657 ms/op
                 createUser·p1.00:   45.154 ms/op

Iteration   2: 3.999 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  25.823 ms/op
                 createUser·p0.9999: 34.996 ms/op
                 createUser·p1.00:   35.783 ms/op

Iteration   3: 3.883 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  19.874 ms/op
                 createUser·p0.9999: 30.433 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238317
  mean =      4.026 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221436 
    [ 5.000, 10.000) = 16153 
    [10.000, 15.000) = 364 
    [15.000, 20.000) = 89 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 145 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 38 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     25.712 ms/op
     p(99.9900) =     43.341 ms/op
     p(99.9990) =     44.892 ms/op
     p(99.9999) =     45.154 ms/op
    p(100.0000) =     45.154 ms/op


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
# Warmup Iteration   1: 12.813 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   6.901 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 23.856 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  23.560 ms/op
                 existUser·p0.9999: 26.414 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.757 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  11.382 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241467
  mean =      3.974 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 411 
    [ 2.500,  5.000) = 225707 
    [ 5.000,  7.500) = 13499 
    [ 7.500, 10.000) = 1354 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     26.762 ms/op
     p(99.9990) =     27.727 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 13.096 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.015 ms/op
Iteration   1: 4.071 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  13.635 ms/op
                 getUser·p0.9999: 27.698 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 4.176 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  11.824 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 4.137 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  28.587 ms/op
                 getUser·p0.9999: 32.867 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232649
  mean =      4.127 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 215102 
    [ 5.000,  7.500) = 14663 
    [ 7.500, 10.000) = 2056 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     14.058 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     33.566 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 14.901 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.666 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.951 ±(99.9%) 0.018 ms/op
Iteration   1: 4.831 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   9.244 ms/op
                 listUser·p0.999:  24.576 ms/op
                 listUser·p0.9999: 26.895 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.980 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  21.016 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 4.900 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  19.792 ms/op
                 listUser·p0.9999: 22.068 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195662
  mean =      4.903 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 146334 
    [ 5.000,  7.500) = 41772 
    [ 7.500, 10.000) = 5871 
    [10.000, 12.500) = 895 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     21.343 ms/op
     p(99.9900) =     26.294 ms/op
     p(99.9990) =     27.203 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.642 ± 4.799  ops/ms
ClientPb.existUser                       thrpt       3   7.826 ± 2.986  ops/ms
ClientPb.getUser                         thrpt       3   7.803 ± 8.367  ops/ms
ClientPb.listUser                        thrpt       3   6.402 ± 0.867  ops/ms
ClientPb.createUser                       avgt       3   4.149 ± 1.790   ms/op
ClientPb.existUser                        avgt       3   3.908 ± 1.073   ms/op
ClientPb.getUser                          avgt       3   4.038 ± 3.638   ms/op
ClientPb.listUser                         avgt       3   4.749 ± 1.074   ms/op
ClientPb.createUser                     sample  238317   4.026 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.712           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.341           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.154           ms/op
ClientPb.existUser                      sample  241467   3.974 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.762           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  232649   4.127 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.530           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.741           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.058           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.588           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  195662   4.903 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.343           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.294           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.329           ms/op
