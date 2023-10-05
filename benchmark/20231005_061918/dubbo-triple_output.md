# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.847 ops/ms
# Warmup Iteration   2: 4.765 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.984 ops/ms
Iteration   2: 8.976 ops/ms
Iteration   3: 9.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.032 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (8.976, 9.032, 9.137), stdev = 0.091
  CI (99.9%): [7.369, 10.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 9.234 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.266 ±(99.9%) 0.614 ops/ms [Average]
  (min, avg, max) = (9.228, 9.266, 9.293), stdev = 0.034
  CI (99.9%): [8.652, 9.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.476 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.544 ops/ms
Iteration   1: 8.975 ops/ms
Iteration   2: 9.060 ops/ms
Iteration   3: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.031 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (8.975, 9.031, 9.060), stdev = 0.049
  CI (99.9%): [8.144, 9.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 7.372 ops/ms
Iteration   1: 7.471 ops/ms
Iteration   2: 7.667 ops/ms
Iteration   3: 7.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.523 ±(99.9%) 2.320 ops/ms [Average]
  (min, avg, max) = (7.429, 7.523, 7.667), stdev = 0.127
  CI (99.9%): [5.203, 9.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 9.696 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.006 ms/op
Iteration   1: 3.572 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.007 ms/op
Iteration   3: 3.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.549 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.529, 3.549, 3.572), stdev = 0.022
  CI (99.9%): [3.149, 3.949] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.402 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.004 ms/op
Iteration   1: 3.419 ±(99.9%) 0.006 ms/op
Iteration   2: 3.467 ±(99.9%) 0.007 ms/op
Iteration   3: 3.407 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.431 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.407, 3.431, 3.467), stdev = 0.032
  CI (99.9%): [2.850, 4.013] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.745 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.006 ms/op
Iteration   1: 3.539 ±(99.9%) 0.003 ms/op
Iteration   2: 3.471 ±(99.9%) 0.005 ms/op
Iteration   3: 3.548 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.519 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.471, 3.519, 3.548), stdev = 0.042
  CI (99.9%): [2.755, 4.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.845 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.006 ms/op
Iteration   1: 4.159 ±(99.9%) 0.006 ms/op
Iteration   2: 4.223 ±(99.9%) 0.009 ms/op
Iteration   3: 4.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.201 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (4.159, 4.201, 4.223), stdev = 0.036
  CI (99.9%): [3.539, 4.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.078 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.012 ms/op
Iteration   1: 3.854 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  21.814 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.551 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  24.277 ms/op
                 createUser·p0.9999: 27.295 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  21.080 ms/op
                 createUser·p0.9999: 27.713 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264474
  mean =      3.629 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3845 
    [ 2.500,  5.000) = 247187 
    [ 5.000,  7.500) = 10991 
    [ 7.500, 10.000) = 1674 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.111 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.697 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.013 ms/op
Iteration   1: 3.462 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  20.087 ms/op
                 existUser·p0.9999: 23.061 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.469 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  23.010 ms/op
                 existUser·p0.9999: 25.342 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.544 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.934 ms/op
                 existUser·p0.999:  15.106 ms/op
                 existUser·p0.9999: 48.429 ms/op
                 existUser·p1.00:   51.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274877
  mean =      3.492 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266076 
    [ 5.000, 10.000) = 8024 
    [10.000, 15.000) = 462 
    [15.000, 20.000) = 45 
    [20.000, 25.000) = 188 
    [25.000, 30.000) = 50 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 13 
    [45.000, 50.000) = 18 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     18.649 ms/op
     p(99.9900) =     42.205 ms/op
     p(99.9990) =     48.824 ms/op
     p(99.9999) =     51.184 ms/op
    p(100.0000) =     51.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.859 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.015 ms/op
Iteration   1: 3.627 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  21.065 ms/op
                 getUser·p0.9999: 24.243 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.493 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  23.903 ms/op
                 getUser·p0.9999: 26.729 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.556 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  19.311 ms/op
                 getUser·p0.9999: 35.720 ms/op
                 getUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269630
  mean =      3.558 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4924 
    [ 2.500,  5.000) = 254031 
    [ 5.000,  7.500) = 8735 
    [ 7.500, 10.000) = 1321 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     20.365 ms/op
     p(99.9900) =     30.804 ms/op
     p(99.9990) =     37.871 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.381 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.618 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.016 ms/op
Iteration   1: 4.228 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  21.309 ms/op
                 listUser·p0.9999: 26.360 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 4.274 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 19.072 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 4.380 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 18.935 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223538
  mean =      4.293 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 209864 
    [ 5.000,  7.500) = 9509 
    [ 7.500, 10.000) = 3109 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.384 ms/op
     p(99.9990) =     26.600 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.032 ± 1.663  ops/ms
ClientPb.existUser                       thrpt       3   9.266 ± 0.614  ops/ms
ClientPb.getUser                         thrpt       3   9.031 ± 0.886  ops/ms
ClientPb.listUser                        thrpt       3   7.523 ± 2.320  ops/ms
ClientPb.createUser                       avgt       3   3.549 ± 0.400   ms/op
ClientPb.existUser                        avgt       3   3.431 ± 0.581   ms/op
ClientPb.getUser                          avgt       3   3.519 ± 0.764   ms/op
ClientPb.listUser                         avgt       3   4.201 ± 0.662   ms/op
ClientPb.createUser                     sample  264474   3.629 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.995           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.725           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  274877   3.492 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.649           ms/op
ClientPb.existUser:existUser·p0.9999    sample          42.205           ms/op
ClientPb.existUser:existUser·p1.00      sample          51.184           ms/op
ClientPb.getUser                        sample  269630   3.558 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.666           ms/op
ClientPb.listUser                       sample  223538   4.293 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.384           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
