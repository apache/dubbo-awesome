# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ops/ms
# Warmup Iteration   2: 12.047 ops/ms
# Warmup Iteration   3: 12.316 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.659 ops/ms
Iteration   3: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.661 ±(99.9%) 0.159 ops/ms [Average]
  (min, avg, max) = (12.653, 12.661, 12.670), stdev = 0.009
  CI (99.9%): [12.501, 12.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.891 ops/ms
# Warmup Iteration   2: 12.941 ops/ms
# Warmup Iteration   3: 12.985 ops/ms
Iteration   1: 12.853 ops/ms
Iteration   2: 13.032 ops/ms
Iteration   3: 12.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.935 ±(99.9%) 1.647 ops/ms [Average]
  (min, avg, max) = (12.853, 12.935, 13.032), stdev = 0.090
  CI (99.9%): [11.288, 14.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 12.541 ops/ms
# Warmup Iteration   3: 12.724 ops/ms
Iteration   1: 12.778 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.697 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (12.642, 12.697, 12.778), stdev = 0.072
  CI (99.9%): [11.388, 14.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.927 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.609 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.539 ±(99.9%) 1.372 ops/ms [Average]
  (min, avg, max) = (10.458, 10.539, 10.606), stdev = 0.075
  CI (99.9%): [9.167, 11.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.003 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.543, 2.558, 2.576), stdev = 0.017
  CI (99.9%): [2.252, 2.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (2.463, 2.486, 2.501), stdev = 0.020
  CI (99.9%): [2.116, 2.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.497, 2.502, 2.511), stdev = 0.008
  CI (99.9%): [2.352, 2.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.887 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.997, 3.000, 3.006), stdev = 0.005
  CI (99.9%): [2.913, 3.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  11.785 ms/op
                 createUser·p0.9999: 14.071 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 12.009 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  8.563 ms/op
                 createUser·p0.9999: 12.601 ms/op
                 createUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375445
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 179827 
    [ 2.500,  3.750) = 191286 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 587 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.672 ms/op
     p(99.9990) =     15.132 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.715 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.458 ms/op
                 existUser·p0.9999: 12.664 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.751 ms/op
                 existUser·p0.999:  8.274 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390413
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 192739 
    [ 2.500,  3.750) = 194866 
    [ 3.750,  5.000) = 2132 
    [ 5.000,  6.250) = 237 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      5.909 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.514 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.382 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  11.787 ms/op
                 getUser·p0.9999: 15.709 ms/op
                 getUser·p1.00:   16.253 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 14.467 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 11.705 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377880
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 184266 
    [ 2.500,  3.750) = 187841 
    [ 3.750,  5.000) = 4676 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      8.527 ms/op
     p(99.9900) =     14.720 ms/op
     p(99.9990) =     16.082 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.822 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.602 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.710 ms/op
                 listUser·p0.9999: 13.888 ms/op
                 listUser·p1.00:   14.680 ms/op

Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.179 ms/op
                 listUser·p0.9999: 10.644 ms/op
                 listUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319845
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 92311 
    [ 2.500,  3.750) = 189638 
    [ 3.750,  5.000) = 31111 
    [ 5.000,  6.250) = 5400 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.799 ms/op
     p(99.9990) =     14.362 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.661 ± 0.159  ops/ms
ClientPb.existUser                       thrpt       3  12.935 ± 1.647  ops/ms
ClientPb.getUser                         thrpt       3  12.697 ± 1.308  ops/ms
ClientPb.listUser                        thrpt       3  10.539 ± 1.372  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.306   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.369   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.150   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.087   ms/op
ClientPb.createUser                     sample  375445   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.823           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.672           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.335           ms/op
ClientPb.existUser                      sample  390413   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.592           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.909           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.795           ms/op
ClientPb.getUser                        sample  377880   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.527           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.720           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.253           ms/op
ClientPb.listUser                       sample  319845   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.799           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.680           ms/op
