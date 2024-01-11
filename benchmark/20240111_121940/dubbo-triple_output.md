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
# Warmup Iteration   1: 4.639 ops/ms
# Warmup Iteration   2: 11.874 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.412 ops/ms
Iteration   2: 12.429 ops/ms
Iteration   3: 12.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.441 ±(99.9%) 0.676 ops/ms [Average]
  (min, avg, max) = (12.412, 12.441, 12.483), stdev = 0.037
  CI (99.9%): [11.765, 13.118] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.256 ops/ms
# Warmup Iteration   2: 12.951 ops/ms
# Warmup Iteration   3: 12.805 ops/ms
Iteration   1: 12.755 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.835 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (12.755, 12.835, 12.911), stdev = 0.078
  CI (99.9%): [11.415, 14.255] (assumes normal distribution)


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
# Warmup Iteration   1: 7.926 ops/ms
# Warmup Iteration   2: 12.228 ops/ms
# Warmup Iteration   3: 12.293 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.519 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.608 ±(99.9%) 1.713 ops/ms [Average]
  (min, avg, max) = (12.519, 12.608, 12.706), stdev = 0.094
  CI (99.9%): [10.895, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 6.603 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.551 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.509 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (10.481, 10.509, 10.551), stdev = 0.037
  CI (99.9%): [9.826, 11.191] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.005 ms/op
Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
Iteration   3: 2.564 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.564, 2.577, 2.588), stdev = 0.012
  CI (99.9%): [2.353, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.475, 2.478, 2.482), stdev = 0.004
  CI (99.9%): [2.407, 2.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.502, 2.508, 2.512), stdev = 0.005
  CI (99.9%): [2.409, 2.607] (assumes normal distribution)


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.005 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.069 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (3.058, 3.069, 3.077), stdev = 0.010
  CI (99.9%): [2.884, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  12.205 ms/op
                 createUser·p0.9999: 13.565 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.585 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.339 ms/op
                 createUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371943
  mean =      2.578 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 176424 
    [ 2.500,  3.750) = 190846 
    [ 3.750,  5.000) = 3681 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.292 ms/op
     p(99.9900) =     13.219 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.318 ms/op
                 existUser·p0.9999: 13.709 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.713 ms/op
                 existUser·p0.999:  6.192 ms/op
                 existUser·p0.9999: 12.184 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  8.665 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388671
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 192327 
    [ 2.500,  3.750) = 192845 
    [ 3.750,  5.000) = 2684 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 150 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.222 ms/op
     p(99.9900) =     12.772 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  11.892 ms/op
                 getUser·p0.9999: 14.192 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  9.931 ms/op
                 getUser·p0.9999: 14.390 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 10.329 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377834
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 185119 
    [ 2.500,  3.750) = 187320 
    [ 3.750,  5.000) = 4116 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.738 ms/op
     p(99.9900) =     13.970 ms/op
     p(99.9990) =     14.957 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.107 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  8.982 ms/op
                 listUser·p0.9999: 10.415 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.956 ms/op
                 listUser·p0.999:  10.568 ms/op
                 listUser·p0.9999: 12.455 ms/op
                 listUser·p1.00:   12.648 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.976 ms/op
                 listUser·p0.9999: 12.976 ms/op
                 listUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309611
  mean =      3.098 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 79050 
    [ 2.500,  3.750) = 184233 
    [ 3.750,  5.000) = 36966 
    [ 5.000,  6.250) = 7475 
    [ 6.250,  7.500) = 1061 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      9.833 ms/op
     p(99.9900) =     12.633 ms/op
     p(99.9990) =     13.181 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.441 ± 0.676  ops/ms
ClientPb.existUser                       thrpt       3  12.835 ± 1.420  ops/ms
ClientPb.getUser                         thrpt       3  12.608 ± 1.713  ops/ms
ClientPb.listUser                        thrpt       3  10.509 ± 0.683  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.071   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   3.069 ± 0.185   ms/op
ClientPb.createUser                     sample  371943   2.578 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.292           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.219           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.696           ms/op
ClientPb.existUser                      sample  388671   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.772           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.041           ms/op
ClientPb.getUser                        sample  377834   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.738           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.970           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  309611   3.098 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.833           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.633           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
