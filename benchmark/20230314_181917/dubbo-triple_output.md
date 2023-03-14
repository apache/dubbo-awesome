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
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 5.709 ops/ms
# Warmup Iteration   3: 9.319 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.059 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.587 ±(99.9%) 9.637 ops/ms [Average]
  (min, avg, max) = (9.059, 9.587, 10.115), stdev = 0.528
  CI (99.9%): [≈ 0, 19.224] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.645 ops/ms
Iteration   2: 10.298 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.537 ±(99.9%) 3.793 ops/ms [Average]
  (min, avg, max) = (10.298, 10.537, 10.670), stdev = 0.208
  CI (99.9%): [6.745, 14.330] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.243 ops/ms
# Warmup Iteration   2: 8.547 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.928 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 9.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.944 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (9.928, 9.944, 9.960), stdev = 0.016
  CI (99.9%): [9.649, 10.240] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.471 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.424 ops/ms
Iteration   1: 8.873 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.558 ±(99.9%) 5.096 ops/ms [Average]
  (min, avg, max) = (8.341, 8.558, 8.873), stdev = 0.279
  CI (99.9%): [3.462, 13.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.004 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
Iteration   2: 3.147 ±(99.9%) 0.005 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.121 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.087, 3.121, 3.147), stdev = 0.031
  CI (99.9%): [2.561, 3.681] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
Iteration   3: 3.203 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (3.035, 3.101, 3.203), stdev = 0.090
  CI (99.9%): [1.467, 4.734] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.436 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.003 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.131 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.119, 3.131, 3.147), stdev = 0.014
  CI (99.9%): [2.872, 3.391] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.795 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.005 ms/op
Iteration   1: 3.698 ±(99.9%) 0.007 ms/op
Iteration   2: 3.641 ±(99.9%) 0.009 ms/op
Iteration   3: 3.670 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.670 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.641, 3.670, 3.698), stdev = 0.029
  CI (99.9%): [3.145, 4.195] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.517 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 18.679 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   6.033 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 18.831 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.219 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  14.565 ms/op
                 createUser·p0.9999: 27.184 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305581
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23904 
    [ 2.500,  5.000) = 276461 
    [ 5.000,  7.500) = 4410 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.497 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     28.113 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.748 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  10.120 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 21.774 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.360 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 22.700 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315451
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24830 
    [ 2.500,  5.000) = 287461 
    [ 5.000,  7.500) = 2619 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     11.243 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.933 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 7.771 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
Iteration   1: 3.163 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.837 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  18.245 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.953 ms/op
                 getUser·p0.9999: 22.327 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  13.008 ms/op
                 getUser·p0.9999: 22.511 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301017
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16912 
    [ 2.500,  5.000) = 277324 
    [ 5.000,  7.500) = 5933 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     16.940 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 8.795 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.011 ms/op
Iteration   1: 3.680 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.602 ms/op
                 listUser·p0.9999: 20.422 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.837 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.007 ms/op
                 listUser·p0.9999: 17.738 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255376
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 246522 
    [ 5.000,  7.500) = 7079 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     19.346 ms/op
     p(99.9990) =     20.706 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.587 ± 9.637  ops/ms
ClientPb.existUser                       thrpt       3  10.537 ± 3.793  ops/ms
ClientPb.getUser                         thrpt       3   9.944 ± 0.296  ops/ms
ClientPb.listUser                        thrpt       3   8.558 ± 5.096  ops/ms
ClientPb.createUser                       avgt       3   3.121 ± 0.560   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 1.634   ms/op
ClientPb.getUser                          avgt       3   3.131 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   3.670 ± 0.525   ms/op
ClientPb.createUser                     sample  305581   3.141 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.497           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.821           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.344           ms/op
ClientPb.existUser                      sample  315451   3.041 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.243           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.053           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.364           ms/op
ClientPb.getUser                        sample  301017   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.002           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.217           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.167           ms/op
ClientPb.listUser                       sample  255376   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.501           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.346           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.037           ms/op
