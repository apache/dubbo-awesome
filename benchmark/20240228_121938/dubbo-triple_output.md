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
# Warmup Iteration   1: 4.247 ops/ms
# Warmup Iteration   2: 12.248 ops/ms
# Warmup Iteration   3: 12.503 ops/ms
Iteration   1: 12.513 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.696 ±(99.9%) 2.903 ops/ms [Average]
  (min, avg, max) = (12.513, 12.696, 12.794), stdev = 0.159
  CI (99.9%): [9.794, 15.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ops/ms
# Warmup Iteration   2: 13.473 ops/ms
# Warmup Iteration   3: 13.488 ops/ms
Iteration   1: 13.489 ops/ms
Iteration   2: 13.471 ops/ms
Iteration   3: 13.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.454 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (13.401, 13.454, 13.489), stdev = 0.046
  CI (99.9%): [12.612, 14.295] (assumes normal distribution)


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
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 13.015 ops/ms
# Warmup Iteration   3: 13.104 ops/ms
Iteration   1: 13.113 ops/ms
Iteration   2: 13.228 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.082 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (12.904, 13.082, 13.228), stdev = 0.165
  CI (99.9%): [10.078, 16.085] (assumes normal distribution)


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
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 10.875 ops/ms
Iteration   3: 10.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.907 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (10.875, 10.907, 10.937), stdev = 0.031
  CI (99.9%): [10.339, 11.476] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.451 ±(99.9%) 0.003 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.434 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.411, 2.434, 2.451), stdev = 0.020
  CI (99.9%): [2.063, 2.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.404 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.371 ±(99.9%) 0.004 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
Iteration   2: 2.387 ±(99.9%) 0.003 ms/op
Iteration   3: 2.395 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.387, 2.395, 2.405), stdev = 0.009
  CI (99.9%): [2.233, 2.558] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.389 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.416 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.389, 2.416, 2.445), stdev = 0.028
  CI (99.9%): [1.911, 2.921] (assumes normal distribution)


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
Iteration   3: 2.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.956, 2.977, 2.989), stdev = 0.018
  CI (99.9%): [2.648, 3.306] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  6.011 ms/op
                 createUser·p0.9999: 13.924 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  10.119 ms/op
                 createUser·p0.9999: 12.485 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.861 ms/op
                 createUser·p0.9999: 11.141 ms/op
                 createUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389674
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 191850 
    [ 2.500,  3.750) = 194110 
    [ 3.750,  5.000) = 2820 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      9.262 ms/op
     p(99.9900) =     13.043 ms/op
     p(99.9990) =     14.489 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.627 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.354 ±(99.9%) 0.005 ms/op
Iteration   1: 2.379 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.396 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  5.579 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.497 ms/op
                 existUser·p0.9999: 14.822 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  6.848 ms/op
                 existUser·p0.9999: 11.626 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399884
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 209372 
    [ 2.500,  3.750) = 186825 
    [ 3.750,  5.000) = 2862 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.922 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      5.882 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.402 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.865 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  6.575 ms/op
                 getUser·p0.9999: 11.797 ms/op
                 getUser·p1.00:   12.239 ms/op

Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  5.382 ms/op
                 getUser·p0.9999: 10.682 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 397753
  mean =      2.411 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 207378 
    [ 2.500,  3.750) = 186304 
    [ 3.750,  5.000) = 3260 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      6.048 ms/op
     p(99.9900) =     13.176 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.009 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 11.424 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.693 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320480
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 93037 
    [ 2.500,  3.750) = 189923 
    [ 3.750,  5.000) = 30963 
    [ 5.000,  6.250) = 5152 
    [ 6.250,  7.500) = 662 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     11.941 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.696 ± 2.903  ops/ms
ClientPb.existUser                       thrpt       3  13.454 ± 0.842  ops/ms
ClientPb.getUser                         thrpt       3  13.082 ± 3.003  ops/ms
ClientPb.listUser                        thrpt       3  10.907 ± 0.568  ops/ms
ClientPb.createUser                       avgt       3   2.434 ± 0.371   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   2.416 ± 0.505   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.329   ms/op
ClientPb.createUser                     sample  389674   2.461 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.921           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.262           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.043           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.221           ms/op
ClientPb.existUser                      sample  399884   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.804           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.882           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.483           ms/op
ClientPb.getUser                        sample  397753   2.411 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.813           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.433           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.937           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.467           ms/op
ClientPb.listUser                       sample  320480   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.108           ms/op
