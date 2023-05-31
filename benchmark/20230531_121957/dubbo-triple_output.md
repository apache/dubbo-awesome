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
# Warmup Iteration   1: 1.065 ops/ms
# Warmup Iteration   2: 2.120 ops/ms
# Warmup Iteration   3: 4.897 ops/ms
Iteration   1: 5.547 ops/ms
Iteration   2: 5.704 ops/ms
Iteration   3: 5.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.713 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (5.547, 5.713, 5.888), stdev = 0.171
  CI (99.9%): [2.598, 8.828] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 4.902 ops/ms
# Warmup Iteration   3: 6.006 ops/ms
Iteration   1: 6.333 ops/ms
Iteration   2: 6.181 ops/ms
Iteration   3: 6.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.267 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (6.181, 6.267, 6.333), stdev = 0.078
  CI (99.9%): [4.849, 7.685] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.631 ops/ms
# Warmup Iteration   2: 4.931 ops/ms
# Warmup Iteration   3: 5.794 ops/ms
Iteration   1: 5.771 ops/ms
Iteration   2: 5.725 ops/ms
Iteration   3: 5.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.802 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (5.725, 5.802, 5.910), stdev = 0.096
  CI (99.9%): [4.048, 7.556] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.560 ops/ms
# Warmup Iteration   2: 4.175 ops/ms
# Warmup Iteration   3: 4.876 ops/ms
Iteration   1: 4.805 ops/ms
Iteration   2: 4.971 ops/ms
Iteration   3: 5.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.932 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (4.805, 4.932, 5.019), stdev = 0.112
  CI (99.9%): [2.886, 6.978] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.904 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.372 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.739 ±(99.9%) 0.009 ms/op
Iteration   1: 5.716 ±(99.9%) 0.006 ms/op
Iteration   2: 5.692 ±(99.9%) 0.016 ms/op
Iteration   3: 5.502 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.637 ±(99.9%) 2.141 ms/op [Average]
  (min, avg, max) = (5.502, 5.637, 5.716), stdev = 0.117
  CI (99.9%): [3.496, 7.778] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.971 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.807 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.439 ±(99.9%) 0.007 ms/op
Iteration   1: 5.046 ±(99.9%) 0.011 ms/op
Iteration   2: 5.171 ±(99.9%) 0.012 ms/op
Iteration   3: 5.045 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.087 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (5.045, 5.087, 5.171), stdev = 0.072
  CI (99.9%): [3.771, 6.403] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.446 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.421 ±(99.9%) 0.014 ms/op
Iteration   1: 5.501 ±(99.9%) 0.010 ms/op
Iteration   2: 5.458 ±(99.9%) 0.013 ms/op
Iteration   3: 5.550 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.503 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (5.458, 5.503, 5.550), stdev = 0.046
  CI (99.9%): [4.661, 6.345] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.798 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 7.676 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.108 ±(99.9%) 0.016 ms/op
Iteration   1: 6.318 ±(99.9%) 0.017 ms/op
Iteration   2: 6.447 ±(99.9%) 0.011 ms/op
Iteration   3: 6.164 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.309 ±(99.9%) 2.585 ms/op [Average]
  (min, avg, max) = (6.164, 6.309, 6.447), stdev = 0.142
  CI (99.9%): [3.725, 8.894] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.616 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.195 ±(99.9%) 0.029 ms/op
Iteration   1: 5.705 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.905 ms/op
                 createUser·p0.99:   11.461 ms/op
                 createUser·p0.999:  31.159 ms/op
                 createUser·p0.9999: 39.046 ms/op
                 createUser·p1.00:   40.567 ms/op

Iteration   2: 5.413 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.234 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  27.525 ms/op
                 createUser·p0.9999: 30.576 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 5.474 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.421 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.791 ms/op
                 createUser·p0.999:  29.575 ms/op
                 createUser·p0.9999: 34.941 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173530
  mean =      5.528 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 58384 
    [ 5.000, 10.000) = 113065 
    [10.000, 15.000) = 1572 
    [15.000, 20.000) = 188 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 110 
    [30.000, 35.000) = 93 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.388 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     28.801 ms/op
     p(99.9900) =     36.916 ms/op
     p(99.9990) =     39.699 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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
