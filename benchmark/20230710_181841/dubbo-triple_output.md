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
# Warmup Iteration   1: 2.015 ops/ms
# Warmup Iteration   2: 5.587 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 9.401 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.304 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (9.198, 9.304, 9.401), stdev = 0.102
  CI (99.9%): [7.445, 11.162] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 8.608 ops/ms
# Warmup Iteration   3: 9.356 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.784 ops/ms
Iteration   3: 9.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.512 ±(99.9%) 4.305 ops/ms [Average]
  (min, avg, max) = (9.367, 9.512, 9.784), stdev = 0.236
  CI (99.9%): [5.208, 13.817] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.052 ops/ms
Iteration   1: 9.389 ops/ms
Iteration   2: 9.343 ops/ms
Iteration   3: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.335 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (9.273, 9.335, 9.389), stdev = 0.058
  CI (99.9%): [8.272, 10.399] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
# Warmup Iteration   2: 6.964 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.817 ±(99.9%) 4.877 ops/ms [Average]
  (min, avg, max) = (7.613, 7.817, 8.120), stdev = 0.267
  CI (99.9%): [2.940, 12.695] (assumes normal distribution)


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
# Warmup Iteration   1: 10.366 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.006 ms/op
Iteration   1: 3.508 ±(99.9%) 0.006 ms/op
Iteration   2: 3.518 ±(99.9%) 0.007 ms/op
Iteration   3: 3.566 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.531 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.508, 3.531, 3.566), stdev = 0.031
  CI (99.9%): [2.969, 4.093] (assumes normal distribution)


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
# Warmup Iteration   1: 8.853 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.005 ms/op
Iteration   1: 3.228 ±(99.9%) 0.003 ms/op
Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
Iteration   3: 3.276 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.248 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.228, 3.248, 3.276), stdev = 0.025
  CI (99.9%): [2.788, 3.707] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.638 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.006 ms/op
Iteration   1: 3.394 ±(99.9%) 0.006 ms/op
Iteration   2: 3.336 ±(99.9%) 0.008 ms/op
Iteration   3: 3.375 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.369 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.336, 3.369, 3.394), stdev = 0.029
  CI (99.9%): [2.832, 3.905] (assumes normal distribution)


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
# Warmup Iteration   1: 10.832 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.010 ms/op
Iteration   1: 4.004 ±(99.9%) 0.007 ms/op
Iteration   2: 3.980 ±(99.9%) 0.006 ms/op
Iteration   3: 3.940 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.975 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (3.940, 3.975, 4.004), stdev = 0.032
  CI (99.9%): [3.386, 4.564] (assumes normal distribution)


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
# Warmup Iteration   1: 9.348 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.009 ms/op
Iteration   1: 3.349 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  19.920 ms/op
                 createUser·p0.9999: 23.247 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.528 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  22.034 ms/op
                 createUser·p0.9999: 25.418 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  16.302 ms/op
                 createUser·p0.9999: 28.102 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280049
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9658 
    [ 2.500,  5.000) = 264538 
    [ 5.000,  7.500) = 4885 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     17.200 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     29.111 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 8.747 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  10.363 ms/op
                 existUser·p0.9999: 22.553 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.597 ms/op
                 existUser·p0.999:  21.603 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  13.516 ms/op
                 existUser·p0.9999: 26.837 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287123
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13243 
    [ 2.500,  5.000) = 269160 
    [ 5.000,  7.500) = 3691 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     13.515 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     26.977 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 8.357 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.014 ms/op
Iteration   1: 3.566 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.130 ms/op
                 getUser·p0.999:  10.393 ms/op
                 getUser·p0.9999: 23.496 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  21.292 ms/op
                 getUser·p0.9999: 26.104 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  23.459 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277022
  mean =      3.464 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7028 
    [ 2.500,  5.000) = 262695 
    [ 5.000,  7.500) = 6448 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     26.486 ms/op
     p(99.9990) =     28.432 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 9.704 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.013 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  18.048 ms/op
                 listUser·p0.9999: 23.173 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 4.188 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  14.739 ms/op
                 listUser·p0.9999: 20.918 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232962
  mean =      4.122 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 221422 
    [ 5.000,  7.500) = 9260 
    [ 7.500, 10.000) = 1399 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 354 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.304 ± 1.858  ops/ms
ClientPb.existUser                       thrpt       3   9.512 ± 4.305  ops/ms
ClientPb.getUser                         thrpt       3   9.335 ± 1.064  ops/ms
ClientPb.listUser                        thrpt       3   7.817 ± 4.877  ops/ms
ClientPb.createUser                       avgt       3   3.531 ± 0.562   ms/op
ClientPb.existUser                        avgt       3   3.248 ± 0.460   ms/op
ClientPb.getUser                          avgt       3   3.369 ± 0.537   ms/op
ClientPb.listUser                         avgt       3   3.975 ± 0.589   ms/op
ClientPb.createUser                     sample  280049   3.427 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.374           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.200           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.903           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  287123   3.342 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.515           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197           ms/op
ClientPb.getUser                        sample  277022   3.464 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.107           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.486           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  232962   4.122 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
