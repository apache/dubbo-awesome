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
# Warmup Iteration   1: 1.764 ops/ms
# Warmup Iteration   2: 3.945 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.535 ops/ms
Iteration   2: 7.926 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.873 ±(99.9%) 5.742 ops/ms [Average]
  (min, avg, max) = (7.535, 7.873, 8.157), stdev = 0.315
  CI (99.9%): [2.131, 13.614] (assumes normal distribution)


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
# Warmup Iteration   1: 2.411 ops/ms
# Warmup Iteration   2: 7.236 ops/ms
# Warmup Iteration   3: 8.222 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.338 ±(99.9%) 0.600 ops/ms [Average]
  (min, avg, max) = (8.300, 8.338, 8.361), stdev = 0.033
  CI (99.9%): [7.738, 8.938] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 6.580 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.929 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (7.757, 7.929, 8.025), stdev = 0.149
  CI (99.9%): [5.208, 10.650] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.344 ops/ms
# Warmup Iteration   2: 5.560 ops/ms
# Warmup Iteration   3: 6.627 ops/ms
Iteration   1: 6.911 ops/ms
Iteration   2: 6.779 ops/ms
Iteration   3: 7.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.917 ±(99.9%) 2.586 ops/ms [Average]
  (min, avg, max) = (6.779, 6.917, 7.062), stdev = 0.142
  CI (99.9%): [4.332, 9.503] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.608 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.005 ms/op
Iteration   1: 4.053 ±(99.9%) 0.007 ms/op
Iteration   2: 3.836 ±(99.9%) 0.006 ms/op
Iteration   3: 3.938 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.942 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (3.836, 3.942, 4.053), stdev = 0.109
  CI (99.9%): [1.958, 5.927] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.133 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.005 ms/op
Iteration   1: 3.791 ±(99.9%) 0.007 ms/op
Iteration   2: 3.737 ±(99.9%) 0.009 ms/op
Iteration   3: 3.847 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.792 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.737, 3.792, 3.847), stdev = 0.055
  CI (99.9%): [2.788, 4.796] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.875 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.002 ms/op
Iteration   1: 4.118 ±(99.9%) 0.006 ms/op
Iteration   2: 3.808 ±(99.9%) 0.014 ms/op
Iteration   3: 3.974 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.967 ±(99.9%) 2.826 ms/op [Average]
  (min, avg, max) = (3.808, 3.967, 4.118), stdev = 0.155
  CI (99.9%): [1.141, 6.792] (assumes normal distribution)


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
# Warmup Iteration   1: 11.785 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.010 ms/op
Iteration   1: 4.582 ±(99.9%) 0.012 ms/op
Iteration   2: 4.500 ±(99.9%) 0.015 ms/op
Iteration   3: 4.691 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.591 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (4.500, 4.591, 4.691), stdev = 0.096
  CI (99.9%): [2.842, 6.340] (assumes normal distribution)


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
# Warmup Iteration   1: 11.704 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 5.389 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.017 ms/op
Iteration   1: 4.442 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  18.120 ms/op
                 createUser·p0.9999: 28.704 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 3.916 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  26.782 ms/op
                 createUser·p0.9999: 33.194 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  16.050 ms/op
                 createUser·p0.9999: 32.309 ms/op
                 createUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236067
  mean =      4.065 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 332 
    [ 2.500,  5.000) = 218301 
    [ 5.000,  7.500) = 11965 
    [ 7.500, 10.000) = 4627 
    [10.000, 12.500) = 499 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     23.586 ms/op
     p(99.9900) =     32.322 ms/op
     p(99.9990) =     33.727 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 11.562 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.736 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  22.375 ms/op
                 existUser·p0.9999: 24.404 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  11.897 ms/op
                 existUser·p0.9999: 27.523 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  21.660 ms/op
                 existUser·p0.9999: 29.029 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244536
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 232287 
    [ 5.000,  7.500) = 10032 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     18.348 ms/op
     p(99.9900) =     27.740 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 11.960 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.015 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.077 ms/op
                 getUser·p0.999:  20.565 ms/op
                 getUser·p0.9999: 23.916 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  22.606 ms/op
                 getUser·p0.9999: 27.295 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 4.022 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  13.613 ms/op
                 getUser·p0.9999: 25.995 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241085
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 230874 
    [ 5.000,  7.500) = 8319 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     20.575 ms/op
     p(99.9900) =     26.178 ms/op
     p(99.9990) =     27.928 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 15.261 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.505 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.865 ±(99.9%) 0.017 ms/op
Iteration   1: 4.701 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  24.281 ms/op
                 listUser·p0.9999: 28.187 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   2: 4.749 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   3: 4.573 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205192
  mean =      4.673 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 178097 
    [ 5.000,  7.500) = 22470 
    [ 7.500, 10.000) = 3252 
    [10.000, 12.500) = 703 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     20.212 ms/op
     p(99.9900) =     27.262 ms/op
     p(99.9990) =     29.123 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.873 ± 5.742  ops/ms
ClientPb.existUser                       thrpt       3   8.338 ± 0.600  ops/ms
ClientPb.getUser                         thrpt       3   7.929 ± 2.721  ops/ms
ClientPb.listUser                        thrpt       3   6.917 ± 2.586  ops/ms
ClientPb.createUser                       avgt       3   3.942 ± 1.985   ms/op
ClientPb.existUser                        avgt       3   3.792 ± 1.004   ms/op
ClientPb.getUser                          avgt       3   3.967 ± 2.826   ms/op
ClientPb.listUser                         avgt       3   4.591 ± 1.749   ms/op
ClientPb.createUser                     sample  236067   4.065 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.628           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.586           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.322           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  244536   3.923 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.556           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.740           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  241085   3.981 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.278           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.178           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  205192   4.673 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.212           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.262           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.835           ms/op
