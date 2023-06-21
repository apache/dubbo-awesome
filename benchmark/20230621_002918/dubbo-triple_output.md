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
# Warmup Iteration   1: 2.131 ops/ms
# Warmup Iteration   2: 5.318 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 8.799 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 8.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.880 ±(99.9%) 3.544 ops/ms [Average]
  (min, avg, max) = (8.738, 8.880, 9.101), stdev = 0.194
  CI (99.9%): [5.336, 12.423] (assumes normal distribution)


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
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 9.605 ops/ms
Iteration   1: 9.873 ops/ms
Iteration   2: 9.723 ops/ms
Iteration   3: 9.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.810 ±(99.9%) 1.417 ops/ms [Average]
  (min, avg, max) = (9.723, 9.810, 9.873), stdev = 0.078
  CI (99.9%): [8.393, 11.226] (assumes normal distribution)


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
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 8.335 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.352 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.257 ±(99.9%) 2.844 ops/ms [Average]
  (min, avg, max) = (9.077, 9.257, 9.352), stdev = 0.156
  CI (99.9%): [6.413, 12.101] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.772 ops/ms
# Warmup Iteration   2: 7.094 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.819 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (7.772, 7.819, 7.858), stdev = 0.043
  CI (99.9%): [7.030, 8.608] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.696 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.005 ms/op
Iteration   1: 3.383 ±(99.9%) 0.009 ms/op
Iteration   2: 3.425 ±(99.9%) 0.008 ms/op
Iteration   3: 3.349 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.385 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.349, 3.385, 3.425), stdev = 0.038
  CI (99.9%): [2.689, 4.082] (assumes normal distribution)


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
# Warmup Iteration   1: 8.400 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
Iteration   1: 3.362 ±(99.9%) 0.006 ms/op
Iteration   2: 3.223 ±(99.9%) 0.006 ms/op
Iteration   3: 3.246 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.277 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.223, 3.277, 3.362), stdev = 0.075
  CI (99.9%): [1.916, 4.638] (assumes normal distribution)


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
# Warmup Iteration   1: 10.542 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
Iteration   2: 3.567 ±(99.9%) 0.004 ms/op
Iteration   3: 3.453 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (3.380, 3.467, 3.567), stdev = 0.094
  CI (99.9%): [1.747, 5.187] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.801 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 3.932 ±(99.9%) 0.012 ms/op
Iteration   2: 3.857 ±(99.9%) 0.017 ms/op
Iteration   3: 3.848 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.879 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.848, 3.879, 3.932), stdev = 0.046
  CI (99.9%): [3.042, 4.717] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.451 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
Iteration   1: 3.465 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  22.979 ms/op
                 createUser·p0.9999: 28.009 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 3.526 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  23.871 ms/op
                 createUser·p0.9999: 30.936 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 3.609 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  24.111 ms/op
                 createUser·p0.9999: 29.533 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271726
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5434 
    [ 2.500,  5.000) = 259344 
    [ 5.000,  7.500) = 5886 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     23.635 ms/op
     p(99.9900) =     29.780 ms/op
     p(99.9990) =     32.061 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 8.692 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.188 ms/op
                 existUser·p0.999:  21.095 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  23.742 ms/op
                 existUser·p0.9999: 26.377 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 3.351 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  13.492 ms/op
                 existUser·p0.9999: 29.375 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285128
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8942 
    [ 2.500,  5.000) = 268604 
    [ 5.000,  7.500) = 6547 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 160 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     27.607 ms/op
     p(99.9990) =     30.446 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 8.829 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
Iteration   1: 3.513 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 26.862 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  22.354 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275284
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3318 
    [ 2.500,  5.000) = 262605 
    [ 5.000,  7.500) = 8228 
    [ 7.500, 10.000) = 646 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.241 ms/op
     p(99.9900) =     26.754 ms/op
     p(99.9990) =     28.514 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 10.412 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.014 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 23.778 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.060 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 17.886 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.099 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238233
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 229240 
    [ 5.000,  7.500) = 6908 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.659 ms/op
     p(99.9900) =     22.010 ms/op
     p(99.9990) =     23.843 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.880 ± 3.544  ops/ms
ClientPb.existUser                       thrpt       3   9.810 ± 1.417  ops/ms
ClientPb.getUser                         thrpt       3   9.257 ± 2.844  ops/ms
ClientPb.listUser                        thrpt       3   7.819 ± 0.789  ops/ms
ClientPb.createUser                       avgt       3   3.385 ± 0.696   ms/op
ClientPb.existUser                        avgt       3   3.277 ± 1.361   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.720   ms/op
ClientPb.listUser                         avgt       3   3.879 ± 0.838   ms/op
ClientPb.createUser                     sample  271726   3.532 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.563           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.635           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  285128   3.369 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.923           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.607           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  275284   3.486 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.386           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.754           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  238233   4.028 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.142           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.659           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
