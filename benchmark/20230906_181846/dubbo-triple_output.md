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
# Warmup Iteration   1: 2.203 ops/ms
# Warmup Iteration   2: 5.704 ops/ms
# Warmup Iteration   3: 8.305 ops/ms
Iteration   1: 8.950 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 8.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.010 ±(99.9%) 1.856 ops/ms [Average]
  (min, avg, max) = (8.950, 9.010, 9.128), stdev = 0.102
  CI (99.9%): [7.154, 10.867] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.339 ops/ms
# Warmup Iteration   2: 8.747 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.245 ops/ms
Iteration   2: 9.555 ops/ms
Iteration   3: 9.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.325 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (9.174, 9.325, 9.555), stdev = 0.203
  CI (99.9%): [5.630, 13.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 8.324 ops/ms
# Warmup Iteration   3: 8.933 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.409 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.318 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (9.204, 9.318, 9.409), stdev = 0.104
  CI (99.9%): [7.419, 11.216] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 7.620 ops/ms
Iteration   1: 7.628 ops/ms
Iteration   2: 7.573 ops/ms
Iteration   3: 7.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.639 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (7.573, 7.639, 7.714), stdev = 0.071
  CI (99.9%): [6.341, 8.936] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.611 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.005 ms/op
Iteration   1: 3.511 ±(99.9%) 0.005 ms/op
Iteration   2: 3.453 ±(99.9%) 0.005 ms/op
Iteration   3: 3.420 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.461 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.420, 3.461, 3.511), stdev = 0.046
  CI (99.9%): [2.619, 4.304] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.755 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.003 ms/op
Iteration   1: 3.392 ±(99.9%) 0.003 ms/op
Iteration   2: 3.339 ±(99.9%) 0.005 ms/op
Iteration   3: 3.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.412 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.339, 3.412, 3.505), stdev = 0.085
  CI (99.9%): [1.856, 4.968] (assumes normal distribution)


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
# Warmup Iteration   1: 9.161 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.003 ms/op
Iteration   1: 3.485 ±(99.9%) 0.004 ms/op
Iteration   2: 3.549 ±(99.9%) 0.002 ms/op
Iteration   3: 3.635 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.556 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (3.485, 3.556, 3.635), stdev = 0.075
  CI (99.9%): [2.189, 4.924] (assumes normal distribution)


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
# Warmup Iteration   1: 11.748 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.011 ms/op
Iteration   1: 4.135 ±(99.9%) 0.009 ms/op
Iteration   2: 4.117 ±(99.9%) 0.012 ms/op
Iteration   3: 4.157 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.136 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (4.117, 4.136, 4.157), stdev = 0.020
  CI (99.9%): [3.775, 4.498] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.394 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.014 ms/op
Iteration   1: 3.534 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  22.138 ms/op
                 createUser·p0.9999: 25.721 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 3.437 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  22.739 ms/op
                 createUser·p0.9999: 27.855 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.105 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.953 ms/op
                 createUser·p0.999:  20.622 ms/op
                 createUser·p0.9999: 32.408 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273359
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12146 
    [ 2.500,  5.000) = 251184 
    [ 5.000,  7.500) = 8411 
    [ 7.500, 10.000) = 868 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     32.984 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 9.153 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  21.125 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 26.710 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.358 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  24.243 ms/op
                 existUser·p0.9999: 29.310 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282220
  mean =      3.400 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7079 
    [ 2.500,  5.000) = 267382 
    [ 5.000,  7.500) = 6358 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     27.878 ms/op
     p(99.9990) =     30.455 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 10.480 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.011 ms/op
Iteration   1: 3.582 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  21.126 ms/op
                 getUser·p0.9999: 25.627 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.590 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.580 ms/op
                 getUser·p0.999:  23.160 ms/op
                 getUser·p0.9999: 32.715 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   3: 3.497 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.312 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 42.009 ms/op
                 getUser·p1.00:   42.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269801
  mean =      3.556 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 258382 
    [ 5.000, 10.000) = 10714 
    [10.000, 15.000) = 413 
    [15.000, 20.000) = 10 
    [20.000, 25.000) = 152 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     20.781 ms/op
     p(99.9900) =     40.371 ms/op
     p(99.9990) =     42.422 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


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
# Warmup Iteration   1: 9.724 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.014 ms/op
Iteration   1: 4.181 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 25.998 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 4.195 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.998 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.192 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229068
  mean =      4.189 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 217968 
    [ 5.000,  7.500) = 7315 
    [ 7.500, 10.000) = 2680 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     24.939 ms/op
     p(99.9990) =     27.441 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.010 ± 1.856  ops/ms
ClientPb.existUser                       thrpt       3   9.325 ± 3.695  ops/ms
ClientPb.getUser                         thrpt       3   9.318 ± 1.899  ops/ms
ClientPb.listUser                        thrpt       3   7.639 ± 1.298  ops/ms
ClientPb.createUser                       avgt       3   3.461 ± 0.843   ms/op
ClientPb.existUser                        avgt       3   3.412 ± 1.556   ms/op
ClientPb.getUser                          avgt       3   3.556 ± 1.368   ms/op
ClientPb.listUser                         avgt       3   4.136 ± 0.361   ms/op
ClientPb.createUser                     sample  273359   3.509 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.523           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  282220   3.400 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.957           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  269801   3.556 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.319           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.781           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.371           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.467           ms/op
ClientPb.listUser                       sample  229068   4.189 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.492           ms/op
