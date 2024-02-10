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
# Warmup Iteration   1: 5.521 ops/ms
# Warmup Iteration   2: 12.155 ops/ms
# Warmup Iteration   3: 12.415 ops/ms
Iteration   1: 12.694 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.770 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (12.694, 12.770, 12.891), stdev = 0.106
  CI (99.9%): [10.841, 14.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ops/ms
# Warmup Iteration   2: 13.517 ops/ms
# Warmup Iteration   3: 13.283 ops/ms
Iteration   1: 13.292 ops/ms
Iteration   2: 13.379 ops/ms
Iteration   3: 13.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.372 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (13.292, 13.372, 13.444), stdev = 0.076
  CI (99.9%): [11.979, 14.764] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ops/ms
# Warmup Iteration   2: 12.915 ops/ms
# Warmup Iteration   3: 13.209 ops/ms
Iteration   1: 13.220 ops/ms
Iteration   2: 13.167 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.211 ±(99.9%) 0.746 ops/ms [Average]
  (min, avg, max) = (13.167, 13.211, 13.247), stdev = 0.041
  CI (99.9%): [12.465, 13.958] (assumes normal distribution)


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
# Warmup Iteration   1: 6.800 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 10.736 ops/ms
Iteration   1: 10.879 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.893 ±(99.9%) 1.778 ops/ms [Average]
  (min, avg, max) = (10.803, 10.893, 10.996), stdev = 0.097
  CI (99.9%): [9.115, 12.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.464, 2.478, 2.497), stdev = 0.017
  CI (99.9%): [2.167, 2.789] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.402 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.396 ±(99.9%) 0.003 ms/op
Iteration   1: 2.408 ±(99.9%) 0.004 ms/op
Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
Iteration   3: 2.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.399 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.393, 2.399, 2.408), stdev = 0.008
  CI (99.9%): [2.254, 2.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.445 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.436, 2.445, 2.461), stdev = 0.014
  CI (99.9%): [2.182, 2.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
Iteration   2: 2.929 ±(99.9%) 0.005 ms/op
Iteration   3: 2.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.944 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.929, 2.944, 2.962), stdev = 0.016
  CI (99.9%): [2.645, 3.243] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.412 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  10.647 ms/op
                 createUser·p0.9999: 13.316 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   3.562 ms/op
                 createUser·p0.999:  7.831 ms/op
                 createUser·p0.9999: 12.299 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.470 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.769 ms/op
                 createUser·p0.999:  7.599 ms/op
                 createUser·p0.9999: 10.247 ms/op
                 createUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394941
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 199332 
    [ 2.500,  3.750) = 192414 
    [ 3.750,  5.000) = 2394 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      8.340 ms/op
     p(99.9900) =     12.919 ms/op
     p(99.9990) =     13.555 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.615 ms/op
                 existUser·p0.9999: 13.364 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.330 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.822 ms/op
                 existUser·p0.95:   2.925 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  7.281 ms/op
                 existUser·p0.9999: 12.612 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.372 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.285 ms/op
                 existUser·p0.9999: 11.838 ms/op
                 existUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405561
  mean =      2.365 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 211105 
    [ 2.500,  3.750) = 191347 
    [ 3.750,  5.000) = 2337 
    [ 5.000,  6.250) = 250 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.775 ms/op
     p(99.9900) =     12.901 ms/op
     p(99.9990) =     13.565 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  5.763 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  6.406 ms/op
                 getUser·p0.9999: 11.534 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  6.229 ms/op
                 getUser·p0.9999: 10.863 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392326
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 199805 
    [ 2.500,  3.750) = 188439 
    [ 3.750,  5.000) = 3202 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.382 ms/op
     p(99.9900) =     13.071 ms/op
     p(99.9990) =     14.109 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 10.785 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.094 ms/op
                 listUser·p0.9999: 11.682 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  8.826 ms/op
                 listUser·p0.9999: 10.593 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322831
  mean =      2.971 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 101342 
    [ 2.500,  3.750) = 184810 
    [ 3.750,  5.000) = 29806 
    [ 5.000,  6.250) = 5479 
    [ 6.250,  7.500) = 552 
    [ 7.500,  8.750) = 277 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.527 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     11.148 ms/op
     p(99.9990) =     12.069 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.770 ± 1.929  ops/ms
ClientPb.existUser                       thrpt       3  13.372 ± 1.393  ops/ms
ClientPb.getUser                         thrpt       3  13.211 ± 0.746  ops/ms
ClientPb.listUser                        thrpt       3  10.893 ± 1.778  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.399 ± 0.146   ms/op
ClientPb.getUser                          avgt       3   2.445 ± 0.263   ms/op
ClientPb.listUser                         avgt       3   2.944 ± 0.299   ms/op
ClientPb.createUser                     sample  394941   2.427 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.823           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.482           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.340           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.919           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.861           ms/op
ClientPb.existUser                      sample  405561   2.365 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.521           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.775           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.901           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  392326   2.445 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.641           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.382           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.071           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.533           ms/op
ClientPb.listUser                       sample  322831   2.971 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.527           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.148           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.239           ms/op
