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
# Warmup Iteration   1: 1.776 ops/ms
# Warmup Iteration   2: 3.795 ops/ms
# Warmup Iteration   3: 7.558 ops/ms
Iteration   1: 7.589 ops/ms
Iteration   2: 7.871 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.827 ±(99.9%) 3.985 ops/ms [Average]
  (min, avg, max) = (7.589, 7.827, 8.019), stdev = 0.218
  CI (99.9%): [3.842, 11.812] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.476 ops/ms
# Warmup Iteration   2: 6.912 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 8.374 ops/ms
Iteration   3: 8.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.220 ±(99.9%) 6.502 ops/ms [Average]
  (min, avg, max) = (7.813, 8.220, 8.474), stdev = 0.356
  CI (99.9%): [1.718, 14.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.250 ops/ms
# Warmup Iteration   2: 6.892 ops/ms
# Warmup Iteration   3: 8.055 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 8.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.129 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (8.041, 8.129, 8.281), stdev = 0.132
  CI (99.9%): [5.728, 10.531] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 5.913 ops/ms
# Warmup Iteration   3: 6.547 ops/ms
Iteration   1: 6.764 ops/ms
Iteration   2: 6.968 ops/ms
Iteration   3: 6.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.893 ±(99.9%) 2.044 ops/ms [Average]
  (min, avg, max) = (6.764, 6.893, 6.968), stdev = 0.112
  CI (99.9%): [4.849, 8.937] (assumes normal distribution)


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
# Warmup Iteration   1: 11.395 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.010 ms/op
Iteration   1: 3.966 ±(99.9%) 0.010 ms/op
Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
Iteration   3: 3.936 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.924 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (3.869, 3.924, 3.966), stdev = 0.050
  CI (99.9%): [3.019, 4.828] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.333 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.006 ms/op
Iteration   1: 3.672 ±(99.9%) 0.010 ms/op
Iteration   2: 3.753 ±(99.9%) 0.008 ms/op
Iteration   3: 3.717 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.714 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.672, 3.714, 3.753), stdev = 0.040
  CI (99.9%): [2.977, 4.451] (assumes normal distribution)


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
# Warmup Iteration   1: 12.820 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.006 ms/op
Iteration   1: 4.058 ±(99.9%) 0.008 ms/op
Iteration   2: 3.873 ±(99.9%) 0.009 ms/op
Iteration   3: 3.889 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.940 ±(99.9%) 1.869 ms/op [Average]
  (min, avg, max) = (3.873, 3.940, 4.058), stdev = 0.102
  CI (99.9%): [2.070, 5.809] (assumes normal distribution)


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
# Warmup Iteration   1: 15.245 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.776 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.972 ±(99.9%) 0.005 ms/op
Iteration   1: 4.614 ±(99.9%) 0.012 ms/op
Iteration   2: 4.642 ±(99.9%) 0.012 ms/op
Iteration   3: 4.655 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.637 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (4.614, 4.637, 4.655), stdev = 0.021
  CI (99.9%): [4.252, 5.022] (assumes normal distribution)


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
# Warmup Iteration   1: 12.228 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.018 ms/op
Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.862 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  23.265 ms/op
                 createUser·p0.9999: 25.779 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.889 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  26.336 ms/op
                 createUser·p0.9999: 31.541 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   3: 3.944 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.823 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.138 ms/op
                 createUser·p0.999:  12.943 ms/op
                 createUser·p0.9999: 31.621 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244849
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 497 
    [ 2.500,  5.000) = 234153 
    [ 5.000,  7.500) = 8025 
    [ 7.500, 10.000) = 1668 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     32.083 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 11.934 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  21.097 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.800 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  13.037 ms/op
                 existUser·p0.9999: 23.841 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  22.612 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255381
  mean =      3.758 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 282 
    [ 2.500,  5.000) = 247025 
    [ 5.000,  7.500) = 6671 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     20.828 ms/op
     p(99.9900) =     27.848 ms/op
     p(99.9990) =     28.778 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 12.109 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
Iteration   1: 4.237 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  13.853 ms/op
                 getUser·p0.9999: 26.554 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 4.080 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 26.388 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 4.053 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  27.921 ms/op
                 getUser·p0.9999: 33.889 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232889
  mean =      4.121 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 215368 
    [ 5.000,  7.500) = 13988 
    [ 7.500, 10.000) = 2674 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.681 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     16.224 ms/op
     p(99.9900) =     33.086 ms/op
     p(99.9990) =     35.084 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 13.715 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 6.173 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.018 ms/op
Iteration   1: 4.696 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.138 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  26.828 ms/op
                 listUser·p0.9999: 30.093 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 4.767 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.964 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 24.208 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 4.604 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204776
  mean =      4.688 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 174877 
    [ 5.000,  7.500) = 24743 
    [ 7.500, 10.000) = 3762 
    [10.000, 12.500) = 834 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.093 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     19.665 ms/op
     p(99.9900) =     28.951 ms/op
     p(99.9990) =     30.599 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.827 ± 3.985  ops/ms
ClientPb.existUser                       thrpt       3   8.220 ± 6.502  ops/ms
ClientPb.getUser                         thrpt       3   8.129 ± 2.402  ops/ms
ClientPb.listUser                        thrpt       3   6.893 ± 2.044  ops/ms
ClientPb.createUser                       avgt       3   3.924 ± 0.905   ms/op
ClientPb.existUser                        avgt       3   3.714 ± 0.737   ms/op
ClientPb.getUser                          avgt       3   3.940 ± 1.869   ms/op
ClientPb.listUser                         avgt       3   4.637 ± 0.385   ms/op
ClientPb.createUser                     sample  244849   3.919 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.200           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  255381   3.758 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.346           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.848           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  232889   4.121 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.681           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.995           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.224           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.086           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  204776   4.688 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.093           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.322           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.665           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.951           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.392           ms/op
