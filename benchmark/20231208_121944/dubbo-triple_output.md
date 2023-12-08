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
# Warmup Iteration   1: 4.270 ops/ms
# Warmup Iteration   2: 12.020 ops/ms
# Warmup Iteration   3: 12.426 ops/ms
Iteration   1: 12.642 ops/ms
Iteration   2: 12.690 ops/ms
Iteration   3: 12.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.634 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (12.571, 12.634, 12.690), stdev = 0.060
  CI (99.9%): [11.539, 13.729] (assumes normal distribution)


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
# Warmup Iteration   1: 8.028 ops/ms
# Warmup Iteration   2: 12.798 ops/ms
# Warmup Iteration   3: 12.907 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 12.924 ops/ms
Iteration   3: 12.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.939 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (12.923, 12.939, 12.969), stdev = 0.026
  CI (99.9%): [12.462, 13.416] (assumes normal distribution)


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
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.683 ops/ms
Iteration   1: 12.947 ops/ms
Iteration   2: 12.686 ops/ms
Iteration   3: 12.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.816 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (12.686, 12.816, 12.947), stdev = 0.131
  CI (99.9%): [10.434, 15.197] (assumes normal distribution)


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
# Warmup Iteration   1: 6.521 ops/ms
# Warmup Iteration   2: 10.386 ops/ms
# Warmup Iteration   3: 10.639 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.579 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (10.441, 10.579, 10.680), stdev = 0.124
  CI (99.9%): [8.319, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.003 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.511, 2.528, 2.541), stdev = 0.015
  CI (99.9%): [2.251, 2.805] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.425, 2.443, 2.463), stdev = 0.019
  CI (99.9%): [2.092, 2.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.451, 2.465, 2.480), stdev = 0.014
  CI (99.9%): [2.206, 2.723] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.726 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.050 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (3.025, 3.050, 3.085), stdev = 0.031
  CI (99.9%): [2.479, 3.622] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  11.031 ms/op
                 createUser·p0.9999: 13.768 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 13.011 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.927 ms/op
                 createUser·p0.9999: 10.855 ms/op
                 createUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382372
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 185509 
    [ 2.500,  3.750) = 193321 
    [ 3.750,  5.000) = 2740 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.365 ms/op
     p(99.9990) =     14.009 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.301 ms/op
                 existUser·p0.999:  5.638 ms/op
                 existUser·p0.9999: 14.302 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  7.086 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 11.342 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390041
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 190905 
    [ 2.500,  3.750) = 196553 
    [ 3.750,  5.000) = 1929 
    [ 5.000,  6.250) = 232 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.816 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.218 ms/op
                 getUser·p0.9999: 17.071 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.970 ms/op
                 getUser·p0.999:  9.459 ms/op
                 getUser·p0.9999: 12.800 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.581 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  6.768 ms/op
                 getUser·p0.9999: 11.602 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384607
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 192058 
    [ 2.500,  3.750) = 188071 
    [ 3.750,  5.000) = 3519 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.159 ms/op
     p(99.9900) =     14.329 ms/op
     p(99.9990) =     17.475 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.328 ms/op
                 listUser·p0.9999: 11.063 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.364 ms/op
                 listUser·p0.9999: 10.918 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.282 ms/op
                 listUser·p0.9999: 12.985 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318896
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 91263 
    [ 2.500,  3.750) = 189472 
    [ 3.750,  5.000) = 31291 
    [ 5.000,  6.250) = 5522 
    [ 6.250,  7.500) = 587 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.783 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     14.007 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.634 ± 1.095  ops/ms
ClientPb.existUser                       thrpt       3  12.939 ± 0.477  ops/ms
ClientPb.getUser                         thrpt       3  12.816 ± 2.381  ops/ms
ClientPb.listUser                        thrpt       3  10.579 ± 2.259  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.277   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.351   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   3.050 ± 0.572   ms/op
ClientPb.createUser                     sample  382372   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.973           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.929           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  390041   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.967           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.250           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.712           ms/op
ClientPb.getUser                        sample  384607   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.581           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.159           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.329           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.121           ms/op
ClientPb.listUser                       sample  318896   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.783           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.173           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.533           ms/op
