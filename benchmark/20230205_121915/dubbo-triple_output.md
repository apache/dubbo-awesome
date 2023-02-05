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
# Warmup Iteration   1: 1.848 ops/ms
# Warmup Iteration   2: 4.249 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.889 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.539 ±(99.9%) 6.547 ops/ms [Average]
  (min, avg, max) = (8.172, 8.539, 8.889), stdev = 0.359
  CI (99.9%): [1.992, 15.086] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.264 ±(99.9%) 5.571 ops/ms [Average]
  (min, avg, max) = (8.922, 9.264, 9.509), stdev = 0.305
  CI (99.9%): [3.694, 14.835] (assumes normal distribution)


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
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 7.976 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 9.059 ops/ms
Iteration   3: 8.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.775 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (8.597, 8.775, 9.059), stdev = 0.249
  CI (99.9%): [4.235, 13.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.490 ops/ms
# Warmup Iteration   3: 7.345 ops/ms
Iteration   1: 7.374 ops/ms
Iteration   2: 7.357 ops/ms
Iteration   3: 7.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.264 ±(99.9%) 3.224 ops/ms [Average]
  (min, avg, max) = (7.060, 7.264, 7.374), stdev = 0.177
  CI (99.9%): [4.040, 10.487] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.928 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.009 ms/op
Iteration   2: 4.320 ±(99.9%) 0.007 ms/op
Iteration   3: 4.176 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.172 ±(99.9%) 2.729 ms/op [Average]
  (min, avg, max) = (4.021, 4.172, 4.320), stdev = 0.150
  CI (99.9%): [1.443, 6.901] (assumes normal distribution)


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
# Warmup Iteration   1: 13.042 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.010 ms/op
Iteration   1: 3.850 ±(99.9%) 0.003 ms/op
Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
Iteration   3: 4.091 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.971 ±(99.9%) 2.204 ms/op [Average]
  (min, avg, max) = (3.850, 3.971, 4.091), stdev = 0.121
  CI (99.9%): [1.767, 6.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 15.414 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.009 ms/op
Iteration   1: 4.189 ±(99.9%) 0.009 ms/op
Iteration   2: 4.113 ±(99.9%) 0.006 ms/op
Iteration   3: 4.292 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.198 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (4.113, 4.198, 4.292), stdev = 0.089
  CI (99.9%): [2.565, 5.831] (assumes normal distribution)


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
# Warmup Iteration   1: 15.348 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
Iteration   1: 4.188 ±(99.9%) 0.009 ms/op
Iteration   2: 5.607 ±(99.9%) 0.004 ms/op
Iteration   3: 5.149 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.981 ±(99.9%) 13.209 ms/op [Average]
  (min, avg, max) = (4.188, 4.981, 5.607), stdev = 0.724
  CI (99.9%): [≈ 0, 18.190] (assumes normal distribution)


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
# Warmup Iteration   1: 13.508 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 7.153 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.013 ±(99.9%) 0.026 ms/op
Iteration   1: 4.317 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.991 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   6.160 ms/op
                 createUser·p0.99:   8.473 ms/op
                 createUser·p0.999:  15.152 ms/op
                 createUser·p0.9999: 38.339 ms/op
                 createUser·p1.00:   39.780 ms/op

Iteration   2: 3.422 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  21.809 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.495 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.982 ms/op
                 createUser·p0.999:  23.348 ms/op
                 createUser·p0.9999: 31.134 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 258984
  mean =      3.704 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2010 
    [ 2.500,  5.000) = 243836 
    [ 5.000,  7.500) = 10451 
    [ 7.500, 10.000) = 1868 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     21.104 ms/op
     p(99.9900) =     36.576 ms/op
     p(99.9990) =     39.101 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 14.665 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.025 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  20.062 ms/op
                 existUser·p0.9999: 24.218 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  12.985 ms/op
                 existUser·p0.9999: 24.129 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  10.772 ms/op
                 existUser·p0.9999: 26.360 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289078
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16722 
    [ 2.500,  5.000) = 265790 
    [ 5.000,  7.500) = 5324 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     25.303 ms/op
     p(99.9990) =     26.662 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 9.625 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.011 ms/op
Iteration   1: 3.438 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.304 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  14.335 ms/op
                 getUser·p0.9999: 25.384 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.184 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 30.557 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284390
  mean =      3.373 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2372 
    [ 2.500,  5.000) = 273963 
    [ 5.000,  7.500) = 6755 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.612 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     28.527 ms/op
     p(99.9990) =     31.183 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 10.320 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
Iteration   1: 4.158 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  19.335 ms/op
                 listUser·p0.9999: 24.825 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   2: 4.168 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.947 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 4.331 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.096 ms/op
                 listUser·p0.999:  16.142 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227410
  mean =      4.218 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 217551 
    [ 5.000,  7.500) = 6597 
    [ 7.500, 10.000) = 2260 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     16.279 ms/op
     p(99.9900) =     23.274 ms/op
     p(99.9990) =     25.273 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.539 ±  6.547  ops/ms
ClientPb.existUser                       thrpt       3   9.264 ±  5.571  ops/ms
ClientPb.getUser                         thrpt       3   8.775 ±  4.541  ops/ms
ClientPb.listUser                        thrpt       3   7.264 ±  3.224  ops/ms
ClientPb.createUser                       avgt       3   4.172 ±  2.729   ms/op
ClientPb.existUser                        avgt       3   3.971 ±  2.204   ms/op
ClientPb.getUser                          avgt       3   4.198 ±  1.633   ms/op
ClientPb.listUser                         avgt       3   4.981 ± 13.209   ms/op
ClientPb.createUser                     sample  258984   3.704 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.424            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.022            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.561            ms/op
ClientPb.createUser:createUser·p0.999   sample          21.104            ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.576            ms/op
ClientPb.createUser:createUser·p1.00    sample          39.780            ms/op
ClientPb.existUser                      sample  289078   3.320 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.630            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.128            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.468            ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.303            ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903            ms/op
ClientPb.getUser                        sample  284390   3.373 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.612            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.287            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.527            ms/op
ClientPb.getUser:getUser·p1.00          sample          31.326            ms/op
ClientPb.listUser                       sample  227410   4.218 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.964            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.012            ms/op
ClientPb.listUser:listUser·p0.999       sample          16.279            ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.274            ms/op
ClientPb.listUser:listUser·p1.00        sample          25.395            ms/op
