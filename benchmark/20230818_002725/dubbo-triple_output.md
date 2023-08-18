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
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 5.884 ops/ms
# Warmup Iteration   3: 8.740 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.032 ops/ms
Iteration   3: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.168 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (9.032, 9.168, 9.257), stdev = 0.120
  CI (99.9%): [6.982, 11.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.497 ops/ms
Iteration   1: 9.586 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 9.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.740 ±(99.9%) 3.992 ops/ms [Average]
  (min, avg, max) = (9.586, 9.740, 9.990), stdev = 0.219
  CI (99.9%): [5.748, 13.731] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 8.380 ops/ms
# Warmup Iteration   3: 8.635 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 9.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.227 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (9.034, 9.227, 9.432), stdev = 0.199
  CI (99.9%): [5.588, 12.866] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 7.739 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.770 ±(99.9%) 0.972 ops/ms [Average]
  (min, avg, max) = (7.739, 7.770, 7.832), stdev = 0.053
  CI (99.9%): [6.799, 8.742] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.938 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.007 ms/op
Iteration   1: 3.441 ±(99.9%) 0.012 ms/op
Iteration   2: 3.513 ±(99.9%) 0.005 ms/op
Iteration   3: 3.458 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.471 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.441, 3.471, 3.513), stdev = 0.037
  CI (99.9%): [2.787, 4.154] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.636 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.003 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op
Iteration   2: 3.343 ±(99.9%) 0.006 ms/op
Iteration   3: 3.345 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.343, 3.350, 3.362), stdev = 0.011
  CI (99.9%): [3.154, 3.546] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.720 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.004 ms/op
Iteration   1: 3.621 ±(99.9%) 0.008 ms/op
Iteration   2: 3.620 ±(99.9%) 0.005 ms/op
Iteration   3: 3.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.581 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.500, 3.581, 3.621), stdev = 0.069
  CI (99.9%): [2.314, 4.847] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.940 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.009 ms/op
Iteration   1: 4.125 ±(99.9%) 0.010 ms/op
Iteration   2: 4.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.972 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.098 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (3.972, 4.098, 4.195), stdev = 0.114
  CI (99.9%): [2.017, 6.178] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.625 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.012 ms/op
Iteration   1: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  19.690 ms/op
                 createUser·p0.9999: 24.601 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.526 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.401 ms/op
                 createUser·p0.999:  21.673 ms/op
                 createUser·p0.9999: 25.157 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  24.065 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276554
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7835 
    [ 2.500,  5.000) = 260996 
    [ 5.000,  7.500) = 6003 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     20.298 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.227 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.429 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.009 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  20.095 ms/op
                 existUser·p0.9999: 28.059 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.653 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  13.604 ms/op
                 existUser·p0.9999: 25.570 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  16.652 ms/op
                 existUser·p0.9999: 28.497 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284482
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15492 
    [ 2.500,  5.000) = 262456 
    [ 5.000,  7.500) = 5282 
    [ 7.500, 10.000) = 881 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     27.478 ms/op
     p(99.9990) =     29.136 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.013 ms/op
Iteration   1: 3.538 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   7.950 ms/op
                 getUser·p0.999:  18.842 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  19.614 ms/op
                 getUser·p0.9999: 27.750 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  9.523 ms/op
                 getUser·p0.9999: 28.670 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272495
  mean =      3.521 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10767 
    [ 2.500,  5.000) = 250764 
    [ 5.000,  7.500) = 8866 
    [ 7.500, 10.000) = 1605 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.869 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.278 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.792 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.014 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  20.499 ms/op
                 listUser·p0.9999: 24.185 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.174 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  15.751 ms/op
                 listUser·p0.9999: 17.607 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.469 ms/op
                 listUser·p0.999:  15.397 ms/op
                 listUser·p0.9999: 20.053 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236099
  mean =      4.064 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 225950 
    [ 5.000,  7.500) = 7295 
    [ 7.500, 10.000) = 1842 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     22.701 ms/op
     p(99.9990) =     24.356 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.168 ± 2.186  ops/ms
ClientPb.existUser                       thrpt       3   9.740 ± 3.992  ops/ms
ClientPb.getUser                         thrpt       3   9.227 ± 3.639  ops/ms
ClientPb.listUser                        thrpt       3   7.770 ± 0.972  ops/ms
ClientPb.createUser                       avgt       3   3.471 ± 0.684   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 0.196   ms/op
ClientPb.getUser                          avgt       3   3.581 ± 1.266   ms/op
ClientPb.listUser                         avgt       3   4.098 ± 2.080   ms/op
ClientPb.createUser                     sample  276554   3.473 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.233           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.444           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  284482   3.372 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  272495   3.521 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.389           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.869           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  236099   4.064 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.318           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.701           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
