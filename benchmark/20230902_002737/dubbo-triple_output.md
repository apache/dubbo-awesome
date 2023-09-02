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
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 4.373 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 9.211 ops/ms
Iteration   2: 9.087 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.953 ±(99.9%) 6.289 ops/ms [Average]
  (min, avg, max) = (8.561, 8.953, 9.211), stdev = 0.345
  CI (99.9%): [2.664, 15.242] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.409 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.360 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (9.296, 9.360, 9.409), stdev = 0.058
  CI (99.9%): [8.303, 10.416] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 6.963 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.213 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (9.154, 9.213, 9.290), stdev = 0.070
  CI (99.9%): [7.935, 10.491] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 7.049 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.977 ±(99.9%) 4.061 ops/ms [Average]
  (min, avg, max) = (7.732, 7.977, 8.167), stdev = 0.223
  CI (99.9%): [3.916, 12.038] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.618 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.006 ms/op
Iteration   1: 3.518 ±(99.9%) 0.006 ms/op
Iteration   2: 3.424 ±(99.9%) 0.005 ms/op
Iteration   3: 3.400 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.448 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.400, 3.448, 3.518), stdev = 0.062
  CI (99.9%): [2.308, 4.587] (assumes normal distribution)


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
# Warmup Iteration   1: 9.511 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.005 ms/op
Iteration   1: 3.349 ±(99.9%) 0.004 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.283 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.283, 3.313, 3.349), stdev = 0.033
  CI (99.9%): [2.704, 3.921] (assumes normal distribution)


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
# Warmup Iteration   1: 10.089 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.004 ms/op
Iteration   1: 3.445 ±(99.9%) 0.002 ms/op
Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
Iteration   3: 3.409 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.409, 3.444, 3.478), stdev = 0.035
  CI (99.9%): [2.811, 4.077] (assumes normal distribution)


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
# Warmup Iteration   1: 10.892 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.005 ms/op
Iteration   1: 4.121 ±(99.9%) 0.008 ms/op
Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
Iteration   3: 4.091 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.116 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (4.091, 4.116, 4.134), stdev = 0.022
  CI (99.9%): [3.715, 4.516] (assumes normal distribution)


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
# Warmup Iteration   1: 8.591 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.011 ms/op
Iteration   1: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  19.961 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.498 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  22.800 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.521 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  20.372 ms/op
                 createUser·p0.9999: 25.425 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275506
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5571 
    [ 2.500,  5.000) = 262958 
    [ 5.000,  7.500) = 5588 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     20.332 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.968 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 10.154 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
Iteration   1: 3.472 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  20.629 ms/op
                 existUser·p0.9999: 23.651 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.489 ms/op
                 existUser·p0.999:  21.460 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.467 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.430 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 29.688 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278599
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14674 
    [ 2.500,  5.000) = 254287 
    [ 5.000,  7.500) = 8260 
    [ 7.500, 10.000) = 963 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     11.688 ms/op
     p(99.9900) =     28.840 ms/op
     p(99.9990) =     30.212 ms/op
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
# Warmup Iteration   1: 9.328 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.014 ms/op
Iteration   1: 3.585 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  17.780 ms/op
                 getUser·p0.9999: 25.204 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 3.627 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.185 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  22.736 ms/op
                 getUser·p0.9999: 27.084 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.580 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  24.612 ms/op
                 getUser·p0.9999: 28.119 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266802
  mean =      3.597 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6386 
    [ 2.500,  5.000) = 247001 
    [ 5.000,  7.500) = 11628 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     20.073 ms/op
     p(99.9900) =     27.339 ms/op
     p(99.9990) =     28.421 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 11.069 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
Iteration   1: 4.029 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.090 ms/op
                 listUser·p0.999:  20.830 ms/op
                 listUser·p0.9999: 28.708 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   2: 4.207 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 18.179 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235976
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 224930 
    [ 5.000,  7.500) = 8046 
    [ 7.500, 10.000) = 1973 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     27.145 ms/op
     p(99.9990) =     29.230 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.953 ± 6.289  ops/ms
ClientPb.existUser                       thrpt       3   9.360 ± 1.056  ops/ms
ClientPb.getUser                         thrpt       3   9.213 ± 1.278  ops/ms
ClientPb.listUser                        thrpt       3   7.977 ± 4.061  ops/ms
ClientPb.createUser                       avgt       3   3.448 ± 1.139   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 0.609   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.633   ms/op
ClientPb.listUser                         avgt       3   4.116 ± 0.400   ms/op
ClientPb.createUser                     sample  275506   3.482 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.360           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.100           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  278599   3.447 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.348           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.688           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.840           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  266802   3.597 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.339           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  235976   4.068 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.268           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.393           ms/op
