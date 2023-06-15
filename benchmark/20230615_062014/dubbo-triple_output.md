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
# Warmup Iteration   1: 1.297 ops/ms
# Warmup Iteration   2: 3.133 ops/ms
# Warmup Iteration   3: 6.172 ops/ms
Iteration   1: 6.487 ops/ms
Iteration   2: 6.495 ops/ms
Iteration   3: 6.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.604 ±(99.9%) 3.567 ops/ms [Average]
  (min, avg, max) = (6.487, 6.604, 6.830), stdev = 0.196
  CI (99.9%): [3.037, 10.171] (assumes normal distribution)


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
# Warmup Iteration   1: 2.068 ops/ms
# Warmup Iteration   2: 5.904 ops/ms
# Warmup Iteration   3: 6.592 ops/ms
Iteration   1: 6.695 ops/ms
Iteration   2: 7.047 ops/ms
Iteration   3: 6.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.868 ±(99.9%) 3.209 ops/ms [Average]
  (min, avg, max) = (6.695, 6.868, 7.047), stdev = 0.176
  CI (99.9%): [3.659, 10.076] (assumes normal distribution)


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
# Warmup Iteration   1: 1.961 ops/ms
# Warmup Iteration   2: 5.307 ops/ms
# Warmup Iteration   3: 6.600 ops/ms
Iteration   1: 6.083 ops/ms
Iteration   2: 6.468 ops/ms
Iteration   3: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.404 ±(99.9%) 5.366 ops/ms [Average]
  (min, avg, max) = (6.083, 6.404, 6.661), stdev = 0.294
  CI (99.9%): [1.038, 11.770] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 4.846 ops/ms
# Warmup Iteration   3: 5.359 ops/ms
Iteration   1: 5.668 ops/ms
Iteration   2: 5.198 ops/ms
Iteration   3: 5.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.530 ±(99.9%) 5.272 ops/ms [Average]
  (min, avg, max) = (5.198, 5.530, 5.724), stdev = 0.289
  CI (99.9%): [0.258, 10.802] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.673 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.085 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.331 ±(99.9%) 0.015 ms/op
Iteration   1: 4.957 ±(99.9%) 0.013 ms/op
Iteration   2: 4.966 ±(99.9%) 0.014 ms/op
Iteration   3: 5.099 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.007 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (4.957, 5.007, 5.099), stdev = 0.080
  CI (99.9%): [3.557, 6.458] (assumes normal distribution)


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
# Warmup Iteration   1: 12.527 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.017 ms/op
Iteration   1: 4.737 ±(99.9%) 0.009 ms/op
Iteration   2: 4.526 ±(99.9%) 0.009 ms/op
Iteration   3: 4.525 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.596 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (4.525, 4.596, 4.737), stdev = 0.122
  CI (99.9%): [2.368, 6.824] (assumes normal distribution)


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
# Warmup Iteration   1: 14.730 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.426 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.825 ±(99.9%) 0.012 ms/op
Iteration   2: 4.911 ±(99.9%) 0.016 ms/op
Iteration   3: 4.610 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.782 ±(99.9%) 2.829 ms/op [Average]
  (min, avg, max) = (4.610, 4.782, 4.911), stdev = 0.155
  CI (99.9%): [1.953, 7.611] (assumes normal distribution)


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
# Warmup Iteration   1: 17.119 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.434 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.022 ms/op
Iteration   1: 5.631 ±(99.9%) 0.022 ms/op
Iteration   2: 5.820 ±(99.9%) 0.014 ms/op
Iteration   3: 5.809 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.753 ±(99.9%) 1.934 ms/op [Average]
  (min, avg, max) = (5.631, 5.753, 5.820), stdev = 0.106
  CI (99.9%): [3.820, 7.687] (assumes normal distribution)


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
# Warmup Iteration   1: 15.076 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.019 ms/op
Iteration   1: 5.067 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  22.362 ms/op
                 createUser·p0.9999: 28.982 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 4.831 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.562 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  15.396 ms/op
                 createUser·p0.9999: 32.060 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   3: 4.916 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.554 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  27.555 ms/op
                 createUser·p0.9999: 32.932 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 194356
  mean =      4.936 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 121026 
    [ 5.000,  7.500) = 68770 
    [ 7.500, 10.000) = 3096 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     24.777 ms/op
     p(99.9900) =     32.066 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 12.876 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.253 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.045 ±(99.9%) 0.018 ms/op
Iteration   1: 4.681 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  21.976 ms/op
                 existUser·p0.9999: 28.322 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 4.705 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.013 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  16.288 ms/op
                 existUser·p0.9999: 27.696 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 4.608 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   9.060 ms/op
                 existUser·p0.999:  18.174 ms/op
                 existUser·p0.9999: 32.113 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 205694
  mean =      4.664 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 134 
    [ 2.500,  5.000) = 156836 
    [ 5.000,  7.500) = 44753 
    [ 7.500, 10.000) = 2905 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     21.352 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     32.467 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 16.788 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.816 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.233 ±(99.9%) 0.017 ms/op
Iteration   1: 4.928 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.351 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.994 ms/op
                 getUser·p0.999:  19.249 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 4.942 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  23.790 ms/op
                 getUser·p0.9999: 27.673 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 5.125 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 29.017 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192072
  mean =      4.997 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 120821 
    [ 5.000,  7.500) = 65018 
    [ 7.500, 10.000) = 4736 
    [10.000, 12.500) = 869 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     21.952 ms/op
     p(99.9900) =     27.944 ms/op
     p(99.9990) =     29.389 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 15.886 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.739 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.750 ±(99.9%) 0.023 ms/op
Iteration   1: 5.945 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  25.074 ms/op
                 listUser·p0.9999: 28.741 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 5.753 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.487 ms/op
                 listUser·p0.99:   10.723 ms/op
                 listUser·p0.999:  24.969 ms/op
                 listUser·p0.9999: 26.899 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   3: 5.659 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 24.250 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 165862
  mean =      5.783 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 33157 
    [ 5.000,  7.500) = 123871 
    [ 7.500, 10.000) = 6388 
    [10.000, 12.500) = 1369 
    [12.500, 15.000) = 454 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     27.735 ms/op
     p(99.9990) =     29.413 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.604 ± 3.567  ops/ms
ClientPb.existUser                       thrpt       3   6.868 ± 3.209  ops/ms
ClientPb.getUser                         thrpt       3   6.404 ± 5.366  ops/ms
ClientPb.listUser                        thrpt       3   5.530 ± 5.272  ops/ms
ClientPb.createUser                       avgt       3   5.007 ± 1.450   ms/op
ClientPb.existUser                        avgt       3   4.596 ± 2.228   ms/op
ClientPb.getUser                          avgt       3   4.782 ± 2.829   ms/op
ClientPb.listUser                         avgt       3   5.753 ± 1.934   ms/op
ClientPb.createUser                     sample  194356   4.936 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.847           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.066           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  205694   4.664 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.778           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.316           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.667           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.228           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.096           ms/op
ClientPb.getUser                        sample  192072   4.997 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.503           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.952           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.944           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  165862   5.783 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.183           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.735           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.147           ms/op
