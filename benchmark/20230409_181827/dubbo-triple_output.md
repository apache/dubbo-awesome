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
# Warmup Iteration   1: 1.129 ops/ms
# Warmup Iteration   2: 2.477 ops/ms
# Warmup Iteration   3: 5.191 ops/ms
Iteration   1: 5.577 ops/ms
Iteration   2: 5.678 ops/ms
Iteration   3: 5.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.688 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (5.577, 5.688, 5.809), stdev = 0.117
  CI (99.9%): [3.562, 7.814] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.442 ops/ms
# Warmup Iteration   2: 4.316 ops/ms
# Warmup Iteration   3: 5.529 ops/ms
Iteration   1: 5.920 ops/ms
Iteration   2: 5.513 ops/ms
Iteration   3: 6.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.819 ±(99.9%) 4.934 ops/ms [Average]
  (min, avg, max) = (5.513, 5.819, 6.025), stdev = 0.270
  CI (99.9%): [0.885, 10.753] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.491 ops/ms
# Warmup Iteration   2: 4.036 ops/ms
# Warmup Iteration   3: 5.069 ops/ms
Iteration   1: 4.956 ops/ms
Iteration   2: 5.148 ops/ms
Iteration   3: 5.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.107 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (4.956, 5.107, 5.217), stdev = 0.135
  CI (99.9%): [2.638, 7.576] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.329 ops/ms
# Warmup Iteration   2: 3.436 ops/ms
# Warmup Iteration   3: 4.677 ops/ms
Iteration   1: 4.525 ops/ms
Iteration   2: 4.809 ops/ms
Iteration   3: 4.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.710 ±(99.9%) 2.928 ops/ms [Average]
  (min, avg, max) = (4.525, 4.710, 4.809), stdev = 0.161
  CI (99.9%): [1.782, 7.638] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.205 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.606 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.116 ±(99.9%) 0.017 ms/op
Iteration   1: 5.902 ±(99.9%) 0.011 ms/op
Iteration   2: 5.658 ±(99.9%) 0.015 ms/op
Iteration   3: 5.751 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.771 ±(99.9%) 2.243 ms/op [Average]
  (min, avg, max) = (5.658, 5.771, 5.902), stdev = 0.123
  CI (99.9%): [3.527, 8.014] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.456 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.618 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.938 ±(99.9%) 0.008 ms/op
Iteration   1: 5.413 ±(99.9%) 0.020 ms/op
Iteration   2: 5.599 ±(99.9%) 0.010 ms/op
Iteration   3: 5.731 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.581 ±(99.9%) 2.914 ms/op [Average]
  (min, avg, max) = (5.413, 5.581, 5.731), stdev = 0.160
  CI (99.9%): [2.667, 8.496] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 20.067 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.589 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.964 ±(99.9%) 0.014 ms/op
Iteration   1: 5.766 ±(99.9%) 0.015 ms/op
Iteration   2: 6.076 ±(99.9%) 0.014 ms/op
Iteration   3: 5.724 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.856 ±(99.9%) 3.509 ms/op [Average]
  (min, avg, max) = (5.724, 5.856, 6.076), stdev = 0.192
  CI (99.9%): [2.347, 9.364] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.084 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 8.385 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.959 ±(99.9%) 0.013 ms/op
Iteration   1: 6.734 ±(99.9%) 0.019 ms/op
Iteration   2: 6.805 ±(99.9%) 0.018 ms/op
Iteration   3: 6.745 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.761 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (6.734, 6.761, 6.805), stdev = 0.038
  CI (99.9%): [6.065, 7.457] (assumes normal distribution)


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
# Warmup Iteration   1: 18.952 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 8.055 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.028 ms/op
Iteration   1: 5.980 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.496 ms/op
                 createUser·p0.95:   8.536 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 29.532 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 5.955 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   11.680 ms/op
                 createUser·p0.999:  24.334 ms/op
                 createUser·p0.9999: 28.853 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 5.822 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.519 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  16.140 ms/op
                 createUser·p0.9999: 28.590 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162154
  mean =      5.918 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 32442 
    [ 5.000,  7.500) = 115540 
    [ 7.500, 10.000) = 10570 
    [10.000, 12.500) = 2614 
    [12.500, 15.000) = 525 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     24.440 ms/op
     p(99.9900) =     28.796 ms/op
     p(99.9990) =     29.963 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 18.363 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.679 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.667 ±(99.9%) 0.022 ms/op
