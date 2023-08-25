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
# Warmup Iteration   1: 2.540 ops/ms
# Warmup Iteration   2: 5.999 ops/ms
# Warmup Iteration   3: 9.059 ops/ms
Iteration   1: 9.575 ops/ms
Iteration   2: 9.665 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.685 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (9.575, 9.685, 9.816), stdev = 0.122
  CI (99.9%): [7.467, 11.904] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 8.574 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.454 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (10.352, 10.454, 10.538), stdev = 0.094
  CI (99.9%): [8.731, 12.176] (assumes normal distribution)


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
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 9.086 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 8.994 ops/ms
Iteration   2: 9.741 ops/ms
Iteration   3: 9.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.491 ±(99.9%) 7.853 ops/ms [Average]
  (min, avg, max) = (8.994, 9.491, 9.741), stdev = 0.430
  CI (99.9%): [1.638, 17.345] (assumes normal distribution)


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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 7.822 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 8.230 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.337 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (8.230, 8.337, 8.439), stdev = 0.104
  CI (99.9%): [6.432, 10.243] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.279 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.002 ms/op
Iteration   1: 3.305 ±(99.9%) 0.004 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.251 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.222, 3.260, 3.305), stdev = 0.042
  CI (99.9%): [2.493, 4.027] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.121 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.002 ms/op
Iteration   1: 3.195 ±(99.9%) 0.004 ms/op
Iteration   2: 3.053 ±(99.9%) 0.001 ms/op
Iteration   3: 3.097 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.115 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.053, 3.115, 3.195), stdev = 0.072
  CI (99.9%): [1.793, 4.437] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.663 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.002 ms/op
Iteration   1: 3.303 ±(99.9%) 0.002 ms/op
Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
Iteration   3: 3.295 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.280 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.241, 3.280, 3.303), stdev = 0.034
  CI (99.9%): [2.661, 3.898] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.822 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.005 ms/op
Iteration   1: 3.803 ±(99.9%) 0.005 ms/op
Iteration   2: 3.869 ±(99.9%) 0.007 ms/op
Iteration   3: 3.836 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.836 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.803, 3.836, 3.869), stdev = 0.033
  CI (99.9%): [3.234, 4.438] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.363 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  14.246 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 3.188 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  16.706 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 19.508 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295834
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18406 
    [ 2.500,  5.000) = 269842 
    [ 5.000,  7.500) = 6198 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     23.994 ms/op
     p(99.9990) =     26.117 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.307 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 18.281 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.776 ms/op
                 existUser·p0.9999: 22.918 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.184 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   6.970 ms/op
                 existUser·p0.999:  16.122 ms/op
                 existUser·p0.9999: 21.068 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304384
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21279 
    [ 2.500,  5.000) = 276785 
    [ 5.000,  7.500) = 4966 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     13.963 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.778 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.320 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.010 ms/op
Iteration   1: 3.374 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  16.784 ms/op
                 getUser·p0.9999: 20.432 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  12.932 ms/op
                 getUser·p0.9999: 23.589 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  13.638 ms/op
                 getUser·p0.9999: 23.118 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291404
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22643 
    [ 2.500,  5.000) = 259374 
    [ 5.000,  7.500) = 7607 
    [ 7.500, 10.000) = 1350 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.601 ms/op
     p(99.9900) =     23.064 ms/op
     p(99.9990) =     23.938 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 9.547 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.014 ms/op
Iteration   1: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.155 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 3.759 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  12.534 ms/op
                 listUser·p0.9999: 16.325 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252987
  mean =      3.794 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 243075 
    [ 5.000,  7.500) = 7079 
    [ 7.500, 10.000) = 1985 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     24.934 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.685 ± 2.218  ops/ms
ClientPb.existUser                       thrpt       3  10.454 ± 1.722  ops/ms
ClientPb.getUser                         thrpt       3   9.491 ± 7.853  ops/ms
ClientPb.listUser                        thrpt       3   8.337 ± 1.906  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.767   ms/op
ClientPb.existUser                        avgt       3   3.115 ± 1.322   ms/op
ClientPb.getUser                          avgt       3   3.280 ± 0.619   ms/op
ClientPb.listUser                         avgt       3   3.836 ± 0.602   ms/op
ClientPb.createUser                     sample  295834   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.502           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.647           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.994           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.247           ms/op
ClientPb.existUser                      sample  304384   3.151 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.001           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.963           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.052           ms/op
ClientPb.getUser                        sample  291404   3.291 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.601           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.064           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.281           ms/op
ClientPb.listUser                       sample  252987   3.794 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.479           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.002           ms/op
