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
# Warmup Iteration   1: 2.435 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 9.361 ops/ms
Iteration   2: 9.378 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.478 ±(99.9%) 3.448 ops/ms [Average]
  (min, avg, max) = (9.361, 9.478, 9.696), stdev = 0.189
  CI (99.9%): [6.030, 12.927] (assumes normal distribution)


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
# Warmup Iteration   1: 3.137 ops/ms
# Warmup Iteration   2: 8.828 ops/ms
# Warmup Iteration   3: 9.266 ops/ms
Iteration   1: 10.037 ops/ms
Iteration   2: 9.858 ops/ms
Iteration   3: 9.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.900 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (9.806, 9.900, 10.037), stdev = 0.121
  CI (99.9%): [7.691, 12.110] (assumes normal distribution)


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
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 8.427 ops/ms
# Warmup Iteration   3: 9.163 ops/ms
Iteration   1: 9.435 ops/ms
Iteration   2: 9.571 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.447 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (9.335, 9.447, 9.571), stdev = 0.118
  CI (99.9%): [7.287, 11.607] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.881 ops/ms
# Warmup Iteration   2: 7.197 ops/ms
# Warmup Iteration   3: 7.554 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.956 ±(99.9%) 3.593 ops/ms [Average]
  (min, avg, max) = (7.748, 7.956, 8.140), stdev = 0.197
  CI (99.9%): [4.363, 11.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.502 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.007 ms/op
Iteration   1: 3.317 ±(99.9%) 0.010 ms/op
Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
Iteration   3: 3.365 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.364 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.317, 3.364, 3.408), stdev = 0.045
  CI (99.9%): [2.534, 4.193] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.459 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.005 ms/op
Iteration   1: 3.385 ±(99.9%) 0.004 ms/op
Iteration   2: 3.228 ±(99.9%) 0.009 ms/op
Iteration   3: 3.292 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.302 ±(99.9%) 1.441 ms/op [Average]
  (min, avg, max) = (3.228, 3.302, 3.385), stdev = 0.079
  CI (99.9%): [1.860, 4.743] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.004 ms/op
Iteration   1: 3.393 ±(99.9%) 0.011 ms/op
Iteration   2: 4.420 ±(99.9%) 0.006 ms/op
Iteration   3: 3.509 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.774 ±(99.9%) 10.265 ms/op [Average]
  (min, avg, max) = (3.393, 3.774, 4.420), stdev = 0.563
  CI (99.9%): [≈ 0, 14.039] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.491 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 4.038 ±(99.9%) 0.007 ms/op
Iteration   2: 3.925 ±(99.9%) 0.014 ms/op
Iteration   3: 4.049 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.004 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.925, 4.004, 4.049), stdev = 0.069
  CI (99.9%): [2.743, 5.266] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.441 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.011 ms/op
Iteration   1: 3.359 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  21.150 ms/op
                 createUser·p0.9999: 24.231 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  23.851 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.824 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 25.592 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279290
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9558 
    [ 2.500,  5.000) = 263273 
    [ 5.000,  7.500) = 5496 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.897 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.618 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  11.165 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.454 ms/op
                 existUser·p0.999:  10.667 ms/op
                 existUser·p0.9999: 27.946 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295444
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12818 
    [ 2.500,  5.000) = 277085 
    [ 5.000,  7.500) = 4875 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     26.229 ms/op
     p(99.9990) =     28.316 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.105 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  21.329 ms/op
                 getUser·p0.9999: 23.385 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  22.669 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  19.370 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280780
  mean =      3.419 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15315 
    [ 2.500,  5.000) = 259056 
    [ 5.000,  7.500) = 5378 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     19.668 ms/op
     p(99.9900) =     25.524 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.278 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
Iteration   1: 4.115 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.855 ms/op
                 listUser·p0.999:  25.887 ms/op
                 listUser·p0.9999: 29.080 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   2: 4.099 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  15.189 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 4.065 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.262 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 17.568 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234458
  mean =      4.093 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 225721 
    [ 5.000,  7.500) = 6042 
    [ 7.500, 10.000) = 1825 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.475 ms/op
     p(99.9900) =     28.526 ms/op
     p(99.9990) =     30.157 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.478 ±  3.448  ops/ms
ClientPb.existUser                       thrpt       3   9.900 ±  2.209  ops/ms
ClientPb.getUser                         thrpt       3   9.447 ±  2.160  ops/ms
ClientPb.listUser                        thrpt       3   7.956 ±  3.593  ops/ms
ClientPb.createUser                       avgt       3   3.364 ±  0.830   ms/op
ClientPb.existUser                        avgt       3   3.302 ±  1.441   ms/op
ClientPb.getUser                          avgt       3   3.774 ± 10.265   ms/op
ClientPb.listUser                         avgt       3   4.004 ±  1.261   ms/op
ClientPb.createUser                     sample  279290   3.433 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.180            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.481            ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.051            ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474            ms/op
ClientPb.existUser                      sample  295444   3.248 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.366            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456            ms/op
ClientPb.existUser:existUser·p0.999     sample          11.076            ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.229            ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443            ms/op
ClientPb.getUser                        sample  280780   3.419 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.668            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.524            ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164            ms/op
ClientPb.listUser                       sample  234458   4.093 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.718            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684            ms/op
ClientPb.listUser:listUser·p0.999       sample          16.475            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.526            ms/op
ClientPb.listUser:listUser·p1.00        sample          30.441            ms/op
