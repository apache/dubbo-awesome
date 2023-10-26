# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.046 ops/ms
# Warmup Iteration   2: 2.290 ops/ms
# Warmup Iteration   3: 5.284 ops/ms
Iteration   1: 5.461 ops/ms
Iteration   2: 5.686 ops/ms
Iteration   3: 5.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.632 ±(99.9%) 2.771 ops/ms [Average]
  (min, avg, max) = (5.461, 5.632, 5.750), stdev = 0.152
  CI (99.9%): [2.861, 8.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.656 ops/ms
# Warmup Iteration   2: 4.399 ops/ms
# Warmup Iteration   3: 5.683 ops/ms
Iteration   1: 5.823 ops/ms
Iteration   2: 5.743 ops/ms
Iteration   3: 5.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.809 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (5.743, 5.809, 5.862), stdev = 0.061
  CI (99.9%): [4.703, 6.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
# Warmup Iteration   2: 4.735 ops/ms
# Warmup Iteration   3: 5.658 ops/ms
Iteration   1: 5.735 ops/ms
Iteration   2: 5.751 ops/ms
Iteration   3: 5.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.690 ±(99.9%) 1.675 ops/ms [Average]
  (min, avg, max) = (5.585, 5.690, 5.751), stdev = 0.092
  CI (99.9%): [4.015, 7.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.470 ops/ms
# Warmup Iteration   2: 3.849 ops/ms
# Warmup Iteration   3: 4.584 ops/ms
Iteration   1: 4.705 ops/ms
Iteration   2: 5.083 ops/ms
Iteration   3: 5.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.954 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (4.705, 4.954, 5.083), stdev = 0.216
  CI (99.9%): [1.018, 8.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.913 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 6.863 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.787 ±(99.9%) 0.011 ms/op
Iteration   1: 5.811 ±(99.9%) 0.012 ms/op
Iteration   2: 5.558 ±(99.9%) 0.013 ms/op
Iteration   3: 5.705 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.691 ±(99.9%) 2.316 ms/op [Average]
  (min, avg, max) = (5.558, 5.691, 5.811), stdev = 0.127
  CI (99.9%): [3.375, 8.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 18.483 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.235 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.008 ms/op
Iteration   1: 5.577 ±(99.9%) 0.008 ms/op
Iteration   2: 5.516 ±(99.9%) 0.008 ms/op
Iteration   3: 5.621 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.571 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (5.516, 5.571, 5.621), stdev = 0.053
  CI (99.9%): [4.606, 6.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 20.413 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.164 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.846 ±(99.9%) 0.007 ms/op
Iteration   1: 5.676 ±(99.9%) 0.008 ms/op
Iteration   2: 5.387 ±(99.9%) 0.014 ms/op
Iteration   3: 5.660 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.574 ±(99.9%) 2.961 ms/op [Average]
  (min, avg, max) = (5.387, 5.574, 5.676), stdev = 0.162
  CI (99.9%): [2.614, 8.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.891 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 8.410 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.528 ±(99.9%) 0.013 ms/op
Iteration   1: 6.643 ±(99.9%) 0.012 ms/op
Iteration   2: 6.514 ±(99.9%) 0.012 ms/op
Iteration   3: 6.426 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.528 ±(99.9%) 1.988 ms/op [Average]
  (min, avg, max) = (6.426, 6.528, 6.643), stdev = 0.109
  CI (99.9%): [4.540, 8.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.192 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.105 ±(99.9%) 0.029 ms/op
Iteration   1: 5.700 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   11.667 ms/op
                 createUser·p0.999:  26.929 ms/op
                 createUser·p0.9999: 31.521 ms/op
                 createUser·p1.00:   32.342 ms/op

Iteration   2: 5.786 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.307 ms/op
                 createUser·p0.95:   8.602 ms/op
                 createUser·p0.99:   11.829 ms/op
                 createUser·p0.999:  16.968 ms/op
                 createUser·p0.9999: 29.595 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 5.761 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  29.492 ms/op
                 createUser·p0.9999: 32.776 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166837
  mean =      5.749 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 48632 
    [ 5.000,  7.500) = 104080 
    [ 7.500, 10.000) = 10344 
    [10.000, 12.500) = 2552 
    [12.500, 15.000) = 732 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     24.581 ms/op
     p(99.9900) =     31.664 ms/op
     p(99.9990) =     33.074 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.012 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 6.515 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.688 ±(99.9%) 0.023 ms/op
Iteration   1: 5.297 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  18.459 ms/op
                 existUser·p0.9999: 29.916 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 5.295 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  24.163 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 5.216 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  26.761 ms/op
                 existUser·p0.9999: 36.665 ms/op
                 existUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182165
  mean =      5.269 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 97651 
    [ 5.000,  7.500) = 74198 
    [ 7.500, 10.000) = 7547 
    [10.000, 12.500) = 1858 
    [12.500, 15.000) = 476 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     19.836 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     38.474 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.178 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.253 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.880 ±(99.9%) 0.024 ms/op
Iteration   1: 5.879 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   9.110 ms/op
                 getUser·p0.99:   14.336 ms/op
                 getUser·p0.999:  26.866 ms/op
                 getUser·p0.9999: 31.418 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   2: 5.606 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.734 ms/op
                 getUser·p0.999:  25.589 ms/op
                 getUser·p0.9999: 28.440 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 5.637 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   11.180 ms/op
                 getUser·p0.999:  16.302 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168251
  mean =      5.705 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 56580 
    [ 5.000,  7.500) = 97250 
    [ 7.500, 10.000) = 10079 
    [10.000, 12.500) = 2574 
    [12.500, 15.000) = 1011 
    [15.000, 17.500) = 420 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     25.149 ms/op
     p(99.9900) =     34.156 ms/op
     p(99.9990) =     34.645 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.816 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 8.726 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.145 ±(99.9%) 0.033 ms/op
Iteration   1: 7.086 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.570 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.732 ms/op
                 listUser·p0.99:   15.881 ms/op
                 listUser·p0.999:  29.786 ms/op
                 listUser·p0.9999: 33.226 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   2: 7.308 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   6.595 ms/op
                 listUser·p0.90:   10.027 ms/op
                 listUser·p0.95:   11.551 ms/op
                 listUser·p0.99:   15.925 ms/op
                 listUser·p0.999:  34.651 ms/op
                 listUser·p0.9999: 53.166 ms/op
                 listUser·p1.00:   53.543 ms/op

Iteration   3: 6.951 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.469 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  36.378 ms/op
                 listUser·p0.9999: 43.883 ms/op
                 listUser·p1.00:   44.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 134859
  mean =      7.112 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2664 
    [ 5.000, 10.000) = 121919 
    [10.000, 15.000) = 8771 
    [15.000, 20.000) = 1027 
    [20.000, 25.000) = 194 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 42 
    [40.000, 45.000) = 22 
    [45.000, 50.000) = 18 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      6.513 ms/op
     p(90.0000) =      9.339 ms/op
     p(95.0000) =     10.928 ms/op
     p(99.0000) =     15.188 ms/op
     p(99.9000) =     32.575 ms/op
     p(99.9900) =     50.530 ms/op
     p(99.9990) =     53.520 ms/op
     p(99.9999) =     53.543 ms/op
    p(100.0000) =     53.543 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.632 ± 2.771  ops/ms
ClientPb.existUser                       thrpt       3   5.809 ± 1.106  ops/ms
ClientPb.getUser                         thrpt       3   5.690 ± 1.675  ops/ms
ClientPb.listUser                        thrpt       3   4.954 ± 3.936  ops/ms
ClientPb.createUser                       avgt       3   5.691 ± 2.316   ms/op
ClientPb.existUser                        avgt       3   5.571 ± 0.965   ms/op
ClientPb.getUser                          avgt       3   5.574 ± 2.961   ms/op
ClientPb.listUser                         avgt       3   6.528 ± 1.988   ms/op
ClientPb.createUser                     sample  166837   5.749 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.311           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.234           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.471           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.731           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  182165   5.269 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.750           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.836           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.717           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.797           ms/op
ClientPb.getUser                        sample  168251   5.705 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.552           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.149           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  134859   7.112 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.220           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.339           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.928           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.188           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.575           ms/op
ClientPb.listUser:listUser·p0.9999      sample          50.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          53.543           ms/op
