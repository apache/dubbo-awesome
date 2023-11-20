# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 11.607 ops/ms
# Warmup Iteration   3: 12.199 ops/ms
Iteration   1: 12.301 ops/ms
Iteration   2: 12.356 ops/ms
Iteration   3: 12.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.380 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (12.301, 12.380, 12.485), stdev = 0.094
  CI (99.9%): [10.659, 14.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 12.508 ops/ms
# Warmup Iteration   3: 12.576 ops/ms
Iteration   1: 12.525 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.594 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (12.525, 12.594, 12.634), stdev = 0.060
  CI (99.9%): [11.505, 13.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.407 ops/ms
# Warmup Iteration   2: 12.241 ops/ms
# Warmup Iteration   3: 12.280 ops/ms
Iteration   1: 12.523 ops/ms
Iteration   2: 12.622 ops/ms
Iteration   3: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.540 ±(99.9%) 1.355 ops/ms [Average]
  (min, avg, max) = (12.476, 12.540, 12.622), stdev = 0.074
  CI (99.9%): [11.185, 13.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.334 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.445 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.343 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.325 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (10.250, 10.325, 10.382), stdev = 0.068
  CI (99.9%): [9.082, 11.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.635 ±(99.9%) 0.004 ms/op
Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
Iteration   3: 2.613 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.617 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.604, 2.617, 2.635), stdev = 0.016
  CI (99.9%): [2.327, 2.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.003 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
Iteration   3: 2.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.535 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.527, 2.535, 2.539), stdev = 0.007
  CI (99.9%): [2.408, 2.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.024 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.004 ms/op
Iteration   1: 2.583 ±(99.9%) 0.005 ms/op
Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
Iteration   3: 2.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.560 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.539, 2.560, 2.583), stdev = 0.022
  CI (99.9%): [2.155, 2.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.998 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.005 ms/op
Iteration   1: 3.105 ±(99.9%) 0.005 ms/op
Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
Iteration   3: 3.106 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.109 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.105, 3.109, 3.115), stdev = 0.006
  CI (99.9%): [3.006, 3.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.263 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.722 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  12.493 ms/op
                 createUser·p0.9999: 14.596 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 14.673 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 10.685 ms/op
                 createUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372731
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 177455 
    [ 2.500,  3.750) = 190208 
    [ 3.750,  5.000) = 3954 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.016 ms/op
     p(99.9900) =     14.479 ms/op
     p(99.9990) =     15.376 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.843 ms/op
                 existUser·p0.999:  5.971 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  9.397 ms/op
                 existUser·p0.9999: 14.606 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  9.934 ms/op
                 existUser·p0.9999: 12.004 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378501
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 184189 
    [ 2.500,  3.750) = 189816 
    [ 3.750,  5.000) = 3306 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.570 ms/op
     p(99.9900) =     14.786 ms/op
     p(99.9990) =     19.045 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.980 ms/op
                 getUser·p0.999:  12.602 ms/op
                 getUser·p0.9999: 14.361 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.375 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 13.151 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  5.742 ms/op
                 getUser·p0.9999: 11.674 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372313
  mean =      2.577 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 179418 
    [ 2.500,  3.750) = 185899 
    [ 3.750,  5.000) = 5236 
    [ 5.000,  6.250) = 1264 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.944 ms/op
     p(99.9900) =     13.939 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.063 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.009 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.679 ms/op
                 listUser·p0.9999: 10.961 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.853 ms/op
                 listUser·p0.9999: 11.445 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.465 ms/op
                 listUser·p0.9999: 11.473 ms/op
                 listUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312096
  mean =      3.074 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 82084 
    [ 2.500,  3.750) = 185757 
    [ 3.750,  5.000) = 35676 
    [ 5.000,  6.250) = 6853 
    [ 6.250,  7.500) = 873 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 201 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     12.067 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.380 ± 1.721  ops/ms
ClientPb.existUser                       thrpt       3  12.594 ± 1.088  ops/ms
ClientPb.getUser                         thrpt       3  12.540 ± 1.355  ops/ms
ClientPb.listUser                        thrpt       3  10.325 ± 1.243  ops/ms
ClientPb.createUser                       avgt       3   2.617 ± 0.290   ms/op
ClientPb.existUser                        avgt       3   2.535 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.560 ± 0.405   ms/op
ClientPb.listUser                         avgt       3   3.109 ± 0.102   ms/op
ClientPb.createUser                     sample  372731   2.573 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.016           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.696           ms/op
ClientPb.existUser                      sample  378501   2.535 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.570           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.786           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.202           ms/op
ClientPb.getUser                        sample  372313   2.577 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.613           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.944           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.939           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  312096   3.074 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.636           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