# Warmup Iteration   1: 14.863 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.974 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.322 ±(99.9%) 0.017 ms/op
Iteration   1: 5.101 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.030 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  22.914 ms/op
                 existUser·p0.9999: 30.701 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 5.411 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   7.266 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  18.050 ms/op
                 existUser·p0.9999: 26.753 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 5.295 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.392 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.395 ms/op
                 existUser·p0.99:   10.305 ms/op
                 existUser·p0.999:  28.302 ms/op
                 existUser·p0.9999: 30.736 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182152
  mean =      5.266 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 99994 
    [ 5.000,  7.500) = 71412 
    [ 7.500, 10.000) = 8662 
    [10.000, 12.500) = 1184 
    [12.500, 15.000) = 517 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     18.812 ms/op
     p(99.9900) =     30.598 ms/op
     p(99.9990) =     31.069 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 16.436 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.164 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.589 ±(99.9%) 0.020 ms/op
Iteration   1: 5.393 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.554 ms/op
                 getUser·p0.95:   7.160 ms/op
                 getUser·p0.99:   9.526 ms/op
                 getUser·p0.999:  22.308 ms/op
                 getUser·p0.9999: 26.585 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 5.509 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.562 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   10.807 ms/op
                 getUser·p0.999:  24.216 ms/op
                 getUser·p0.9999: 28.619 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 5.360 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.062 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  17.500 ms/op
                 getUser·p0.9999: 29.365 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177055
  mean =      5.420 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 70554 
    [ 5.000,  7.500) = 99006 
    [ 7.500, 10.000) = 5621 
    [10.000, 12.500) = 1216 
    [12.500, 15.000) = 350 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     28.953 ms/op
     p(99.9990) =     29.925 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 22.542 ±(99.9%) 0.382 ms/op
# Warmup Iteration   2: 9.374 ±(99.9%) 0.083 ms/op
# Warmup Iteration   3: 6.951 ±(99.9%) 0.032 ms/op
Iteration   1: 6.346 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  28.574 ms/op
                 listUser·p0.9999: 31.220 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   2: 6.461 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  29.983 ms/op
                 listUser·p0.9999: 35.334 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   3: 6.322 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  22.377 ms/op
                 listUser·p0.9999: 31.881 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150498
  mean =      6.376 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 5275 
    [ 5.000,  7.500) = 130440 
    [ 7.500, 10.000) = 11275 
    [10.000, 12.500) = 2403 
    [12.500, 15.000) = 512 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 135 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      6.046 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     28.639 ms/op
     p(99.9900) =     32.542 ms/op
     p(99.9990) =     36.335 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.713 ± 3.115  ops/ms
ClientPb.existUser                       thrpt       3   6.267 ± 1.418  ops/ms
ClientPb.getUser                         thrpt       3   5.802 ± 1.754  ops/ms
ClientPb.listUser                        thrpt       3   4.932 ± 2.046  ops/ms
ClientPb.createUser                       avgt       3   5.637 ± 2.141   ms/op
ClientPb.existUser                        avgt       3   5.087 ± 1.316   ms/op
ClientPb.getUser                          avgt       3   5.503 ± 0.842   ms/op
ClientPb.listUser                         avgt       3   6.309 ± 2.585   ms/op
ClientPb.createUser                     sample  173530   5.528 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.388           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.801           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.916           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.567           ms/op
ClientPb.existUser                      sample  182152   5.266 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.030           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.692           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.240           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.598           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  177055   5.420 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.506           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.234           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.060           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.953           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950           ms/op
ClientPb.listUser                       sample  150498   6.376 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.600           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.639           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.766           ms/op
