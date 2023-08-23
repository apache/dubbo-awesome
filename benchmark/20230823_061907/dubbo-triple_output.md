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
# Warmup Iteration   1: 1.057 ops/ms
# Warmup Iteration   2: 2.342 ops/ms
# Warmup Iteration   3: 4.793 ops/ms
Iteration   1: 5.240 ops/ms
Iteration   2: 5.590 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.498 ±(99.9%) 4.128 ops/ms [Average]
  (min, avg, max) = (5.240, 5.498, 5.663), stdev = 0.226
  CI (99.9%): [1.369, 9.626] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.567 ops/ms
# Warmup Iteration   2: 4.719 ops/ms
# Warmup Iteration   3: 5.506 ops/ms
Iteration   1: 5.719 ops/ms
Iteration   2: 5.572 ops/ms
Iteration   3: 5.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.691 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (5.572, 5.691, 5.782), stdev = 0.107
  CI (99.9%): [3.730, 7.652] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.471 ops/ms
# Warmup Iteration   2: 4.286 ops/ms
# Warmup Iteration   3: 5.417 ops/ms
Iteration   1: 5.156 ops/ms
Iteration   2: 5.208 ops/ms
Iteration   3: 5.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.294 ±(99.9%) 3.577 ops/ms [Average]
  (min, avg, max) = (5.156, 5.294, 5.519), stdev = 0.196
  CI (99.9%): [1.717, 8.871] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.354 ops/ms
# Warmup Iteration   2: 3.511 ops/ms
# Warmup Iteration   3: 4.347 ops/ms
Iteration   1: 4.675 ops/ms
Iteration   2: 4.802 ops/ms
Iteration   3: 4.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.737 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (4.675, 4.737, 4.802), stdev = 0.064
  CI (99.9%): [3.575, 5.899] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.565 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.600 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.993 ±(99.9%) 0.008 ms/op
Iteration   1: 5.913 ±(99.9%) 0.011 ms/op
Iteration   2: 5.786 ±(99.9%) 0.009 ms/op
Iteration   3: 5.964 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.888 ±(99.9%) 1.666 ms/op [Average]
  (min, avg, max) = (5.786, 5.888, 5.964), stdev = 0.091
  CI (99.9%): [4.222, 7.554] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.031 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.316 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.480 ±(99.9%) 0.012 ms/op
Iteration   1: 5.459 ±(99.9%) 0.011 ms/op
Iteration   2: 5.266 ±(99.9%) 0.018 ms/op
Iteration   3: 5.383 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.369 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (5.266, 5.369, 5.459), stdev = 0.097
  CI (99.9%): [3.594, 7.144] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.515 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.043 ±(99.9%) 0.010 ms/op
Iteration   1: 5.734 ±(99.9%) 0.010 ms/op
Iteration   2: 5.596 ±(99.9%) 0.007 ms/op
Iteration   3: 5.541 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.624 ±(99.9%) 1.819 ms/op [Average]
  (min, avg, max) = (5.541, 5.624, 5.734), stdev = 0.100
  CI (99.9%): [3.805, 7.443] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.508 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 8.444 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.378 ±(99.9%) 0.020 ms/op
