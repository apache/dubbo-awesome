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
# Warmup Iteration   1: 4.302 ops/ms
# Warmup Iteration   2: 11.542 ops/ms
# Warmup Iteration   3: 11.890 ops/ms
Iteration   1: 12.451 ops/ms
Iteration   2: 12.337 ops/ms
Iteration   3: 12.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.376 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (12.337, 12.376, 12.451), stdev = 0.065
  CI (99.9%): [11.198, 13.555] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.851 ops/ms
# Warmup Iteration   2: 12.978 ops/ms
# Warmup Iteration   3: 13.153 ops/ms
Iteration   1: 13.168 ops/ms
Iteration   2: 13.073 ops/ms
Iteration   3: 12.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.062 ±(99.9%) 2.037 ops/ms [Average]
  (min, avg, max) = (12.945, 13.062, 13.168), stdev = 0.112
  CI (99.9%): [11.025, 15.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ops/ms
# Warmup Iteration   2: 12.619 ops/ms
# Warmup Iteration   3: 12.695 ops/ms
Iteration   1: 12.952 ops/ms
Iteration   2: 12.522 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.754 ±(99.9%) 3.959 ops/ms [Average]
  (min, avg, max) = (12.522, 12.754, 12.952), stdev = 0.217
  CI (99.9%): [8.795, 16.713] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.433 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.479 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (10.433, 10.479, 10.551), stdev = 0.063
  CI (99.9%): [9.328, 11.629] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.004 ms/op
Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
Iteration   3: 2.530 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (2.530, 2.549, 2.576), stdev = 0.024
  CI (99.9%): [2.107, 2.990] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.003 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.454, 2.471, 2.486), stdev = 0.016
  CI (99.9%): [2.175, 2.768] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (2.497, 2.536, 2.585), stdev = 0.045
  CI (99.9%): [1.715, 3.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.998, 3.016, 3.037), stdev = 0.020
  CI (99.9%): [2.656, 3.375] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  11.857 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  9.703 ms/op
                 createUser·p0.9999: 12.897 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 11.141 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379639
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 180460 
    [ 2.500,  3.750) = 194810 
    [ 3.750,  5.000) = 3263 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 136 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.640 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     13.881 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.674 ms/op
                 existUser·p0.9999: 14.301 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.143 ms/op
                 existUser·p0.9999: 14.367 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  8.112 ms/op
                 existUser·p0.9999: 12.106 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392582
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 193979 
    [ 2.500,  3.750) = 195106 
    [ 3.750,  5.000) = 2549 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =     14.147 ms/op
     p(99.9990) =     14.748 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  11.848 ms/op
                 getUser·p0.9999: 15.018 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  10.079 ms/op
                 getUser·p0.9999: 15.683 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 11.972 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377083
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 183810 
    [ 2.500,  3.750) = 188303 
    [ 3.750,  5.000) = 3902 
    [ 5.000,  6.250) = 484 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.977 ms/op
     p(99.9900) =     15.057 ms/op
     p(99.9990) =     16.301 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.047 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.346 ms/op
                 listUser·p0.9999: 13.779 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.870 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315272
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 86787 
    [ 2.500,  3.750) = 187561 
    [ 3.750,  5.000) = 33160 
    [ 5.000,  6.250) = 6052 
    [ 6.250,  7.500) = 852 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 277 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     17.988 ms/op
     p(99.9990) =     19.492 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.376 ± 1.179  ops/ms
ClientPb.existUser                       thrpt       3  13.062 ± 2.037  ops/ms
ClientPb.getUser                         thrpt       3  12.754 ± 3.959  ops/ms
ClientPb.listUser                        thrpt       3  10.479 ± 1.151  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.442   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.297   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.820   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.359   ms/op
ClientPb.createUser                     sample  379639   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.640           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  392582   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.778           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.455           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  377083   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.633           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.977           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.433           ms/op
ClientPb.listUser                       sample  315272   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.871           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.988           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.628           ms/op
