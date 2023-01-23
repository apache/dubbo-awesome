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
# Warmup Iteration   1: 2.775 ops/ms
# Warmup Iteration   2: 6.642 ops/ms
# Warmup Iteration   3: 9.478 ops/ms
Iteration   1: 10.081 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 10.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.029 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (9.935, 10.029, 10.081), stdev = 0.082
  CI (99.9%): [8.540, 11.519] (assumes normal distribution)


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
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 9.066 ops/ms
# Warmup Iteration   3: 10.078 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.088 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (9.918, 10.088, 10.244), stdev = 0.164
  CI (99.9%): [7.100, 13.075] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 9.279 ops/ms
# Warmup Iteration   3: 9.414 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.155 ±(99.9%) 5.455 ops/ms [Average]
  (min, avg, max) = (9.974, 10.155, 10.500), stdev = 0.299
  CI (99.9%): [4.700, 15.610] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ops/ms
# Warmup Iteration   2: 7.594 ops/ms
# Warmup Iteration   3: 8.373 ops/ms
Iteration   1: 8.587 ops/ms
Iteration   2: 8.487 ops/ms
Iteration   3: 8.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.586 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (8.487, 8.586, 8.682), stdev = 0.098
  CI (99.9%): [6.803, 10.368] (assumes normal distribution)


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
# Warmup Iteration   1: 8.551 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.004 ms/op
Iteration   1: 3.245 ±(99.9%) 0.006 ms/op
Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
Iteration   3: 3.106 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.189 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.106, 3.189, 3.245), stdev = 0.073
  CI (99.9%): [1.850, 4.527] (assumes normal distribution)


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
# Warmup Iteration   1: 7.497 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.005 ms/op
Iteration   1: 3.126 ±(99.9%) 0.006 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.058 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (3.018, 3.058, 3.126), stdev = 0.059
  CI (99.9%): [1.987, 4.130] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.113 ±(99.9%) 0.005 ms/op
Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
Iteration   3: 3.082 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.114 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (3.082, 3.114, 3.148), stdev = 0.033
  CI (99.9%): [2.507, 3.722] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.007 ms/op
Iteration   1: 3.778 ±(99.9%) 0.004 ms/op
Iteration   2: 3.635 ±(99.9%) 0.009 ms/op
Iteration   3: 3.707 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.635, 3.707, 3.778), stdev = 0.071
  CI (99.9%): [2.407, 5.006] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.992 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.012 ms/op
Iteration   1: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  19.037 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 23.588 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  15.106 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303797
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23353 
    [ 2.500,  5.000) = 276189 
    [ 5.000,  7.500) = 3353 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     15.496 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     24.240 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 23.547 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 22.272 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311940
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25343 
    [ 2.500,  5.000) = 283087 
    [ 5.000,  7.500) = 2877 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.758 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 8.517 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
Iteration   1: 3.303 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  14.183 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  11.802 ms/op
                 getUser·p0.9999: 20.717 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299835
  mean =      3.201 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16798 
    [ 2.500,  5.000) = 276225 
    [ 5.000,  7.500) = 5977 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     27.100 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 9.600 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.011 ms/op
Iteration   1: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  16.196 ms/op
                 listUser·p0.9999: 20.374 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.663 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 14.926 ms/op
                 listUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258264
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 250691 
    [ 5.000,  7.500) = 5784 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     19.138 ms/op
     p(99.9990) =     20.832 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.029 ± 1.490  ops/ms
ClientPb.existUser                       thrpt       3  10.088 ± 2.987  ops/ms
ClientPb.getUser                         thrpt       3  10.155 ± 5.455  ops/ms
ClientPb.listUser                        thrpt       3   8.586 ± 1.782  ops/ms
ClientPb.createUser                       avgt       3   3.189 ± 1.338   ms/op
ClientPb.existUser                        avgt       3   3.058 ± 1.071   ms/op
ClientPb.getUser                          avgt       3   3.114 ± 0.608   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 1.299   ms/op
ClientPb.createUser                     sample  303797   3.158 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.850           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  311940   3.076 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.736           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.632           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  299835   3.201 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.057           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.100           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  258264   3.718 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.580           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.138           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
