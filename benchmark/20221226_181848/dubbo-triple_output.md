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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 8.980 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.381 ±(99.9%) 2.852 ops/ms [Average]
  (min, avg, max) = (9.221, 9.381, 9.533), stdev = 0.156
  CI (99.9%): [6.529, 12.234] (assumes normal distribution)


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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 8.988 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 9.993 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.864 ±(99.9%) 3.094 ops/ms [Average]
  (min, avg, max) = (9.672, 9.864, 9.993), stdev = 0.170
  CI (99.9%): [6.771, 12.958] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.363 ops/ms
# Warmup Iteration   2: 8.569 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.439 ops/ms
Iteration   3: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.287 ±(99.9%) 5.048 ops/ms [Average]
  (min, avg, max) = (8.968, 9.287, 9.455), stdev = 0.277
  CI (99.9%): [4.239, 14.336] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.175 ops/ms
# Warmup Iteration   3: 7.816 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.122 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (7.959, 8.122, 8.239), stdev = 0.145
  CI (99.9%): [5.472, 10.771] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.563 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.012 ms/op
Iteration   1: 3.340 ±(99.9%) 0.012 ms/op
Iteration   2: 3.403 ±(99.9%) 0.008 ms/op
Iteration   3: 3.345 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.363 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.340, 3.363, 3.403), stdev = 0.035
  CI (99.9%): [2.718, 4.007] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.476 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.005 ms/op
Iteration   1: 3.268 ±(99.9%) 0.003 ms/op
Iteration   2: 3.369 ±(99.9%) 0.004 ms/op
Iteration   3: 3.255 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.297 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.255, 3.297, 3.369), stdev = 0.063
  CI (99.9%): [2.154, 4.441] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.005 ms/op
Iteration   1: 3.318 ±(99.9%) 0.010 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.514 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 1.896 ms/op [Average]
  (min, avg, max) = (3.318, 3.396, 3.514), stdev = 0.104
  CI (99.9%): [1.500, 5.293] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.891 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 4.120 ±(99.9%) 0.008 ms/op
Iteration   2: 4.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.817 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.997 ±(99.9%) 2.904 ms/op [Average]
  (min, avg, max) = (3.817, 3.997, 4.120), stdev = 0.159
  CI (99.9%): [1.093, 6.900] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.834 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
Iteration   1: 3.586 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.287 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.433 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 25.285 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277980
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6468 
    [ 2.500,  5.000) = 265818 
    [ 5.000,  7.500) = 4655 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     25.336 ms/op
     p(99.9990) =     26.618 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  9.325 ms/op
                 existUser·p0.9999: 22.221 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  13.532 ms/op
                 existUser·p0.9999: 24.936 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.007 ms/op
                 existUser·p0.999:  21.415 ms/op
                 existUser·p0.9999: 27.004 ms/op
                 existUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290843
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20412 
    [ 2.500,  5.000) = 264968 
    [ 5.000,  7.500) = 4694 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     11.439 ms/op
     p(99.9900) =     25.392 ms/op
     p(99.9990) =     27.650 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.358 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.012 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 27.329 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.499 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  22.050 ms/op
                 getUser·p0.9999: 26.135 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  21.011 ms/op
                 getUser·p0.9999: 33.377 ms/op
                 getUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277022
  mean =      3.464 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6175 
    [ 2.500,  5.000) = 262114 
    [ 5.000,  7.500) = 7611 
    [ 7.500, 10.000) = 670 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     20.968 ms/op
     p(99.9900) =     30.746 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.667 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.373 ms/op
                 listUser·p0.9999: 23.107 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  15.639 ms/op
                 listUser·p0.9999: 18.529 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.905 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.067 ms/op
                 listUser·p0.999:  15.174 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241919
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 234102 
    [ 5.000,  7.500) = 5517 
    [ 7.500, 10.000) = 1600 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.408 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.381 ± 2.852  ops/ms
ClientPb.existUser                       thrpt       3   9.864 ± 3.094  ops/ms
ClientPb.getUser                         thrpt       3   9.287 ± 5.048  ops/ms
ClientPb.listUser                        thrpt       3   8.122 ± 2.649  ops/ms
ClientPb.createUser                       avgt       3   3.363 ± 0.644   ms/op
ClientPb.existUser                        avgt       3   3.297 ± 1.143   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 1.896   ms/op
ClientPb.listUser                         avgt       3   3.997 ± 2.904   ms/op
ClientPb.createUser                     sample  277980   3.450 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.922           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.399           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.460           ms/op
ClientPb.existUser                      sample  290843   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.967           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.439           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  277022   3.464 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.997           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.968           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  241919   3.963 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.559           ms/op
