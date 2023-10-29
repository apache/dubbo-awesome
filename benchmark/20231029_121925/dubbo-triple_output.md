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
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 4.877 ops/ms
# Warmup Iteration   3: 8.455 ops/ms
Iteration   1: 9.084 ops/ms
Iteration   2: 9.006 ops/ms
Iteration   3: 8.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.005 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (8.926, 9.005, 9.084), stdev = 0.079
  CI (99.9%): [7.563, 10.448] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.965 ops/ms
# Warmup Iteration   2: 8.439 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.352 ops/ms
Iteration   2: 9.480 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.434 ±(99.9%) 1.288 ops/ms [Average]
  (min, avg, max) = (9.352, 9.434, 9.480), stdev = 0.071
  CI (99.9%): [8.146, 10.722] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 8.892 ops/ms
Iteration   1: 8.775 ops/ms
Iteration   2: 8.946 ops/ms
Iteration   3: 8.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.901 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (8.775, 8.901, 8.981), stdev = 0.111
  CI (99.9%): [6.884, 10.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 6.823 ops/ms
# Warmup Iteration   3: 7.524 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.593 ops/ms
Iteration   3: 7.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.544 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (7.466, 7.544, 7.593), stdev = 0.068
  CI (99.9%): [6.301, 8.788] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.754 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.003 ms/op
Iteration   1: 3.452 ±(99.9%) 0.006 ms/op
Iteration   2: 3.654 ±(99.9%) 0.006 ms/op
Iteration   3: 3.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.529 ±(99.9%) 1.989 ms/op [Average]
  (min, avg, max) = (3.452, 3.529, 3.654), stdev = 0.109
  CI (99.9%): [1.540, 5.517] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.379 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.002 ms/op
Iteration   1: 3.407 ±(99.9%) 0.003 ms/op
Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.451 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (3.407, 3.451, 3.493), stdev = 0.043
  CI (99.9%): [2.672, 4.230] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.169 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.525 ±(99.9%) 0.004 ms/op
Iteration   2: 3.498 ±(99.9%) 0.006 ms/op
Iteration   3: 3.556 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.526 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.498, 3.526, 3.556), stdev = 0.029
  CI (99.9%): [2.996, 4.057] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.537 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.005 ms/op
Iteration   1: 4.197 ±(99.9%) 0.007 ms/op
Iteration   2: 4.244 ±(99.9%) 0.005 ms/op
Iteration   3: 4.219 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.220 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (4.197, 4.220, 4.244), stdev = 0.023
  CI (99.9%): [3.794, 4.647] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.464 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.010 ms/op
Iteration   1: 3.626 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  17.227 ms/op
                 createUser·p0.9999: 22.149 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.508 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  7.635 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.516 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.751 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270407
  mean =      3.549 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4177 
    [ 2.500,  5.000) = 261123 
    [ 5.000,  7.500) = 4283 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     14.427 ms/op
     p(99.9900) =     22.640 ms/op
     p(99.9990) =     24.266 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.008 ms/op
Iteration   1: 3.541 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  13.147 ms/op
                 existUser·p0.9999: 21.952 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.428 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  17.687 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  18.903 ms/op
                 existUser·p0.9999: 23.224 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276816
  mean =      3.467 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7364 
    [ 2.500,  5.000) = 263369 
    [ 5.000,  7.500) = 4923 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     13.782 ms/op
     p(99.9900) =     22.031 ms/op
     p(99.9990) =     23.623 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.349 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.012 ms/op
Iteration   1: 3.634 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  19.104 ms/op
                 getUser·p0.9999: 32.356 ms/op
                 getUser·p1.00:   35.717 ms/op

Iteration   2: 3.534 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.576 ms/op
                 getUser·p0.999:  16.918 ms/op
                 getUser·p0.9999: 24.632 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269775
  mean =      3.554 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5309 
    [ 2.500,  5.000) = 255986 
    [ 5.000,  7.500) = 6450 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     31.755 ms/op
     p(99.9990) =     33.540 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 11.297 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.012 ms/op
Iteration   1: 4.236 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 29.434 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 4.208 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.367 ms/op
                 listUser·p0.999:  16.132 ms/op
                 listUser·p0.9999: 18.376 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 4.251 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.841 ms/op
                 listUser·p0.9999: 15.605 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226785
  mean =      4.232 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 212913 
    [ 5.000,  7.500) = 11652 
    [ 7.500, 10.000) = 1403 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.001 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     28.257 ms/op
     p(99.9990) =     30.269 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.005 ± 1.443  ops/ms
ClientPb.existUser                       thrpt       3   9.434 ± 1.288  ops/ms
ClientPb.getUser                         thrpt       3   8.901 ± 2.017  ops/ms
ClientPb.listUser                        thrpt       3   7.544 ± 1.244  ops/ms
ClientPb.createUser                       avgt       3   3.529 ± 1.989   ms/op
ClientPb.existUser                        avgt       3   3.451 ± 0.779   ms/op
ClientPb.getUser                          avgt       3   3.526 ± 0.531   ms/op
ClientPb.listUser                         avgt       3   4.220 ± 0.426   ms/op
ClientPb.createUser                     sample  270407   3.549 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.427           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.640           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.707           ms/op
ClientPb.existUser                      sample  276816   3.467 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.376           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.782           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.031           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.281           ms/op
ClientPb.getUser                        sample  269775   3.554 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.045           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.755           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.717           ms/op
ClientPb.listUser                       sample  226785   4.232 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.001           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