Iteration   1: 6.513 ±(99.9%) 0.014 ms/op
Iteration   2: 6.549 ±(99.9%) 0.013 ms/op
Iteration   3: 6.450 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.504 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (6.450, 6.504, 6.549), stdev = 0.050
  CI (99.9%): [5.590, 7.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.419 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 7.573 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.290 ±(99.9%) 0.027 ms/op
Iteration   1: 5.976 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.671 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.430 ms/op
                 createUser·p0.95:   8.815 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  28.557 ms/op
                 createUser·p0.9999: 32.920 ms/op
                 createUser·p1.00:   34.734 ms/op

Iteration   2: 5.631 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.851 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  20.530 ms/op
                 createUser·p0.9999: 30.898 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   3: 5.663 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  29.094 ms/op
                 createUser·p0.9999: 36.307 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166697
  mean =      5.752 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 32620 
    [ 5.000,  7.500) = 123395 
    [ 7.500, 10.000) = 8008 
    [10.000, 12.500) = 1898 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     22.269 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     36.984 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.346 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 6.955 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.803 ±(99.9%) 0.024 ms/op
Iteration   1: 5.558 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.662 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.561 ms/op
                 existUser·p0.99:   10.977 ms/op
                 existUser·p0.999:  15.892 ms/op
                 existUser·p0.9999: 27.762 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 5.493 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.159 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  27.418 ms/op
                 existUser·p0.9999: 31.088 ms/op
                 existUser·p1.00:   31.556 ms/op

Iteration   3: 5.933 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   5.587 ms/op
                 existUser·p0.90:   7.348 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.960 ms/op
                 existUser·p0.999:  28.572 ms/op
                 existUser·p0.9999: 34.840 ms/op
                 existUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169526
  mean =      5.654 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 43598 
    [ 5.000,  7.500) = 115864 
    [ 7.500, 10.000) = 7110 
    [10.000, 12.500) = 2093 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     19.657 ms/op
     p(99.9900) =     32.314 ms/op
     p(99.9990) =     35.629 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.930 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.821 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.836 ±(99.9%) 0.023 ms/op
Iteration   1: 5.703 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.777 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   11.895 ms/op
                 getUser·p0.999:  17.988 ms/op
                 getUser·p0.9999: 25.492 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 5.573 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.848 ms/op
                 getUser·p0.99:   11.370 ms/op
                 getUser·p0.999:  25.330 ms/op
                 getUser·p0.9999: 30.491 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   3: 5.763 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.045 ms/op
                 getUser·p0.95:   7.922 ms/op
                 getUser·p0.99:   10.868 ms/op
                 getUser·p0.999:  29.362 ms/op
                 getUser·p0.9999: 34.614 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168893
  mean =      5.679 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 46322 
    [ 5.000,  7.500) = 111431 
    [ 7.500, 10.000) = 7807 
    [10.000, 12.500) = 2369 
    [12.500, 15.000) = 610 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     22.572 ms/op
     p(99.9900) =     33.107 ms/op
     p(99.9990) =     35.569 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 21.665 ±(99.9%) 0.385 ms/op
# Warmup Iteration   2: 9.160 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.024 ±(99.9%) 0.033 ms/op
Iteration   1: 6.730 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.367 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   13.512 ms/op
                 listUser·p0.999:  31.272 ms/op
                 listUser·p0.9999: 45.593 ms/op
                 listUser·p1.00:   48.169 ms/op

Iteration   2: 6.968 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.405 ms/op
                 listUser·p0.99:   14.300 ms/op
                 listUser·p0.999:  31.067 ms/op
                 listUser·p0.9999: 34.710 ms/op
                 listUser·p1.00:   37.749 ms/op

Iteration   3: 6.868 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   9.978 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  28.605 ms/op
                 listUser·p0.9999: 39.541 ms/op
                 listUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139965
  mean =      6.854 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2071 
    [ 5.000, 10.000) = 130917 
    [10.000, 15.000) = 6137 
    [15.000, 20.000) = 508 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 88 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      6.390 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =      9.994 ms/op
     p(99.0000) =     13.648 ms/op
     p(99.9000) =     30.573 ms/op
     p(99.9900) =     43.188 ms/op
     p(99.9990) =     48.064 ms/op
     p(99.9999) =     48.169 ms/op
    p(100.0000) =     48.169 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.498 ± 4.128  ops/ms
ClientPb.existUser                       thrpt       3   5.691 ± 1.961  ops/ms
ClientPb.getUser                         thrpt       3   5.294 ± 3.577  ops/ms
ClientPb.listUser                        thrpt       3   4.737 ± 1.162  ops/ms
ClientPb.createUser                       avgt       3   5.888 ± 1.666   ms/op
ClientPb.existUser                        avgt       3   5.369 ± 1.775   ms/op
ClientPb.getUser                          avgt       3   5.624 ± 1.819   ms/op
ClientPb.listUser                         avgt       3   6.504 ± 0.914   ms/op
ClientPb.createUser                     sample  166697   5.752 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.200           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  169526   5.654 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.799           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.657           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.176           ms/op
ClientPb.getUser                        sample  168893   5.679 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.077           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.370           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.572           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  139965   6.854 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.253           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.390           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.994           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.573           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.188           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.169           ms/op
