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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 12.017 ops/ms
# Warmup Iteration   3: 12.166 ops/ms
Iteration   1: 12.440 ops/ms
Iteration   2: 12.322 ops/ms
Iteration   3: 12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.419 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (12.322, 12.419, 12.494), stdev = 0.088
  CI (99.9%): [10.815, 14.023] (assumes normal distribution)


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
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 12.753 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 12.872 ops/ms
Iteration   2: 12.914 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.878 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (12.847, 12.878, 12.914), stdev = 0.034
  CI (99.9%): [12.256, 13.499] (assumes normal distribution)


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
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 12.300 ops/ms
# Warmup Iteration   3: 12.477 ops/ms
Iteration   1: 12.665 ops/ms
Iteration   2: 12.499 ops/ms
Iteration   3: 12.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.609 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (12.499, 12.609, 12.665), stdev = 0.095
  CI (99.9%): [10.870, 14.348] (assumes normal distribution)


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
# Warmup Iteration   1: 6.899 ops/ms
# Warmup Iteration   2: 10.324 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.505 ±(99.9%) 0.301 ops/ms [Average]
  (min, avg, max) = (10.492, 10.505, 10.524), stdev = 0.017
  CI (99.9%): [10.204, 10.807] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.005 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.031 ms/op [Average]
  (min, avg, max) = (2.547, 2.549, 2.551), stdev = 0.002
  CI (99.9%): [2.518, 2.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.003 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.490, 2.496, 2.508), stdev = 0.010
  CI (99.9%): [2.313, 2.680] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
Iteration   2: 2.546 ±(99.9%) 0.003 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.511, 2.524, 2.546), stdev = 0.019
  CI (99.9%): [2.173, 2.875] (assumes normal distribution)


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.004 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.035, 3.049, 3.059), stdev = 0.012
  CI (99.9%): [2.827, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.775 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.594 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.725 ms/op
                 createUser·p0.999:  11.596 ms/op
                 createUser·p0.9999: 13.861 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.460 ms/op
                 createUser·p0.9999: 15.143 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 2.620 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.203 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.071 ms/op
                 createUser·p0.999:  8.637 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367984
  mean =      2.605 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 174220 
    [ 2.500,  3.750) = 188951 
    [ 3.750,  5.000) = 3902 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     15.756 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.648 ms/op
                 existUser·p0.999:  8.856 ms/op
                 existUser·p0.9999: 14.029 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  10.310 ms/op
                 existUser·p0.9999: 13.233 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.586 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386171
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 186856 
    [ 2.500,  3.750) = 195111 
    [ 3.750,  5.000) = 3039 
    [ 5.000,  6.250) = 629 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.271 ms/op
     p(99.9900) =     13.518 ms/op
     p(99.9990) =     14.302 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  11.586 ms/op
                 getUser·p0.9999: 14.156 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 14.278 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.403 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 12.822 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375770
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 182737 
    [ 2.500,  3.750) = 187730 
    [ 3.750,  5.000) = 4405 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     14.852 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 11.782 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.248 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 12.072 ms/op
                 listUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313821
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 83968 
    [ 2.500,  3.750) = 187580 
    [ 3.750,  5.000) = 34665 
    [ 5.000,  6.250) = 6090 
    [ 6.250,  7.500) = 764 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.456 ms/op
     p(99.9900) =     11.456 ms/op
     p(99.9990) =     12.906 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.419 ± 1.604  ops/ms
ClientPb.existUser                       thrpt       3  12.878 ± 0.622  ops/ms
ClientPb.getUser                         thrpt       3  12.609 ± 1.739  ops/ms
ClientPb.listUser                        thrpt       3  10.505 ± 0.301  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.031   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.183   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.351   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.222   ms/op
ClientPb.createUser                     sample  367984   2.605 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.926           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.876           ms/op
ClientPb.existUser                      sample  386171   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.518           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  375770   2.552 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.123           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  313821   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.456           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.456           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
