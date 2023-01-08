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
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.986 ops/ms
# Warmup Iteration   3: 8.687 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.675 ±(99.9%) 6.580 ops/ms [Average]
  (min, avg, max) = (9.300, 9.675, 10.019), stdev = 0.361
  CI (99.9%): [3.095, 16.255] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 9.535 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.321 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.319 ±(99.9%) 2.835 ops/ms [Average]
  (min, avg, max) = (10.162, 10.319, 10.473), stdev = 0.155
  CI (99.9%): [7.484, 13.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ops/ms
# Warmup Iteration   2: 9.220 ops/ms
# Warmup Iteration   3: 9.550 ops/ms
Iteration   1: 9.873 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 9.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.922 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (9.801, 9.922, 10.090), stdev = 0.150
  CI (99.9%): [7.180, 12.663] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.873 ops/ms
Iteration   3: 8.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.675 ±(99.9%) 5.079 ops/ms [Average]
  (min, avg, max) = (8.357, 8.675, 8.873), stdev = 0.278
  CI (99.9%): [3.596, 13.754] (assumes normal distribution)


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
# Warmup Iteration   1: 8.920 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.002 ms/op
Iteration   1: 3.163 ±(99.9%) 0.007 ms/op
Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.128 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.106, 3.128, 3.163), stdev = 0.030
  CI (99.9%): [2.573, 3.684] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.646 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.004 ms/op
Iteration   1: 3.186 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
Iteration   3: 3.088 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.029, 3.101, 3.186), stdev = 0.079
  CI (99.9%): [1.663, 4.540] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.004 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
Iteration   3: 3.184 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.171 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.083, 3.171, 3.246), stdev = 0.082
  CI (99.9%): [1.672, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 10.147 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.007 ms/op
Iteration   1: 3.745 ±(99.9%) 0.008 ms/op
Iteration   2: 3.880 ±(99.9%) 0.007 ms/op
Iteration   3: 3.641 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 2.189 ms/op [Average]
  (min, avg, max) = (3.641, 3.755, 3.880), stdev = 0.120
  CI (99.9%): [1.566, 5.944] (assumes normal distribution)


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
# Warmup Iteration   1: 9.125 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  14.304 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.779 ms/op
                 createUser·p0.999:  13.613 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  16.409 ms/op
                 createUser·p0.9999: 33.749 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296887
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22127 
    [ 2.500,  5.000) = 268838 
    [ 5.000,  7.500) = 5104 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.116 ms/op
     p(99.9900) =     32.100 ms/op
     p(99.9990) =     34.277 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.490 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  9.170 ms/op
                 existUser·p0.9999: 18.537 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.747 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.676 ms/op
                 existUser·p0.9999: 20.079 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.783 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309937
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37625 
    [ 2.500,  5.000) = 266905 
    [ 5.000,  7.500) = 4660 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     22.213 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 8.427 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.010 ms/op
Iteration   1: 3.395 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.946 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  18.240 ms/op
                 getUser·p0.9999: 20.565 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 26.852 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.197 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 23.495 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294797
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11979 
    [ 2.500,  5.000) = 275114 
    [ 5.000,  7.500) = 6642 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.852 ms/op
     p(99.9900) =     25.560 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.011 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.883 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 16.294 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253589
  mean =      3.785 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 246129 
    [ 5.000,  7.500) = 5506 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 356 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.113 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     25.600 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.675 ± 6.580  ops/ms
ClientPb.existUser                       thrpt       3  10.319 ± 2.835  ops/ms
ClientPb.getUser                         thrpt       3   9.922 ± 2.742  ops/ms
ClientPb.listUser                        thrpt       3   8.675 ± 5.079  ops/ms
ClientPb.createUser                       avgt       3   3.128 ± 0.555   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 1.438   ms/op
ClientPb.getUser                          avgt       3   3.171 ± 1.499   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 2.189   ms/op
ClientPb.createUser                     sample  296887   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.116           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.100           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  309937   3.096 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.126           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.336           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.316           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.643           ms/op
ClientPb.getUser                        sample  294797   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.978           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.852           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.787           ms/op
ClientPb.listUser                       sample  253589   3.785 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.059           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.113           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
