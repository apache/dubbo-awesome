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
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 11.650 ops/ms
# Warmup Iteration   3: 12.469 ops/ms
Iteration   1: 12.508 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (12.508, 12.648, 12.757), stdev = 0.127
  CI (99.9%): [10.326, 14.970] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.700 ops/ms
# Warmup Iteration   2: 12.715 ops/ms
# Warmup Iteration   3: 12.997 ops/ms
Iteration   1: 12.899 ops/ms
Iteration   2: 12.975 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.926 ±(99.9%) 0.777 ops/ms [Average]
  (min, avg, max) = (12.899, 12.926, 12.975), stdev = 0.043
  CI (99.9%): [12.149, 13.703] (assumes normal distribution)


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
# Warmup Iteration   1: 7.585 ops/ms
# Warmup Iteration   2: 12.195 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.533 ops/ms
Iteration   2: 12.576 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.549 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (12.533, 12.549, 12.576), stdev = 0.023
  CI (99.9%): [12.123, 12.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ops/ms
# Warmup Iteration   2: 10.354 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.529 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (10.484, 10.529, 10.618), stdev = 0.077
  CI (99.9%): [9.127, 11.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.574 ±(99.9%) 0.005 ms/op
Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.576 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.558, 2.576, 2.596), stdev = 0.019
  CI (99.9%): [2.222, 2.930] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
Iteration   2: 2.407 ±(99.9%) 0.011 ms/op
Iteration   3: 2.386 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.405 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (2.386, 2.405, 2.422), stdev = 0.018
  CI (99.9%): [2.075, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.008 ms/op
Iteration   1: 2.507 ±(99.9%) 0.008 ms/op
Iteration   2: 2.481 ±(99.9%) 0.007 ms/op
Iteration   3: 2.498 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.481, 2.495, 2.507), stdev = 0.013
  CI (99.9%): [2.254, 2.736] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
Iteration   3: 3.056 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.042, 3.047, 3.056), stdev = 0.008
  CI (99.9%): [2.910, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.489 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.641 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 15.565 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   3.195 ms/op
                 createUser·p0.95:   3.461 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.462 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.424 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  9.009 ms/op
                 createUser·p0.9999: 12.359 ms/op
                 createUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373149
  mean =      2.571 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 184936 
    [ 2.500,  3.750) = 177580 
    [ 3.750,  5.000) = 9284 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     15.073 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.006 ms/op
Iteration   1: 2.432 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.686 ms/op
                 existUser·p0.9999: 16.040 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 2.425 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.339 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  9.399 ms/op
                 existUser·p0.9999: 17.236 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 2.472 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.362 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.120 ms/op
                 existUser·p0.999:  9.312 ms/op
                 existUser·p0.9999: 12.666 ms/op
                 existUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392553
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 244 
    [ 1.250,  2.500) = 215401 
    [ 2.500,  3.750) = 169166 
    [ 3.750,  5.000) = 6401 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      2.396 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      9.344 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     18.025 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.007 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  12.713 ms/op
                 getUser·p0.9999: 14.632 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 15.679 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.496 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   3.158 ms/op
                 getUser·p0.95:   3.465 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.174 ms/op
                 getUser·p0.9999: 12.132 ms/op
                 getUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380022
  mean =      2.524 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 192837 
    [ 2.500,  3.750) = 176203 
    [ 3.750,  5.000) = 9277 
    [ 5.000,  6.250) = 869 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.428 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.813 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     15.873 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.009 ms/op
Iteration   1: 2.965 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.645 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.736 ms/op
                 listUser·p0.999:  10.453 ms/op
                 listUser·p0.9999: 16.833 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 12.281 ms/op
                 listUser·p1.00:   13.222 ms/op

Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.584 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.987 ms/op
                 listUser·p0.9999: 12.808 ms/op
                 listUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323174
  mean =      2.966 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107091 
    [ 2.500,  5.000) = 209166 
    [ 5.000,  7.500) = 6137 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     12.764 ms/op
     p(99.9990) =     18.571 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 2.322  ops/ms
ClientPb.existUser                       thrpt       3  12.926 ± 0.777  ops/ms
ClientPb.getUser                         thrpt       3  12.549 ± 0.426  ops/ms
ClientPb.listUser                        thrpt       3  10.529 ± 1.403  ops/ms
ClientPb.createUser                       avgt       3   2.576 ± 0.354   ms/op
ClientPb.existUser                        avgt       3   2.405 ± 0.330   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.241   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.137   ms/op
ClientPb.createUser                     sample  373149   2.571 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.713           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.814           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.073           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  392553   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.396           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.182           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.344           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.138           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.121           ms/op
ClientPb.getUser                        sample  380022   2.524 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.496           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.813           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.713           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.302           ms/op
ClientPb.listUser                       sample  323174   2.966 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.584           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.764           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
