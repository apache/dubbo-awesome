# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.313 ops/ms
# Warmup Iteration   3: 7.395 ops/ms
Iteration   1: 7.427 ops/ms
Iteration   2: 7.642 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.656 ±(99.9%) 4.313 ops/ms [Average]
  (min, avg, max) = (7.427, 7.656, 7.899), stdev = 0.236
  CI (99.9%): [3.343, 11.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 6.535 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 8.101 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.143 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (8.086, 8.143, 8.241), stdev = 0.086
  CI (99.9%): [6.583, 9.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 6.911 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.099 ±(99.9%) 4.048 ops/ms [Average]
  (min, avg, max) = (7.843, 8.099, 8.232), stdev = 0.222
  CI (99.9%): [4.052, 12.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.968 ops/ms
# Warmup Iteration   2: 5.291 ops/ms
# Warmup Iteration   3: 6.842 ops/ms
Iteration   1: 6.823 ops/ms
Iteration   2: 7.102 ops/ms
Iteration   3: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.892 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (6.751, 6.892, 7.102), stdev = 0.185
  CI (99.9%): [3.514, 10.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.568 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.005 ms/op
Iteration   1: 4.057 ±(99.9%) 0.010 ms/op
Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
Iteration   3: 3.988 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.972 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.871, 3.972, 4.057), stdev = 0.094
  CI (99.9%): [2.253, 5.691] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.868 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.008 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
Iteration   2: 3.783 ±(99.9%) 0.012 ms/op
Iteration   3: 3.835 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.794 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.764, 3.794, 3.835), stdev = 0.037
  CI (99.9%): [3.120, 4.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.973 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.014 ms/op
Iteration   1: 4.121 ±(99.9%) 0.009 ms/op
Iteration   2: 3.980 ±(99.9%) 0.014 ms/op
Iteration   3: 3.950 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.017 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (3.950, 4.017, 4.121), stdev = 0.091
  CI (99.9%): [2.349, 5.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.098 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.874 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.865 ±(99.9%) 0.008 ms/op
Iteration   1: 4.663 ±(99.9%) 0.015 ms/op
Iteration   2: 4.545 ±(99.9%) 0.013 ms/op
Iteration   3: 4.521 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.576 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (4.521, 4.576, 4.663), stdev = 0.076
  CI (99.9%): [3.191, 5.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.061 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.018 ms/op
Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  22.946 ms/op
                 createUser·p0.9999: 25.658 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.116 ms/op
                 createUser·p0.999:  11.660 ms/op
                 createUser·p0.9999: 34.929 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 4.329 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.417 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   8.319 ms/op
                 createUser·p0.999:  28.805 ms/op
                 createUser·p0.9999: 45.260 ms/op
                 createUser·p1.00:   47.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233922
  mean =      4.105 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216981 
    [ 5.000, 10.000) = 16223 
    [10.000, 15.000) = 405 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 81 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 59 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     23.268 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     46.435 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.731 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.013 ms/op
Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.942 ms/op
                 existUser·p0.999:  23.241 ms/op
                 existUser·p0.9999: 25.563 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  17.054 ms/op
                 existUser·p0.9999: 28.998 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 3.749 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  25.980 ms/op
                 existUser·p0.9999: 31.243 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251511
  mean =      3.819 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 587 
    [ 2.500,  5.000) = 241308 
    [ 5.000,  7.500) = 7717 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     22.772 ms/op
     p(99.9900) =     30.043 ms/op
     p(99.9990) =     32.161 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.415 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.075 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 26.847 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  23.829 ms/op
                 getUser·p0.9999: 29.584 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 4.079 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 26.580 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238338
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 136 
    [ 2.500,  5.000) = 222816 
    [ 5.000,  7.500) = 13130 
    [ 7.500, 10.000) = 1513 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     21.288 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     30.036 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.297 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.834 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.914 ±(99.9%) 0.017 ms/op
Iteration   1: 4.641 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.091 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  23.593 ms/op
                 listUser·p0.9999: 26.691 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   2: 4.657 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 23.827 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.519 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.397 ms/op
                 listUser·p0.9999: 21.587 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208344
  mean =      4.605 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 185795 
    [ 5.000,  7.500) = 17954 
    [ 7.500, 10.000) = 3592 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.709 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     25.805 ms/op
     p(99.9990) =     27.386 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.656 ± 4.313  ops/ms
ClientPb.existUser                       thrpt       3   8.143 ± 1.560  ops/ms
ClientPb.getUser                         thrpt       3   8.099 ± 4.048  ops/ms
ClientPb.listUser                        thrpt       3   6.892 ± 3.378  ops/ms
ClientPb.createUser                       avgt       3   3.972 ± 1.719   ms/op
ClientPb.existUser                        avgt       3   3.794 ± 0.674   ms/op
ClientPb.getUser                          avgt       3   4.017 ± 1.668   ms/op
ClientPb.listUser                         avgt       3   4.576 ± 1.385   ms/op
ClientPb.createUser                     sample  233922   4.105 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.417           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          47.317           ms/op
ClientPb.existUser                      sample  251511   3.819 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.772           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.043           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  238338   4.026 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.288           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  208344   4.605 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.179           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.513           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.805           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.558           ms/op
