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
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 4.128 ops/ms
# Warmup Iteration   3: 7.413 ops/ms
Iteration   1: 7.612 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.948 ±(99.9%) 5.494 ops/ms [Average]
  (min, avg, max) = (7.612, 7.948, 8.194), stdev = 0.301
  CI (99.9%): [2.454, 13.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.207 ops/ms
# Warmup Iteration   2: 7.437 ops/ms
# Warmup Iteration   3: 8.164 ops/ms
Iteration   1: 8.586 ops/ms
Iteration   2: 8.636 ops/ms
Iteration   3: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.607 ±(99.9%) 0.469 ops/ms [Average]
  (min, avg, max) = (8.586, 8.607, 8.636), stdev = 0.026
  CI (99.9%): [8.138, 9.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 6.634 ops/ms
# Warmup Iteration   3: 7.806 ops/ms
Iteration   1: 7.904 ops/ms
Iteration   2: 8.252 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.224 ±(99.9%) 5.584 ops/ms [Average]
  (min, avg, max) = (7.904, 8.224, 8.515), stdev = 0.306
  CI (99.9%): [2.640, 13.808] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 5.536 ops/ms
# Warmup Iteration   3: 6.531 ops/ms
Iteration   1: 7.043 ops/ms
Iteration   2: 6.873 ops/ms
Iteration   3: 6.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.967 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (6.873, 6.967, 7.043), stdev = 0.087
  CI (99.9%): [5.388, 8.545] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.413 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.005 ms/op
Iteration   1: 4.038 ±(99.9%) 0.008 ms/op
Iteration   2: 3.923 ±(99.9%) 0.004 ms/op
Iteration   3: 3.952 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.971 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.923, 3.971, 4.038), stdev = 0.060
  CI (99.9%): [2.881, 5.061] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.765 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.004 ms/op
Iteration   1: 3.644 ±(99.9%) 0.004 ms/op
Iteration   2: 3.603 ±(99.9%) 0.006 ms/op
Iteration   3: 3.644 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.630 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.603, 3.630, 3.644), stdev = 0.024
  CI (99.9%): [3.199, 4.061] (assumes normal distribution)


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
# Warmup Iteration   1: 12.387 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.003 ms/op
Iteration   1: 3.803 ±(99.9%) 0.006 ms/op
Iteration   2: 3.787 ±(99.9%) 0.006 ms/op
Iteration   3: 3.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.858 ±(99.9%) 1.986 ms/op [Average]
  (min, avg, max) = (3.787, 3.858, 3.983), stdev = 0.109
  CI (99.9%): [1.872, 5.844] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.035 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.017 ±(99.9%) 0.006 ms/op
Iteration   1: 4.873 ±(99.9%) 0.007 ms/op
Iteration   2: 4.676 ±(99.9%) 0.006 ms/op
Iteration   3: 4.665 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.738 ±(99.9%) 2.128 ms/op [Average]
  (min, avg, max) = (4.665, 4.738, 4.873), stdev = 0.117
  CI (99.9%): [2.610, 6.866] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.967 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.020 ms/op
Iteration   1: 3.960 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.210 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 26.015 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.948 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  25.264 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.527 ms/op
                 createUser·p0.999:  15.704 ms/op
                 createUser·p0.9999: 31.326 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244607
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1096 
    [ 2.500,  5.000) = 232044 
    [ 5.000,  7.500) = 9028 
    [ 7.500, 10.000) = 1624 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.495 ms/op
     p(99.9000) =     21.902 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     32.000 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.077 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.014 ms/op
Iteration   1: 3.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  13.745 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.916 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  16.413 ms/op
                 existUser·p0.9999: 38.973 ms/op
                 existUser·p1.00:   40.370 ms/op

Iteration   3: 3.955 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   8.020 ms/op
                 existUser·p0.999:  29.506 ms/op
                 existUser·p0.9999: 37.028 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245510
  mean =      3.908 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229786 
    [ 5.000, 10.000) = 14856 
    [10.000, 15.000) = 540 
    [15.000, 20.000) = 61 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 89 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 59 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     22.199 ms/op
     p(99.9900) =     37.188 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.367 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  16.841 ms/op
                 getUser·p0.9999: 25.555 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 3.960 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   8.098 ms/op
                 getUser·p0.999:  23.503 ms/op
                 getUser·p0.9999: 28.815 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 4.077 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  10.730 ms/op
                 getUser·p0.9999: 34.941 ms/op
                 getUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240347
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 325 
    [ 2.500,  5.000) = 224989 
    [ 5.000,  7.500) = 11903 
    [ 7.500, 10.000) = 2235 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     17.713 ms/op
     p(99.9900) =     33.878 ms/op
     p(99.9990) =     36.331 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 14.949 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.223 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.870 ±(99.9%) 0.020 ms/op
Iteration   1: 5.127 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  26.846 ms/op
                 listUser·p0.9999: 29.156 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 4.787 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.277 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 4.605 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  18.683 ms/op
                 listUser·p0.9999: 22.221 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198571
  mean =      4.830 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 152727 
    [ 5.000,  7.500) = 39657 
    [ 7.500, 10.000) = 4244 
    [10.000, 12.500) = 1182 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.688 ms/op
     p(99.0000) =      9.933 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     28.026 ms/op
     p(99.9990) =     29.558 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.948 ± 5.494  ops/ms
ClientPb.existUser                       thrpt       3   8.607 ± 0.469  ops/ms
ClientPb.getUser                         thrpt       3   8.224 ± 5.584  ops/ms
ClientPb.listUser                        thrpt       3   6.967 ± 1.578  ops/ms
ClientPb.createUser                       avgt       3   3.971 ± 1.090   ms/op
ClientPb.existUser                        avgt       3   3.630 ± 0.431   ms/op
ClientPb.getUser                          avgt       3   3.858 ± 1.986   ms/op
ClientPb.listUser                         avgt       3   4.738 ± 2.128   ms/op
ClientPb.createUser                     sample  244607   3.923 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.495           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.902           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.721           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  245510   3.908 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.769           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.199           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.188           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.370           ms/op
ClientPb.getUser                        sample  240347   3.991 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.020           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.713           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.878           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.962           ms/op
ClientPb.listUser                       sample  198571   4.830 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.101           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.688           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.933           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.655           ms/op
