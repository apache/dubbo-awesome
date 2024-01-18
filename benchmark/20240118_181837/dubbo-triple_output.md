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
# Warmup Iteration   1: 5.016 ops/ms
# Warmup Iteration   2: 12.139 ops/ms
# Warmup Iteration   3: 12.266 ops/ms
Iteration   1: 12.612 ops/ms
Iteration   2: 12.580 ops/ms
Iteration   3: 12.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.598 ±(99.9%) 0.292 ops/ms [Average]
  (min, avg, max) = (12.580, 12.598, 12.612), stdev = 0.016
  CI (99.9%): [12.306, 12.890] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.406 ops/ms
# Warmup Iteration   2: 12.937 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 13.283 ops/ms
Iteration   3: 13.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.150 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (13.034, 13.150, 13.283), stdev = 0.125
  CI (99.9%): [10.866, 15.434] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ops/ms
# Warmup Iteration   2: 12.562 ops/ms
# Warmup Iteration   3: 12.793 ops/ms
Iteration   1: 13.004 ops/ms
Iteration   2: 12.816 ops/ms
Iteration   3: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.901 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (12.816, 12.901, 13.004), stdev = 0.095
  CI (99.9%): [11.170, 14.633] (assumes normal distribution)


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
# Warmup Iteration   1: 6.837 ops/ms
# Warmup Iteration   2: 10.740 ops/ms
# Warmup Iteration   3: 10.767 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.724 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (10.634, 10.724, 10.782), stdev = 0.079
  CI (99.9%): [9.280, 12.168] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.523, 2.531, 2.541), stdev = 0.009
  CI (99.9%): [2.366, 2.695] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.434, 2.439, 2.443), stdev = 0.004
  CI (99.9%): [2.358, 2.521] (assumes normal distribution)


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
# Warmup Iteration   1: 3.653 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
Iteration   3: 2.416 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.425 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.412, 2.425, 2.447), stdev = 0.020
  CI (99.9%): [2.069, 2.781] (assumes normal distribution)


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.974, 2.991, 3.018), stdev = 0.024
  CI (99.9%): [2.557, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  11.089 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  9.086 ms/op
                 createUser·p0.9999: 11.688 ms/op
                 createUser·p1.00:   12.091 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  8.376 ms/op
                 createUser·p0.9999: 10.294 ms/op
                 createUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384438
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 186576 
    [ 2.500,  3.750) = 193657 
    [ 3.750,  5.000) = 3182 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     12.576 ms/op
     p(99.9990) =     13.802 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.452 ms/op
                 existUser·p0.9999: 13.614 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.603 ms/op
                 existUser·p0.999:  5.773 ms/op
                 existUser·p0.9999: 13.110 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.301 ms/op
                 existUser·p0.9999: 11.701 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388214
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 194604 
    [ 2.500,  3.750) = 190778 
    [ 3.750,  5.000) = 2000 
    [ 5.000,  6.250) = 323 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      6.983 ms/op
     p(99.9900) =     13.061 ms/op
     p(99.9990) =     14.145 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  5.317 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  9.001 ms/op
                 getUser·p0.9999: 13.471 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 11.143 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384931
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 191655 
    [ 2.500,  3.750) = 188720 
    [ 3.750,  5.000) = 3547 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      6.473 ms/op
     p(99.9900) =     13.345 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
Iteration   1: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.456 ms/op
                 listUser·p0.9999: 10.588 ms/op
                 listUser·p1.00:   10.863 ms/op

Iteration   2: 2.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.652 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 2.937 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.098 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325638
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 102615 
    [ 2.500,  3.750) = 187684 
    [ 3.750,  5.000) = 28487 
    [ 5.000,  6.250) = 5382 
    [ 6.250,  7.500) = 650 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 178 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.366 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.598 ± 0.292  ops/ms
ClientPb.existUser                       thrpt       3  13.150 ± 2.284  ops/ms
ClientPb.getUser                         thrpt       3  12.901 ± 1.731  ops/ms
ClientPb.listUser                        thrpt       3  10.724 ± 1.444  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.165   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.081   ms/op
ClientPb.getUser                          avgt       3   2.425 ± 0.356   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.434   ms/op
ClientPb.createUser                     sample  384438   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.576           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  388214   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.950           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.983           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.061           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  384931   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.473           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  325638   2.945 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.684           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.616           ms/op
