# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 5.405 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 9.464 ops/ms
Iteration   2: 9.750 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.639 ±(99.9%) 2.807 ops/ms [Average]
  (min, avg, max) = (9.464, 9.639, 9.750), stdev = 0.154
  CI (99.9%): [6.832, 12.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 8.889 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.228 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 10.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.158 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (10.057, 10.158, 10.228), stdev = 0.090
  CI (99.9%): [8.524, 11.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.267 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 9.737 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 10.052 ops/ms
Iteration   3: 10.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.950 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (9.779, 9.950, 10.052), stdev = 0.149
  CI (99.9%): [7.228, 12.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.844 ops/ms
# Warmup Iteration   2: 7.506 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.598 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.413 ±(99.9%) 3.472 ops/ms [Average]
  (min, avg, max) = (8.217, 8.413, 8.598), stdev = 0.190
  CI (99.9%): [4.942, 11.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.855 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.003 ms/op
Iteration   1: 3.394 ±(99.9%) 0.006 ms/op
Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
Iteration   3: 3.400 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.351 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (3.260, 3.351, 3.400), stdev = 0.080
  CI (99.9%): [1.901, 4.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.932 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.005 ms/op
Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.115 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.067, 3.115, 3.156), stdev = 0.045
  CI (99.9%): [2.299, 3.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.702 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.005 ms/op
Iteration   1: 3.368 ±(99.9%) 0.004 ms/op
Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
Iteration   3: 3.288 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.301 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (3.246, 3.301, 3.368), stdev = 0.062
  CI (99.9%): [2.176, 4.426] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.674 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.004 ms/op
Iteration   1: 3.895 ±(99.9%) 0.004 ms/op
Iteration   2: 3.803 ±(99.9%) 0.007 ms/op
Iteration   3: 3.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.840 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.803, 3.840, 3.895), stdev = 0.049
  CI (99.9%): [2.953, 4.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.540 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  18.568 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.805 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 23.761 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.226 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  16.746 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291523
  mean =      3.292 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14459 
    [ 2.500,  5.000) = 268867 
    [ 5.000,  7.500) = 6438 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     17.102 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     35.537 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.443 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.281 ms/op
                 existUser·p0.9999: 21.172 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  17.045 ms/op
                 existUser·p0.9999: 21.830 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 3.290 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  12.943 ms/op
                 existUser·p0.9999: 29.590 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294610
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26240 
    [ 2.500,  5.000) = 259969 
    [ 5.000,  7.500) = 7398 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     28.821 ms/op
     p(99.9990) =     31.109 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.053 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.012 ms/op
Iteration   1: 3.277 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.116 ms/op
                 getUser·p0.999:  11.780 ms/op
                 getUser·p0.9999: 23.117 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.416 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.323 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.282 ms/op
                 getUser·p0.999:  16.498 ms/op
                 getUser·p0.9999: 23.454 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287627
  mean =      3.338 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20633 
    [ 2.500,  5.000) = 258919 
    [ 5.000,  7.500) = 6727 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     24.166 ms/op
     p(99.9990) =     26.390 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.009 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.011 ms/op
Iteration   1: 3.832 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.714 ms/op
                 listUser·p0.99:   8.034 ms/op
                 listUser·p0.999:  16.956 ms/op
                 listUser·p0.9999: 20.031 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 15.746 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248613
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 237857 
    [ 5.000,  7.500) = 8092 
    [ 7.500, 10.000) = 1792 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     26.297 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.639 ± 2.807  ops/ms
ClientPb.existUser                       thrpt       3  10.158 ± 1.633  ops/ms
ClientPb.getUser                         thrpt       3   9.950 ± 2.721  ops/ms
ClientPb.listUser                        thrpt       3   8.413 ± 3.472  ops/ms
ClientPb.createUser                       avgt       3   3.351 ± 1.451   ms/op
ClientPb.existUser                        avgt       3   3.115 ± 0.816   ms/op
ClientPb.getUser                          avgt       3   3.301 ± 1.125   ms/op
ClientPb.listUser                         avgt       3   3.840 ± 0.887   ms/op
ClientPb.createUser                     sample  291523   3.292 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.686           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.128           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  294610   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.280           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.821           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  287627   3.338 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.166           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.230           ms/op
ClientPb.listUser                       sample  248613   3.861 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
