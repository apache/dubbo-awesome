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
# Warmup Iteration   1: 1.066 ops/ms
# Warmup Iteration   2: 2.215 ops/ms
# Warmup Iteration   3: 4.568 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.516 ops/ms
Iteration   3: 5.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.585 ±(99.9%) 2.930 ops/ms [Average]
  (min, avg, max) = (5.469, 5.585, 5.768), stdev = 0.161
  CI (99.9%): [2.654, 8.515] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 4.746 ops/ms
# Warmup Iteration   3: 6.004 ops/ms
Iteration   1: 6.111 ops/ms
Iteration   2: 6.073 ops/ms
Iteration   3: 6.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.107 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (6.073, 6.107, 6.138), stdev = 0.033
  CI (99.9%): [5.506, 6.709] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 4.750 ops/ms
# Warmup Iteration   3: 5.793 ops/ms
Iteration   1: 5.933 ops/ms
Iteration   2: 5.740 ops/ms
Iteration   3: 5.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.811 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (5.740, 5.811, 5.933), stdev = 0.107
  CI (99.9%): [3.865, 7.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.554 ops/ms
# Warmup Iteration   2: 4.068 ops/ms
# Warmup Iteration   3: 5.075 ops/ms
Iteration   1: 4.977 ops/ms
Iteration   2: 5.125 ops/ms
Iteration   3: 5.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.090 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (4.977, 5.090, 5.168), stdev = 0.100
  CI (99.9%): [3.262, 6.918] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.043 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 7.149 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.804 ±(99.9%) 0.007 ms/op
Iteration   1: 5.364 ±(99.9%) 0.017 ms/op
Iteration   2: 5.468 ±(99.9%) 0.011 ms/op
Iteration   3: 5.408 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.413 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (5.364, 5.413, 5.468), stdev = 0.052
  CI (99.9%): [4.460, 6.367] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.011 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.889 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.278 ±(99.9%) 0.009 ms/op
Iteration   1: 5.265 ±(99.9%) 0.007 ms/op
Iteration   2: 5.165 ±(99.9%) 0.011 ms/op
Iteration   3: 5.125 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.185 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (5.125, 5.185, 5.265), stdev = 0.072
  CI (99.9%): [3.864, 6.506] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.689 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.709 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.009 ms/op
Iteration   1: 5.434 ±(99.9%) 0.011 ms/op
Iteration   2: 5.425 ±(99.9%) 0.010 ms/op
Iteration   3: 5.457 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.439 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (5.425, 5.439, 5.457), stdev = 0.017
  CI (99.9%): [5.136, 5.741] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.109 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.345 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.345 ±(99.9%) 0.015 ms/op
Iteration   1: 6.548 ±(99.9%) 0.009 ms/op
Iteration   2: 6.390 ±(99.9%) 0.010 ms/op
Iteration   3: 6.178 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.372 ±(99.9%) 3.385 ms/op [Average]
  (min, avg, max) = (6.178, 6.372, 6.548), stdev = 0.186
  CI (99.9%): [2.987, 9.757] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.157 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 7.919 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.138 ±(99.9%) 0.029 ms/op
Iteration   1: 5.686 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.175 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   8.110 ms/op
                 createUser·p0.99:   10.487 ms/op
                 createUser·p0.999:  15.890 ms/op
                 createUser·p0.9999: 28.000 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 5.592 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.551 ms/op
                 createUser·p0.999:  26.594 ms/op
                 createUser·p0.9999: 29.846 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 5.591 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  30.132 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170649
  mean =      5.623 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 51374 
    [ 5.000,  7.500) = 109159 
    [ 7.500, 10.000) = 7982 
    [10.000, 12.500) = 1420 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     20.983 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.535 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.808 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.185 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.401 ±(99.9%) 0.019 ms/op
Iteration   1: 5.179 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   10.003 ms/op
                 existUser·p0.999:  27.370 ms/op
                 existUser·p0.9999: 30.212 ms/op
                 existUser·p1.00:   31.883 ms/op

Iteration   2: 5.261 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   7.158 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  21.859 ms/op
                 existUser·p0.9999: 30.949 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 5.268 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.234 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  28.746 ms/op
                 existUser·p0.9999: 32.466 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183266
  mean =      5.236 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 96125 
    [ 5.000,  7.500) = 80363 
    [ 7.500, 10.000) = 4888 
    [10.000, 12.500) = 1042 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =     10.032 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     31.447 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.623 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 6.816 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.461 ±(99.9%) 0.017 ms/op
Iteration   1: 5.545 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   7.913 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  24.281 ms/op
                 getUser·p0.9999: 33.260 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   2: 5.580 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  26.466 ms/op
                 getUser·p0.9999: 29.607 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   3: 5.507 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  30.437 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173077
  mean =      5.544 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 63999 
    [ 5.000,  7.500) = 97373 
    [ 7.500, 10.000) = 9430 
    [10.000, 12.500) = 1605 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     24.737 ms/op
     p(99.9900) =     32.836 ms/op
     p(99.9990) =     34.048 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.897 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 8.818 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.845 ±(99.9%) 0.032 ms/op
Iteration   1: 6.250 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.423 ms/op
                 listUser·p0.999:  28.982 ms/op
                 listUser·p0.9999: 33.196 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.278 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  30.569 ms/op
                 listUser·p0.9999: 34.079 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   3: 6.338 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.828 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  25.674 ms/op
                 listUser·p0.9999: 31.336 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152579
  mean =      6.288 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 5571 
    [ 5.000,  7.500) = 132259 
    [ 7.500, 10.000) = 11061 
    [10.000, 12.500) = 2700 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      5.923 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     28.751 ms/op
     p(99.9900) =     32.791 ms/op
     p(99.9990) =     35.812 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.585 ± 2.930  ops/ms
ClientPb.existUser                       thrpt       3   6.107 ± 0.602  ops/ms
ClientPb.getUser                         thrpt       3   5.811 ± 1.946  ops/ms
ClientPb.listUser                        thrpt       3   5.090 ± 1.828  ops/ms
ClientPb.createUser                       avgt       3   5.413 ± 0.954   ms/op
ClientPb.existUser                        avgt       3   5.185 ± 1.321   ms/op
ClientPb.getUser                          avgt       3   5.439 ± 0.302   ms/op
ClientPb.listUser                         avgt       3   6.372 ± 3.385   ms/op
ClientPb.createUser                     sample  170649   5.623 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.529           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.983           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.554           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  183266   5.236 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.037           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.032           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.708           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.447           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  173077   5.544 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.737           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.836           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  152579   6.288 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.923           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.436           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.751           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.791           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.224           ms/op
