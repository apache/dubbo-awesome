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
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.395 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 9.157 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.235 ±(99.9%) 3.568 ops/ms [Average]
  (min, avg, max) = (9.091, 9.235, 9.458), stdev = 0.196
  CI (99.9%): [5.667, 12.804] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.503 ops/ms
Iteration   1: 9.936 ops/ms
Iteration   2: 9.799 ops/ms
Iteration   3: 9.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.808 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (9.690, 9.808, 9.936), stdev = 0.124
  CI (99.9%): [7.554, 12.063] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 8.210 ops/ms
# Warmup Iteration   3: 9.352 ops/ms
Iteration   1: 9.149 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.347 ±(99.9%) 5.982 ops/ms [Average]
  (min, avg, max) = (9.149, 9.347, 9.726), stdev = 0.328
  CI (99.9%): [3.365, 15.329] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.915 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 7.623 ops/ms
Iteration   1: 7.810 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.937 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (7.810, 7.937, 8.012), stdev = 0.111
  CI (99.9%): [5.912, 9.963] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.132 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.349 ±(99.9%) 0.011 ms/op
Iteration   2: 3.584 ±(99.9%) 0.006 ms/op
Iteration   3: 3.501 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 2.178 ms/op [Average]
  (min, avg, max) = (3.349, 3.478, 3.584), stdev = 0.119
  CI (99.9%): [1.300, 5.656] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.004 ms/op
Iteration   1: 3.311 ±(99.9%) 0.007 ms/op
Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
Iteration   3: 3.275 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.242, 3.276, 3.311), stdev = 0.035
  CI (99.9%): [2.647, 3.905] (assumes normal distribution)


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
# Warmup Iteration   1: 9.203 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
Iteration   3: 3.373 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.447 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (3.373, 3.447, 3.518), stdev = 0.072
  CI (99.9%): [2.128, 4.766] (assumes normal distribution)


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
# Warmup Iteration   1: 11.741 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.011 ms/op
Iteration   1: 3.998 ±(99.9%) 0.008 ms/op
Iteration   2: 4.027 ±(99.9%) 0.009 ms/op
Iteration   3: 4.125 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.050 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.998, 4.050, 4.125), stdev = 0.067
  CI (99.9%): [2.829, 5.271] (assumes normal distribution)


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
# Warmup Iteration   1: 9.963 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.011 ms/op
Iteration   1: 3.553 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  21.332 ms/op
                 createUser·p0.9999: 28.377 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 31.301 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 3.406 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  20.727 ms/op
                 createUser·p0.9999: 32.231 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275772
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7426 
    [ 2.500,  5.000) = 261803 
    [ 5.000,  7.500) = 5492 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     22.101 ms/op
     p(99.9900) =     31.275 ms/op
     p(99.9990) =     34.684 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.453 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.153 ms/op
                 existUser·p0.999:  22.755 ms/op
                 existUser·p0.9999: 25.208 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  24.122 ms/op
                 existUser·p0.9999: 28.439 ms/op
                 existUser·p1.00:   30.212 ms/op

Iteration   3: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  9.899 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284252
  mean =      3.374 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8954 
    [ 2.500,  5.000) = 268253 
    [ 5.000,  7.500) = 6187 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.009 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     29.482 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 10.782 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.014 ms/op
Iteration   1: 3.439 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 25.159 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.424 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.342 ms/op
                 getUser·p0.999:  22.987 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 3.489 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.689 ms/op
                 getUser·p0.999:  21.344 ms/op
                 getUser·p0.9999: 31.343 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278147
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11202 
    [ 2.500,  5.000) = 259032 
    [ 5.000,  7.500) = 6251 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     29.956 ms/op
     p(99.9990) =     31.563 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 11.659 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.014 ms/op
Iteration   1: 4.144 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  24.823 ms/op
                 listUser·p0.9999: 27.558 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.225 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.606 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.028 ms/op
                 listUser·p0.9999: 25.656 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233301
  mean =      4.115 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 222684 
    [ 5.000,  7.500) = 7116 
    [ 7.500, 10.000) = 2509 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     26.946 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.235 ± 3.568  ops/ms
ClientPb.existUser                       thrpt       3   9.808 ± 2.255  ops/ms
ClientPb.getUser                         thrpt       3   9.347 ± 5.982  ops/ms
ClientPb.listUser                        thrpt       3   7.937 ± 2.026  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 2.178   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 0.629   ms/op
ClientPb.getUser                          avgt       3   3.447 ± 1.319   ms/op
ClientPb.listUser                         avgt       3   4.050 ± 1.221   ms/op
ClientPb.createUser                     sample  275772   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.489           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.101           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  284252   3.374 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.194           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.009           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.482           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  278147   3.451 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.221           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.956           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.785           ms/op
ClientPb.listUser                       sample  233301   4.115 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.350           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.946           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
