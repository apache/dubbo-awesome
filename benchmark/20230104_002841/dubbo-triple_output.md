# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.049 ops/ms
# Warmup Iteration   2: 2.698 ops/ms
# Warmup Iteration   3: 5.366 ops/ms
Iteration   1: 5.166 ops/ms
Iteration   2: 5.740 ops/ms
Iteration   3: 5.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.625 ±(99.9%) 7.549 ops/ms [Average]
  (min, avg, max) = (5.166, 5.625, 5.969), stdev = 0.414
  CI (99.9%): [≈ 0, 13.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 4.717 ops/ms
# Warmup Iteration   3: 5.264 ops/ms
Iteration   1: 5.353 ops/ms
Iteration   2: 5.738 ops/ms
Iteration   3: 5.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.675 ±(99.9%) 5.394 ops/ms [Average]
  (min, avg, max) = (5.353, 5.675, 5.934), stdev = 0.296
  CI (99.9%): [0.282, 11.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.455 ops/ms
# Warmup Iteration   2: 4.155 ops/ms
# Warmup Iteration   3: 5.493 ops/ms
Iteration   1: 5.554 ops/ms
Iteration   2: 5.364 ops/ms
Iteration   3: 5.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.400 ±(99.9%) 2.545 ops/ms [Average]
  (min, avg, max) = (5.283, 5.400, 5.554), stdev = 0.140
  CI (99.9%): [2.855, 7.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.361 ops/ms
# Warmup Iteration   2: 3.127 ops/ms
# Warmup Iteration   3: 3.941 ops/ms
Iteration   1: 4.380 ops/ms
Iteration   2: 4.345 ops/ms
Iteration   3: 4.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.356 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (4.344, 4.356, 4.380), stdev = 0.021
  CI (99.9%): [3.979, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.753 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.855 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.017 ms/op
Iteration   1: 6.017 ±(99.9%) 0.013 ms/op
Iteration   2: 5.673 ±(99.9%) 0.020 ms/op
Iteration   3: 5.676 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.789 ±(99.9%) 3.612 ms/op [Average]
  (min, avg, max) = (5.673, 5.789, 6.017), stdev = 0.198
  CI (99.9%): [2.177, 9.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.040 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 6.774 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.768 ±(99.9%) 0.011 ms/op
Iteration   1: 6.572 ±(99.9%) 0.013 ms/op
Iteration   2: 5.789 ±(99.9%) 0.012 ms/op
Iteration   3: 6.356 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.239 ±(99.9%) 7.378 ms/op [Average]
  (min, avg, max) = (5.789, 6.239, 6.572), stdev = 0.404
  CI (99.9%): [≈ 0, 13.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.454 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 8.018 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.118 ±(99.9%) 0.015 ms/op
Iteration   1: 6.638 ±(99.9%) 0.008 ms/op
Iteration   2: 6.113 ±(99.9%) 0.015 ms/op
Iteration   3: 6.084 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.278 ±(99.9%) 5.684 ms/op [Average]
  (min, avg, max) = (6.084, 6.278, 6.638), stdev = 0.312
  CI (99.9%): [0.595, 11.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.752 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 9.614 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 7.779 ±(99.9%) 0.022 ms/op
Iteration   1: 7.367 ±(99.9%) 0.025 ms/op
Iteration   2: 7.731 ±(99.9%) 0.021 ms/op
Iteration   3: 7.150 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.416 ±(99.9%) 5.363 ms/op [Average]
  (min, avg, max) = (7.150, 7.416, 7.731), stdev = 0.294
  CI (99.9%): [2.053, 12.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.380 ±(99.9%) 0.532 ms/op
# Warmup Iteration   2: 7.650 ±(99.9%) 0.087 ms/op
# Warmup Iteration   3: 6.189 ±(99.9%) 0.063 ms/op
Iteration   1: 5.480 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   32.641 ms/op
                 createUser·p0.999:  53.281 ms/op
                 createUser·p0.9999: 76.677 ms/op
                 createUser·p1.00:   181.666 ms/op

Iteration   2: 6.349 ±(99.9%) 0.122 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   10.426 ms/op
                 createUser·p0.99:   37.937 ms/op
                 createUser·p0.999:  124.148 ms/op
                 createUser·p0.9999: 178.771 ms/op
                 createUser·p1.00:   179.569 ms/op

Iteration   3: 5.957 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   4.833 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   9.355 ms/op
                 createUser·p0.99:   34.079 ms/op
                 createUser·p0.999:  61.997 ms/op
                 createUser·p0.9999: 117.348 ms/op
                 createUser·p1.00:   119.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162502
  mean =      5.907 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 156429 
    [ 12.500,  25.000) = 2877 
    [ 25.000,  37.500) = 2113 
    [ 37.500,  50.000) = 565 
    [ 50.000,  62.500) = 272 
    [ 62.500,  75.000) = 75 
    [ 75.000,  87.500) = 44 
    [ 87.500, 100.000) = 7 
    [100.000, 112.500) = 23 
    [112.500, 125.000) = 53 
    [125.000, 137.500) = 8 
    [137.500, 150.000) = 2 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 1 
    [175.000, 187.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     34.603 ms/op
     p(99.9000) =     76.415 ms/op
     p(99.9900) =    177.734 ms/op
     p(99.9990) =    180.355 ms/op
     p(99.9999) =    181.666 ms/op
    p(100.0000) =    181.666 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.262 ±(99.9%) 0.429 ms/op
# Warmup Iteration   2: 6.740 ±(99.9%) 0.077 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.061 ms/op
Iteration   1: 5.545 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   1.958 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   8.405 ms/op
                 existUser·p0.99:   33.284 ms/op
                 existUser·p0.999:  49.021 ms/op
                 existUser·p0.9999: 70.386 ms/op
                 existUser·p1.00:   115.212 ms/op

Iteration   2: 5.859 ±(99.9%) 0.103 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   35.127 ms/op
                 existUser·p0.999:  82.313 ms/op
                 existUser·p0.9999: 234.404 ms/op
                 existUser·p1.00:   271.057 ms/op

Iteration   3: 5.392 ±(99.9%) 0.057 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   4.571 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.848 ms/op
                 existUser·p0.99:   32.965 ms/op
                 existUser·p0.999:  54.181 ms/op
                 existUser·p0.9999: 69.184 ms/op
                 existUser·p1.00:   94.765 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171568
  mean =      5.592 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [  0.000,  25.000) = 168591 
    [ 25.000,  50.000) = 2647 
    [ 50.000,  75.000) = 236 
    [ 75.000, 100.000) = 60 
    [100.000, 125.000) = 2 
    [125.000, 150.000) = 2 
    [150.000, 175.000) = 4 
    [175.000, 200.000) = 13 
    [200.000, 225.000) = 8 
    [225.000, 250.000) = 0 
    [250.000, 275.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     33.882 ms/op
     p(99.9000) =     54.423 ms/op
     p(99.9900) =    195.297 ms/op
     p(99.9990) =    270.682 ms/op
     p(99.9999) =    271.057 ms/op
    p(100.0000) =    271.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.085 ±(99.9%) 0.517 ms/op
# Warmup Iteration   2: 8.290 ±(99.9%) 0.110 ms/op
# Warmup Iteration   3: 7.029 ±(99.9%) 0.116 ms/op
Iteration   1: 6.069 ±(99.9%) 0.073 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   10.306 ms/op
                 getUser·p0.99:   33.882 ms/op
                 getUser·p0.999:  60.645 ms/op
                 getUser·p0.9999: 71.041 ms/op
                 getUser·p1.00:   97.911 ms/op

Iteration   2: 6.771 ±(99.9%) 0.134 ms/op
                 getUser·p0.00:   0.382 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   8.602 ms/op
                 getUser·p0.95:   14.795 ms/op
                 getUser·p0.99:   40.239 ms/op
                 getUser·p0.999:  87.529 ms/op
                 getUser·p0.9999: 248.061 ms/op
                 getUser·p1.00:   248.513 ms/op

Iteration   3: 6.041 ±(99.9%) 0.071 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   7.832 ms/op
                 getUser·p0.95:   11.780 ms/op
                 getUser·p0.99:   34.079 ms/op
                 getUser·p0.999:  54.793 ms/op
                 getUser·p0.9999: 60.831 ms/op
                 getUser·p1.00:   89.915 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 152942
  mean =      6.276 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [  0.000,  25.000) = 149480 
    [ 25.000,  50.000) = 2927 
    [ 50.000,  75.000) = 466 
    [ 75.000, 100.000) = 35 
    [100.000, 125.000) = 1 
    [125.000, 150.000) = 0 
    [150.000, 175.000) = 3 
    [175.000, 200.000) = 0 
    [200.000, 225.000) = 0 
    [225.000, 250.000) = 30 
    [250.000, 275.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =     12.812 ms/op
     p(99.0000) =     34.669 ms/op
     p(99.9000) =     63.570 ms/op
     p(99.9900) =    234.017 ms/op
     p(99.9990) =    248.374 ms/op
     p(99.9999) =    248.513 ms/op
    p(100.0000) =    248.513 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.091 ±(99.9%) 0.695 ms/op
# Warmup Iteration   2: 9.762 ±(99.9%) 0.165 ms/op
# Warmup Iteration   3: 8.132 ±(99.9%) 0.149 ms/op
Iteration   1: 7.759 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   10.076 ms/op
                 listUser·p0.95:   16.368 ms/op
                 listUser·p0.99:   45.158 ms/op
                 listUser·p0.999:  80.494 ms/op
                 listUser·p0.9999: 119.030 ms/op
                 listUser·p1.00:   163.840 ms/op

Iteration   2: 7.458 ±(99.9%) 0.158 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   8.859 ms/op
                 listUser·p0.95:   14.008 ms/op
                 listUser·p0.99:   49.229 ms/op
                 listUser·p0.999:  141.558 ms/op
                 listUser·p0.9999: 222.560 ms/op
                 listUser·p1.00:   236.454 ms/op

Iteration   3: 7.636 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   9.486 ms/op
                 listUser·p0.95:   15.986 ms/op
                 listUser·p0.99:   46.191 ms/op
                 listUser·p0.999:  93.622 ms/op
                 listUser·p0.9999: 107.292 ms/op
                 listUser·p1.00:   191.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 126005
  mean =      7.615 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [  0.000,  25.000) = 121410 
    [ 25.000,  50.000) = 3506 
    [ 50.000,  75.000) = 771 
    [ 75.000, 100.000) = 241 
    [100.000, 125.000) = 20 
    [125.000, 150.000) = 18 
    [150.000, 175.000) = 6 
    [175.000, 200.000) = 1 
    [200.000, 225.000) = 31 
    [225.000, 250.000) = 1 
    [250.000, 275.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      9.650 ms/op
     p(95.0000) =     15.139 ms/op
     p(99.0000) =     47.514 ms/op
     p(99.9000) =     92.797 ms/op
     p(99.9900) =    221.879 ms/op
     p(99.9990) =    232.977 ms/op
     p(99.9999) =    236.454 ms/op
    p(100.0000) =    236.454 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3    5.625 ± 7.549  ops/ms
ClientPb.existUser                       thrpt       3    5.675 ± 5.394  ops/ms
ClientPb.getUser                         thrpt       3    5.400 ± 2.545  ops/ms
ClientPb.listUser                        thrpt       3    4.356 ± 0.377  ops/ms
ClientPb.createUser                       avgt       3    5.789 ± 3.612   ms/op
ClientPb.existUser                        avgt       3    6.239 ± 7.378   ms/op
ClientPb.getUser                          avgt       3    6.278 ± 5.684   ms/op
ClientPb.listUser                         avgt       3    7.416 ± 5.363   ms/op
ClientPb.createUser                     sample  162502    5.907 ± 0.051   ms/op
ClientPb.createUser:createUser·p0.00    sample            1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample            4.760           ms/op
ClientPb.createUser:createUser·p0.90    sample            6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample            8.897           ms/op
ClientPb.createUser:createUser·p0.99    sample           34.603           ms/op
ClientPb.createUser:createUser·p0.999   sample           76.415           ms/op
ClientPb.createUser:createUser·p0.9999  sample          177.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          181.666           ms/op
ClientPb.existUser                      sample  171568    5.592 ± 0.044   ms/op
ClientPb.existUser:existUser·p0.00      sample            0.618           ms/op
ClientPb.existUser:existUser·p0.50      sample            4.620           ms/op
ClientPb.existUser:existUser·p0.90      sample            6.324           ms/op
ClientPb.existUser:existUser·p0.95      sample            8.069           ms/op
ClientPb.existUser:existUser·p0.99      sample           33.882           ms/op
ClientPb.existUser:existUser·p0.999     sample           54.423           ms/op
ClientPb.existUser:existUser·p0.9999    sample          195.297           ms/op
ClientPb.existUser:existUser·p1.00      sample          271.057           ms/op
ClientPb.getUser                        sample  152942    6.276 ± 0.055   ms/op
ClientPb.getUser:getUser·p0.00          sample            0.382           ms/op
ClientPb.getUser:getUser·p0.50          sample            4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample            7.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           12.812           ms/op
ClientPb.getUser:getUser·p0.99          sample           34.669           ms/op
ClientPb.getUser:getUser·p0.999         sample           63.570           ms/op
ClientPb.getUser:getUser·p0.9999        sample          234.017           ms/op
ClientPb.getUser:getUser·p1.00          sample          248.513           ms/op
ClientPb.listUser                       sample  126005    7.615 ± 0.080   ms/op
ClientPb.listUser:listUser·p0.00        sample            1.208           ms/op
ClientPb.listUser:listUser·p0.50        sample            5.579           ms/op
ClientPb.listUser:listUser·p0.90        sample            9.650           ms/op
ClientPb.listUser:listUser·p0.95        sample           15.139           ms/op
ClientPb.listUser:listUser·p0.99        sample           47.514           ms/op
ClientPb.listUser:listUser·p0.999       sample           92.797           ms/op
ClientPb.listUser:listUser·p0.9999      sample          221.879           ms/op
ClientPb.listUser:listUser·p1.00        sample          236.454           ms/op
