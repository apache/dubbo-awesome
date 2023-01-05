# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.977 ops/ms
# Warmup Iteration   2: 2.163 ops/ms
# Warmup Iteration   3: 4.543 ops/ms
Iteration   1: 5.003 ops/ms
Iteration   2: 5.224 ops/ms
Iteration   3: 5.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.169 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (5.003, 5.169, 5.280), stdev = 0.146
  CI (99.9%): [2.499, 7.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.441 ops/ms
# Warmup Iteration   2: 4.630 ops/ms
# Warmup Iteration   3: 5.765 ops/ms
Iteration   1: 5.899 ops/ms
Iteration   2: 5.826 ops/ms
Iteration   3: 5.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.807 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (5.695, 5.807, 5.899), stdev = 0.104
  CI (99.9%): [3.917, 7.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 4.220 ops/ms
# Warmup Iteration   3: 5.209 ops/ms
Iteration   1: 5.258 ops/ms
Iteration   2: 5.418 ops/ms
Iteration   3: 5.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.367 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (5.258, 5.367, 5.426), stdev = 0.095
  CI (99.9%): [3.637, 7.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 3.356 ops/ms
# Warmup Iteration   3: 4.567 ops/ms
Iteration   1: 4.502 ops/ms
Iteration   2: 4.698 ops/ms
Iteration   3: 4.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.697 ±(99.9%) 3.551 ops/ms [Average]
  (min, avg, max) = (4.502, 4.697, 4.891), stdev = 0.195
  CI (99.9%): [1.146, 8.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.462 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.323 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.092 ±(99.9%) 0.010 ms/op
Iteration   1: 6.185 ±(99.9%) 0.010 ms/op
Iteration   2: 5.988 ±(99.9%) 0.026 ms/op
Iteration   3: 5.894 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.022 ±(99.9%) 2.702 ms/op [Average]
  (min, avg, max) = (5.894, 6.022, 6.185), stdev = 0.148
  CI (99.9%): [3.320, 8.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.396 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.723 ±(99.9%) 0.010 ms/op
Iteration   1: 5.765 ±(99.9%) 0.013 ms/op
Iteration   2: 5.496 ±(99.9%) 0.013 ms/op
Iteration   3: 5.732 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.664 ±(99.9%) 2.674 ms/op [Average]
  (min, avg, max) = (5.496, 5.664, 5.765), stdev = 0.147
  CI (99.9%): [2.990, 8.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.964 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.018 ±(99.9%) 0.007 ms/op
Iteration   1: 5.916 ±(99.9%) 0.007 ms/op
Iteration   2: 6.113 ±(99.9%) 0.009 ms/op
Iteration   3: 5.837 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.955 ±(99.9%) 2.598 ms/op [Average]
  (min, avg, max) = (5.837, 5.955, 6.113), stdev = 0.142
  CI (99.9%): [3.357, 8.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.607 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 8.691 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.955 ±(99.9%) 0.012 ms/op
Iteration   1: 6.608 ±(99.9%) 0.013 ms/op
Iteration   2: 7.024 ±(99.9%) 0.012 ms/op
Iteration   3: 6.575 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.735 ±(99.9%) 4.564 ms/op [Average]
  (min, avg, max) = (6.575, 6.735, 7.024), stdev = 0.250
  CI (99.9%): [2.171, 11.300] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.930 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.611 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.399 ±(99.9%) 0.034 ms/op
Iteration   1: 5.898 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.504 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   12.141 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 31.326 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   2: 6.034 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.650 ms/op
                 createUser·p0.50:   5.669 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  27.395 ms/op
                 createUser·p0.9999: 35.940 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   3: 6.002 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.593 ms/op
                 createUser·p0.50:   5.693 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.197 ms/op
                 createUser·p0.999:  29.483 ms/op
                 createUser·p0.9999: 34.255 ms/op
                 createUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160461
  mean =      5.977 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 39855 
    [ 5.000,  7.500) = 103351 
    [ 7.500, 10.000) = 13579 
    [10.000, 12.500) = 2617 
    [12.500, 15.000) = 658 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.054 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     27.349 ms/op
     p(99.9900) =     34.329 ms/op
     p(99.9990) =     36.840 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 21.166 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 7.969 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.063 ±(99.9%) 0.025 ms/op
Iteration   1: 5.998 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   5.652 ms/op
                 existUser·p0.90:   7.881 ms/op
                 existUser·p0.95:   9.110 ms/op
                 existUser·p0.99:   11.944 ms/op
                 existUser·p0.999:  17.138 ms/op
                 existUser·p0.9999: 25.701 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 5.645 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.511 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.062 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  26.716 ms/op
                 existUser·p0.9999: 32.538 ms/op
                 existUser·p1.00:   34.275 ms/op

Iteration   3: 5.800 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   5.472 ms/op
                 existUser·p0.90:   7.266 ms/op
                 existUser·p0.95:   8.389 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  27.476 ms/op
                 existUser·p0.9999: 31.440 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 165145
  mean =      5.811 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 51864 
    [ 5.000,  7.500) = 97767 
    [ 7.500, 10.000) = 12090 
    [10.000, 12.500) = 2532 
    [12.500, 15.000) = 518 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.281 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     31.244 ms/op
     p(99.9990) =     34.019 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.187 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.586 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.194 ±(99.9%) 0.026 ms/op
Iteration   1: 6.178 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   5.997 ms/op
                 getUser·p0.90:   7.774 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  28.606 ms/op
                 getUser·p0.9999: 38.053 ms/op
                 getUser·p1.00:   38.994 ms/op

Iteration   2: 6.038 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.691 ms/op
                 getUser·p0.50:   5.685 ms/op
                 getUser·p0.90:   7.692 ms/op
                 getUser·p0.95:   9.110 ms/op
                 getUser·p0.99:   12.981 ms/op
                 getUser·p0.999:  27.657 ms/op
                 getUser·p0.9999: 30.750 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   3: 5.870 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.953 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   7.274 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   10.306 ms/op
                 getUser·p0.999:  14.975 ms/op
                 getUser·p0.9999: 34.246 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159211
  mean =      6.026 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 36545 
    [ 5.000,  7.500) = 105901 
    [ 7.500, 10.000) = 13223 
    [10.000, 12.500) = 2337 
    [12.500, 15.000) = 645 
    [15.000, 17.500) = 263 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     26.599 ms/op
     p(99.9900) =     36.050 ms/op
     p(99.9990) =     38.800 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.376 ±(99.9%) 0.378 ms/op
# Warmup Iteration   2: 8.822 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 7.131 ±(99.9%) 0.033 ms/op
Iteration   1: 6.853 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.461 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  28.389 ms/op
                 listUser·p0.9999: 32.812 ms/op
                 listUser·p1.00:   33.194 ms/op

Iteration   2: 6.889 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  30.330 ms/op
                 listUser·p0.9999: 46.727 ms/op
                 listUser·p1.00:   48.824 ms/op

Iteration   3: 6.786 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.699 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  26.299 ms/op
                 listUser·p0.9999: 36.475 ms/op
                 listUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140186
  mean =      6.842 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4632 
    [ 5.000, 10.000) = 129746 
    [10.000, 15.000) = 5119 
    [15.000, 20.000) = 368 
    [20.000, 25.000) = 79 
    [25.000, 30.000) = 124 
    [30.000, 35.000) = 75 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.716 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      8.585 ms/op
     p(95.0000) =      9.716 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     28.377 ms/op
     p(99.9900) =     41.549 ms/op
     p(99.9990) =     48.087 ms/op
     p(99.9999) =     48.824 ms/op
    p(100.0000) =     48.824 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.169 ± 2.670  ops/ms
ClientPb.existUser                       thrpt       3   5.807 ± 1.890  ops/ms
ClientPb.getUser                         thrpt       3   5.367 ± 1.730  ops/ms
ClientPb.listUser                        thrpt       3   4.697 ± 3.551  ops/ms
ClientPb.createUser                       avgt       3   6.022 ± 2.702   ms/op
ClientPb.existUser                        avgt       3   5.664 ± 2.674   ms/op
ClientPb.getUser                          avgt       3   5.955 ± 2.598   ms/op
ClientPb.listUser                         avgt       3   6.735 ± 4.564   ms/op
ClientPb.createUser                     sample  160461   5.977 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.054           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.602           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.602           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.551           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.329           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  165145   5.811 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.782           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.414           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.454           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.281           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.298           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.244           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  159211   6.026 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.567           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.846           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.599           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.050           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.994           ms/op
ClientPb.listUser                       sample  140186   6.842 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.716           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.829           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.549           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.824           ms/op
