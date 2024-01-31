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
# Warmup Iteration   1: 5.168 ops/ms
# Warmup Iteration   2: 12.121 ops/ms
# Warmup Iteration   3: 12.342 ops/ms
Iteration   1: 12.489 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.703 ±(99.9%) 3.448 ops/ms [Average]
  (min, avg, max) = (12.489, 12.703, 12.847), stdev = 0.189
  CI (99.9%): [9.255, 16.150] (assumes normal distribution)


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
# Warmup Iteration   1: 8.169 ops/ms
# Warmup Iteration   2: 12.798 ops/ms
# Warmup Iteration   3: 12.989 ops/ms
Iteration   1: 13.072 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 13.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.058 ±(99.9%) 0.454 ops/ms [Average]
  (min, avg, max) = (13.029, 13.058, 13.073), stdev = 0.025
  CI (99.9%): [12.604, 13.512] (assumes normal distribution)


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
# Warmup Iteration   1: 8.061 ops/ms
# Warmup Iteration   2: 12.633 ops/ms
# Warmup Iteration   3: 12.722 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.628 ops/ms
Iteration   3: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.656 ±(99.9%) 0.543 ops/ms [Average]
  (min, avg, max) = (12.628, 12.656, 12.687), stdev = 0.030
  CI (99.9%): [12.113, 13.199] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.975 ops/ms
# Warmup Iteration   2: 10.332 ops/ms
# Warmup Iteration   3: 10.756 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.734 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (10.691, 10.734, 10.771), stdev = 0.040
  CI (99.9%): [10.002, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.531, 2.548, 2.573), stdev = 0.022
  CI (99.9%): [2.143, 2.953] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.428 ±(99.9%) 0.003 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.428, 2.435, 2.442), stdev = 0.007
  CI (99.9%): [2.311, 2.558] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.532 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.523, 2.532, 2.544), stdev = 0.011
  CI (99.9%): [2.332, 2.731] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
Iteration   1: 2.982 ±(99.9%) 0.003 ms/op
Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.974, 2.988, 3.008), stdev = 0.018
  CI (99.9%): [2.664, 3.312] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  7.328 ms/op
                 createUser·p0.9999: 15.041 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.498 ms/op
                 createUser·p0.999:  6.526 ms/op
                 createUser·p0.9999: 11.568 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  8.680 ms/op
                 createUser·p0.9999: 10.338 ms/op
                 createUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386183
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 188018 
    [ 2.500,  3.750) = 194076 
    [ 3.750,  5.000) = 3038 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.648 ms/op
     p(99.9900) =     12.671 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  9.036 ms/op
                 existUser·p0.9999: 13.932 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.642 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 12.540 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.179 ms/op
                 existUser·p0.9999: 12.194 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381881
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 184913 
    [ 2.500,  3.750) = 193832 
    [ 3.750,  5.000) = 2233 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      8.187 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.110 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  8.384 ms/op
                 getUser·p0.9999: 14.401 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  6.043 ms/op
                 getUser·p0.9999: 10.749 ms/op
                 getUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386005
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 191785 
    [ 2.500,  3.750) = 189918 
    [ 3.750,  5.000) = 3478 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.239 ms/op
     p(99.9900) =     13.540 ms/op
     p(99.9990) =     14.814 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.968 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.009 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.856 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.962 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313813
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 84400 
    [ 2.500,  3.750) = 186715 
    [ 3.750,  5.000) = 35169 
    [ 5.000,  6.250) = 5956 
    [ 6.250,  7.500) = 809 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.489 ms/op
     p(99.9900) =     11.583 ms/op
     p(99.9990) =     12.274 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.703 ± 3.448  ops/ms
ClientPb.existUser                       thrpt       3  13.058 ± 0.454  ops/ms
ClientPb.getUser                         thrpt       3  12.656 ± 0.543  ops/ms
ClientPb.listUser                        thrpt       3  10.734 ± 0.732  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.405   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.123   ms/op
ClientPb.getUser                          avgt       3   2.532 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.324   ms/op
ClientPb.createUser                     sample  386183   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.603           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.671           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.811           ms/op
ClientPb.existUser                      sample  381881   2.511 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.609           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.187           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  386005   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.785           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.239           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.540           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.499           ms/op
ClientPb.listUser                       sample  313813   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.489           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
