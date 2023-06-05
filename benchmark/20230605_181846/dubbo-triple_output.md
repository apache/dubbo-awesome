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
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 6.466 ops/ms
# Warmup Iteration   3: 8.881 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 8.912 ops/ms
Iteration   3: 9.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.236 ±(99.9%) 6.152 ops/ms [Average]
  (min, avg, max) = (8.912, 9.236, 9.585), stdev = 0.337
  CI (99.9%): [3.084, 15.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.082 ops/ms
# Warmup Iteration   2: 8.798 ops/ms
# Warmup Iteration   3: 9.521 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.720 ±(99.9%) 5.721 ops/ms [Average]
  (min, avg, max) = (9.418, 9.720, 10.044), stdev = 0.314
  CI (99.9%): [3.998, 15.441] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 9.057 ops/ms
Iteration   1: 9.282 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 9.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.350 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (9.247, 9.350, 9.522), stdev = 0.150
  CI (99.9%): [6.613, 12.087] (assumes normal distribution)


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
# Warmup Iteration   1: 2.995 ops/ms
# Warmup Iteration   2: 7.264 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.051 ops/ms
Iteration   3: 7.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.039 ±(99.9%) 5.746 ops/ms [Average]
  (min, avg, max) = (7.718, 8.039, 8.348), stdev = 0.315
  CI (99.9%): [2.293, 13.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.801 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.011 ms/op
Iteration   1: 3.375 ±(99.9%) 0.010 ms/op
Iteration   2: 3.332 ±(99.9%) 0.006 ms/op
Iteration   3: 3.301 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.336 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.301, 3.336, 3.375), stdev = 0.037
  CI (99.9%): [2.661, 4.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.004 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
Iteration   2: 3.240 ±(99.9%) 0.004 ms/op
Iteration   3: 3.218 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.235 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.218, 3.235, 3.247), stdev = 0.015
  CI (99.9%): [2.954, 3.516] (assumes normal distribution)


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.006 ms/op
Iteration   1: 3.523 ±(99.9%) 0.008 ms/op
Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
Iteration   3: 3.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 2.539 ms/op [Average]
  (min, avg, max) = (3.272, 3.433, 3.523), stdev = 0.139
  CI (99.9%): [0.894, 5.971] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.631 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.911 ±(99.9%) 0.007 ms/op
Iteration   2: 3.849 ±(99.9%) 0.014 ms/op
Iteration   3: 3.902 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.849, 3.887, 3.911), stdev = 0.034
  CI (99.9%): [3.271, 4.504] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.978 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
Iteration   1: 3.397 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  21.130 ms/op
                 createUser·p0.9999: 27.577 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  21.529 ms/op
                 createUser·p0.9999: 25.523 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 3.386 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  22.208 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279541
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7117 
    [ 2.500,  5.000) = 264768 
    [ 5.000,  7.500) = 6582 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     21.707 ms/op
     p(99.9900) =     33.198 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  9.635 ms/op
                 existUser·p0.9999: 21.663 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  13.460 ms/op
                 existUser·p0.9999: 25.976 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  21.986 ms/op
                 existUser·p0.9999: 25.836 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292331
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15081 
    [ 2.500,  5.000) = 272733 
    [ 5.000,  7.500) = 3829 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     11.661 ms/op
     p(99.9900) =     25.617 ms/op
     p(99.9990) =     26.774 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.333 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.013 ms/op
Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 22.940 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.137 ms/op
                 getUser·p0.999:  22.374 ms/op
                 getUser·p0.9999: 31.856 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  16.725 ms/op
                 getUser·p0.9999: 30.994 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277091
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8369 
    [ 2.500,  5.000) = 261300 
    [ 5.000,  7.500) = 6226 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     32.521 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.482 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  18.674 ms/op
                 listUser·p0.9999: 22.481 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 3.819 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.553 ms/op
                 listUser·p0.9999: 19.493 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.042 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 17.698 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242061
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 232805 
    [ 5.000,  7.500) = 6937 
    [ 7.500, 10.000) = 1644 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.409 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     21.312 ms/op
     p(99.9990) =     22.988 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.236 ± 6.152  ops/ms
ClientPb.existUser                       thrpt       3   9.720 ± 5.721  ops/ms
ClientPb.getUser                         thrpt       3   9.350 ± 2.737  ops/ms
ClientPb.listUser                        thrpt       3   8.039 ± 5.746  ops/ms
ClientPb.createUser                       avgt       3   3.336 ± 0.675   ms/op
ClientPb.existUser                        avgt       3   3.235 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 2.539   ms/op
ClientPb.listUser                         avgt       3   3.887 ± 0.617   ms/op
ClientPb.createUser                     sample  279541   3.431 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.707           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.198           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  292331   3.283 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.884           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.661           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.617           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  277091   3.462 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670           ms/op
ClientPb.listUser                       sample  242061   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.122           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.409           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.312           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
