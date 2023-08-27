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
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 5.390 ops/ms
# Warmup Iteration   3: 8.525 ops/ms
Iteration   1: 8.756 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 8.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.948 ±(99.9%) 4.333 ops/ms [Average]
  (min, avg, max) = (8.756, 8.948, 9.214), stdev = 0.238
  CI (99.9%): [4.615, 13.281] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 8.617 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 9.459 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.652 ±(99.9%) 3.163 ops/ms [Average]
  (min, avg, max) = (9.459, 9.652, 9.794), stdev = 0.173
  CI (99.9%): [6.489, 12.815] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.324 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.047 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.290 ±(99.9%) 3.895 ops/ms [Average]
  (min, avg, max) = (9.047, 9.290, 9.447), stdev = 0.213
  CI (99.9%): [5.395, 13.184] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 7.040 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 7.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.826 ±(99.9%) 5.027 ops/ms [Average]
  (min, avg, max) = (7.526, 7.826, 8.067), stdev = 0.276
  CI (99.9%): [2.800, 12.853] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.678 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.003 ms/op
Iteration   1: 3.567 ±(99.9%) 0.004 ms/op
Iteration   2: 3.423 ±(99.9%) 0.008 ms/op
Iteration   3: 3.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 1.399 ms/op [Average]
  (min, avg, max) = (3.423, 3.479, 3.567), stdev = 0.077
  CI (99.9%): [2.080, 4.879] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.903 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.329 ±(99.9%) 0.006 ms/op
Iteration   2: 3.308 ±(99.9%) 0.005 ms/op
Iteration   3: 3.315 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (3.308, 3.317, 3.329), stdev = 0.011
  CI (99.9%): [3.115, 3.519] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.879 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
Iteration   2: 3.440 ±(99.9%) 0.005 ms/op
Iteration   3: 3.638 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 2.119 ms/op [Average]
  (min, avg, max) = (3.433, 3.504, 3.638), stdev = 0.116
  CI (99.9%): [1.384, 5.623] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.400 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.008 ms/op
Iteration   1: 4.114 ±(99.9%) 0.007 ms/op
Iteration   2: 4.110 ±(99.9%) 0.007 ms/op
Iteration   3: 3.955 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.060 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.955, 4.060, 4.114), stdev = 0.091
  CI (99.9%): [2.404, 5.716] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.303 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
Iteration   1: 3.451 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  17.965 ms/op
                 createUser·p0.9999: 24.292 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.444 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.418 ms/op
                 createUser·p0.999:  20.317 ms/op
                 createUser·p0.9999: 24.439 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.789 ms/op
                 createUser·p0.999:  18.059 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279151
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11273 
    [ 2.500,  5.000) = 259070 
    [ 5.000,  7.500) = 7366 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     18.017 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.855 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.307 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  19.795 ms/op
                 existUser·p0.9999: 22.401 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  21.747 ms/op
                 existUser·p0.9999: 25.685 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.473 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.987 ms/op
                 existUser·p0.999:  14.221 ms/op
                 existUser·p0.9999: 26.359 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281667
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13126 
    [ 2.500,  5.000) = 259949 
    [ 5.000,  7.500) = 6821 
    [ 7.500, 10.000) = 1136 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.265 ms/op
     p(99.9900) =     25.504 ms/op
     p(99.9990) =     26.934 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.633 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.013 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  19.899 ms/op
                 getUser·p0.9999: 22.732 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  22.922 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  17.526 ms/op
                 getUser·p0.9999: 28.114 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276307
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2387 
    [ 2.500,  5.000) = 264632 
    [ 5.000,  7.500) = 7550 
    [ 7.500, 10.000) = 1336 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     17.937 ms/op
     p(99.9900) =     29.569 ms/op
     p(99.9990) =     31.510 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.406 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.014 ms/op
Iteration   1: 4.149 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.332 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  20.444 ms/op
                 listUser·p0.9999: 26.954 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232134
  mean =      4.133 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 220038 
    [ 5.000,  7.500) = 8434 
    [ 7.500, 10.000) = 2382 
    [10.000, 12.500) = 705 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     18.459 ms/op
     p(99.9900) =     25.119 ms/op
     p(99.9990) =     27.187 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.948 ± 4.333  ops/ms
ClientPb.existUser                       thrpt       3   9.652 ± 3.163  ops/ms
ClientPb.getUser                         thrpt       3   9.290 ± 3.895  ops/ms
ClientPb.listUser                        thrpt       3   7.826 ± 5.027  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 1.399   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 0.202   ms/op
ClientPb.getUser                          avgt       3   3.504 ± 2.119   ms/op
ClientPb.listUser                         avgt       3   4.060 ± 1.656   ms/op
ClientPb.createUser                     sample  279151   3.439 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.444           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.017           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.707           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.345           ms/op
ClientPb.existUser                      sample  281667   3.406 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.043           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.265           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.504           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.115           ms/op
ClientPb.getUser                        sample  276307   3.473 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.937           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.569           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  232134   4.133 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.459           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.119           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
