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
# Warmup Iteration   1: 4.674 ops/ms
# Warmup Iteration   2: 11.787 ops/ms
# Warmup Iteration   3: 12.510 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.534 ops/ms
Iteration   3: 12.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.564 ±(99.9%) 0.616 ops/ms [Average]
  (min, avg, max) = (12.534, 12.564, 12.601), stdev = 0.034
  CI (99.9%): [11.948, 13.180] (assumes normal distribution)


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
# Warmup Iteration   1: 7.984 ops/ms
# Warmup Iteration   2: 13.020 ops/ms
# Warmup Iteration   3: 12.882 ops/ms
Iteration   1: 12.684 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 13.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.891 ±(99.9%) 3.618 ops/ms [Average]
  (min, avg, max) = (12.684, 12.891, 13.079), stdev = 0.198
  CI (99.9%): [9.273, 16.509] (assumes normal distribution)


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
# Warmup Iteration   1: 7.701 ops/ms
# Warmup Iteration   2: 12.531 ops/ms
# Warmup Iteration   3: 12.796 ops/ms
Iteration   1: 12.825 ops/ms
Iteration   2: 12.850 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.861 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (12.825, 12.861, 12.908), stdev = 0.043
  CI (99.9%): [12.080, 13.642] (assumes normal distribution)


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
# Warmup Iteration   1: 6.677 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.638 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (10.490, 10.535, 10.576), stdev = 0.043
  CI (99.9%): [9.755, 11.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.003 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.500, 2.520, 2.551), stdev = 0.027
  CI (99.9%): [2.021, 3.020] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.445, 2.450, 2.459), stdev = 0.008
  CI (99.9%): [2.305, 2.595] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.505, 2.520, 2.529), stdev = 0.013
  CI (99.9%): [2.277, 2.764] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
Iteration   2: 2.994 ±(99.9%) 0.004 ms/op
Iteration   3: 2.982 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.982, 2.989, 2.994), stdev = 0.007
  CI (99.9%): [2.869, 3.109] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.056 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  11.325 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  9.041 ms/op
                 createUser·p0.9999: 12.153 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 10.965 ms/op
                 createUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382406
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 183600 
    [ 2.500,  3.750) = 194810 
    [ 3.750,  5.000) = 3208 
    [ 5.000,  6.250) = 323 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.549 ms/op
                 existUser·p0.9999: 24.492 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.829 ms/op
                 existUser·p0.9999: 12.416 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 11.498 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393132
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 197465 
    [ 2.500,  5.000) = 194875 
    [ 5.000,  7.500) = 391 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      7.903 ms/op
     p(99.9900) =     13.339 ms/op
     p(99.9990) =     24.744 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.501 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  7.137 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.339 ms/op
                 getUser·p0.999:  9.118 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  8.055 ms/op
                 getUser·p0.9999: 12.937 ms/op
                 getUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381528
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 188261 
    [ 2.500,  3.750) = 188269 
    [ 3.750,  5.000) = 3762 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.528 ms/op
     p(99.9900) =     13.350 ms/op
     p(99.9990) =     14.001 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.146 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.634 ms/op
                 listUser·p0.9999: 11.921 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 10.501 ms/op
                 listUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319509
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 96468 
    [ 2.500,  3.750) = 183546 
    [ 3.750,  5.000) = 32257 
    [ 5.000,  6.250) = 5664 
    [ 6.250,  7.500) = 772 
    [ 7.500,  8.750) = 296 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      8.888 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     12.193 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.564 ± 0.616  ops/ms
ClientPb.existUser                       thrpt       3  12.891 ± 3.618  ops/ms
ClientPb.getUser                         thrpt       3  12.861 ± 0.781  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 0.781  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.500   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.145   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.244   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.120   ms/op
ClientPb.createUser                     sample  382406   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.787           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  393132   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.903           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.339           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  381528   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.947           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.528           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.350           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.205           ms/op
ClientPb.listUser                       sample  319509   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.783           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.888           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
