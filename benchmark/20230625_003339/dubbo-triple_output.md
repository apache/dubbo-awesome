# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.501 ops/ms
# Warmup Iteration   2: 6.148 ops/ms
# Warmup Iteration   3: 8.839 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 9.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.705 ±(99.9%) 1.773 ops/ms [Average]
  (min, avg, max) = (9.621, 9.705, 9.811), stdev = 0.097
  CI (99.9%): [7.932, 11.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.546 ops/ms
# Warmup Iteration   2: 9.176 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.306 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (10.238, 10.306, 10.428), stdev = 0.105
  CI (99.9%): [8.383, 12.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ops/ms
# Warmup Iteration   2: 8.123 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 9.826 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.054 ±(99.9%) 4.250 ops/ms [Average]
  (min, avg, max) = (9.826, 10.054, 10.291), stdev = 0.233
  CI (99.9%): [5.803, 14.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 6.954 ops/ms
# Warmup Iteration   3: 8.596 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.395 ±(99.9%) 3.394 ops/ms [Average]
  (min, avg, max) = (8.222, 8.395, 8.592), stdev = 0.186
  CI (99.9%): [5.001, 11.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.597 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.003 ms/op
Iteration   1: 3.172 ±(99.9%) 0.004 ms/op
Iteration   2: 3.127 ±(99.9%) 0.005 ms/op
Iteration   3: 3.105 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.135 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.105, 3.135, 3.172), stdev = 0.034
  CI (99.9%): [2.509, 3.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 2.941 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.015 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (2.941, 3.015, 3.072), stdev = 0.067
  CI (99.9%): [1.795, 4.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.419 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.002 ms/op
Iteration   1: 3.265 ±(99.9%) 0.003 ms/op
Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
Iteration   3: 3.266 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.273 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.265, 3.273, 3.289), stdev = 0.014
  CI (99.9%): [3.027, 3.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.472 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.005 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
Iteration   2: 3.732 ±(99.9%) 0.007 ms/op
Iteration   3: 3.676 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.713 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.676, 3.713, 3.732), stdev = 0.032
  CI (99.9%): [3.123, 4.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.098 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 24.840 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  20.341 ms/op
                 createUser·p0.9999: 23.491 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 35.979 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297323
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22962 
    [ 2.500,  5.000) = 268955 
    [ 5.000,  7.500) = 4558 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.714 ms/op
                 existUser·p0.9999: 22.341 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  12.003 ms/op
                 existUser·p0.9999: 24.910 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  17.248 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300093
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23295 
    [ 2.500,  5.000) = 273028 
    [ 5.000,  7.500) = 2807 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     15.268 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.549 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.238 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.761 ms/op
                 getUser·p0.999:  13.856 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.687 ms/op
                 getUser·p0.9999: 23.736 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.206 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 25.527 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297227
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9883 
    [ 2.500,  5.000) = 280702 
    [ 5.000,  7.500) = 5580 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.722 ms/op
                 listUser·p0.9999: 21.876 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.866 ms/op
                 listUser·p0.9999: 16.256 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   3: 3.759 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.186 ms/op
                 listUser·p0.999:  12.206 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251926
  mean =      3.810 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 244035 
    [ 5.000,  7.500) = 5506 
    [ 7.500, 10.000) = 1681 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     22.834 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.705 ± 1.773  ops/ms
ClientPb.existUser                       thrpt       3  10.306 ± 1.923  ops/ms
ClientPb.getUser                         thrpt       3  10.054 ± 4.250  ops/ms
ClientPb.listUser                        thrpt       3   8.395 ± 3.394  ops/ms
ClientPb.createUser                       avgt       3   3.135 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   3.015 ± 1.220   ms/op
ClientPb.getUser                          avgt       3   3.273 ± 0.246   ms/op
ClientPb.listUser                         avgt       3   3.713 ± 0.590   ms/op
ClientPb.createUser                     sample  297323   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.810           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.586           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  300093   3.197 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.268           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  297227   3.227 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.746           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.952           ms/op
ClientPb.listUser                       sample  251926   3.810 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.845           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.004           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.134           ms/op
