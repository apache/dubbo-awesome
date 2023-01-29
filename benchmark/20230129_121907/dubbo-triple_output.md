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
# Warmup Iteration   1: 2.614 ops/ms
# Warmup Iteration   2: 6.017 ops/ms
# Warmup Iteration   3: 9.225 ops/ms
Iteration   1: 9.826 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 10.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.914 ±(99.9%) 2.713 ops/ms [Average]
  (min, avg, max) = (9.826, 9.914, 10.086), stdev = 0.149
  CI (99.9%): [7.201, 12.628] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ops/ms
# Warmup Iteration   2: 9.741 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.413 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (10.302, 10.413, 10.488), stdev = 0.098
  CI (99.9%): [8.628, 12.197] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.371 ops/ms
# Warmup Iteration   3: 9.910 ops/ms
Iteration   1: 10.051 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.085 ±(99.9%) 4.546 ops/ms [Average]
  (min, avg, max) = (9.855, 10.085, 10.350), stdev = 0.249
  CI (99.9%): [5.540, 14.631] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.376 ops/ms
# Warmup Iteration   2: 7.596 ops/ms
# Warmup Iteration   3: 8.484 ops/ms
Iteration   1: 8.286 ops/ms
Iteration   2: 8.288 ops/ms
Iteration   3: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.427 ±(99.9%) 4.416 ops/ms [Average]
  (min, avg, max) = (8.286, 8.427, 8.706), stdev = 0.242
  CI (99.9%): [4.011, 12.842] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.773 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.003 ms/op
Iteration   1: 3.134 ±(99.9%) 0.008 ms/op
Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
Iteration   3: 3.154 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.138 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.126, 3.138, 3.154), stdev = 0.015
  CI (99.9%): [2.873, 3.404] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.004 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.156 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.080 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.030, 3.080, 3.156), stdev = 0.067
  CI (99.9%): [1.863, 4.297] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.607 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.004 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.270 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.198 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.156, 3.198, 3.270), stdev = 0.063
  CI (99.9%): [2.052, 4.343] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 9.188 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.009 ms/op
Iteration   1: 3.711 ±(99.9%) 0.008 ms/op
Iteration   2: 3.829 ±(99.9%) 0.002 ms/op
Iteration   3: 3.618 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (3.618, 3.720, 3.829), stdev = 0.106
  CI (99.9%): [1.790, 5.650] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.367 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.008 ms/op
Iteration   1: 3.264 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  19.227 ms/op
                 createUser·p0.9999: 21.371 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  16.786 ms/op
                 createUser·p0.9999: 27.700 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.357 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  15.106 ms/op
                 createUser·p0.9999: 21.496 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290107
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24219 
    [ 2.500,  5.000) = 258589 
    [ 5.000,  7.500) = 6439 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     16.348 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.089 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 19.934 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.763 ms/op
                 existUser·p0.999:  12.587 ms/op
                 existUser·p0.9999: 22.123 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 32.635 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302718
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25016 
    [ 2.500,  5.000) = 272045 
    [ 5.000,  7.500) = 4829 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.477 ms/op
     p(99.9900) =     32.188 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  9.171 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  14.139 ms/op
                 getUser·p0.9999: 20.384 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304321
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16405 
    [ 2.500,  5.000) = 282810 
    [ 5.000,  7.500) = 4399 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     13.954 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.019 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.338 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.010 ms/op
Iteration   1: 3.791 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 22.130 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 3.730 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 15.499 ms/op
                 listUser·p1.00:   15.548 ms/op

Iteration   3: 3.676 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.435 ms/op
                 listUser·p0.999:  15.026 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257105
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 250770 
    [ 5.000,  7.500) = 4752 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     23.565 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.914 ± 2.713  ops/ms
ClientPb.existUser                       thrpt       3  10.413 ± 1.784  ops/ms
ClientPb.getUser                         thrpt       3  10.085 ± 4.546  ops/ms
ClientPb.listUser                        thrpt       3   8.427 ± 4.416  ops/ms
ClientPb.createUser                       avgt       3   3.138 ± 0.266   ms/op
ClientPb.existUser                        avgt       3   3.080 ± 1.217   ms/op
ClientPb.getUser                          avgt       3   3.198 ± 1.146   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 1.930   ms/op
ClientPb.createUser                     sample  290107   3.309 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  302718   3.170 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.477           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.188           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  304321   3.152 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.268           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.954           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.103           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.905           ms/op
ClientPb.listUser                       sample  257105   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
