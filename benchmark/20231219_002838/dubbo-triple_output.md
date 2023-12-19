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
# Warmup Iteration   1: 4.011 ops/ms
# Warmup Iteration   2: 11.839 ops/ms
# Warmup Iteration   3: 12.599 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.520 ops/ms
Iteration   3: 12.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.555 ±(99.9%) 0.755 ops/ms [Average]
  (min, avg, max) = (12.520, 12.555, 12.601), stdev = 0.041
  CI (99.9%): [11.800, 13.310] (assumes normal distribution)


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
# Warmup Iteration   1: 8.040 ops/ms
# Warmup Iteration   2: 13.171 ops/ms
# Warmup Iteration   3: 13.108 ops/ms
Iteration   1: 13.210 ops/ms
Iteration   2: 13.153 ops/ms
Iteration   3: 13.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.182 ±(99.9%) 0.527 ops/ms [Average]
  (min, avg, max) = (13.153, 13.182, 13.210), stdev = 0.029
  CI (99.9%): [12.655, 13.710] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.849 ops/ms
# Warmup Iteration   2: 12.603 ops/ms
# Warmup Iteration   3: 12.874 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 13.046 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.967 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (12.896, 12.967, 13.046), stdev = 0.075
  CI (99.9%): [11.592, 14.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.811 ops/ms
# Warmup Iteration   2: 10.533 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.648 ±(99.9%) 0.812 ops/ms [Average]
  (min, avg, max) = (10.603, 10.648, 10.691), stdev = 0.044
  CI (99.9%): [9.837, 11.460] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (2.512, 2.540, 2.577), stdev = 0.034
  CI (99.9%): [1.928, 3.152] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.632 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.003 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.445, 2.452, 2.456), stdev = 0.006
  CI (99.9%): [2.336, 2.567] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
Iteration   3: 2.498 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.459, 2.486, 2.501), stdev = 0.023
  CI (99.9%): [2.060, 2.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.969, 2.975, 2.981), stdev = 0.006
  CI (99.9%): [2.861, 3.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  11.980 ms/op
                 createUser·p0.9999: 16.126 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  6.702 ms/op
                 createUser·p0.9999: 12.518 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  7.093 ms/op
                 createUser·p0.9999: 10.815 ms/op
                 createUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386392
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 188390 
    [ 2.500,  3.750) = 194152 
    [ 3.750,  5.000) = 3064 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      7.160 ms/op
     p(99.9900) =     14.516 ms/op
     p(99.9990) =     16.274 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  5.779 ms/op
                 existUser·p0.9999: 14.379 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.660 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391939
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 197996 
    [ 2.500,  3.750) = 190031 
    [ 3.750,  5.000) = 3045 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     13.520 ms/op
     p(99.9990) =     14.635 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  9.887 ms/op
                 getUser·p0.9999: 14.322 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.713 ms/op
                 getUser·p0.9999: 13.700 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385826
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 193347 
    [ 2.500,  3.750) = 187702 
    [ 3.750,  5.000) = 3724 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.686 ms/op
     p(99.9900) =     13.917 ms/op
     p(99.9990) =     14.664 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.656 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 12.501 ms/op
                 listUser·p1.00:   14.221 ms/op

Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320213
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 94799 
    [ 2.500,  3.750) = 187376 
    [ 3.750,  5.000) = 31257 
    [ 5.000,  6.250) = 5383 
    [ 6.250,  7.500) = 557 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 308 
    [10.000, 11.250) = 179 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     11.583 ms/op
     p(99.9990) =     13.415 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.555 ± 0.755  ops/ms
ClientPb.existUser                       thrpt       3  13.182 ± 0.527  ops/ms
ClientPb.getUser                         thrpt       3  12.967 ± 1.376  ops/ms
ClientPb.listUser                        thrpt       3  10.648 ± 0.812  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.612   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.115   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.114   ms/op
ClientPb.createUser                     sample  386392   2.482 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.160           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.516           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.368           ms/op
ClientPb.existUser                      sample  391939   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.635           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.355           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.520           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.844           ms/op
ClientPb.getUser                        sample  385826   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.686           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.917           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  320213   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.701           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
