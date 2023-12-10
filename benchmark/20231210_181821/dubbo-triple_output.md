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
# Warmup Iteration   1: 4.766 ops/ms
# Warmup Iteration   2: 11.489 ops/ms
# Warmup Iteration   3: 12.016 ops/ms
Iteration   1: 12.271 ops/ms
Iteration   2: 12.258 ops/ms
Iteration   3: 12.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.261 ±(99.9%) 0.162 ops/ms [Average]
  (min, avg, max) = (12.253, 12.261, 12.271), stdev = 0.009
  CI (99.9%): [12.098, 12.423] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 12.878 ops/ms
# Warmup Iteration   3: 12.949 ops/ms
Iteration   1: 12.985 ops/ms
Iteration   2: 12.910 ops/ms
Iteration   3: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.895 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (12.790, 12.895, 12.985), stdev = 0.099
  CI (99.9%): [11.097, 14.692] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.047 ops/ms
# Warmup Iteration   2: 12.611 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 12.704 ops/ms
Iteration   2: 12.489 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.631 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (12.489, 12.631, 12.704), stdev = 0.122
  CI (99.9%): [10.397, 14.865] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.903 ops/ms
# Warmup Iteration   2: 10.435 ops/ms
# Warmup Iteration   3: 10.567 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.581 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (10.505, 10.581, 10.648), stdev = 0.072
  CI (99.9%): [9.268, 11.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.003 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.544, 2.549, 2.553), stdev = 0.005
  CI (99.9%): [2.465, 2.633] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.003 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.463, 2.473, 2.489), stdev = 0.014
  CI (99.9%): [2.221, 2.725] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.523 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.513, 2.523, 2.532), stdev = 0.010
  CI (99.9%): [2.345, 2.700] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
Iteration   3: 3.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.031, 3.034, 3.038), stdev = 0.004
  CI (99.9%): [2.967, 3.102] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 14.971 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 13.576 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  8.151 ms/op
                 createUser·p0.9999: 21.938 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377593
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179933 
    [ 2.500,  5.000) = 196649 
    [ 5.000,  7.500) = 605 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     15.372 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 13.459 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  5.416 ms/op
                 existUser·p0.9999: 13.321 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.470 ms/op
                 existUser·p0.9999: 12.011 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386823
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 189576 
    [ 2.500,  3.750) = 193450 
    [ 3.750,  5.000) = 2853 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.924 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.174 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  12.084 ms/op
                 getUser·p0.9999: 19.974 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  9.720 ms/op
                 getUser·p0.9999: 14.500 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 11.450 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378950
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185280 
    [ 2.500,  5.000) = 192386 
    [ 5.000,  7.500) = 890 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     15.124 ms/op
     p(99.9990) =     20.421 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.917 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.537 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 10.940 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.094 ms/op
                 listUser·p0.9999: 10.887 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315235
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 85855 
    [ 2.500,  3.750) = 189473 
    [ 3.750,  5.000) = 32713 
    [ 5.000,  6.250) = 5617 
    [ 6.250,  7.500) = 766 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 299 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.157 ms/op
     p(99.9990) =     12.146 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.261 ± 0.162  ops/ms
ClientPb.existUser                       thrpt       3  12.895 ± 1.797  ops/ms
ClientPb.getUser                         thrpt       3  12.631 ± 2.234  ops/ms
ClientPb.listUser                        thrpt       3  10.581 ± 1.313  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.084   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.252   ms/op
ClientPb.getUser                          avgt       3   2.523 ± 0.177   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.068   ms/op
ClientPb.createUser                     sample  377593   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.858           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.274           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.372           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  386823   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.961           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.924           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.271           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  378950   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.814           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.611           ms/op
ClientPb.listUser                       sample  315235   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.895           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