Iteration   1: 5.514 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.873 ms/op
                 existUser·p0.95:   7.995 ms/op
                 existUser·p0.99:   10.565 ms/op
                 existUser·p0.999:  28.343 ms/op
                 existUser·p0.9999: 35.009 ms/op
                 existUser·p1.00:   35.389 ms/op

Iteration   2: 5.502 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.944 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.516 ms/op
                 existUser·p0.99:   10.846 ms/op
                 existUser·p0.999:  28.059 ms/op
                 existUser·p0.9999: 34.777 ms/op
                 existUser·p1.00:   37.159 ms/op

Iteration   3: 5.514 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.611 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  29.196 ms/op
                 existUser·p0.9999: 32.512 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174253
  mean =      5.510 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 54985 
    [ 5.000,  7.500) = 109421 
    [ 7.500, 10.000) = 7537 
    [10.000, 12.500) = 1495 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     28.459 ms/op
     p(99.9900) =     34.744 ms/op
     p(99.9990) =     37.013 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 18.516 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.118 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.098 ±(99.9%) 0.025 ms/op
Iteration   1: 6.149 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.867 ms/op
                 getUser·p0.50:   5.702 ms/op
                 getUser·p0.90:   8.045 ms/op
                 getUser·p0.95:   9.650 ms/op
                 getUser·p0.99:   13.664 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 28.364 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 5.589 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  26.415 ms/op
                 getUser·p0.9999: 29.907 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.544 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.187 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.381 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  30.420 ms/op
                 getUser·p0.9999: 34.337 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166867
  mean =      5.748 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 41900 
    [ 5.000,  7.500) = 113550 
    [ 7.500, 10.000) = 7810 
    [10.000, 12.500) = 2441 
    [12.500, 15.000) = 690 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      8.331 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     33.411 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 19.444 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.270 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.835 ±(99.9%) 0.031 ms/op
Iteration   1: 6.680 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.273 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.173 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 32.316 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.467 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.574 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  29.492 ms/op
                 listUser·p0.9999: 32.424 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   3: 6.432 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  23.986 ms/op
                 listUser·p0.9999: 39.782 ms/op
                 listUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147046
  mean =      6.524 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4082 
    [ 5.000, 10.000) = 138786 
    [10.000, 15.000) = 3750 
    [15.000, 20.000) = 146 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 144 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      6.210 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     28.344 ms/op
     p(99.9900) =     37.545 ms/op
     p(99.9990) =     41.415 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.688 ± 2.126  ops/ms
ClientPb.existUser                       thrpt       3   5.819 ± 4.934  ops/ms
ClientPb.getUser                         thrpt       3   5.107 ± 2.469  ops/ms
ClientPb.listUser                        thrpt       3   4.710 ± 2.928  ops/ms
ClientPb.createUser                       avgt       3   5.771 ± 2.243   ms/op
ClientPb.existUser                        avgt       3   5.581 ± 2.914   ms/op
ClientPb.getUser                          avgt       3   5.856 ± 3.509   ms/op
ClientPb.listUser                         avgt       3   6.761 ± 0.696   ms/op
ClientPb.createUser                     sample  162154   5.918 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.340           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.405           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.485           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.440           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  174253   5.510 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.660           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.733           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          28.459           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.744           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.159           ms/op
ClientPb.getUser                        sample  166867   5.748 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.187           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.331           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.665           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.411           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  147046   6.524 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.813           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.344           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.878           ms/op
