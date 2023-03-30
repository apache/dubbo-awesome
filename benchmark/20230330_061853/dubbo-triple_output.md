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
# Warmup Iteration   1: 1.863 ops/ms
# Warmup Iteration   2: 4.403 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 8.894 ops/ms
Iteration   2: 8.985 ops/ms
Iteration   3: 9.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.992 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (8.894, 8.992, 9.097), stdev = 0.101
  CI (99.9%): [7.146, 10.839] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 8.478 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 9.386 ops/ms
Iteration   2: 9.941 ops/ms
Iteration   3: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.631 ±(99.9%) 5.167 ops/ms [Average]
  (min, avg, max) = (9.386, 9.631, 9.941), stdev = 0.283
  CI (99.9%): [4.464, 14.799] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ops/ms
# Warmup Iteration   2: 8.527 ops/ms
# Warmup Iteration   3: 8.851 ops/ms
Iteration   1: 9.321 ops/ms
Iteration   2: 9.322 ops/ms
Iteration   3: 9.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.345 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (9.321, 9.345, 9.391), stdev = 0.040
  CI (99.9%): [8.616, 10.073] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.534 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 8.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.987 ±(99.9%) 4.539 ops/ms [Average]
  (min, avg, max) = (7.786, 7.987, 8.265), stdev = 0.249
  CI (99.9%): [3.448, 12.526] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.857 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.007 ms/op
Iteration   1: 3.348 ±(99.9%) 0.010 ms/op
Iteration   2: 3.472 ±(99.9%) 0.009 ms/op
Iteration   3: 3.357 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (3.348, 3.393, 3.472), stdev = 0.069
  CI (99.9%): [2.130, 4.655] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.425 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.006 ms/op
Iteration   1: 3.338 ±(99.9%) 0.007 ms/op
Iteration   2: 3.264 ±(99.9%) 0.011 ms/op
Iteration   3: 3.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.227, 3.276, 3.338), stdev = 0.056
  CI (99.9%): [2.251, 4.301] (assumes normal distribution)


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
# Warmup Iteration   1: 10.112 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.004 ms/op
Iteration   1: 3.499 ±(99.9%) 0.007 ms/op
Iteration   2: 3.396 ±(99.9%) 0.003 ms/op
Iteration   3: 3.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.396, 3.455, 3.499), stdev = 0.053
  CI (99.9%): [2.487, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 11.981 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.013 ms/op
Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
Iteration   2: 4.075 ±(99.9%) 0.005 ms/op
Iteration   3: 3.971 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.011 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.971, 4.011, 4.075), stdev = 0.055
  CI (99.9%): [3.000, 5.023] (assumes normal distribution)


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
# Warmup Iteration   1: 10.585 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.014 ms/op
Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  21.896 ms/op
                 createUser·p0.9999: 24.697 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  21.490 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278988
  mean =      3.435 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7408 
    [ 2.500,  5.000) = 262791 
    [ 5.000,  7.500) = 7805 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     20.841 ms/op
     p(99.9900) =     27.823 ms/op
     p(99.9990) =     29.007 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  12.433 ms/op
                 existUser·p0.9999: 23.382 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  16.993 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  18.174 ms/op
                 existUser·p0.9999: 25.974 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290712
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11781 
    [ 2.500,  5.000) = 273365 
    [ 5.000,  7.500) = 4372 
    [ 7.500, 10.000) = 595 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     17.737 ms/op
     p(99.9900) =     24.901 ms/op
     p(99.9990) =     26.480 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 9.483 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  19.642 ms/op
                 getUser·p0.9999: 22.166 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  21.660 ms/op
                 getUser·p0.9999: 25.887 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.461 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  20.774 ms/op
                 getUser·p0.9999: 45.410 ms/op
                 getUser·p1.00:   47.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278721
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270870 
    [ 5.000, 10.000) = 7312 
    [10.000, 15.000) = 251 
    [15.000, 20.000) = 9 
    [20.000, 25.000) = 219 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     31.863 ms/op
     p(99.9990) =     47.214 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


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
# Warmup Iteration   1: 11.078 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.014 ms/op
Iteration   1: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.855 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  20.124 ms/op
                 listUser·p0.9999: 23.715 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.177 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.692 ms/op
                 listUser·p0.9999: 36.418 ms/op
                 listUser·p1.00:   39.125 ms/op

Iteration   3: 4.044 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.483 ms/op
                 listUser·p0.999:  14.859 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236926
  mean =      4.049 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 227588 
    [ 5.000,  7.500) = 7473 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.855 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     17.664 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     38.849 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.992 ± 1.847  ops/ms
ClientPb.existUser                       thrpt       3   9.631 ± 5.167  ops/ms
ClientPb.getUser                         thrpt       3   9.345 ± 0.729  ops/ms
ClientPb.listUser                        thrpt       3   7.987 ± 4.539  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 1.262   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 0.968   ms/op
ClientPb.listUser                         avgt       3   4.011 ± 1.012   ms/op
ClientPb.createUser                     sample  278988   3.435 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.526           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.841           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.823           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  290712   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.901           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  278721   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.863           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.645           ms/op
ClientPb.listUser                       sample  236926   4.049 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.168           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.125           ms/op
