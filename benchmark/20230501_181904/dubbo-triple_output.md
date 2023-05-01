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
# Warmup Iteration   1: 1.685 ops/ms
# Warmup Iteration   2: 3.477 ops/ms
# Warmup Iteration   3: 6.660 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 8.043 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.967 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (7.711, 7.967, 8.148), stdev = 0.228
  CI (99.9%): [3.803, 12.132] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.436 ops/ms
# Warmup Iteration   2: 6.703 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 8.471 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.550 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (8.471, 8.550, 8.616), stdev = 0.073
  CI (99.9%): [7.213, 9.887] (assumes normal distribution)


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
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 5.856 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.016 ±(99.9%) 5.053 ops/ms [Average]
  (min, avg, max) = (7.698, 8.016, 8.204), stdev = 0.277
  CI (99.9%): [2.963, 13.069] (assumes normal distribution)


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
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 6.076 ops/ms
# Warmup Iteration   3: 6.428 ops/ms
Iteration   1: 6.514 ops/ms
Iteration   2: 7.035 ops/ms
Iteration   3: 6.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.839 ±(99.9%) 5.177 ops/ms [Average]
  (min, avg, max) = (6.514, 6.839, 7.035), stdev = 0.284
  CI (99.9%): [1.663, 12.016] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.871 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.008 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
Iteration   2: 3.982 ±(99.9%) 0.008 ms/op
Iteration   3: 3.801 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.922 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (3.801, 3.922, 3.983), stdev = 0.105
  CI (99.9%): [2.014, 5.830] (assumes normal distribution)


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
# Warmup Iteration   1: 11.018 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
Iteration   1: 3.832 ±(99.9%) 0.012 ms/op
Iteration   2: 3.688 ±(99.9%) 0.006 ms/op
Iteration   3: 3.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.769 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.688, 3.769, 3.832), stdev = 0.074
  CI (99.9%): [2.424, 5.115] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.098 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
Iteration   2: 3.757 ±(99.9%) 0.012 ms/op
Iteration   3: 3.874 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.832 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.757, 3.832, 3.874), stdev = 0.065
  CI (99.9%): [2.644, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 14.151 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.009 ms/op
Iteration   1: 4.601 ±(99.9%) 0.013 ms/op
Iteration   2: 4.528 ±(99.9%) 0.014 ms/op
Iteration   3: 4.572 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.567 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.528, 4.567, 4.601), stdev = 0.037
  CI (99.9%): [3.899, 5.235] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.044 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.302 ±(99.9%) 0.018 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  11.548 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 3.900 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.524 ms/op
                 createUser·p0.999:  24.446 ms/op
                 createUser·p0.9999: 28.463 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   3: 4.008 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  26.232 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241643
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 344 
    [ 2.500,  5.000) = 229126 
    [ 5.000,  7.500) = 10228 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     24.096 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     32.536 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.766 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
Iteration   1: 3.991 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   8.143 ms/op
                 existUser·p0.999:  23.383 ms/op
                 existUser·p0.9999: 31.031 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   2: 3.844 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.838 ms/op
                 existUser·p0.999:  10.776 ms/op
                 existUser·p0.9999: 31.239 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   3: 3.711 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  10.514 ms/op
                 existUser·p0.9999: 46.121 ms/op
                 existUser·p1.00:   46.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249778
  mean =      3.845 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 235864 
    [ 5.000, 10.000) = 13414 
    [10.000, 15.000) = 276 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 31 
    [25.000, 30.000) = 127 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     44.567 ms/op
     p(99.9990) =     46.465 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


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
# Warmup Iteration   1: 13.240 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.988 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.013 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  15.663 ms/op
                 getUser·p0.9999: 28.929 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   2: 4.007 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  28.519 ms/op
                 getUser·p0.9999: 35.652 ms/op
                 getUser·p1.00:   37.356 ms/op

Iteration   3: 3.952 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.216 ms/op
                 getUser·p0.999:  25.821 ms/op
                 getUser·p0.9999: 28.791 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241656
  mean =      3.971 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 231037 
    [ 5.000,  7.500) = 7196 
    [ 7.500, 10.000) = 2753 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 107 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     24.937 ms/op
     p(99.9900) =     34.516 ms/op
     p(99.9990) =     36.542 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 13.099 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.829 ±(99.9%) 0.016 ms/op
Iteration   1: 4.667 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  23.338 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 4.563 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   4.949 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 19.396 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.507 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.973 ms/op
                 listUser·p0.9999: 19.716 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209643
  mean =      4.578 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 191831 
    [ 5.000,  7.500) = 13615 
    [ 7.500, 10.000) = 3177 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     18.001 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     26.645 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.967 ± 4.164  ops/ms
ClientPb.existUser                       thrpt       3   8.550 ± 1.337  ops/ms
ClientPb.getUser                         thrpt       3   8.016 ± 5.053  ops/ms
ClientPb.listUser                        thrpt       3   6.839 ± 5.177  ops/ms
ClientPb.createUser                       avgt       3   3.922 ± 1.908   ms/op
ClientPb.existUser                        avgt       3   3.769 ± 1.345   ms/op
ClientPb.getUser                          avgt       3   3.832 ± 1.187   ms/op
ClientPb.listUser                         avgt       3   4.567 ± 0.668   ms/op
ClientPb.createUser                     sample  241643   3.969 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.096           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.359           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  249778   3.845 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          44.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.727           ms/op
ClientPb.getUser                        sample  241656   3.971 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.937           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.516           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  209643   4.578 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.001           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.674           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
