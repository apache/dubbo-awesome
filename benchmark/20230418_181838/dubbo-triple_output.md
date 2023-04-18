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
# Warmup Iteration   1: 1.567 ops/ms
# Warmup Iteration   2: 3.751 ops/ms
# Warmup Iteration   3: 7.682 ops/ms
Iteration   1: 7.516 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.926 ±(99.9%) 6.577 ops/ms [Average]
  (min, avg, max) = (7.516, 7.926, 8.194), stdev = 0.361
  CI (99.9%): [1.349, 14.503] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 7.121 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.718 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.553 ±(99.9%) 3.697 ops/ms [Average]
  (min, avg, max) = (8.326, 8.553, 8.718), stdev = 0.203
  CI (99.9%): [4.856, 12.250] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 6.720 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.210 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (8.136, 8.210, 8.358), stdev = 0.128
  CI (99.9%): [5.874, 10.547] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.079 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 6.922 ops/ms
Iteration   1: 6.990 ops/ms
Iteration   2: 7.222 ops/ms
Iteration   3: 6.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.040 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (6.908, 7.040, 7.222), stdev = 0.163
  CI (99.9%): [4.068, 10.012] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.713 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.835 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.004 ms/op
Iteration   1: 3.755 ±(99.9%) 0.014 ms/op
Iteration   2: 3.795 ±(99.9%) 0.011 ms/op
Iteration   3: 3.880 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.810 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.755, 3.810, 3.880), stdev = 0.064
  CI (99.9%): [2.642, 4.978] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.738 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.005 ms/op
Iteration   1: 3.780 ±(99.9%) 0.005 ms/op
Iteration   2: 3.860 ±(99.9%) 0.005 ms/op
Iteration   3: 3.732 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.790 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (3.732, 3.790, 3.860), stdev = 0.065
  CI (99.9%): [2.609, 4.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.780 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 3.894 ±(99.9%) 0.007 ms/op
Iteration   2: 3.881 ±(99.9%) 0.009 ms/op
Iteration   3: 4.010 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.928 ±(99.9%) 1.298 ms/op [Average]
  (min, avg, max) = (3.881, 3.928, 4.010), stdev = 0.071
  CI (99.9%): [2.631, 5.226] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.871 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.009 ms/op
Iteration   1: 4.875 ±(99.9%) 0.007 ms/op
Iteration   2: 4.475 ±(99.9%) 0.011 ms/op
Iteration   3: 4.371 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.574 ±(99.9%) 4.849 ms/op [Average]
  (min, avg, max) = (4.371, 4.574, 4.875), stdev = 0.266
  CI (99.9%): [≈ 0, 9.423] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.921 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.927 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.590 ±(99.9%) 0.022 ms/op
Iteration   1: 4.041 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  24.559 ms/op
                 createUser·p0.9999: 32.026 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  17.634 ms/op
                 createUser·p0.9999: 32.083 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   3: 3.834 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  26.973 ms/op
                 createUser·p0.9999: 34.056 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246401
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 788 
    [ 2.500,  5.000) = 232864 
    [ 5.000,  7.500) = 10515 
    [ 7.500, 10.000) = 1666 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     23.403 ms/op
     p(99.9900) =     32.911 ms/op
     p(99.9990) =     34.346 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 11.998 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.011 ms/op
Iteration   1: 3.732 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.867 ms/op
                 existUser·p0.9999: 23.935 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.793 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  24.871 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   3: 3.717 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  15.932 ms/op
                 existUser·p0.9999: 30.546 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256145
  mean =      3.747 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1044 
    [ 2.500,  5.000) = 245652 
    [ 5.000,  7.500) = 8116 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.452 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     29.516 ms/op
     p(99.9990) =     31.679 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 13.198 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.014 ms/op
Iteration   1: 4.261 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  24.998 ms/op
                 getUser·p0.9999: 32.963 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   2: 4.062 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 4.005 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  27.169 ms/op
                 getUser·p0.9999: 30.839 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233732
  mean =      4.106 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 215800 
    [ 5.000,  7.500) = 14931 
    [ 7.500, 10.000) = 1998 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     24.290 ms/op
     p(99.9900) =     31.478 ms/op
     p(99.9990) =     34.230 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 15.672 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.017 ms/op
Iteration   1: 4.541 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  22.891 ms/op
                 listUser·p0.9999: 25.588 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 4.701 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 23.383 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 4.713 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 23.558 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206240
  mean =      4.650 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 179824 
    [ 5.000,  7.500) = 22228 
    [ 7.500, 10.000) = 3085 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.049 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.926 ± 6.577  ops/ms
ClientPb.existUser                       thrpt       3   8.553 ± 3.697  ops/ms
ClientPb.getUser                         thrpt       3   8.210 ± 2.336  ops/ms
ClientPb.listUser                        thrpt       3   7.040 ± 2.972  ops/ms
ClientPb.createUser                       avgt       3   3.810 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.790 ± 1.182   ms/op
ClientPb.getUser                          avgt       3   3.928 ± 1.298   ms/op
ClientPb.listUser                         avgt       3   4.574 ± 4.849   ms/op
ClientPb.createUser                     sample  246401   3.894 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.403           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  256145   3.747 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.452           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.516           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  233732   4.106 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.850           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.290           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.478           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  206240   4.650 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.985           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.840           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.099           ms/op
