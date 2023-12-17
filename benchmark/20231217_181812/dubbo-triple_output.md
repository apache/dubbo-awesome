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
# Warmup Iteration   1: 4.934 ops/ms
# Warmup Iteration   2: 11.766 ops/ms
# Warmup Iteration   3: 12.300 ops/ms
Iteration   1: 12.599 ops/ms
Iteration   2: 12.592 ops/ms
Iteration   3: 12.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.581 ±(99.9%) 0.464 ops/ms [Average]
  (min, avg, max) = (12.552, 12.581, 12.599), stdev = 0.025
  CI (99.9%): [12.117, 13.045] (assumes normal distribution)


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
# Warmup Iteration   1: 7.975 ops/ms
# Warmup Iteration   2: 12.981 ops/ms
# Warmup Iteration   3: 12.771 ops/ms
Iteration   1: 12.852 ops/ms
Iteration   2: 12.875 ops/ms
Iteration   3: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.827 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (12.752, 12.827, 12.875), stdev = 0.066
  CI (99.9%): [11.627, 14.026] (assumes normal distribution)


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
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 12.481 ops/ms
# Warmup Iteration   3: 12.789 ops/ms
Iteration   1: 12.763 ops/ms
Iteration   2: 12.672 ops/ms
Iteration   3: 12.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.734 ±(99.9%) 0.983 ops/ms [Average]
  (min, avg, max) = (12.672, 12.734, 12.768), stdev = 0.054
  CI (99.9%): [11.752, 13.717] (assumes normal distribution)


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
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 10.509 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.752 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.742 ±(99.9%) 0.347 ops/ms [Average]
  (min, avg, max) = (10.720, 10.742, 10.754), stdev = 0.019
  CI (99.9%): [10.395, 11.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.483 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (2.442, 2.483, 2.504), stdev = 0.035
  CI (99.9%): [1.839, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.003 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.431, 2.438, 2.444), stdev = 0.007
  CI (99.9%): [2.313, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.463, 2.479, 2.495), stdev = 0.016
  CI (99.9%): [2.196, 2.763] (assumes normal distribution)


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
Iteration   3: 2.975 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.960, 2.972, 2.981), stdev = 0.011
  CI (99.9%): [2.775, 3.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.927 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.664 ms/op
                 createUser·p0.999:  9.348 ms/op
                 createUser·p0.9999: 12.999 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.926 ms/op
                 createUser·p0.9999: 10.312 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377046
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 180929 
    [ 2.500,  3.750) = 191437 
    [ 3.750,  5.000) = 3661 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.225 ms/op
     p(99.9990) =     14.597 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.045 ms/op
                 existUser·p0.9999: 15.091 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  9.074 ms/op
                 existUser·p0.9999: 12.586 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.179 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385770
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 188705 
    [ 2.500,  3.750) = 193965 
    [ 3.750,  5.000) = 2363 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.618 ms/op
     p(99.9900) =     13.842 ms/op
     p(99.9990) =     15.682 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  10.655 ms/op
                 getUser·p0.9999: 14.142 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 12.321 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 11.163 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383753
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 190087 
    [ 2.500,  3.750) = 188552 
    [ 3.750,  5.000) = 3718 
    [ 5.000,  6.250) = 903 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      6.382 ms/op
     p(99.9900) =     13.363 ms/op
     p(99.9990) =     14.240 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.560 ms/op
                 listUser·p0.999:  9.334 ms/op
                 listUser·p0.9999: 11.517 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.118 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316566
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 88101 
    [ 2.500,  3.750) = 187887 
    [ 3.750,  5.000) = 33389 
    [ 5.000,  6.250) = 5786 
    [ 6.250,  7.500) = 628 
    [ 7.500,  8.750) = 155 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 203 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.821 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.581 ± 0.464  ops/ms
ClientPb.existUser                       thrpt       3  12.827 ± 1.199  ops/ms
ClientPb.getUser                         thrpt       3  12.734 ± 0.983  ops/ms
ClientPb.listUser                        thrpt       3  10.742 ± 0.347  ops/ms
ClientPb.createUser                       avgt       3   2.483 ± 0.644   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.284   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.197   ms/op
ClientPb.createUser                     sample  377046   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.805           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.225           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  385770   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.695           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.618           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.842           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.958           ms/op
ClientPb.getUser                        sample  383753   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.382           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.363           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.303           ms/op
ClientPb.listUser                       sample  316566   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.854           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.895           ms/op
