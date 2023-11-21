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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 11.865 ops/ms
# Warmup Iteration   3: 12.346 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.655 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (12.549, 12.655, 12.774), stdev = 0.113
  CI (99.9%): [10.594, 14.715] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.653 ops/ms
# Warmup Iteration   2: 13.034 ops/ms
# Warmup Iteration   3: 13.021 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 12.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.918 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (12.893, 12.918, 12.934), stdev = 0.022
  CI (99.9%): [12.516, 13.320] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ops/ms
# Warmup Iteration   2: 12.318 ops/ms
# Warmup Iteration   3: 12.402 ops/ms
Iteration   1: 12.471 ops/ms
Iteration   2: 12.595 ops/ms
Iteration   3: 12.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.547 ±(99.9%) 1.211 ops/ms [Average]
  (min, avg, max) = (12.471, 12.547, 12.595), stdev = 0.066
  CI (99.9%): [11.336, 13.758] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.793 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.196 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.345 ±(99.9%) 2.471 ops/ms [Average]
  (min, avg, max) = (10.196, 10.345, 10.459), stdev = 0.135
  CI (99.9%): [7.874, 12.816] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.551, 2.554, 2.558), stdev = 0.003
  CI (99.9%): [2.495, 2.613] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.003 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.504 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.489, 2.504, 2.512), stdev = 0.013
  CI (99.9%): [2.265, 2.743] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.524, 2.536, 2.555), stdev = 0.016
  CI (99.9%): [2.240, 2.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (2.989, 2.994, 2.996), stdev = 0.004
  CI (99.9%): [2.916, 3.072] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.744 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  11.778 ms/op
                 createUser·p0.9999: 14.533 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 15.440 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.558 ms/op
                 createUser·p0.9999: 11.181 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377615
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 178403 
    [ 2.500,  3.750) = 194576 
    [ 3.750,  5.000) = 3541 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      9.329 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     15.716 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.957 ms/op
                 existUser·p0.9999: 13.890 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.271 ms/op
                 existUser·p0.9999: 16.061 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  8.856 ms/op
                 existUser·p0.9999: 11.354 ms/op
                 existUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388788
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 190533 
    [ 2.500,  3.750) = 194335 
    [ 3.750,  5.000) = 2689 
    [ 5.000,  6.250) = 671 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.343 ms/op
     p(99.9900) =     14.130 ms/op
     p(99.9990) =     16.346 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.783 ms/op
                 getUser·p0.999:  12.104 ms/op
                 getUser·p0.9999: 15.190 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  10.700 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  9.438 ms/op
                 getUser·p0.9999: 10.966 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379141
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 184741 
    [ 2.500,  3.750) = 188161 
    [ 3.750,  5.000) = 4559 
    [ 5.000,  6.250) = 910 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     14.325 ms/op
     p(99.9990) =     15.568 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.856 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.780 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   2: 3.069 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  10.509 ms/op
                 listUser·p0.9999: 16.914 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.498 ms/op
                 listUser·p0.999:  9.452 ms/op
                 listUser·p0.9999: 10.953 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313342
  mean =      3.061 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 83084 
    [ 2.500,  3.750) = 187283 
    [ 3.750,  5.000) = 35117 
    [ 5.000,  6.250) = 6420 
    [ 6.250,  7.500) = 710 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     17.326 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.655 ± 2.061  ops/ms
ClientPb.existUser                       thrpt       3  12.918 ± 0.402  ops/ms
ClientPb.getUser                         thrpt       3  12.547 ± 1.211  ops/ms
ClientPb.listUser                        thrpt       3  10.345 ± 2.471  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.059   ms/op
ClientPb.existUser                        avgt       3   2.504 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.296   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.078   ms/op
ClientPb.createUser                     sample  377615   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.329           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.400           ms/op
ClientPb.existUser                      sample  388788   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.343           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.138           ms/op
ClientPb.getUser                        sample  379141   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.700           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.519           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.325           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  313342   3.061 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.904           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.647           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.433           ms/op
