# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.539 ops/ms
# Warmup Iteration   2: 6.369 ops/ms
# Warmup Iteration   3: 8.803 ops/ms
Iteration   1: 8.985 ops/ms
Iteration   2: 9.425 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.302 ±(99.9%) 5.049 ops/ms [Average]
  (min, avg, max) = (8.985, 9.302, 9.496), stdev = 0.277
  CI (99.9%): [4.253, 14.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ops/ms
# Warmup Iteration   2: 8.545 ops/ms
# Warmup Iteration   3: 9.803 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.848 ±(99.9%) 4.959 ops/ms [Average]
  (min, avg, max) = (9.537, 9.848, 10.042), stdev = 0.272
  CI (99.9%): [4.889, 14.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 8.261 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.125 ops/ms
Iteration   2: 9.441 ops/ms
Iteration   3: 9.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.445 ±(99.9%) 5.883 ops/ms [Average]
  (min, avg, max) = (9.125, 9.445, 9.770), stdev = 0.322
  CI (99.9%): [3.563, 15.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 7.206 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 7.882 ops/ms
Iteration   3: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.944 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (7.882, 7.944, 8.013), stdev = 0.066
  CI (99.9%): [6.745, 9.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.845 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.005 ms/op
Iteration   1: 3.494 ±(99.9%) 0.006 ms/op
Iteration   2: 3.292 ±(99.9%) 0.004 ms/op
Iteration   3: 3.354 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.380 ±(99.9%) 1.882 ms/op [Average]
  (min, avg, max) = (3.292, 3.380, 3.494), stdev = 0.103
  CI (99.9%): [1.498, 5.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.842 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.003 ms/op
Iteration   1: 3.371 ±(99.9%) 0.007 ms/op
Iteration   2: 3.295 ±(99.9%) 0.011 ms/op
Iteration   3: 3.141 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.269 ±(99.9%) 2.143 ms/op [Average]
  (min, avg, max) = (3.141, 3.269, 3.371), stdev = 0.117
  CI (99.9%): [1.126, 5.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.820 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.006 ms/op
Iteration   1: 3.442 ±(99.9%) 0.007 ms/op
Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
Iteration   3: 3.308 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 1.850 ms/op [Average]
  (min, avg, max) = (3.308, 3.419, 3.506), stdev = 0.101
  CI (99.9%): [1.568, 5.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.293 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.008 ms/op
Iteration   1: 3.836 ±(99.9%) 0.012 ms/op
Iteration   2: 3.753 ±(99.9%) 0.012 ms/op
Iteration   3: 3.866 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.818 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.753, 3.818, 3.866), stdev = 0.059
  CI (99.9%): [2.749, 4.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.729 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  10.517 ms/op
                 createUser·p0.9999: 32.425 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  21.986 ms/op
                 createUser·p0.9999: 24.697 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284834
  mean =      3.369 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6592 
    [ 2.500,  5.000) = 273045 
    [ 5.000,  7.500) = 4193 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     31.576 ms/op
     p(99.9990) =     33.204 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.985 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
Iteration   1: 3.173 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  8.705 ms/op
                 existUser·p0.9999: 22.181 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.711 ms/op
                 existUser·p0.999:  14.513 ms/op
                 existUser·p0.9999: 24.270 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 23.590 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298315
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10054 
    [ 2.500,  5.000) = 284120 
    [ 5.000,  7.500) = 3330 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.956 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     24.806 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.519 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
Iteration   1: 3.668 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  11.333 ms/op
                 getUser·p0.9999: 23.799 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.312 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  14.478 ms/op
                 getUser·p0.9999: 24.620 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.404 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  18.524 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274092
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11161 
    [ 2.500,  5.000) = 250179 
    [ 5.000,  7.500) = 11684 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     11.563 ms/op
     p(99.9900) =     27.924 ms/op
     p(99.9990) =     28.582 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.552 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.697 ms/op
                 listUser·p0.999:  20.677 ms/op
                 listUser·p0.9999: 23.372 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   8.058 ms/op
                 listUser·p0.999:  14.476 ms/op
                 listUser·p0.9999: 22.914 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.993 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239115
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 230920 
    [ 5.000,  7.500) = 5523 
    [ 7.500, 10.000) = 1669 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     15.217 ms/op
     p(99.9900) =     22.780 ms/op
     p(99.9990) =     24.315 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.302 ± 5.049  ops/ms
ClientPb.existUser                       thrpt       3   9.848 ± 4.959  ops/ms
ClientPb.getUser                         thrpt       3   9.445 ± 5.883  ops/ms
ClientPb.listUser                        thrpt       3   7.944 ± 1.199  ops/ms
ClientPb.createUser                       avgt       3   3.380 ± 1.882   ms/op
ClientPb.existUser                        avgt       3   3.269 ± 2.143   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 1.850   ms/op
ClientPb.listUser                         avgt       3   3.818 ± 1.069   ms/op
ClientPb.createUser                     sample  284834   3.369 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.302           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.576           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  298315   3.216 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.956           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.855           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  274092   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.404           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.390           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.563           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.924           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  239115   4.015 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.135           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.217           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.780           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
