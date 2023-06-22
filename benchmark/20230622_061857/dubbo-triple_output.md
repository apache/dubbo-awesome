# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.136 ops/ms
# Warmup Iteration   2: 2.702 ops/ms
# Warmup Iteration   3: 5.548 ops/ms
Iteration   1: 5.562 ops/ms
Iteration   2: 5.761 ops/ms
Iteration   3: 5.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.761 ±(99.9%) 3.635 ops/ms [Average]
  (min, avg, max) = (5.562, 5.761, 5.960), stdev = 0.199
  CI (99.9%): [2.126, 9.396] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
# Warmup Iteration   2: 5.130 ops/ms
# Warmup Iteration   3: 6.066 ops/ms
Iteration   1: 6.085 ops/ms
Iteration   2: 6.290 ops/ms
Iteration   3: 6.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.197 ±(99.9%) 1.891 ops/ms [Average]
  (min, avg, max) = (6.085, 6.197, 6.290), stdev = 0.104
  CI (99.9%): [4.306, 8.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.697 ops/ms
# Warmup Iteration   2: 4.300 ops/ms
# Warmup Iteration   3: 5.825 ops/ms
Iteration   1: 5.649 ops/ms
Iteration   2: 5.637 ops/ms
Iteration   3: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.706 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (5.637, 5.706, 5.831), stdev = 0.109
  CI (99.9%): [3.722, 7.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 1.637 ops/ms
# Warmup Iteration   2: 4.178 ops/ms
# Warmup Iteration   3: 4.902 ops/ms
Iteration   1: 4.957 ops/ms
Iteration   2: 4.865 ops/ms
Iteration   3: 5.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.977 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (4.865, 4.977, 5.108), stdev = 0.123
  CI (99.9%): [2.735, 7.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.837 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.211 ±(99.9%) 0.007 ms/op
Iteration   1: 5.841 ±(99.9%) 0.015 ms/op
Iteration   2: 5.608 ±(99.9%) 0.017 ms/op
Iteration   3: 5.605 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.685 ±(99.9%) 2.471 ms/op [Average]
  (min, avg, max) = (5.605, 5.685, 5.841), stdev = 0.135
  CI (99.9%): [3.214, 8.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.796 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.549 ±(99.9%) 0.006 ms/op
Iteration   1: 5.228 ±(99.9%) 0.013 ms/op
Iteration   2: 5.124 ±(99.9%) 0.010 ms/op
Iteration   3: 5.097 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.149 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (5.097, 5.149, 5.228), stdev = 0.069
  CI (99.9%): [3.888, 6.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 16.873 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.380 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.010 ms/op
Iteration   1: 5.749 ±(99.9%) 0.012 ms/op
Iteration   2: 5.651 ±(99.9%) 0.011 ms/op
Iteration   3: 5.488 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.629 ±(99.9%) 2.404 ms/op [Average]
  (min, avg, max) = (5.488, 5.629, 5.749), stdev = 0.132
  CI (99.9%): [3.225, 8.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.501 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 8.142 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.603 ±(99.9%) 0.014 ms/op
Iteration   1: 6.443 ±(99.9%) 0.010 ms/op
Iteration   2: 6.414 ±(99.9%) 0.016 ms/op
Iteration   3: 6.322 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.393 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (6.322, 6.393, 6.443), stdev = 0.063
  CI (99.9%): [5.235, 7.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 17.484 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.983 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.027 ms/op
Iteration   1: 5.633 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  24.791 ms/op
                 createUser·p0.9999: 30.810 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   2: 5.540 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.652 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  25.240 ms/op
                 createUser·p0.9999: 29.433 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 5.577 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.922 ms/op
                 createUser·p0.95:   7.840 ms/op
                 createUser·p0.99:   11.174 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 33.048 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171822
  mean =      5.583 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 58557 
    [ 5.000,  7.500) = 104303 
    [ 7.500, 10.000) = 6782 
    [10.000, 12.500) = 1469 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     23.664 ms/op
     p(99.9900) =     31.657 ms/op
     p(99.9990) =     33.245 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.690 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.089 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.435 ±(99.9%) 0.019 ms/op
Iteration   1: 5.333 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   9.110 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 5.191 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.191 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  27.334 ms/op
                 existUser·p0.9999: 31.195 ms/op
                 existUser·p1.00:   32.899 ms/op

Iteration   3: 5.318 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.449 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.389 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  31.174 ms/op
                 existUser·p0.9999: 35.844 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181841
  mean =      5.280 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 92204 
    [ 5.000,  7.500) = 81312 
    [ 7.500, 10.000) = 6820 
    [10.000, 12.500) = 932 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     19.142 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.286 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 6.363 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.021 ms/op
Iteration   1: 5.631 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 26.432 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 5.557 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  25.854 ms/op
                 getUser·p0.9999: 29.540 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 5.383 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.720 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  16.585 ms/op
                 getUser·p0.9999: 28.877 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173774
  mean =      5.522 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 59449 
    [ 5.000,  7.500) = 105372 
    [ 7.500, 10.000) = 7108 
    [10.000, 12.500) = 1177 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.080 ms/op
     p(99.9000) =     17.276 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     30.898 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.866 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.694 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.934 ±(99.9%) 0.026 ms/op
Iteration   1: 6.648 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.162 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.560 ms/op
                 listUser·p0.999:  27.680 ms/op
                 listUser·p0.9999: 34.681 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 6.677 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.133 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   13.352 ms/op
                 listUser·p0.999:  27.820 ms/op
                 listUser·p0.9999: 30.376 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 6.706 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.244 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  28.882 ms/op
                 listUser·p0.9999: 32.725 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143692
  mean =      6.677 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2381 
    [ 5.000,  7.500) = 121372 
    [ 7.500, 10.000) = 15730 
    [10.000, 12.500) = 2715 
    [12.500, 15.000) = 783 
    [15.000, 17.500) = 294 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.133 ms/op
     p(50.0000) =      6.365 ms/op
     p(90.0000) =      7.873 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     27.918 ms/op
     p(99.9900) =     32.809 ms/op
     p(99.9990) =     35.881 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.761 ± 3.635  ops/ms
ClientPb.existUser                       thrpt       3   6.197 ± 1.891  ops/ms
ClientPb.getUser                         thrpt       3   5.706 ± 1.984  ops/ms
ClientPb.listUser                        thrpt       3   4.977 ± 2.242  ops/ms
ClientPb.createUser                       avgt       3   5.685 ± 2.471   ms/op
ClientPb.existUser                        avgt       3   5.149 ± 1.261   ms/op
ClientPb.getUser                          avgt       3   5.629 ± 2.404   ms/op
ClientPb.listUser                         avgt       3   6.393 ± 1.158   ms/op
ClientPb.createUser                     sample  171822   5.583 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  181841   5.280 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.191           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.348           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.568           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.142           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.307           ms/op
ClientPb.getUser                        sample  173774   5.522 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.839           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.537           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.080           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.276           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.196           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  143692   6.677 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.133           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.365           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.873           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.918           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.809           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.110           ms/op
