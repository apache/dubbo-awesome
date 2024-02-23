# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.022 ops/ms
# Warmup Iteration   2: 11.977 ops/ms
# Warmup Iteration   3: 12.348 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.699 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.761 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (12.699, 12.761, 12.846), stdev = 0.076
  CI (99.9%): [11.369, 14.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.196 ops/ms
# Warmup Iteration   2: 13.103 ops/ms
# Warmup Iteration   3: 13.220 ops/ms
Iteration   1: 13.154 ops/ms
Iteration   2: 13.317 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.243 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (13.154, 13.243, 13.317), stdev = 0.082
  CI (99.9%): [11.738, 14.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.174 ops/ms
# Warmup Iteration   2: 12.398 ops/ms
# Warmup Iteration   3: 12.874 ops/ms
Iteration   1: 12.951 ops/ms
Iteration   2: 12.582 ops/ms
Iteration   3: 12.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.826 ±(99.9%) 3.851 ops/ms [Average]
  (min, avg, max) = (12.582, 12.826, 12.951), stdev = 0.211
  CI (99.9%): [8.975, 16.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.572 ops/ms
# Warmup Iteration   2: 10.415 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.674 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.616, 10.674, 10.738), stdev = 0.061
  CI (99.9%): [9.558, 11.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
Iteration   3: 2.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.526 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.504, 2.526, 2.545), stdev = 0.020
  CI (99.9%): [2.158, 2.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.436 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.436, 2.448, 2.455), stdev = 0.010
  CI (99.9%): [2.257, 2.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.458, 2.464, 2.468), stdev = 0.006
  CI (99.9%): [2.358, 2.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.991, 3.005, 3.013), stdev = 0.012
  CI (99.9%): [2.785, 3.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.280 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  7.294 ms/op
                 createUser·p0.9999: 13.353 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  6.317 ms/op
                 createUser·p0.9999: 11.987 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 10.870 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386281
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 186369 
    [ 2.500,  3.750) = 196277 
    [ 3.750,  5.000) = 2921 
    [ 5.000,  6.250) = 257 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     13.598 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.593 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  8.161 ms/op
                 existUser·p0.9999: 13.480 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  7.094 ms/op
                 existUser·p0.9999: 11.696 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392223
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 192821 
    [ 2.500,  3.750) = 195470 
    [ 3.750,  5.000) = 2821 
    [ 5.000,  6.250) = 589 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      7.788 ms/op
     p(99.9900) =     13.497 ms/op
     p(99.9990) =     13.952 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  11.811 ms/op
                 getUser·p0.9999: 14.004 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  5.928 ms/op
                 getUser·p0.9999: 12.407 ms/op
                 getUser·p1.00:   12.616 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.844 ms/op
                 getUser·p0.999:  8.104 ms/op
                 getUser·p0.9999: 13.306 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383315
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 190069 
    [ 2.500,  3.750) = 187175 
    [ 3.750,  5.000) = 4620 
    [ 5.000,  6.250) = 928 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.673 ms/op
     p(99.9900) =     13.462 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.638 ms/op
                 listUser·p0.9999: 11.234 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.209 ms/op
                 listUser·p0.9999: 12.872 ms/op
                 listUser·p1.00:   14.189 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.682 ms/op
                 listUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320124
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 94764 
    [ 2.500,  3.750) = 186829 
    [ 3.750,  5.000) = 31281 
    [ 5.000,  6.250) = 5617 
    [ 6.250,  7.500) = 849 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.779 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     13.470 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.761 ± 1.392  ops/ms
ClientPb.existUser                       thrpt       3  13.243 ± 1.505  ops/ms
ClientPb.getUser                         thrpt       3  12.826 ± 3.851  ops/ms
ClientPb.listUser                        thrpt       3  10.674 ± 1.116  ops/ms
ClientPb.createUser                       avgt       3   2.526 ± 0.368   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.191   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.106   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.219   ms/op
ClientPb.createUser                     sample  386281   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.795           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.898           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.698           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  392223   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.788           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.497           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  383315   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.785           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.673           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.462           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  320124   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
