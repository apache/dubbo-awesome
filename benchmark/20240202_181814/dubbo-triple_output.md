# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.012 ops/ms
# Warmup Iteration   2: 11.992 ops/ms
# Warmup Iteration   3: 12.550 ops/ms
Iteration   1: 12.696 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.747 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (12.696, 12.747, 12.780), stdev = 0.045
  CI (99.9%): [11.934, 13.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.223 ops/ms
# Warmup Iteration   2: 13.099 ops/ms
# Warmup Iteration   3: 13.040 ops/ms
Iteration   1: 13.047 ops/ms
Iteration   2: 12.955 ops/ms
Iteration   3: 13.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (12.955, 13.006, 13.047), stdev = 0.047
  CI (99.9%): [12.152, 13.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.496 ops/ms
# Warmup Iteration   2: 12.607 ops/ms
# Warmup Iteration   3: 12.862 ops/ms
Iteration   1: 12.848 ops/ms
Iteration   2: 12.998 ops/ms
Iteration   3: 12.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.907 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (12.848, 12.907, 12.998), stdev = 0.080
  CI (99.9%): [11.447, 14.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.624 ops/ms
# Warmup Iteration   2: 10.548 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.738 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (10.663, 10.738, 10.783), stdev = 0.065
  CI (99.9%): [9.543, 11.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.003 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.503, 2.516, 2.527), stdev = 0.012
  CI (99.9%): [2.292, 2.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.003 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.459, 2.462, 2.468), stdev = 0.005
  CI (99.9%): [2.363, 2.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.003 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.495, 2.510, 2.521), stdev = 0.013
  CI (99.9%): [2.269, 2.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.995, 2.999, 3.002), stdev = 0.004
  CI (99.9%): [2.924, 3.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.018 ms/op
                 createUser·p0.9999: 13.558 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.682 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.921 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379703
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 181633 
    [ 2.500,  3.750) = 194412 
    [ 3.750,  5.000) = 2773 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.953 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  5.564 ms/op
                 existUser·p0.9999: 14.081 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  7.484 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.656 ms/op
                 existUser·p0.999:  7.679 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386097
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 189348 
    [ 2.500,  3.750) = 193574 
    [ 3.750,  5.000) = 2332 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.192 ms/op
     p(99.9900) =     13.821 ms/op
     p(99.9990) =     14.617 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  5.073 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 15.679 ms/op
                 getUser·p1.00:   16.630 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  7.799 ms/op
                 getUser·p0.9999: 11.706 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382447
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 190914 
    [ 2.500,  3.750) = 186343 
    [ 3.750,  5.000) = 4207 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      6.215 ms/op
     p(99.9900) =     15.073 ms/op
     p(99.9990) =     16.475 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.554 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 12.878 ms/op
                 listUser·p1.00:   14.959 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.873 ms/op
                 listUser·p0.9999: 12.655 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.659 ms/op
                 listUser·p0.9999: 10.179 ms/op
                 listUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321017
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 97186 
    [ 2.500,  3.750) = 186326 
    [ 3.750,  5.000) = 30148 
    [ 5.000,  6.250) = 6035 
    [ 6.250,  7.500) = 585 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.280 ms/op
     p(99.9990) =     13.802 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.747 ± 0.813  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 0.853  ops/ms
ClientPb.getUser                         thrpt       3  12.907 ± 1.461  ops/ms
ClientPb.listUser                        thrpt       3  10.738 ± 1.194  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.241   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.076   ms/op
ClientPb.createUser                     sample  379703   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.942           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.009           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  386097   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.821           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  382447   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.761           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.630           ms/op
ClientPb.listUser                       sample  321017   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.959           ms/op
