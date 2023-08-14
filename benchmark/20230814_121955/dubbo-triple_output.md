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
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.004 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.035 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (7.823, 8.035, 8.184), stdev = 0.189
  CI (99.9%): [4.592, 11.477] (assumes normal distribution)


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
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 6.887 ops/ms
# Warmup Iteration   3: 8.067 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.183 ±(99.9%) 4.386 ops/ms [Average]
  (min, avg, max) = (8.001, 8.183, 8.455), stdev = 0.240
  CI (99.9%): [3.797, 12.569] (assumes normal distribution)


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
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 8.035 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.017 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (7.834, 8.017, 8.182), stdev = 0.175
  CI (99.9%): [4.828, 11.206] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 5.999 ops/ms
# Warmup Iteration   3: 6.828 ops/ms
Iteration   1: 6.919 ops/ms
Iteration   2: 6.851 ops/ms
Iteration   3: 6.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.869 ±(99.9%) 0.806 ops/ms [Average]
  (min, avg, max) = (6.836, 6.869, 6.919), stdev = 0.044
  CI (99.9%): [6.063, 7.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.254 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.006 ms/op
Iteration   1: 3.948 ±(99.9%) 0.007 ms/op
Iteration   2: 3.984 ±(99.9%) 0.006 ms/op
Iteration   3: 3.877 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.936 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.877, 3.936, 3.984), stdev = 0.054
  CI (99.9%): [2.946, 4.926] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.092 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.007 ms/op
Iteration   1: 3.961 ±(99.9%) 0.004 ms/op
Iteration   2: 3.891 ±(99.9%) 0.004 ms/op
Iteration   3: 3.735 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.862 ±(99.9%) 2.113 ms/op [Average]
  (min, avg, max) = (3.735, 3.862, 3.961), stdev = 0.116
  CI (99.9%): [1.749, 5.976] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.707 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.003 ms/op
Iteration   1: 3.899 ±(99.9%) 0.006 ms/op
Iteration   2: 3.922 ±(99.9%) 0.010 ms/op
Iteration   3: 3.926 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.916 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.899, 3.916, 3.926), stdev = 0.015
  CI (99.9%): [3.645, 4.186] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.599 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.007 ms/op
Iteration   1: 4.634 ±(99.9%) 0.007 ms/op
Iteration   2: 4.585 ±(99.9%) 0.012 ms/op
Iteration   3: 4.597 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.605 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (4.585, 4.605, 4.634), stdev = 0.025
  CI (99.9%): [4.141, 5.069] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.289 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.812 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.018 ms/op
Iteration   1: 3.881 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   7.137 ms/op
                 createUser·p0.999:  21.972 ms/op
                 createUser·p0.9999: 31.711 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   2: 3.805 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  24.874 ms/op
                 createUser·p0.9999: 28.377 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.917 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  28.753 ms/op
                 createUser·p0.9999: 31.779 ms/op
                 createUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248194
  mean =      3.867 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 630 
    [ 2.500,  5.000) = 234513 
    [ 5.000,  7.500) = 11049 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 117 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     32.312 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.505 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
Iteration   1: 3.643 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  10.800 ms/op
                 existUser·p0.9999: 29.367 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   2: 3.865 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  24.773 ms/op
                 existUser·p0.9999: 31.710 ms/op
                 existUser·p1.00:   32.440 ms/op

Iteration   3: 3.762 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 36.602 ms/op
                 existUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255520
  mean =      3.755 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 679 
    [ 2.500,  5.000) = 245196 
    [ 5.000,  7.500) = 6868 
    [ 7.500, 10.000) = 2124 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     37.181 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.651 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.016 ms/op
Iteration   1: 4.169 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  23.766 ms/op
                 getUser·p0.9999: 29.720 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 3.937 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  12.477 ms/op
                 getUser·p0.9999: 26.341 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.892 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.688 ms/op
                 getUser·p0.999:  27.553 ms/op
                 getUser·p0.9999: 30.256 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240100
  mean =      3.996 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 167 
    [ 2.500,  5.000) = 222742 
    [ 5.000,  7.500) = 12849 
    [ 7.500, 10.000) = 3306 
    [10.000, 12.500) = 715 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     29.916 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 14.350 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 6.083 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.018 ms/op
Iteration   1: 4.747 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.999 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  24.888 ms/op
                 listUser·p0.9999: 27.485 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.677 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  16.524 ms/op
                 listUser·p0.9999: 19.797 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.736 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 21.832 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203300
  mean =      4.720 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 174309 
    [ 5.000,  7.500) = 22074 
    [ 7.500, 10.000) = 5195 
    [10.000, 12.500) = 1089 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     19.608 ms/op
     p(99.9900) =     26.586 ms/op
     p(99.9990) =     27.884 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.035 ± 3.442  ops/ms
ClientPb.existUser                       thrpt       3   8.183 ± 4.386  ops/ms
ClientPb.getUser                         thrpt       3   8.017 ± 3.189  ops/ms
ClientPb.listUser                        thrpt       3   6.869 ± 0.806  ops/ms
ClientPb.createUser                       avgt       3   3.936 ± 0.990   ms/op
ClientPb.existUser                        avgt       3   3.862 ± 2.113   ms/op
ClientPb.getUser                          avgt       3   3.916 ± 0.270   ms/op
ClientPb.listUser                         avgt       3   4.605 ± 0.464   ms/op
ClientPb.createUser                     sample  248194   3.867 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.523           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  255520   3.755 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.619           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.848           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.945           ms/op
ClientPb.getUser                        sample  240100   3.996 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.992           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.658           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.916           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  203300   4.720 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.608           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.586           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
