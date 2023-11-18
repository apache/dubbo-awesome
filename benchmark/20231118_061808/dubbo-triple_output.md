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
# Warmup Iteration   1: 4.904 ops/ms
# Warmup Iteration   2: 12.042 ops/ms
# Warmup Iteration   3: 12.311 ops/ms
Iteration   1: 12.464 ops/ms
Iteration   2: 12.639 ops/ms
Iteration   3: 12.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.542 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (12.464, 12.542, 12.639), stdev = 0.089
  CI (99.9%): [10.916, 14.169] (assumes normal distribution)


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
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 13.011 ops/ms
# Warmup Iteration   3: 13.093 ops/ms
Iteration   1: 12.916 ops/ms
Iteration   2: 13.056 ops/ms
Iteration   3: 13.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.007 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (12.916, 13.007, 13.056), stdev = 0.079
  CI (99.9%): [11.568, 14.446] (assumes normal distribution)


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
# Warmup Iteration   1: 7.704 ops/ms
# Warmup Iteration   2: 12.559 ops/ms
# Warmup Iteration   3: 12.670 ops/ms
Iteration   1: 12.715 ops/ms
Iteration   2: 12.711 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.717 ±(99.9%) 0.126 ops/ms [Average]
  (min, avg, max) = (12.711, 12.717, 12.724), stdev = 0.007
  CI (99.9%): [12.591, 12.843] (assumes normal distribution)


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
# Warmup Iteration   1: 6.495 ops/ms
# Warmup Iteration   2: 10.487 ops/ms
# Warmup Iteration   3: 10.417 ops/ms
Iteration   1: 10.566 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.560 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (10.513, 10.560, 10.601), stdev = 0.044
  CI (99.9%): [9.758, 11.362] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.474 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.462, 2.474, 2.498), stdev = 0.020
  CI (99.9%): [2.107, 2.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.439, 2.450, 2.468), stdev = 0.015
  CI (99.9%): [2.171, 2.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.532 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.519, 2.532, 2.541), stdev = 0.012
  CI (99.9%): [2.313, 2.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.990, 3.013, 3.030), stdev = 0.020
  CI (99.9%): [2.643, 3.383] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.179 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.335 ms/op
                 createUser·p0.9999: 12.300 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.738 ms/op
                 createUser·p0.9999: 10.915 ms/op
                 createUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377611
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 180598 
    [ 2.500,  3.750) = 192535 
    [ 3.750,  5.000) = 3681 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.797 ms/op
     p(99.9900) =     13.365 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.522 ms/op
                 existUser·p0.999:  6.222 ms/op
                 existUser·p0.9999: 14.243 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.487 ms/op
                 existUser·p0.999:  7.880 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  6.161 ms/op
                 existUser·p0.9999: 12.257 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389276
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192287 
    [ 2.500,  3.750) = 193933 
    [ 3.750,  5.000) = 2267 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.488 ms/op
     p(99.9900) =     13.715 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  12.030 ms/op
                 getUser·p0.9999: 13.622 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  9.188 ms/op
                 getUser·p0.9999: 12.952 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  8.186 ms/op
                 getUser·p0.9999: 10.655 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377327
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 183906 
    [ 2.500,  3.750) = 187934 
    [ 3.750,  5.000) = 4277 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     13.210 ms/op
     p(99.9990) =     13.783 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.419 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.220 ms/op
                 listUser·p0.9999: 11.149 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315964
  mean =      3.036 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 88294 
    [ 2.500,  3.750) = 186806 
    [ 3.750,  5.000) = 32797 
    [ 5.000,  6.250) = 6394 
    [ 6.250,  7.500) = 845 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     11.964 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.542 ± 1.626  ops/ms
ClientPb.existUser                       thrpt       3  13.007 ± 1.439  ops/ms
ClientPb.getUser                         thrpt       3  12.717 ± 0.126  ops/ms
ClientPb.listUser                        thrpt       3  10.560 ± 0.802  ops/ms
ClientPb.createUser                       avgt       3   2.474 ± 0.367   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.279   ms/op
ClientPb.getUser                          avgt       3   2.532 ± 0.219   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.370   ms/op
ClientPb.createUser                     sample  377611   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.797           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  389276   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.488           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.715           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  377327   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.210           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.041           ms/op
ClientPb.listUser                       sample  315964   3.036 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.863           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
