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
# Warmup Iteration   1: 4.423 ops/ms
# Warmup Iteration   2: 11.734 ops/ms
# Warmup Iteration   3: 12.444 ops/ms
Iteration   1: 12.438 ops/ms
Iteration   2: 12.266 ops/ms
Iteration   3: 12.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.501 ±(99.9%) 4.958 ops/ms [Average]
  (min, avg, max) = (12.266, 12.501, 12.798), stdev = 0.272
  CI (99.9%): [7.542, 17.459] (assumes normal distribution)


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
# Warmup Iteration   1: 7.561 ops/ms
# Warmup Iteration   2: 12.759 ops/ms
# Warmup Iteration   3: 12.870 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.836 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (12.723, 12.836, 12.898), stdev = 0.098
  CI (99.9%): [11.053, 14.618] (assumes normal distribution)


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
# Warmup Iteration   1: 7.784 ops/ms
# Warmup Iteration   2: 12.443 ops/ms
# Warmup Iteration   3: 12.569 ops/ms
Iteration   1: 12.704 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.651 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (12.572, 12.651, 12.704), stdev = 0.070
  CI (99.9%): [11.378, 13.925] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.391 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.446 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (10.391, 10.446, 10.483), stdev = 0.049
  CI (99.9%): [9.558, 11.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.003 ms/op
Iteration   1: 2.571 ±(99.9%) 0.003 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.512, 2.539, 2.571), stdev = 0.030
  CI (99.9%): [1.990, 3.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.464, 2.475, 2.492), stdev = 0.014
  CI (99.9%): [2.212, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.487, 2.506, 2.528), stdev = 0.021
  CI (99.9%): [2.129, 2.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
Iteration   3: 2.991 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.969, 2.985, 2.994), stdev = 0.014
  CI (99.9%): [2.737, 3.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.723 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  11.288 ms/op
                 createUser·p0.9999: 13.686 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  9.398 ms/op
                 createUser·p0.9999: 14.277 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.307 ms/op
                 createUser·p0.9999: 10.371 ms/op
                 createUser·p1.00:   10.486 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380427
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 183974 
    [ 2.500,  3.750) = 193029 
    [ 3.750,  5.000) = 2657 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      9.119 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     15.096 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  7.887 ms/op
                 existUser·p0.9999: 13.598 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.614 ms/op
                 existUser·p0.9999: 13.108 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.558 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388306
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 190581 
    [ 2.500,  3.750) = 193560 
    [ 3.750,  5.000) = 2686 
    [ 5.000,  6.250) = 848 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.565 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.818 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.843 ms/op
                 getUser·p0.9999: 14.783 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 12.286 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  5.197 ms/op
                 getUser·p0.9999: 12.001 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382607
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 188846 
    [ 2.500,  3.750) = 189409 
    [ 3.750,  5.000) = 3436 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     14.847 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.755 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.049 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 12.605 ms/op
                 listUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318389
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 91653 
    [ 2.500,  3.750) = 187352 
    [ 3.750,  5.000) = 32263 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 326 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.283 ms/op
     p(99.9990) =     12.861 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.501 ± 4.958  ops/ms
ClientPb.existUser                       thrpt       3  12.836 ± 1.783  ops/ms
ClientPb.getUser                         thrpt       3  12.651 ± 1.273  ops/ms
ClientPb.listUser                        thrpt       3  10.446 ± 0.889  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.549   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.263   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.377   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.247   ms/op
ClientPb.createUser                     sample  380427   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.717           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.119           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.630           ms/op
ClientPb.existUser                      sample  388306   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.565           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  382607   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.709           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.909           ms/op
ClientPb.listUser                       sample  318389   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.283           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
