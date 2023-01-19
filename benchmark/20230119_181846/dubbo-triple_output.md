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
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 6.780 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 9.983 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.958 ±(99.9%) 3.959 ops/ms [Average]
  (min, avg, max) = (9.730, 9.958, 10.162), stdev = 0.217
  CI (99.9%): [5.999, 13.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 9.294 ops/ms
# Warmup Iteration   3: 10.344 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (9.983, 10.128, 10.321), stdev = 0.174
  CI (99.9%): [6.952, 13.303] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 8.711 ops/ms
# Warmup Iteration   3: 10.148 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 10.167 ops/ms
Iteration   3: 10.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.988 ±(99.9%) 3.558 ops/ms [Average]
  (min, avg, max) = (9.780, 9.988, 10.167), stdev = 0.195
  CI (99.9%): [6.430, 13.545] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 8.583 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.613 ops/ms
Iteration   3: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.622 ±(99.9%) 0.273 ops/ms [Average]
  (min, avg, max) = (8.613, 8.622, 8.639), stdev = 0.015
  CI (99.9%): [8.349, 8.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.876 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.089 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.106 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (3.089, 3.106, 3.127), stdev = 0.019
  CI (99.9%): [2.754, 3.459] (assumes normal distribution)


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
# Warmup Iteration   1: 7.712 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.015 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (2.969, 3.015, 3.080), stdev = 0.058
  CI (99.9%): [1.958, 4.072] (assumes normal distribution)


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
# Warmup Iteration   1: 8.228 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.004 ms/op
Iteration   2: 3.249 ±(99.9%) 0.005 ms/op
Iteration   3: 3.138 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.205 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.138, 3.205, 3.249), stdev = 0.059
  CI (99.9%): [2.129, 4.280] (assumes normal distribution)


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
# Warmup Iteration   1: 8.944 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.005 ms/op
Iteration   1: 3.666 ±(99.9%) 0.010 ms/op
Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
Iteration   3: 3.694 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.681 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.666, 3.681, 3.694), stdev = 0.014
  CI (99.9%): [3.423, 3.938] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.473 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  13.566 ms/op
                 createUser·p0.9999: 19.343 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 22.765 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 25.023 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302091
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12454 
    [ 2.500,  5.000) = 283879 
    [ 5.000,  7.500) = 4901 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     12.893 ms/op
     p(99.9900) =     23.972 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 7.718 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  8.652 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.613 ms/op
                 existUser·p0.999:  17.309 ms/op
                 existUser·p0.9999: 25.098 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 21.352 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311206
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31971 
    [ 2.500,  5.000) = 274453 
    [ 5.000,  7.500) = 4003 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     26.029 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 7.609 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  16.007 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  18.328 ms/op
                 getUser·p0.9999: 21.883 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  9.506 ms/op
                 getUser·p0.9999: 19.548 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302485
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12976 
    [ 2.500,  5.000) = 282345 
    [ 5.000,  7.500) = 6245 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     20.931 ms/op
     p(99.9990) =     23.425 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.777 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.009 ms/op
Iteration   1: 3.668 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.507 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 17.470 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 17.364 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.691 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 22.468 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259194
  mean =      3.700 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 250909 
    [ 5.000,  7.500) = 6320 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.958 ± 3.959  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 3.176  ops/ms
ClientPb.getUser                         thrpt       3   9.988 ± 3.558  ops/ms
ClientPb.listUser                        thrpt       3   8.622 ± 0.273  ops/ms
ClientPb.createUser                       avgt       3   3.106 ± 0.353   ms/op
ClientPb.existUser                        avgt       3   3.015 ± 1.057   ms/op
ClientPb.getUser                          avgt       3   3.205 ± 1.075   ms/op
ClientPb.listUser                         avgt       3   3.681 ± 0.257   ms/op
ClientPb.createUser                     sample  302091   3.176 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.893           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  311206   3.083 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.116           ms/op
ClientPb.getUser                        sample  302485   3.169 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.969           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.319           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.931           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  259194   3.700 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.053           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
