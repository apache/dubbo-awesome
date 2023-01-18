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
# Warmup Iteration   1: 2.469 ops/ms
# Warmup Iteration   2: 5.720 ops/ms
# Warmup Iteration   3: 9.093 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.230 ops/ms
Iteration   3: 9.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.539 ±(99.9%) 5.777 ops/ms [Average]
  (min, avg, max) = (9.230, 9.539, 9.862), stdev = 0.317
  CI (99.9%): [3.762, 15.315] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 9.265 ops/ms
# Warmup Iteration   3: 10.068 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.344 ±(99.9%) 8.295 ops/ms [Average]
  (min, avg, max) = (9.867, 10.344, 10.773), stdev = 0.455
  CI (99.9%): [2.049, 18.640] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.537 ops/ms
# Warmup Iteration   2: 8.946 ops/ms
# Warmup Iteration   3: 9.497 ops/ms
Iteration   1: 10.368 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.249 ±(99.9%) 3.841 ops/ms [Average]
  (min, avg, max) = (10.006, 10.249, 10.372), stdev = 0.211
  CI (99.9%): [6.408, 14.089] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ops/ms
# Warmup Iteration   2: 7.144 ops/ms
# Warmup Iteration   3: 8.644 ops/ms
Iteration   1: 8.612 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.514 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (8.339, 8.514, 8.612), stdev = 0.152
  CI (99.9%): [5.739, 11.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.405 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.003 ms/op
Iteration   1: 3.141 ±(99.9%) 0.003 ms/op
Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.141, 3.214, 3.254), stdev = 0.063
  CI (99.9%): [2.062, 4.366] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.914 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
Iteration   3: 3.030 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.017 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (2.956, 3.017, 3.065), stdev = 0.056
  CI (99.9%): [2.004, 4.030] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.002 ms/op
Iteration   1: 3.233 ±(99.9%) 0.006 ms/op
Iteration   2: 3.126 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.138 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (3.055, 3.138, 3.233), stdev = 0.089
  CI (99.9%): [1.506, 4.771] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.164 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.007 ms/op
Iteration   1: 3.734 ±(99.9%) 0.006 ms/op
Iteration   2: 3.652 ±(99.9%) 0.007 ms/op
Iteration   3: 3.685 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.690 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.652, 3.690, 3.734), stdev = 0.041
  CI (99.9%): [2.936, 4.445] (assumes normal distribution)


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
# Warmup Iteration   1: 7.727 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
Iteration   1: 3.259 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  19.169 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 26.562 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 21.959 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298143
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27084 
    [ 2.500,  5.000) = 264244 
    [ 5.000,  7.500) = 6057 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.521 ms/op
     p(99.9900) =     26.909 ms/op
     p(99.9990) =     27.758 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 7.008 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  9.223 ms/op
                 existUser·p0.9999: 19.188 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.479 ms/op
                 existUser·p0.9999: 21.296 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 3.198 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 17.532 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309736
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15988 
    [ 2.500,  5.000) = 289093 
    [ 5.000,  7.500) = 4063 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     20.809 ms/op
     p(99.9990) =     21.784 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 7.292 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.010 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  18.447 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  10.858 ms/op
                 getUser·p0.9999: 23.169 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 18.779 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301505
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18044 
    [ 2.500,  5.000) = 277856 
    [ 5.000,  7.500) = 4892 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     15.950 ms/op
     p(99.9900) =     21.415 ms/op
     p(99.9990) =     24.244 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 9.132 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.011 ms/op
Iteration   1: 3.666 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.084 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.579 ms/op
                 listUser·p0.9999: 18.237 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.745 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257430
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 250814 
    [ 5.000,  7.500) = 4775 
    [ 7.500, 10.000) = 1136 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     20.704 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.539 ± 5.777  ops/ms
ClientPb.existUser                       thrpt       3  10.344 ± 8.295  ops/ms
ClientPb.getUser                         thrpt       3  10.249 ± 3.841  ops/ms
ClientPb.listUser                        thrpt       3   8.514 ± 2.775  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 1.152   ms/op
ClientPb.existUser                        avgt       3   3.017 ± 1.013   ms/op
ClientPb.getUser                          avgt       3   3.138 ± 1.633   ms/op
ClientPb.listUser                         avgt       3   3.690 ± 0.755   ms/op
ClientPb.createUser                     sample  298143   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.813           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.521           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.909           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  309736   3.097 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.208           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.809           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.987           ms/op
ClientPb.getUser                        sample  301505   3.181 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.944           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.281           ms/op
ClientPb.listUser                       sample  257430   3.723 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.317           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
