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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 5.082 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 9.064 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 9.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.107 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (9.029, 9.107, 9.227), stdev = 0.106
  CI (99.9%): [7.180, 11.033] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 8.864 ops/ms
# Warmup Iteration   3: 9.509 ops/ms
Iteration   1: 9.800 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.695 ±(99.9%) 5.379 ops/ms [Average]
  (min, avg, max) = (9.362, 9.695, 9.922), stdev = 0.295
  CI (99.9%): [4.316, 15.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.035 ops/ms
# Warmup Iteration   2: 8.173 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 9.168 ops/ms
Iteration   3: 9.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.128 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (9.078, 9.128, 9.168), stdev = 0.046
  CI (99.9%): [8.291, 9.965] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.837 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 7.360 ops/ms
Iteration   2: 7.658 ops/ms
Iteration   3: 7.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.526 ±(99.9%) 2.762 ops/ms [Average]
  (min, avg, max) = (7.360, 7.526, 7.658), stdev = 0.151
  CI (99.9%): [4.764, 10.288] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.159 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.003 ms/op
Iteration   1: 3.518 ±(99.9%) 0.004 ms/op
Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
Iteration   3: 3.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.511 ±(99.9%) 1.523 ms/op [Average]
  (min, avg, max) = (3.424, 3.511, 3.590), stdev = 0.084
  CI (99.9%): [1.987, 5.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.003 ms/op
Iteration   1: 3.393 ±(99.9%) 0.002 ms/op
Iteration   2: 3.305 ±(99.9%) 0.002 ms/op
Iteration   3: 3.454 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.384 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (3.305, 3.384, 3.454), stdev = 0.075
  CI (99.9%): [2.015, 4.753] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.842 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.004 ms/op
Iteration   1: 3.612 ±(99.9%) 0.006 ms/op
Iteration   2: 3.572 ±(99.9%) 0.003 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.592 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.572, 3.592, 3.612), stdev = 0.020
  CI (99.9%): [3.226, 3.958] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.949 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.006 ms/op
Iteration   1: 4.125 ±(99.9%) 0.009 ms/op
Iteration   2: 4.104 ±(99.9%) 0.006 ms/op
Iteration   3: 4.154 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.128 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (4.104, 4.128, 4.154), stdev = 0.025
  CI (99.9%): [3.672, 4.583] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.056 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.013 ms/op
Iteration   1: 3.493 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  17.069 ms/op
                 createUser·p0.9999: 20.147 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.572 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  11.780 ms/op
                 createUser·p0.9999: 21.202 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  21.553 ms/op
                 createUser·p0.9999: 27.820 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271385
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4824 
    [ 2.500,  5.000) = 260620 
    [ 5.000,  7.500) = 4790 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     14.781 ms/op
     p(99.9900) =     26.931 ms/op
     p(99.9990) =     28.588 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.885 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 23.791 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.466 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  19.332 ms/op
                 existUser·p0.9999: 21.004 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  18.517 ms/op
                 existUser·p0.9999: 25.314 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281930
  mean =      3.403 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6832 
    [ 2.500,  5.000) = 268082 
    [ 5.000,  7.500) = 5844 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     17.933 ms/op
     p(99.9900) =     24.570 ms/op
     p(99.9990) =     25.970 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.616 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
Iteration   1: 3.492 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.122 ms/op
                 getUser·p0.999:  17.345 ms/op
                 getUser·p0.9999: 22.992 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.535 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  21.840 ms/op
                 getUser·p0.9999: 24.379 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 28.564 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272345
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4343 
    [ 2.500,  5.000) = 261789 
    [ 5.000,  7.500) = 5054 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     18.404 ms/op
     p(99.9900) =     26.436 ms/op
     p(99.9990) =     29.367 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.748 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.013 ms/op
Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  19.739 ms/op
                 listUser·p0.9999: 23.797 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.097 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.268 ms/op
                 listUser·p0.9999: 16.010 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 4.155 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.828 ms/op
                 listUser·p0.9999: 18.179 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232692
  mean =      4.125 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 223253 
    [ 5.000,  7.500) = 7644 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 300 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.952 ms/op
     p(99.9900) =     22.241 ms/op
     p(99.9990) =     24.458 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.107 ± 1.927  ops/ms
ClientPb.existUser                       thrpt       3   9.695 ± 5.379  ops/ms
ClientPb.getUser                         thrpt       3   9.128 ± 0.837  ops/ms
ClientPb.listUser                        thrpt       3   7.526 ± 2.762  ops/ms
ClientPb.createUser                       avgt       3   3.511 ± 1.523   ms/op
ClientPb.existUser                        avgt       3   3.384 ± 1.369   ms/op
ClientPb.getUser                          avgt       3   3.592 ± 0.366   ms/op
ClientPb.listUser                         avgt       3   4.128 ± 0.456   ms/op
ClientPb.createUser                     sample  271385   3.536 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.430           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.781           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  281930   3.403 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.933           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.570           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.345           ms/op
ClientPb.getUser                        sample  272345   3.523 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.734           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.404           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.436           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.688           ms/op
ClientPb.listUser                       sample  232692   4.125 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.952           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
