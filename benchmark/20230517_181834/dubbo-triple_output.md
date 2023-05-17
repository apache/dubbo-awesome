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
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 5.648 ops/ms
# Warmup Iteration   3: 8.795 ops/ms
Iteration   1: 9.616 ops/ms
Iteration   2: 9.733 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.607 ±(99.9%) 2.389 ops/ms [Average]
  (min, avg, max) = (9.472, 9.607, 9.733), stdev = 0.131
  CI (99.9%): [7.218, 11.996] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ops/ms
# Warmup Iteration   2: 8.734 ops/ms
# Warmup Iteration   3: 10.234 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.255 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.193 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (10.125, 10.193, 10.255), stdev = 0.065
  CI (99.9%): [9.011, 11.375] (assumes normal distribution)


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
# Warmup Iteration   1: 3.307 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 9.772 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.931 ±(99.9%) 3.027 ops/ms [Average]
  (min, avg, max) = (9.744, 9.931, 10.060), stdev = 0.166
  CI (99.9%): [6.903, 12.958] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ops/ms
# Warmup Iteration   2: 7.549 ops/ms
# Warmup Iteration   3: 8.310 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.339 ±(99.9%) 3.244 ops/ms [Average]
  (min, avg, max) = (8.139, 8.339, 8.479), stdev = 0.178
  CI (99.9%): [5.094, 11.583] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.005 ms/op
Iteration   1: 3.229 ±(99.9%) 0.004 ms/op
Iteration   2: 3.244 ±(99.9%) 0.002 ms/op
Iteration   3: 3.335 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (3.229, 3.269, 3.335), stdev = 0.057
  CI (99.9%): [2.221, 4.318] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.005 ms/op
Iteration   1: 3.172 ±(99.9%) 0.005 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.144 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.079, 3.131, 3.172), stdev = 0.048
  CI (99.9%): [2.259, 4.004] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.193 ±(99.9%) 0.006 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.251 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.180, 3.208, 3.251), stdev = 0.038
  CI (99.9%): [2.519, 3.897] (assumes normal distribution)


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
# Warmup Iteration   1: 10.114 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.004 ms/op
Iteration   1: 4.006 ±(99.9%) 0.004 ms/op
Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
Iteration   3: 3.801 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.870 ±(99.9%) 2.154 ms/op [Average]
  (min, avg, max) = (3.801, 3.870, 4.006), stdev = 0.118
  CI (99.9%): [1.715, 6.024] (assumes normal distribution)


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
# Warmup Iteration   1: 8.622 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
Iteration   1: 3.263 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  17.650 ms/op
                 createUser·p0.9999: 26.986 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   2: 3.223 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  12.405 ms/op
                 createUser·p0.9999: 23.399 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 3.193 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  20.737 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297470
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10469 
    [ 2.500,  5.000) = 281023 
    [ 5.000,  7.500) = 4870 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     27.845 ms/op
     p(99.9990) =     29.517 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 7.846 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.289 ms/op
                 existUser·p0.999:  13.213 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 22.388 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  15.346 ms/op
                 existUser·p0.9999: 24.323 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301864
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28225 
    [ 2.500,  5.000) = 268658 
    [ 5.000,  7.500) = 4088 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     13.273 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     25.361 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 8.378 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.336 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  20.487 ms/op
                 getUser·p0.9999: 24.065 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.335 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.369 ms/op
                 getUser·p0.999:  21.926 ms/op
                 getUser·p0.9999: 25.357 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.625 ms/op
                 getUser·p0.999:  16.302 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291383
  mean =      3.292 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20192 
    [ 2.500,  5.000) = 263133 
    [ 5.000,  7.500) = 6822 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 166 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     24.801 ms/op
     p(99.9990) =     28.153 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 9.788 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
Iteration   1: 3.902 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 25.834 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   2: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.969 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 21.679 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.076 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 20.944 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251685
  mean =      3.812 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 244116 
    [ 5.000,  7.500) = 5192 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     25.128 ms/op
     p(99.9990) =     26.959 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.607 ± 2.389  ops/ms
ClientPb.existUser                       thrpt       3  10.193 ± 1.182  ops/ms
ClientPb.getUser                         thrpt       3   9.931 ± 3.027  ops/ms
ClientPb.listUser                        thrpt       3   8.339 ± 3.244  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 1.048   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 0.872   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 0.689   ms/op
ClientPb.listUser                         avgt       3   3.870 ± 2.154   ms/op
ClientPb.createUser                     sample  297470   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.231           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.382           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.309           ms/op
ClientPb.existUser                      sample  301864   3.179 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.273           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.495           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  291383   3.292 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.728           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.801           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  251685   3.812 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.662           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.128           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.115           ms/op
