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
# Warmup Iteration   1: 2.403 ops/ms
# Warmup Iteration   2: 5.439 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.154 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.411 ±(99.9%) 4.971 ops/ms [Average]
  (min, avg, max) = (9.154, 9.411, 9.696), stdev = 0.272
  CI (99.9%): [4.440, 14.381] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.456 ops/ms
# Warmup Iteration   2: 9.408 ops/ms
# Warmup Iteration   3: 9.945 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.289 ops/ms
Iteration   3: 10.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.365 ±(99.9%) 3.153 ops/ms [Average]
  (min, avg, max) = (10.243, 10.365, 10.563), stdev = 0.173
  CI (99.9%): [7.212, 13.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.568 ops/ms
Iteration   1: 9.586 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.932 ±(99.9%) 5.666 ops/ms [Average]
  (min, avg, max) = (9.586, 9.932, 10.186), stdev = 0.311
  CI (99.9%): [4.266, 15.598] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 7.736 ops/ms
# Warmup Iteration   3: 8.236 ops/ms
Iteration   1: 8.368 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.477 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (8.368, 8.477, 8.587), stdev = 0.110
  CI (99.9%): [6.478, 10.477] (assumes normal distribution)


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
# Warmup Iteration   1: 8.163 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.004 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
Iteration   3: 3.235 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.157 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.114, 3.157, 3.235), stdev = 0.068
  CI (99.9%): [1.922, 4.393] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.281 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (3.036, 3.098, 3.176), stdev = 0.071
  CI (99.9%): [1.798, 4.398] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.568 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.001 ms/op
Iteration   1: 3.240 ±(99.9%) 0.006 ms/op
Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
Iteration   3: 3.262 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.148, 3.217, 3.262), stdev = 0.061
  CI (99.9%): [2.109, 4.324] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.579 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.008 ms/op
Iteration   2: 3.733 ±(99.9%) 0.008 ms/op
Iteration   3: 3.668 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 1.781 ms/op [Average]
  (min, avg, max) = (3.668, 3.754, 3.860), stdev = 0.098
  CI (99.9%): [1.973, 5.534] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.362 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  14.443 ms/op
                 createUser·p0.9999: 20.488 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 25.917 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.548 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  14.728 ms/op
                 createUser·p0.9999: 20.488 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295252
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25514 
    [ 2.500,  5.000) = 262182 
    [ 5.000,  7.500) = 6505 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     16.256 ms/op
     p(99.9900) =     24.460 ms/op
     p(99.9990) =     26.266 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 8.338 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 20.692 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.333 ms/op
                 existUser·p0.9999: 21.311 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.803 ms/op
                 existUser·p0.9999: 25.165 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294856
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22842 
    [ 2.500,  5.000) = 266106 
    [ 5.000,  7.500) = 5379 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.500 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     24.022 ms/op
     p(99.9990) =     25.331 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 8.282 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.011 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  17.935 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.426 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  18.112 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.476 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 30.454 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286860
  mean =      3.344 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6356 
    [ 2.500,  5.000) = 263516 
    [ 5.000,  7.500) = 15025 
    [ 7.500, 10.000) = 1357 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.354 ms/op
     p(99.9900) =     28.648 ms/op
     p(99.9990) =     31.199 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 9.141 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.799 ms/op
                 listUser·p0.9999: 23.252 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 3.826 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.049 ms/op
                 listUser·p0.9999: 15.182 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   3: 3.877 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 16.613 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251660
  mean =      3.812 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 242833 
    [ 5.000,  7.500) = 7021 
    [ 7.500, 10.000) = 1125 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     21.387 ms/op
     p(99.9990) =     24.325 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.411 ± 4.971  ops/ms
ClientPb.existUser                       thrpt       3  10.365 ± 3.153  ops/ms
ClientPb.getUser                         thrpt       3   9.932 ± 5.666  ops/ms
ClientPb.listUser                        thrpt       3   8.477 ± 1.999  ops/ms
ClientPb.createUser                       avgt       3   3.157 ± 1.236   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.300   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 1.108   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 1.781   ms/op
ClientPb.createUser                     sample  295252   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.647           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.256           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.739           ms/op
ClientPb.existUser                      sample  294856   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.500           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.699           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.022           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  286860   3.344 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.955           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.251           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.354           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  251660   3.812 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.249           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.582           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
