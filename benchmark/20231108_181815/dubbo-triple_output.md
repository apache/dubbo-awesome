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
# Warmup Iteration   1: 4.838 ops/ms
# Warmup Iteration   2: 12.185 ops/ms
# Warmup Iteration   3: 12.450 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.762 ops/ms
Iteration   3: 12.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.753 ±(99.9%) 1.764 ops/ms [Average]
  (min, avg, max) = (12.653, 12.753, 12.845), stdev = 0.097
  CI (99.9%): [10.990, 14.517] (assumes normal distribution)


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
# Warmup Iteration   1: 8.225 ops/ms
# Warmup Iteration   2: 13.187 ops/ms
# Warmup Iteration   3: 13.093 ops/ms
Iteration   1: 13.084 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.066 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (12.967, 13.066, 13.146), stdev = 0.091
  CI (99.9%): [11.400, 14.731] (assumes normal distribution)


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
# Warmup Iteration   1: 7.426 ops/ms
# Warmup Iteration   2: 12.527 ops/ms
# Warmup Iteration   3: 12.766 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.904 ops/ms
Iteration   3: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.841 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (12.770, 12.841, 12.904), stdev = 0.068
  CI (99.9%): [11.607, 14.075] (assumes normal distribution)


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
# Warmup Iteration   1: 7.013 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.697 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.616 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (10.576, 10.616, 10.638), stdev = 0.035
  CI (99.9%): [9.973, 11.259] (assumes normal distribution)


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.532, 2.542, 2.549), stdev = 0.009
  CI (99.9%): [2.379, 2.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.003 ms/op
Iteration   1: 2.411 ±(99.9%) 0.003 ms/op
Iteration   2: 2.404 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.404, 2.409, 2.413), stdev = 0.004
  CI (99.9%): [2.328, 2.491] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.450 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.436, 2.450, 2.467), stdev = 0.016
  CI (99.9%): [2.166, 2.735] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.989, 2.996, 3.002), stdev = 0.007
  CI (99.9%): [2.874, 3.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  10.741 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 12.550 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.212 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 10.781 ms/op
                 createUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381289
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183418 
    [ 2.500,  3.750) = 192919 
    [ 3.750,  5.000) = 3859 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      9.084 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.396 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.352 ms/op
                 existUser·p0.9999: 13.776 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.900 ms/op
                 existUser·p0.999:  5.796 ms/op
                 existUser·p0.9999: 14.384 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  8.290 ms/op
                 existUser·p0.9999: 11.902 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394345
  mean =      2.432 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 200770 
    [ 2.500,  3.750) = 189735 
    [ 3.750,  5.000) = 2847 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.069 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  6.936 ms/op
                 getUser·p0.9999: 17.249 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  7.515 ms/op
                 getUser·p0.9999: 11.454 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386101
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 191258 
    [ 2.500,  3.750) = 188729 
    [ 3.750,  5.000) = 4435 
    [ 5.000,  6.250) = 1122 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     14.483 ms/op
     p(99.9990) =     17.994 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 10.403 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 13.836 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.217 ms/op
                 listUser·p0.9999: 11.706 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321600
  mean =      2.982 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 100451 
    [ 2.500,  3.750) = 182622 
    [ 3.750,  5.000) = 30169 
    [ 5.000,  6.250) = 6517 
    [ 6.250,  7.500) = 1041 
    [ 7.500,  8.750) = 335 
    [ 8.750, 10.000) = 182 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     12.474 ms/op
     p(99.9990) =     14.551 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.753 ± 1.764  ops/ms
ClientPb.existUser                       thrpt       3  13.066 ± 1.665  ops/ms
ClientPb.getUser                         thrpt       3  12.841 ± 1.234  ops/ms
ClientPb.listUser                        thrpt       3  10.616 ± 0.643  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.081   ms/op
ClientPb.getUser                          avgt       3   2.450 ± 0.284   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.122   ms/op
ClientPb.createUser                     sample  381289   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.084           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  394345   2.432 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.069           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  386101   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.483           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.055           ms/op
ClientPb.listUser                       sample  321600   2.982 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.738           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.474           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.188           ms/op
