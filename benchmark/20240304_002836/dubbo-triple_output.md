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
# Warmup Iteration   1: 4.983 ops/ms
# Warmup Iteration   2: 11.964 ops/ms
# Warmup Iteration   3: 12.524 ops/ms
Iteration   1: 12.719 ops/ms
Iteration   2: 12.813 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.819 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (12.719, 12.819, 12.926), stdev = 0.104
  CI (99.9%): [10.929, 14.709] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.021 ops/ms
# Warmup Iteration   2: 12.953 ops/ms
# Warmup Iteration   3: 13.107 ops/ms
Iteration   1: 13.056 ops/ms
Iteration   2: 13.089 ops/ms
Iteration   3: 13.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.062 ±(99.9%) 0.444 ops/ms [Average]
  (min, avg, max) = (13.042, 13.062, 13.089), stdev = 0.024
  CI (99.9%): [12.618, 13.506] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.160 ops/ms
# Warmup Iteration   2: 12.905 ops/ms
# Warmup Iteration   3: 13.098 ops/ms
Iteration   1: 13.128 ops/ms
Iteration   2: 13.014 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.027 ±(99.9%) 1.756 ops/ms [Average]
  (min, avg, max) = (12.937, 13.027, 13.128), stdev = 0.096
  CI (99.9%): [11.271, 14.782] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.413 ops/ms
# Warmup Iteration   2: 10.362 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.659 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (10.597, 10.659, 10.716), stdev = 0.059
  CI (99.9%): [9.575, 11.742] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.432 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.421, 2.432, 2.450), stdev = 0.016
  CI (99.9%): [2.138, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.004 ms/op
Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.413 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.397, 2.413, 2.431), stdev = 0.017
  CI (99.9%): [2.104, 2.721] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.466 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.443, 2.466, 2.479), stdev = 0.020
  CI (99.9%): [2.098, 2.834] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.773 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.993 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.967, 2.993, 3.006), stdev = 0.022
  CI (99.9%): [2.586, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  6.487 ms/op
                 createUser·p0.9999: 14.508 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  7.423 ms/op
                 createUser·p0.9999: 11.841 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 12.030 ms/op
                 createUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391543
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 194585 
    [ 2.500,  3.750) = 192427 
    [ 3.750,  5.000) = 3247 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.658 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     15.027 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  5.606 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.048 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.638 ms/op
                 existUser·p0.9999: 10.385 ms/op
                 existUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393987
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 197898 
    [ 2.500,  3.750) = 192572 
    [ 3.750,  5.000) = 2731 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     13.438 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.457 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  7.528 ms/op
                 getUser·p0.9999: 20.807 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.502 ms/op
                 getUser·p0.50:   2.492 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.581 ms/op
                 getUser·p0.9999: 12.098 ms/op
                 getUser·p1.00:   12.517 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  5.939 ms/op
                 getUser·p0.9999: 11.693 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390708
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 197683 
    [ 2.500,  5.000) = 191770 
    [ 5.000,  7.500) = 826 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     13.565 ms/op
     p(99.9990) =     21.401 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 12.228 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.394 ms/op
                 listUser·p0.9999: 11.065 ms/op
                 listUser·p1.00:   12.943 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.919 ms/op
                 listUser·p0.9999: 11.524 ms/op
                 listUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319710
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 96414 
    [ 2.500,  3.750) = 183180 
    [ 3.750,  5.000) = 32427 
    [ 5.000,  6.250) = 6180 
    [ 6.250,  7.500) = 688 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 199 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.442 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     12.905 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.819 ± 1.890  ops/ms
ClientPb.existUser                       thrpt       3  13.062 ± 0.444  ops/ms
ClientPb.getUser                         thrpt       3  13.027 ± 1.756  ops/ms
ClientPb.listUser                        thrpt       3  10.659 ± 1.083  ops/ms
ClientPb.createUser                       avgt       3   2.432 ± 0.294   ms/op
ClientPb.existUser                        avgt       3   2.413 ± 0.308   ms/op
ClientPb.getUser                          avgt       3   2.466 ± 0.368   ms/op
ClientPb.listUser                         avgt       3   2.993 ± 0.407   ms/op
ClientPb.createUser                     sample  391543   2.449 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.756           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.658           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.400           ms/op
ClientPb.existUser                      sample  393987   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.636           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.438           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  390708   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.502           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.897           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.725           ms/op
ClientPb.listUser                       sample  319710   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.442           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.074           ms/op
