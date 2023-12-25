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
# Warmup Iteration   1: 4.942 ops/ms
# Warmup Iteration   2: 11.829 ops/ms
# Warmup Iteration   3: 12.105 ops/ms
Iteration   1: 12.372 ops/ms
Iteration   2: 12.421 ops/ms
Iteration   3: 12.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.424 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (12.372, 12.424, 12.480), stdev = 0.054
  CI (99.9%): [11.439, 13.409] (assumes normal distribution)


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
# Warmup Iteration   1: 8.080 ops/ms
# Warmup Iteration   2: 12.883 ops/ms
# Warmup Iteration   3: 12.852 ops/ms
Iteration   1: 12.738 ops/ms
Iteration   2: 12.924 ops/ms
Iteration   3: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.843 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (12.738, 12.843, 12.924), stdev = 0.095
  CI (99.9%): [11.108, 14.577] (assumes normal distribution)


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
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 12.412 ops/ms
# Warmup Iteration   3: 12.552 ops/ms
Iteration   1: 12.671 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.680 ±(99.9%) 1.003 ops/ms [Average]
  (min, avg, max) = (12.630, 12.680, 12.739), stdev = 0.055
  CI (99.9%): [11.677, 13.683] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.533 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (10.475, 10.533, 10.605), stdev = 0.066
  CI (99.9%): [9.326, 11.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (2.523, 2.552, 2.588), stdev = 0.033
  CI (99.9%): [1.945, 3.160] (assumes normal distribution)


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.454, 2.469, 2.486), stdev = 0.016
  CI (99.9%): [2.182, 2.757] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.003 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.534, 2.539, 2.542), stdev = 0.005
  CI (99.9%): [2.455, 2.624] (assumes normal distribution)


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
# Warmup Iteration   1: 4.897 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
Iteration   3: 3.062 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.026, 3.039, 3.062), stdev = 0.020
  CI (99.9%): [2.672, 3.405] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.169 ms/op
                 createUser·p0.9999: 13.991 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 10.872 ms/op
                 createUser·p1.00:   11.534 ms/op

Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 11.527 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375634
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 179670 
    [ 2.500,  3.750) = 190471 
    [ 3.750,  5.000) = 4136 
    [ 5.000,  6.250) = 689 
    [ 6.250,  7.500) = 213 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.082 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 13.585 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  5.571 ms/op
                 existUser·p0.9999: 12.895 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382286
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 185864 
    [ 2.500,  3.750) = 193342 
    [ 3.750,  5.000) = 2246 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      6.224 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     18.552 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  11.254 ms/op
                 getUser·p0.9999: 13.881 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.457 ms/op
                 getUser·p0.999:  7.681 ms/op
                 getUser·p0.9999: 12.700 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 10.819 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382884
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 187702 
    [ 2.500,  3.750) = 190013 
    [ 3.750,  5.000) = 3954 
    [ 5.000,  6.250) = 767 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      6.518 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.361 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.643 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.887 ms/op
                 listUser·p0.9999: 10.789 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  10.945 ms/op
                 listUser·p0.9999: 14.516 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.499 ms/op
                 listUser·p0.999:  9.665 ms/op
                 listUser·p0.9999: 11.804 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314566
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 84701 
    [ 2.500,  3.750) = 188835 
    [ 3.750,  5.000) = 33862 
    [ 5.000,  6.250) = 5868 
    [ 6.250,  7.500) = 561 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 180 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.723 ms/op
     p(99.9900) =     14.175 ms/op
     p(99.9990) =     14.874 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.424 ± 0.985  ops/ms
ClientPb.existUser                       thrpt       3  12.843 ± 1.734  ops/ms
ClientPb.getUser                         thrpt       3  12.680 ± 1.003  ops/ms
ClientPb.listUser                        thrpt       3  10.533 ± 1.207  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.608   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.085   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.367   ms/op
ClientPb.createUser                     sample  375634   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.672           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.082           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  382286   2.509 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.224           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.038           ms/op
ClientPb.getUser                        sample  382884   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.518           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.615           ms/op
ClientPb.listUser                       sample  314566   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.723           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.175           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.942           ms/op
