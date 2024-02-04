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
# Warmup Iteration   1: 4.628 ops/ms
# Warmup Iteration   2: 11.961 ops/ms
# Warmup Iteration   3: 12.181 ops/ms
Iteration   1: 12.425 ops/ms
Iteration   2: 12.463 ops/ms
Iteration   3: 12.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.489 ±(99.9%) 1.483 ops/ms [Average]
  (min, avg, max) = (12.425, 12.489, 12.581), stdev = 0.081
  CI (99.9%): [11.006, 13.973] (assumes normal distribution)


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
# Warmup Iteration   1: 8.219 ops/ms
# Warmup Iteration   2: 12.836 ops/ms
# Warmup Iteration   3: 12.872 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 12.939 ops/ms
Iteration   3: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.926 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (12.870, 12.926, 12.969), stdev = 0.051
  CI (99.9%): [11.993, 13.859] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.551 ops/ms
# Warmup Iteration   2: 12.560 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.579 ops/ms
Iteration   3: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.682 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (12.579, 12.682, 12.752), stdev = 0.090
  CI (99.9%): [11.031, 14.333] (assumes normal distribution)


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
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 10.505 ops/ms
# Warmup Iteration   3: 10.608 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.624 ±(99.9%) 1.883 ops/ms [Average]
  (min, avg, max) = (10.505, 10.624, 10.685), stdev = 0.103
  CI (99.9%): [8.741, 12.507] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.003 ms/op
Iteration   1: 2.570 ±(99.9%) 0.005 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.533, 2.546, 2.570), stdev = 0.020
  CI (99.9%): [2.175, 2.917] (assumes normal distribution)


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.003 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.495 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.484, 2.495, 2.512), stdev = 0.015
  CI (99.9%): [2.225, 2.766] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.497, 2.502, 2.505), stdev = 0.004
  CI (99.9%): [2.429, 2.574] (assumes normal distribution)


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.007 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.998, 3.020, 3.035), stdev = 0.020
  CI (99.9%): [2.663, 3.376] (assumes normal distribution)


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.974 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.216 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379723
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 185055 
    [ 2.500,  3.750) = 190403 
    [ 3.750,  5.000) = 3288 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.243 ms/op
     p(99.9900) =     13.583 ms/op
     p(99.9990) =     14.113 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.121 ms/op
                 existUser·p0.9999: 13.257 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  8.149 ms/op
                 existUser·p0.9999: 12.569 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.171 ms/op
                 existUser·p0.999:  7.957 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384437
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189837 
    [ 2.500,  3.750) = 189526 
    [ 3.750,  5.000) = 4153 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.894 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  5.699 ms/op
                 getUser·p0.9999: 13.488 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  9.668 ms/op
                 getUser·p0.9999: 13.750 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  8.227 ms/op
                 getUser·p0.9999: 11.485 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379642
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 187181 
    [ 2.500,  3.750) = 188609 
    [ 3.750,  5.000) = 3018 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      6.095 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.477 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 14.615 ms/op
                 listUser·p1.00:   15.761 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.961 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319101
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 93298 
    [ 2.500,  3.750) = 187204 
    [ 3.750,  5.000) = 31243 
    [ 5.000,  6.250) = 5772 
    [ 6.250,  7.500) = 806 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.288 ms/op
     p(99.9900) =     13.144 ms/op
     p(99.9990) =     15.460 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.489 ± 1.483  ops/ms
ClientPb.existUser                       thrpt       3  12.926 ± 0.933  ops/ms
ClientPb.getUser                         thrpt       3  12.682 ± 1.651  ops/ms
ClientPb.listUser                        thrpt       3  10.624 ± 1.883  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.371   ms/op
ClientPb.existUser                        avgt       3   2.495 ± 0.270   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.072   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.356   ms/op
ClientPb.createUser                     sample  379723   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.786           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.243           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.583           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  384437   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.901           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.499           ms/op
ClientPb.getUser                        sample  379642   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.678           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.095           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.680           ms/op
ClientPb.listUser                       sample  319101   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.288           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.761           ms/op
