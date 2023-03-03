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
# Warmup Iteration   1: 1.124 ops/ms
# Warmup Iteration   2: 2.672 ops/ms
# Warmup Iteration   3: 5.582 ops/ms
Iteration   1: 5.802 ops/ms
Iteration   2: 5.967 ops/ms
Iteration   3: 6.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.943 ±(99.9%) 2.380 ops/ms [Average]
  (min, avg, max) = (5.802, 5.943, 6.060), stdev = 0.130
  CI (99.9%): [3.563, 8.323] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.628 ops/ms
# Warmup Iteration   2: 4.740 ops/ms
# Warmup Iteration   3: 5.948 ops/ms
Iteration   1: 6.368 ops/ms
Iteration   2: 6.272 ops/ms
Iteration   3: 6.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.311 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (6.272, 6.311, 6.368), stdev = 0.050
  CI (99.9%): [5.397, 7.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 5.040 ops/ms
# Warmup Iteration   3: 5.774 ops/ms
Iteration   1: 5.672 ops/ms
Iteration   2: 5.713 ops/ms
Iteration   3: 6.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.825 ±(99.9%) 4.185 ops/ms [Average]
  (min, avg, max) = (5.672, 5.825, 6.089), stdev = 0.229
  CI (99.9%): [1.639, 10.010] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.564 ops/ms
# Warmup Iteration   2: 4.161 ops/ms
# Warmup Iteration   3: 5.054 ops/ms
Iteration   1: 4.980 ops/ms
Iteration   2: 5.316 ops/ms
Iteration   3: 5.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.216 ±(99.9%) 3.748 ops/ms [Average]
  (min, avg, max) = (4.980, 5.216, 5.353), stdev = 0.205
  CI (99.9%): [1.469, 8.964] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.795 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 6.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.841 ±(99.9%) 0.013 ms/op
Iteration   1: 5.495 ±(99.9%) 0.023 ms/op
Iteration   2: 5.554 ±(99.9%) 0.017 ms/op
Iteration   3: 5.349 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.466 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (5.349, 5.466, 5.554), stdev = 0.106
  CI (99.9%): [3.539, 7.392] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.202 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.080 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.012 ms/op
Iteration   1: 5.345 ±(99.9%) 0.011 ms/op
Iteration   2: 5.207 ±(99.9%) 0.016 ms/op
Iteration   3: 5.286 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.279 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (5.207, 5.279, 5.345), stdev = 0.069
  CI (99.9%): [4.015, 6.543] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.382 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.667 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.731 ±(99.9%) 0.007 ms/op
Iteration   1: 5.489 ±(99.9%) 0.010 ms/op
Iteration   2: 5.371 ±(99.9%) 0.014 ms/op
Iteration   3: 5.417 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.426 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (5.371, 5.426, 5.489), stdev = 0.059
  CI (99.9%): [4.344, 6.507] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.285 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.575 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.719 ±(99.9%) 0.015 ms/op
Iteration   1: 6.513 ±(99.9%) 0.015 ms/op
Iteration   2: 6.251 ±(99.9%) 0.011 ms/op
Iteration   3: 6.386 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.383 ±(99.9%) 2.392 ms/op [Average]
  (min, avg, max) = (6.251, 6.383, 6.513), stdev = 0.131
  CI (99.9%): [3.991, 8.776] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.185 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.561 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.032 ±(99.9%) 0.031 ms/op
Iteration   1: 5.423 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   11.441 ms/op
                 createUser·p0.999:  23.762 ms/op
                 createUser·p0.9999: 26.611 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 5.394 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.635 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 31.230 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   3: 5.565 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.265 ms/op
                 createUser·p0.99:   12.042 ms/op
                 createUser·p0.999:  28.100 ms/op
                 createUser·p0.9999: 30.089 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175694
  mean =      5.460 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 78582 
    [ 5.000,  7.500) = 85888 
    [ 7.500, 10.000) = 8304 
    [10.000, 12.500) = 1729 
    [12.500, 15.000) = 650 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     24.505 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     31.511 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.583 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.706 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.421 ±(99.9%) 0.021 ms/op
Iteration   1: 5.408 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.881 ms/op
                 existUser·p0.95:   8.167 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  24.521 ms/op
                 existUser·p0.9999: 28.484 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   2: 5.342 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.982 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  24.321 ms/op
                 existUser·p0.9999: 29.077 ms/op
                 existUser·p1.00:   31.097 ms/op

Iteration   3: 5.419 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  26.443 ms/op
                 existUser·p0.9999: 39.590 ms/op
                 existUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177975
  mean =      5.390 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 89059 
    [ 5.000, 10.000) = 85993 
    [10.000, 15.000) = 2407 
    [15.000, 20.000) = 306 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     24.544 ms/op
     p(99.9900) =     31.202 ms/op
     p(99.9990) =     40.450 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.911 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 6.558 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.019 ms/op
Iteration   1: 5.526 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.404 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   7.111 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  17.606 ms/op
                 getUser·p0.9999: 24.983 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 5.509 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  23.389 ms/op
                 getUser·p0.9999: 27.536 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 5.620 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   12.586 ms/op
                 getUser·p0.999:  27.657 ms/op
                 getUser·p0.9999: 34.380 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172951
  mean =      5.551 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 70849 
    [ 5.000,  7.500) = 89490 
    [ 7.500, 10.000) = 9141 
    [10.000, 12.500) = 2262 
    [12.500, 15.000) = 680 
    [15.000, 17.500) = 248 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     21.039 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.604 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.248 ±(99.9%) 0.371 ms/op
# Warmup Iteration   2: 8.525 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.581 ±(99.9%) 0.031 ms/op
Iteration   1: 6.601 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   12.685 ms/op
                 listUser·p0.999:  27.592 ms/op
                 listUser·p0.9999: 29.816 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 6.631 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.894 ms/op
                 listUser·p0.999:  30.886 ms/op
                 listUser·p0.9999: 33.840 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   3: 6.456 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.993 ms/op
                 listUser·p0.999:  26.214 ms/op
                 listUser·p0.9999: 29.984 ms/op
                 listUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146270
  mean =      6.562 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 6592 
    [ 5.000,  7.500) = 117094 
    [ 7.500, 10.000) = 16272 
    [10.000, 12.500) = 4386 
    [12.500, 15.000) = 1193 
    [15.000, 17.500) = 313 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      6.128 ms/op
     p(90.0000) =      8.298 ms/op
     p(95.0000) =      9.716 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     27.951 ms/op
     p(99.9900) =     33.317 ms/op
     p(99.9990) =     34.789 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.943 ± 2.380  ops/ms
ClientPb.existUser                       thrpt       3   6.311 ± 0.915  ops/ms
ClientPb.getUser                         thrpt       3   5.825 ± 4.185  ops/ms
ClientPb.listUser                        thrpt       3   5.216 ± 3.748  ops/ms
ClientPb.createUser                       avgt       3   5.466 ± 1.927   ms/op
ClientPb.existUser                        avgt       3   5.279 ± 1.264   ms/op
ClientPb.getUser                          avgt       3   5.426 ± 1.081   ms/op
ClientPb.listUser                         avgt       3   6.383 ± 2.392   ms/op
ClientPb.createUser                     sample  175694   5.460 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.241           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.905           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.370           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.505           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.441           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  177975   5.390 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.370           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.544           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.202           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.501           ms/op
ClientPb.getUser                        sample  172951   5.551 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.313           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.159           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.518           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  146270   6.562 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.716           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.951           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.317           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.062           ms/op
