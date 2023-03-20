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
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 9.401 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.413 ±(99.9%) 4.217 ops/ms [Average]
  (min, avg, max) = (9.188, 9.413, 9.650), stdev = 0.231
  CI (99.9%): [5.196, 13.630] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 8.384 ops/ms
# Warmup Iteration   3: 9.457 ops/ms
Iteration   1: 9.747 ops/ms
Iteration   2: 9.880 ops/ms
Iteration   3: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.827 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (9.747, 9.827, 9.880), stdev = 0.070
  CI (99.9%): [8.545, 11.109] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 8.882 ops/ms
Iteration   1: 9.504 ops/ms
Iteration   2: 9.618 ops/ms
Iteration   3: 9.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.489 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (9.345, 9.489, 9.618), stdev = 0.137
  CI (99.9%): [6.987, 11.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.797 ops/ms
# Warmup Iteration   2: 7.275 ops/ms
# Warmup Iteration   3: 8.168 ops/ms
Iteration   1: 8.098 ops/ms
Iteration   2: 7.721 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.012 ±(99.9%) 4.721 ops/ms [Average]
  (min, avg, max) = (7.721, 8.012, 8.216), stdev = 0.259
  CI (99.9%): [3.291, 12.733] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.004 ms/op
Iteration   1: 3.385 ±(99.9%) 0.003 ms/op
Iteration   2: 3.429 ±(99.9%) 0.007 ms/op
Iteration   3: 3.375 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.375, 3.396, 3.429), stdev = 0.029
  CI (99.9%): [2.869, 3.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.696 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.005 ms/op
Iteration   1: 3.166 ±(99.9%) 0.010 ms/op
Iteration   2: 3.284 ±(99.9%) 0.011 ms/op
Iteration   3: 3.234 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.228 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.166, 3.228, 3.284), stdev = 0.059
  CI (99.9%): [2.152, 4.303] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.166 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.005 ms/op
Iteration   1: 3.311 ±(99.9%) 0.008 ms/op
Iteration   2: 3.445 ±(99.9%) 0.004 ms/op
Iteration   3: 3.377 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.377 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (3.311, 3.377, 3.445), stdev = 0.067
  CI (99.9%): [2.149, 4.606] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.508 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.008 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
Iteration   2: 3.916 ±(99.9%) 0.012 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.919 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.870, 3.919, 3.972), stdev = 0.051
  CI (99.9%): [2.988, 4.850] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.476 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  12.247 ms/op
                 createUser·p0.9999: 24.029 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.505 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 25.621 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.441 ms/op
                 createUser·p0.9999: 28.522 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283744
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11731 
    [ 2.500,  5.000) = 265765 
    [ 5.000,  7.500) = 5247 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     19.571 ms/op
     p(99.9900) =     27.337 ms/op
     p(99.9990) =     29.207 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.902 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.011 ms/op
Iteration   1: 3.271 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  9.621 ms/op
                 existUser·p0.9999: 23.313 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 27.824 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  11.297 ms/op
                 existUser·p0.9999: 25.896 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293868
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6355 
    [ 2.500,  5.000) = 281843 
    [ 5.000,  7.500) = 4661 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     10.760 ms/op
     p(99.9900) =     26.759 ms/op
     p(99.9990) =     27.986 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.012 ms/op
Iteration   1: 3.515 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  21.525 ms/op
                 getUser·p0.9999: 28.760 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.832 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  23.189 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.357 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280574
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8686 
    [ 2.500,  5.000) = 262749 
    [ 5.000,  7.500) = 8059 
    [ 7.500, 10.000) = 768 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     10.362 ms/op
     p(99.9900) =     27.485 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.104 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  18.114 ms/op
                 listUser·p0.9999: 23.889 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  15.682 ms/op
                 listUser·p0.9999: 18.124 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.912 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 16.478 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241162
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 232402 
    [ 5.000,  7.500) = 6298 
    [ 7.500, 10.000) = 1623 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     23.229 ms/op
     p(99.9990) =     24.354 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.413 ± 4.217  ops/ms
ClientPb.existUser                       thrpt       3   9.827 ± 1.282  ops/ms
ClientPb.getUser                         thrpt       3   9.489 ± 2.502  ops/ms
ClientPb.listUser                        thrpt       3   8.012 ± 4.721  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   3.228 ± 1.075   ms/op
ClientPb.getUser                          avgt       3   3.377 ± 1.228   ms/op
ClientPb.listUser                         avgt       3   3.919 ± 0.931   ms/op
ClientPb.createUser                     sample  283744   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.329           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.571           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.786           ms/op
ClientPb.existUser                      sample  293868   3.264 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.221           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.760           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.759           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  280574   3.421 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.270           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.362           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.485           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  241162   3.981 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.229           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
