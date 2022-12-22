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
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 5.401 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 9.286 ops/ms
Iteration   2: 9.404 ops/ms
Iteration   3: 9.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.369 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (9.286, 9.369, 9.416), stdev = 0.072
  CI (99.9%): [8.055, 10.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 8.807 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 9.667 ops/ms
Iteration   2: 9.632 ops/ms
Iteration   3: 9.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.713 ±(99.9%) 2.032 ops/ms [Average]
  (min, avg, max) = (9.632, 9.713, 9.840), stdev = 0.111
  CI (99.9%): [7.681, 11.745] (assumes normal distribution)


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
# Warmup Iteration   1: 3.385 ops/ms
# Warmup Iteration   2: 8.295 ops/ms
# Warmup Iteration   3: 8.380 ops/ms
Iteration   1: 9.116 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.233 ±(99.9%) 1.942 ops/ms [Average]
  (min, avg, max) = (9.116, 9.233, 9.325), stdev = 0.106
  CI (99.9%): [7.291, 11.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 7.308 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 8.132 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.031 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (7.957, 8.031, 8.132), stdev = 0.091
  CI (99.9%): [6.379, 9.684] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.242 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
Iteration   1: 3.391 ±(99.9%) 0.013 ms/op
Iteration   2: 3.410 ±(99.9%) 0.011 ms/op
Iteration   3: 3.327 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.376 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.327, 3.376, 3.410), stdev = 0.044
  CI (99.9%): [2.580, 4.172] (assumes normal distribution)


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
# Warmup Iteration   1: 7.830 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.004 ms/op
Iteration   1: 3.229 ±(99.9%) 0.011 ms/op
Iteration   2: 3.314 ±(99.9%) 0.007 ms/op
Iteration   3: 3.322 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.229, 3.288, 3.322), stdev = 0.051
  CI (99.9%): [2.351, 4.226] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.451 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.005 ms/op
Iteration   1: 3.526 ±(99.9%) 0.008 ms/op
Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
Iteration   3: 3.542 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.440, 3.502, 3.542), stdev = 0.055
  CI (99.9%): [2.503, 4.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.539 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.008 ms/op
Iteration   1: 3.969 ±(99.9%) 0.017 ms/op
Iteration   2: 4.078 ±(99.9%) 0.010 ms/op
Iteration   3: 3.982 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.010 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.969, 4.010, 4.078), stdev = 0.060
  CI (99.9%): [2.919, 5.100] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.662 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.011 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  20.902 ms/op
                 createUser·p0.9999: 27.157 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   2: 3.487 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  23.859 ms/op
                 createUser·p0.9999: 29.532 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  18.515 ms/op
                 createUser·p0.9999: 26.572 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273957
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4779 
    [ 2.500,  5.000) = 260626 
    [ 5.000,  7.500) = 7462 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.286 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.160 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
Iteration   1: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.596 ms/op
                 existUser·p0.999:  21.399 ms/op
                 existUser·p0.9999: 25.023 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 29.809 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284334
  mean =      3.373 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9020 
    [ 2.500,  5.000) = 267738 
    [ 5.000,  7.500) = 6421 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     12.921 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     30.119 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.044 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.009 ms/op
Iteration   1: 3.536 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.057 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  18.807 ms/op
                 getUser·p0.9999: 61.601 ms/op
                 getUser·p1.00:   63.373 ms/op

Iteration   2: 3.495 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  22.333 ms/op
                 getUser·p0.9999: 33.325 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.183 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  19.442 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272622
  mean =      3.516 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264193 
    [ 5.000, 10.000) = 7953 
    [10.000, 15.000) = 136 
    [15.000, 20.000) = 77 
    [20.000, 25.000) = 155 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     19.391 ms/op
     p(99.9900) =     33.520 ms/op
     p(99.9990) =     63.111 ms/op
     p(99.9999) =     63.373 ms/op
    p(100.0000) =     63.373 ms/op


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
# Warmup Iteration   1: 10.751 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.013 ms/op
Iteration   1: 4.243 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  22.043 ms/op
                 listUser·p0.9999: 31.523 ms/op
                 listUser·p1.00:   32.244 ms/op

Iteration   2: 4.191 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  16.066 ms/op
                 listUser·p0.9999: 24.197 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 4.228 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  17.152 ms/op
                 listUser·p0.9999: 21.590 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227076
  mean =      4.221 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 215126 
    [ 5.000,  7.500) = 8602 
    [ 7.500, 10.000) = 2253 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     17.985 ms/op
     p(99.9900) =     30.331 ms/op
     p(99.9990) =     32.169 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.369 ± 1.314  ops/ms
ClientPb.existUser                       thrpt       3   9.713 ± 2.032  ops/ms
ClientPb.getUser                         thrpt       3   9.233 ± 1.942  ops/ms
ClientPb.listUser                        thrpt       3   8.031 ± 1.652  ops/ms
ClientPb.createUser                       avgt       3   3.376 ± 0.796   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 0.938   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 1.000   ms/op
ClientPb.listUser                         avgt       3   4.010 ± 1.090   ms/op
ClientPb.createUser                     sample  273957   3.508 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  284334   3.373 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.923           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.921           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.525           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  272622   3.516 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.532           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.391           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.520           ms/op
ClientPb.getUser:getUser·p1.00          sample          63.373           ms/op
ClientPb.listUser                       sample  227076   4.221 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.985           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.244           ms/op
