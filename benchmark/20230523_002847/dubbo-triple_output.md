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
# Warmup Iteration   1: 1.752 ops/ms
# Warmup Iteration   2: 3.924 ops/ms
# Warmup Iteration   3: 7.128 ops/ms
Iteration   1: 7.072 ops/ms
Iteration   2: 7.470 ops/ms
Iteration   3: 7.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.389 ±(99.9%) 5.199 ops/ms [Average]
  (min, avg, max) = (7.072, 7.389, 7.624), stdev = 0.285
  CI (99.9%): [2.190, 12.587] (assumes normal distribution)


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
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 6.771 ops/ms
# Warmup Iteration   3: 7.868 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.023 ±(99.9%) 6.469 ops/ms [Average]
  (min, avg, max) = (7.613, 8.023, 8.239), stdev = 0.355
  CI (99.9%): [1.553, 14.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 6.393 ops/ms
# Warmup Iteration   3: 7.435 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.900 ±(99.9%) 3.303 ops/ms [Average]
  (min, avg, max) = (7.691, 7.900, 8.006), stdev = 0.181
  CI (99.9%): [4.597, 11.204] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.917 ops/ms
# Warmup Iteration   2: 4.884 ops/ms
# Warmup Iteration   3: 6.336 ops/ms
Iteration   1: 6.567 ops/ms
Iteration   2: 6.602 ops/ms
Iteration   3: 6.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.665 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (6.567, 6.665, 6.826), stdev = 0.140
  CI (99.9%): [4.105, 9.224] (assumes normal distribution)


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
# Warmup Iteration   1: 13.457 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.004 ms/op
Iteration   1: 4.228 ±(99.9%) 0.010 ms/op
Iteration   2: 4.059 ±(99.9%) 0.006 ms/op
Iteration   3: 4.047 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.111 ±(99.9%) 1.838 ms/op [Average]
  (min, avg, max) = (4.047, 4.111, 4.228), stdev = 0.101
  CI (99.9%): [2.273, 5.949] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.021 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.006 ms/op
Iteration   1: 4.014 ±(99.9%) 0.008 ms/op
Iteration   2: 3.702 ±(99.9%) 0.011 ms/op
Iteration   3: 3.863 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.860 ±(99.9%) 2.841 ms/op [Average]
  (min, avg, max) = (3.702, 3.860, 4.014), stdev = 0.156
  CI (99.9%): [1.019, 6.700] (assumes normal distribution)


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
# Warmup Iteration   1: 13.091 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.007 ms/op
Iteration   1: 4.295 ±(99.9%) 0.008 ms/op
Iteration   2: 4.353 ±(99.9%) 0.008 ms/op
Iteration   3: 4.231 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.293 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (4.231, 4.293, 4.353), stdev = 0.061
  CI (99.9%): [3.182, 5.404] (assumes normal distribution)


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
# Warmup Iteration   1: 14.888 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.596 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.955 ±(99.9%) 0.006 ms/op
Iteration   1: 4.815 ±(99.9%) 0.008 ms/op
Iteration   2: 4.769 ±(99.9%) 0.014 ms/op
Iteration   3: 4.838 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.807 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (4.769, 4.807, 4.838), stdev = 0.035
  CI (99.9%): [4.168, 5.446] (assumes normal distribution)


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
# Warmup Iteration   1: 14.081 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.244 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.022 ms/op
Iteration   1: 4.266 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   8.258 ms/op
                 createUser·p0.999:  22.316 ms/op
                 createUser·p0.9999: 26.362 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 4.099 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  27.099 ms/op
                 createUser·p0.9999: 31.214 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 4.238 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.446 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  26.411 ms/op
                 createUser·p0.9999: 33.232 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228534
  mean =      4.200 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 207762 
    [ 5.000,  7.500) = 17593 
    [ 7.500, 10.000) = 1908 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     23.722 ms/op
     p(99.9900) =     31.369 ms/op
     p(99.9990) =     34.126 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 14.319 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.012 ms/op
Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 26.405 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.992 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  14.622 ms/op
                 existUser·p0.9999: 38.665 ms/op
                 existUser·p1.00:   39.256 ms/op

Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.036 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  29.288 ms/op
                 existUser·p0.9999: 31.587 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242034
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 257 
    [ 2.500,  5.000) = 226445 
    [ 5.000,  7.500) = 13425 
    [ 7.500, 10.000) = 1384 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     14.564 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     39.091 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 12.916 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.800 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.014 ms/op
Iteration   1: 4.242 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  13.454 ms/op
                 getUser·p0.9999: 27.475 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  26.490 ms/op
                 getUser·p0.9999: 32.104 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   3: 4.070 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  15.319 ms/op
                 getUser·p0.9999: 34.144 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233560
  mean =      4.107 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 214104 
    [ 5.000,  7.500) = 16016 
    [ 7.500, 10.000) = 2290 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     15.425 ms/op
     p(99.9900) =     32.768 ms/op
     p(99.9990) =     35.366 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 16.099 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 5.945 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.885 ±(99.9%) 0.015 ms/op
Iteration   1: 4.780 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.129 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 31.052 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 4.801 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  23.069 ms/op
                 listUser·p0.9999: 27.166 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 4.657 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.558 ms/op
                 listUser·p0.999:  16.635 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202122
  mean =      4.745 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 165771 
    [ 5.000,  7.500) = 31061 
    [ 7.500, 10.000) = 4034 
    [10.000, 12.500) = 668 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.975 ms/op
     p(99.9000) =     22.602 ms/op
     p(99.9900) =     29.070 ms/op
     p(99.9990) =     31.485 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.389 ± 5.199  ops/ms
ClientPb.existUser                       thrpt       3   8.023 ± 6.469  ops/ms
ClientPb.getUser                         thrpt       3   7.900 ± 3.303  ops/ms
ClientPb.listUser                        thrpt       3   6.665 ± 2.559  ops/ms
ClientPb.createUser                       avgt       3   4.111 ± 1.838   ms/op
ClientPb.existUser                        avgt       3   3.860 ± 2.841   ms/op
ClientPb.getUser                          avgt       3   4.293 ± 1.111   ms/op
ClientPb.listUser                         avgt       3   4.807 ± 0.639   ms/op
ClientPb.createUser                     sample  228534   4.200 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.446           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.077           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.722           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  242034   3.967 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.487           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.256           ms/op
ClientPb.getUser                        sample  233560   4.107 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.526           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.425           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.768           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  202122   4.745 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.718           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.975           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.602           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.070           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.687           ms/op
