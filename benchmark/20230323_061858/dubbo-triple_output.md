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
# Warmup Iteration   1: 2.438 ops/ms
# Warmup Iteration   2: 5.961 ops/ms
# Warmup Iteration   3: 9.288 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 10.041 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.714 ±(99.9%) 7.066 ops/ms [Average]
  (min, avg, max) = (9.287, 9.714, 10.041), stdev = 0.387
  CI (99.9%): [2.649, 16.780] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ops/ms
# Warmup Iteration   2: 9.749 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.849 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.690 ±(99.9%) 2.519 ops/ms [Average]
  (min, avg, max) = (10.597, 10.690, 10.849), stdev = 0.138
  CI (99.9%): [8.171, 13.210] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 9.272 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 9.813 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.904 ±(99.9%) 3.318 ops/ms [Average]
  (min, avg, max) = (9.786, 9.904, 10.114), stdev = 0.182
  CI (99.9%): [6.586, 13.222] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.223 ops/ms
# Warmup Iteration   2: 7.625 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.331 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.347 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (8.250, 8.347, 8.460), stdev = 0.106
  CI (99.9%): [6.414, 10.280] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.913 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
Iteration   3: 3.211 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.129 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (3.047, 3.129, 3.211), stdev = 0.082
  CI (99.9%): [1.633, 4.625] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.980 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.004 ms/op
Iteration   1: 2.946 ±(99.9%) 0.004 ms/op
Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.032 ±(99.9%) 1.390 ms/op [Average]
  (min, avg, max) = (2.946, 3.032, 3.091), stdev = 0.076
  CI (99.9%): [1.641, 4.422] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.005 ms/op
Iteration   1: 3.209 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.308 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.185 ±(99.9%) 2.483 ms/op [Average]
  (min, avg, max) = (3.039, 3.185, 3.308), stdev = 0.136
  CI (99.9%): [0.702, 5.668] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.096 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.005 ms/op
Iteration   1: 3.726 ±(99.9%) 0.006 ms/op
Iteration   2: 3.787 ±(99.9%) 0.007 ms/op
Iteration   3: 3.732 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (3.726, 3.748, 3.787), stdev = 0.034
  CI (99.9%): [3.135, 4.361] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.248 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  18.068 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  13.149 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  16.531 ms/op
                 createUser·p0.9999: 19.464 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300850
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24973 
    [ 2.500,  5.000) = 268834 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 196 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     23.811 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.577 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 26.770 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 22.770 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 27.350 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310677
  mean =      3.089 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19532 
    [ 2.500,  5.000) = 284773 
    [ 5.000,  7.500) = 5372 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.447 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.008 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  20.067 ms/op
                 getUser·p0.9999: 24.033 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  9.068 ms/op
                 getUser·p0.9999: 23.679 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  8.737 ms/op
                 getUser·p0.9999: 18.626 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304355
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10912 
    [ 2.500,  5.000) = 287096 
    [ 5.000,  7.500) = 5464 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.063 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.011 ms/op
Iteration   1: 3.701 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 19.312 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.317 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 22.264 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 3.750 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.838 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257191
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 249039 
    [ 5.000,  7.500) = 6421 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 303 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.714 ± 7.066  ops/ms
ClientPb.existUser                       thrpt       3  10.690 ± 2.519  ops/ms
ClientPb.getUser                         thrpt       3   9.904 ± 3.318  ops/ms
ClientPb.listUser                        thrpt       3   8.347 ± 1.933  ops/ms
ClientPb.createUser                       avgt       3   3.129 ± 1.496   ms/op
ClientPb.existUser                        avgt       3   3.032 ± 1.390   ms/op
ClientPb.getUser                          avgt       3   3.185 ± 2.483   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 0.613   ms/op
ClientPb.createUser                     sample  300850   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.465           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.811           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  310677   3.089 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.895           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.706           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  304355   3.153 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.385           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.362           ms/op
ClientPb.listUser                       sample  257191   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.317           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
