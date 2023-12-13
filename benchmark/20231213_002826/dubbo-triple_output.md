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
# Warmup Iteration   1: 5.276 ops/ms
# Warmup Iteration   2: 12.341 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.581 ops/ms
Iteration   2: 12.618 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.637 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (12.581, 12.637, 12.713), stdev = 0.068
  CI (99.9%): [11.399, 13.876] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.309 ops/ms
# Warmup Iteration   2: 12.887 ops/ms
# Warmup Iteration   3: 12.887 ops/ms
Iteration   1: 12.968 ops/ms
Iteration   2: 13.040 ops/ms
Iteration   3: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.966 ±(99.9%) 1.372 ops/ms [Average]
  (min, avg, max) = (12.890, 12.966, 13.040), stdev = 0.075
  CI (99.9%): [11.594, 14.338] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 12.528 ops/ms
# Warmup Iteration   3: 12.633 ops/ms
Iteration   1: 12.716 ops/ms
Iteration   2: 12.595 ops/ms
Iteration   3: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.669 ±(99.9%) 1.188 ops/ms [Average]
  (min, avg, max) = (12.595, 12.669, 12.716), stdev = 0.065
  CI (99.9%): [11.481, 13.856] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.525 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.542 ops/ms
Iteration   2: 10.705 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.671 ±(99.9%) 2.123 ops/ms [Average]
  (min, avg, max) = (10.542, 10.671, 10.767), stdev = 0.116
  CI (99.9%): [8.548, 12.794] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.003 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.491, 2.498, 2.501), stdev = 0.006
  CI (99.9%): [2.396, 2.600] (assumes normal distribution)


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.003 ms/op
Iteration   1: 2.399 ±(99.9%) 0.003 ms/op
Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
Iteration   3: 2.409 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.402 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.398, 2.402, 2.409), stdev = 0.006
  CI (99.9%): [2.295, 2.509] (assumes normal distribution)


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.486, 2.497, 2.517), stdev = 0.017
  CI (99.9%): [2.186, 2.808] (assumes normal distribution)


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.000, 3.026, 3.055), stdev = 0.027
  CI (99.9%): [2.528, 3.523] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.099 ms/op
                 createUser·p0.9999: 14.835 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378342
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 180473 
    [ 2.500,  3.750) = 194043 
    [ 3.750,  5.000) = 2934 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     13.571 ms/op
     p(99.9990) =     16.145 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
Iteration   1: 2.386 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.310 ms/op
                 existUser·p0.999:  5.104 ms/op
                 existUser·p0.9999: 13.799 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.373 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  7.884 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403001
  mean =      2.380 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 208619 
    [ 2.500,  3.750) = 191894 
    [ 3.750,  5.000) = 1740 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =      6.447 ms/op
     p(99.9900) =     13.643 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  11.839 ms/op
                 getUser·p0.9999: 13.410 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.535 ms/op
                 getUser·p0.999:  7.784 ms/op
                 getUser·p0.9999: 10.620 ms/op
                 getUser·p1.00:   11.141 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 14.421 ms/op
                 getUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382873
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 188762 
    [ 2.500,  3.750) = 190776 
    [ 3.750,  5.000) = 2732 
    [ 5.000,  6.250) = 176 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     13.447 ms/op
     p(99.9990) =     15.362 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
Iteration   1: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.425 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   2: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.180 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 13.032 ms/op
                 listUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324752
  mean =      2.953 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 104799 
    [ 2.500,  3.750) = 183969 
    [ 3.750,  5.000) = 28831 
    [ 5.000,  6.250) = 5706 
    [ 6.250,  7.500) = 559 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.540 ms/op
     p(99.9900) =     11.592 ms/op
     p(99.9990) =     13.554 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.637 ± 1.239  ops/ms
ClientPb.existUser                       thrpt       3  12.966 ± 1.372  ops/ms
ClientPb.getUser                         thrpt       3  12.669 ± 1.188  ops/ms
ClientPb.listUser                        thrpt       3  10.671 ± 2.123  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.102   ms/op
ClientPb.existUser                        avgt       3   2.402 ± 0.107   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.311   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.498   ms/op
ClientPb.createUser                     sample  378342   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.821           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.571           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.663           ms/op
ClientPb.existUser                      sample  403001   2.380 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.767           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.888           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.447           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.643           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  382873   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.487           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.447           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.318           ms/op
ClientPb.listUser                       sample  324752   2.953 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.540           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.592           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.730           ms/op
