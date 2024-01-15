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
# Warmup Iteration   1: 5.099 ops/ms
# Warmup Iteration   2: 11.861 ops/ms
# Warmup Iteration   3: 12.186 ops/ms
Iteration   1: 12.258 ops/ms
Iteration   2: 12.406 ops/ms
Iteration   3: 12.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.362 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (12.258, 12.362, 12.421), stdev = 0.090
  CI (99.9%): [10.724, 14.000] (assumes normal distribution)


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
# Warmup Iteration   1: 8.035 ops/ms
# Warmup Iteration   2: 12.792 ops/ms
# Warmup Iteration   3: 12.741 ops/ms
Iteration   1: 12.571 ops/ms
Iteration   2: 13.008 ops/ms
Iteration   3: 13.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.864 ±(99.9%) 4.638 ops/ms [Average]
  (min, avg, max) = (12.571, 12.864, 13.014), stdev = 0.254
  CI (99.9%): [8.226, 17.502] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 12.406 ops/ms
# Warmup Iteration   3: 12.618 ops/ms
Iteration   1: 12.785 ops/ms
Iteration   2: 12.838 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.814 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (12.785, 12.814, 12.838), stdev = 0.027
  CI (99.9%): [12.323, 13.305] (assumes normal distribution)


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
# Warmup Iteration   1: 6.635 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.425 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.516 ±(99.9%) 0.283 ops/ms [Average]
  (min, avg, max) = (10.498, 10.516, 10.528), stdev = 0.015
  CI (99.9%): [10.233, 10.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.005 ms/op
Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.514, 2.541, 2.568), stdev = 0.027
  CI (99.9%): [2.049, 3.032] (assumes normal distribution)


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.441, 2.447, 2.454), stdev = 0.007
  CI (99.9%): [2.323, 2.570] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.003 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.505, 2.520, 2.542), stdev = 0.019
  CI (99.9%): [2.166, 2.875] (assumes normal distribution)


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.056 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (3.049, 3.055, 3.059), stdev = 0.005
  CI (99.9%): [2.964, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.538 ms/op
                 createUser·p0.9999: 15.229 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.360 ms/op
                 createUser·p0.9999: 13.330 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  7.710 ms/op
                 createUser·p0.9999: 10.633 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375879
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 180211 
    [ 2.500,  3.750) = 191268 
    [ 3.750,  5.000) = 3523 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     14.038 ms/op
     p(99.9990) =     15.602 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.033 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.685 ms/op
                 existUser·p0.999:  6.853 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  4.872 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390456
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 191539 
    [ 2.500,  3.750) = 196075 
    [ 3.750,  5.000) = 2136 
    [ 5.000,  6.250) = 262 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     12.992 ms/op
     p(99.9990) =     13.731 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  11.846 ms/op
                 getUser·p0.9999: 14.302 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 2.594 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 12.851 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.512 ms/op
                 getUser·p0.9999: 10.663 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374489
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 181511 
    [ 2.500,  3.750) = 186410 
    [ 3.750,  5.000) = 5327 
    [ 5.000,  6.250) = 735 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      7.320 ms/op
     p(99.9900) =     13.722 ms/op
     p(99.9990) =     14.938 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.009 ms/op
Iteration   1: 3.085 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.490 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.619 ms/op
                 listUser·p0.999:  9.665 ms/op
                 listUser·p0.9999: 11.242 ms/op
                 listUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311279
  mean =      3.081 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 77515 
    [ 2.500,  3.750) = 189508 
    [ 3.750,  5.000) = 36161 
    [ 5.000,  6.250) = 6421 
    [ 6.250,  7.500) = 844 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 212 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     11.989 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.362 ± 1.638  ops/ms
ClientPb.existUser                       thrpt       3  12.864 ± 4.638  ops/ms
ClientPb.getUser                         thrpt       3  12.814 ± 0.491  ops/ms
ClientPb.listUser                        thrpt       3  10.516 ± 0.283  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.491   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.124   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.354   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.091   ms/op
ClientPb.createUser                     sample  375879   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.038           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.597           ms/op
ClientPb.existUser                      sample  390456   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.992           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.844           ms/op
ClientPb.getUser                        sample  374489   2.561 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.746           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.320           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.722           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.188           ms/op
ClientPb.listUser                       sample  311279   3.081 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.305           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
