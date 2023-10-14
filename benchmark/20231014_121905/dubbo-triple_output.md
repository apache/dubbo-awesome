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
# Warmup Iteration   1: 1.985 ops/ms
# Warmup Iteration   2: 4.380 ops/ms
# Warmup Iteration   3: 8.441 ops/ms
Iteration   1: 8.667 ops/ms
Iteration   2: 8.994 ops/ms
Iteration   3: 8.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.806 ±(99.9%) 3.083 ops/ms [Average]
  (min, avg, max) = (8.667, 8.806, 8.994), stdev = 0.169
  CI (99.9%): [5.723, 11.889] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ops/ms
# Warmup Iteration   2: 8.626 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.372 ±(99.9%) 2.052 ops/ms [Average]
  (min, avg, max) = (9.246, 9.372, 9.463), stdev = 0.112
  CI (99.9%): [7.321, 11.424] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 8.536 ops/ms
# Warmup Iteration   3: 8.879 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.001 ops/ms
Iteration   3: 8.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.037 ±(99.9%) 1.430 ops/ms [Average]
  (min, avg, max) = (8.983, 9.037, 9.127), stdev = 0.078
  CI (99.9%): [7.607, 10.467] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 6.871 ops/ms
# Warmup Iteration   3: 7.516 ops/ms
Iteration   1: 7.628 ops/ms
Iteration   2: 7.707 ops/ms
Iteration   3: 7.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.668 ±(99.9%) 0.720 ops/ms [Average]
  (min, avg, max) = (7.628, 7.668, 7.707), stdev = 0.039
  CI (99.9%): [6.947, 8.388] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.421 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.004 ms/op
Iteration   1: 3.617 ±(99.9%) 0.004 ms/op
Iteration   2: 3.559 ±(99.9%) 0.007 ms/op
Iteration   3: 3.627 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.601 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.559, 3.601, 3.627), stdev = 0.037
  CI (99.9%): [2.930, 4.272] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.430 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.005 ms/op
Iteration   1: 3.391 ±(99.9%) 0.005 ms/op
Iteration   2: 3.423 ±(99.9%) 0.003 ms/op
Iteration   3: 3.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.428 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.391, 3.428, 3.470), stdev = 0.040
  CI (99.9%): [2.705, 4.151] (assumes normal distribution)


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
# Warmup Iteration   1: 11.037 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.006 ms/op
Iteration   1: 3.571 ±(99.9%) 0.004 ms/op
Iteration   2: 3.575 ±(99.9%) 0.004 ms/op
Iteration   3: 3.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.530 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.445, 3.530, 3.575), stdev = 0.074
  CI (99.9%): [2.183, 4.877] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.967 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.005 ms/op
Iteration   1: 4.232 ±(99.9%) 0.009 ms/op
Iteration   2: 4.137 ±(99.9%) 0.008 ms/op
Iteration   3: 4.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.170 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (4.137, 4.170, 4.232), stdev = 0.054
  CI (99.9%): [3.194, 5.147] (assumes normal distribution)


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
# Warmup Iteration   1: 9.961 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.011 ms/op
Iteration   1: 3.607 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  16.827 ms/op
                 createUser·p0.9999: 34.677 ms/op
                 createUser·p1.00:   35.979 ms/op

Iteration   2: 3.604 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  18.115 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   7.293 ms/op
                 createUser·p0.999:  18.614 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267711
  mean =      3.585 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4198 
    [ 2.500,  5.000) = 254340 
    [ 5.000,  7.500) = 7424 
    [ 7.500, 10.000) = 1025 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     17.615 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.647 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 9.429 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  19.794 ms/op
                 existUser·p0.9999: 22.334 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.377 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  22.652 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.969 ms/op
                 existUser·p0.999:  15.548 ms/op
                 existUser·p0.9999: 29.276 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279568
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10006 
    [ 2.500,  5.000) = 258436 
    [ 5.000,  7.500) = 9782 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     19.361 ms/op
     p(99.9900) =     26.824 ms/op
     p(99.9990) =     32.299 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 9.555 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.011 ms/op
Iteration   1: 3.595 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  21.759 ms/op
                 getUser·p0.9999: 28.532 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   2: 3.593 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.483 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  20.840 ms/op
                 getUser·p0.9999: 27.602 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269548
  mean =      3.561 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4051 
    [ 2.500,  5.000) = 255265 
    [ 5.000,  7.500) = 7942 
    [ 7.500, 10.000) = 1590 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 152 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     27.166 ms/op
     p(99.9990) =     29.519 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 11.775 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.013 ms/op
Iteration   1: 4.226 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.855 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.388 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  21.540 ms/op
                 listUser·p0.9999: 24.539 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.040 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 18.978 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.293 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.230 ms/op
                 listUser·p0.999:  14.848 ms/op
                 listUser·p0.9999: 26.910 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229227
  mean =      4.184 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 217358 
    [ 5.000,  7.500) = 8414 
    [ 7.500, 10.000) = 2457 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     27.997 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.806 ± 3.083  ops/ms
ClientPb.existUser                       thrpt       3   9.372 ± 2.052  ops/ms
ClientPb.getUser                         thrpt       3   9.037 ± 1.430  ops/ms
ClientPb.listUser                        thrpt       3   7.668 ± 0.720  ops/ms
ClientPb.createUser                       avgt       3   3.601 ± 0.671   ms/op
ClientPb.existUser                        avgt       3   3.428 ± 0.723   ms/op
ClientPb.getUser                          avgt       3   3.530 ± 1.347   ms/op
ClientPb.listUser                         avgt       3   4.170 ± 0.977   ms/op
ClientPb.createUser                     sample  267711   3.585 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.615           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  279568   3.433 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.977           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.361           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.824           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  269548   3.561 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.340           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.166           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  229227   4.184 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.115           ms/op
